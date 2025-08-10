---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/x86addressmode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `X86AddressMode` Struct

<p><a href="/web-llvm/docs/api/structs/llvm/x86addressmode">X86AddressMode</a> - This struct holds a generalized full x86 address mode. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::X86AddressMode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrbuilder-h">Target/X86/X86InstrBuilder.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a47626c396b3692c11cb940faf7578a4f">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71e2b7928cd0743a0b1834cd441696eb">X86AddressMode</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a593e839307453b63de7b7021e8cc059a">getFullAddress</a> (SmallVectorImpl&lt; MachineOperand &gt; &amp;MO)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum <a href="/web-llvm/docs/api/structs/llvm/x86addressmode">llvm::X86AddressMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad89c0e74be4dc1391cb4225984ce1c92">BaseType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdbb5443e06c46eba409abb252121105">Reg</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a967aafff1ceb0ab66c9de70c5a94eacd">FrameIndex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/structs/llvm/x86addressmode">llvm::X86AddressMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17a6d6e90566fa2abeb797273f9acc36">Base</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad094c5c9174ced82b0e50cc1107f6b6">Scale</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1965b0188d8595d0aaf002d0eb6d009">IndexReg</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a883f2182cecc59883f24a9b886ffeb74">Disp</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69cfaa345b14e467ea8934fe48cc3365">GV</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1894a1e6be0ec8bbc763476332735765">GVOpFlags</a></td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/x86addressmode">X86AddressMode</a> - This struct holds a generalized full x86 address mode.</p>


<p>The base register can be a frame index, which will eventually be replaced with BP or SP and Disp being offsetted accordingly. The displacement may also include the offset of a global value.</p>


<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrbuilder-h">X86InstrBuilder.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a47626c396b3692c11cb940faf7578a4f}

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
<td class="doxyEnumItemName">RegBase<a id="a47626c396b3692c11cb940faf7578a4fa8763369023c9ed44c8a2861b80107e9f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FrameIndexBase<a id="a47626c396b3692c11cb940faf7578a4fab07c42c17fdd1279c09b961c89653ffb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrbuilder-h">X86InstrBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### X86AddressMode() {#a71e2b7928cd0743a0b1834cd441696eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::X86AddressMode::X86AddressMode ()</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrbuilder-h">X86InstrBuilder.h</a>.</p>


<p>References <a href="#a17a6d6e90566fa2abeb797273f9acc36">Base</a>, <a href="#ad89c0e74be4dc1391cb4225984ce1c92">BaseType</a>, <a href="#a883f2182cecc59883f24a9b886ffeb74">Disp</a>, <a href="#a69cfaa345b14e467ea8934fe48cc3365">GV</a>, <a href="#a1894a1e6be0ec8bbc763476332735765">GVOpFlags</a>, <a href="#af1965b0188d8595d0aaf002d0eb6d009">IndexReg</a>, <a href="#a47626c396b3692c11cb940faf7578a4fa8763369023c9ed44c8a2861b80107e9f">RegBase</a> and <a href="#aad094c5c9174ced82b0e50cc1107f6b6">Scale</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getFullAddress() {#a593e839307453b63de7b7021e8cc059a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86AddressMode::getFullAddress (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; &amp; MO)</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrbuilder-h">X86InstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a17a6d6e90566fa2abeb797273f9acc36">Base</a>, <a href="#ad89c0e74be4dc1391cb4225984ce1c92">BaseType</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#afda3f1971b3e44709267be818ffd3035">llvm::MachineOperand::CreateFI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ace112d8a86396bd55e99738cd41005b6">llvm::MachineOperand::CreateGA</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab09679b541a6ba1219b3602569847364">llvm::MachineOperand::CreateImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af2c351dad09a71aa08e1d85c67ae6e53">llvm::MachineOperand::CreateReg</a>, <a href="#a883f2182cecc59883f24a9b886ffeb74">Disp</a>, <a href="#a47626c396b3692c11cb940faf7578a4fab07c42c17fdd1279c09b961c89653ffb">FrameIndexBase</a>, <a href="#a69cfaa345b14e467ea8934fe48cc3365">GV</a>, <a href="#a1894a1e6be0ec8bbc763476332735765">GVOpFlags</a>, <a href="#af1965b0188d8595d0aaf002d0eb6d009">IndexReg</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a47626c396b3692c11cb940faf7578a4fa8763369023c9ed44c8a2861b80107e9f">RegBase</a> and <a href="#aad094c5c9174ced82b0e50cc1107f6b6">Scale</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#aa1616cca9834ae9c228730c62f4f8b43">anonymous{X86FastISel.cpp}::X86FastISel::tryToFoldLoadIntoMI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Base {#a17a6d6e90566fa2abeb797273f9acc36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::X86AddressMode llvm::X86AddressMode::Base</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrbuilder-h">X86InstrBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a41229d95ec1712486d97ae6c27a0ba8a">llvm::addFullAddress</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2475576febdb5d6a1929ef786a57a03">llvm::getAddressFromInstr</a>, <a href="#a593e839307453b63de7b7021e8cc059a">getFullAddress</a>, <a href="#a71e2b7928cd0743a0b1834cd441696eb">X86AddressMode</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp/#af73334c0150d71c2d565ecce0d5e9ff4">X86SelectAddress</a>.</p>

</div>
</div>

### BaseType {#ad89c0e74be4dc1391cb4225984ce1c92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86AddressMode llvm::X86AddressMode::BaseType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrbuilder-h">X86InstrBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a41229d95ec1712486d97ae6c27a0ba8a">llvm::addFullAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2475576febdb5d6a1929ef786a57a03">llvm::getAddressFromInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a05177d88a5bc1830eedc7a240560f7c9">llvm::X86InstrInfo::getFrameIndexOperands</a>, <a href="#a593e839307453b63de7b7021e8cc059a">getFullAddress</a>, <a href="#a71e2b7928cd0743a0b1834cd441696eb">X86AddressMode</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp/#af73334c0150d71c2d565ecce0d5e9ff4">X86SelectAddress</a>.</p>

</div>
</div>

### Disp {#a883f2182cecc59883f24a9b886ffeb74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::X86AddressMode::Disp</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrbuilder-h">X86InstrBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a41229d95ec1712486d97ae6c27a0ba8a">llvm::addFullAddress</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2475576febdb5d6a1929ef786a57a03">llvm::getAddressFromInstr</a>, <a href="#a593e839307453b63de7b7021e8cc059a">getFullAddress</a>, <a href="#a71e2b7928cd0743a0b1834cd441696eb">X86AddressMode</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp/#af73334c0150d71c2d565ecce0d5e9ff4">X86SelectAddress</a>.</p>

</div>
</div>

### FrameIndex {#a967aafff1ceb0ab66c9de70c5a94eacd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::X86AddressMode::FrameIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrbuilder-h">X86InstrBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a41229d95ec1712486d97ae6c27a0ba8a">llvm::addFullAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2475576febdb5d6a1929ef786a57a03">llvm::getAddressFromInstr</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp/#af73334c0150d71c2d565ecce0d5e9ff4">X86SelectAddress</a>.</p>

</div>
</div>

### GV {#a69cfaa345b14e467ea8934fe48cc3365}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GlobalValue* llvm::X86AddressMode::GV</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrbuilder-h">X86InstrBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a41229d95ec1712486d97ae6c27a0ba8a">llvm::addFullAddress</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2475576febdb5d6a1929ef786a57a03">llvm::getAddressFromInstr</a>, <a href="#a593e839307453b63de7b7021e8cc059a">getFullAddress</a> and <a href="#a71e2b7928cd0743a0b1834cd441696eb">X86AddressMode</a>.</p>

</div>
</div>

### GVOpFlags {#a1894a1e6be0ec8bbc763476332735765}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86AddressMode::GVOpFlags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrbuilder-h">X86InstrBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a41229d95ec1712486d97ae6c27a0ba8a">llvm::addFullAddress</a>, <a href="#a593e839307453b63de7b7021e8cc059a">getFullAddress</a> and <a href="#a71e2b7928cd0743a0b1834cd441696eb">X86AddressMode</a>.</p>

</div>
</div>

### IndexReg {#af1965b0188d8595d0aaf002d0eb6d009}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86AddressMode::IndexReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrbuilder-h">X86InstrBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a41229d95ec1712486d97ae6c27a0ba8a">llvm::addFullAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5fd231b7f6dc1db67a2bb2f48bf5f342">llvm::X86TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2475576febdb5d6a1929ef786a57a03">llvm::getAddressFromInstr</a>, <a href="#a593e839307453b63de7b7021e8cc059a">getFullAddress</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#aa1616cca9834ae9c228730c62f4f8b43">anonymous{X86FastISel.cpp}::X86FastISel::tryToFoldLoadIntoMI</a> and <a href="#a71e2b7928cd0743a0b1834cd441696eb">X86AddressMode</a>.</p>

</div>
</div>

### Reg {#abdbb5443e06c46eba409abb252121105}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86AddressMode::Reg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrbuilder-h">X86InstrBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a41229d95ec1712486d97ae6c27a0ba8a">llvm::addFullAddress</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2475576febdb5d6a1929ef786a57a03">llvm::getAddressFromInstr</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp/#af73334c0150d71c2d565ecce0d5e9ff4">X86SelectAddress</a>.</p>

</div>
</div>

### Scale {#aad094c5c9174ced82b0e50cc1107f6b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86AddressMode::Scale</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrbuilder-h">X86InstrBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a41229d95ec1712486d97ae6c27a0ba8a">llvm::addFullAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2475576febdb5d6a1929ef786a57a03">llvm::getAddressFromInstr</a>, <a href="#a593e839307453b63de7b7021e8cc059a">getFullAddress</a> and <a href="#a71e2b7928cd0743a0b1834cd441696eb">X86AddressMode</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrbuilder-h">X86InstrBuilder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
