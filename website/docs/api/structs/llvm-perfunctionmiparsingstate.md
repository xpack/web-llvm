---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/perfunctionmiparsingstate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `PerFunctionMIParsingState` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::PerFunctionMIParsingState { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/miparser-h">llvm/CodeGen/MIRParser/MIParser.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3daa16706c91dbfe0794c2ff21f20ef">PerFunctionMIParsingState</a> (MachineFunction &amp;MF, SourceMgr &amp;SM, const SlotMapping &amp;IRSlots, PerTargetMIParsingState &amp;Target)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/vreginfo">VRegInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cf857c0d07b6c5d63ebdb58adfb174a">getVRegInfo</a> (Register Num)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/vreginfo">VRegInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1c454669c5be28c6ce12b84bc5faa28">getVRegInfoNamed</a> (StringRef RegName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43b844ddf83274d3654e60f1001a58c1">getIRValue</a> (unsigned Slot)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc459f5bfde045e674bc383f253427d1">Allocator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7f8c6f160583712d2adaafb4cca24fe">MF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04c6eaa02b55eaf51e4b182bd0c640cb">SM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/slotmapping">SlotMapping</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29a0307a8247736e8fe65240c5c8b4d0">IRSlots</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/pertargetmiparsingstate">PerTargetMIParsingState</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfc43bb1d08a6af8915f5eb4b6211a24">Target</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; unsigned, <a href="/web-llvm/docs/api/namespaces/llvm/#a0b32d680d9bfed0636f7297d89583e27">TrackingMDNodeRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71a28de65ad4244111f7ad9e4965bf98">MachineMetadataNodes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; unsigned, std::pair&lt; TempMDTuple, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae7833cc08e3b69a50ffa05d10e06348">MachineForwardRefMDNodes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62f25a77000d3c925fceea154f442559">MBBSlots</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/structs/llvm/vreginfo">VRegInfo</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af04a49c4719319a475237aa431d2c1ba">VRegInfos</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/vreginfo">VRegInfo</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c00589d8b2d82496406b0ceeb825d2a">VRegInfosNamed</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19f71c010b6aa6cb68154df3628b105c">FixedStackObjectSlots</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a952ba2c542e998e95f8d2dc847250845">StackObjectSlots</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e33668004b320a3ccfc96d48a235302">ConstantPoolSlots</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a000b59a1a49e0cf2befc72e409bd3ef3">JumpTableSlots</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a912f2d783a3b438e5f50fbbf83dac84b">Slots2Values</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps from slot numbers to function's unnamed values. <a href="#a912f2d783a3b438e5f50fbbf83dac84b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/miparser-h">MIParser.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PerFunctionMIParsingState() {#aa3daa16706c91dbfe0794c2ff21f20ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PerFunctionMIParsingState::PerFunctionMIParsingState (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/slotmapping">SlotMapping</a> &amp; IRSlots, <a href="/web-llvm/docs/api/structs/llvm/pertargetmiparsingstate">PerTargetMIParsingState</a> &amp; Target)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/miparser-h">MIParser.h</a>, definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="#a29a0307a8247736e8fe65240c5c8b4d0">IRSlots</a>, <a href="#ae7f8c6f160583712d2adaafb4cca24fe">MF</a>, <a href="#a04c6eaa02b55eaf51e4b182bd0c640cb">SM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="#abfc43bb1d08a6af8915f5eb4b6211a24">Target</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getIRValue() {#a43b844ddf83274d3654e60f1001a58c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value * PerFunctionMIParsingState::getIRValue (unsigned Slot)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/miparser-h">MIParser.h</a>, definition at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a2845d82e260f8f8c9e8d5bc349214fec">initSlots2Values</a>, <a href="#ae7f8c6f160583712d2adaafb4cca24fe">MF</a> and <a href="#a912f2d783a3b438e5f50fbbf83dac84b">Slots2Values</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a35017776f5e9dd9dbc7f71d56a77135a">parseIRValue</a>.</p>

</div>
</div>

### getVRegInfo() {#a0cf857c0d07b6c5d63ebdb58adfb174a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VRegInfo &amp; PerFunctionMIParsingState::getVRegInfo (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Num)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/miparser-h">MIParser.h</a>, definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="#afc459f5bfde045e674bc383f253427d1">Allocator</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ae7f8c6f160583712d2adaafb4cca24fe">MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/structs/llvm/vreginfo/#ab6ce1c2de1091462eb4e63b760b03bed">llvm::VRegInfo::VReg</a> and <a href="#af04a49c4719319a475237aa431d2c1ba">VRegInfos</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a0cd181d3140028362e24cdc5d675ac16">llvm::MIRParserImpl::parseRegisterInfo</a>.</p>

</div>
</div>

### getVRegInfoNamed() {#af1c454669c5be28c6ce12b84bc5faa28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VRegInfo &amp; PerFunctionMIParsingState::getVRegInfoNamed (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RegName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/miparser-h">MIParser.h</a>, definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="#afc459f5bfde045e674bc383f253427d1">Allocator</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ae7f8c6f160583712d2adaafb4cca24fe">MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lvlgen-cpp/#a0a198e38a5def54ba58bebc655eda8e7">RegName</a>, <a href="/web-llvm/docs/api/structs/llvm/vreginfo/#ab6ce1c2de1091462eb4e63b760b03bed">llvm::VRegInfo::VReg</a> and <a href="#a6c00589d8b2d82496406b0ceeb825d2a">VRegInfosNamed</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Allocator {#afc459f5bfde045e674bc383f253427d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator llvm::PerFunctionMIParsingState::Allocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/miparser-h">MIParser.h</a>.</p>


<p>Referenced by <a href="#a0cf857c0d07b6c5d63ebdb58adfb174a">getVRegInfo</a> and <a href="#af1c454669c5be28c6ce12b84bc5faa28">getVRegInfoNamed</a>.</p>

</div>
</div>

### ConstantPoolSlots {#a5e33668004b320a3ccfc96d48a235302}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, unsigned&gt; llvm::PerFunctionMIParsingState::ConstantPoolSlots</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/miparser-h">MIParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a69398364db52b18db9d922fec6d8eb87">llvm::MIRParserImpl::initializeConstantPool</a>.</p>

</div>
</div>

### FixedStackObjectSlots {#a19f71c010b6aa6cb68154df3628b105c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, int&gt; llvm::PerFunctionMIParsingState::FixedStackObjectSlots</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/miparser-h">MIParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>.</p>

</div>
</div>

### IRSlots {#a29a0307a8247736e8fe65240c5c8b4d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SlotMapping&amp; llvm::PerFunctionMIParsingState::IRSlots</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/miparser-h">MIParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#ad9f5610f1837c8d9df4a404f2b880b63">parseGlobalValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a21ef92ee94136c11407030eee4319eab">parseIRConstant</a> and <a href="#aa3daa16706c91dbfe0794c2ff21f20ef">PerFunctionMIParsingState</a>.</p>

</div>
</div>

### JumpTableSlots {#a000b59a1a49e0cf2befc72e409bd3ef3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, unsigned&gt; llvm::PerFunctionMIParsingState::JumpTableSlots</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/miparser-h">MIParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a4e8962fa2139c288809acff971691109">llvm::MIRParserImpl::initializeJumpTableInfo</a>.</p>

</div>
</div>

### MachineForwardRefMDNodes {#aae7833cc08e3b69a50ffa05d10e06348}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;unsigned, std::pair&lt;TempMDTuple, SMLoc&gt; &gt; llvm::PerFunctionMIParsingState::MachineForwardRefMDNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/miparser-h">MIParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#add4fede1a05c8d8148b6ef72f2da3494">llvm::MIRParserImpl::parseMachineMetadataNodes</a>.</p>

</div>
</div>

### MachineMetadataNodes {#a71a28de65ad4244111f7ad9e4965bf98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;unsigned, TrackingMDNodeRef&gt; llvm::PerFunctionMIParsingState::MachineMetadataNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/miparser-h">MIParser.h</a>.</p>

</div>
</div>

### MBBSlots {#a62f25a77000d3c925fceea154f442559}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, MachineBasicBlock *&gt; llvm::PerFunctionMIParsingState::MBBSlots</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/miparser-h">MIParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a46e5b5618c54f98506becf5e4878b626">llvm::parseMachineBasicBlockDefinitions</a>.</p>

</div>
</div>

### MF {#ae7f8c6f160583712d2adaafb4cca24fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction&amp; llvm::PerFunctionMIParsingState::MF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/miparser-h">MIParser.h</a>.</p>


<p>Referenced by <a href="#a43b844ddf83274d3654e60f1001a58c1">getIRValue</a>, <a href="#a0cf857c0d07b6c5d63ebdb58adfb174a">getVRegInfo</a>, <a href="#af1c454669c5be28c6ce12b84bc5faa28">getVRegInfoNamed</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#aea53e647298055af644a50c3a29e1411">llvm::MIRParserImpl::initializeCallSiteInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a69398364db52b18db9d922fec6d8eb87">llvm::MIRParserImpl::initializeConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a4e8962fa2139c288809acff971691109">llvm::MIRParserImpl::initializeJumpTableInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#ad9f5610f1837c8d9df4a404f2b880b63">parseGlobalValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a21ef92ee94136c11407030eee4319eab">parseIRConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a35017776f5e9dd9dbc7f71d56a77135a">parseIRValue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#a9d7a25c9afc1ea6d9d24a3c4e63431a0">llvm::AArch64TargetMachine::parseMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#a1589249b2983702336aeaa27b46a7bdf">llvm::ARMBaseTargetMachine::parseMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetmachine/#ac44c40ffe6213c3edb995e9ccc5fe9cd">llvm::RISCVTargetMachine::parseMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetmachine/#a1f105b1ab02dcb52f17181b399c004f2">llvm::WebAssemblyTargetMachine::parseMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetmachine/#ab89228eb897b597f42d44eebf26081dc">llvm::X86TargetMachine::parseMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a0cd181d3140028362e24cdc5d675ac16">llvm::MIRParserImpl::parseRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a350e13622868acbfca1779538a0f3b9b">llvm::MIRParserImpl::parseStackObjectsDebugInfo</a>, <a href="#aa3daa16706c91dbfe0794c2ff21f20ef">PerFunctionMIParsingState</a> and <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a0909a505055aae0cb9dee8e5730b3724">llvm::MIRParserImpl::setupRegisterInfo</a>.</p>

</div>
</div>

### Slots2Values {#a912f2d783a3b438e5f50fbbf83dac84b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, const Value *&gt; llvm::PerFunctionMIParsingState::Slots2Values</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps from slot numbers to function's unnamed values.</p>

<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/miparser-h">MIParser.h</a>.</p>


<p>Referenced by <a href="#a43b844ddf83274d3654e60f1001a58c1">getIRValue</a>.</p>

</div>
</div>

### SM {#a04c6eaa02b55eaf51e4b182bd0c640cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourceMgr* llvm::PerFunctionMIParsingState::SM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/miparser-h">MIParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a3518bb886d39c70ab9163440243d2d5b">llvm::MIRParserImpl::initializeMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a> and <a href="#aa3daa16706c91dbfe0794c2ff21f20ef">PerFunctionMIParsingState</a>.</p>

</div>
</div>

### StackObjectSlots {#a952ba2c542e998e95f8d2dc847250845}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, int&gt; llvm::PerFunctionMIParsingState::StackObjectSlots</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/miparser-h">MIParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>.</p>

</div>
</div>

### Target {#abfc43bb1d08a6af8915f5eb4b6211a24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PerTargetMIParsingState&amp; llvm::PerFunctionMIParsingState::Target</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/miparser-h">MIParser.h</a>.</p>


<p>Referenced by <a href="#aa3daa16706c91dbfe0794c2ff21f20ef">PerFunctionMIParsingState</a>.</p>

</div>
</div>

### VRegInfos {#af04a49c4719319a475237aa431d2c1ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Register, VRegInfo *&gt; llvm::PerFunctionMIParsingState::VRegInfos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/miparser-h">MIParser.h</a>.</p>


<p>Referenced by <a href="#a0cf857c0d07b6c5d63ebdb58adfb174a">getVRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a0909a505055aae0cb9dee8e5730b3724">llvm::MIRParserImpl::setupRegisterInfo</a>.</p>

</div>
</div>

### VRegInfosNamed {#a6c00589d8b2d82496406b0ceeb825d2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;VRegInfo *&gt; llvm::PerFunctionMIParsingState::VRegInfosNamed</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/miparser-h">MIParser.h</a>.</p>


<p>Referenced by <a href="#af1c454669c5be28c6ce12b84bc5faa28">getVRegInfoNamed</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a0909a505055aae0cb9dee8e5730b3724">llvm::MIRParserImpl::setupRegisterInfo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/miparser-h">MIParser.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
