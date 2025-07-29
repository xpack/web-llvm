---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/rdf/physicalregisterinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `PhysicalRegisterInfo` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::rdf::PhysicalRegisterInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">llvm/CodeGen/RDFRegisters.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11dfc334374b4579c63c4269e3e1d34b">PhysicalRegisterInfo</a> (const TargetRegisterInfo &amp;tri, const MachineFunction &amp;mf)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ac7072dcf10008631e0ac026bc5f8beae">RegisterId</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a112859e582ad6783c922bac9f63d377c">getRegMaskId</a> (const uint32_t *RM) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ed460e206904e6731fb5a812a74d874">getRegMaskBits</a> (RegisterId R) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dad4dca6c149dcc5a2138f9c3ca50d6">alias</a> (RegisterRef RA, RegisterRef RB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::set&lt; <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ac7072dcf10008631e0ac026bc5f8beae">RegisterId</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85c1ec2b6a80a274d6f070a19045d392">getAliasSet</a> (RegisterId Reg) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff74ab74f8d91f36b55b0eba3ba18edc">getRefForUnit</a> (uint32_t U) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b41fbff427a806361170cffabc62e41">getMaskUnits</a> (RegisterId MaskId) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::set&lt; <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ac7072dcf10008631e0ac026bc5f8beae">RegisterId</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbe9878ae041d77351364bc60fe4a3fe">getUnits</a> (RegisterRef RR) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8916ac9663dc46ece86fc8227bc96ac9">getUnitAliases</a> (uint32_t U) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab895a9e549543404ea829bb14f6162c1">mapTo</a> (RegisterRef RR, unsigned R) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37e1235677602b5f723384757dc64d68">getTRI</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bc3d5451e079cf6bcbb2df76f71f293">equal_to</a> (RegisterRef A, RegisterRef B) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addd4894584bf563edc6e3ef084b771ef">less</a> (RegisterRef A, RegisterRef B) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35ed7153814f84233fc75351452cf30c">print</a> (raw_ostream &amp;OS, RegisterRef A) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9260d3ebfcccff33d2e0b9ed4e0ddddf">print</a> (raw_ostream &amp;OS, const RegisterAggr &amp;A) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29428464e975e069e74922e67b2ec222">TRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/indexedset">IndexedSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7c392b672c5fdf48c8b569ea935f16e">RegMasks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/reginfo">RegInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54620d8b54ce6f0b73af814c556b962f">RegInfos</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; UnitInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76847da64d3bcfe76a4968ce32c05ba3">UnitInfos</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; MaskInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01bc61da07a3ab40aadb0828e00af855">MaskInfos</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; AliasInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45280801e897ee066d12e958db77a6cc">AliasInfos</a></td>
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


<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PhysicalRegisterInfo() {#a11dfc334374b4579c63c4269e3e1d34b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::rdf::PhysicalRegisterInfo::PhysicalRegisterInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; tri, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; mf)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfregisters-cpp">RDFRegisters.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### alias() {#a9dad4dca6c149dcc5a2138f9c3ca50d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::rdf::PhysicalRegisterInfo::alias (<a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a> RA, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a> RB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>, definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfregisters-cpp">RDFRegisters.cpp</a>.</p>


<p>References <a href="#a9dad4dca6c149dcc5a2138f9c3ca50d6">alias</a>, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ae3b5e436afeb0d1e4781f4c47beee60d">llvm::rdf::disjoint</a>, <a href="#afbe9878ae041d77351364bc60fe4a3fe">getUnits</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp/#a3e47bdb3e296b00df96eff7896fa57bf">RA</a>.</p>


<p>Referenced by <a href="#a9dad4dca6c149dcc5a2138f9c3ca50d6">alias</a>.</p>

</div>
</div>

### equal\_to() {#a8bc3d5451e079cf6bcbb2df76f71f293}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::rdf::PhysicalRegisterInfo::equal_to (<a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a> A, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a> B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>, definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfregisters-cpp">RDFRegisters.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a8bc3d5451e079cf6bcbb2df76f71f293">equal_to</a>, <a href="#a37e1235677602b5f723384757dc64d68">getTRI</a> and <a href="/web-llvm/docs/api/classes/llvm/mcregunitmaskiterator/#a73b0d1192402b944dbc7aac0db77258d">llvm::MCRegUnitMaskIterator::isValid</a>.</p>


<p>Referenced by <a href="#a8bc3d5451e079cf6bcbb2df76f71f293">equal_to</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/copypropagation/#ab5cc393f3a921f0a6fe0505561a80e23">llvm::rdf::CopyPropagation::run</a>.</p>

</div>
</div>

### getAliasSet() {#a85c1ec2b6a80a274d6f070a19045d392}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::set&lt; RegisterId &gt; llvm::rdf::PhysicalRegisterInfo::getAliasSet (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ac7072dcf10008631e0ac026bc5f8beae">RegisterId</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>, definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfregisters-cpp">RDFRegisters.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a85c1ec2b6a80a274d6f070a19045d392">getAliasSet</a>, <a href="#a7ed460e206904e6731fb5a812a74d874">getRegMaskBits</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#a7a6e00a1aed89e42fd185379d3309666">llvm::rdf::RegisterRef::isMaskId</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#a987ae88dea5396b51031fe9a52d8388a">llvm::rdf::RegisterRef::isRegId</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#aaaa495ab731d5c7de060f932c8bbc869">llvm::rdf::RegisterRef::isUnitId</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregaliasiterator/#ac336c049c12ead7be5b86e6d046f8ab0">llvm::MCRegAliasIterator::isValid</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#a85c1ec2b6a80a274d6f070a19045d392">getAliasSet</a>.</p>

</div>
</div>

### getMaskUnits() {#a0b41fbff427a806361170cffabc62e41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BitVector &amp; llvm::rdf::PhysicalRegisterInfo::getMaskUnits (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ac7072dcf10008631e0ac026bc5f8beae">RegisterId</a> MaskId)</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/register/#a47caf9a25186eed2215d13171af1f3ca">llvm::Register::stackSlot2Index</a>.</p>

</div>
</div>

### getRefForUnit() {#aff74ab74f8d91f36b55b0eba3ba18edc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterRef llvm::rdf::PhysicalRegisterInfo::getRefForUnit (uint32_t U)</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### getRegMaskBits() {#a7ed460e206904e6731fb5a812a74d874}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t * llvm::rdf::PhysicalRegisterInfo::getRegMaskBits (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ac7072dcf10008631e0ac026bc5f8beae">RegisterId</a> R)</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/register/#a47caf9a25186eed2215d13171af1f3ca">llvm::Register::stackSlot2Index</a>.</p>


<p>Referenced by <a href="#a85c1ec2b6a80a274d6f070a19045d392">getAliasSet</a> and <a href="#afbe9878ae041d77351364bc60fe4a3fe">getUnits</a>.</p>

</div>
</div>

### getRegMaskId() {#a112859e582ad6783c922bac9f63d377c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterId llvm::rdf::PhysicalRegisterInfo::getRegMaskId (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t * RM)</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/register/#a92cd11abfd541caadc1fc825b78f9903">llvm::Register::index2StackSlot</a>.</p>

</div>
</div>

### getTRI() {#a37e1235677602b5f723384757dc64d68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo &amp; llvm::rdf::PhysicalRegisterInfo::getTRI ()</td>
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



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>Referenced by <a href="#a8bc3d5451e079cf6bcbb2df76f71f293">equal_to</a> and <a href="#addd4894584bf563edc6e3ef084b771ef">less</a>.</p>

</div>
</div>

### getUnitAliases() {#a8916ac9663dc46ece86fc8227bc96ac9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BitVector &amp; llvm::rdf::PhysicalRegisterInfo::getUnitAliases (uint32_t U)</td>
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



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>

</div>
</div>

### getUnits() {#afbe9878ae041d77351364bc60fe4a3fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::set&lt; RegisterId &gt; llvm::rdf::PhysicalRegisterInfo::getUnits (<a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a> RR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>, definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfregisters-cpp">RDFRegisters.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a7ed460e206904e6731fb5a812a74d874">getRegMaskBits</a>, <a href="#afbe9878ae041d77351364bc60fe4a3fe">getUnits</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#a05a3bdf2a3d5c33f370bc778fabaee9c">llvm::rdf::RegisterRef::idx</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#a75a80381a8983087ea1f89b9fadabede">llvm::rdf::RegisterRef::isMask</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#a6e855d6b2f844f3bdce575f3d0330bb5">llvm::rdf::RegisterRef::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregunitmaskiterator/#a73b0d1192402b944dbc7aac0db77258d">llvm::MCRegUnitMaskIterator::isValid</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#a5ad5cb9affeee19ca5894e5d950ea869">llvm::rdf::RegisterRef::Mask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3d063b3cfffeac6b26118598d1f8413">llvm::maskLeadingOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79dff91526e31b1a05f59eed6c189eb4">llvm::maskTrailingOnes</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a60907035da962ba7bea74ffb9af977bd">llvm::LaneBitmask::none</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#aff344ef4b411a5f449ef8839d98f1750">llvm::rdf::RegisterRef::Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a9dad4dca6c149dcc5a2138f9c3ca50d6">alias</a> and <a href="#afbe9878ae041d77351364bc60fe4a3fe">getUnits</a>.</p>

</div>
</div>

### less() {#addd4894584bf563edc6e3ef084b771ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::rdf::PhysicalRegisterInfo::less (<a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a> A, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a> B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>, definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfregisters-cpp">RDFRegisters.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a37e1235677602b5f723384757dc64d68">getTRI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregunitmaskiterator/#a73b0d1192402b944dbc7aac0db77258d">llvm::MCRegUnitMaskIterator::isValid</a> and <a href="#addd4894584bf563edc6e3ef084b771ef">less</a>.</p>


<p>Referenced by <a href="#addd4894584bf563edc6e3ef084b771ef">less</a>.</p>

</div>
</div>

### mapTo() {#ab895a9e549543404ea829bb14f6162c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterRef llvm::rdf::PhysicalRegisterInfo::mapTo (<a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a> RR, unsigned R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>, definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfregisters-cpp">RDFRegisters.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a3714a639930eab71d7202da05ad82990">llvm::LaneBitmask::getAll</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a0363c6cc08fe464f66f9e53239bb35e3">llvm::TargetRegisterClass::LaneMask</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#ab895a9e549543404ea829bb14f6162c1">mapTo</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#a5ad5cb9affeee19ca5894e5d950ea869">llvm::rdf::RegisterRef::Mask</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#aff344ef4b411a5f449ef8839d98f1750">llvm::rdf::RegisterRef::Reg</a>.</p>


<p>Referenced by <a href="#ab895a9e549543404ea829bb14f6162c1">mapTo</a>.</p>

</div>
</div>

### print() {#a35ed7153814f84233fc75351452cf30c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::PhysicalRegisterInfo::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a> A)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>, definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfregisters-cpp">RDFRegisters.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="#a35ed7153814f84233fc75351452cf30c">print</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a34302b557354b8a09796c30b9f7408ab">llvm::printRegUnit</a> and <a href="/web-llvm/docs/api/classes/llvm/register/#a47caf9a25186eed2215d13171af1f3ca">llvm::Register::stackSlot2Index</a>.</p>


<p>Referenced by <a href="#a9260d3ebfcccff33d2e0b9ed4e0ddddf">print</a> and <a href="#a35ed7153814f84233fc75351452cf30c">print</a>.</p>

</div>
</div>

### print() {#a9260d3ebfcccff33d2e0b9ed4e0ddddf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::PhysicalRegisterInfo::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr">RegisterAggr</a> &amp; A)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>, definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfregisters-cpp">RDFRegisters.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a35ed7153814f84233fc75351452cf30c">print</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a34302b557354b8a09796c30b9f7408ab">llvm::printRegUnit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AliasInfos {#a45280801e897ee066d12e958db77a6cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;AliasInfo&gt; llvm::rdf::PhysicalRegisterInfo::AliasInfos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>

</div>
</div>

### MaskInfos {#a01bc61da07a3ab40aadb0828e00af855}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MaskInfo&gt; llvm::rdf::PhysicalRegisterInfo::MaskInfos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>

</div>
</div>

### RegInfos {#a54620d8b54ce6f0b73af814c556b962f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;RegInfo&gt; llvm::rdf::PhysicalRegisterInfo::RegInfos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>

</div>
</div>

### RegMasks {#ac7c392b672c5fdf48c8b569ea935f16e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndexedSet&lt;const uint32_t *&gt; llvm::rdf::PhysicalRegisterInfo::RegMasks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>

</div>
</div>

### TRI {#a29428464e975e069e74922e67b2ec222}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo&amp; llvm::rdf::PhysicalRegisterInfo::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>

</div>
</div>

### UnitInfos {#a76847da64d3bcfe76a4968ce32c05ba3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;UnitInfo&gt; llvm::rdf::PhysicalRegisterInfo::UnitInfos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfregisters-cpp">RDFRegisters.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
