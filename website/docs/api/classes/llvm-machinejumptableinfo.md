---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/machinejumptableinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MachineJumpTableInfo` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MachineJumpTableInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinejumptableinfo-h">llvm/CodeGen/MachineJumpTableInfo.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">JTEntryKind { <a href="#aaa21facdbb167f7c33d21907b8e5b9d3">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#aaa21facdbb167f7c33d21907b8e5b9d3">JTEntryKind</a> - This enum indicates how each entry of the jump table is represented and emitted. <a href="#aaa21facdbb167f7c33d21907b8e5b9d3">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e51fede2625324f2e23fccc99ace42d">MachineJumpTableInfo</a> (JTEntryKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aaa21facdbb167f7c33d21907b8e5b9d3">JTEntryKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab63740cb84cbbb0300d8fd6cf987928d">getEntryKind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d6ef9167ddc2ae5fdf29a41cbaa5202">getEntrySize</a> (const DataLayout &amp;TD) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getEntrySize - Return the size of each entry in the jump table. <a href="#a4d6ef9167ddc2ae5fdf29a41cbaa5202">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0097819d1d3f4c8eca96c9d9ac4fa0d">getEntryAlignment</a> (const DataLayout &amp;TD) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getEntryAlignment - Return the alignment of each entry in the jump table. <a href="#ab0097819d1d3f4c8eca96c9d9ac4fa0d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a48ea8ae9371565b98b24668016e5ef">createJumpTableIndex</a> (const std::vector&lt; MachineBasicBlock * &gt; &amp;DestBBs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createJumpTableIndex - Create a new jump table. <a href="#a5a48ea8ae9371565b98b24668016e5ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a519c867ae285099cc58e9bfad73a8895">isEmpty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isEmpty - Return true if there are no jump tables. <a href="#a519c867ae285099cc58e9bfad73a8895">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/machinejumptableentry">MachineJumpTableEntry</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9c60f4a0193375a5dd205fb945107a8">getJumpTables</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8399f4d8dfa10432948d8da0ef0e6674">updateJumpTableEntryHotness</a> (size_t JTI, MachineFunctionDataHotness Hotness)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4884f00bcde9528a64e1c18adc789641">RemoveJumpTable</a> (unsigned Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RemoveJumpTable - Mark the specific index as being dead. <a href="#a4884f00bcde9528a64e1c18adc789641">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d850b9f4484d7ec9a8ab1880922dcb5">RemoveMBBFromJumpTables</a> (MachineBasicBlock *MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RemoveMBBFromJumpTables - If MBB is present in any jump tables, remove it. <a href="#a0d850b9f4484d7ec9a8ab1880922dcb5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a20b9072a0cd65db50bed95c12e915b">ReplaceMBBInJumpTables</a> (MachineBasicBlock *Old, MachineBasicBlock *New)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ReplaceMBBInJumpTables - If Old is the target of any jump tables, update the jump tables to branch to New instead. <a href="#a1a20b9072a0cd65db50bed95c12e915b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a729a069c6d2880c2c75148c61998c129">ReplaceMBBInJumpTable</a> (unsigned Idx, MachineBasicBlock *Old, MachineBasicBlock *New)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ReplaceMBBInJumpTable - If Old is a target of the jump tables, update the jump table to branch to New instead. <a href="#a729a069c6d2880c2c75148c61998c129">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f4b116ba160a0fb57241dee011905e6">print</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print - Used by the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> printer to print information about jump tables. <a href="#a2f4b116ba160a0fb57241dee011905e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a723eff4a497357d7c8602abd695daa11">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>dump - Call to stderr. <a href="#a723eff4a497357d7c8602abd695daa11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aaa21facdbb167f7c33d21907b8e5b9d3">JTEntryKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41fed3e29345a23866eac293ab161a8d">EntryKind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/machinejumptableentry">MachineJumpTableEntry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b2a87a24e0ecdb058314bd056475b39">JumpTables</a></td>
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


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinejumptableinfo-h">MachineJumpTableInfo.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### JTEntryKind {#aaa21facdbb167f7c33d21907b8e5b9d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MachineJumpTableInfo::JTEntryKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#aaa21facdbb167f7c33d21907b8e5b9d3">JTEntryKind</a> - This enum indicates how each entry of the jump table is represented and emitted.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EK_BlockAddress<a id="aaa21facdbb167f7c33d21907b8e5b9d3ab0c4687afc1a6858d37711a814f8f5b3"></a></td>
<td class="doxyEnumItemDescription">EK_BlockAddress - Each entry is a plain address of block, e.g.: .word LBB123</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EK_GPRel64BlockAddress<a id="aaa21facdbb167f7c33d21907b8e5b9d3aba174e822c60ce5af99bdb57ab3ec640"></a></td>
<td class="doxyEnumItemDescription">EK_GPRel64BlockAddress - Each entry is an address of block, encoded with a relocation as gp-relative, e.g.: .gpdword LBB123</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EK_GPRel32BlockAddress<a id="aaa21facdbb167f7c33d21907b8e5b9d3a0145ef8496d090993849ec0d7ca947f7"></a></td>
<td class="doxyEnumItemDescription">EK_GPRel32BlockAddress - Each entry is an address of block, encoded with a relocation as gp-relative, e.g.: .gprel32 LBB123</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EK_LabelDifference32<a id="aaa21facdbb167f7c33d21907b8e5b9d3a6e05991949952d4e85600b0868dcd803"></a></td>
<td class="doxyEnumItemDescription">EK_LabelDifference32 - Each entry is the address of the block minus the address of the jump table</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EK_LabelDifference64<a id="aaa21facdbb167f7c33d21907b8e5b9d3a9f3683fb3f6e9f802d817742cf08a1a5"></a></td>
<td class="doxyEnumItemDescription">EK_LabelDifference64 - Each entry is the address of the block minus the address of the jump table</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EK_Inline<a id="aaa21facdbb167f7c33d21907b8e5b9d3a0c8edab8f0150200196e0c217e343058"></a></td>
<td class="doxyEnumItemDescription">EK_Inline - Jump table entries are emitted inline at their point of use</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EK_Custom32<a id="aaa21facdbb167f7c33d21907b8e5b9d3a9e655fb625d744f96e03aed78ca85707"></a></td>
<td class="doxyEnumItemDescription">EK_Custom32 - Each entry is a 32-bit value that is custom lowered by the <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#acf30ced2ac2474a0dd5af2e3417c7b7d">TargetLowering::LowerCustomJumpTableEntry</a> hook</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinejumptableinfo-h">MachineJumpTableInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MachineJumpTableInfo() {#a8e51fede2625324f2e23fccc99ace42d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineJumpTableInfo::MachineJumpTableInfo (<a href="#aaa21facdbb167f7c33d21907b8e5b9d3">JTEntryKind</a> Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinejumptableinfo-h">MachineJumpTableInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createJumpTableIndex() {#a5a48ea8ae9371565b98b24668016e5ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MachineJumpTableInfo::createJumpTableIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; DestBBs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>createJumpTableIndex - Create a new jump table.</p>


<p>Create a new jump table entry in the jump table info.</p>


<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinejumptableinfo-h">MachineJumpTableInfo.h</a>, definition at line 1361 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunction-cpp">MachineFunction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/switchcg/switchlowering/#ae706b72bcadad3acf12a239b257aabc6">llvm::SwitchCG::SwitchLowering::buildJumpTable</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a751f59893007a8fdcc892d81119abc82">llvm::VETargetLowering::emitSjLjDispatchBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a4e8962fa2139c288809acff971691109">llvm::MIRParserImpl::initializeJumpTableInfo</a>.</p>

</div>
</div>

### dump() {#a723eff4a497357d7c8602abd695daa11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void MachineJumpTableInfo::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>dump - Call to stderr.</p>

<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinejumptableinfo-h">MachineJumpTableInfo.h</a>, definition at line 1434 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunction-cpp">MachineFunction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a2f4b116ba160a0fb57241dee011905e6">print</a>.</p>

</div>
</div>

### getEntryAlignment() {#ab0097819d1d3f4c8eca96c9d9ac4fa0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MachineJumpTableInfo::getEntryAlignment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; TD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getEntryAlignment - Return the alignment of each entry in the jump table.</p>


<p>Return the alignment of each entry in the jump table.</p>


<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinejumptableinfo-h">MachineJumpTableInfo.h</a>, definition at line 1340 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunction-cpp">MachineFunction.cpp</a>.</p>


<p>References <a href="#aaa21facdbb167f7c33d21907b8e5b9d3ab0c4687afc1a6858d37711a814f8f5b3">EK_BlockAddress</a>, <a href="#aaa21facdbb167f7c33d21907b8e5b9d3a9e655fb625d744f96e03aed78ca85707">EK_Custom32</a>, <a href="#aaa21facdbb167f7c33d21907b8e5b9d3a0145ef8496d090993849ec0d7ca947f7">EK_GPRel32BlockAddress</a>, <a href="#aaa21facdbb167f7c33d21907b8e5b9d3aba174e822c60ce5af99bdb57ab3ec640">EK_GPRel64BlockAddress</a>, <a href="#aaa21facdbb167f7c33d21907b8e5b9d3a0c8edab8f0150200196e0c217e343058">EK_Inline</a>, <a href="#aaa21facdbb167f7c33d21907b8e5b9d3a6e05991949952d4e85600b0868dcd803">EK_LabelDifference32</a>, <a href="#aaa21facdbb167f7c33d21907b8e5b9d3a9f3683fb3f6e9f802d817742cf08a1a5">EK_LabelDifference64</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a4ed9cb07b066ca1f510e65f375aca091">llvm::DataLayout::getABIIntegerTypeAlignment</a>, <a href="#ab63740cb84cbbb0300d8fd6cf987928d">getEntryKind</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#af46786371f2d40a54174ac9c9abfd12f">llvm::DataLayout::getPointerABIAlignment</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>

</div>
</div>

### getEntryKind() {#ab63740cb84cbbb0300d8fd6cf987928d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JTEntryKind llvm::MachineJumpTableInfo::getEntryKind ()</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinejumptableinfo-h">MachineJumpTableInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a144cc64259d65d3f419f9d176fcf8078">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a52b44307c581360f228fe357414b2784">llvm::AsmPrinter::emitJumpTableInfo</a>, <a href="#ab0097819d1d3f4c8eca96c9d9ac4fa0d">getEntryAlignment</a> and <a href="#a4d6ef9167ddc2ae5fdf29a41cbaa5202">getEntrySize</a>.</p>

</div>
</div>

### getEntrySize() {#a4d6ef9167ddc2ae5fdf29a41cbaa5202}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MachineJumpTableInfo::getEntrySize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; TD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getEntrySize - Return the size of each entry in the jump table.</p>


<p>Return the size of each entry in the jump table.</p>


<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinejumptableinfo-h">MachineJumpTableInfo.h</a>, definition at line 1320 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunction-cpp">MachineFunction.cpp</a>.</p>


<p>References <a href="#aaa21facdbb167f7c33d21907b8e5b9d3ab0c4687afc1a6858d37711a814f8f5b3">EK_BlockAddress</a>, <a href="#aaa21facdbb167f7c33d21907b8e5b9d3a9e655fb625d744f96e03aed78ca85707">EK_Custom32</a>, <a href="#aaa21facdbb167f7c33d21907b8e5b9d3a0145ef8496d090993849ec0d7ca947f7">EK_GPRel32BlockAddress</a>, <a href="#aaa21facdbb167f7c33d21907b8e5b9d3aba174e822c60ce5af99bdb57ab3ec640">EK_GPRel64BlockAddress</a>, <a href="#aaa21facdbb167f7c33d21907b8e5b9d3a0c8edab8f0150200196e0c217e343058">EK_Inline</a>, <a href="#aaa21facdbb167f7c33d21907b8e5b9d3a6e05991949952d4e85600b0868dcd803">EK_LabelDifference32</a>, <a href="#aaa21facdbb167f7c33d21907b8e5b9d3a9f3683fb3f6e9f802d817742cf08a1a5">EK_LabelDifference64</a>, <a href="#ab63740cb84cbbb0300d8fd6cf987928d">getEntryKind</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#ac4d8e60ce9a5b62049e6b71f19a24c8b">llvm::DataLayout::getPointerSize</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getJumpTables() {#af9c60f4a0193375a5dd205fb945107a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::vector&lt; MachineJumpTableEntry &gt; &amp; llvm::MachineJumpTableInfo::getJumpTables ()</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinejumptableinfo-h">MachineJumpTableInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a144cc64259d65d3f419f9d176fcf8078">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a11d81bc488e34bd6e757c2831ecc5e42">llvm::ARMAsmPrinter::emitJumpTableAddrs</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a7b744276265a7587d11961d5cbf82dd0">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::emitJumpTableInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a52b44307c581360f228fe357414b2784">llvm::AsmPrinter::emitJumpTableInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#aa925bb5b36e9ac03cfbe86ebcd70dd57">llvm::ARMAsmPrinter::emitJumpTableInsts</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a27e1e6e35a8e68da67d5090a6e9f4c0d">llvm::ARMAsmPrinter::emitJumpTableTBInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a558790807cf5c060c4c82f09decb89d5">EstimateFunctionSizeInBytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp/#a466674860524a217292797476e9ce371">jumpTableHasOtherUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#ab55c74c151c09190ab2204e33e77b299">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerHardenedBRJumpTable</a>, <a href="/web-llvm/docs/api/classes/llvm/branchfolder/#aa0d50fee4d0d41ccf591e29de109786f">llvm::BranchFolder::OptimizeFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-xcoreasmprinter-cpp-/xcoreasmprinter/#a0449defbfc0b9bf98fd830be8dc2587a">anonymous{XCoreAsmPrinter.cpp}::XCoreAsmPrinter::printInlineJT</a>.</p>

</div>
</div>

### isEmpty() {#a519c867ae285099cc58e9bfad73a8895}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineJumpTableInfo::isEmpty ()</td>
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

<p>isEmpty - Return true if there are no jump tables.</p>

<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinejumptableinfo-h">MachineJumpTableInfo.h</a>.</p>

</div>
</div>

### print() {#a2f4b116ba160a0fb57241dee011905e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineJumpTableInfo::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>print - Used by the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> printer to print information about jump tables.</p>


<p>Implemented in <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunction-cpp">MachineFunction.cpp</a></p>


<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinejumptableinfo-h">MachineJumpTableInfo.h</a>, definition at line 1417 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunction-cpp">MachineFunction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4610639927aff734aeacb607c43f01f2">llvm::printJumpTableEntryReference</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>.</p>


<p>Referenced by <a href="#a723eff4a497357d7c8602abd695daa11">dump</a>.</p>

</div>
</div>

### RemoveJumpTable() {#a4884f00bcde9528a64e1c18adc789641}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineJumpTableInfo::RemoveJumpTable (unsigned Idx)</td>
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

<p>RemoveJumpTable - Mark the specific index as being dead.</p>


<p>This will prevent it from being emitted.</p>


<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinejumptableinfo-h">MachineJumpTableInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/branchfolder/#aa0d50fee4d0d41ccf591e29de109786f">llvm::BranchFolder::OptimizeFunction</a>.</p>

</div>
</div>

### RemoveMBBFromJumpTables() {#a0d850b9f4484d7ec9a8ab1880922dcb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineJumpTableInfo::RemoveMBBFromJumpTables (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>RemoveMBBFromJumpTables - If MBB is present in any jump tables, remove it.</p>


<p>If MBB is present in any jump tables, remove it.</p>


<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinejumptableinfo-h">MachineJumpTableInfo.h</a>, definition at line 1391 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunction-cpp">MachineFunction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### ReplaceMBBInJumpTable() {#a729a069c6d2880c2c75148c61998c129}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineJumpTableInfo::ReplaceMBBInJumpTable (unsigned Idx, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Old, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * New)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ReplaceMBBInJumpTable - If Old is a target of the jump tables, update the jump table to branch to New instead.</p>


<p>If Old is a target of the jump tables, update the jump table to branch to New instead.</p>


<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinejumptableinfo-h">MachineJumpTableInfo.h</a>, definition at line 1403 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunction-cpp">MachineFunction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/structs/llvm/machinejumptableentry/#a9c14af1916ca19e3e7fbec5fb2e11c79">llvm::MachineJumpTableEntry::MBBs</a>.</p>


<p>Referenced by <a href="#a1a20b9072a0cd65db50bed95c12e915b">ReplaceMBBInJumpTables</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa80aaa82844ab5560ece045eee7b34ac">llvm::MachineBasicBlock::SplitCriticalEdge</a>.</p>

</div>
</div>

### ReplaceMBBInJumpTables() {#a1a20b9072a0cd65db50bed95c12e915b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineJumpTableInfo::ReplaceMBBInJumpTables (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Old, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * New)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ReplaceMBBInJumpTables - If Old is the target of any jump tables, update the jump tables to branch to New instead.</p>


<p>If Old is the target of any jump tables, update the jump tables to branch to New instead.</p>


<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinejumptableinfo-h">MachineJumpTableInfo.h</a>, definition at line 1381 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunction-cpp">MachineFunction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a729a069c6d2880c2c75148c61998c129">ReplaceMBBInJumpTable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/gcemptybasicblocks/#a77700a9eb5ecac3a68b09ea0ec2b18a7">GCEmptyBasicBlocks::runOnMachineFunction</a>.</p>

</div>
</div>

### updateJumpTableEntryHotness() {#a8399f4d8dfa10432948d8da0ef0e6674}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineJumpTableInfo::updateJumpTableEntryHotness (size_t JTI, <a href="/web-llvm/docs/api/namespaces/llvm/#a59c007354dfad2f618a37e6efaf7cd9b">MachineFunctionDataHotness</a> Hotness)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinejumptableinfo-h">MachineJumpTableInfo.h</a>, definition at line 1368 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunction-cpp">MachineFunction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### EntryKind {#a41fed3e29345a23866eac293ab161a8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JTEntryKind llvm::MachineJumpTableInfo::EntryKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinejumptableinfo-h">MachineJumpTableInfo.h</a>.</p>

</div>
</div>

### JumpTables {#a1b2a87a24e0ecdb058314bd056475b39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MachineJumpTableEntry&gt; llvm::MachineJumpTableInfo::JumpTables</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinejumptableinfo-h">MachineJumpTableInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinejumptableinfo-h">MachineJumpTableInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunction-cpp">MachineFunction.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
