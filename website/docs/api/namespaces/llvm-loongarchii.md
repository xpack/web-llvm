---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/loongarchii
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `LoongArchII` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::LoongArchII { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a03a83eb6d12005ac7d43d370f4eb5078">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a1b3c5f4543d57e05692d5af0fbe96738">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4d10aeb6baa9b7d22a3e7a108243e7a">getDirectFlags</a> (const MachineOperand &amp;MO)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec7148c4c79a82435bb10820b7b77a63">encodeFlags</a> (unsigned Flags, bool Relax)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f9fa0e4abfc14d359493021fdef57ca">hasRelaxFlag</a> (const MachineOperand &amp;MO)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4875afc76f72cb9aea2d71bca9062f30">isSubjectToAMORdConstraint</a> (uint64_t TSFlags)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a030c30e0c488cbb774391a37978bc024">isAMCAS</a> (uint64_t TSFlags)</td>
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


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a03a83eb6d12005ac7d43d370f4eb5078}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
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
<td class="doxyEnumItemName">MO_None<a id="a03a83eb6d12005ac7d43d370f4eb5078a7e0b3356a9a3617e6341ea02d6275cb3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_CALL<a id="a03a83eb6d12005ac7d43d370f4eb5078a47cd4b1e13d896a3c839c26ce7c9bace"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_CALL_PLT<a id="a03a83eb6d12005ac7d43d370f4eb5078adc1fe3e72c9d5fd9003f77dfbf61505a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_PCREL_HI<a id="a03a83eb6d12005ac7d43d370f4eb5078a5e18166bf3ee69c16c30ada264da3067"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_PCREL_LO<a id="a03a83eb6d12005ac7d43d370f4eb5078a0048a64a7cbea49becaf00a3877006ed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_PCREL64_LO<a id="a03a83eb6d12005ac7d43d370f4eb5078ae1dcf847f8f53350ba32361bfda5bb5c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_PCREL64_HI<a id="a03a83eb6d12005ac7d43d370f4eb5078ac204c91c6c9f520505f55f5ccf012136"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOT_PC_HI<a id="a03a83eb6d12005ac7d43d370f4eb5078a4cf49e1eebba4fe318b1e60b142e7a1d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOT_PC_LO<a id="a03a83eb6d12005ac7d43d370f4eb5078a14482ab8d5abc3ee10f93dd895bd65a5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOT_PC64_LO<a id="a03a83eb6d12005ac7d43d370f4eb5078a53c989ca902e693043ae60d02625c853"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOT_PC64_HI<a id="a03a83eb6d12005ac7d43d370f4eb5078ab02370623a4c55790186678faff4fffa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_LE_HI<a id="a03a83eb6d12005ac7d43d370f4eb5078abe9ec4f9a1d5546b5b27426640726240"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_LE_LO<a id="a03a83eb6d12005ac7d43d370f4eb5078a570b6df712e56db765351bc63a4774ec"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_LE64_LO<a id="a03a83eb6d12005ac7d43d370f4eb5078a31822c312e2327e2cf3d688abb94671d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_LE64_HI<a id="a03a83eb6d12005ac7d43d370f4eb5078ad93e0f18f610cdb34229ab6ecca73ec7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_IE_PC_HI<a id="a03a83eb6d12005ac7d43d370f4eb5078a6ef876630029cffa0fc2581b6f2a6cbd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_IE_PC_LO<a id="a03a83eb6d12005ac7d43d370f4eb5078a4cdf03d43999841e402cd1058c9ba6d8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_IE_PC64_LO<a id="a03a83eb6d12005ac7d43d370f4eb5078ae31981e988e08f34a895090659048017"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_IE_PC64_HI<a id="a03a83eb6d12005ac7d43d370f4eb5078a611c28719399932181f6d2f07b0e241b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_LD_PC_HI<a id="a03a83eb6d12005ac7d43d370f4eb5078a1d89198c1efc61c0a7bf6e50c994425c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GD_PC_HI<a id="a03a83eb6d12005ac7d43d370f4eb5078a4c0eba82d8842c407247ba4c0345122d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_CALL36<a id="a03a83eb6d12005ac7d43d370f4eb5078a25d2eba87ca5c835c21760f9720504d9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_DESC_PC_HI<a id="a03a83eb6d12005ac7d43d370f4eb5078a375020882b17576e0993863147dc34c7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_DESC_PC_LO<a id="a03a83eb6d12005ac7d43d370f4eb5078ad04fda120f5e018a803ae4369fe00043"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_DESC64_PC_HI<a id="a03a83eb6d12005ac7d43d370f4eb5078a77a0574b3dc8b83f538804f8e3df84d7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_DESC64_PC_LO<a id="a03a83eb6d12005ac7d43d370f4eb5078ab395ff3151115b55c5e9bdccdab63a79"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_DESC_LD<a id="a03a83eb6d12005ac7d43d370f4eb5078af6ed8cbbc6b55692f6bd04e284ac92a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_DESC_CALL<a id="a03a83eb6d12005ac7d43d370f4eb5078a2ed9da17c1681309f48f9bc32dbfa333"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_LE_HI_R<a id="a03a83eb6d12005ac7d43d370f4eb5078aa9b58d2f9b15720c61836b790e67df8a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_LE_ADD_R<a id="a03a83eb6d12005ac7d43d370f4eb5078aa5960be7a10593432cac2a48ba0130b6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_LE_LO_R<a id="a03a83eb6d12005ac7d43d370f4eb5078af7ae9605028f7b775ea830206d1fee8d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_DIRECT_FLAG_MASK<a id="a03a83eb6d12005ac7d43d370f4eb5078a603e42cc9130112fdcc131ac29a8e56f"></a></td>
<td class="doxyEnumItemDescription"> (= 0x3f)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_RELAX<a id="a03a83eb6d12005ac7d43d370f4eb5078a54a53e14720548a9a542da056797792d"></a></td>
<td class="doxyEnumItemDescription"> (= 0x40)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchbaseinfo-h">LoongArchBaseInfo.h</a>.</p>

</div>
</div>

### anonymous enum  {#a1b3c5f4543d57e05692d5af0fbe96738}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
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
<td class="doxyEnumItemName">IsSubjectToAMORdConstraintShift<a id="a1b3c5f4543d57e05692d5af0fbe96738a286ed93291ef31d4d11c04e96126b23d"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IsSubjectToAMORdConstraintMask<a id="a1b3c5f4543d57e05692d5af0fbe96738ab792d4fa2c40e2ed4c2119ca402b74fc"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; IsSubjectToAMORdConstraintShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IsAMCASShift<a id="a1b3c5f4543d57e05692d5af0fbe96738af1cb94b353279a3a957b0a63e7dcbf3b"></a></td>
<td class="doxyEnumItemDescription"> (= IsSubjectToAMORdConstraintShift + 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IsAMCASMask<a id="a1b3c5f4543d57e05692d5af0fbe96738a46be2cc5190008faeac52cd5dd937b43"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; IsAMCASShift)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchbaseinfo-h">LoongArchBaseInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### encodeFlags() {#aec7148c4c79a82435bb10820b7b77a63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LoongArchII::encodeFlags (unsigned Flags, bool Relax)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchbaseinfo-h">LoongArchBaseInfo.h</a>.</p>


<p>Reference <a href="#a03a83eb6d12005ac7d43d370f4eb5078a54a53e14720548a9a542da056797792d">MO_RELAX</a>.</p>

</div>
</div>

### getDirectFlags() {#ab4d10aeb6baa9b7d22a3e7a108243e7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LoongArchII::getDirectFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchbaseinfo-h">LoongArchBaseInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab06dda088d3c7686f7dfcdb2b96323f5">llvm::MachineOperand::getTargetFlags</a> and <a href="#a03a83eb6d12005ac7d43d370f4eb5078a603e42cc9130112fdcc131ac29a8e56f">MO_DIRECT_FLAG_MASK</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#ae0bcd8452ba359569789760d5dde2434">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::foldIntoMemoryOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchmergebaseoffset-cpp/#a735102341f94b533b3c6b75f22989db4">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#aa7bdfd429f78e266cde062d9adf4a155">llvm::LoongArchInstrInfo::isSchedulingBoundary</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchmcinstlower-cpp/#a931cec5e0b9faa60b9b6943de522e49b">lowerSymbolOperand</a>.</p>

</div>
</div>

### hasRelaxFlag() {#a2f9fa0e4abfc14d359493021fdef57ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoongArchII::hasRelaxFlag (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchbaseinfo-h">LoongArchBaseInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab06dda088d3c7686f7dfcdb2b96323f5">llvm::MachineOperand::getTargetFlags</a> and <a href="#a03a83eb6d12005ac7d43d370f4eb5078a54a53e14720548a9a542da056797792d">MO_RELAX</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchmcinstlower-cpp/#a931cec5e0b9faa60b9b6943de522e49b">lowerSymbolOperand</a>.</p>

</div>
</div>

### isAMCAS() {#a030c30e0c488cbb774391a37978bc024}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoongArchII::isAMCAS (uint64_t TSFlags)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if this instruction belongs to the AMCAS family.</p></dd>
</dl>


<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchbaseinfo-h">LoongArchBaseInfo.h</a>.</p>


<p>Reference <a href="#a1b3c5f4543d57e05692d5af0fbe96738a46be2cc5190008faeac52cd5dd937b43">IsAMCASMask</a>.</p>

</div>
</div>

### isSubjectToAMORdConstraint() {#a4875afc76f72cb9aea2d71bca9062f30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoongArchII::isSubjectToAMORdConstraint (uint64_t TSFlags)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if this instruction's rd is normally required to differ from rj and rk, in the way 3-register atomic memory operations behave.</p></dd>
</dl>


<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchbaseinfo-h">LoongArchBaseInfo.h</a>.</p>


<p>Reference <a href="#a1b3c5f4543d57e05692d5af0fbe96738ab792d4fa2c40e2ed4c2119ca402b74fc">IsSubjectToAMORdConstraintMask</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchbaseinfo-h">LoongArchBaseInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
