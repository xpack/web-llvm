---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/machineirbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MachineIRBuilder` Class Reference

<p>Helper class to build <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MachineIRBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">llvm/CodeGen/GlobalISel/MachineIRBuilder.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/csemirbuilder">CSEMIRBuilder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Defines a builder that does CSE of MachineInstructions using <a href="/web-llvm/docs/api/classes/llvm/giselcseinfo">GISelCSEInfo</a>. <a href="/web-llvm/docs/api/classes/llvm/csemirbuilder/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad662a74c60eeb99f6a24927479eda063">MachineIRBuilder</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Some constructors for easy use. <a href="#ad662a74c60eeb99f6a24927479eda063">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa03c7e0eb5346e000177cb95b910cc71">MachineIRBuilder</a> (MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6149c9a2642b91bfdb471868a7f8bd1f">MachineIRBuilder</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator InsPt)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d5d8e859928cc003454a2ba18372a71">MachineIRBuilder</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d69fb9fe28f38bfe61a276caec92263">MachineIRBuilder</a> (MachineInstr &amp;MI, GISelChangeObserver &amp;Observer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa048045615f06db86c3a4e317ed3a2b3">MachineIRBuilder</a> (const MachineIRBuilderState &amp;BState)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c9f7862be40509888ddd3febc051c85">~MachineIRBuilder</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35384c47e5ca9690216b1aa8fed5a8c9">getTII</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ec04f3692b9601036d2d4477c4c3749">getMF</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Getter for the function we currently build. <a href="#a9ec04f3692b9601036d2d4477c4c3749">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e8dc93a8e1664c946eca6f60140ea29">getMF</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb6d0a9254bc3183046873436fc7c12e">getDataLayout</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a120dbb8d0a1ad4437456001a302a1da7">getContext</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93ab05c4fb48bd5e87965bef6ec9ac2e">getDL</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Getter for <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a>. <a href="#a93ab05c4fb48bd5e87965bef6ec9ac2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Getter for MRI. <a href="#ad7322f56c0659b8dc8e55567767b74d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94a2451b7b4e853eb884be8d8e3c69d9">getMRI</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/machineirbuilderstate">MachineIRBuilderState</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc500b8cc6b22cec3d3cdc03234f23b9">getState</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Getter for the State. <a href="#adc500b8cc6b22cec3d3cdc03234f23b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af66f20f7acbbf9bbb0585aeaa2dcfdbd">setState</a> (const MachineIRBuilderState &amp;NewState)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Setter for the State. <a href="#af66f20f7acbbf9bbb0585aeaa2dcfdbd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8f6c5b9180bd630c92e1126877d0b08">getMBB</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Getter for the basic block we currently build. <a href="#ac8f6c5b9180bd630c92e1126877d0b08">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7be5d9bbd5832221068ae6c93cf24d51">getMBB</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/giselcseinfo">GISelCSEInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a885e28d6a7936c7442d063aea666f6">getCSEInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/giselcseinfo">GISelCSEInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7336e3815d2fdc6dec4d59d47db6b5b9">getCSEInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a430daa77692b7b25f93a72d83e51964f">getInsertPt</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Current insertion point for new instructions. <a href="#a430daa77692b7b25f93a72d83e51964f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0df93c0f752428162e14b54f8999172d">setInsertPt</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator II)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the insertion point before the specified position. <a href="#a0df93c0f752428162e14b54f8999172d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2a55990c65a2e9965e91c74a293df22">setCSEInfo</a> (GISelCSEInfo *Info)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab24db762f0912a99f1e4d9e44eaeaa44">setInstrAndDebugLoc</a> (MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the insertion point to before MI, and set the debug loc to MI's loc. <a href="#ab24db762f0912a99f1e4d9e44eaeaa44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af69cfe118f734f35607c8fd4615ea1bf">setChangeObserver</a> (GISelChangeObserver &amp;Observer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver">GISelChangeObserver</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a035ff811981517c4885338606c70d928">getObserver</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fc63d7dce70789203fc3966a2c08243">stopObservingChanges</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac79fef5aa90485941b9c604ece34199d">isObservingChanges</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac444a61cbfb8a46d48688a530e5defe1">setDebugLoc</a> (const DebugLoc &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the debug location to <span class="doxyComputerOutput">DL</span> for all the next build instructions. <a href="#ac444a61cbfb8a46d48688a530e5defe1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfe60198abd7ecf64270c987689c6c1b">getDebugLoc</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the current instruction's debug location. <a href="#acfe60198abd7ecf64270c987689c6c1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab86e7a422665e421ea6e21cbf1902d7c">setPCSections</a> (MDNode *MD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the PC sections metadata to <span class="doxyComputerOutput">MD</span> for all the next build instructions. <a href="#ab86e7a422665e421ea6e21cbf1902d7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d965aceed7f5b45e11799d0fa0b36e3">getPCSections</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the current instruction's PC sections metadata. <a href="#a4d965aceed7f5b45e11799d0fa0b36e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2ef6f73b6f2821c0852ab1a60866a3d">setMMRAMetadata</a> (MDNode *MMRA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the PC sections metadata to <span class="doxyComputerOutput">MD</span> for all the next build instructions. <a href="#ab2ef6f73b6f2821c0852ab1a60866a3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae93b0a855cdf8afb141d16e217158683">getMMRAMetadata</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the current instruction's MMRA metadata. <a href="#ae93b0a855cdf8afb141d16e217158683">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a> (unsigned Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert &lt;empty&gt; = <span class="doxyComputerOutput">Opcode</span> &lt;empty&gt;. <a href="#a8bc92b8a902afb7675480ecc729a66d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae04499daa8807ddb4d00e7ed18b1698f">buildInstrNoInsert</a> (unsigned Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build but don't insert &lt;empty&gt; = <span class="doxyComputerOutput">Opcode</span> &lt;empty&gt;. <a href="#ae04499daa8807ddb4d00e7ed18b1698f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06dc2f24e1f4dea357bf6c646f5b2607">insertInstr</a> (MachineInstrBuilder MIB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert an existing instruction at the insertion point. <a href="#a06dc2f24e1f4dea357bf6c646f5b2607">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92bad84c9e323ab0a96d8d8bbb22d149">buildDirectDbgValue</a> (Register Reg, const MDNode *Variable, const MDNode *Expr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert a DBG_VALUE instruction expressing the fact that the associated <span class="doxyComputerOutput">Variable</span> lives in <span class="doxyComputerOutput">Reg</span> (suitably modified by <span class="doxyComputerOutput">Expr</span>). <a href="#a92bad84c9e323ab0a96d8d8bbb22d149">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a76abb6dd3946ca5c9cd6e8f341d63c">buildIndirectDbgValue</a> (Register Reg, const MDNode *Variable, const MDNode *Expr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert a DBG_VALUE instruction expressing the fact that the associated <span class="doxyComputerOutput">Variable</span> lives in memory at <span class="doxyComputerOutput">Reg</span> (suitably modified by <span class="doxyComputerOutput">Expr</span>). <a href="#a5a76abb6dd3946ca5c9cd6e8f341d63c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab107810eccfb0e46e47348ea9ef8d0ed">buildFIDbgValue</a> (int FI, const MDNode *Variable, const MDNode *Expr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert a DBG_VALUE instruction expressing the fact that the associated <span class="doxyComputerOutput">Variable</span> lives in the stack slot specified by <span class="doxyComputerOutput">FI</span> (suitably modified by <span class="doxyComputerOutput">Expr</span>). <a href="#ab107810eccfb0e46e47348ea9ef8d0ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ab34a535b1441b48a0ede2c2aa6fb98">buildConstDbgValue</a> (const Constant &amp;C, const MDNode *Variable, const MDNode *Expr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert a DBG_VALUE instructions specifying that <span class="doxyComputerOutput">Variable</span> is given by <span class="doxyComputerOutput">C</span> (suitably modified by <span class="doxyComputerOutput">Expr</span>). <a href="#a6ab34a535b1441b48a0ede2c2aa6fb98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadc416be0ccae999a06a3a9452bf8d37">buildDbgLabel</a> (const MDNode *Label)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert a DBG_LABEL instructions specifying that <span class="doxyComputerOutput">Label</span> is given. <a href="#aadc416be0ccae999a06a3a9452bf8d37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab00eba007903e9b4a69440782cd7c9c9">buildDynStackAlloc</a> (const DstOp &amp;Res, const SrcOp &amp;Size, Align Alignment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_DYN_STACKALLOC <span class="doxyComputerOutput">Size</span>, <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></span>. <a href="#ab00eba007903e9b4a69440782cd7c9c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92664cdbeb0b24030809439993ac271d">buildFrameIndex</a> (const DstOp &amp;Res, int Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FRAME_INDEX <span class="doxyComputerOutput">Idx</span>. <a href="#a92664cdbeb0b24030809439993ac271d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ac2ceaa32ba0511bb9e14e6edfbc329">buildGlobalValue</a> (const DstOp &amp;Res, const GlobalValue *GV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_GLOBAL_VALUE <span class="doxyComputerOutput">GV</span>. <a href="#a0ac2ceaa32ba0511bb9e14e6edfbc329">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1da8389b4eb951b11309c28ad492e8d4">buildConstantPool</a> (const DstOp &amp;Res, unsigned Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_CONSTANT_POOL <span class="doxyComputerOutput">Idx</span>. <a href="#a1da8389b4eb951b11309c28ad492e8d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7aae2634e3c0980c4f68983738b90ff7">buildPtrAdd</a> (const DstOp &amp;Res, const SrcOp &amp;Op0, const SrcOp &amp;Op1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_PTR_ADD <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>. <a href="#a7aae2634e3c0980c4f68983738b90ff7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f2bb4d63ad6914f3783967bf881a14b">materializePtrAdd</a> (Register &amp;Res, Register Op0, const LLT ValueTy, uint64_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Materialize and insert <span class="doxyComputerOutput">Res</span> = G_PTR_ADD <span class="doxyComputerOutput">Op0</span>, (G_CONSTANT <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span>) <a href="#a0f2bb4d63ad6914f3783967bf881a14b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1d84823ec8a6332f2e5f8572a492255">buildPtrMask</a> (const DstOp &amp;Res, const SrcOp &amp;Op0, const SrcOp &amp;Op1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_PTRMASK <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>. <a href="#ae1d84823ec8a6332f2e5f8572a492255">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6aed1d3b2cf7133b73cf8bfa5122186">buildMaskLowPtrBits</a> (const DstOp &amp;Res, const SrcOp &amp;Op0, uint32_t NumBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_PTRMASK <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">G_CONSTANT</span> (1 &lt;&lt; NumBits) - 1. <a href="#af6aed1d3b2cf7133b73cf8bfa5122186">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a901a49f9b5721ab01d9d371f96e4bcea">buildPadVectorWithUndefElements</a> (const DstOp &amp;Res, const SrcOp &amp;Op0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert a, b, ..., x = G_UNMERGE_VALUES <span class="doxyComputerOutput">Op0</span> <span class="doxyComputerOutput">Res</span> = G_BUILD_VECTOR a, b, ..., x, undef, ..., undef. <a href="#a901a49f9b5721ab01d9d371f96e4bcea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad68c3cafb2cc7ee28ee3c7dff2a45f2e">buildDeleteTrailingVectorElements</a> (const DstOp &amp;Res, const SrcOp &amp;Op0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert a, b, ..., x, y, z = G_UNMERGE_VALUES <span class="doxyComputerOutput">Op0</span> <span class="doxyComputerOutput">Res</span> = G_BUILD_VECTOR a, b, ..., x. <a href="#ad68c3cafb2cc7ee28ee3c7dff2a45f2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad01ffef0e7c1bd556a76f6ead4d7d9fb">buildUAddo</a> (const DstOp &amp;Res, const DstOp &amp;CarryOut, const SrcOp &amp;Op0, const SrcOp &amp;Op1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span>, <span class="doxyComputerOutput">CarryOut</span> = G_UADDO <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>. <a href="#ad01ffef0e7c1bd556a76f6ead4d7d9fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c12041fb9751bb3445d1da887a91e66">buildUSubo</a> (const DstOp &amp;Res, const DstOp &amp;CarryOut, const SrcOp &amp;Op0, const SrcOp &amp;Op1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span>, <span class="doxyComputerOutput">CarryOut</span> = G_USUBO <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>. <a href="#a5c12041fb9751bb3445d1da887a91e66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b6ed90b8df9e1da2212087d1f9199ba">buildSAddo</a> (const DstOp &amp;Res, const DstOp &amp;CarryOut, const SrcOp &amp;Op0, const SrcOp &amp;Op1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span>, <span class="doxyComputerOutput">CarryOut</span> = G_SADDO <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>. <a href="#a3b6ed90b8df9e1da2212087d1f9199ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7553894d44938e9e9f4016dae66b72e">buildSSubo</a> (const DstOp &amp;Res, const DstOp &amp;CarryOut, const SrcOp &amp;Op0, const SrcOp &amp;Op1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span>, <span class="doxyComputerOutput">CarryOut</span> = G_SUBO <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>. <a href="#ac7553894d44938e9e9f4016dae66b72e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfcd8132aaf36162d0ac865c74933456">buildUAdde</a> (const DstOp &amp;Res, const DstOp &amp;CarryOut, const SrcOp &amp;Op0, const SrcOp &amp;Op1, const SrcOp &amp;CarryIn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span>, <span class="doxyComputerOutput">CarryOut</span> = G_UADDE <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>, <span class="doxyComputerOutput">CarryIn</span>. <a href="#abfcd8132aaf36162d0ac865c74933456">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac80662067cf7650fa86ffb1c9cf75249">buildUSube</a> (const DstOp &amp;Res, const DstOp &amp;CarryOut, const SrcOp &amp;Op0, const SrcOp &amp;Op1, const SrcOp &amp;CarryIn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span>, <span class="doxyComputerOutput">CarryOut</span> = G_USUBE <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>, <span class="doxyComputerOutput">CarryInp</span>. <a href="#ac80662067cf7650fa86ffb1c9cf75249">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36e19c5ffd6bb0b19cd01c41104fb083">buildSAdde</a> (const DstOp &amp;Res, const DstOp &amp;CarryOut, const SrcOp &amp;Op0, const SrcOp &amp;Op1, const SrcOp &amp;CarryIn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span>, <span class="doxyComputerOutput">CarryOut</span> = G_SADDE <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>, <span class="doxyComputerOutput">CarryInp</span>. <a href="#a36e19c5ffd6bb0b19cd01c41104fb083">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3bc600ec4a43f1914fed894c9cf9fc0">buildSSube</a> (const DstOp &amp;Res, const DstOp &amp;CarryOut, const SrcOp &amp;Op0, const SrcOp &amp;Op1, const SrcOp &amp;CarryIn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span>, <span class="doxyComputerOutput">CarryOut</span> = G_SSUBE <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>, <span class="doxyComputerOutput">CarryInp</span>. <a href="#ab3bc600ec4a43f1914fed894c9cf9fc0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acac15566596b1d588d87450ab77bf0d7">buildAnyExt</a> (const DstOp &amp;Res, const SrcOp &amp;Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_ANYEXT <span class="doxyComputerOutput">Op0</span>. <a href="#acac15566596b1d588d87450ab77bf0d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42427e969917da5da61fadd006fed326">buildSExt</a> (const DstOp &amp;Res, const SrcOp &amp;Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_SEXT <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>. <a href="#a42427e969917da5da61fadd006fed326">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe73ac7a93f98c40c8fb66fce8fa4400">buildSExtInReg</a> (const DstOp &amp;Res, const SrcOp &amp;Op, int64_t ImmOp)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_SEXT_INREG <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>, ImmOp. <a href="#afe73ac7a93f98c40c8fb66fce8fa4400">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14b6de2cb8956f133042a43a1f888efe">buildFPExt</a> (const DstOp &amp;Res, const SrcOp &amp;Op, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FPEXT <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>. <a href="#a14b6de2cb8956f133042a43a1f888efe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd3920e024c9e79df5fd07b03c64d314">buildPtrToInt</a> (const DstOp &amp;Dst, const SrcOp &amp;Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert a G_PTRTOINT instruction. <a href="#afd3920e024c9e79df5fd07b03c64d314">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5986a45c021d42bcc2f1563aa25c4cc8">buildIntToPtr</a> (const DstOp &amp;Dst, const SrcOp &amp;Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert a G_INTTOPTR instruction. <a href="#a5986a45c021d42bcc2f1563aa25c4cc8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf0f51041fbaaed06a39f2fe2686bb92">buildBitcast</a> (const DstOp &amp;Dst, const SrcOp &amp;Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_BITCAST <span class="doxyComputerOutput">Src</span>. <a href="#acf0f51041fbaaed06a39f2fe2686bb92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a534266d65ce335e1d212f37fc554dbb4">buildAddrSpaceCast</a> (const DstOp &amp;Dst, const SrcOp &amp;Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_ADDRSPACE_CAST <span class="doxyComputerOutput">Src</span>. <a href="#a534266d65ce335e1d212f37fc554dbb4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5aafc4bc2c28b6cb5d9aeb319b186d11">getBoolExtOp</a> (bool IsVec, bool IsFP) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e5b88856596e413494661b5fae9fc39">buildBoolExt</a> (const DstOp &amp;Res, const SrcOp &amp;Op, bool IsFP)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a060616c6385361df8bd72cde315d4267">buildBoolExtInReg</a> (const DstOp &amp;Res, const SrcOp &amp;Op, bool IsVector, bool IsFP)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44a49b5f4dd2932058e3fbe21c098655">buildZExt</a> (const DstOp &amp;Res, const SrcOp &amp;Op, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_ZEXT <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>. <a href="#a44a49b5f4dd2932058e3fbe21c098655">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a437e7190e38ee7e10daee0f4909d5066">buildSExtOrTrunc</a> (const DstOp &amp;Res, const SrcOp &amp;Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_SEXT <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>, <span class="doxyComputerOutput">Res</span> = G_TRUNC <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>, or <span class="doxyComputerOutput">Res</span> = COPY <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> depending on the differing sizes of <span class="doxyComputerOutput">Res</span> and <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>. <a href="#a437e7190e38ee7e10daee0f4909d5066">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ac5295bdfdd480a2c66ee54273ebe21">buildZExtOrTrunc</a> (const DstOp &amp;Res, const SrcOp &amp;Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_ZEXT <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>, <span class="doxyComputerOutput">Res</span> = G_TRUNC <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>, or <span class="doxyComputerOutput">Res</span> = COPY <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> depending on the differing sizes of <span class="doxyComputerOutput">Res</span> and <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>. <a href="#a7ac5295bdfdd480a2c66ee54273ebe21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40c85353b0cd7cfdc7d8f8b364758c15">buildAnyExtOrTrunc</a> (const DstOp &amp;Res, const SrcOp &amp;Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">Res</span> = COPY <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> depending on the differing sizes of <span class="doxyComputerOutput">Res</span> and <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>. <a href="#a40c85353b0cd7cfdc7d8f8b364758c15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8da4d08f2c0875e9623bb712aa64303">buildExtOrTrunc</a> (unsigned ExtOpc, const DstOp &amp;Res, const SrcOp &amp;Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = <span class="doxyComputerOutput">ExtOpc</span>, <span class="doxyComputerOutput">Res</span> = G_TRUNC <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>, or <span class="doxyComputerOutput">Res</span> = COPY <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> depending on the differing sizes of <span class="doxyComputerOutput">Res</span> and <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>. <a href="#ab8da4d08f2c0875e9623bb712aa64303">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26edc3c3cae5a3f4d6ddd7f628b98c45">buildZExtInReg</a> (const DstOp &amp;Res, const SrcOp &amp;Op, int64_t ImmOp)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and inserts <span class="doxyComputerOutput">Res</span> = <span class="doxyComputerOutput">G_AND</span> <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>, <span class="doxyComputerOutput">LowBitsSet(ImmOp)</span> Since there is no G_ZEXT_INREG like G_SEXT_INREG, the instruction is emulated using G_AND. <a href="#a26edc3c3cae5a3f4d6ddd7f628b98c45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3493ece271aff0f2c3d162494e3fcc81">buildCast</a> (const DstOp &amp;Dst, const SrcOp &amp;Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert an appropriate cast between two registers of equal size. <a href="#a3493ece271aff0f2c3d162494e3fcc81">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ae44597e21d583e46c8bdfa52e56fa3">buildBr</a> (MachineBasicBlock &amp;Dest)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert G_BR <span class="doxyComputerOutput">Dest</span>. <a href="#a0ae44597e21d583e46c8bdfa52e56fa3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e0f051c17bd6354aec061d308d80841">buildBrCond</a> (const SrcOp &amp;Tst, MachineBasicBlock &amp;Dest)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert G_BRCOND <span class="doxyComputerOutput">Tst</span>, <span class="doxyComputerOutput">Dest</span>. <a href="#a6e0f051c17bd6354aec061d308d80841">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecf67aca8d78d0136244799c4182e52f">buildBrIndirect</a> (Register Tgt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert G_BRINDIRECT <span class="doxyComputerOutput">Tgt</span>. <a href="#aecf67aca8d78d0136244799c4182e52f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf1013659ccc9708197f76c0bd724936">buildBrJT</a> (Register TablePtr, unsigned JTI, Register IndexReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert G_BRJT <span class="doxyComputerOutput">TablePtr</span>, <span class="doxyComputerOutput">JTI</span>, <span class="doxyComputerOutput">IndexReg</span>. <a href="#aaf1013659ccc9708197f76c0bd724936">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af751c28a69e1d07e19dad11e4e26a70d">buildConstant</a> (const DstOp &amp;Res, const ConstantInt &amp;Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_CONSTANT <span class="doxyComputerOutput">Val</span>. <a href="#af751c28a69e1d07e19dad11e4e26a70d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdce4b9880a0aed02fe487da6a613cbd">buildConstant</a> (const DstOp &amp;Res, int64_t Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_CONSTANT <span class="doxyComputerOutput">Val</span>. <a href="#afdce4b9880a0aed02fe487da6a613cbd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab952b8b71fdba5baaf6a083e06d71da2">buildConstant</a> (const DstOp &amp;Res, const APInt &amp;Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81a7959d3e7f624343ecdf6905e251dd">buildFConstant</a> (const DstOp &amp;Res, const ConstantFP &amp;Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FCONSTANT <span class="doxyComputerOutput">Val</span>. <a href="#a81a7959d3e7f624343ecdf6905e251dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4265ff404073d12b765bc9fee4e7f186">buildFConstant</a> (const DstOp &amp;Res, double Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa28f164b227803f0fef41094366c2dca">buildFConstant</a> (const DstOp &amp;Res, const APFloat &amp;Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff3c145b6d12a00e7432953b1c454ebc">buildConstantPtrAuth</a> (const DstOp &amp;Res, const ConstantPtrAuth *CPA, Register Addr, Register AddrDisc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert G_PTRAUTH_GLOBAL_VALUE. <a href="#aff3c145b6d12a00e7432953b1c454ebc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae32b6e2213ad3119a124e6e0673a5898">buildCopy</a> (const DstOp &amp;Res, const SrcOp &amp;Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = COPY <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a>. <a href="#ae32b6e2213ad3119a124e6e0673a5898">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf3d2a21deea258c4c4a961586114ef9">buildAssertInstr</a> (unsigned Opc, const DstOp &amp;Res, const SrcOp &amp;Op, unsigned Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert G_ASSERT_SEXT, G_ASSERT_ZEXT, or G_ASSERT_ALIGN. <a href="#adf3d2a21deea258c4c4a961586114ef9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b02e5030940984fb331116653635050">buildAssertZExt</a> (const DstOp &amp;Res, const SrcOp &amp;Op, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_ASSERT_ZEXT <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a>, Size. <a href="#a6b02e5030940984fb331116653635050">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af22c90d17d814b2d13e0024cb4139c81">buildAssertSExt</a> (const DstOp &amp;Res, const SrcOp &amp;Op, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_ASSERT_SEXT <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a>, Size. <a href="#af22c90d17d814b2d13e0024cb4139c81">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5f844c0201df2446266aa977e285f5f">buildAssertAlign</a> (const DstOp &amp;Res, const SrcOp &amp;Op, Align AlignVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_ASSERT_ALIGN <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a>, AlignVal. <a href="#aa5f844c0201df2446266aa977e285f5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7962eca94c9f77da448245745fb22f57">buildLoad</a> (const DstOp &amp;Res, const SrcOp &amp;Addr, MachineMemOperand &amp;MMO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res = G_LOAD Addr, MMO</span>. <a href="#a7962eca94c9f77da448245745fb22f57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d61feda2a7e9f526ff461c900295bc1">buildLoad</a> (const DstOp &amp;Res, const SrcOp &amp;Addr, MachinePointerInfo PtrInfo, Align Alignment, MachineMemOperand::Flags MMOFlags=MachineMemOperand::MONone, const AAMDNodes &amp;AAInfo=AAMDNodes())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert a G_LOAD instruction, while constructing the <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a>. <a href="#a3d61feda2a7e9f526ff461c900295bc1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeede510b1aaac978daaba60dcc2817de">buildLoadInstr</a> (unsigned Opcode, const DstOp &amp;Res, const SrcOp &amp;Addr, MachineMemOperand &amp;MMO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res = &lt;opcode&gt; Addr, MMO</span>. <a href="#aeede510b1aaac978daaba60dcc2817de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a010032df630a417383fa44deee43ac0c">buildLoadFromOffset</a> (const DstOp &amp;Dst, const SrcOp &amp;BasePtr, MachineMemOperand &amp;BaseMMO, int64_t Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to create a load from a constant offset given a base address. <a href="#a010032df630a417383fa44deee43ac0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87a7405685118d45876c996318829ceb">buildStore</a> (const SrcOp &amp;Val, const SrcOp &amp;Addr, MachineMemOperand &amp;MMO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">G_STORE Val, Addr, MMO</span>. <a href="#a87a7405685118d45876c996318829ceb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea1b43a8ad482493c4b6898bf120a176">buildStore</a> (const SrcOp &amp;Val, const SrcOp &amp;Addr, MachinePointerInfo PtrInfo, Align Alignment, MachineMemOperand::Flags MMOFlags=MachineMemOperand::MONone, const AAMDNodes &amp;AAInfo=AAMDNodes())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert a G_STORE instruction, while constructing the <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a>. <a href="#aea1b43a8ad482493c4b6898bf120a176">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f52fec4aa17c3066db14a8d4717469d">buildExtract</a> (const DstOp &amp;Res, const SrcOp &amp;Src, uint64_t Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res0, ... = G_EXTRACT Src, Idx0</span>. <a href="#a2f52fec4aa17c3066db14a8d4717469d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a137bf40e73f82a78b6d2227ff65aeadf">buildUndef</a> (const DstOp &amp;Res)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = IMPLICIT_DEF. <a href="#a137bf40e73f82a78b6d2227ff65aeadf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe954ecff531c2cb1dcca7ed8813a318">buildMergeValues</a> (const DstOp &amp;Res, ArrayRef&lt; Register &gt; Ops)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_MERGE_VALUES <span class="doxyComputerOutput">Op0</span>, ... <a href="#abe954ecff531c2cb1dcca7ed8813a318">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7075ef788cb3dea0ea239c1a6830734c">buildMergeLikeInstr</a> (const DstOp &amp;Res, ArrayRef&lt; Register &gt; Ops)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_MERGE_VALUES <span class="doxyComputerOutput">Op0</span>, ... or <span class="doxyComputerOutput">Res</span> = G_BUILD_VECTOR <span class="doxyComputerOutput">Op0</span>, ... or <span class="doxyComputerOutput">Res</span> = G_CONCAT_VECTORS <span class="doxyComputerOutput">Op0</span>, ... <a href="#a7075ef788cb3dea0ea239c1a6830734c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0c1b48d1366572e4f3afa03e5c5f175">buildMergeLikeInstr</a> (const DstOp &amp;Res, std::initializer_list&lt; SrcOp &gt; Ops)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e9e055fc19307bc3c7c1be6ccd36812">buildUnmerge</a> (ArrayRef&lt; LLT &gt; Res, const SrcOp &amp;Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res0</span>, ... = G_UNMERGE_VALUES <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>. <a href="#a1e9e055fc19307bc3c7c1be6ccd36812">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a330499e5e11e1c2e82e0a8c7179f335d">buildUnmerge</a> (ArrayRef&lt; Register &gt; Res, const SrcOp &amp;Op)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeec9f9188630ac797d11be83445197b0">buildUnmerge</a> (LLT Res, const SrcOp &amp;Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert an unmerge of <span class="doxyComputerOutput">Res</span> sized pieces to cover <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>. <a href="#aeec9f9188630ac797d11be83445197b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3c19ecc16565c150796b834a8a63963">buildUnmerge</a> (MachineRegisterInfo::VRegAttrs Attrs, const SrcOp &amp;Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert an unmerge of pieces with <span class="doxyComputerOutput">Attrs</span> register attributes to cover <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>. <a href="#ac3c19ecc16565c150796b834a8a63963">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60609bd46d38414e2c9e2334f9740727">buildBuildVector</a> (const DstOp &amp;Res, ArrayRef&lt; Register &gt; Ops)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_BUILD_VECTOR <span class="doxyComputerOutput">Op0</span>, ... <a href="#a60609bd46d38414e2c9e2334f9740727">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96b7ed72c9782cd69b2b9b341cf73112">buildBuildVectorConstant</a> (const DstOp &amp;Res, ArrayRef&lt; APInt &gt; Ops)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_BUILD_VECTOR <span class="doxyComputerOutput">Op0</span>, ... where each OpN is built with G_CONSTANT. <a href="#a96b7ed72c9782cd69b2b9b341cf73112">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55bde2ba6aacac745a29a7e50c6be007">buildSplatBuildVector</a> (const DstOp &amp;Res, const SrcOp &amp;Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_BUILD_VECTOR with <span class="doxyComputerOutput">Src</span> replicated to fill the number of elements. <a href="#a55bde2ba6aacac745a29a7e50c6be007">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7acf8a5ebb4b351a451a2d63faf13294">buildBuildVectorTrunc</a> (const DstOp &amp;Res, ArrayRef&lt; Register &gt; Ops)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_BUILD_VECTOR_TRUNC <span class="doxyComputerOutput">Op0</span>, ... <a href="#a7acf8a5ebb4b351a451a2d63faf13294">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43b43271e5bcbbc5cc620b4dfa94937a">buildShuffleSplat</a> (const DstOp &amp;Res, const SrcOp &amp;Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert a vector splat of a scalar <span class="doxyComputerOutput">Src</span> using a G_INSERT_VECTOR_ELT and G_SHUFFLE_VECTOR idiom. <a href="#a43b43271e5bcbbc5cc620b4dfa94937a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aded2b440bea348970816da1ecd40f2c1">buildShuffleVector</a> (const DstOp &amp;Res, const SrcOp &amp;Src1, const SrcOp &amp;Src2, ArrayRef&lt; int &gt; Mask)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_SHUFFLE_VECTOR <span class="doxyComputerOutput">Src1</span>, <span class="doxyComputerOutput">Src2</span>, <span class="doxyComputerOutput">Mask</span>. <a href="#aded2b440bea348970816da1ecd40f2c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeea5857133a04085b450948e90fdcd1e">buildSplatVector</a> (const DstOp &amp;Res, const SrcOp &amp;Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_SPLAT_VECTOR <span class="doxyComputerOutput">Val</span>. <a href="#aeea5857133a04085b450948e90fdcd1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46cfa445be514255440f986c4b7b496f">buildConcatVectors</a> (const DstOp &amp;Res, ArrayRef&lt; Register &gt; Ops)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_CONCAT_VECTORS <span class="doxyComputerOutput">Op0</span>, ... <a href="#a46cfa445be514255440f986c4b7b496f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33a09195e1324b12063bf4d35c646066">buildInsertSubvector</a> (const DstOp &amp;Res, const SrcOp &amp;Src0, const SrcOp &amp;Src1, unsigned Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res = G_INSERT_SUBVECTOR Src0, Src1, Idx</span>. <a href="#a33a09195e1324b12063bf4d35c646066">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb07fff3cb0ad02bf88651e9388777de">buildExtractSubvector</a> (const DstOp &amp;Res, const SrcOp &amp;Src, unsigned Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res = G_EXTRACT_SUBVECTOR Src, Idx0</span>. <a href="#aeb07fff3cb0ad02bf88651e9388777de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf34795e0fa82f3edac1a235f50da4c1">buildInsert</a> (const DstOp &amp;Res, const SrcOp &amp;Src, const SrcOp &amp;Op, unsigned Index)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1b182c58ed8ff82a5958635de5ccb15">buildStepVector</a> (const DstOp &amp;Res, unsigned Step)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_STEP_VECTOR <span class="doxyComputerOutput">Step</span>. <a href="#af1b182c58ed8ff82a5958635de5ccb15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50ec87d072ddb08830486e9fb31ca6de">buildVScale</a> (const DstOp &amp;Res, unsigned MinElts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VSCALE <span class="doxyComputerOutput">MinElts</span>. <a href="#a50ec87d072ddb08830486e9fb31ca6de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3480c1f40e51b1673754af7384a5078">buildVScale</a> (const DstOp &amp;Res, const ConstantInt &amp;MinElts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VSCALE <span class="doxyComputerOutput">MinElts</span>. <a href="#ab3480c1f40e51b1673754af7384a5078">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad8f2c80f7625613c869923fbe25db5b">buildVScale</a> (const DstOp &amp;Res, const APInt &amp;MinElts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VSCALE <span class="doxyComputerOutput">MinElts</span>. <a href="#aad8f2c80f7625613c869923fbe25db5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b8abd0c10d11d7388c85825c9c220bf">buildIntrinsic</a> (Intrinsic::ID ID, ArrayRef&lt; Register &gt; Res, bool HasSideEffects, bool isConvergent)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert a G_INTRINSIC instruction. <a href="#a4b8abd0c10d11d7388c85825c9c220bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3481726c6f5714e53ed2efc761ed52bc">buildIntrinsic</a> (Intrinsic::ID ID, ArrayRef&lt; Register &gt; Res)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84f7ac7613ff133970f83e8531085353">buildIntrinsic</a> (Intrinsic::ID ID, ArrayRef&lt; DstOp &gt; Res, bool HasSideEffects, bool isConvergent)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41d7c53499da41b1739015f7036cf6da">buildIntrinsic</a> (Intrinsic::ID ID, ArrayRef&lt; DstOp &gt; Res)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad84b765997ad4d3bb1ca3e9393d70ab8">buildFPTrunc</a> (const DstOp &amp;Res, const SrcOp &amp;Op, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FPTRUNC <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>. <a href="#ad84b765997ad4d3bb1ca3e9393d70ab8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf1763199cd36c9253c6f062fa5e973e">buildTrunc</a> (const DstOp &amp;Res, const SrcOp &amp;Op, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_TRUNC <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>. <a href="#abf1763199cd36c9253c6f062fa5e973e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a618c7b84d45b5e188f6a7e4305ee39">buildICmp</a> (CmpInst::Predicate Pred, const DstOp &amp;Res, const SrcOp &amp;Op0, const SrcOp &amp;Op1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert a <span class="doxyComputerOutput">Res</span> = G_ICMP <span class="doxyComputerOutput">Pred</span>, <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>. <a href="#a3a618c7b84d45b5e188f6a7e4305ee39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb3340c638c09709ce5766dcf672500d">buildFCmp</a> (CmpInst::Predicate Pred, const DstOp &amp;Res, const SrcOp &amp;Op0, const SrcOp &amp;Op1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert a <span class="doxyComputerOutput">Res</span> = G_FCMP <span class="doxyComputerOutput">Pred<span class="doxyComputerOutput">Op0</span>,</span> <span class="doxyComputerOutput">Op1</span>. <a href="#afb3340c638c09709ce5766dcf672500d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21c1b400982de1ca29ecc051da8bb5b6">buildSCmp</a> (const DstOp &amp;Res, const SrcOp &amp;Op0, const SrcOp &amp;Op1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert a <span class="doxyComputerOutput">Res</span> = G_SCMP <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>. <a href="#a21c1b400982de1ca29ecc051da8bb5b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19fd5e11c62df9e228eb03dd466f5d0f">buildUCmp</a> (const DstOp &amp;Res, const SrcOp &amp;Op0, const SrcOp &amp;Op1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert a <span class="doxyComputerOutput">Res</span> = G_UCMP <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>. <a href="#a19fd5e11c62df9e228eb03dd466f5d0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe81abfee02ad99b922c40c0571e87a3">buildIsFPClass</a> (const DstOp &amp;Res, const SrcOp &amp;Src, unsigned Mask)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert a <span class="doxyComputerOutput">Res</span> = G_IS_FPCLASS <span class="doxyComputerOutput">Src</span>, <span class="doxyComputerOutput">Mask</span>. <a href="#abe81abfee02ad99b922c40c0571e87a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23ad1ea55dda3ab7617c7fad52c571ab">buildSelect</a> (const DstOp &amp;Res, const SrcOp &amp;Tst, const SrcOp &amp;Op0, const SrcOp &amp;Op1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert a <span class="doxyComputerOutput">Res</span> = G_SELECT <span class="doxyComputerOutput">Tst</span>, <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>. <a href="#a23ad1ea55dda3ab7617c7fad52c571ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca31191486506a279715dd3bf677d75f">buildInsertVectorElement</a> (const DstOp &amp;Res, const SrcOp &amp;Val, const SrcOp &amp;Elt, const SrcOp &amp;Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_INSERT_VECTOR_ELT <span class="doxyComputerOutput">Val</span>, <span class="doxyComputerOutput">Elt</span>, <span class="doxyComputerOutput">Idx</span>. <a href="#aca31191486506a279715dd3bf677d75f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e58ecea881b2ea06fee315563860e39">buildExtractVectorElementConstant</a> (const DstOp &amp;Res, const SrcOp &amp;Val, const int Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_EXTRACT_VECTOR_ELT <span class="doxyComputerOutput">Val</span>, <span class="doxyComputerOutput">Idx</span>. <a href="#a7e58ecea881b2ea06fee315563860e39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7835e6cd3f1b340d3bb617304038d744">buildExtractVectorElement</a> (const DstOp &amp;Res, const SrcOp &amp;Val, const SrcOp &amp;Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_EXTRACT_VECTOR_ELT <span class="doxyComputerOutput">Val</span>, <span class="doxyComputerOutput">Idx</span>. <a href="#a7835e6cd3f1b340d3bb617304038d744">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc22ffc46525708d66c036f878572523">buildAtomicCmpXchgWithSuccess</a> (const DstOp &amp;OldValRes, const DstOp &amp;SuccessRes, const SrcOp &amp;Addr, const SrcOp &amp;CmpVal, const SrcOp &amp;NewVal, MachineMemOperand &amp;MMO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt;, SuccessRes&lt;def&gt; = / G_ATOMIC_CMPXCHG_WITH_SUCCESS Addr, CmpVal, NewVal, MMO</span>. <a href="#acc22ffc46525708d66c036f878572523">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbf5d6125fa84e067907320d93e9fab5">buildAtomicCmpXchg</a> (const DstOp &amp;OldValRes, const SrcOp &amp;Addr, const SrcOp &amp;CmpVal, const SrcOp &amp;NewVal, MachineMemOperand &amp;MMO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMIC_CMPXCHG Addr, CmpVal, NewVal, / MMO</span>. <a href="#adbf5d6125fa84e067907320d93e9fab5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a497e8884b8ae421c7dadff0f0eea5e3e">buildAtomicRMW</a> (unsigned Opcode, const DstOp &amp;OldValRes, const SrcOp &amp;Addr, const SrcOp &amp;Val, MachineMemOperand &amp;MMO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_&lt;Opcode&gt; Addr, Val, MMO</span>. <a href="#a497e8884b8ae421c7dadff0f0eea5e3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5df6737579f8493e9dbf21b3e042daa">buildAtomicRMWXchg</a> (Register OldValRes, Register Addr, Register Val, MachineMemOperand &amp;MMO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_XCHG Addr, Val, MMO</span>. <a href="#af5df6737579f8493e9dbf21b3e042daa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad774da71cf0e58cad3b2436fc229b132">buildAtomicRMWAdd</a> (Register OldValRes, Register Addr, Register Val, MachineMemOperand &amp;MMO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_ADD Addr, Val, MMO</span>. <a href="#ad774da71cf0e58cad3b2436fc229b132">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb60c486a89a799e7fce06a7ea27d6fc">buildAtomicRMWSub</a> (Register OldValRes, Register Addr, Register Val, MachineMemOperand &amp;MMO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_SUB Addr, Val, MMO</span>. <a href="#abb60c486a89a799e7fce06a7ea27d6fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25352371c64f8746170df411d8929e2a">buildAtomicRMWAnd</a> (Register OldValRes, Register Addr, Register Val, MachineMemOperand &amp;MMO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_AND Addr, Val, MMO</span>. <a href="#a25352371c64f8746170df411d8929e2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37b11e193190795f9e0978f79faf6912">buildAtomicRMWNand</a> (Register OldValRes, Register Addr, Register Val, MachineMemOperand &amp;MMO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_NAND Addr, Val, MMO</span>. <a href="#a37b11e193190795f9e0978f79faf6912">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac79b1872a1bb01984f7c9470a1bc7bc7">buildAtomicRMWOr</a> (Register OldValRes, Register Addr, Register Val, MachineMemOperand &amp;MMO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_OR Addr, Val, MMO</span>. <a href="#ac79b1872a1bb01984f7c9470a1bc7bc7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a35bae390b9e7d83ce0ef35512da4ce">buildAtomicRMWXor</a> (Register OldValRes, Register Addr, Register Val, MachineMemOperand &amp;MMO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_XOR Addr, Val, MMO</span>. <a href="#a0a35bae390b9e7d83ce0ef35512da4ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea9f7405f8585dc061b0d5acb0988af0">buildAtomicRMWMax</a> (Register OldValRes, Register Addr, Register Val, MachineMemOperand &amp;MMO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_MAX Addr, Val, MMO</span>. <a href="#aea9f7405f8585dc061b0d5acb0988af0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c003dfc5b9bf2d8caa989ee52b3ee1b">buildAtomicRMWMin</a> (Register OldValRes, Register Addr, Register Val, MachineMemOperand &amp;MMO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_MIN Addr, Val, MMO</span>. <a href="#a2c003dfc5b9bf2d8caa989ee52b3ee1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fc31f69cb8aa379a0980ae5dce016bb">buildAtomicRMWUmax</a> (Register OldValRes, Register Addr, Register Val, MachineMemOperand &amp;MMO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_UMAX Addr, Val, MMO</span>. <a href="#a5fc31f69cb8aa379a0980ae5dce016bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97ffa56276d72a7b72e8b35d399d78a3">buildAtomicRMWUmin</a> (Register OldValRes, Register Addr, Register Val, MachineMemOperand &amp;MMO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_UMIN Addr, Val, MMO</span>. <a href="#a97ffa56276d72a7b72e8b35d399d78a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35fc180add02489be9e74ac41feacaf5">buildAtomicRMWFAdd</a> (const DstOp &amp;OldValRes, const SrcOp &amp;Addr, const SrcOp &amp;Val, MachineMemOperand &amp;MMO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_FADD Addr, Val, MMO</span>. <a href="#a35fc180add02489be9e74ac41feacaf5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1ffbbfa60b85f1fed7801afeb4a04a7">buildAtomicRMWFSub</a> (const DstOp &amp;OldValRes, const SrcOp &amp;Addr, const SrcOp &amp;Val, MachineMemOperand &amp;MMO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_FSUB Addr, Val, MMO</span>. <a href="#af1ffbbfa60b85f1fed7801afeb4a04a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac162dd239c19924c2ea4b0168b4dd551">buildAtomicRMWFMax</a> (const DstOp &amp;OldValRes, const SrcOp &amp;Addr, const SrcOp &amp;Val, MachineMemOperand &amp;MMO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_FMAX Addr, Val, MMO</span>. <a href="#ac162dd239c19924c2ea4b0168b4dd551">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01da2856dd0ee1c3f1ecf64b5500e714">buildAtomicRMWFMin</a> (const DstOp &amp;OldValRes, const SrcOp &amp;Addr, const SrcOp &amp;Val, MachineMemOperand &amp;MMO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_FMIN Addr, Val, MMO</span>. <a href="#a01da2856dd0ee1c3f1ecf64b5500e714">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b09525023b6ebfc6954493271dded49">buildAtomicRMWUSubCond</a> (const DstOp &amp;OldValRes, const SrcOp &amp;Addr, const SrcOp &amp;Val, MachineMemOperand &amp;MMO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_USUB_COND Addr, Val, MMO</span>. <a href="#a4b09525023b6ebfc6954493271dded49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17fe1c83d1fe58f743ec0d66f2073443">buildAtomicRMWUSubSat</a> (const DstOp &amp;OldValRes, const SrcOp &amp;Addr, const SrcOp &amp;Val, MachineMemOperand &amp;MMO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_USUB_SAT Addr, Val, MMO</span>. <a href="#a17fe1c83d1fe58f743ec0d66f2073443">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21f358f36e1ae7fc91568266264f760e">buildFence</a> (unsigned Ordering, unsigned Scope)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">G_FENCE Ordering, Scope</span>. <a href="#a21f358f36e1ae7fc91568266264f760e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeacc7cca9ff75b34872d7f7099d4261e">buildPrefetch</a> (const SrcOp &amp;Addr, unsigned RW, unsigned Locality, unsigned CacheType, MachineMemOperand &amp;MMO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert G_PREFETCH <span class="doxyComputerOutput">Addr</span>, <span class="doxyComputerOutput">RW</span>, <span class="doxyComputerOutput">Locality</span>, <span class="doxyComputerOutput">CacheType</span>. <a href="#aeacc7cca9ff75b34872d7f7099d4261e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08361fe1409d7e2a9b96b0cabb918383">buildFreeze</a> (const DstOp &amp;Dst, const SrcOp &amp;Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_FREEZE <span class="doxyComputerOutput">Src</span>. <a href="#a08361fe1409d7e2a9b96b0cabb918383">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae83cc330c36190cf8ee9618a28e9a300">buildBlockAddress</a> (Register Res, const BlockAddress *BA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_BLOCK_ADDR <span class="doxyComputerOutput">BA</span>. <a href="#ae83cc330c36190cf8ee9618a28e9a300">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12a128f6b9c963b6fd300cbdf52fba84">buildAdd</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_ADD <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>. <a href="#a12a128f6b9c963b6fd300cbdf52fba84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b2fab18274c6ca276053bb774c6e8c3">buildSub</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_SUB <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>. <a href="#a4b2fab18274c6ca276053bb774c6e8c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31a4848346777be4c13b39d57c0885d0">buildMul</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_MUL <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>. <a href="#a31a4848346777be4c13b39d57c0885d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90c3b61ed604fab822cb8f20a8e93fcb">buildAbds</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_ABDS <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>. <a href="#a90c3b61ed604fab822cb8f20a8e93fcb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a631d12fbfa91b33345eeec945832c8dd">buildAbdu</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_ABDU <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>. <a href="#a631d12fbfa91b33345eeec945832c8dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bf669233b50fac473a92c3039c48c4b">buildUMulH</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a284731f0ecc71898bf4ddc032e9f9a47">buildSMulH</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b08f09b085506a31ea5ac83f5d8fda1">buildURem</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_UREM <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>. <a href="#a3b08f09b085506a31ea5ac83f5d8fda1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04873b91eebbedfe4fd28d54029068d6">buildFMul</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad3884fe393aca6b2c9aa240a2bcdea4">buildFMinNum</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabf1fb6f032d501430f9f917739aaf11">buildFMaxNum</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a226e1d000521c2ff3964171f4f78ab5e">buildFMinNumIEEE</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad32b91bbb8f081b9c3d3040697dc5eac">buildFMaxNumIEEE</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8528b8088d41e3b859d4ea0f25e13991">buildShl</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e17399c568f784acb8ebf8be9a558ec">buildLShr</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d8cf0723104442c5ec84740aa7d43f9">buildAShr</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33eb6083767372c564ea4bcf6c06eaf1">buildAnd</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_AND <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>. <a href="#a33eb6083767372c564ea4bcf6c06eaf1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad93e8a9d68a578f6a53c70d39aef0dbe">buildOr</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_OR <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>. <a href="#ad93e8a9d68a578f6a53c70d39aef0dbe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af474773f09e4dbbc430d8d8df632e9fb">buildXor</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_XOR <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>. <a href="#af474773f09e4dbbc430d8d8df632e9fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16532d0d8fb47080714810131b45b75b">buildNot</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert a bitwise not, <span class="doxyComputerOutput">NegOne</span> = G_CONSTANT -1 <span class="doxyComputerOutput">Res</span> = G_OR <span class="doxyComputerOutput">Op0</span>, NegOne. <a href="#a16532d0d8fb47080714810131b45b75b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66aef31356eb4467a34fbcb72f1649ad">buildNeg</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert integer negation <span class="doxyComputerOutput">Zero</span> = G_CONSTANT 0 <span class="doxyComputerOutput">Res</span> = G_SUB Zero, <span class="doxyComputerOutput">Op0</span>. <a href="#a66aef31356eb4467a34fbcb72f1649ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9607e5a365ae4ce30b73b802f590bb21">buildCTPOP</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_CTPOP <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Src0</span>. <a href="#a9607e5a365ae4ce30b73b802f590bb21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a31c8e33dcb4c2c60d965227c227e8e">buildCTLZ</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_CTLZ <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Src0</span>. <a href="#a6a31c8e33dcb4c2c60d965227c227e8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fe52c440f33a8895fb01730017de4be">buildCTLZ_ZERO_UNDEF</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_CTLZ_ZERO_UNDEF <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Src0</span>. <a href="#a4fe52c440f33a8895fb01730017de4be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c1ac6707657ae4a0b6509e7857c1c68">buildCTTZ</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_CTTZ <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Src0</span>. <a href="#a1c1ac6707657ae4a0b6509e7857c1c68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80194aed09e8b4c04c228940ff2a56a5">buildCTTZ_ZERO_UNDEF</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_CTTZ_ZERO_UNDEF <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Src0</span>. <a href="#a80194aed09e8b4c04c228940ff2a56a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ef9ec8bbb1cbf1ad44e5039537ddfe3">buildBSwap</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_BSWAP <span class="doxyComputerOutput">Src0</span>. <a href="#a4ef9ec8bbb1cbf1ad44e5039537ddfe3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc51b7318978bc4878cce41bdf1774db">buildFAdd</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FADD <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>. <a href="#afc51b7318978bc4878cce41bdf1774db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c47deaeb76718f7eaa6262308a72dd5">buildStrictFAdd</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_STRICT_FADD <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>. <a href="#a6c47deaeb76718f7eaa6262308a72dd5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02d0daf870f6458a98b61f4b82a399c3">buildFSub</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FSUB <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>. <a href="#a02d0daf870f6458a98b61f4b82a399c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f3162ab8134a05797e7a1d21889d880">buildFDiv</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FDIV <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>. <a href="#a6f3162ab8134a05797e7a1d21889d880">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23b0488d15477183dec5de35d9082ef7">buildFMA</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1, const SrcOp &amp;Src2, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FMA <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>, <span class="doxyComputerOutput">Op2</span>. <a href="#a23b0488d15477183dec5de35d9082ef7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d77ec102570efb92c2b7571ac17cf4f">buildFMAD</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1, const SrcOp &amp;Src2, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FMAD <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>, <span class="doxyComputerOutput">Op2</span>. <a href="#a8d77ec102570efb92c2b7571ac17cf4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac939f3c7fdf6c976421d61564d078506">buildFNeg</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FNEG <span class="doxyComputerOutput">Op0</span>. <a href="#ac939f3c7fdf6c976421d61564d078506">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2161bd545c3baa8bfaa0d7b44ecf38c4">buildFAbs</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FABS <span class="doxyComputerOutput">Op0</span>. <a href="#a2161bd545c3baa8bfaa0d7b44ecf38c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe0950de33581b21ef3c56db5f4382c1">buildFCanonicalize</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_FCANONICALIZE <span class="doxyComputerOutput">Src0</span>. <a href="#afe0950de33581b21ef3c56db5f4382c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4252eb25f822e53c1bea2ec59e5c0f07">buildIntrinsicTrunc</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_INTRINSIC_TRUNC <span class="doxyComputerOutput">Src0</span>. <a href="#a4252eb25f822e53c1bea2ec59e5c0f07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5b247bb13afd8a0d31abedb522c7f46">buildFFloor</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = GFFLOOR <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>. <a href="#ad5b247bb13afd8a0d31abedb522c7f46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a914ca92cbc07e52a5115a023dc474f08">buildFLog</a> (const DstOp &amp;Dst, const SrcOp &amp;Src, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_FLOG <span class="doxyComputerOutput">Src</span>. <a href="#a914ca92cbc07e52a5115a023dc474f08">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d453180d499c717c2d4a189e7615b48">buildFLog2</a> (const DstOp &amp;Dst, const SrcOp &amp;Src, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_FLOG2 <span class="doxyComputerOutput">Src</span>. <a href="#a1d453180d499c717c2d4a189e7615b48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5849bcf7d4b148009464f4a8b7d3d367">buildFExp2</a> (const DstOp &amp;Dst, const SrcOp &amp;Src, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_FEXP2 <span class="doxyComputerOutput">Src</span>. <a href="#a5849bcf7d4b148009464f4a8b7d3d367">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f2727e87d9863c60b67b7d08b05d2e6">buildFPow</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_FPOW <span class="doxyComputerOutput">Src0</span>, <span class="doxyComputerOutput">Src1</span>. <a href="#a3f2727e87d9863c60b67b7d08b05d2e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a081e4f97d236d1d1c4e6599b7530498d">buildFLdexp</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_FLDEXP <span class="doxyComputerOutput">Src0</span>, <span class="doxyComputerOutput">Src1</span>. <a href="#a081e4f97d236d1d1c4e6599b7530498d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6391767e768c022d095516b3b86f3ae">buildFFrexp</a> (const DstOp &amp;Fract, const DstOp &amp;Exp, const SrcOp &amp;Src, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Fract</span>, <span class="doxyComputerOutput">Exp</span> = G_FFREXP <span class="doxyComputerOutput">Src</span>. <a href="#ad6391767e768c022d095516b3b86f3ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaa44dab2084014833b3744dfa291c89">buildFSincos</a> (const DstOp &amp;Sin, const DstOp &amp;Cos, const SrcOp &amp;Src, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Sin</span>, <span class="doxyComputerOutput">Cos</span> = G_FSINCOS <span class="doxyComputerOutput">Src</span>. <a href="#adaa44dab2084014833b3744dfa291c89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6b47b51bfacb6c594a3c6b8472202c1">buildFCopysign</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FCOPYSIGN <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>. <a href="#ac6b47b51bfacb6c594a3c6b8472202c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86e0c21f3e1e706b8d26733726c76195">buildUITOFP</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_UITOFP <span class="doxyComputerOutput">Src0</span>. <a href="#a86e0c21f3e1e706b8d26733726c76195">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c0db0c02bedbc26aba0fe9ebc77fff9">buildSITOFP</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_SITOFP <span class="doxyComputerOutput">Src0</span>. <a href="#a8c0db0c02bedbc26aba0fe9ebc77fff9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bb6c93f088c2df4bcb58e6f677e1213">buildFPTOUI</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FPTOUI <span class="doxyComputerOutput">Src0</span>. <a href="#a3bb6c93f088c2df4bcb58e6f677e1213">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03241215374b8ba88272333652a4a151">buildFPTOSI</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FPTOSI <span class="doxyComputerOutput">Src0</span>. <a href="#a03241215374b8ba88272333652a4a151">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00ac61b8d79a357bd578193be5f15454">buildFPTOUI_SAT</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FPTOUI_SAT <span class="doxyComputerOutput">Src0</span>. <a href="#a00ac61b8d79a357bd578193be5f15454">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a170e74a42d89ea7a0b8e0b8634afa404">buildFPTOSI_SAT</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FPTOSI_SAT <span class="doxyComputerOutput">Src0</span>. <a href="#a170e74a42d89ea7a0b8e0b8634afa404">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6de576f28600915731f6825a5c967f6">buildIntrinsicRoundeven</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_INTRINSIC_ROUNDEVEN <span class="doxyComputerOutput">Src0</span>, <span class="doxyComputerOutput">Src1</span>. <a href="#ab6de576f28600915731f6825a5c967f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad02a49b6c2f7c3c92a4ad7df5c4eb47">buildSMin</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_SMIN <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>. <a href="#aad02a49b6c2f7c3c92a4ad7df5c4eb47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a42ee731fc4e33eab8c5d6f76f8d8b2">buildSMax</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_SMAX <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>. <a href="#a6a42ee731fc4e33eab8c5d6f76f8d8b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9ac32566a3d7b10a68fac371f15f643">buildUMin</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_UMIN <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>. <a href="#af9ac32566a3d7b10a68fac371f15f643">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afae1758b4922383832826f8382b0ab54">buildUMax</a> (const DstOp &amp;Dst, const SrcOp &amp;Src0, const SrcOp &amp;Src1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_UMAX <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>. <a href="#afae1758b4922383832826f8382b0ab54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96860390999e933a817881a50a905219">buildAbs</a> (const DstOp &amp;Dst, const SrcOp &amp;Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_ABS <span class="doxyComputerOutput">Src</span>. <a href="#a96860390999e933a817881a50a905219">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e0ff1c3970daea3b6b33a07f4ad839e">buildJumpTable</a> (const LLT PtrTy, unsigned JTI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_JUMP_TABLE <span class="doxyComputerOutput">JTI</span>. <a href="#a1e0ff1c3970daea3b6b33a07f4ad839e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17c80c4630830047bb693ee47f58c8c3">buildVecReduceSeqFAdd</a> (const DstOp &amp;Dst, const SrcOp &amp;ScalarIn, const SrcOp &amp;VecIn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_SEQ_FADD <span class="doxyComputerOutput">ScalarIn</span>, <span class="doxyComputerOutput">VecIn</span>. <a href="#a17c80c4630830047bb693ee47f58c8c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a5597c997afda710f863873c38c534e">buildVecReduceSeqFMul</a> (const DstOp &amp;Dst, const SrcOp &amp;ScalarIn, const SrcOp &amp;VecIn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_SEQ_FMUL <span class="doxyComputerOutput">ScalarIn</span>, <span class="doxyComputerOutput">VecIn</span>. <a href="#a4a5597c997afda710f863873c38c534e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e1c6502399d7e0af30cba7a9925003f">buildVecReduceFAdd</a> (const DstOp &amp;Dst, const SrcOp &amp;ScalarIn, const SrcOp &amp;VecIn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_FADD <span class="doxyComputerOutput">Src</span>. <a href="#a5e1c6502399d7e0af30cba7a9925003f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f45e804fb39d50c4d8ec6bb1f5307a5">buildVecReduceFMul</a> (const DstOp &amp;Dst, const SrcOp &amp;ScalarIn, const SrcOp &amp;VecIn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_FMUL <span class="doxyComputerOutput">Src</span>. <a href="#a4f45e804fb39d50c4d8ec6bb1f5307a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cfde3d2db07050c016b443eaae2702d">buildVecReduceFMax</a> (const DstOp &amp;Dst, const SrcOp &amp;Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_FMAX <span class="doxyComputerOutput">Src</span>. <a href="#a2cfde3d2db07050c016b443eaae2702d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ededbd32ca155120e2dfd50f755688c">buildVecReduceFMin</a> (const DstOp &amp;Dst, const SrcOp &amp;Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_FMIN <span class="doxyComputerOutput">Src</span>. <a href="#a6ededbd32ca155120e2dfd50f755688c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a71277627a30c423608a2e598ba4d32">buildVecReduceFMaximum</a> (const DstOp &amp;Dst, const SrcOp &amp;Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_FMAXIMUM <span class="doxyComputerOutput">Src</span>. <a href="#a9a71277627a30c423608a2e598ba4d32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6397aa0392a0e4e57470de5e450da0b2">buildVecReduceFMinimum</a> (const DstOp &amp;Dst, const SrcOp &amp;Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_FMINIMUM <span class="doxyComputerOutput">Src</span>. <a href="#a6397aa0392a0e4e57470de5e450da0b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba86fb134fa3b2f01695749e0c7d84b6">buildVecReduceAdd</a> (const DstOp &amp;Dst, const SrcOp &amp;Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_ADD <span class="doxyComputerOutput">Src</span>. <a href="#aba86fb134fa3b2f01695749e0c7d84b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af80e0eddf323d627ac891582fcb4710e">buildVecReduceMul</a> (const DstOp &amp;Dst, const SrcOp &amp;Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_MUL <span class="doxyComputerOutput">Src</span>. <a href="#af80e0eddf323d627ac891582fcb4710e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a997b3e4a8a93ae662f2f972297415fd6">buildVecReduceAnd</a> (const DstOp &amp;Dst, const SrcOp &amp;Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_AND <span class="doxyComputerOutput">Src</span>. <a href="#a997b3e4a8a93ae662f2f972297415fd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cf2e534999d7df7c847a4331924000d">buildVecReduceOr</a> (const DstOp &amp;Dst, const SrcOp &amp;Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_OR <span class="doxyComputerOutput">Src</span>. <a href="#a1cf2e534999d7df7c847a4331924000d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e96b1d2ea4e991019ef283c4f588904">buildVecReduceXor</a> (const DstOp &amp;Dst, const SrcOp &amp;Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_XOR <span class="doxyComputerOutput">Src</span>. <a href="#a6e96b1d2ea4e991019ef283c4f588904">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4f70fb94cc8468f64183b6a5c75a0e0">buildVecReduceSMax</a> (const DstOp &amp;Dst, const SrcOp &amp;Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_SMAX <span class="doxyComputerOutput">Src</span>. <a href="#ae4f70fb94cc8468f64183b6a5c75a0e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a686f39d5b9c570d44717e2cf9ca3da07">buildVecReduceSMin</a> (const DstOp &amp;Dst, const SrcOp &amp;Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_SMIN <span class="doxyComputerOutput">Src</span>. <a href="#a686f39d5b9c570d44717e2cf9ca3da07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92a4e4e7dc4ca706beb3fb702283a77f">buildVecReduceUMax</a> (const DstOp &amp;Dst, const SrcOp &amp;Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_UMAX <span class="doxyComputerOutput">Src</span>. <a href="#a92a4e4e7dc4ca706beb3fb702283a77f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0d22cadad3d84314a8847549ecc0a55">buildVecReduceUMin</a> (const DstOp &amp;Dst, const SrcOp &amp;Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_UMIN <span class="doxyComputerOutput">Src</span>. <a href="#ab0d22cadad3d84314a8847549ecc0a55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae57ad469173d1ad36cb91dde447623ce">buildMemTransferInst</a> (unsigned Opcode, const SrcOp &amp;DstPtr, const SrcOp &amp;SrcPtr, const SrcOp &amp;Size, MachineMemOperand &amp;DstMMO, MachineMemOperand &amp;SrcMMO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert G_MEMCPY or G_MEMMOVE. <a href="#ae57ad469173d1ad36cb91dde447623ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3b92017579b7ddbca8c13cf7f746789">buildMemCpy</a> (const SrcOp &amp;DstPtr, const SrcOp &amp;SrcPtr, const SrcOp &amp;Size, MachineMemOperand &amp;DstMMO, MachineMemOperand &amp;SrcMMO)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5732a98562641ab5536b451ec72c5d4">buildTrap</a> (bool Debug=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert G_TRAP or G_DEBUGTRAP. <a href="#ad5732a98562641ab5536b451ec72c5d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8a77031249a2b8a1d527d156f54f9d5">buildSbfx</a> (const DstOp &amp;Dst, const SrcOp &amp;Src, const SrcOp &amp;LSB, const SrcOp &amp;Width)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_SBFX <span class="doxyComputerOutput">Src</span>, <span class="doxyComputerOutput">LSB</span>, <span class="doxyComputerOutput">Width</span>. <a href="#aa8a77031249a2b8a1d527d156f54f9d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a942b13bfd9c50bb5af1828739035ebe1">buildUbfx</a> (const DstOp &amp;Dst, const SrcOp &amp;Src, const SrcOp &amp;LSB, const SrcOp &amp;Width)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_UBFX <span class="doxyComputerOutput">Src</span>, <span class="doxyComputerOutput">LSB</span>, <span class="doxyComputerOutput">Width</span>. <a href="#a942b13bfd9c50bb5af1828739035ebe1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a197cbf8c5affd9a6e856e2ccb8085438">buildRotateRight</a> (const DstOp &amp;Dst, const SrcOp &amp;Src, const SrcOp &amp;Amt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_ROTR <span class="doxyComputerOutput">Src</span>, <span class="doxyComputerOutput">Amt</span>. <a href="#a197cbf8c5affd9a6e856e2ccb8085438">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff16332e2953a0f1430e9204b84f5aa6">buildRotateLeft</a> (const DstOp &amp;Dst, const SrcOp &amp;Src, const SrcOp &amp;Amt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_ROTL <span class="doxyComputerOutput">Src</span>, <span class="doxyComputerOutput">Amt</span>. <a href="#aff16332e2953a0f1430e9204b84f5aa6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a828ddf4cfe2b05f70a6566d36b4804c5">buildBitReverse</a> (const DstOp &amp;Dst, const SrcOp &amp;Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_BITREVERSE <span class="doxyComputerOutput">Src</span>. <a href="#a828ddf4cfe2b05f70a6566d36b4804c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac69ef19d33fd455e8684cb53be2e46bb">buildGetFPEnv</a> (const DstOp &amp;Dst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_GET_FPENV. <a href="#ac69ef19d33fd455e8684cb53be2e46bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc7eb07b74fdeb50e151b325880fd51d">buildSetFPEnv</a> (const SrcOp &amp;Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert G_SET_FPENV <span class="doxyComputerOutput">Src</span>. <a href="#afc7eb07b74fdeb50e151b325880fd51d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab727f77aa5c064c0881a08e4bbb61c86">buildResetFPEnv</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert G_RESET_FPENV. <a href="#ab727f77aa5c064c0881a08e4bbb61c86">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23dbfe8493962b776dd1635121d87cd0">buildGetFPMode</a> (const DstOp &amp;Dst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_GET_FPMODE. <a href="#a23dbfe8493962b776dd1635121d87cd0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a585b4bef3330a9b489810dab77c07d3b">buildSetFPMode</a> (const SrcOp &amp;Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert G_SET_FPMODE <span class="doxyComputerOutput">Src</span>. <a href="#a585b4bef3330a9b489810dab77c07d3b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14a087440fb584f0874f38801175bc64">buildResetFPMode</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert G_RESET_FPMODE. <a href="#a14a087440fb584f0874f38801175bc64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dacb1328b30771530a48be17307efb0">buildInstr</a> (unsigned Opc, ArrayRef&lt; DstOp &gt; DstOps, ArrayRef&lt; SrcOp &gt; SrcOps, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfd8cf26645132e9a23697eed85685e1">validateTruncExt</a> (const LLT Dst, const LLT Src, bool IsExtend)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae63e90ab103cd2159b9431b5ed5e9a53">validateUnaryOp</a> (const LLT Res, const LLT Op0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9856f0ee59ced7e9724315502ea9a380">validateBinaryOp</a> (const LLT Res, const LLT Op0, const LLT Op1)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8154c310c33839a5d134b63c4d9cb6">validateShiftOp</a> (const LLT Res, const LLT Op0, const LLT Op1)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91a10c5f7ca3b7a86768cb33f8955b5c">validateSelectOp</a> (const LLT ResTy, const LLT TstTy, const LLT Op0Ty, const LLT Op1Ty)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6baa0ad8a95dcded4f50f3bf0d20c94d">recordInsertion</a> (MachineInstr *InsertedInstr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8ef2c990e66f323d8b61022a4af9ab7">getOpcodeForMerge</a> (const DstOp &amp;DstOp, ArrayRef&lt; SrcOp &gt; SrcOps) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/machineirbuilderstate">MachineIRBuilderState</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a786dd19ce6843c72e9a16e8b0c886517">State</a></td>
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

## Setters for the insertion point. Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0d9669bbadd4d5e1d75c3c833c8d5ac">setMF</a> (MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd5c75a12ec8c12c35de46c60d18c699">setMBB</a> (MachineBasicBlock &amp;MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the insertion point to the end of <span class="doxyComputerOutput">MBB</span>. <a href="#acd5c75a12ec8c12c35de46c60d18c699">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cac2a17ab11d53dd0a49871b80f5c7a">setInstr</a> (MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the insertion point to before MI. <a href="#a4cac2a17ab11d53dd0a49871b80f5c7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Helper class to build <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>.</p>


<p>It keeps internally the insertion point and debug location for all the new instructions we want to create. This information can be modified via the related setters.</p>


<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MachineIRBuilder() {#ad662a74c60eeb99f6a24927479eda063}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineIRBuilder::MachineIRBuilder ()</td>
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

<p>Some constructors for easy use.</p>

<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a7be5d9bbd5832221068ae6c93cf24d51">getMBB</a>, <a href="#a7d5d8e859928cc003454a2ba18372a71">MachineIRBuilder</a> and <a href="#a8d69fb9fe28f38bfe61a276caec92263">MachineIRBuilder</a>.</p>

</div>
</div>

### MachineIRBuilder() {#aa03c7e0eb5346e000177cb95b910cc71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineIRBuilder::MachineIRBuilder (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#af0d9669bbadd4d5e1d75c3c833c8d5ac">setMF</a>.</p>

</div>
</div>

### MachineIRBuilder() {#a6149c9a2642b91bfdb471868a7f8bd1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineIRBuilder::MachineIRBuilder (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> InsPt)</td>
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



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#a0df93c0f752428162e14b54f8999172d">setInsertPt</a> and <a href="#af0d9669bbadd4d5e1d75c3c833c8d5ac">setMF</a>.</p>

</div>
</div>

### MachineIRBuilder() {#a7d5d8e859928cc003454a2ba18372a71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineIRBuilder::MachineIRBuilder (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>, <a href="#ad662a74c60eeb99f6a24927479eda063">MachineIRBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ac444a61cbfb8a46d48688a530e5defe1">setDebugLoc</a> and <a href="#a4cac2a17ab11d53dd0a49871b80f5c7a">setInstr</a>.</p>

</div>
</div>

### MachineIRBuilder() {#a8d69fb9fe28f38bfe61a276caec92263}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineIRBuilder::MachineIRBuilder (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver">GISelChangeObserver</a> &amp; Observer)</td>
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



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="#ad662a74c60eeb99f6a24927479eda063">MachineIRBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#af69cfe118f734f35607c8fd4615ea1bf">setChangeObserver</a>.</p>

</div>
</div>

### MachineIRBuilder() {#aa048045615f06db86c3a4e317ed3a2b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineIRBuilder::MachineIRBuilder (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machineirbuilderstate">MachineIRBuilderState</a> &amp; BState)</td>
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



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MachineIRBuilder() {#a1c9f7862be40509888ddd3febc051c85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::MachineIRBuilder::~MachineIRBuilder ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### buildAbds() {#a90c3b61ed604fab822cb8f20a8e93fcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildAbds (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_ABDS <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>.</p>


<p>G_ABDS return the signed absolute difference of <span class="doxyComputerOutput">Op0</span> and <span class="doxyComputerOutput">Op1</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span>, <span class="doxyComputerOutput">Op0</span> and <span class="doxyComputerOutput">Op1</span> must be generic virtual registers with the same (scalar or vector) type).</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Definition at line 1784 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildAbdu() {#a631d12fbfa91b33345eeec945832c8dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildAbdu (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_ABDU <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>.</p>


<p>G_ABDU return the unsigned absolute difference of <span class="doxyComputerOutput">Op0</span> and <span class="doxyComputerOutput">Op1</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span>, <span class="doxyComputerOutput">Op0</span> and <span class="doxyComputerOutput">Op1</span> must be generic virtual registers with the same (scalar or vector) type).</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Definition at line 1798 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildAbs() {#a96860390999e933a817881a50a905219}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildAbs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_ABS <span class="doxyComputerOutput">Src</span>.</p>

<p>Definition at line 2144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildAdd() {#a12a128f6b9c963b6fd300cbdf52fba84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_ADD <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>.</p>


<p>G_ADD sets <span class="doxyComputerOutput">Res</span> to the sum of integer parameters <span class="doxyComputerOutput">Op0</span> and <span class="doxyComputerOutput">Op1</span>, truncated to their width.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span>, <span class="doxyComputerOutput">Op0</span> and <span class="doxyComputerOutput">Op1</span> must be generic virtual registers with the same (scalar or vector) type).</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Definition at line 1736 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildAddrSpaceCast() {#a534266d65ce335e1d212f37fc554dbb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildAddrSpaceCast (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_ADDRSPACE_CAST <span class="doxyComputerOutput">Src</span>.</p>

<p>Definition at line 728 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildAnd() {#a33eb6083767372c564ea4bcf6c06eaf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildAnd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_AND <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>.</p>


<p>G_AND sets <span class="doxyComputerOutput">Res</span> to the bitwise and of integer parameters <span class="doxyComputerOutput">Op0</span> and <span class="doxyComputerOutput">Op1</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span>, <span class="doxyComputerOutput">Op0</span> and <span class="doxyComputerOutput">Op1</span> must be generic virtual registers with the same (scalar or vector) type).</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Definition at line 1881 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a580c192e2fc41ab69e61d087027ceabf">anonymous{AArch64PostLegalizerLowering.cpp}::applyNonConstInsert</a>, <a href="#a26edc3c3cae5a3f4d6ddd7f628b98c45">buildZExtInReg</a>, <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a2aeed55e4456de4086b3592eb92dc2e2">llvm::ARMLegalizerInfo::legalizeCustom</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#a1ddebf0db857b4b9fd7004511b7eb393">llvm::RISCVLegalizerInfo::legalizeCustom</a>.</p>

</div>
</div>

### buildAnyExt() {#acac15566596b1d588d87450ab77bf0d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildAnyExt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_ANYEXT <span class="doxyComputerOutput">Op0</span>.</p>


<p>G_ANYEXT produces a register of the specified width, with bits 0 to sizeof(<span class="doxyComputerOutput">Ty</span>) * 8 set to <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>. The remaining bits are unspecified (i.e. this is neither zero nor sign-extension). For a vector register, each element is extended individually.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register with scalar or vector type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> must be a generic virtual register with scalar or vector type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> must be smaller than <span class="doxyComputerOutput">Res</span></p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The newly created instruction.</p></dd>
</dl>


<p>Declaration at line 685 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp/#af5f0f04b137494bbf8fb56286dea2762">buildAnyextOrCopy</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpucalllowering-cpp-/#af49a6097a8071a69f37f57febd91c05c">anonymous{AMDGPUCallLowering.cpp}::extendRegisterMin32</a>, <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a867592b1a0963211ea415ea436a976e5">llvm::MipsLegalizerInfo::legalizeCustom</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#aa48b853fae2f40e3e483078a944ab8d1">llvm::AArch64LegalizerInfo::legalizeIntrinsic</a>.</p>

</div>
</div>

### buildAnyExtOrTrunc() {#a40c85353b0cd7cfdc7d8f8b364758c15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildAnyExtOrTrunc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><span class="doxyComputerOutput">Res</span> = COPY <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> depending on the differing sizes of <span class="doxyComputerOutput">Res</span> and <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>.</p>


<p>///</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register with scalar or vector type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> must be a generic virtual register with scalar or vector type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The newly created instruction.</p></dd>
</dl>


<p>Declaration at line 791 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 581 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#ab8da4d08f2c0875e9623bb712aa64303">buildExtOrTrunc</a>.</p>

</div>
</div>

### buildAShr() {#a1d8cf0723104442c5ec84740aa7d43f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildAShr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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



<p>Definition at line 1864 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildAssertAlign() {#aa5f844c0201df2446266aa977e285f5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildAssertAlign (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> AlignVal)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_ASSERT_ALIGN <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a>, AlignVal.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Definition at line 944 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="#adf3d2a21deea258c4c4a961586114ef9">buildAssertInstr</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af5462628f10dea9944615cd509dd3634">llvm::CallLowering::lowerCall</a>.</p>

</div>
</div>

### buildAssertInstr() {#adf3d2a21deea258c4c4a961586114ef9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildAssertInstr (unsigned Opc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op, unsigned Val)</td>
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

<p>Build and insert G_ASSERT_SEXT, G_ASSERT_ZEXT, or G_ASSERT_ALIGN.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Definition at line 920 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a> and <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>


<p>Referenced by <a href="#aa5f844c0201df2446266aa977e285f5f">buildAssertAlign</a>, <a href="#af22c90d17d814b2d13e0024cb4139c81">buildAssertSExt</a> and <a href="#a6b02e5030940984fb331116653635050">buildAssertZExt</a>.</p>

</div>
</div>

### buildAssertSExt() {#af22c90d17d814b2d13e0024cb4139c81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildAssertSExt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op, unsigned Size)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_ASSERT_SEXT <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a>, Size.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Definition at line 936 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="#adf3d2a21deea258c4c4a961586114ef9">buildAssertInstr</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### buildAssertZExt() {#a6b02e5030940984fb331116653635050}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildAssertZExt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op, unsigned Size)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_ASSERT_ZEXT <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a>, Size.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Definition at line 928 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="#adf3d2a21deea258c4c4a961586114ef9">buildAssertInstr</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#af647b791a2c24c4f48aa11d1a77a5bc5">llvm::AArch64CallLowering::lowerFormalArguments</a>.</p>

</div>
</div>

### buildAtomicCmpXchg() {#adbf5d6125fa84e067907320d93e9fab5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildAtomicCmpXchg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; OldValRes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Addr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; CmpVal, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; NewVal, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; MMO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMIC_CMPXCHG Addr, CmpVal, NewVal, / MMO</span>.</p>



<pre><code>  Atomically replace the value at \p Addr with \p NewVal if it is currently
  \p CmpVal otherwise leaves it unchanged. Puts the original value from \p
  Addr in \p Res.

  \pre setBasicBlock or setMI must have been called.
  \pre \p OldValRes must be a generic virtual register of scalar type.
  \pre \p Addr must be a generic virtual register with pointer type.
  \pre \p OldValRes, \p CmpVal, and \p NewVal must be generic virtual
       registers of the same type.

  \return a MachineInstrBuilder for the newly created instruction.
</code></pre>


<p>Declaration at line 1431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 1013 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dstop/#a45141d649d02a2ed17b51b5419ee884d">llvm::DstOp::addDefToMIB</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#aba93d72255e1239b5209e416a1b7f199">llvm::SrcOp::addSrcToMIB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a49a5649c0de9dee3dacbab3019872923">llvm::DstOp::getLLTTy</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#a99fb11458708b57172b6b0df633fd4fc">llvm::SrcOp::getLLTTy</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a9d825f5954d7bd527aea490668c624c6">llvm::LLT::isPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a69fb30748f1b3e8a0affd486a9f59f6d">llvm::LLT::isValid</a>.</p>

</div>
</div>

### buildAtomicCmpXchgWithSuccess() {#acc22ffc46525708d66c036f878572523}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildAtomicCmpXchgWithSuccess (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; OldValRes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; SuccessRes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Addr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; CmpVal, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; NewVal, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; MMO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt;, SuccessRes&lt;def&gt; = / G_ATOMIC_CMPXCHG_WITH_SUCCESS Addr, CmpVal, NewVal, MMO</span>.</p>



<pre><code>  Atomically replace the value at \p Addr with \p NewVal if it is currently
  \p CmpVal otherwise leaves it unchanged. Puts the original value from \p
  Addr in \p Res, along with an s1 indicating whether it was replaced.

  \pre setBasicBlock or setMI must have been called.
  \pre \p OldValRes must be a generic virtual register of scalar type.
  \pre \p SuccessRes must be a generic virtual register of scalar type. It
       will be assigned 0 on failure and 1 on success.
  \pre \p Addr must be a generic virtual register with pointer type.
  \pre \p OldValRes, \p CmpVal, and \p NewVal must be generic virtual
       registers of the same type.

  \return a MachineInstrBuilder for the newly created instruction.
</code></pre>


<p>Declaration at line 1413 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 984 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dstop/#a45141d649d02a2ed17b51b5419ee884d">llvm::DstOp::addDefToMIB</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#aba93d72255e1239b5209e416a1b7f199">llvm::SrcOp::addSrcToMIB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a49a5649c0de9dee3dacbab3019872923">llvm::DstOp::getLLTTy</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#a99fb11458708b57172b6b0df633fd4fc">llvm::SrcOp::getLLTTy</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a9d825f5954d7bd527aea490668c624c6">llvm::LLT::isPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a69fb30748f1b3e8a0affd486a9f59f6d">llvm::LLT::isValid</a>.</p>

</div>
</div>

### buildAtomicRMW() {#a497e8884b8ae421c7dadff0f0eea5e3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildAtomicRMW (unsigned Opcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; OldValRes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Addr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Val, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; MMO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_&lt;Opcode&gt; Addr, Val, MMO</span>.</p>


<p>Atomically read-modify-update the value at <span class="doxyComputerOutput">Addr</span> with <span class="doxyComputerOutput">Val</span>. Puts the original value from <span class="doxyComputerOutput">Addr</span> in <span class="doxyComputerOutput">OldValRes</span>. The modification is determined by the opcode.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span> must be a generic virtual register.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Addr</span> must be a generic virtual register with pointer type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span>, and <span class="doxyComputerOutput">Val</span> must be generic virtual registers of the same type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 1038 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dstop/#a45141d649d02a2ed17b51b5419ee884d">llvm::DstOp::addDefToMIB</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#aba93d72255e1239b5209e416a1b7f199">llvm::SrcOp::addSrcToMIB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a49a5649c0de9dee3dacbab3019872923">llvm::DstOp::getLLTTy</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#a99fb11458708b57172b6b0df633fd4fc">llvm::SrcOp::getLLTTy</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a6829ff090c767b553f2390e0785adf4a">llvm::MachineMemOperand::isAtomic</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a9d825f5954d7bd527aea490668c624c6">llvm::LLT::isPointer</a>.</p>


<p>Referenced by <a href="#ad774da71cf0e58cad3b2436fc229b132">buildAtomicRMWAdd</a>, <a href="#a25352371c64f8746170df411d8929e2a">buildAtomicRMWAnd</a>, <a href="#a35fc180add02489be9e74ac41feacaf5">buildAtomicRMWFAdd</a>, <a href="#ac162dd239c19924c2ea4b0168b4dd551">buildAtomicRMWFMax</a>, <a href="#a01da2856dd0ee1c3f1ecf64b5500e714">buildAtomicRMWFMin</a>, <a href="#af1ffbbfa60b85f1fed7801afeb4a04a7">buildAtomicRMWFSub</a>, <a href="#aea9f7405f8585dc061b0d5acb0988af0">buildAtomicRMWMax</a>, <a href="#a2c003dfc5b9bf2d8caa989ee52b3ee1b">buildAtomicRMWMin</a>, <a href="#a37b11e193190795f9e0978f79faf6912">buildAtomicRMWNand</a>, <a href="#ac79b1872a1bb01984f7c9470a1bc7bc7">buildAtomicRMWOr</a>, <a href="#abb60c486a89a799e7fce06a7ea27d6fc">buildAtomicRMWSub</a>, <a href="#a5fc31f69cb8aa379a0980ae5dce016bb">buildAtomicRMWUmax</a>, <a href="#a97ffa56276d72a7b72e8b35d399d78a3">buildAtomicRMWUmin</a>, <a href="#af5df6737579f8493e9dbf21b3e042daa">buildAtomicRMWXchg</a> and <a href="#a0a35bae390b9e7d83ce0ef35512da4ce">buildAtomicRMWXor</a>.</p>

</div>
</div>

### buildAtomicRMWAdd() {#ad774da71cf0e58cad3b2436fc229b132}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildAtomicRMWAdd (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> OldValRes, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Val, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; MMO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_ADD Addr, Val, MMO</span>.</p>


<p>Atomically replace the value at <span class="doxyComputerOutput">Addr</span> with the addition of <span class="doxyComputerOutput">Val</span> and the original value. Puts the original value from <span class="doxyComputerOutput">Addr</span> in <span class="doxyComputerOutput">OldValRes</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span> must be a generic virtual register.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Addr</span> must be a generic virtual register with pointer type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span>, and <span class="doxyComputerOutput">Val</span> must be generic virtual registers of the same type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1480 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 1068 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a497e8884b8ae421c7dadff0f0eea5e3e">buildAtomicRMW</a>.</p>

</div>
</div>

### buildAtomicRMWAnd() {#a25352371c64f8746170df411d8929e2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildAtomicRMWAnd (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> OldValRes, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Val, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; MMO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_AND Addr, Val, MMO</span>.</p>


<p>Atomically replace the value at <span class="doxyComputerOutput">Addr</span> with the bitwise and of <span class="doxyComputerOutput">Val</span> and the original value. Puts the original value from <span class="doxyComputerOutput">Addr</span> in <span class="doxyComputerOutput">OldValRes</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span> must be a generic virtual register.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Addr</span> must be a generic virtual register with pointer type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span>, and <span class="doxyComputerOutput">Val</span> must be generic virtual registers of the same type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1510 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 1080 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a497e8884b8ae421c7dadff0f0eea5e3e">buildAtomicRMW</a>.</p>

</div>
</div>

### buildAtomicRMWFAdd() {#a35fc180add02489be9e74ac41feacaf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildAtomicRMWFAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; OldValRes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Addr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Val, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; MMO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_FADD Addr, Val, MMO</span>.</p>

<p>Declaration at line 1624 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 1130 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a497e8884b8ae421c7dadff0f0eea5e3e">buildAtomicRMW</a>.</p>

</div>
</div>

### buildAtomicRMWFMax() {#ac162dd239c19924c2ea4b0168b4dd551}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildAtomicRMWFMax (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; OldValRes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Addr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Val, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; MMO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_FMAX Addr, Val, MMO</span>.</p>


<p>Atomically replace the value at <span class="doxyComputerOutput">Addr</span> with the floating point maximum of <span class="doxyComputerOutput">Val</span> and the original value. Puts the original value from <span class="doxyComputerOutput">Addr</span> in <span class="doxyComputerOutput">OldValRes</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span> must be a generic virtual register.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Addr</span> must be a generic virtual register with pointer type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span>, and <span class="doxyComputerOutput">Val</span> must be generic virtual registers of the same type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1646 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 1145 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a497e8884b8ae421c7dadff0f0eea5e3e">buildAtomicRMW</a>.</p>

</div>
</div>

### buildAtomicRMWFMin() {#a01da2856dd0ee1c3f1ecf64b5500e714}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildAtomicRMWFMin (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; OldValRes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Addr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Val, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; MMO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_FMIN Addr, Val, MMO</span>.</p>


<p>Atomically replace the value at <span class="doxyComputerOutput">Addr</span> with the floating point minimum of <span class="doxyComputerOutput">Val</span> and the original value. Puts the original value from <span class="doxyComputerOutput">Addr</span> in <span class="doxyComputerOutput">OldValRes</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span> must be a generic virtual register.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Addr</span> must be a generic virtual register with pointer type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span>, and <span class="doxyComputerOutput">Val</span> must be generic virtual registers of the same type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1663 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 1152 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a497e8884b8ae421c7dadff0f0eea5e3e">buildAtomicRMW</a>.</p>

</div>
</div>

### buildAtomicRMWFSub() {#af1ffbbfa60b85f1fed7801afeb4a04a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildAtomicRMWFSub (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; OldValRes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Addr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Val, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; MMO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_FSUB Addr, Val, MMO</span>.</p>

<p>Declaration at line 1629 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 1138 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a497e8884b8ae421c7dadff0f0eea5e3e">buildAtomicRMW</a>.</p>

</div>
</div>

### buildAtomicRMWMax() {#aea9f7405f8585dc061b0d5acb0988af0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildAtomicRMWMax (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> OldValRes, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Val, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; MMO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_MAX Addr, Val, MMO</span>.</p>


<p>Atomically replace the value at <span class="doxyComputerOutput">Addr</span> with the signed maximum of <span class="doxyComputerOutput">Val</span> and the original value. Puts the original value from <span class="doxyComputerOutput">Addr</span> in <span class="doxyComputerOutput">OldValRes</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span> must be a generic virtual register.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Addr</span> must be a generic virtual register with pointer type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span>, and <span class="doxyComputerOutput">Val</span> must be generic virtual registers of the same type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1572 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 1105 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a497e8884b8ae421c7dadff0f0eea5e3e">buildAtomicRMW</a>.</p>

</div>
</div>

### buildAtomicRMWMin() {#a2c003dfc5b9bf2d8caa989ee52b3ee1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildAtomicRMWMin (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> OldValRes, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Val, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; MMO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_MIN Addr, Val, MMO</span>.</p>


<p>Atomically replace the value at <span class="doxyComputerOutput">Addr</span> with the signed minimum of <span class="doxyComputerOutput">Val</span> and the original value. Puts the original value from <span class="doxyComputerOutput">Addr</span> in <span class="doxyComputerOutput">OldValRes</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span> must be a generic virtual register.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Addr</span> must be a generic virtual register with pointer type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span>, and <span class="doxyComputerOutput">Val</span> must be generic virtual registers of the same type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1588 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 1111 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a497e8884b8ae421c7dadff0f0eea5e3e">buildAtomicRMW</a>.</p>

</div>
</div>

### buildAtomicRMWNand() {#a37b11e193190795f9e0978f79faf6912}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildAtomicRMWNand (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> OldValRes, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Val, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; MMO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_NAND Addr, Val, MMO</span>.</p>


<p>Atomically replace the value at <span class="doxyComputerOutput">Addr</span> with the bitwise nand of <span class="doxyComputerOutput">Val</span> and the original value. Puts the original value from <span class="doxyComputerOutput">Addr</span> in <span class="doxyComputerOutput">OldValRes</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span> must be a generic virtual register.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Addr</span> must be a generic virtual register with pointer type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span>, and <span class="doxyComputerOutput">Val</span> must be generic virtual registers of the same type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1526 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 1086 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a497e8884b8ae421c7dadff0f0eea5e3e">buildAtomicRMW</a>.</p>

</div>
</div>

### buildAtomicRMWOr() {#ac79b1872a1bb01984f7c9470a1bc7bc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildAtomicRMWOr (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> OldValRes, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Val, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; MMO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_OR Addr, Val, MMO</span>.</p>


<p>Atomically replace the value at <span class="doxyComputerOutput">Addr</span> with the bitwise or of <span class="doxyComputerOutput">Val</span> and the original value. Puts the original value from <span class="doxyComputerOutput">Addr</span> in <span class="doxyComputerOutput">OldValRes</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span> must be a generic virtual register.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Addr</span> must be a generic virtual register with pointer type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span>, and <span class="doxyComputerOutput">Val</span> must be generic virtual registers of the same type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1541 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 1091 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a497e8884b8ae421c7dadff0f0eea5e3e">buildAtomicRMW</a>.</p>

</div>
</div>

### buildAtomicRMWSub() {#abb60c486a89a799e7fce06a7ea27d6fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildAtomicRMWSub (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> OldValRes, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Val, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; MMO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_SUB Addr, Val, MMO</span>.</p>


<p>Atomically replace the value at <span class="doxyComputerOutput">Addr</span> with the subtraction of <span class="doxyComputerOutput">Val</span> and the original value. Puts the original value from <span class="doxyComputerOutput">Addr</span> in <span class="doxyComputerOutput">OldValRes</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span> must be a generic virtual register.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Addr</span> must be a generic virtual register with pointer type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span>, and <span class="doxyComputerOutput">Val</span> must be generic virtual registers of the same type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1495 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 1074 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a497e8884b8ae421c7dadff0f0eea5e3e">buildAtomicRMW</a>.</p>

</div>
</div>

### buildAtomicRMWUmax() {#a5fc31f69cb8aa379a0980ae5dce016bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildAtomicRMWUmax (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> OldValRes, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Val, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; MMO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_UMAX Addr, Val, MMO</span>.</p>


<p>Atomically replace the value at <span class="doxyComputerOutput">Addr</span> with the unsigned maximum of <span class="doxyComputerOutput">Val</span> and the original value. Puts the original value from <span class="doxyComputerOutput">Addr</span> in <span class="doxyComputerOutput">OldValRes</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span> must be a generic virtual register.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Addr</span> must be a generic virtual register with pointer type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span>, and <span class="doxyComputerOutput">Val</span> must be generic virtual registers of the same type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1604 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 1117 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a497e8884b8ae421c7dadff0f0eea5e3e">buildAtomicRMW</a>.</p>

</div>
</div>

### buildAtomicRMWUmin() {#a97ffa56276d72a7b72e8b35d399d78a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildAtomicRMWUmin (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> OldValRes, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Val, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; MMO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_UMIN Addr, Val, MMO</span>.</p>


<p>Atomically replace the value at <span class="doxyComputerOutput">Addr</span> with the unsigned minimum of <span class="doxyComputerOutput">Val</span> and the original value. Puts the original value from <span class="doxyComputerOutput">Addr</span> in <span class="doxyComputerOutput">OldValRes</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span> must be a generic virtual register.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Addr</span> must be a generic virtual register with pointer type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span>, and <span class="doxyComputerOutput">Val</span> must be generic virtual registers of the same type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1620 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 1123 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a497e8884b8ae421c7dadff0f0eea5e3e">buildAtomicRMW</a>.</p>

</div>
</div>

### buildAtomicRMWUSubCond() {#a4b09525023b6ebfc6954493271dded49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildAtomicRMWUSubCond (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; OldValRes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Addr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Val, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; MMO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_USUB_COND Addr, Val, MMO</span>.</p>


<p>Atomically replace the value at <span class="doxyComputerOutput">Addr</span> with the original value minus <span class="doxyComputerOutput">Val</span> if the original value is greater than or equal to <span class="doxyComputerOutput">Val</span>, or leaves it unchanged otherwise. Puts the original value from <span class="doxyComputerOutput">Addr</span> in <span class="doxyComputerOutput">OldValRes</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span> must be a generic virtual register.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Addr</span> must be a generic virtual register with pointer type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span>, and <span class="doxyComputerOutput">Val</span> must be generic virtual registers of the same type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Definition at line 1680 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>

</div>
</div>

### buildAtomicRMWUSubSat() {#a17fe1c83d1fe58f743ec0d66f2073443}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildAtomicRMWUSubSat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; OldValRes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Addr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Val, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; MMO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_USUB_SAT Addr, Val, MMO</span>.</p>


<p>Atomically replace the value at <span class="doxyComputerOutput">Addr</span> with the original value minus <span class="doxyComputerOutput">Val</span>, with clamping to zero if the unsigned subtraction would overflow. Puts the original value from <span class="doxyComputerOutput">Addr</span> in <span class="doxyComputerOutput">OldValRes</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span> must be a generic virtual register.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Addr</span> must be a generic virtual register with pointer type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span>, and <span class="doxyComputerOutput">Val</span> must be generic virtual registers of the same type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Definition at line 1698 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>

</div>
</div>

### buildAtomicRMWXchg() {#af5df6737579f8493e9dbf21b3e042daa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildAtomicRMWXchg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> OldValRes, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Val, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; MMO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_XCHG Addr, Val, MMO</span>.</p>


<p>Atomically replace the value at <span class="doxyComputerOutput">Addr</span> with <span class="doxyComputerOutput">Val</span>. Puts the original value from <span class="doxyComputerOutput">Addr</span> in <span class="doxyComputerOutput">OldValRes</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span> must be a generic virtual register.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Addr</span> must be a generic virtual register with pointer type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span>, and <span class="doxyComputerOutput">Val</span> must be generic virtual registers of the same type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1465 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 1062 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a497e8884b8ae421c7dadff0f0eea5e3e">buildAtomicRMW</a>.</p>

</div>
</div>

### buildAtomicRMWXor() {#a0a35bae390b9e7d83ce0ef35512da4ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildAtomicRMWXor (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> OldValRes, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Val, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; MMO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">OldValRes&lt;def&gt; = G_ATOMICRMW_XOR Addr, Val, MMO</span>.</p>


<p>Atomically replace the value at <span class="doxyComputerOutput">Addr</span> with the bitwise xor of <span class="doxyComputerOutput">Val</span> and the original value. Puts the original value from <span class="doxyComputerOutput">Addr</span> in <span class="doxyComputerOutput">OldValRes</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span> must be a generic virtual register.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Addr</span> must be a generic virtual register with pointer type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">OldValRes</span>, and <span class="doxyComputerOutput">Val</span> must be generic virtual registers of the same type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1556 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 1099 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a497e8884b8ae421c7dadff0f0eea5e3e">buildAtomicRMW</a>.</p>

</div>
</div>

### buildBitcast() {#acf0f51041fbaaed06a39f2fe2686bb92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildBitcast (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_BITCAST <span class="doxyComputerOutput">Src</span>.</p>

<p>Definition at line 723 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a5457cbda7e9b1866c1c16af5ac330273">insertBitcasts</a>.</p>

</div>
</div>

### buildBitReverse() {#a828ddf4cfe2b05f70a6566d36b4804c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildBitReverse (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_BITREVERSE <span class="doxyComputerOutput">Src</span>.</p>

<p>Definition at line 2315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildBlockAddress() {#ae83cc330c36190cf8ee9618a28e9a300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildBlockAddress (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/blockaddress">BlockAddress</a> * BA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_BLOCK_ADDR <span class="doxyComputerOutput">BA</span>.</p>


<p>G_BLOCK_ADDR computes the address of a basic block.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register of a pointer type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1723 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 1178 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6eb17a3fc032cb29dbc1908f1d4ba046">llvm::MachineInstrBuilder::addBlockAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>.</p>

</div>
</div>

### buildBoolExt() {#a1e5b88856596e413494661b5fae9fc39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildBoolExt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op, bool IsFP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 738 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 523 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="#a5aafc4bc2c28b6cb5d9aeb319b186d11">getBoolExtOp</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>.</p>

</div>
</div>

### buildBoolExtInReg() {#a060616c6385361df8bd72cde315d4267}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildBoolExtInReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op, bool IsVector, bool IsFP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 744 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 530 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="#ae32b6e2213ad3119a124e6e0673a5898">buildCopy</a>, <a href="#afe73ac7a93f98c40c8fb66fce8fa4400">buildSExtInReg</a>, <a href="#a26edc3c3cae5a3f4d6ddd7f628b98c45">buildZExtInReg</a>, <a href="#a9ec04f3692b9601036d2d4477c4c3749">getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#ade3f0d8b35d67c43df9425bb730a9a7c">llvm::TargetSubtargetInfo::getTargetLowering</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa61af767c51a95e2dd0dff2001168755a145391af8fd5e5455ffa3170c2d701ce">llvm::TargetLoweringBase::UndefinedBooleanContent</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa61af767c51a95e2dd0dff2001168755a695a19c9c3ae14638be151add82755cb">llvm::TargetLoweringBase::ZeroOrNegativeOneBooleanContent</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa61af767c51a95e2dd0dff2001168755a0e2d72cfdcc49d2d189f440b3cc31dff">llvm::TargetLoweringBase::ZeroOrOneBooleanContent</a>.</p>

</div>
</div>

### buildBr() {#a0ae44597e21d583e46c8bdfa52e56fa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildBr (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert G_BR <span class="doxyComputerOutput">Dest</span>.</p>


<p>G_BR is an unconditional branch to <span class="doxyComputerOutput">Dest</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 821 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abf1febf2a98f588146548a3a485d3838">llvm::MachineInstrBuilder::addMBB</a> and <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a3a0acd458319c9256fa67a622bbfd9d6">removeImplicitFallthroughs</a>.</p>

</div>
</div>

### buildBrCond() {#a6e0f051c17bd6354aec061d308d80841}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildBrCond (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Tst, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert G_BRCOND <span class="doxyComputerOutput">Tst</span>, <span class="doxyComputerOutput">Dest</span>.</p>


<p>G_BRCOND is a conditional branch to <span class="doxyComputerOutput">Dest</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Tst</span> must be a generic virtual register with scalar type. At the beginning of legalization, this will be a single bit (s1). Targets with interesting flags registers may change this. For a wider type, whether the branch is taken must only depend on bit 0 (for now).</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The newly created instruction.</p></dd>
</dl>


<p>Declaration at line 835 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/srcop/#aba93d72255e1239b5209e416a1b7f199">llvm::SrcOp::addSrcToMIB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#a99fb11458708b57172b6b0df633fd4fc">llvm::SrcOp::getLLTTy</a> and <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a>.</p>

</div>
</div>

### buildBrIndirect() {#aecf67aca8d78d0136244799c4182e52f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildBrIndirect (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Tgt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert G_BRINDIRECT <span class="doxyComputerOutput">Tgt</span>.</p>


<p>G_BRINDIRECT is an indirect branch to <span class="doxyComputerOutput">Tgt</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Tgt</span> must be a generic virtual register with pointer type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 845 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad88e27102395957e457fed8e73a085cf">llvm::MachineInstrBuilder::addUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>.</p>

</div>
</div>

### buildBrJT() {#aaf1013659ccc9708197f76c0bd724936}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildBrJT (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> TablePtr, unsigned JTI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> IndexReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert G_BRJT <span class="doxyComputerOutput">TablePtr</span>, <span class="doxyComputerOutput">JTI</span>, <span class="doxyComputerOutput">IndexReg</span>.</p>


<p>G_BRJT is a jump table branch using a table base pointer <span class="doxyComputerOutput">TablePtr</span>, jump table index <span class="doxyComputerOutput">JTI</span> and index <span class="doxyComputerOutput">IndexReg</span></p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">TablePtr</span> must be a generic virtual register with pointer type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">JTI</span> must be a jump table index.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">IndexReg</span> must be a generic virtual register with pointer type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 858 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#aaa7ad3e87d858a3ed3b3dc8b05b70078">llvm::MachineInstrBuilder::addJumpTableIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad88e27102395957e457fed8e73a085cf">llvm::MachineInstrBuilder::addUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>.</p>

</div>
</div>

### buildBSwap() {#a4ef9ec8bbb1cbf1ad44e5039537ddfe3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildBSwap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_BSWAP <span class="doxyComputerOutput">Src0</span>.</p>

<p>Definition at line 1950 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildBuildVector() {#a60609bd46d38414e2c9e2334f9740727}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildBuildVector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_BUILD_VECTOR <span class="doxyComputerOutput">Op0</span>, ...</p>


<p>G_BUILD_VECTOR creates a vector value from multiple scalar registers.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>The entire register <span class="doxyComputerOutput">Res</span> (and no more) must be covered by the input scalar registers.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>The type of all <span class="doxyComputerOutput">Ops</span> registers must be identical.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1090 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 720 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a> and <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/csemirbuilder/#a9c2e15b867893ec15cb49acfbb38e542">llvm::CSEMIRBuilder::buildInstr</a>.</p>

</div>
</div>

### buildBuildVectorConstant() {#a96b7ed72c9782cd69b2b9b341cf73112}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildBuildVectorConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &gt; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_BUILD_VECTOR <span class="doxyComputerOutput">Op0</span>, ... where each OpN is built with G_CONSTANT.</p>

<p>Declaration at line 1095 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 730 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="#af751c28a69e1d07e19dad11e4e26a70d">buildConstant</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a49a5649c0de9dee3dacbab3019872923">llvm::DstOp::getLLTTy</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/csemirbuilder/#a9c2e15b867893ec15cb49acfbb38e542">llvm::CSEMIRBuilder::buildInstr</a>.</p>

</div>
</div>

### buildBuildVectorTrunc() {#a7acf8a5ebb4b351a451a2d63faf13294}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildBuildVectorTrunc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_BUILD_VECTOR_TRUNC <span class="doxyComputerOutput">Op0</span>, ...</p>


<p>G_BUILD_VECTOR_TRUNC creates a vector value from multiple scalar registers which have types larger than the destination vector element type, and truncates the values to fit.</p>


<p>If the operands given are already the same size as the vector elt type, then this method will instead create a G_BUILD_VECTOR instruction.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>The type of all <span class="doxyComputerOutput">Ops</span> registers must be identical.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 747 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a49a5649c0de9dee3dacbab3019872923">llvm::DstOp::getLLTTy</a> and <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a>.</p>

</div>
</div>

### buildCast() {#a3493ece271aff0f2c3d162494e3fcc81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildCast (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert an appropriate cast between two registers of equal size.</p>

<p>Declaration at line 812 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 595 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae32b6e2213ad3119a124e6e0673a5898">buildCopy</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#acd23ed05c97e269d0d268636c7d6a6b7">llvm::LLT::isPointerOrPointerVector</a>.</p>


<p>Referenced by <a href="#a2f52fec4aa17c3066db14a8d4717469d">buildExtract</a> and <a href="#aaf34795e0fa82f3edac1a235f50da4c1">buildInsert</a>.</p>

</div>
</div>

### buildConcatVectors() {#a46cfa445be514255440f986c4b7b496f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildConcatVectors (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_CONCAT_VECTORS <span class="doxyComputerOutput">Op0</span>, ...</p>


<p>G_CONCAT_VECTORS creates a vector from the concatenation of 2 or more vectors.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>The entire register <span class="doxyComputerOutput">Res</span> (and no more) must be covered by the input registers.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>The type of all source operands must be identical.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 798 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a> and <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#ae26a44292d42d576349e053e3497c18f">anonymous{AArch64PreLegalizerCombiner.cpp}::applyExtAddvToUdotAddv</a>.</p>

</div>
</div>

### buildConstant() {#af751c28a69e1d07e19dad11e4e26a70d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> &amp; Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_CONSTANT <span class="doxyComputerOutput">Val</span>.</p>


<p>G_CONSTANT is an integer constant with the specified size and value. <span class="doxyComputerOutput">Val</span> will be extended or truncated to the size of <span class="doxyComputerOutput">Reg</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register with scalar or pointer type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The newly created instruction.</p></dd>
</dl>


<p>Declaration at line 871 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a3348f4e81264ccfe03832f141fdf44a3">llvm::MachineInstrBuilder::addCImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a45141d649d02a2ed17b51b5419ee884d">llvm::DstOp::addDefToMIB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="#a55bde2ba6aacac745a29a7e50c6be007">buildSplatBuildVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#ab240d0d30dfa9b392ef9d813f3f9e4be">llvm::ConstantInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a49a5649c0de9dee3dacbab3019872923">llvm::DstOp::getLLTTy</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a50bbcbf690dd0de0a3f4abe2dd51fb55">anonymous{AArch64PostLegalizerLowering.cpp}::applyAdjustICmpImmAndPred</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#acaf0ebafd584479c2c6a1a782ff149f9">llvm::CombinerHelper::applyCombineMulToShl</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#ab5aa406f974e74967376237df439846a">anonymous{AArch64PostLegalizerLowering.cpp}::applyEXT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#ae26a44292d42d576349e053e3497c18f">anonymous{AArch64PreLegalizerCombiner.cpp}::applyExtAddvToUdotAddv</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#a2bc19898d48a85699db2ea0cdb8ec55f">anonymous{AArch64PreLegalizerCombiner.cpp}::applyFConstantToConstant</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#adf82bf97d32fede84099257eb720a1a2">anonymous{AArch64PostLegalizerLowering.cpp}::applyFullRev</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#a9bddeb3377e91345c52d28658dad61a3">anonymous{AArch64PreLegalizerCombiner.cpp}::applyICmpRedundantTrunc</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a79c39eb0fd06bbc443b66f4b6d6711af">anonymous{AArch64PostLegalizerLowering.cpp}::applyINS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a580c192e2fc41ab69e61d087027ceabf">anonymous{AArch64PostLegalizerLowering.cpp}::applyNonConstInsert</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a8cd84da3b005d88c0f1b19d868e0a2b3">llvm::CombinerHelper::applyPtrAddImmedChain</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a976bf3034ffa13d0fd59454e588e316a">anonymous{AArch64PostLegalizerLowering.cpp}::applyVAshrLshrImm</a>, <a href="#a96b7ed72c9782cd69b2b9b341cf73112">buildBuildVectorConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/csemirbuilder/#af20c06f6ef57cddf624f531efbaf69e7">llvm::CSEMIRBuilder::buildConstant</a>, <a href="#ab952b8b71fdba5baaf6a083e06d71da2">buildConstant</a>, <a href="#afdce4b9880a0aed02fe487da6a613cbd">buildConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#affb04c244423615aa0df24ee36f2de20">llvm::SPIRVGlobalRegistry::buildConstantInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvlegalizerinfo-cpp/#a45e6e22e05efa275135c8ae32f60da40">buildDefaultVLOps</a>, <a href="#a7e58ecea881b2ea06fee315563860e39">buildExtractVectorElementConstant</a>, <a href="#a010032df630a417383fa44deee43ac0c">buildLoadFromOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#afc84382af091d9a0de9586212e16a195">buildLogBase2</a>, <a href="#af6aed1d3b2cf7133b73cf8bfa5122186">buildMaskLowPtrBits</a>, <a href="#a66aef31356eb4467a34fbcb72f1649ad">buildNeg</a>, <a href="#a16532d0d8fb47080714810131b45b75b">buildNot</a>, <a href="#a43b43271e5bcbbc5cc620b4dfa94937a">buildShuffleSplat</a>, <a href="#a26edc3c3cae5a3f4d6ddd7f628b98c45">buildZExtInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aa386a0afb3210b56c30181f93a434ed3">createAtomicLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a2f1d26ea9bced931d104b4dd8b26775f">getMemsetValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a2aeed55e4456de4086b3592eb92dc2e2">llvm::ARMLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a867592b1a0963211ea415ea436a976e5">llvm::MipsLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#a1ddebf0db857b4b9fd7004511b7eb393">llvm::RISCVLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#aa48b853fae2f40e3e483078a944ab8d1">llvm::AArch64LegalizerInfo::legalizeIntrinsic</a>, <a href="#a0f2bb4d63ad6914f3783967bf881a14b">materializePtrAdd</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#ac9f5ed1e7ae99c336e8ae9b4ccf10b50">llvm::AMDGPUCallLowering::passSpecialInputs</a>.</p>

</div>
</div>

### buildConstant() {#afdce4b9880a0aed02fe487da6a613cbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, int64_t Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_CONSTANT <span class="doxyComputerOutput">Val</span>.</p>


<p>G_CONSTANT is an integer constant with the specified size and value.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register with scalar type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The newly created instruction.</p></dd>
</dl>


<p>Declaration at line 882 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="#af751c28a69e1d07e19dad11e4e26a70d">buildConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="#a120dbb8d0a1ad4437456001a302a1da7">getContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/evaluator-cpp/#a92efb02157b6836e1232c577d34678d6">getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a49a5649c0de9dee3dacbab3019872923">llvm::DstOp::getLLTTy</a>, <a href="#a9ec04f3692b9601036d2d4477c4c3749">getMF</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargettransforminfo-cpp/#a69eeffbc38c079195008fbfb5aaad0b9">getScalarSizeInBits</a>.</p>

</div>
</div>

### buildConstant() {#ab952b8b71fdba5baaf6a083e06d71da2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 883 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="#af751c28a69e1d07e19dad11e4e26a70d">buildConstant</a>, <a href="#a120dbb8d0a1ad4437456001a302a1da7">getContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/evaluator-cpp/#a92efb02157b6836e1232c577d34678d6">getFunction</a> and <a href="#a9ec04f3692b9601036d2d4477c4c3749">getMF</a>.</p>

</div>
</div>

### buildConstantPool() {#a1da8389b4eb951b11309c28ad492e8d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildConstantPool (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, unsigned Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_CONSTANT_POOL <span class="doxyComputerOutput">Idx</span>.</p>


<p>G_CONSTANT_POOL materializes the address of an object in the constant pool.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register with pointer type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 502 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dstop/#a45141d649d02a2ed17b51b5419ee884d">llvm::DstOp::addDefToMIB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a49a5649c0de9dee3dacbab3019872923">llvm::DstOp::getLLTTy</a> and <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a8f8ee7977675d9e8cdded7bda420b96e">emitLoadFromConstantPool</a>.</p>

</div>
</div>

### buildConstantPtrAuth() {#aff3c145b6d12a00e7432953b1c454ebc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildConstantPtrAuth (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantptrauth">ConstantPtrAuth</a> * CPA, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> AddrDisc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert G_PTRAUTH_GLOBAL_VALUE.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 903 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dstop/#a45141d649d02a2ed17b51b5419ee884d">llvm::DstOp::addDefToMIB</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/constantptrauth/#aa847cae058691cafe0cbc8f2eecb331a">llvm::ConstantPtrAuth::getDiscriminator</a>, <a href="/web-llvm/docs/api/classes/llvm/constantptrauth/#a9c3928485f63866f20e21c67776300e7">llvm::ConstantPtrAuth::getKey</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a> and <a href="/web-llvm/docs/api/classes/llvm/constantint/#ac09a21c371a9c535cbc13e8f82503aec">llvm::ConstantInt::getZExtValue</a>.</p>

</div>
</div>

### buildConstDbgValue() {#a6ab34a535b1441b48a0ede2c2aa6fb98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildConstDbgValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> &amp; C, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Variable, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Expr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert a DBG_VALUE instructions specifying that <span class="doxyComputerOutput">Variable</span> is given by <span class="doxyComputerOutput">C</span> (suitably modified by <span class="doxyComputerOutput">Expr</span>).</p>

<p>Declaration at line 451 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/value/#aa1b0638c63ba711320b3bb9c69367ed6">llvm::Value::addMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae04499daa8807ddb4d00e7ed18b1698f">buildInstrNoInsert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a93ab05c4fb48bd5e87965bef6ec9ac2e">getDL</a>, <a href="#a06dc2f24e1f4dea357bf6c646f5b2607">insertInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#a103d8cfe62c1651cd70e181746f8a840">isValid</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>.</p>

</div>
</div>

### buildCopy() {#ae32b6e2213ad3119a124e6e0673a5898}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildCopy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = COPY <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a>.</p>


<p>Register-to-register COPY sets <span class="doxyComputerOutput">Res</span> to <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 914 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#ab5aa406f974e74967376237df439846a">anonymous{AArch64PostLegalizerLowering.cpp}::applyEXT</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp/#af5f0f04b137494bbf8fb56286dea2762">buildAnyextOrCopy</a>, <a href="#a060616c6385361df8bd72cde315d4267">buildBoolExtInReg</a>, <a href="#a3493ece271aff0f2c3d162494e3fcc81">buildCast</a>, <a href="#ad68c3cafb2cc7ee28ee3c7dff2a45f2e">buildDeleteTrailingVectorElements</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a881c9e75128e7e943b6d8f33606ccc74">llvm::SPIRVGlobalRegistry::buildGlobalVariable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#aafb37937e5f21c12443bd5278264d08b">fixupPHIOpBanks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab28508dbb1f9996154ae13f70fa4f2e2">llvm::genWorkgroupQuery</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a755cbbd3d8b7e1f3e6659ede9cd88f94">llvm::AMDGPUCallLowering::handleImplicitCallArguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp/#a133ddcbd001fd6de4f055542a6a95595">handleMustTailForwardedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#aa48b853fae2f40e3e483078a944ab8d1">llvm::AArch64LegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a5344895d462c34e2c90e930471d8e4d9">llvm::MipsCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a3a0c76714485f4713fed0661f961b09a">llvm::MipsCallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasmlowering/#a1c9cd272afbe2a9aaca46369f9e61b79">llvm::InlineAsmLowering::lowerInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#a010cf32a5c68f9701c57d7a3172f1b3f">llvm::AArch64CallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/x86calllowering/#ace03d9ed2825d1401093a441f164ecdf">llvm::X86CallLowering::lowerReturn</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#a933b079df28c77f3850ed1edf94c6ed8">selectCopy</a>.</p>

</div>
</div>

### buildCTLZ() {#a6a31c8e33dcb4c2c60d965227c227e8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildCTLZ (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_CTLZ <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Src0</span>.</p>

<p>Definition at line 1930 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#afc84382af091d9a0de9586212e16a195">buildLogBase2</a>.</p>

</div>
</div>

### buildCTLZ\_ZERO\_UNDEF() {#a4fe52c440f33a8895fb01730017de4be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildCTLZ_ZERO_UNDEF (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_CTLZ_ZERO_UNDEF <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Src0</span>.</p>

<p>Definition at line 1935 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildCTPOP() {#a9607e5a365ae4ce30b73b802f590bb21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildCTPOP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_CTPOP <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Src0</span>.</p>

<p>Definition at line 1925 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildCTTZ() {#a1c1ac6707657ae4a0b6509e7857c1c68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildCTTZ (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_CTTZ <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Src0</span>.</p>

<p>Definition at line 1940 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildCTTZ\_ZERO\_UNDEF() {#a80194aed09e8b4c04c228940ff2a56a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildCTTZ_ZERO_UNDEF (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_CTTZ_ZERO_UNDEF <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Src0</span>.</p>

<p>Definition at line 1945 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildDbgLabel() {#aadc416be0ccae999a06a3a9452bf8d37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildDbgLabel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Label)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert a DBG_LABEL instructions specifying that <span class="doxyComputerOutput">Label</span> is given.</p>


<p>Convert "llvm.dbg.label Label" to "DBG_LABEL Label".</p>


<p>Declaration at line 457 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### buildDeleteTrailingVectorElements() {#ad68c3cafb2cc7ee28ee3c7dff2a45f2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildDeleteTrailingVectorElements (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert a, b, ..., x, y, z = G_UNMERGE_VALUES <span class="doxyComputerOutput">Op0</span> <span class="doxyComputerOutput">Res</span> = G_BUILD_VECTOR a, b, ..., x.</p>


<p>Delete trailing elements in <span class="doxyComputerOutput">Op0</span> to match number of elements in <span class="doxyComputerOutput">Res</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> and <span class="doxyComputerOutput">Op0</span> must be generic virtual registers with vector type, same vector element type and Op0 must have more elements then Res.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created build vector instr.</p></dd>
</dl>


<p>Declaration at line 588 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae32b6e2213ad3119a124e6e0673a5898">buildCopy</a>, <a href="#a7075ef788cb3dea0ea239c1a6830734c">buildMergeLikeInstr</a>, <a href="#a1e9e055fc19307bc3c7c1be6ccd36812">buildUnmerge</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a49a5649c0de9dee3dacbab3019872923">llvm::DstOp::getLLTTy</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#a99fb11458708b57172b6b0df633fd4fc">llvm::SrcOp::getLLTTy</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#ad5f891a5d9822c7aab1b8bb0190a522f">llvm::DstOp::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### buildDirectDbgValue() {#a92bad84c9e323ab0a96d8d8bbb22d149}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildDirectDbgValue (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Variable, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Expr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert a DBG_VALUE instruction expressing the fact that the associated <span class="doxyComputerOutput">Variable</span> lives in <span class="doxyComputerOutput">Reg</span> (suitably modified by <span class="doxyComputerOutput">Expr</span>).</p>

<p>Declaration at line 433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="#a93ab05c4fb48bd5e87965bef6ec9ac2e">getDL</a>, <a href="#a9ec04f3692b9601036d2d4477c4c3749">getMF</a>, <a href="#a35384c47e5ca9690216b1aa8fed5a8c9">getTII</a>, <a href="#a06dc2f24e1f4dea357bf6c646f5b2607">insertInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#a103d8cfe62c1651cd70e181746f8a840">isValid</a>.</p>

</div>
</div>

### buildDynStackAlloc() {#ab00eba007903e9b4a69440782cd7c9c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildDynStackAlloc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_DYN_STACKALLOC <span class="doxyComputerOutput">Size</span>, <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></span>.</p>


<p>G_DYN_STACKALLOC does a dynamic stack allocation and writes the address of the allocated memory into <span class="doxyComputerOutput">Res</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register with pointer type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dstop/#a45141d649d02a2ed17b51b5419ee884d">llvm::DstOp::addDefToMIB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a49a5649c0de9dee3dacbab3019872923">llvm::DstOp::getLLTTy</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>

</div>
</div>

### buildExtOrTrunc() {#ab8da4d08f2c0875e9623bb712aa64303}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildExtOrTrunc (unsigned ExtOpc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = <span class="doxyComputerOutput">ExtOpc</span>, <span class="doxyComputerOutput">Res</span> = G_TRUNC <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>, or <span class="doxyComputerOutput">Res</span> = COPY <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> depending on the differing sizes of <span class="doxyComputerOutput">Res</span> and <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>.</p>


<p>///</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register with scalar or vector type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> must be a generic virtual register with scalar or vector type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The newly created instruction.</p></dd>
</dl>


<p>Declaration at line 802 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 547 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a49a5649c0de9dee3dacbab3019872923">llvm::DstOp::getLLTTy</a> and <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a>.</p>


<p>Referenced by <a href="#a40c85353b0cd7cfdc7d8f8b364758c15">buildAnyExtOrTrunc</a>, <a href="#a437e7190e38ee7e10daee0f4909d5066">buildSExtOrTrunc</a>, <a href="#a7ac5295bdfdd480a2c66ee54273ebe21">buildZExtOrTrunc</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#aa48b853fae2f40e3e483078a944ab8d1">llvm::AArch64LegalizerInfo::legalizeIntrinsic</a>.</p>

</div>
</div>

### buildExtract() {#a2f52fec4aa17c3066db14a8d4717469d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildExtract (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src, uint64_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res0, ... = G_EXTRACT Src, Idx0</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> and <span class="doxyComputerOutput">Src</span> must be generic virtual registers.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1018 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 616 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3493ece271aff0f2c3d162494e3fcc81">buildCast</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a69fb30748f1b3e8a0affd486a9f59f6d">llvm::LLT::isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a2c32a92de16156166b3fd4de261d20a0">llvm::extractParts</a>.</p>

</div>
</div>

### buildExtractSubvector() {#aeb07fff3cb0ad02bf88651e9388777de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildExtractSubvector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src, unsigned Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res = G_EXTRACT_SUBVECTOR Src, Idx0</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> and <span class="doxyComputerOutput">Src</span> must be generic virtual registers with vector type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 965 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildExtractVectorElement() {#a7835e6cd3f1b340d3bb617304038d744}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildExtractVectorElement (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_EXTRACT_VECTOR_ELT <span class="doxyComputerOutput">Val</span>, <span class="doxyComputerOutput">Idx</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register with scalar type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Val</span> must be a generic virtual register with vector type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Idx</span> must be a generic virtual register with scalar type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1392 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 979 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a79c39eb0fd06bbc443b66f4b6d6711af">anonymous{AArch64PostLegalizerLowering.cpp}::applyINS</a> and <a href="#a7e58ecea881b2ea06fee315563860e39">buildExtractVectorElementConstant</a>.</p>

</div>
</div>

### buildExtractVectorElementConstant() {#a7e58ecea881b2ea06fee315563860e39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildExtractVectorElementConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int Idx)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_EXTRACT_VECTOR_ELT <span class="doxyComputerOutput">Val</span>, <span class="doxyComputerOutput">Idx</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register with scalar type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Val</span> must be a generic virtual register with vector type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The newly created instruction.</p></dd>
</dl>


<p>Definition at line 1375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="#af751c28a69e1d07e19dad11e4e26a70d">buildConstant</a>, <a href="#a7835e6cd3f1b340d3bb617304038d744">buildExtractVectorElement</a>, <a href="#aeb6d0a9254bc3183046873436fc7c12e">getDataLayout</a>, <a href="#a9ec04f3692b9601036d2d4477c4c3749">getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7be7c6dd92efc0d6f866d4a3b433eed0">llvm::MVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#ade3f0d8b35d67c43df9425bb730a9a7c">llvm::TargetSubtargetInfo::getTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a2dd702dca28f51ec1137faed5d0e5837">llvm::TargetLoweringBase::getVectorIdxTy</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>

</div>
</div>

### buildFAbs() {#a2161bd545c3baa8bfaa0d7b44ecf38c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildFAbs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FABS <span class="doxyComputerOutput">Op0</span>.</p>

<p>Definition at line 2003 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildFAdd() {#afc51b7318978bc4878cce41bdf1774db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildFAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FADD <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>.</p>

<p>Definition at line 1955 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildFCanonicalize() {#afe0950de33581b21ef3c56db5f4382c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildFCanonicalize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_FCANONICALIZE <span class="doxyComputerOutput">Src0</span>.</p>

<p>Definition at line 2010 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildFCmp() {#afb3340c638c09709ce5766dcf672500d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildFCmp (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert a <span class="doxyComputerOutput">Res</span> = G_FCMP <span class="doxyComputerOutput">Pred<span class="doxyComputerOutput">Op0</span>,</span> <span class="doxyComputerOutput">Op1</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register with scalar or vector type. Typically this starts as s1 or &lt;N x s1&gt;.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Op0</span> and Op1 must be generic virtual registers with the same number of elements as <span class="doxyComputerOutput">Res</span> (or scalar, if <span class="doxyComputerOutput">Res</span> is scalar).</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Pred</span> must be a floating-point predicate.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 928 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildFConstant() {#a81a7959d3e7f624343ecdf6905e251dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildFConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantfp">ConstantFP</a> &amp; Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FCONSTANT <span class="doxyComputerOutput">Val</span>.</p>


<p>G_FCONSTANT is a floating-point constant with the specified size and value.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register with scalar type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The newly created instruction.</p></dd>
</dl>


<p>Declaration at line 894 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a45141d649d02a2ed17b51b5419ee884d">llvm::DstOp::addDefToMIB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a95c7b5ed23471212aeaba1eee6501261">llvm::MachineInstrBuilder::addFPImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="#a55bde2ba6aacac745a29a7e50c6be007">buildSplatBuildVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a49a5649c0de9dee3dacbab3019872923">llvm::DstOp::getLLTTy</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a643f8cd038a6fa41604fe8e3df11f977">llvm::APFloat::getSemantics</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a3536ced38fb9e6404151cfa03b4531dc">llvm::APFloatBase::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a32aa14715eeb813d764fcf20f161f0a1">llvm::ConstantFP::getValueAPF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/csemirbuilder/#ae1fe7f5085d203a5984b2450f907b239">llvm::CSEMIRBuilder::buildFConstant</a>, <a href="#aa28f164b227803f0fef41094366c2dca">buildFConstant</a>, <a href="#a4265ff404073d12b765bc9fee4e7f186">buildFConstant</a> and <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a867592b1a0963211ea415ea436a976e5">llvm::MipsLegalizerInfo::legalizeCustom</a>.</p>

</div>
</div>

### buildFConstant() {#a4265ff404073d12b765bc9fee4e7f186}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildFConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, double Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 897 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="#a81a7959d3e7f624343ecdf6905e251dd">buildFConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee5a9adb5b8a88c8913aed9c85e5a52">llvm::getAPFloatFromSize</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a49a5649c0de9dee3dacbab3019872923">llvm::DstOp::getLLTTy</a>, <a href="#a9ec04f3692b9601036d2d4477c4c3749">getMF</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>.</p>

</div>
</div>

### buildFConstant() {#aa28f164b227803f0fef41094366c2dca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildFConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 898 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="#a81a7959d3e7f624343ecdf6905e251dd">buildFConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a> and <a href="#a9ec04f3692b9601036d2d4477c4c3749">getMF</a>.</p>

</div>
</div>

### buildFCopysign() {#ac6b47b51bfacb6c594a3c6b8472202c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildFCopysign (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FCOPYSIGN <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>.</p>

<p>Definition at line 2076 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildFDiv() {#a6f3162ab8134a05797e7a1d21889d880}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildFDiv (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FDIV <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>.</p>

<p>Definition at line 1976 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildFence() {#a21f358f36e1ae7fc91568266264f760e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildFence (unsigned Ordering, unsigned Scope)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">G_FENCE Ordering, Scope</span>.</p>

<p>Declaration at line 1703 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 1159 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a> and <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildFExp2() {#a5849bcf7d4b148009464f4a8b7d3d367}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildFExp2 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_FEXP2 <span class="doxyComputerOutput">Src</span>.</p>

<p>Definition at line 2042 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildFFloor() {#ad5b247bb13afd8a0d31abedb522c7f46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildFFloor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = GFFLOOR <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>.</p>

<p>Definition at line 2024 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildFFrexp() {#ad6391767e768c022d095516b3b86f3ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildFFrexp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Fract, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Exp, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Fract</span>, <span class="doxyComputerOutput">Exp</span> = G_FFREXP <span class="doxyComputerOutput">Src</span>.</p>

<p>Definition at line 2063 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildFIDbgValue() {#ab107810eccfb0e46e47348ea9ef8d0ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildFIDbgValue (int FI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Variable, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Expr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert a DBG_VALUE instruction expressing the fact that the associated <span class="doxyComputerOutput">Variable</span> lives in the stack slot specified by <span class="doxyComputerOutput">FI</span> (suitably modified by <span class="doxyComputerOutput">Expr</span>).</p>

<p>Declaration at line 446 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae04499daa8807ddb4d00e7ed18b1698f">buildInstrNoInsert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a93ab05c4fb48bd5e87965bef6ec9ac2e">getDL</a>, <a href="#a06dc2f24e1f4dea357bf6c646f5b2607">insertInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#a103d8cfe62c1651cd70e181746f8a840">isValid</a>.</p>

</div>
</div>

### buildFLdexp() {#a081e4f97d236d1d1c4e6599b7530498d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildFLdexp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_FLDEXP <span class="doxyComputerOutput">Src0</span>, <span class="doxyComputerOutput">Src1</span>.</p>

<p>Definition at line 2056 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildFLog() {#a914ca92cbc07e52a5115a023dc474f08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildFLog (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_FLOG <span class="doxyComputerOutput">Src</span>.</p>

<p>Definition at line 2030 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildFLog2() {#a1d453180d499c717c2d4a189e7615b48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildFLog2 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_FLOG2 <span class="doxyComputerOutput">Src</span>.</p>

<p>Definition at line 2036 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildFMA() {#a23b0488d15477183dec5de35d9082ef7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildFMA (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src2, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FMA <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>, <span class="doxyComputerOutput">Op2</span>.</p>

<p>Definition at line 1983 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildFMAD() {#a8d77ec102570efb92c2b7571ac17cf4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildFMAD (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src2, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FMAD <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>, <span class="doxyComputerOutput">Op2</span>.</p>

<p>Definition at line 1990 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildFMaxNum() {#aabf1fb6f032d501430f9f917739aaf11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildFMaxNum (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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



<p>Definition at line 1835 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildFMaxNumIEEE() {#ad32b91bbb8f081b9c3d3040697dc5eac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildFMaxNumIEEE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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



<p>Definition at line 1847 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildFMinNum() {#aad3884fe393aca6b2c9aa240a2bcdea4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildFMinNum (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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



<p>Definition at line 1829 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildFMinNumIEEE() {#a226e1d000521c2ff3964171f4f78ab5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildFMinNumIEEE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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



<p>Definition at line 1841 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildFMul() {#a04873b91eebbedfe4fd28d54029068d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildFMul (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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



<p>Definition at line 1822 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildFNeg() {#ac939f3c7fdf6c976421d61564d078506}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildFNeg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FNEG <span class="doxyComputerOutput">Op0</span>.</p>

<p>Definition at line 1997 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildFPExt() {#a14b6de2cb8956f133042a43a1f888efe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildFPExt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FPEXT <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>.</p>

<p>Definition at line 707 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildFPow() {#a3f2727e87d9863c60b67b7d08b05d2e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildFPow (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_FPOW <span class="doxyComputerOutput">Src0</span>, <span class="doxyComputerOutput">Src1</span>.</p>

<p>Definition at line 2048 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildFPTOSI() {#a03241215374b8ba88272333652a4a151}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildFPTOSI (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FPTOSI <span class="doxyComputerOutput">Src0</span>.</p>

<p>Definition at line 2097 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildFPTOSI\_SAT() {#a170e74a42d89ea7a0b8e0b8634afa404}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildFPTOSI_SAT (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FPTOSI_SAT <span class="doxyComputerOutput">Src0</span>.</p>

<p>Definition at line 2107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildFPTOUI() {#a3bb6c93f088c2df4bcb58e6f677e1213}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildFPTOUI (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FPTOUI <span class="doxyComputerOutput">Src0</span>.</p>

<p>Definition at line 2092 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildFPTOUI\_SAT() {#a00ac61b8d79a357bd578193be5f15454}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildFPTOUI_SAT (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FPTOUI_SAT <span class="doxyComputerOutput">Src0</span>.</p>

<p>Definition at line 2102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildFPTrunc() {#ad84b765997ad4d3bb1ca3e9393d70ab8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildFPTrunc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FPTRUNC <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>.</p>


<p>G_FPTRUNC converts a floating-point value into one with a smaller type.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register with scalar or vector type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> must be a generic virtual register with scalar or vector type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be smaller than <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span></p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 915 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a867592b1a0963211ea415ea436a976e5">llvm::MipsLegalizerInfo::legalizeCustom</a>.</p>

</div>
</div>

### buildFrameIndex() {#a92664cdbeb0b24030809439993ac271d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildFrameIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, int Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FRAME_INDEX <span class="doxyComputerOutput">Idx</span>.</p>


<p>G_FRAME_INDEX materializes the address of an alloca value or other stack-based object.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register with pointer type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 479 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dstop/#a45141d649d02a2ed17b51b5419ee884d">llvm::DstOp::addDefToMIB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a49a5649c0de9dee3dacbab3019872923">llvm::DstOp::getLLTTy</a> and <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a580c192e2fc41ab69e61d087027ceabf">anonymous{AArch64PostLegalizerLowering.cpp}::applyNonConstInsert</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a1b22f5dbcd629f145563ba79bcb7ce9b">llvm::CallLowering::insertSRetOutgoingArgument</a> and <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a3a0c76714485f4713fed0661f961b09a">llvm::MipsCallLowering::lowerFormalArguments</a>.</p>

</div>
</div>

### buildFreeze() {#a08361fe1409d7e2a9b96b0cabb918383}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildFreeze (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_FREEZE <span class="doxyComputerOutput">Src</span>.</p>

<p>Definition at line 1711 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildFSincos() {#adaa44dab2084014833b3744dfa291c89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildFSincos (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Sin, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Cos, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Sin</span>, <span class="doxyComputerOutput">Cos</span> = G_FSINCOS <span class="doxyComputerOutput">Src</span>.</p>

<p>Definition at line 2070 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildFSub() {#a02d0daf870f6458a98b61f4b82a399c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildFSub (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FSUB <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>.</p>

<p>Definition at line 1969 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a867592b1a0963211ea415ea436a976e5">llvm::MipsLegalizerInfo::legalizeCustom</a>.</p>

</div>
</div>

### buildGetFPEnv() {#ac69ef19d33fd455e8684cb53be2e46bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildGetFPEnv (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_GET_FPENV.</p>

<p>Definition at line 2320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a2aeed55e4456de4086b3592eb92dc2e2">llvm::ARMLegalizerInfo::legalizeCustom</a>.</p>

</div>
</div>

### buildGetFPMode() {#a23dbfe8493962b776dd1635121d87cd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildGetFPMode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_GET_FPMODE.</p>

<p>Definition at line 2335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildGlobalValue() {#a0ac2ceaa32ba0511bb9e14e6edfbc329}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildGlobalValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_GLOBAL_VALUE <span class="doxyComputerOutput">GV</span>.</p>


<p>G_GLOBAL_VALUE materializes the address of the specified global into <span class="doxyComputerOutput">Res</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register with pointer type in the same address space as <span class="doxyComputerOutput">GV</span>.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 491 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dstop/#a45141d649d02a2ed17b51b5419ee884d">llvm::DstOp::addDefToMIB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxaliasanalysis-cpp/#af6ab6e89a7e272521d7641859805a0ba">getAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8aeced5e71d2589fa3e9791043af5cb">llvm::PointerType::getAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a49a5649c0de9dee3dacbab3019872923">llvm::DstOp::getLLTTy</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a913a5d4b2cddde762446bd494e81a3f2">llvm::GlobalValue::getType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucalllowering-cpp/#a0f19540db0c8b48eebad9481053dc719">addCallTargetOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af5462628f10dea9944615cd509dd3634">llvm::CallLowering::lowerCall</a> and <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a5344895d462c34e2c90e930471d8e4d9">llvm::MipsCallLowering::lowerCall</a>.</p>

</div>
</div>

### buildICmp() {#a3a618c7b84d45b5e188f6a7e4305ee39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildICmp (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert a <span class="doxyComputerOutput">Res</span> = G_ICMP <span class="doxyComputerOutput">Pred</span>, <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register with scalar or vector type. Typically this starts as s1 or &lt;N x s1&gt;.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Op0</span> and Op1 must be generic virtual registers with the same number of elements as <span class="doxyComputerOutput">Res</span>. If <span class="doxyComputerOutput">Res</span> is a scalar, <span class="doxyComputerOutput">Op0</span> must be either a scalar or pointer.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Pred</span> must be an integer predicate.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 920 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af62f51194838248f650985e8299d7a97">llvm::buildAtomicCompareExchangeInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2947a09647c5d7fc7429c90d93fd2f17">llvm::generateGroupInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab28508dbb1f9996154ae13f70fa4f2e2">llvm::genWorkgroupQuery</a>, <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a2aeed55e4456de4086b3592eb92dc2e2">llvm::ARMLegalizerInfo::legalizeCustom</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#a1ddebf0db857b4b9fd7004511b7eb393">llvm::RISCVLegalizerInfo::legalizeCustom</a>.</p>

</div>
</div>

### buildIndirectDbgValue() {#a5a76abb6dd3946ca5c9cd6e8f341d63c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildIndirectDbgValue (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Variable, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Expr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert a DBG_VALUE instruction expressing the fact that the associated <span class="doxyComputerOutput">Variable</span> lives in memory at <span class="doxyComputerOutput">Reg</span> (suitably modified by <span class="doxyComputerOutput">Expr</span>).</p>

<p>Declaration at line 439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="#a93ab05c4fb48bd5e87965bef6ec9ac2e">getDL</a>, <a href="#a9ec04f3692b9601036d2d4477c4c3749">getMF</a>, <a href="#a35384c47e5ca9690216b1aa8fed5a8c9">getTII</a>, <a href="#a06dc2f24e1f4dea357bf6c646f5b2607">insertInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#a103d8cfe62c1651cd70e181746f8a840">isValid</a>.</p>

</div>
</div>

### buildInsert() {#aaf34795e0fa82f3edac1a235f50da4c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildInsert (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op, unsigned Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 806 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3493ece271aff0f2c3d162494e3fcc81">buildCast</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a49a5649c0de9dee3dacbab3019872923">llvm::DstOp::getLLTTy</a> and <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a>.</p>

</div>
</div>

### buildInsertSubvector() {#a33a09195e1324b12063bf4d35c646066}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildInsertSubvector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1, unsigned Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res = G_INSERT_SUBVECTOR Src0, Src1, Idx</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span>, <span class="doxyComputerOutput">Src0</span>, and <span class="doxyComputerOutput">Src1</span> must be generic virtual registers with vector type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 957 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildInsertVectorElement() {#aca31191486506a279715dd3bf677d75f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildInsertVectorElement (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Elt, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_INSERT_VECTOR_ELT <span class="doxyComputerOutput">Val</span>, <span class="doxyComputerOutput">Elt</span>, <span class="doxyComputerOutput">Idx</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> and <span class="doxyComputerOutput">Val</span> must be a generic virtual register</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Elt</span> and <span class="doxyComputerOutput">Idx</span> must be a generic virtual register with scalar type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 973 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a79c39eb0fd06bbc443b66f4b6d6711af">anonymous{AArch64PostLegalizerLowering.cpp}::applyINS</a> and <a href="#a43b43271e5bcbbc5cc620b4dfa94937a">buildShuffleSplat</a>.</p>

</div>
</div>

### buildInstr() {#a8bc92b8a902afb7675480ecc729a66d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildInstr (unsigned Opcode)</td>
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

<p>Build and insert &lt;empty&gt; = <span class="doxyComputerOutput">Opcode</span> &lt;empty&gt;.</p>


<p>The insertion point is the one set by the last call of either setBasicBlock or setMI.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="#ae04499daa8807ddb4d00e7ed18b1698f">buildInstrNoInsert</a> and <a href="#a06dc2f24e1f4dea357bf6c646f5b2607">insertInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#ab5aa406f974e74967376237df439846a">anonymous{AArch64PostLegalizerLowering.cpp}::applyEXT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#ae26a44292d42d576349e053e3497c18f">anonymous{AArch64PreLegalizerCombiner.cpp}::applyExtAddvToUdotAddv</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#adf82bf97d32fede84099257eb720a1a2">anonymous{AArch64PostLegalizerLowering.cpp}::applyFullRev</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#ad32e02ce8096aee6a5378ec754bf5034">anonymous{AArch64PostLegalizerLowering.cpp}::applyShuffleVectorPseudo</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a976bf3034ffa13d0fd59454e588e316a">anonymous{AArch64PostLegalizerLowering.cpp}::applyVAshrLshrImm</a>, <a href="#a90c3b61ed604fab822cb8f20a8e93fcb">buildAbds</a>, <a href="#a631d12fbfa91b33345eeec945832c8dd">buildAbdu</a>, <a href="#a96860390999e933a817881a50a905219">buildAbs</a>, <a href="#a12a128f6b9c963b6fd300cbdf52fba84">buildAdd</a>, <a href="#a534266d65ce335e1d212f37fc554dbb4">buildAddrSpaceCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvlegalizerinfo-cpp/#a42b3a4fddf9f295aaafa90d119e4733c">buildAllOnesMask</a>, <a href="#a33eb6083767372c564ea4bcf6c06eaf1">buildAnd</a>, <a href="#acac15566596b1d588d87450ab77bf0d7">buildAnyExt</a>, <a href="#a1d8cf0723104442c5ec84740aa7d43f9">buildAShr</a>, <a href="#adf3d2a21deea258c4c4a961586114ef9">buildAssertInstr</a>, <a href="#adbf5d6125fa84e067907320d93e9fab5">buildAtomicCmpXchg</a>, <a href="#acc22ffc46525708d66c036f878572523">buildAtomicCmpXchgWithSuccess</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af62f51194838248f650985e8299d7a97">llvm::buildAtomicCompareExchangeInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17fda1a191d8f69587355e32c5f15618">llvm::buildAtomicFlagInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abaf31a84826d881e8cebb369b37c6ff1">llvm::buildAtomicFloatingRMWInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad914aa705137aa18db88ae760f534f25">llvm::buildAtomicInitInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa24e8200fb460e1454ce71de5921fc7b">llvm::buildAtomicLoadInst</a>, <a href="#a497e8884b8ae421c7dadff0f0eea5e3e">buildAtomicRMW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acec38968fb25d9da84d9d606eca35d7d">llvm::buildAtomicRMWInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1e86010cc9381660c973391ab0034e00">llvm::buildAtomicStoreInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7380fc2046fc70f0b6040466a1a535af">llvm::buildBarrierInst</a>, <a href="#acf0f51041fbaaed06a39f2fe2686bb92">buildBitcast</a>, <a href="#a828ddf4cfe2b05f70a6566d36b4804c5">buildBitReverse</a>, <a href="#ae83cc330c36190cf8ee9618a28e9a300">buildBlockAddress</a>, <a href="#a1e5b88856596e413494661b5fae9fc39">buildBoolExt</a>, <a href="#a0ae44597e21d583e46c8bdfa52e56fa3">buildBr</a>, <a href="#a6e0f051c17bd6354aec061d308d80841">buildBrCond</a>, <a href="#aecf67aca8d78d0136244799c4182e52f">buildBrIndirect</a>, <a href="#aaf1013659ccc9708197f76c0bd724936">buildBrJT</a>, <a href="#a4ef9ec8bbb1cbf1ad44e5039537ddfe3">buildBSwap</a>, <a href="#a60609bd46d38414e2c9e2334f9740727">buildBuildVector</a>, <a href="#a96b7ed72c9782cd69b2b9b341cf73112">buildBuildVectorConstant</a>, <a href="#a7acf8a5ebb4b351a451a2d63faf13294">buildBuildVectorTrunc</a>, <a href="#a3493ece271aff0f2c3d162494e3fcc81">buildCast</a>, <a href="#a46cfa445be514255440f986c4b7b496f">buildConcatVectors</a>, <a href="#af751c28a69e1d07e19dad11e4e26a70d">buildConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a6aee777d2869b23ba59b88b9ceb32cfe">llvm::SPIRVGlobalRegistry::buildConstantFP</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#affb04c244423615aa0df24ee36f2de20">llvm::SPIRVGlobalRegistry::buildConstantInt</a>, <a href="#a1da8389b4eb951b11309c28ad492e8d4">buildConstantPool</a>, <a href="#aff3c145b6d12a00e7432953b1c454ebc">buildConstantPtrAuth</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a4280c0cdf83d31309a8ad8d0d6815e66">llvm::SPIRVGlobalRegistry::buildConstantSampler</a>, <a href="#ae32b6e2213ad3119a124e6e0673a5898">buildCopy</a>, <a href="#a6a31c8e33dcb4c2c60d965227c227e8e">buildCTLZ</a>, <a href="#a4fe52c440f33a8895fb01730017de4be">buildCTLZ_ZERO_UNDEF</a>, <a href="#a9607e5a365ae4ce30b73b802f590bb21">buildCTPOP</a>, <a href="#a1c1ac6707657ae4a0b6509e7857c1c68">buildCTTZ</a>, <a href="#a80194aed09e8b4c04c228940ff2a56a5">buildCTTZ_ZERO_UNDEF</a>, <a href="#aadc416be0ccae999a06a3a9452bf8d37">buildDbgLabel</a>, <a href="#ab00eba007903e9b4a69440782cd7c9c9">buildDynStackAlloc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac5631975d77a389618f6cdb0035cc561">llvm::buildEnqueueKernel</a>, <a href="#ab8da4d08f2c0875e9623bb712aa64303">buildExtOrTrunc</a>, <a href="#a2f52fec4aa17c3066db14a8d4717469d">buildExtract</a>, <a href="#aeb07fff3cb0ad02bf88651e9388777de">buildExtractSubvector</a>, <a href="#a7835e6cd3f1b340d3bb617304038d744">buildExtractVectorElement</a>, <a href="#a2161bd545c3baa8bfaa0d7b44ecf38c4">buildFAbs</a>, <a href="#afc51b7318978bc4878cce41bdf1774db">buildFAdd</a>, <a href="#afe0950de33581b21ef3c56db5f4382c1">buildFCanonicalize</a>, <a href="#afb3340c638c09709ce5766dcf672500d">buildFCmp</a>, <a href="#a81a7959d3e7f624343ecdf6905e251dd">buildFConstant</a>, <a href="#ac6b47b51bfacb6c594a3c6b8472202c1">buildFCopysign</a>, <a href="#a6f3162ab8134a05797e7a1d21889d880">buildFDiv</a>, <a href="#a21f358f36e1ae7fc91568266264f760e">buildFence</a>, <a href="#a5849bcf7d4b148009464f4a8b7d3d367">buildFExp2</a>, <a href="#ad5b247bb13afd8a0d31abedb522c7f46">buildFFloor</a>, <a href="#ad6391767e768c022d095516b3b86f3ae">buildFFrexp</a>, <a href="#a081e4f97d236d1d1c4e6599b7530498d">buildFLdexp</a>, <a href="#a914ca92cbc07e52a5115a023dc474f08">buildFLog</a>, <a href="#a1d453180d499c717c2d4a189e7615b48">buildFLog2</a>, <a href="#a23b0488d15477183dec5de35d9082ef7">buildFMA</a>, <a href="#a8d77ec102570efb92c2b7571ac17cf4f">buildFMAD</a>, <a href="#aabf1fb6f032d501430f9f917739aaf11">buildFMaxNum</a>, <a href="#ad32b91bbb8f081b9c3d3040697dc5eac">buildFMaxNumIEEE</a>, <a href="#aad3884fe393aca6b2c9aa240a2bcdea4">buildFMinNum</a>, <a href="#a226e1d000521c2ff3964171f4f78ab5e">buildFMinNumIEEE</a>, <a href="#a04873b91eebbedfe4fd28d54029068d6">buildFMul</a>, <a href="#ac939f3c7fdf6c976421d61564d078506">buildFNeg</a>, <a href="#a14b6de2cb8956f133042a43a1f888efe">buildFPExt</a>, <a href="#a3f2727e87d9863c60b67b7d08b05d2e6">buildFPow</a>, <a href="#a03241215374b8ba88272333652a4a151">buildFPTOSI</a>, <a href="#a170e74a42d89ea7a0b8e0b8634afa404">buildFPTOSI_SAT</a>, <a href="#a3bb6c93f088c2df4bcb58e6f677e1213">buildFPTOUI</a>, <a href="#a00ac61b8d79a357bd578193be5f15454">buildFPTOUI_SAT</a>, <a href="#ad84b765997ad4d3bb1ca3e9393d70ab8">buildFPTrunc</a>, <a href="#a92664cdbeb0b24030809439993ac271d">buildFrameIndex</a>, <a href="#a08361fe1409d7e2a9b96b0cabb918383">buildFreeze</a>, <a href="#adaa44dab2084014833b3744dfa291c89">buildFSincos</a>, <a href="#a02d0daf870f6458a98b61f4b82a399c3">buildFSub</a>, <a href="#ac69ef19d33fd455e8684cb53be2e46bb">buildGetFPEnv</a>, <a href="#a23dbfe8493962b776dd1635121d87cd0">buildGetFPMode</a>, <a href="#a0ac2ceaa32ba0511bb9e14e6edfbc329">buildGlobalValue</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a881c9e75128e7e943b6d8f33606ccc74">llvm::SPIRVGlobalRegistry::buildGlobalVariable</a>, <a href="#a3a618c7b84d45b5e188f6a7e4305ee39">buildICmp</a>, <a href="#aaf34795e0fa82f3edac1a235f50da4c1">buildInsert</a>, <a href="#a33a09195e1324b12063bf4d35c646066">buildInsertSubvector</a>, <a href="#aca31191486506a279715dd3bf677d75f">buildInsertVectorElement</a>, <a href="/web-llvm/docs/api/classes/llvm/csemirbuilder/#a9c2e15b867893ec15cb49acfbb38e542">llvm::CSEMIRBuilder::buildInstr</a>, <a href="#a6dacb1328b30771530a48be17307efb0">buildInstr</a>, <a href="#a84f7ac7613ff133970f83e8531085353">buildIntrinsic</a>, <a href="#a4b8abd0c10d11d7388c85825c9c220bf">buildIntrinsic</a>, <a href="#ab6de576f28600915731f6825a5c967f6">buildIntrinsicRoundeven</a>, <a href="#a4252eb25f822e53c1bea2ec59e5c0f07">buildIntrinsicTrunc</a>, <a href="#a5986a45c021d42bcc2f1563aa25c4cc8">buildIntToPtr</a>, <a href="#abe81abfee02ad99b922c40c0571e87a3">buildIsFPClass</a>, <a href="#a1e0ff1c3970daea3b6b33a07f4ad839e">buildJumpTable</a>, <a href="#aeede510b1aaac978daaba60dcc2817de">buildLoadInstr</a>, <a href="#a3e17399c568f784acb8ebf8be9a558ec">buildLShr</a>, <a href="#ae57ad469173d1ad36cb91dde447623ce">buildMemTransferInst</a>, <a href="#a7075ef788cb3dea0ea239c1a6830734c">buildMergeLikeInstr</a>, <a href="#aa0c1b48d1366572e4f3afa03e5c5f175">buildMergeLikeInstr</a>, <a href="#abe954ecff531c2cb1dcca7ed8813a318">buildMergeValues</a>, <a href="#a31a4848346777be4c13b39d57c0885d0">buildMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed92c21265205e69855b23b8b25707e2">llvm::buildNDRange</a>, <a href="#a66aef31356eb4467a34fbcb72f1649ad">buildNeg</a>, <a href="#a16532d0d8fb47080714810131b45b75b">buildNot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a8dcc4e0c146cff251e73a2a59123683b">buildOpBitcast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a686587ed0b5b8437aa621630cf56d147">llvm::buildOpDecorate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a01f1b2c1fbaec02e4f0d0af133830ca6">llvm::buildOpName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec2c920f97cffa508fee51ee5e722056">llvm::buildOpSpirvDecorations</a>, <a href="#ad93e8a9d68a578f6a53c70d39aef0dbe">buildOr</a>, <a href="#aeacc7cca9ff75b34872d7f7099d4261e">buildPrefetch</a>, <a href="#a7aae2634e3c0980c4f68983738b90ff7">buildPtrAdd</a>, <a href="#ae1d84823ec8a6332f2e5f8572a492255">buildPtrMask</a>, <a href="#afd3920e024c9e79df5fd07b03c64d314">buildPtrToInt</a>, <a href="#ab727f77aa5c064c0881a08e4bbb61c86">buildResetFPEnv</a>, <a href="#a14a087440fb584f0874f38801175bc64">buildResetFPMode</a>, <a href="#aff16332e2953a0f1430e9204b84f5aa6">buildRotateLeft</a>, <a href="#a197cbf8c5affd9a6e856e2ccb8085438">buildRotateRight</a>, <a href="#a36e19c5ffd6bb0b19cd01c41104fb083">buildSAdde</a>, <a href="#a3b6ed90b8df9e1da2212087d1f9199ba">buildSAddo</a>, <a href="#aa8a77031249a2b8a1d527d156f54f9d5">buildSbfx</a>, <a href="#a21c1b400982de1ca29ecc051da8bb5b6">buildSCmp</a>, <a href="#a23ad1ea55dda3ab7617c7fad52c571ab">buildSelect</a>, <a href="#afc7eb07b74fdeb50e151b325880fd51d">buildSetFPEnv</a>, <a href="#a585b4bef3330a9b489810dab77c07d3b">buildSetFPMode</a>, <a href="#a42427e969917da5da61fadd006fed326">buildSExt</a>, <a href="#afe73ac7a93f98c40c8fb66fce8fa4400">buildSExtInReg</a>, <a href="#a8528b8088d41e3b859d4ea0f25e13991">buildShl</a>, <a href="#aded2b440bea348970816da1ecd40f2c1">buildShuffleVector</a>, <a href="#a8c0db0c02bedbc26aba0fe9ebc77fff9">buildSITOFP</a>, <a href="#a6a42ee731fc4e33eab8c5d6f76f8d8b2">buildSMax</a>, <a href="#aad02a49b6c2f7c3c92a4ad7df5c4eb47">buildSMin</a>, <a href="#a284731f0ecc71898bf4ddc032e9f9a47">buildSMulH</a>, <a href="#a55bde2ba6aacac745a29a7e50c6be007">buildSplatBuildVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvlegalizerinfo-cpp/#acf786882a93d0d71ff5e5f39e1d12212">buildSplatPartsS64WithVL</a>, <a href="#aeea5857133a04085b450948e90fdcd1e">buildSplatVector</a>, <a href="#ab3bc600ec4a43f1914fed894c9cf9fc0">buildSSube</a>, <a href="#ac7553894d44938e9e9f4016dae66b72e">buildSSubo</a>, <a href="#af1b182c58ed8ff82a5958635de5ccb15">buildStepVector</a>, <a href="#a87a7405685118d45876c996318829ceb">buildStore</a>, <a href="#a6c47deaeb76718f7eaa6262308a72dd5">buildStrictFAdd</a>, <a href="#a4b2fab18274c6ca276053bb774c6e8c3">buildSub</a>, <a href="#ad5732a98562641ab5536b451ec72c5d4">buildTrap</a>, <a href="#abf1763199cd36c9253c6f062fa5e973e">buildTrunc</a>, <a href="#abfcd8132aaf36162d0ac865c74933456">buildUAdde</a>, <a href="#ad01ffef0e7c1bd556a76f6ead4d7d9fb">buildUAddo</a>, <a href="#a942b13bfd9c50bb5af1828739035ebe1">buildUbfx</a>, <a href="#a19fd5e11c62df9e228eb03dd466f5d0f">buildUCmp</a>, <a href="#a86e0c21f3e1e706b8d26733726c76195">buildUITOFP</a>, <a href="#afae1758b4922383832826f8382b0ab54">buildUMax</a>, <a href="#af9ac32566a3d7b10a68fac371f15f643">buildUMin</a>, <a href="#a6bf669233b50fac473a92c3039c48c4b">buildUMulH</a>, <a href="#a137bf40e73f82a78b6d2227ff65aeadf">buildUndef</a>, <a href="#a1e9e055fc19307bc3c7c1be6ccd36812">buildUnmerge</a>, <a href="#a330499e5e11e1c2e82e0a8c7179f335d">buildUnmerge</a>, <a href="#aeec9f9188630ac797d11be83445197b0">buildUnmerge</a>, <a href="#ac3c19ecc16565c150796b834a8a63963">buildUnmerge</a>, <a href="#a3b08f09b085506a31ea5ac83f5d8fda1">buildURem</a>, <a href="#ac80662067cf7650fa86ffb1c9cf75249">buildUSube</a>, <a href="#a5c12041fb9751bb3445d1da887a91e66">buildUSubo</a>, <a href="#aba86fb134fa3b2f01695749e0c7d84b6">buildVecReduceAdd</a>, <a href="#a997b3e4a8a93ae662f2f972297415fd6">buildVecReduceAnd</a>, <a href="#a5e1c6502399d7e0af30cba7a9925003f">buildVecReduceFAdd</a>, <a href="#a2cfde3d2db07050c016b443eaae2702d">buildVecReduceFMax</a>, <a href="#a9a71277627a30c423608a2e598ba4d32">buildVecReduceFMaximum</a>, <a href="#a6ededbd32ca155120e2dfd50f755688c">buildVecReduceFMin</a>, <a href="#a6397aa0392a0e4e57470de5e450da0b2">buildVecReduceFMinimum</a>, <a href="#a4f45e804fb39d50c4d8ec6bb1f5307a5">buildVecReduceFMul</a>, <a href="#af80e0eddf323d627ac891582fcb4710e">buildVecReduceMul</a>, <a href="#a1cf2e534999d7df7c847a4331924000d">buildVecReduceOr</a>, <a href="#a17c80c4630830047bb693ee47f58c8c3">buildVecReduceSeqFAdd</a>, <a href="#a4a5597c997afda710f863873c38c534e">buildVecReduceSeqFMul</a>, <a href="#ae4f70fb94cc8468f64183b6a5c75a0e0">buildVecReduceSMax</a>, <a href="#a686f39d5b9c570d44717e2cf9ca3da07">buildVecReduceSMin</a>, <a href="#a92a4e4e7dc4ca706beb3fb702283a77f">buildVecReduceUMax</a>, <a href="#ab0d22cadad3d84314a8847549ecc0a55">buildVecReduceUMin</a>, <a href="#a6e96b1d2ea4e991019ef283c4f588904">buildVecReduceXor</a>, <a href="#ab3480c1f40e51b1673754af7384a5078">buildVScale</a>, <a href="#af474773f09e4dbbc430d8d8df632e9fb">buildXor</a>, <a href="#a44a49b5f4dd2932058e3fbe21c098655">buildZExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvlegalizerinfo-cpp/#a3b8f2c8dafaf2b1007b8661546ce5aca">convertPtrToInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#a9acef535219004fa4c89f4f996343b6f">copySubReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#afb7df659747f14484e642788c2fe6788">createTuple</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#a2abcc0dade6e762f2145f49e3158a71c">doInsertBitcast</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748bbd916eb5b48b009f8ee2e6a6afc9">llvm::generateAsyncCopy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae60b3860c5a2f98d349a53660758ddd9">llvm::generateCastToPtrInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a884a65fc47e7cf521d37505e1548e9ca">llvm::generateConvertInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2d2d83de91f5be342b9beeb36a6e8c2">llvm::generateCoopMatrInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a515c6055dea0a74d18c4549511921e8c">llvm::generateDotOrFMulInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7e92ead0d298bfaef08370c3877e05c9">llvm::generateEnqueueInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aebcace45f75d5389e0c72effb52530b6">llvm::generateExtInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2947a09647c5d7fc7429c90d93fd2f17">llvm::generateGroupInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a610c7b58032f5eac1b06aa0c66cadb6a">llvm::generateGroupUniformInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3abab01a19c99b6700cc0aadde16edc2">llvm::generateICarryBorrowInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9aa2920e81d3e11168548e83a60ddaaf">llvm::generateImageMiscQueryInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a9a34bef43457f75fa60fb4186af2ef">llvm::generateImageSizeQueryInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa258d22bc5ca54e36dc15a8c3e724e52">llvm::generateIntelSubgroupsInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5c9c060a884e9461f06d7601681d2bcf">llvm::generateKernelClockInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0fc9e18e3a0aeb8c6426eae57a1ab61e">llvm::generateLoadStoreInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac44c583be05bf96fc1323db172608e32">llvm::generateReadImageInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acfd0973871508362181539a1e103e0ed">llvm::generateRelationalInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a519951c274914148448a0942705a1fc2">llvm::generateSampleImageInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aabf50e80c80c98fd130ff1cb70553742">llvm::generateSpecConstantInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab25d01b38cf3d0b9e22fe06c673243d6">llvm::generateVectorLoadStoreInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ada8921c7a351b3829e06720c0858f541">llvm::generateWriteImageInst</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#af54e9ce01961e65d9b74fef2193a8d95">llvm::SPIRVGlobalRegistry::getOrCreateConstFP</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a08f607435df14840793b848f2b3c0257">llvm::SPIRVGlobalRegistry::getOrCreateConstInt</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#af99db04834e1ae3fc23466a80045a4d9">llvm::SPIRVGlobalRegistry::getOrCreateConstNullPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a69f73e1b5f8a3e376c63293408b6786e">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeByOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#acbccd3fb66e9075690f45dea7440cf9e">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeCoopMatr</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#abeddeff35f8dd231213915a6f77f0920">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeDeviceEvent</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a4cd2c03c778450920cd3b53acdcb4fba">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeImage</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a0067190a151de0ad367e8d1e56c1016a">llvm::SPIRVGlobalRegistry::getOrCreateOpTypePipe</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a8cdc39b963a62003cd157541feca56f6">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeSampledImage</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#aea914eb511a3b8ebf605c62c07e8ab44">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeSampler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a2222b2a89839a157c1b2992743effe">llvm::insertAssignInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a307848f42e24813c2b6a55b8d8959fa4">insertInlineAsmProcess</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#a1ddebf0db857b4b9fd7004511b7eb393">llvm::RISCVLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#aa48b853fae2f40e3e483078a944ab8d1">llvm::AArch64LegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#ae1eb226b5600f7802dc31d1903a5040e">llvm::AMDGPUCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/armcalllowering/#af3fdfad8a2951ca4c86fd64560c550a7">llvm::ARMCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kcalllowering/#a2c714d045da3eaad01dfd893048e9a0c">llvm::M68kCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a5344895d462c34e2c90e930471d8e4d9">llvm::MipsCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvcalllowering/#a82f1da052b54c0bd8969fea523e25066">llvm::RISCVCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ab055c9ed89ccbcf823971615232941d1">llvm::SPIRVCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/x86calllowering/#a699fa07bf5290218677fc2a1e69e0781">llvm::X86CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#af4911ff1c4fabd84b05d4529da80021e">llvm::SPIRVCallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#a010cf32a5c68f9701c57d7a3172f1b3f">llvm::AArch64CallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfcalllowering/#a233177d33a84d04ee5ff91e1c33d16e0">llvm::BPFCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ac8dc1642db124c4da34fbec06040a0c4">llvm::SPIRVCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a0c3beb54f8fa06f2fd8074561a5a515c">llvm::AMDGPUCallLowering::lowerTailCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipslegalizerinfo-cpp/#a606d158739fd7cd13395bd7db9fc3e36">MSA2OpIntrinsicToGeneric</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipslegalizerinfo-cpp/#ad90722edae1f87193dcefae806cae4b8">MSA3OpIntrinsicToGeneric</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2d5aaa74bb3796fbcd85861222730ab">llvm::processInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinstructionselector-cpp-/riscvinstructionselector/#a285142054aed60907906550e49ed07e2">anonymous{RISCVInstructionSelector.cpp}::RISCVInstructionSelector::select</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipslegalizerinfo-cpp/#a8a476245face103d65c519250257e499">SelectMSA3OpIntrinsic</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64giselutils/#a9922ec95e157a3432c8ccd4a8a6a2653">llvm::AArch64GISelUtils::tryEmitBZero</a>.</p>

</div>
</div>

### buildInstr() {#a6dacb1328b30771530a48be17307efb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildInstr (unsigned Opc, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &gt; DstOps, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &gt; SrcOps, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 1222 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa911a7e9e51b7ed20810fc819efe6a26">llvm::LLT::getElementCount</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a7bd850492d35a34f0fe419e5555997a9">llvm::CmpInst::isFPPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#ad73f009e1b3b060bcdf6c2c1dd86600e">llvm::CmpInst::isIntPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a9d825f5954d7bd527aea490668c624c6">llvm::LLT::isPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#a0173b34b2346b5bfdfb06974b064c857a2d0e1304ef8d805e2c04c15c53db4e48">llvm::SrcOp::Ty_Predicate</a>, <a href="#a9856f0ee59ced7e9724315502ea9a380">validateBinaryOp</a>, <a href="#a91a10c5f7ca3b7a86768cb33f8955b5c">validateSelectOp</a>, <a href="#a9c8154c310c33839a5d134b63c4d9cb6">validateShiftOp</a>, <a href="#adfd8cf26645132e9a23697eed85685e1">validateTruncExt</a> and <a href="#ae63e90ab103cd2159b9431b5ed5e9a53">validateUnaryOp</a>.</p>

</div>
</div>

### buildInstrNoInsert() {#ae04499daa8807ddb4d00e7ed18b1698f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildInstrNoInsert (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build but don't insert &lt;empty&gt; = <span class="doxyComputerOutput">Opcode</span> &lt;empty&gt;.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setMF, setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 426 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo/#a176ca2c9108a997dcfd8aadf4c0f0fa0">llvm::MCInstrInfo::get</a>, <a href="#a93ab05c4fb48bd5e87965bef6ec9ac2e">getDL</a>, <a href="#a9ec04f3692b9601036d2d4477c4c3749">getMF</a>, <a href="#ae93b0a855cdf8afb141d16e217158683">getMMRAMetadata</a>, <a href="#a4d965aceed7f5b45e11799d0fa0b36e3">getPCSections</a> and <a href="#a35384c47e5ca9690216b1aa8fed5a8c9">getTII</a>.</p>


<p>Referenced by <a href="#a6ab34a535b1441b48a0ede2c2aa6fb98">buildConstDbgValue</a>, <a href="#ab107810eccfb0e46e47348ea9ef8d0ed">buildFIDbgValue</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#ae1eb226b5600f7802dc31d1903a5040e">llvm::AMDGPUCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/armcalllowering/#af3fdfad8a2951ca4c86fd64560c550a7">llvm::ARMCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kcalllowering/#a2c714d045da3eaad01dfd893048e9a0c">llvm::M68kCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a5344895d462c34e2c90e930471d8e4d9">llvm::MipsCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvcalllowering/#a82f1da052b54c0bd8969fea523e25066">llvm::RISCVCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/x86calllowering/#a699fa07bf5290218677fc2a1e69e0781">llvm::X86CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasmlowering/#a1c9cd272afbe2a9aaca46369f9e61b79">llvm::InlineAsmLowering::lowerInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#a010cf32a5c68f9701c57d7a3172f1b3f">llvm::AArch64CallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/armcalllowering/#a49a30e74a8632576007b3678649c9fb9">llvm::ARMCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kcalllowering/#abfdadd18c92c595797ca5409d708f2ef">llvm::M68kCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a821ed33f62736f960fa90c585205677d">llvm::MipsCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/ppccalllowering/#a0895983a48b4fe2de9c52579431f8744">llvm::PPCCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvcalllowering/#a2a90be51e47dadfbb04df4f64465ea04">llvm::RISCVCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/x86calllowering/#ace03d9ed2825d1401093a441f164ecdf">llvm::X86CallLowering::lowerReturn</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a0c3beb54f8fa06f2fd8074561a5a515c">llvm::AMDGPUCallLowering::lowerTailCall</a>.</p>

</div>
</div>

### buildIntrinsic() {#a4b8abd0c10d11d7388c85825c9c220bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildIntrinsic (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> ID, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; Res, bool HasSideEffects, bool isConvergent)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert a G_INTRINSIC instruction.</p>


<p>There are four different opcodes based on combinations of whether the intrinsic has side effects and whether it is convergent. These properties can be specified as explicit parameters, or else they are retrieved from the <a href="/web-llvm/docs/api/namespaces/llvm/mcid">MCID</a> for the intrinsic.</p>


<p>The parameter <span class="doxyComputerOutput">Res</span> provides the Registers or MOs that will be defined by this instruction.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 870 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp/#a728ffc3d33c9386682ad1a9b4eb217a6">getIntrinsicOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac5631975d77a389618f6cdb0035cc561">llvm::buildEnqueueKernel</a>, <a href="#a41d7c53499da41b1739015f7036cf6da">buildIntrinsic</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab28508dbb1f9996154ae13f70fa4f2e2">llvm::genWorkgroupQuery</a>.</p>

</div>
</div>

### buildIntrinsic() {#a3481726c6f5714e53ed2efc761ed52bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildIntrinsic (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> ID, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; Res)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 881 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>

</div>
</div>

### buildIntrinsic() {#a84f7ac7613ff133970f83e8531085353}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildIntrinsic (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> ID, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &gt; Res, bool HasSideEffects, bool isConvergent)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 889 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp/#a728ffc3d33c9386682ad1a9b4eb217a6">getIntrinsicOpcode</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp/#a7e344cff0feadf0b02223fee63cc7475">Results</a>.</p>

</div>
</div>

### buildIntrinsic() {#a41d7c53499da41b1739015f7036cf6da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildIntrinsic (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> ID, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &gt; Res)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 900 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="#a4b8abd0c10d11d7388c85825c9c220bf">buildIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a89cda2218259523c41863fc1175d6907">llvm::Intrinsic::getAttributes</a>, <a href="#a120dbb8d0a1ad4437456001a302a1da7">getContext</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp/#a7e344cff0feadf0b02223fee63cc7475">Results</a>.</p>

</div>
</div>

### buildIntrinsicRoundeven() {#ab6de576f28600915731f6825a5c967f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildIntrinsicRoundeven (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_INTRINSIC_ROUNDEVEN <span class="doxyComputerOutput">Src0</span>, <span class="doxyComputerOutput">Src1</span>.</p>

<p>Definition at line 2113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildIntrinsicTrunc() {#a4252eb25f822e53c1bea2ec59e5c0f07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildIntrinsicTrunc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_INTRINSIC_TRUNC <span class="doxyComputerOutput">Src0</span>.</p>

<p>Definition at line 2017 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildIntToPtr() {#a5986a45c021d42bcc2f1563aa25c4cc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildIntToPtr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src)</td>
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

<p>Build and insert a G_INTTOPTR instruction.</p>

<p>Definition at line 718 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildIsFPClass() {#abe81abfee02ad99b922c40c0571e87a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildIsFPClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src, unsigned Mask)</td>
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

<p>Build and insert a <span class="doxyComputerOutput">Res</span> = G_IS_FPCLASS <span class="doxyComputerOutput">Src</span>, <span class="doxyComputerOutput">Mask</span>.</p>

<p>Definition at line 1333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildJumpTable() {#a1e0ff1c3970daea3b6b33a07f4ad839e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildJumpTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> PtrTy, unsigned JTI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_JUMP_TABLE <span class="doxyComputerOutput">JTI</span>.</p>


<p>G_JUMP_TABLE sets <span class="doxyComputerOutput">Res</span> to the address of the jump table specified by the jump table index <span class="doxyComputerOutput">JTI</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 2154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildLoad() {#a7962eca94c9f77da448245745fb22f57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildLoad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Addr, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; MMO)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res = G_LOAD Addr, MMO</span>.</p>


<p>Loads the value stored at <span class="doxyComputerOutput">Addr</span>. Puts the result in <span class="doxyComputerOutput">Res</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Addr</span> must be a generic virtual register with pointer type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Definition at line 959 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#aeede510b1aaac978daaba60dcc2817de">buildLoadInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a580c192e2fc41ab69e61d087027ceabf">anonymous{AArch64PostLegalizerLowering.cpp}::applyNonConstInsert</a>, <a href="#a3d61feda2a7e9f526ff461c900295bc1">buildLoad</a>, <a href="#a010032df630a417383fa44deee43ac0c">buildLoadFromOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7cd4d3025cb2ea4e0ce7e5a317f47d4b">llvm::buildLoadInst</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a33a30176a7fd636333a4e618ef109f57">llvm::CallLowering::insertSRetLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a867592b1a0963211ea415ea436a976e5">llvm::MipsLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#aa48b853fae2f40e3e483078a944ab8d1">llvm::AArch64LegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#aabf8e09177e2ae41bc06eb1f2be342e8">llvm::MipsLegalizerInfo::legalizeIntrinsic</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#aa97467a5c0d54755f0e725e9310ffaa0">llvm::RISCVLegalizerInfo::legalizeIntrinsic</a>.</p>

</div>
</div>

### buildLoad() {#a3d61feda2a7e9f526ff461c900295bc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildLoad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Addr, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> PtrInfo, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dd">MachineMemOperand::Flags</a> MMOFlags=<a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddac2989bebe46c9b9fcb7a92e5ade8dde6">MachineMemOperand::MONone</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a> &amp; AAInfo=<a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert a G_LOAD instruction, while constructing the <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a>.</p>

<p>Declaration at line 967 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7962eca94c9f77da448245745fb22f57">buildLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="#a9ec04f3692b9601036d2d4477c4c3749">getMF</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a> and <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddaed357b1367bc90a56fefa4d1b0e17374">llvm::MachineMemOperand::MOStore</a>.</p>

</div>
</div>

### buildLoadFromOffset() {#a010032df630a417383fa44deee43ac0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildLoadFromOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; BasePtr, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; BaseMMO, int64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper to create a load from a constant offset given a base address.</p>


<p>Load the type of <span class="doxyComputerOutput">Dst</span> from <span class="doxyComputerOutput">Offset</span> from the given base address and memory operand.</p>


<p>Declaration at line 987 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 451 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="#af751c28a69e1d07e19dad11e4e26a70d">buildConstant</a>, <a href="#a7962eca94c9f77da448245745fb22f57">buildLoad</a>, <a href="#a7aae2634e3c0980c4f68983738b90ff7">buildPtrAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="#a9ec04f3692b9601036d2d4477c4c3749">getMF</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>

</div>
</div>

### buildLoadInstr() {#aeede510b1aaac978daaba60dcc2817de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildLoadInstr (unsigned Opcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Addr, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; MMO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res = &lt;opcode&gt; Addr, MMO</span>.</p>


<p>Loads the value stored at <span class="doxyComputerOutput">Addr</span>. Puts the result in <span class="doxyComputerOutput">Res</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Addr</span> must be a generic virtual register with pointer type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 981 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dstop/#a45141d649d02a2ed17b51b5419ee884d">llvm::DstOp::addDefToMIB</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#aba93d72255e1239b5209e416a1b7f199">llvm::SrcOp::addSrcToMIB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a49a5649c0de9dee3dacbab3019872923">llvm::DstOp::getLLTTy</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#a99fb11458708b57172b6b0df633fd4fc">llvm::SrcOp::getLLTTy</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#a103d8cfe62c1651cd70e181746f8a840">isValid</a>.</p>


<p>Referenced by <a href="#a7962eca94c9f77da448245745fb22f57">buildLoad</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a8f8ee7977675d9e8cdded7bda420b96e">emitLoadFromConstantPool</a>.</p>

</div>
</div>

### buildLShr() {#a3e17399c568f784acb8ebf8be9a558ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildLShr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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



<p>Definition at line 1858 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a867592b1a0963211ea415ea436a976e5">llvm::MipsLegalizerInfo::legalizeCustom</a>.</p>

</div>
</div>

### buildMaskLowPtrBits() {#af6aed1d3b2cf7133b73cf8bfa5122186}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildMaskLowPtrBits (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op0, uint32_t NumBits)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_PTRMASK <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">G_CONSTANT</span> (1 &lt;&lt; NumBits) - 1.</p>


<p>This clears the low bits of a pointer operand without destroying its pointer properties. This has the effect of rounding the address <em>down</em> to a specified alignment in bits.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> and <span class="doxyComputerOutput">Op0</span> must be generic virtual registers with pointer type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">NumBits</span> must be an integer representing the number of low bits to be cleared in <span class="doxyComputerOutput">Op0</span>.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 560 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="#af751c28a69e1d07e19dad11e4e26a70d">buildConstant</a>, <a href="#ae1d84823ec8a6332f2e5f8572a492255">buildPtrMask</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a9694f2906cfe1d6d35bbe6742c67dff0">llvm::MachineRegisterInfo::createGenericVirtualRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a49a5649c0de9dee3dacbab3019872923">llvm::DstOp::getLLTTy</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7a32d8533843aab2ce0254e2e2389c9c">llvm::maskTrailingZeros</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>

</div>
</div>

### buildMemCpy() {#aa3b92017579b7ddbca8c13cf7f746789}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildMemCpy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; DstPtr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; SrcPtr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Size, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; DstMMO, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; SrcMMO)</td>
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



<p>Definition at line 2278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="#ae57ad469173d1ad36cb91dde447623ce">buildMemTransferInst</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### buildMemTransferInst() {#ae57ad469173d1ad36cb91dde447623ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildMemTransferInst (unsigned Opcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; DstPtr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; SrcPtr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Size, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; DstMMO, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; SrcMMO)</td>
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

<p>Build and insert G_MEMCPY or G_MEMMOVE.</p>

<p>Definition at line 2266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ae565d45627e1678a3e37bd6a016c561c">llvm::MachineInstrBuilder::addMemOperand</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#aa3b92017579b7ddbca8c13cf7f746789">buildMemCpy</a>.</p>

</div>
</div>

### buildMergeLikeInstr() {#a7075ef788cb3dea0ea239c1a6830734c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildMergeLikeInstr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_MERGE_VALUES <span class="doxyComputerOutput">Op0</span>, ... or <span class="doxyComputerOutput">Res</span> = G_BUILD_VECTOR <span class="doxyComputerOutput">Op0</span>, ... or <span class="doxyComputerOutput">Res</span> = G_CONCAT_VECTORS <span class="doxyComputerOutput">Op0</span>, ...</p>


<p>G_MERGE_VALUES combines the input elements contiguously into a larger register. It is used when the destination register is not a vector. G_BUILD_VECTOR combines scalar inputs into a vector register. G_CONCAT_VECTORS combines vector inputs into a vector register.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>The entire register <span class="doxyComputerOutput">Res</span> (and no more) must be covered by the input registers.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>The type of all <span class="doxyComputerOutput">Ops</span> registers must be identical.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction. The opcode of the new instruction will depend on the types of both the destination and the sources.</p></dd>
</dl>


<p>Declaration at line 1055 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 656 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#ad68c3cafb2cc7ee28ee3c7dff2a45f2e">buildDeleteTrailingVectorElements</a>, <a href="#a901a49f9b5721ab01d9d371f96e4bcea">buildPadVectorWithUndefElements</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2c32a92de16156166b3fd4de261d20a0">llvm::extractParts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af4c0f443e3b75e7b2ffaf53d2ab73fc0">llvm::extractVectorParts</a>, <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a867592b1a0963211ea415ea436a976e5">llvm::MipsLegalizerInfo::legalizeCustom</a> and <a href="/web-llvm/docs/api/classes/llvm/x86calllowering/#a699fa07bf5290218677fc2a1e69e0781">llvm::X86CallLowering::lowerCall</a>.</p>

</div>
</div>

### buildMergeLikeInstr() {#aa0c1b48d1366572e4f3afa03e5c5f175}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildMergeLikeInstr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &gt; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1057 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 667 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildMergeValues() {#abe954ecff531c2cb1dcca7ed8813a318}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildMergeValues (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_MERGE_VALUES <span class="doxyComputerOutput">Op0</span>, ...</p>


<p>G_MERGE_VALUES combines the input elements contiguously into a larger register. It should only be used when the destination register is not a vector.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>The entire register <span class="doxyComputerOutput">Res</span> (and no more) must be covered by the input registers.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>The type of all <span class="doxyComputerOutput">Ops</span> registers must be identical.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1035 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 645 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### buildMul() {#a31a4848346777be4c13b39d57c0885d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildMul (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_MUL <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>.</p>


<p>G_MUL sets <span class="doxyComputerOutput">Res</span> to the product of integer parameters <span class="doxyComputerOutput">Op0</span> and <span class="doxyComputerOutput">Op1</span>, truncated to their width.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span>, <span class="doxyComputerOutput">Op0</span> and <span class="doxyComputerOutput">Op1</span> must be generic virtual registers with the same (scalar or vector) type).</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Definition at line 1769 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a580c192e2fc41ab69e61d087027ceabf">anonymous{AArch64PostLegalizerLowering.cpp}::applyNonConstInsert</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a2f1d26ea9bced931d104b4dd8b26775f">getMemsetValue</a>.</p>

</div>
</div>

### buildNeg() {#a66aef31356eb4467a34fbcb72f1649ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildNeg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0)</td>
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

<p>Build and insert integer negation <span class="doxyComputerOutput">Zero</span> = G_CONSTANT 0 <span class="doxyComputerOutput">Res</span> = G_SUB Zero, <span class="doxyComputerOutput">Op0</span>.</p>

<p>Definition at line 1919 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="#af751c28a69e1d07e19dad11e4e26a70d">buildConstant</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a> and <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a>.</p>

</div>
</div>

### buildNot() {#a16532d0d8fb47080714810131b45b75b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildNot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0)</td>
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

<p>Build and insert a bitwise not, <span class="doxyComputerOutput">NegOne</span> = G_CONSTANT -1 <span class="doxyComputerOutput">Res</span> = G_OR <span class="doxyComputerOutput">Op0</span>, NegOne.</p>

<p>Definition at line 1911 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="#af751c28a69e1d07e19dad11e4e26a70d">buildConstant</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a> and <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#ac9275cee4b272a43dca3299ab8b6144c">anonymous{AArch64PostLegalizerLowering.cpp}::applyLowerVectorFCMP</a>.</p>

</div>
</div>

### buildOr() {#ad93e8a9d68a578f6a53c70d39aef0dbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildOr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_OR <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>.</p>


<p>G_OR sets <span class="doxyComputerOutput">Res</span> to the bitwise or of integer parameters <span class="doxyComputerOutput">Op0</span> and <span class="doxyComputerOutput">Op1</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span>, <span class="doxyComputerOutput">Op0</span> and <span class="doxyComputerOutput">Op1</span> must be generic virtual registers with the same (scalar or vector) type).</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Definition at line 1896 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#ac9275cee4b272a43dca3299ab8b6144c">anonymous{AArch64PostLegalizerLowering.cpp}::applyLowerVectorFCMP</a>, <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a2aeed55e4456de4086b3592eb92dc2e2">llvm::ARMLegalizerInfo::legalizeCustom</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#ac9f5ed1e7ae99c336e8ae9b4ccf10b50">llvm::AMDGPUCallLowering::passSpecialInputs</a>.</p>

</div>
</div>

### buildPadVectorWithUndefElements() {#a901a49f9b5721ab01d9d371f96e4bcea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildPadVectorWithUndefElements (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert a, b, ..., x = G_UNMERGE_VALUES <span class="doxyComputerOutput">Op0</span> <span class="doxyComputerOutput">Res</span> = G_BUILD_VECTOR a, b, ..., x, undef, ..., undef.</p>


<p>Pad <span class="doxyComputerOutput">Op0</span> with undef elements to match number of elements in <span class="doxyComputerOutput">Res</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> and <span class="doxyComputerOutput">Op0</span> must be generic virtual registers with vector type, same vector element type and Op0 must have fewer elements then Res.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created build vector instr.</p></dd>
</dl>


<p>Declaration at line 574 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7075ef788cb3dea0ea239c1a6830734c">buildMergeLikeInstr</a>, <a href="#a137bf40e73f82a78b6d2227ff65aeadf">buildUndef</a>, <a href="#a1e9e055fc19307bc3c7c1be6ccd36812">buildUnmerge</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a49a5649c0de9dee3dacbab3019872923">llvm::DstOp::getLLTTy</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#a99fb11458708b57172b6b0df633fd4fc">llvm::SrcOp::getLLTTy</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a1c5fadb14ff1d77faad0cb58a43252ab">llvm::MachineInstrBuilder::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#ae229785d0c8a8ce25d34be18fe150a54">llvm::SrcOp::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#a010cf32a5c68f9701c57d7a3172f1b3f">llvm::AArch64CallLowering::lowerReturn</a>.</p>

</div>
</div>

### buildPrefetch() {#aeacc7cca9ff75b34872d7f7099d4261e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildPrefetch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Addr, unsigned RW, unsigned Locality, unsigned CacheType, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; MMO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert G_PREFETCH <span class="doxyComputerOutput">Addr</span>, <span class="doxyComputerOutput">RW</span>, <span class="doxyComputerOutput">Locality</span>, <span class="doxyComputerOutput">CacheType</span>.</p>

<p>Declaration at line 1706 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 1165 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/srcop/#aba93d72255e1239b5209e416a1b7f199">llvm::SrcOp::addSrcToMIB</a> and <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildPtrAdd() {#a7aae2634e3c0980c4f68983738b90ff7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildPtrAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_PTR_ADD <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>.</p>


<p>G_PTR_ADD adds <span class="doxyComputerOutput">Op1</span> addressible units to the pointer specified by <span class="doxyComputerOutput">Op0</span>, storing the resulting pointer in <span class="doxyComputerOutput">Res</span>. Addressible units are typically bytes but this can vary between targets.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> and <span class="doxyComputerOutput">Op0</span> must be generic virtual registers with pointer type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Op1</span> must be a generic virtual register with scalar type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 516 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a49a5649c0de9dee3dacbab3019872923">llvm::DstOp::getLLTTy</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#a99fb11458708b57172b6b0df633fd4fc">llvm::SrcOp::getLLTTy</a> and <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a580c192e2fc41ab69e61d087027ceabf">anonymous{AArch64PostLegalizerLowering.cpp}::applyNonConstInsert</a>, <a href="#a010032df630a417383fa44deee43ac0c">buildLoadFromOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a867592b1a0963211ea415ea436a976e5">llvm::MipsLegalizerInfo::legalizeCustom</a> and <a href="#a0f2bb4d63ad6914f3783967bf881a14b">materializePtrAdd</a>.</p>

</div>
</div>

### buildPtrMask() {#ae1d84823ec8a6332f2e5f8572a492255}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildPtrMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op1)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_PTRMASK <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>.</p>

<p>Definition at line 542 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>


<p>Referenced by <a href="#af6aed1d3b2cf7133b73cf8bfa5122186">buildMaskLowPtrBits</a>.</p>

</div>
</div>

### buildPtrToInt() {#afd3920e024c9e79df5fd07b03c64d314}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildPtrToInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src)</td>
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

<p>Build and insert a G_PTRTOINT instruction.</p>

<p>Definition at line 713 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildResetFPEnv() {#ab727f77aa5c064c0881a08e4bbb61c86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildResetFPEnv ()</td>
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

<p>Build and insert G_RESET_FPENV.</p>

<p>Definition at line 2330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildResetFPMode() {#a14a087440fb584f0874f38801175bc64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildResetFPMode ()</td>
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

<p>Build and insert G_RESET_FPMODE.</p>

<p>Definition at line 2345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildRotateLeft() {#aff16332e2953a0f1430e9204b84f5aa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildRotateLeft (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Amt)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_ROTL <span class="doxyComputerOutput">Src</span>, <span class="doxyComputerOutput">Amt</span>.</p>

<p>Definition at line 2309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildRotateRight() {#a197cbf8c5affd9a6e856e2ccb8085438}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildRotateRight (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Amt)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_ROTR <span class="doxyComputerOutput">Src</span>, <span class="doxyComputerOutput">Amt</span>.</p>

<p>Definition at line 2303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildSAdde() {#a36e19c5ffd6bb0b19cd01c41104fb083}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildSAdde (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; CarryOut, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; CarryIn)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span>, <span class="doxyComputerOutput">CarryOut</span> = G_SADDE <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>, <span class="doxyComputerOutput">CarryInp</span>.</p>

<p>Definition at line 656 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildSAddo() {#a3b6ed90b8df9e1da2212087d1f9199ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildSAddo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; CarryOut, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op1)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span>, <span class="doxyComputerOutput">CarryOut</span> = G_SADDO <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>.</p>

<p>Definition at line 615 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildSbfx() {#aa8a77031249a2b8a1d527d156f54f9d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildSbfx (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; LSB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Width)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_SBFX <span class="doxyComputerOutput">Src</span>, <span class="doxyComputerOutput">LSB</span>, <span class="doxyComputerOutput">Width</span>.</p>

<p>Definition at line 2291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildSCmp() {#a21c1b400982de1ca29ecc051da8bb5b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildSCmp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert a <span class="doxyComputerOutput">Res</span> = G_SCMP <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register with scalar or vector type. Typically this starts as s2 or &lt;N x s2&gt;.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Op0</span> and Op1 must be generic virtual registers with the same number of elements as <span class="doxyComputerOutput">Res</span>. If <span class="doxyComputerOutput">Res</span> is a scalar, <span class="doxyComputerOutput">Op0</span> must be a scalar.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 937 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildSelect() {#a23ad1ea55dda3ab7617c7fad52c571ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildSelect (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Tst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert a <span class="doxyComputerOutput">Res</span> = G_SELECT <span class="doxyComputerOutput">Tst</span>, <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span>, <span class="doxyComputerOutput">Op0</span> and <span class="doxyComputerOutput">Op1</span> must be generic virtual registers with the same type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Tst</span> must be a generic virtual register with scalar, pointer or vector type. If vector then it must have the same number of elements as the other parameters.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 950 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a813af4f625c1b136c991637d08bf9087">llvm::buildSelectInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa2054eea3e96cb42235590ae3fe4ee6e">llvm::generateSelectInst</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab28508dbb1f9996154ae13f70fa4f2e2">llvm::genWorkgroupQuery</a>.</p>

</div>
</div>

### buildSetFPEnv() {#afc7eb07b74fdeb50e151b325880fd51d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildSetFPEnv (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src)</td>
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

<p>Build and insert G_SET_FPENV <span class="doxyComputerOutput">Src</span>.</p>

<p>Definition at line 2325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a2aeed55e4456de4086b3592eb92dc2e2">llvm::ARMLegalizerInfo::legalizeCustom</a>.</p>

</div>
</div>

### buildSetFPMode() {#a585b4bef3330a9b489810dab77c07d3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildSetFPMode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src)</td>
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

<p>Build and insert G_SET_FPMODE <span class="doxyComputerOutput">Src</span>.</p>

<p>Definition at line 2340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildSExt() {#a42427e969917da5da61fadd006fed326}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildSExt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_SEXT <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>.</p>


<p>G_SEXT produces a register of the specified width, with bits 0 to sizeof(<span class="doxyComputerOutput">Ty</span>) * 8 set to <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>. The remaining bits are duplicated from the high bit of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> (i.e. 2s-complement sign extended).</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register with scalar or vector type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> must be a generic virtual register with scalar or vector type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> must be smaller than <span class="doxyComputerOutput">Res</span></p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The newly created instruction.</p></dd>
</dl>


<p>Declaration at line 699 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildSExtInReg() {#afe73ac7a93f98c40c8fb66fce8fa4400}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildSExtInReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op, int64_t ImmOp)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_SEXT_INREG <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>, ImmOp.</p>

<p>Definition at line 702 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>


<p>Referenced by <a href="#a060616c6385361df8bd72cde315d4267">buildBoolExtInReg</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#a1ddebf0db857b4b9fd7004511b7eb393">llvm::RISCVLegalizerInfo::legalizeCustom</a>.</p>

</div>
</div>

### buildSExtOrTrunc() {#a437e7190e38ee7e10daee0f4909d5066}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildSExtOrTrunc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_SEXT <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>, <span class="doxyComputerOutput">Res</span> = G_TRUNC <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>, or <span class="doxyComputerOutput">Res</span> = COPY <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> depending on the differing sizes of <span class="doxyComputerOutput">Res</span> and <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>.</p>


<p>///</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register with scalar or vector type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> must be a generic virtual register with scalar or vector type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The newly created instruction.</p></dd>
</dl>


<p>Declaration at line 771 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 571 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#ab8da4d08f2c0875e9623bb712aa64303">buildExtOrTrunc</a>.</p>

</div>
</div>

### buildShl() {#a8528b8088d41e3b859d4ea0f25e13991}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildShl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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



<p>Definition at line 1852 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#ac9f5ed1e7ae99c336e8ae9b4ccf10b50">llvm::AMDGPUCallLowering::passSpecialInputs</a>.</p>

</div>
</div>

### buildShuffleSplat() {#a43b43271e5bcbbc5cc620b4dfa94937a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildShuffleSplat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert a vector splat of a scalar <span class="doxyComputerOutput">Src</span> using a G_INSERT_VECTOR_ELT and G_SHUFFLE_VECTOR idiom.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Src</span> must have the same type as the element type of <span class="doxyComputerOutput">Dst</span></p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 759 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af751c28a69e1d07e19dad11e4e26a70d">buildConstant</a>, <a href="#aca31191486506a279715dd3bf677d75f">buildInsertVectorElement</a>, <a href="#aded2b440bea348970816da1ecd40f2c1">buildShuffleVector</a>, <a href="#a137bf40e73f82a78b6d2227ff65aeadf">buildUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a49a5649c0de9dee3dacbab3019872923">llvm::DstOp::getLLTTy</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>

</div>
</div>

### buildShuffleVector() {#aded2b440bea348970816da1ecd40f2c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildShuffleVector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src2, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_SHUFFLE_VECTOR <span class="doxyComputerOutput">Src1</span>, <span class="doxyComputerOutput">Src2</span>, <span class="doxyComputerOutput">Mask</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 778 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a2fcb27493c046f8b158e085b45c31764">llvm::MachineFunction::allocateShuffleMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a49a5649c0de9dee3dacbab3019872923">llvm::DstOp::getLLTTy</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#a99fb11458708b57172b6b0df633fd4fc">llvm::SrcOp::getLLTTy</a>, <a href="#a9ec04f3692b9601036d2d4477c4c3749">getMF</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>.</p>


<p>Referenced by <a href="#a43b43271e5bcbbc5cc620b4dfa94937a">buildShuffleSplat</a>.</p>

</div>
</div>

### buildSITOFP() {#a8c0db0c02bedbc26aba0fe9ebc77fff9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildSITOFP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_SITOFP <span class="doxyComputerOutput">Src0</span>.</p>

<p>Definition at line 2087 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildSMax() {#a6a42ee731fc4e33eab8c5d6f76f8d8b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildSMax (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_SMAX <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>.</p>

<p>Definition at line 2126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildSMin() {#aad02a49b6c2f7c3c92a4ad7df5c4eb47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildSMin (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_SMIN <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>.</p>

<p>Definition at line 2120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildSMulH() {#a284731f0ecc71898bf4ddc032e9f9a47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildSMulH (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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



<p>Definition at line 1809 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildSplatBuildVector() {#a55bde2ba6aacac745a29a7e50c6be007}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildSplatBuildVector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_BUILD_VECTOR with <span class="doxyComputerOutput">Src</span> replicated to fill the number of elements.</p>

<p>Declaration at line 1100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 740 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a49a5649c0de9dee3dacbab3019872923">llvm::DstOp::getLLTTy</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a2f1d58ac35de4475017aca6c5bda6d44">getNumElements</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/csemirbuilder/#af20c06f6ef57cddf624f531efbaf69e7">llvm::CSEMIRBuilder::buildConstant</a>, <a href="#af751c28a69e1d07e19dad11e4e26a70d">buildConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/csemirbuilder/#ae1fe7f5085d203a5984b2450f907b239">llvm::CSEMIRBuilder::buildFConstant</a>, <a href="#a81a7959d3e7f624343ecdf6905e251dd">buildFConstant</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a2f1d26ea9bced931d104b4dd8b26775f">getMemsetValue</a>.</p>

</div>
</div>

### buildSplatVector() {#aeea5857133a04085b450948e90fdcd1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildSplatVector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_SPLAT_VECTOR <span class="doxyComputerOutput">Val</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register with vector type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Val</span> must be a generic virtual register with scalar type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 771 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a49a5649c0de9dee3dacbab3019872923">llvm::DstOp::getLLTTy</a> and <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a>.</p>

</div>
</div>

### buildSSube() {#ab3bc600ec4a43f1914fed894c9cf9fc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildSSube (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; CarryOut, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; CarryIn)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span>, <span class="doxyComputerOutput">CarryOut</span> = G_SSUBE <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>, <span class="doxyComputerOutput">CarryInp</span>.</p>

<p>Definition at line 664 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildSSubo() {#ac7553894d44938e9e9f4016dae66b72e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildSSubo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; CarryOut, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op1)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span>, <span class="doxyComputerOutput">CarryOut</span> = G_SUBO <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>.</p>

<p>Definition at line 621 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildStepVector() {#af1b182c58ed8ff82a5958635de5ccb15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildStepVector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, unsigned Step)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_STEP_VECTOR <span class="doxyComputerOutput">Step</span>.</p>


<p>G_STEP_VECTOR returns a scalable vector of linear sequence of step <span class="doxyComputerOutput">Step</span> into <span class="doxyComputerOutput">Res</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register with scalable vector type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 822 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dstop/#a45141d649d02a2ed17b51b5419ee884d">llvm::DstOp::addDefToMIB</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="#a120dbb8d0a1ad4437456001a302a1da7">getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/evaluator-cpp/#a92efb02157b6836e1232c577d34678d6">getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a49a5649c0de9dee3dacbab3019872923">llvm::DstOp::getLLTTy</a>, <a href="#a9ec04f3692b9601036d2d4477c4c3749">getMF</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>.</p>

</div>
</div>

### buildStore() {#a87a7405685118d45876c996318829ceb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildStore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Addr, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; MMO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">G_STORE Val, Addr, MMO</span>.</p>


<p>Stores the value <span class="doxyComputerOutput">Val</span> to <span class="doxyComputerOutput">Addr</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Val</span> must be a generic virtual register.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Addr</span> must be a generic virtual register with pointer type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1001 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 468 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/srcop/#aba93d72255e1239b5209e416a1b7f199">llvm::SrcOp::addSrcToMIB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#a99fb11458708b57172b6b0df633fd4fc">llvm::SrcOp::getLLTTy</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#a103d8cfe62c1651cd70e181746f8a840">isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a580c192e2fc41ab69e61d087027ceabf">anonymous{AArch64PostLegalizerLowering.cpp}::applyNonConstInsert</a>, <a href="#aea1b43a8ad482493c4b6898bf120a176">buildStore</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a852a45fa0766bf5cb65ea6010d32330a">llvm::CallLowering::insertSRetStores</a>, <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a867592b1a0963211ea415ea436a976e5">llvm::MipsLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#aa48b853fae2f40e3e483078a944ab8d1">llvm::AArch64LegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#aabf8e09177e2ae41bc06eb1f2be342e8">llvm::MipsLegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#aa97467a5c0d54755f0e725e9310ffaa0">llvm::RISCVLegalizerInfo::legalizeIntrinsic</a> and <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a3a0c76714485f4713fed0661f961b09a">llvm::MipsCallLowering::lowerFormalArguments</a>.</p>

</div>
</div>

### buildStore() {#aea1b43a8ad482493c4b6898bf120a176}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildStore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Addr, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> PtrInfo, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dd">MachineMemOperand::Flags</a> MMOFlags=<a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddac2989bebe46c9b9fcb7a92e5ade8dde6">MachineMemOperand::MONone</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a> &amp; AAInfo=<a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert a G_STORE instruction, while constructing the <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a>.</p>

<p>Declaration at line 1007 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 482 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a87a7405685118d45876c996318829ceb">buildStore</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#a99fb11458708b57172b6b0df633fd4fc">llvm::SrcOp::getLLTTy</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="#a9ec04f3692b9601036d2d4477c4c3749">getMF</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a> and <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddaed357b1367bc90a56fefa4d1b0e17374">llvm::MachineMemOperand::MOStore</a>.</p>

</div>
</div>

### buildStrictFAdd() {#a6c47deaeb76718f7eaa6262308a72dd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildStrictFAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_STRICT_FADD <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>.</p>

<p>Definition at line 1963 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildSub() {#a4b2fab18274c6ca276053bb774c6e8c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildSub (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_SUB <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>.</p>


<p>G_SUB sets <span class="doxyComputerOutput">Res</span> to the difference of integer parameters <span class="doxyComputerOutput">Op0</span> and <span class="doxyComputerOutput">Op1</span>, truncated to their width.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span>, <span class="doxyComputerOutput">Op0</span> and <span class="doxyComputerOutput">Op1</span> must be generic virtual registers with the same (scalar or vector) type).</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Definition at line 1753 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#afc84382af091d9a0de9586212e16a195">buildLogBase2</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aa386a0afb3210b56c30181f93a434ed3">createAtomicLibcall</a>.</p>

</div>
</div>

### buildTrap() {#ad5732a98562641ab5536b451ec72c5d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildTrap (bool Debug=false)</td>
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

<p>Build and insert G_TRAP or G_DEBUGTRAP.</p>

<p>Definition at line 2286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/debug-cpp/#a3fd0c3ac7c0e9187aa5c690ef9c70ebe">Debug</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ab055c9ed89ccbcf823971615232941d1">llvm::SPIRVCallLowering::lowerCall</a>.</p>

</div>
</div>

### buildTrunc() {#abf1763199cd36c9253c6f062fa5e973e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildTrunc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_TRUNC <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>.</p>


<p>G_TRUNC extracts the low bits of a type. For a vector type each element is truncated independently before being packed into the destination.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register with scalar or vector type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> must be a generic virtual register with scalar or vector type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be smaller than <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span></p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 909 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a2aeed55e4456de4086b3592eb92dc2e2">llvm::ARMLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a867592b1a0963211ea415ea436a976e5">llvm::MipsLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#aa48b853fae2f40e3e483078a944ab8d1">llvm::AArch64LegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#af647b791a2c24c4f48aa11d1a77a5bc5">llvm::AArch64CallLowering::lowerFormalArguments</a> and <a href="/web-llvm/docs/api/classes/llvm/inlineasmlowering/#a1c9cd272afbe2a9aaca46369f9e61b79">llvm::InlineAsmLowering::lowerInlineAsm</a>.</p>

</div>
</div>

### buildUAdde() {#abfcd8132aaf36162d0ac865c74933456}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildUAdde (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; CarryOut, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; CarryIn)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span>, <span class="doxyComputerOutput">CarryOut</span> = G_UADDE <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>, <span class="doxyComputerOutput">CarryIn</span>.</p>


<p>G_UADDE sets <span class="doxyComputerOutput">Res</span> to <span class="doxyComputerOutput">Op0</span> + <span class="doxyComputerOutput">Op1</span> + <span class="doxyComputerOutput">CarryIn</span> (truncated to the bit width) and sets <span class="doxyComputerOutput">CarryOut</span> to 1 if the result overflowed in unsigned arithmetic.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span>, <span class="doxyComputerOutput">Op0</span> and <span class="doxyComputerOutput">Op1</span> must be generic virtual registers with the same scalar type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">CarryOut</span> and <span class="doxyComputerOutput">CarryIn</span> must be generic virtual registers with the same scalar type (typically s1)</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The newly created instruction.</p></dd>
</dl>


<p>Definition at line 640 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildUAddo() {#ad01ffef0e7c1bd556a76f6ead4d7d9fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildUAddo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; CarryOut, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op1)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span>, <span class="doxyComputerOutput">CarryOut</span> = G_UADDO <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>.</p>


<p>G_UADDO sets <span class="doxyComputerOutput">Res</span> to <span class="doxyComputerOutput">Op0</span> + <span class="doxyComputerOutput">Op1</span> (truncated to the bit width) and sets <span class="doxyComputerOutput">CarryOut</span> to 1 if the result overflowed in unsigned arithmetic.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span>, <span class="doxyComputerOutput">Op0</span> and <span class="doxyComputerOutput">Op1</span> must be generic virtual registers with the same scalar type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">CarryOut</span> must be generic virtual register with scalar type (typically s1)</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The newly created instruction.</p></dd>
</dl>


<p>Definition at line 603 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildUbfx() {#a942b13bfd9c50bb5af1828739035ebe1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildUbfx (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; LSB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Width)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Dst</span> = G_UBFX <span class="doxyComputerOutput">Src</span>, <span class="doxyComputerOutput">LSB</span>, <span class="doxyComputerOutput">Width</span>.</p>

<p>Definition at line 2297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildUCmp() {#a19fd5e11c62df9e228eb03dd466f5d0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildUCmp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert a <span class="doxyComputerOutput">Res</span> = G_UCMP <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register with scalar or vector type. Typically this starts as s2 or &lt;N x s2&gt;.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Op0</span> and Op1 must be generic virtual registers with the same number of elements as <span class="doxyComputerOutput">Res</span>. If <span class="doxyComputerOutput">Res</span> is a scalar, <span class="doxyComputerOutput">Op0</span> must be a scalar.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 943 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildUITOFP() {#a86e0c21f3e1e706b8d26733726c76195}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildUITOFP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_UITOFP <span class="doxyComputerOutput">Src0</span>.</p>

<p>Definition at line 2082 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildUMax() {#afae1758b4922383832826f8382b0ab54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildUMax (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_UMAX <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>.</p>

<p>Definition at line 2138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildUMin() {#af9ac32566a3d7b10a68fac371f15f643}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildUMin (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_UMIN <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>.</p>

<p>Definition at line 2132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildUMulH() {#a6bf669233b50fac473a92c3039c48c4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildUMulH (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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



<p>Definition at line 1803 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildUndef() {#a137bf40e73f82a78b6d2227ff65aeadf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildUndef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = IMPLICIT_DEF.</p>

<p>Declaration at line 1021 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 641 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>


<p>Referenced by <a href="#a901a49f9b5721ab01d9d371f96e4bcea">buildPadVectorWithUndefElements</a>, <a href="#a43b43271e5bcbbc5cc620b4dfa94937a">buildShuffleSplat</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#ac9f5ed1e7ae99c336e8ae9b4ccf10b50">llvm::AMDGPUCallLowering::passSpecialInputs</a>.</p>

</div>
</div>

### buildUnmerge() {#a1e9e055fc19307bc3c7c1be6ccd36812}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildUnmerge (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res0</span>, ... = G_UNMERGE_VALUES <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>.</p>


<p>G_UNMERGE_VALUES splits contiguous bits of the input into multiple</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>The entire register <span class="doxyComputerOutput">Res</span> (and no more) must be covered by the input registers.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>The type of all <span class="doxyComputerOutput">Res</span> registers must be identical.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1070 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 684 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#ad68c3cafb2cc7ee28ee3c7dff2a45f2e">buildDeleteTrailingVectorElements</a>, <a href="#a901a49f9b5721ab01d9d371f96e4bcea">buildPadVectorWithUndefElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvlegalizerinfo-cpp/#a77d3589f9460c3f08bc6afc49a9985c6">buildSplatSplitS64WithVL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2c32a92de16156166b3fd4de261d20a0">llvm::extractParts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9e6be5e780735b6ac4df380430d09808">llvm::extractParts</a> and <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a867592b1a0963211ea415ea436a976e5">llvm::MipsLegalizerInfo::legalizeCustom</a>.</p>

</div>
</div>

### buildUnmerge() {#a330499e5e11e1c2e82e0a8c7179f335d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildUnmerge (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1071 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 710 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### buildUnmerge() {#aeec9f9188630ac797d11be83445197b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildUnmerge (<a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert an unmerge of <span class="doxyComputerOutput">Res</span> sized pieces to cover <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>.</p>

<p>Declaration at line 1074 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 694 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>.</p>

</div>
</div>

### buildUnmerge() {#ac3c19ecc16565c150796b834a8a63963}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildUnmerge (<a href="/web-llvm/docs/api/structs/llvm/machineregisterinfo/vregattrs">MachineRegisterInfo::VRegAttrs</a> Attrs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert an unmerge of pieces with <span class="doxyComputerOutput">Attrs</span> register attributes to cover <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>.</p>

<p>Declaration at line 1078 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 702 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>.</p>

</div>
</div>

### buildURem() {#a3b08f09b085506a31ea5ac83f5d8fda1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildURem (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_UREM <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>.</p>

<p>Definition at line 1816 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildUSube() {#ac80662067cf7650fa86ffb1c9cf75249}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildUSube (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; CarryOut, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; CarryIn)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span>, <span class="doxyComputerOutput">CarryOut</span> = G_USUBE <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>, <span class="doxyComputerOutput">CarryInp</span>.</p>

<p>Definition at line 648 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildUSubo() {#a5c12041fb9751bb3445d1da887a91e66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildUSubo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; CarryOut, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op1)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span>, <span class="doxyComputerOutput">CarryOut</span> = G_USUBO <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>.</p>

<p>Definition at line 609 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildVecReduceAdd() {#aba86fb134fa3b2f01695749e0c7d84b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildVecReduceAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_ADD <span class="doxyComputerOutput">Src</span>.</p>

<p>Definition at line 2221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#ae26a44292d42d576349e053e3497c18f">anonymous{AArch64PreLegalizerCombiner.cpp}::applyExtAddvToUdotAddv</a>.</p>

</div>
</div>

### buildVecReduceAnd() {#a997b3e4a8a93ae662f2f972297415fd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildVecReduceAnd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_AND <span class="doxyComputerOutput">Src</span>.</p>

<p>Definition at line 2231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildVecReduceFAdd() {#a5e1c6502399d7e0af30cba7a9925003f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildVecReduceFAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; ScalarIn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; VecIn)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_FADD <span class="doxyComputerOutput">Src</span>.</p>


<p><span class="doxyComputerOutput">ScalarIn</span> is the scalar accumulator input to the reduction operation of <span class="doxyComputerOutput">VecIn</span>.</p>


<p>Definition at line 2182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildVecReduceFMax() {#a2cfde3d2db07050c016b443eaae2702d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildVecReduceFMax (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_FMAX <span class="doxyComputerOutput">Src</span>.</p>

<p>Definition at line 2199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildVecReduceFMaximum() {#a9a71277627a30c423608a2e598ba4d32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildVecReduceFMaximum (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_FMAXIMUM <span class="doxyComputerOutput">Src</span>.</p>

<p>Definition at line 2209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildVecReduceFMin() {#a6ededbd32ca155120e2dfd50f755688c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildVecReduceFMin (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_FMIN <span class="doxyComputerOutput">Src</span>.</p>

<p>Definition at line 2204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildVecReduceFMinimum() {#a6397aa0392a0e4e57470de5e450da0b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildVecReduceFMinimum (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_FMINIMUM <span class="doxyComputerOutput">Src</span>.</p>

<p>Definition at line 2215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildVecReduceFMul() {#a4f45e804fb39d50c4d8ec6bb1f5307a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildVecReduceFMul (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; ScalarIn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; VecIn)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_FMUL <span class="doxyComputerOutput">Src</span>.</p>


<p><span class="doxyComputerOutput">ScalarIn</span> is the scalar accumulator input to the reduction operation of <span class="doxyComputerOutput">VecIn</span>.</p>


<p>Definition at line 2192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildVecReduceMul() {#af80e0eddf323d627ac891582fcb4710e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildVecReduceMul (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_MUL <span class="doxyComputerOutput">Src</span>.</p>

<p>Definition at line 2226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildVecReduceOr() {#a1cf2e534999d7df7c847a4331924000d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildVecReduceOr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_OR <span class="doxyComputerOutput">Src</span>.</p>

<p>Definition at line 2236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildVecReduceSeqFAdd() {#a17c80c4630830047bb693ee47f58c8c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildVecReduceSeqFAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; ScalarIn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; VecIn)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_SEQ_FADD <span class="doxyComputerOutput">ScalarIn</span>, <span class="doxyComputerOutput">VecIn</span>.</p>


<p><span class="doxyComputerOutput">ScalarIn</span> is the scalar accumulator input to start the sequential reduction operation of <span class="doxyComputerOutput">VecIn</span>.</p>


<p>Definition at line 2160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildVecReduceSeqFMul() {#a4a5597c997afda710f863873c38c534e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildVecReduceSeqFMul (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; ScalarIn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; VecIn)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_SEQ_FMUL <span class="doxyComputerOutput">ScalarIn</span>, <span class="doxyComputerOutput">VecIn</span>.</p>


<p><span class="doxyComputerOutput">ScalarIn</span> is the scalar accumulator input to start the sequential reduction operation of <span class="doxyComputerOutput">VecIn</span>.</p>


<p>Definition at line 2171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildVecReduceSMax() {#ae4f70fb94cc8468f64183b6a5c75a0e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildVecReduceSMax (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_SMAX <span class="doxyComputerOutput">Src</span>.</p>

<p>Definition at line 2246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildVecReduceSMin() {#a686f39d5b9c570d44717e2cf9ca3da07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildVecReduceSMin (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_SMIN <span class="doxyComputerOutput">Src</span>.</p>

<p>Definition at line 2251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildVecReduceUMax() {#a92a4e4e7dc4ca706beb3fb702283a77f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildVecReduceUMax (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_UMAX <span class="doxyComputerOutput">Src</span>.</p>

<p>Definition at line 2256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildVecReduceUMin() {#ab0d22cadad3d84314a8847549ecc0a55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildVecReduceUMin (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_UMIN <span class="doxyComputerOutput">Src</span>.</p>

<p>Definition at line 2261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildVecReduceXor() {#a6e96b1d2ea4e991019ef283c4f588904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildVecReduceXor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VECREDUCE_XOR <span class="doxyComputerOutput">Src</span>.</p>

<p>Definition at line 2241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>

</div>
</div>

### buildVScale() {#a50ec87d072ddb08830486e9fb31ca6de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildVScale (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, unsigned MinElts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VSCALE <span class="doxyComputerOutput">MinElts</span>.</p>


<p>G_VSCALE puts the value of the runtime vscale multiplied by <span class="doxyComputerOutput">MinElts</span> into <span class="doxyComputerOutput">Res</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register with scalar type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 834 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="#a50ec87d072ddb08830486e9fb31ca6de">buildVScale</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="#a120dbb8d0a1ad4437456001a302a1da7">getContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/evaluator-cpp/#a92efb02157b6836e1232c577d34678d6">getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a49a5649c0de9dee3dacbab3019872923">llvm::DstOp::getLLTTy</a>, <a href="#a9ec04f3692b9601036d2d4477c4c3749">getMF</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargettransforminfo-cpp/#a69eeffbc38c079195008fbfb5aaad0b9">getScalarSizeInBits</a>.</p>


<p>Referenced by <a href="#aad8f2c80f7625613c869923fbe25db5b">buildVScale</a> and <a href="#a50ec87d072ddb08830486e9fb31ca6de">buildVScale</a>.</p>

</div>
</div>

### buildVScale() {#ab3480c1f40e51b1673754af7384a5078}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildVScale (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> &amp; MinElts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VSCALE <span class="doxyComputerOutput">MinElts</span>.</p>


<p>G_VSCALE puts the value of the runtime vscale multiplied by <span class="doxyComputerOutput">MinElts</span> into <span class="doxyComputerOutput">Res</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register with scalar type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 843 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dstop/#a45141d649d02a2ed17b51b5419ee884d">llvm::DstOp::addDefToMIB</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a> and <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a>.</p>

</div>
</div>

### buildVScale() {#aad8f2c80f7625613c869923fbe25db5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildVScale (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; MinElts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_VSCALE <span class="doxyComputerOutput">MinElts</span>.</p>


<p>G_VSCALE puts the value of the runtime vscale multiplied by <span class="doxyComputerOutput">MinElts</span> into <span class="doxyComputerOutput">Res</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register with scalar type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 1222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 852 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="#a50ec87d072ddb08830486e9fb31ca6de">buildVScale</a>, <a href="#a120dbb8d0a1ad4437456001a302a1da7">getContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/evaluator-cpp/#a92efb02157b6836e1232c577d34678d6">getFunction</a> and <a href="#a9ec04f3692b9601036d2d4477c4c3749">getMF</a>.</p>

</div>
</div>

### buildXor() {#af474773f09e4dbbc430d8d8df632e9fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder llvm::MachineIRBuilder::buildXor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Src1)</td>
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

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_XOR <span class="doxyComputerOutput">Op0</span>, <span class="doxyComputerOutput">Op1</span>.</p>

<p>Definition at line 1903 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aa386a0afb3210b56c30181f93a434ed3">createAtomicLibcall</a>.</p>

</div>
</div>

### buildZExt() {#a44a49b5f4dd2932058e3fbe21c098655}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildZExt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op, std::optional&lt; unsigned &gt; Flags=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_ZEXT <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>.</p>


<p>G_ZEXT produces a register of the specified width, with bits 0 to sizeof(<span class="doxyComputerOutput">Ty</span>) * 8 set to <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>. The remaining bits are 0. For a vector register, each element is extended individually.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register with scalar or vector type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> must be a generic virtual register with scalar or vector type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> must be smaller than <span class="doxyComputerOutput">Res</span></p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The newly created instruction.</p></dd>
</dl>


<p>Declaration at line 760 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 505 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#a010cf32a5c68f9701c57d7a3172f1b3f">llvm::AArch64CallLowering::lowerReturn</a>.</p>

</div>
</div>

### buildZExtInReg() {#a26edc3c3cae5a3f4d6ddd7f628b98c45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildZExtInReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op, int64_t ImmOp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and inserts <span class="doxyComputerOutput">Res</span> = <span class="doxyComputerOutput">G_AND</span> <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>, <span class="doxyComputerOutput">LowBitsSet(ImmOp)</span> Since there is no G_ZEXT_INREG like G_SEXT_INREG, the instruction is emulated using G_AND.</p>

<p>Declaration at line 808 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 586 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="#a33eb6083767372c564ea4bcf6c06eaf1">buildAnd</a>, <a href="#af751c28a69e1d07e19dad11e4e26a70d">buildConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a49a5649c0de9dee3dacbab3019872923">llvm::DstOp::getLLTTy</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ad960e1ff48d25c382b6d28e7961f074e">llvm::APInt::getLowBitsSet</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>.</p>


<p>Referenced by <a href="#a060616c6385361df8bd72cde315d4267">buildBoolExtInReg</a>.</p>

</div>
</div>

### buildZExtOrTrunc() {#a7ac5295bdfdd480a2c66ee54273ebe21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildZExtOrTrunc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_ZEXT <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>, <span class="doxyComputerOutput">Res</span> = G_TRUNC <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>, or <span class="doxyComputerOutput">Res</span> = COPY <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> depending on the differing sizes of <span class="doxyComputerOutput">Res</span> and <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>.</p>


<p>///</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register with scalar or vector type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> must be a generic virtual register with scalar or vector type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The newly created instruction.</p></dd>
</dl>


<p>Declaration at line 781 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 576 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>Reference <a href="#ab8da4d08f2c0875e9623bb712aa64303">buildExtOrTrunc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab28508dbb1f9996154ae13f70fa4f2e2">llvm::genWorkgroupQuery</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a2f1d26ea9bced931d104b4dd8b26775f">getMemsetValue</a>.</p>

</div>
</div>

### getBoolExtOp() {#a5aafc4bc2c28b6cb5d9aeb319b186d11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MachineIRBuilder::getBoolExtOp (bool IsVec, bool IsFP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The opcode of the extension the target wants to use for boolean values.</p></dd>
</dl>


<p>Declaration at line 734 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 511 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="#a9ec04f3692b9601036d2d4477c4c3749">getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#ade3f0d8b35d67c43df9425bb730a9a7c">llvm::TargetSubtargetInfo::getTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa61af767c51a95e2dd0dff2001168755a695a19c9c3ae14638be151add82755cb">llvm::TargetLoweringBase::ZeroOrNegativeOneBooleanContent</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa61af767c51a95e2dd0dff2001168755a0e2d72cfdcc49d2d189f440b3cc31dff">llvm::TargetLoweringBase::ZeroOrOneBooleanContent</a>.</p>


<p>Referenced by <a href="#a1e5b88856596e413494661b5fae9fc39">buildBoolExt</a>.</p>

</div>
</div>

### getContext() {#a120dbb8d0a1ad4437456001a302a1da7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext &amp; llvm::MachineIRBuilder::getContext ()</td>
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



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a> and <a href="#a9ec04f3692b9601036d2d4477c4c3749">getMF</a>.</p>


<p>Referenced by <a href="#ab952b8b71fdba5baaf6a083e06d71da2">buildConstant</a>, <a href="#afdce4b9880a0aed02fe487da6a613cbd">buildConstant</a>, <a href="#a41d7c53499da41b1739015f7036cf6da">buildIntrinsic</a>, <a href="#af1b182c58ed8ff82a5958635de5ccb15">buildStepVector</a>, <a href="#aad8f2c80f7625613c869923fbe25db5b">buildVScale</a>, <a href="#a50ec87d072ddb08830486e9fb31ca6de">buildVScale</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a8f17d3e92f855f675577a021e9bc2a35">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVTypeByName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#aac0431719235a7ccda58a3df4894d130">llvm::SPIRV::lowerBuiltinType</a>.</p>

</div>
</div>

### getCSEInfo() {#a2a885e28d6a7936c7442d063aea666f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GISelCSEInfo * llvm::MachineIRBuilder::getCSEInfo ()</td>
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



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/csemirbuilder/#a9c2e15b867893ec15cb49acfbb38e542">llvm::CSEMIRBuilder::buildInstr</a>.</p>

</div>
</div>

### getCSEInfo() {#a7336e3815d2fdc6dec4d59d47db6b5b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GISelCSEInfo * llvm::MachineIRBuilder::getCSEInfo ()</td>
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



<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>

</div>
</div>

### getDataLayout() {#aeb6d0a9254bc3183046873436fc7c12e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout &amp; llvm::MachineIRBuilder::getDataLayout ()</td>
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



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#a3275c50993afaf4fdd723640c2c3ca0f">llvm::Function::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a> and <a href="#a9ec04f3692b9601036d2d4477c4c3749">getMF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac5631975d77a389618f6cdb0035cc561">llvm::buildEnqueueKernel</a>, <a href="#a7e58ecea881b2ea06fee315563860e39">buildExtractVectorElementConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/csemirbuilder/#a9c2e15b867893ec15cb49acfbb38e542">llvm::CSEMIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a8f8ee7977675d9e8cdded7bda420b96e">emitLoadFromConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a1b22f5dbcd629f145563ba79bcb7ce9b">llvm::CallLowering::insertSRetOutgoingArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#aa97467a5c0d54755f0e725e9310ffaa0">llvm::RISCVLegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af5462628f10dea9944615cd509dd3634">llvm::CallLowering::lowerCall</a> and <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ab055c9ed89ccbcf823971615232941d1">llvm::SPIRVCallLowering::lowerCall</a>.</p>

</div>
</div>

### getDebugLoc() {#acfe60198abd7ecf64270c987689c6c1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DebugLoc &amp; llvm::MachineIRBuilder::getDebugLoc ()</td>
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

<p>Get the current instruction's debug location.</p>

<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#acab67f583801f5c01ee9ac2162f5e27d">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVPointerType</a>.</p>

</div>
</div>

### getDL() {#a93ab05c4fb48bd5e87965bef6ec9ac2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DebugLoc &amp; llvm::MachineIRBuilder::getDL ()</td>
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

<p>Getter for <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a>.</p>

<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a6ab34a535b1441b48a0ede2c2aa6fb98">buildConstDbgValue</a>, <a href="#a92bad84c9e323ab0a96d8d8bbb22d149">buildDirectDbgValue</a>, <a href="#ab107810eccfb0e46e47348ea9ef8d0ed">buildFIDbgValue</a>, <a href="#a5a76abb6dd3946ca5c9cd6e8f341d63c">buildIndirectDbgValue</a> and <a href="#ae04499daa8807ddb4d00e7ed18b1698f">buildInstrNoInsert</a>.</p>

</div>
</div>

### getInsertPt() {#a430daa77692b7b25f93a72d83e51964f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator llvm::MachineIRBuilder::getInsertPt ()</td>
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

<p>Current insertion point for new instructions.</p>

<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aed92c21265205e69855b23b8b25707e2">llvm::buildNDRange</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#acab67f583801f5c01ee9ac2162f5e27d">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVPointerType</a>, <a href="#a06dc2f24e1f4dea357bf6c646f5b2607">insertInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#a1ddebf0db857b4b9fd7004511b7eb393">llvm::RISCVLegalizerInfo::legalizeCustom</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#aa48b853fae2f40e3e483078a944ab8d1">llvm::AArch64LegalizerInfo::legalizeIntrinsic</a>.</p>

</div>
</div>

### getMBB() {#ac8f6c5b9180bd630c92e1126877d0b08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineBasicBlock &amp; llvm::MachineIRBuilder::getMBB ()</td>
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

<p>Getter for the basic block we currently build.</p>

<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#acab67f583801f5c01ee9ac2162f5e27d">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVPointerType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp/#a133ddcbd001fd6de4f055542a6a95595">handleMustTailForwardedRegisters</a>, <a href="#a06dc2f24e1f4dea357bf6c646f5b2607">insertInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#a1ddebf0db857b4b9fd7004511b7eb393">llvm::RISCVLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#aa48b853fae2f40e3e483078a944ab8d1">llvm::AArch64LegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#af647b791a2c24c4f48aa11d1a77a5bc5">llvm::AArch64CallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/armcalllowering/#a7f23ab7ec21b86b46d5a5e34ac33ba7d">llvm::ARMCallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a3a0c76714485f4713fed0661f961b09a">llvm::MipsCallLowering::lowerFormalArguments</a> and <a href="/web-llvm/docs/api/classes/llvm/x86calllowering/#ae22f2d3294d95f6cb262f8732eb0f479">llvm::X86CallLowering::lowerFormalArguments</a>.</p>

</div>
</div>

### getMBB() {#a7be5d9bbd5832221068ae6c93cf24d51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock &amp; llvm::MachineIRBuilder::getMBB ()</td>
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



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#ad662a74c60eeb99f6a24927479eda063">MachineIRBuilder</a>.</p>

</div>
</div>

### getMF() {#a9ec04f3692b9601036d2d4477c4c3749}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction &amp; llvm::MachineIRBuilder::getMF ()</td>
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

<p>Getter for the function we currently build.</p>

<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a580c192e2fc41ab69e61d087027ceabf">anonymous{AArch64PostLegalizerLowering.cpp}::applyNonConstInsert</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#aa66e13122dec2a32f7d1b1f7240048e2">llvm::SPIRVGlobalRegistry::assignTypeToVReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp/#af5f0f04b137494bbf8fb56286dea2762">buildAnyextOrCopy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af62f51194838248f650985e8299d7a97">llvm::buildAtomicCompareExchangeInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acec38968fb25d9da84d9d606eca35d7d">llvm::buildAtomicRMWInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7380fc2046fc70f0b6040466a1a535af">llvm::buildBarrierInst</a>, <a href="#a060616c6385361df8bd72cde315d4267">buildBoolExtInReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a42caa499245638127d7d889ff5716066">llvm::buildBoolRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a191e4c250748ed5043795f6bf3caf4e9">llvm::buildBuiltinVariableLoad</a>, <a href="#ab952b8b71fdba5baaf6a083e06d71da2">buildConstant</a>, <a href="#afdce4b9880a0aed02fe487da6a613cbd">buildConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a6aee777d2869b23ba59b88b9ceb32cfe">llvm::SPIRVGlobalRegistry::buildConstantFP</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#affb04c244423615aa0df24ee36f2de20">llvm::SPIRVGlobalRegistry::buildConstantInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvlegalizerinfo-cpp/#a45e6e22e05efa275135c8ae32f60da40">buildDefaultVLOps</a>, <a href="#a92bad84c9e323ab0a96d8d8bbb22d149">buildDirectDbgValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac5631975d77a389618f6cdb0035cc561">llvm::buildEnqueueKernel</a>, <a href="#a7e58ecea881b2ea06fee315563860e39">buildExtractVectorElementConstant</a>, <a href="#aa28f164b227803f0fef41094366c2dca">buildFConstant</a>, <a href="#a4265ff404073d12b765bc9fee4e7f186">buildFConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a881c9e75128e7e943b6d8f33606ccc74">llvm::SPIRVGlobalRegistry::buildGlobalVariable</a>, <a href="#a5a76abb6dd3946ca5c9cd6e8f341d63c">buildIndirectDbgValue</a>, <a href="#ae04499daa8807ddb4d00e7ed18b1698f">buildInstrNoInsert</a>, <a href="#a3d61feda2a7e9f526ff461c900295bc1">buildLoad</a>, <a href="#a010032df630a417383fa44deee43ac0c">buildLoadFromOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed92c21265205e69855b23b8b25707e2">llvm::buildNDRange</a>, <a href="#aded2b440bea348970816da1ecd40f2c1">buildShuffleVector</a>, <a href="#af1b182c58ed8ff82a5958635de5ccb15">buildStepVector</a>, <a href="#aea1b43a8ad482493c4b6898bf120a176">buildStore</a>, <a href="#aad8f2c80f7625613c869923fbe25db5b">buildVScale</a>, <a href="#a50ec87d072ddb08830486e9fb31ca6de">buildVScale</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvlegalizerinfo-cpp/#a3b8f2c8dafaf2b1007b8661546ce5aca">convertPtrToInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aa386a0afb3210b56c30181f93a434ed3">createAtomicLibcall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8829536a23c01dcd3a6017dccb148c90">llvm::createLibcall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b8fc31cace25c498444cd6853de598a">llvm::createLibcall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a524d3d59c93afc0f68256056ba5bfa0b">llvm::createMemLibcall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#afb7df659747f14484e642788c2fe6788">createTuple</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp/#ac2a15e60c215ba084b8efc539a6ef376">createTypeVReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05ced79f0a24215eb2699d1c356552eb">llvm::createVirtualRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a837dc9f535c4db3c1d4bc3cea1358651">llvm::CallLowering::determineAndHandleAssignments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#a2abcc0dade6e762f2145f49e3158a71c">doInsertBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a8f8ee7977675d9e8cdded7bda420b96e">emitLoadFromConstantPool</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#af160026cdf05f7d7c962d4d490d19add">generateAssignInstrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748bbd916eb5b48b009f8ee2e6a6afc9">llvm::generateAsyncCopy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a884a65fc47e7cf521d37505e1548e9ca">llvm::generateConvertInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2947a09647c5d7fc7429c90d93fd2f17">llvm::generateGroupInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a610c7b58032f5eac1b06aa0c66cadb6a">llvm::generateGroupUniformInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3abab01a19c99b6700cc0aadde16edc2">llvm::generateICarryBorrowInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a9a34bef43457f75fa60fb4186af2ef">llvm::generateImageSizeQueryInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa258d22bc5ca54e36dc15a8c3e724e52">llvm::generateIntelSubgroupsInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5c9c060a884e9461f06d7601681d2bcf">llvm::generateKernelClockInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac44c583be05bf96fc1323db172608e32">llvm::generateReadImageInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab28508dbb1f9996154ae13f70fa4f2e2">llvm::genWorkgroupQuery</a>, <a href="#a5aafc4bc2c28b6cb5d9aeb319b186d11">getBoolExtOp</a>, <a href="#a120dbb8d0a1ad4437456001a302a1da7">getContext</a>, <a href="#aeb6d0a9254bc3183046873436fc7c12e">getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a69f73e1b5f8a3e376c63293408b6786e">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeByOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#acbccd3fb66e9075690f45dea7440cf9e">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeCoopMatr</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#abeddeff35f8dd231213915a6f77f0920">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeDeviceEvent</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#aac40b88bee839e32d4f0f860282d0fc4">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeFunctionWithArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a4cd2c03c778450920cd3b53acdcb4fba">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeImage</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a0067190a151de0ad367e8d1e56c1016a">llvm::SPIRVGlobalRegistry::getOrCreateOpTypePipe</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a8cdc39b963a62003cd157541feca56f6">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeSampledImage</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#aea914eb511a3b8ebf605c62c07e8ab44">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeSampler</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a3d6978ae20178c8f9414ff980fd4e3b2">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVBoolType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadf38ec8e97afd05668e524d9ab0e60d">llvm::getOrCreateSPIRVDeviceEventPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#acdec96f14d81b2043e31f3452e440a4b">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVIntegerType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a7712aacb3f4a1a860a15ca4de83e6a9f">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a8f17d3e92f855f675577a021e9bc2a35">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVTypeByName</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp/#a133ddcbd001fd6de4f055542a6a95595">handleMustTailForwardedRegisters</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a2222b2a89839a157c1b2992743effe">llvm::insertAssignInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a5457cbda7e9b1866c1c16af5ac330273">insertBitcasts</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a33a30176a7fd636333a4e618ef109f57">llvm::CallLowering::insertSRetLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a1b22f5dbcd629f145563ba79bcb7ce9b">llvm::CallLowering::insertSRetOutgoingArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a852a45fa0766bf5cb65ea6010d32330a">llvm::CallLowering::insertSRetStores</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#aba8fa9d02ad8b557faaf41b37b714ba4">llvm::AArch64CallLowering::isEligibleForTailCallOptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a2aeed55e4456de4086b3592eb92dc2e2">llvm::ARMLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a867592b1a0963211ea415ea436a976e5">llvm::MipsLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a91b85787aa32d7f1f0d38d59a77cee68">llvm::AMDGPULegalizerInfo::legalizeMinNumMaxNum</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#ae1eb226b5600f7802dc31d1903a5040e">llvm::AMDGPUCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/armcalllowering/#af3fdfad8a2951ca4c86fd64560c550a7">llvm::ARMCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af5462628f10dea9944615cd509dd3634">llvm::CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kcalllowering/#a2c714d045da3eaad01dfd893048e9a0c">llvm::M68kCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a5344895d462c34e2c90e930471d8e4d9">llvm::MipsCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvcalllowering/#a82f1da052b54c0bd8969fea523e25066">llvm::RISCVCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ab055c9ed89ccbcf823971615232941d1">llvm::SPIRVCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/x86calllowering/#a699fa07bf5290218677fc2a1e69e0781">llvm::X86CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a90a141a0a4ccdd0ff757cac3d29f0ee6">llvm::AMDGPUCallLowering::lowerChainCall</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#af647b791a2c24c4f48aa11d1a77a5bc5">llvm::AArch64CallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/armcalllowering/#a7f23ab7ec21b86b46d5a5e34ac33ba7d">llvm::ARMCallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kcalllowering/#a74c78051669d5513b0b9616495bfc7a5">llvm::M68kCallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a3a0c76714485f4713fed0661f961b09a">llvm::MipsCallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/ppccalllowering/#ab9fec62bac8ad2e7614fdc8a5cdc5c8b">llvm::PPCCallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvcalllowering/#a8cc7d29f4f0c77bb62d3f77629678a64">llvm::RISCVCallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#af4911ff1c4fabd84b05d4529da80021e">llvm::SPIRVCallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/x86calllowering/#ae22f2d3294d95f6cb262f8732eb0f479">llvm::X86CallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasmlowering/#a1c9cd272afbe2a9aaca46369f9e61b79">llvm::InlineAsmLowering::lowerInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#a010cf32a5c68f9701c57d7a3172f1b3f">llvm::AArch64CallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/armcalllowering/#a49a30e74a8632576007b3678649c9fb9">llvm::ARMCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kcalllowering/#abfdadd18c92c595797ca5409d708f2ef">llvm::M68kCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a821ed33f62736f960fa90c585205677d">llvm::MipsCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/ppccalllowering/#a0895983a48b4fe2de9c52579431f8744">llvm::PPCCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvcalllowering/#a2a90be51e47dadfbb04df4f64465ea04">llvm::RISCVCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ac8dc1642db124c4da34fbec06040a0c4">llvm::SPIRVCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/x86calllowering/#ace03d9ed2825d1401093a441f164ecdf">llvm::X86CallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a0c3beb54f8fa06f2fd8074561a5a515c">llvm::AMDGPUCallLowering::lowerTailCall</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#ac9f5ed1e7ae99c336e8ae9b4ccf10b50">llvm::AMDGPUCallLowering::passSpecialInputs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a6f6181bdacf4ed6dda045f9c832df313">propagateSPIRVType</a>, <a href="#a0df93c0f752428162e14b54f8999172d">setInsertPt</a>, <a href="#acd5c75a12ec8c12c35de46c60d18c699">setMBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7d4f8e3bb109dd110769f33e9c00e89f">llvm::setRegClassType</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ae1fd41e303fcb42122f8a0432efcd87d">llvm::CombinerHelper::tryCombineMemCpyFamily</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64giselutils/#a9922ec95e157a3432c8ccd4a8a6a2653">llvm::AArch64GISelUtils::tryEmitBZero</a> and <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a4c12c2286b1a252d619bb618c8b5d356">llvm::CombinerHelper::tryEmitMemcpyInline</a>.</p>

</div>
</div>

### getMF() {#a0e8dc93a8e1664c946eca6f60140ea29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineFunction &amp; llvm::MachineIRBuilder::getMF ()</td>
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



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getMMRAMetadata() {#ae93b0a855cdf8afb141d16e217158683}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * llvm::MachineIRBuilder::getMMRAMetadata ()</td>
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

<p>Get the current instruction's MMRA metadata.</p>

<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Referenced by <a href="#ae04499daa8807ddb4d00e7ed18b1698f">buildInstrNoInsert</a>.</p>

</div>
</div>

### getMRI() {#ad7322f56c0659b8dc8e55567767b74d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo * llvm::MachineIRBuilder::getMRI ()</td>
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

<p>Getter for MRI.</p>

<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a50bbcbf690dd0de0a3f4abe2dd51fb55">anonymous{AArch64PostLegalizerLowering.cpp}::applyAdjustICmpImmAndPred</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp/#af5f0f04b137494bbf8fb56286dea2762">buildAnyextOrCopy</a>, <a href="#adbf5d6125fa84e067907320d93e9fab5">buildAtomicCmpXchg</a>, <a href="#acc22ffc46525708d66c036f878572523">buildAtomicCmpXchgWithSuccess</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af62f51194838248f650985e8299d7a97">llvm::buildAtomicCompareExchangeInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17fda1a191d8f69587355e32c5f15618">llvm::buildAtomicFlagInst</a>, <a href="#a497e8884b8ae421c7dadff0f0eea5e3e">buildAtomicRMW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acec38968fb25d9da84d9d606eca35d7d">llvm::buildAtomicRMWInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7380fc2046fc70f0b6040466a1a535af">llvm::buildBarrierInst</a>, <a href="#ae83cc330c36190cf8ee9618a28e9a300">buildBlockAddress</a>, <a href="#a1e5b88856596e413494661b5fae9fc39">buildBoolExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a42caa499245638127d7d889ff5716066">llvm::buildBoolRegister</a>, <a href="#a6e0f051c17bd6354aec061d308d80841">buildBrCond</a>, <a href="#aecf67aca8d78d0136244799c4182e52f">buildBrIndirect</a>, <a href="#aaf1013659ccc9708197f76c0bd724936">buildBrJT</a>, <a href="#a96b7ed72c9782cd69b2b9b341cf73112">buildBuildVectorConstant</a>, <a href="#a7acf8a5ebb4b351a451a2d63faf13294">buildBuildVectorTrunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a191e4c250748ed5043795f6bf3caf4e9">llvm::buildBuiltinVariableLoad</a>, <a href="#a3493ece271aff0f2c3d162494e3fcc81">buildCast</a>, <a href="/web-llvm/docs/api/classes/llvm/csemirbuilder/#af20c06f6ef57cddf624f531efbaf69e7">llvm::CSEMIRBuilder::buildConstant</a>, <a href="#af751c28a69e1d07e19dad11e4e26a70d">buildConstant</a>, <a href="#afdce4b9880a0aed02fe487da6a613cbd">buildConstant</a>, <a href="#a1da8389b4eb951b11309c28ad492e8d4">buildConstantPool</a>, <a href="#aff3c145b6d12a00e7432953b1c454ebc">buildConstantPtrAuth</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a4280c0cdf83d31309a8ad8d0d6815e66">llvm::SPIRVGlobalRegistry::buildConstantSampler</a>, <a href="#ad68c3cafb2cc7ee28ee3c7dff2a45f2e">buildDeleteTrailingVectorElements</a>, <a href="#ab00eba007903e9b4a69440782cd7c9c9">buildDynStackAlloc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac5631975d77a389618f6cdb0035cc561">llvm::buildEnqueueKernel</a>, <a href="#ab8da4d08f2c0875e9623bb712aa64303">buildExtOrTrunc</a>, <a href="#a2f52fec4aa17c3066db14a8d4717469d">buildExtract</a>, <a href="/web-llvm/docs/api/classes/llvm/csemirbuilder/#ae1fe7f5085d203a5984b2450f907b239">llvm::CSEMIRBuilder::buildFConstant</a>, <a href="#a81a7959d3e7f624343ecdf6905e251dd">buildFConstant</a>, <a href="#a4265ff404073d12b765bc9fee4e7f186">buildFConstant</a>, <a href="#a92664cdbeb0b24030809439993ac271d">buildFrameIndex</a>, <a href="#a0ac2ceaa32ba0511bb9e14e6edfbc329">buildGlobalValue</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a881c9e75128e7e943b6d8f33606ccc74">llvm::SPIRVGlobalRegistry::buildGlobalVariable</a>, <a href="#aaf34795e0fa82f3edac1a235f50da4c1">buildInsert</a>, <a href="/web-llvm/docs/api/classes/llvm/csemirbuilder/#a9c2e15b867893ec15cb49acfbb38e542">llvm::CSEMIRBuilder::buildInstr</a>, <a href="#a6dacb1328b30771530a48be17307efb0">buildInstr</a>, <a href="#a84f7ac7613ff133970f83e8531085353">buildIntrinsic</a>, <a href="#a3d61feda2a7e9f526ff461c900295bc1">buildLoad</a>, <a href="#a010032df630a417383fa44deee43ac0c">buildLoadFromOffset</a>, <a href="#aeede510b1aaac978daaba60dcc2817de">buildLoadInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#afc84382af091d9a0de9586212e16a195">buildLogBase2</a>, <a href="#af6aed1d3b2cf7133b73cf8bfa5122186">buildMaskLowPtrBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92b7677cd4ee158a68f41214d43bfae4">llvm::buildMemSemanticsReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed92c21265205e69855b23b8b25707e2">llvm::buildNDRange</a>, <a href="#a66aef31356eb4467a34fbcb72f1649ad">buildNeg</a>, <a href="#a16532d0d8fb47080714810131b45b75b">buildNot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a8dcc4e0c146cff251e73a2a59123683b">buildOpBitcast</a>, <a href="#a901a49f9b5721ab01d9d371f96e4bcea">buildPadVectorWithUndefElements</a>, <a href="#a7aae2634e3c0980c4f68983738b90ff7">buildPtrAdd</a>, <a href="#a43b43271e5bcbbc5cc620b4dfa94937a">buildShuffleSplat</a>, <a href="#aded2b440bea348970816da1ecd40f2c1">buildShuffleVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp/#a665946cb74a98ed20ca7e0acf68d9b03">buildSpirvTypeName</a>, <a href="#a55bde2ba6aacac745a29a7e50c6be007">buildSplatBuildVector</a>, <a href="#aeea5857133a04085b450948e90fdcd1e">buildSplatVector</a>, <a href="#af1b182c58ed8ff82a5958635de5ccb15">buildStepVector</a>, <a href="#a87a7405685118d45876c996318829ceb">buildStore</a>, <a href="#aea1b43a8ad482493c4b6898bf120a176">buildStore</a>, <a href="#aeec9f9188630ac797d11be83445197b0">buildUnmerge</a>, <a href="#ac3c19ecc16565c150796b834a8a63963">buildUnmerge</a>, <a href="#ab3480c1f40e51b1673754af7384a5078">buildVScale</a>, <a href="#a50ec87d072ddb08830486e9fb31ca6de">buildVScale</a>, <a href="#a26edc3c3cae5a3f4d6ddd7f628b98c45">buildZExtInReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8829536a23c01dcd3a6017dccb148c90">llvm::createLibcall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05ced79f0a24215eb2699d1c356552eb">llvm::createVirtualRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a8f8ee7977675d9e8cdded7bda420b96e">emitLoadFromConstantPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2d2d83de91f5be342b9beeb36a6e8c2">llvm::generateCoopMatrInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2947a09647c5d7fc7429c90d93fd2f17">llvm::generateGroupInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a610c7b58032f5eac1b06aa0c66cadb6a">llvm::generateGroupUniformInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3abab01a19c99b6700cc0aadde16edc2">llvm::generateICarryBorrowInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a9a34bef43457f75fa60fb4186af2ef">llvm::generateImageSizeQueryInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0fc9e18e3a0aeb8c6426eae57a1ab61e">llvm::generateLoadStoreInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac44c583be05bf96fc1323db172608e32">llvm::generateReadImageInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a519951c274914148448a0942705a1fc2">llvm::generateSampleImageInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aabf50e80c80c98fd130ff1cb70553742">llvm::generateSpecConstantInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab28508dbb1f9996154ae13f70fa4f2e2">llvm::genWorkgroupQuery</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a2f1d26ea9bced931d104b4dd8b26775f">getMemsetValue</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a0d65d879a707f0fcaa221e60be3a1a54">llvm::SPIRVGlobalRegistry::getOrCreateGlobalVariableWithBinding</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp/#a4cdd09538b5a878eff565f40b9c5776a">GetSpirvImageTypeName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a5457cbda7e9b1866c1c16af5ac330273">insertBitcasts</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#a14251e7cc7c001be8b83a76caa7acd92">llvm::AArch64LegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a2aeed55e4456de4086b3592eb92dc2e2">llvm::ARMLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a867592b1a0963211ea415ea436a976e5">llvm::MipsLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#a1ddebf0db857b4b9fd7004511b7eb393">llvm::RISCVLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/x86legalizerinfo/#a088615ef5bf315b474c43859307730ec">llvm::X86LegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#aa48b853fae2f40e3e483078a944ab8d1">llvm::AArch64LegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#aa97467a5c0d54755f0e725e9310ffaa0">llvm::RISCVLegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#aac0431719235a7ccda58a3df4894d130">llvm::SPIRV::lowerBuiltinType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ab055c9ed89ccbcf823971615232941d1">llvm::SPIRVCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#af4911ff1c4fabd84b05d4529da80021e">llvm::SPIRVCallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasmlowering/#a1c9cd272afbe2a9aaca46369f9e61b79">llvm::InlineAsmLowering::lowerInlineAsm</a>, <a href="#a0f2bb4d63ad6914f3783967bf881a14b">materializePtrAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7d4f8e3bb109dd110769f33e9c00e89f">llvm::setRegClassType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64giselutils/#a9922ec95e157a3432c8ccd4a8a6a2653">llvm::AArch64GISelUtils::tryEmitBZero</a>.</p>

</div>
</div>

### getMRI() {#a94a2451b7b4e853eb884be8d8e3c69d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineRegisterInfo * llvm::MachineIRBuilder::getMRI ()</td>
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



<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>

</div>
</div>

### getObserver() {#a035ff811981517c4885338606c70d928}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GISelChangeObserver * llvm::MachineIRBuilder::getObserver ()</td>
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



<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>.</p>

</div>
</div>

### getPCSections() {#a4d965aceed7f5b45e11799d0fa0b36e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * llvm::MachineIRBuilder::getPCSections ()</td>
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

<p>Get the current instruction's PC sections metadata.</p>

<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Referenced by <a href="#ae04499daa8807ddb4d00e7ed18b1698f">buildInstrNoInsert</a>.</p>

</div>
</div>

### getState() {#adc500b8cc6b22cec3d3cdc03234f23b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineIRBuilderState &amp; llvm::MachineIRBuilder::getState ()</td>
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

<p>Getter for the State.</p>

<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>

</div>
</div>

### getTII() {#a35384c47e5ca9690216b1aa8fed5a8c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo &amp; llvm::MachineIRBuilder::getTII ()</td>
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



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#acaf0ebafd584479c2c6a1a782ff149f9">llvm::CombinerHelper::applyCombineMulToShl</a>, <a href="#a92bad84c9e323ab0a96d8d8bbb22d149">buildDirectDbgValue</a>, <a href="#a5a76abb6dd3946ca5c9cd6e8f341d63c">buildIndirectDbgValue</a>, <a href="#ae04499daa8807ddb4d00e7ed18b1698f">buildInstrNoInsert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aa386a0afb3210b56c30181f93a434ed3">createAtomicLibcall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8829536a23c01dcd3a6017dccb148c90">llvm::createLibcall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a524d3d59c93afc0f68256056ba5bfa0b">llvm::createMemLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#acab67f583801f5c01ee9ac2162f5e27d">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVPointerType</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#a1ddebf0db857b4b9fd7004511b7eb393">llvm::RISCVLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a5344895d462c34e2c90e930471d8e4d9">llvm::MipsCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ab055c9ed89ccbcf823971615232941d1">llvm::SPIRVCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ac8dc1642db124c4da34fbec06040a0c4">llvm::SPIRVCallLowering::lowerReturn</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipslegalizerinfo-cpp/#a8a476245face103d65c519250257e499">SelectMSA3OpIntrinsic</a>.</p>

</div>
</div>

### insertInstr() {#a06dc2f24e1f4dea357bf6c646f5b2607}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::insertInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> MIB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert an existing instruction at the insertion point.</p>

<p>Declaration at line 429 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="#a430daa77692b7b25f93a72d83e51964f">getInsertPt</a>, <a href="#ac8f6c5b9180bd630c92e1126877d0b08">getMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3435a2381e60e842e915f85c931b7dde">llvm::MachineBasicBlock::insert</a> and <a href="#a6baa0ad8a95dcded4f50f3bf0d20c94d">recordInsertion</a>.</p>


<p>Referenced by <a href="#a6ab34a535b1441b48a0ede2c2aa6fb98">buildConstDbgValue</a>, <a href="#a92bad84c9e323ab0a96d8d8bbb22d149">buildDirectDbgValue</a>, <a href="#ab107810eccfb0e46e47348ea9ef8d0ed">buildFIDbgValue</a>, <a href="#a5a76abb6dd3946ca5c9cd6e8f341d63c">buildIndirectDbgValue</a>, <a href="#a8bc92b8a902afb7675480ecc729a66d4">buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#ae1eb226b5600f7802dc31d1903a5040e">llvm::AMDGPUCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/armcalllowering/#af3fdfad8a2951ca4c86fd64560c550a7">llvm::ARMCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kcalllowering/#a2c714d045da3eaad01dfd893048e9a0c">llvm::M68kCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a5344895d462c34e2c90e930471d8e4d9">llvm::MipsCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvcalllowering/#a82f1da052b54c0bd8969fea523e25066">llvm::RISCVCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/x86calllowering/#a699fa07bf5290218677fc2a1e69e0781">llvm::X86CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasmlowering/#a1c9cd272afbe2a9aaca46369f9e61b79">llvm::InlineAsmLowering::lowerInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#a010cf32a5c68f9701c57d7a3172f1b3f">llvm::AArch64CallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/armcalllowering/#a49a30e74a8632576007b3678649c9fb9">llvm::ARMCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kcalllowering/#abfdadd18c92c595797ca5409d708f2ef">llvm::M68kCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a821ed33f62736f960fa90c585205677d">llvm::MipsCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/ppccalllowering/#a0895983a48b4fe2de9c52579431f8744">llvm::PPCCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvcalllowering/#a2a90be51e47dadfbb04df4f64465ea04">llvm::RISCVCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/x86calllowering/#ace03d9ed2825d1401093a441f164ecdf">llvm::X86CallLowering::lowerReturn</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a0c3beb54f8fa06f2fd8074561a5a515c">llvm::AMDGPUCallLowering::lowerTailCall</a>.</p>

</div>
</div>

### isObservingChanges() {#ac79fef5aa90485941b9c604ece34199d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineIRBuilder::isObservingChanges ()</td>
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



<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>

</div>
</div>

### materializePtrAdd() {#a0f2bb4d63ad6914f3783967bf881a14b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; MachineInstrBuilder &gt; MachineIRBuilder::materializePtrAdd (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; Res, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Op0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> ValueTy, uint64_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Materialize and insert <span class="doxyComputerOutput">Res</span> = G_PTR_ADD <span class="doxyComputerOutput">Op0</span>, (G_CONSTANT <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span>)</p>


<p>G_PTR_ADD adds <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> bytes to the pointer specified by <span class="doxyComputerOutput">Op0</span>, storing the resulting pointer in <span class="doxyComputerOutput">Res</span>. If <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> is zero then no G_PTR_ADD or G_CONSTANT will be created and</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>Op0 will be assigned to <span class="doxyComputerOutput">Res</span>.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Op0</span> must be a generic virtual register with pointer type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">ValueTy</span> must be a scalar type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be 0. This is to detect confusion between <a href="#a0f2bb4d63ad6914f3783967bf881a14b">materializePtrAdd()</a> and <a href="#a7aae2634e3c0980c4f68983738b90ff7">buildPtrAdd()</a>.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Postcondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> will either be a new generic virtual register of the same type as <span class="doxyComputerOutput">Op0</span> or <span class="doxyComputerOutput">Op0</span> itself.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for the newly created instruction.</p></dd>
</dl>


<p>Declaration at line 536 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af751c28a69e1d07e19dad11e4e26a70d">buildConstant</a>, <a href="#a7aae2634e3c0980c4f68983738b90ff7">buildPtrAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a9694f2906cfe1d6d35bbe6742c67dff0">llvm::MachineRegisterInfo::createGenericVirtualRegister</a>, <a href="#ad7322f56c0659b8dc8e55567767b74d6">getMRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a33a30176a7fd636333a4e618ef109f57">llvm::CallLowering::insertSRetLoads</a> and <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a852a45fa0766bf5cb65ea6010d32330a">llvm::CallLowering::insertSRetStores</a>.</p>

</div>
</div>

### setChangeObserver() {#af69cfe118f734f35607c8fd4615ea1bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineIRBuilder::setChangeObserver (<a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver">GISelChangeObserver</a> &amp; Observer)</td>
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



<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a8d69fb9fe28f38bfe61a276caec92263">MachineIRBuilder</a>.</p>

</div>
</div>

### setCSEInfo() {#ad2a55990c65a2e9965e91c74a293df22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineIRBuilder::setCSEInfo (<a href="/web-llvm/docs/api/classes/llvm/giselcseinfo">GISelCSEInfo</a> * Info)</td>
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



<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>.</p>

</div>
</div>

### setDebugLoc() {#ac444a61cbfb8a46d48688a530e5defe1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineIRBuilder::setDebugLoc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL)</td>
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

<p>Set the debug location to <span class="doxyComputerOutput">DL</span> for all the next build instructions.</p>

<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/structs/llvm/machineirbuilderstate/#a2abf68a06724188700320d207c6c3a4a">llvm::MachineIRBuilderState::DL</a>.</p>


<p>Referenced by <a href="#a7d5d8e859928cc003454a2ba18372a71">MachineIRBuilder</a> and <a href="#ab24db762f0912a99f1e4d9e44eaeaa44">setInstrAndDebugLoc</a>.</p>

</div>
</div>

### setInsertPt() {#a0df93c0f752428162e14b54f8999172d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineIRBuilder::setInsertPt (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> II)</td>
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

<p>Set the insertion point before the specified position.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>MBB must be in <a href="#a9ec04f3692b9601036d2d4477c4c3749">getMF()</a>.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>II must be a valid iterator in MBB.</p></dd>
</dl>


<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9ec04f3692b9601036d2d4477c4c3749">getMF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#aafb37937e5f21c12443bd5278264d08b">fixupPHIOpBanks</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#af160026cdf05f7d7c962d4d490d19add">generateAssignInstrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a5457cbda7e9b1866c1c16af5ac330273">insertBitcasts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a307848f42e24813c2b6a55b8d8959fa4">insertInlineAsmProcess</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#ae10045fb6d9eaa95d29bee13a3abfb39">insertSpirvDecorations</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#a1ddebf0db857b4b9fd7004511b7eb393">llvm::RISCVLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#aa48b853fae2f40e3e483078a944ab8d1">llvm::AArch64LegalizerInfo::legalizeIntrinsic</a>, <a href="#a6149c9a2642b91bfdb471868a7f8bd1f">MachineIRBuilder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2d5aaa74bb3796fbcd85861222730ab">llvm::processInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a6f6181bdacf4ed6dda045f9c832df313">propagateSPIRVType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a3a0acd458319c9256fa67a622bbfd9d6">removeImplicitFallthroughs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a2d4e715bbecedf15f5f072b1be7efdb5">selectOpBitcasts</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a4a0932ba53071b318a28853918d6e65b">setInsertPtAfterDef</a>.</p>

</div>
</div>

### setInstrAndDebugLoc() {#ab24db762f0912a99f1e4d9e44eaeaa44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineIRBuilder::setInstrAndDebugLoc (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>Set the insertion point to before MI, and set the debug loc to MI's loc.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>MI must be in <a href="#a9ec04f3692b9601036d2d4477c4c3749">getMF()</a>.</p></dd>
</dl>


<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ac444a61cbfb8a46d48688a530e5defe1">setDebugLoc</a> and <a href="#a4cac2a17ab11d53dd0a49871b80f5c7a">setInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a50bbcbf690dd0de0a3f4abe2dd51fb55">anonymous{AArch64PostLegalizerLowering.cpp}::applyAdjustICmpImmAndPred</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#a9bddeb3377e91345c52d28658dad61a3">anonymous{AArch64PreLegalizerCombiner.cpp}::applyICmpRedundantTrunc</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a79c39eb0fd06bbc443b66f4b6d6711af">anonymous{AArch64PostLegalizerLowering.cpp}::applyINS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#ac9275cee4b272a43dca3299ab8b6144c">anonymous{AArch64PostLegalizerLowering.cpp}::applyLowerVectorFCMP</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsregisterbankinfo/#a1e12ed6a5b2d3f3dd790e2c48f7d7906">llvm::MipsRegisterBankInfo::applyMappingImpl</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a580c192e2fc41ab69e61d087027ceabf">anonymous{AArch64PostLegalizerLowering.cpp}::applyNonConstInsert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64giselutils/#a9922ec95e157a3432c8ccd4a8a6a2653">llvm::AArch64GISelUtils::tryEmitBZero</a>.</p>

</div>
</div>

### setMMRAMetadata() {#ab2ef6f73b6f2821c0852ab1a60866a3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineIRBuilder::setMMRAMetadata (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * MMRA)</td>
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

<p>Set the PC sections metadata to <span class="doxyComputerOutput">MD</span> for all the next build instructions.</p>

<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a4cac2a17ab11d53dd0a49871b80f5c7a">setInstr</a>.</p>

</div>
</div>

### setPCSections() {#ab86e7a422665e421ea6e21cbf1902d7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineIRBuilder::setPCSections (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * MD)</td>
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

<p>Set the PC sections metadata to <span class="doxyComputerOutput">MD</span> for all the next build instructions.</p>

<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a4cac2a17ab11d53dd0a49871b80f5c7a">setInstr</a>.</p>

</div>
</div>

### setState() {#af66f20f7acbbf9bbb0585aeaa2dcfdbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineIRBuilder::setState (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machineirbuilderstate">MachineIRBuilderState</a> &amp; NewState)</td>
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

<p>Setter for the State.</p>

<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>

</div>
</div>

### stopObservingChanges() {#a7fc63d7dce70789203fc3966a2c08243}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineIRBuilder::stopObservingChanges ()</td>
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



<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizer/#a80314c2b261b78cb7335a265f43ba1b5">llvm::Legalizer::legalizeMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### recordInsertion() {#a6baa0ad8a95dcded4f50f3bf0d20c94d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineIRBuilder::recordInsertion (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * InsertedInstr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a06dc2f24e1f4dea357bf6c646f5b2607">insertInstr</a>.</p>

</div>
</div>

### validateBinaryOp() {#a9856f0ee59ced7e9724315502ea9a380}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineIRBuilder::validateBinaryOp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Op0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Op1)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>.</p>


<p>Referenced by <a href="#a6dacb1328b30771530a48be17307efb0">buildInstr</a>.</p>

</div>
</div>

### validateSelectOp() {#a91a10c5f7ca3b7a86768cb33f8955b5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineIRBuilder::validateSelectOp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> ResTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> TstTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Op0Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Op1Ty)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 1205 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa911a7e9e51b7ed20810fc819efe6a26">llvm::LLT::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a9d825f5954d7bd527aea490668c624c6">llvm::LLT::isPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>.</p>


<p>Referenced by <a href="#a6dacb1328b30771530a48be17307efb0">buildInstr</a>.</p>

</div>
</div>

### validateShiftOp() {#a9c8154c310c33839a5d134b63c4d9cb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineIRBuilder::validateShiftOp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Op0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Op1)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>.</p>


<p>Referenced by <a href="#a6dacb1328b30771530a48be17307efb0">buildInstr</a>.</p>

</div>
</div>

### validateTruncExt() {#adfd8cf26645132e9a23697eed85685e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineIRBuilder::validateTruncExt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Src, bool IsExtend)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 1186 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa911a7e9e51b7ed20810fc819efe6a26">llvm::LLT::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#addaa86bfa4ca26b7f366cbdd868f99bf">llvm::details::FixedOrScalableQuantity&lt; TypeSize, uint64_t &gt;::isKnownGT</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a83e6442f8ebefccdb5e089732fe397ac">llvm::details::FixedOrScalableQuantity&lt; TypeSize, uint64_t &gt;::isKnownLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>.</p>


<p>Referenced by <a href="#a6dacb1328b30771530a48be17307efb0">buildInstr</a>.</p>

</div>
</div>

### validateUnaryOp() {#ae63e90ab103cd2159b9431b5ed5e9a53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineIRBuilder::validateUnaryOp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Op0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>.</p>


<p>Referenced by <a href="#a6dacb1328b30771530a48be17307efb0">buildInstr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getOpcodeForMerge() {#ad8ef2c990e66f323d8b61022a4af9ab7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MachineIRBuilder::getOpcodeForMerge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; DstOp, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &gt; SrcOps)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 673 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### State {#a786dd19ce6843c72e9a16e8b0c886517}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineIRBuilderState llvm::MachineIRBuilder::State</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Setters for the insertion point.



<p>Set the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> where to build instructions.</p>


### setInstr {#a4cac2a17ab11d53dd0a49871b80f5c7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineIRBuilder::setInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>Set the insertion point to before MI.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>MI must be in <a href="#a9ec04f3692b9601036d2d4477c4c3749">getMF()</a>.</p></dd>
</dl>


<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#acd5c75a12ec8c12c35de46c60d18c699">setMBB</a>, <a href="#ab2ef6f73b6f2821c0852ab1a60866a3d">setMMRAMetadata</a> and <a href="#ab86e7a422665e421ea6e21cbf1902d7c">setPCSections</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#af647b791a2c24c4f48aa11d1a77a5bc5">llvm::AArch64CallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/armcalllowering/#a7f23ab7ec21b86b46d5a5e34ac33ba7d">llvm::ARMCallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/x86calllowering/#ae22f2d3294d95f6cb262f8732eb0f479">llvm::X86CallLowering::lowerFormalArguments</a>, <a href="#a7d5d8e859928cc003454a2ba18372a71">MachineIRBuilder</a> and <a href="#ab24db762f0912a99f1e4d9e44eaeaa44">setInstrAndDebugLoc</a>.</p>

</div>
</div>

### setMBB {#acd5c75a12ec8c12c35de46c60d18c699}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineIRBuilder::setMBB (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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

<p>Set the insertion point to the end of <span class="doxyComputerOutput">MBB</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">MBB</span> must be contained by <a href="#a9ec04f3692b9601036d2d4477c4c3749">getMF()</a>.</p></dd>
</dl>


<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9ec04f3692b9601036d2d4477c4c3749">getMF</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ab055c9ed89ccbcf823971615232941d1">llvm::SPIRVCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#af647b791a2c24c4f48aa11d1a77a5bc5">llvm::AArch64CallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/armcalllowering/#a7f23ab7ec21b86b46d5a5e34ac33ba7d">llvm::ARMCallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/x86calllowering/#ae22f2d3294d95f6cb262f8732eb0f479">llvm::X86CallLowering::lowerFormalArguments</a> and <a href="#a4cac2a17ab11d53dd0a49871b80f5c7a">setInstr</a>.</p>

</div>
</div>

### setMF {#af0d9669bbadd4d5e1d75c3c833c8d5ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineIRBuilder::setMF (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizer/#a80314c2b261b78cb7335a265f43ba1b5">llvm::Legalizer::legalizeMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ab055c9ed89ccbcf823971615232941d1">llvm::SPIRVCallLowering::lowerCall</a>, <a href="#a6149c9a2642b91bfdb471868a7f8bd1f">MachineIRBuilder</a> and <a href="#aa03c7e0eb5346e000177cb95b910cc71">MachineIRBuilder</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
