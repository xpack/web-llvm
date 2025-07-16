---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-siloadstoreoptimizer-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{SILoadStoreOptimizer.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{SILoadStoreOptimizer.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-siloadstoreoptimizer-cpp-/addressregs">AddressRegs</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-siloadstoreoptimizer-cpp-/siloadstoreoptimizer">SILoadStoreOptimizer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-siloadstoreoptimizer-cpp-/siloadstoreoptimizerlegacy">SILoadStoreOptimizerLegacy</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">InstClassEnum { <a href="#a9cdba213ffd6154673089cc93fc01ab7">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ba14064f22753524c51583f271e597f">getOpcodeWidth</a> (const MachineInstr &amp;MI, const SIInstrInfo &amp;TII)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a9cdba213ffd6154673089cc93fc01ab7">InstClassEnum</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51840450ea858bf2bcc5713704034fdd">getInstClass</a> (unsigned Opc, const SIInstrInfo &amp;TII)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps instruction opcode to enum <a href="#a9cdba213ffd6154673089cc93fc01ab7">InstClassEnum</a>. <a href="#a51840450ea858bf2bcc5713704034fdd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33b80c3cfb98b829bd9642bfac84d2d1">getInstSubclass</a> (unsigned Opc, const SIInstrInfo &amp;TII)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determines instruction subclass from opcode. <a href="#a33b80c3cfb98b829bd9642bfac84d2d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/anonymous-siloadstoreoptimizer-cpp-/addressregs">AddressRegs</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3ab1fbdd7ae62be4c5a351f187e2308">getRegs</a> (unsigned Opc, const SIInstrInfo &amp;TII)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a771977b49f1c5450354b56d43e622f06">MaxAddressRegs</a> = 12 + 1 + 1</td>
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

### InstClassEnum {#a9cdba213ffd6154673089cc93fc01ab7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{SILoadStoreOptimizer.cpp}::InstClassEnum </td>
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
<td class="doxyEnumItemName">UNKNOWN<a id="a9cdba213ffd6154673089cc93fc01ab7a1b7c12263a77d8c513dbf1267cefc7fc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DS_READ<a id="a9cdba213ffd6154673089cc93fc01ab7a66dbbc43923dc01b699168dd03268f22"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DS_WRITE<a id="a9cdba213ffd6154673089cc93fc01ab7a3493feb96a33a365ee4f23f07354721a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S_BUFFER_LOAD_IMM<a id="a9cdba213ffd6154673089cc93fc01ab7ab15fea60c6ebc0b100637d2f328a7dcd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S_BUFFER_LOAD_SGPR_IMM<a id="a9cdba213ffd6154673089cc93fc01ab7a23cc9b82a472c3f9d8647fe0de81fb94"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S_LOAD_IMM<a id="a9cdba213ffd6154673089cc93fc01ab7a4700b9d4628af721191c8175a6d451d4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_LOAD<a id="a9cdba213ffd6154673089cc93fc01ab7a24241abee844da9a868cb72cea77b61f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_STORE<a id="a9cdba213ffd6154673089cc93fc01ab7a84c3d079210d69b19f54d25b11f61352"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MIMG<a id="a9cdba213ffd6154673089cc93fc01ab7a4c89efbad0ffb61616e70d1126e9e40f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TBUFFER_LOAD<a id="a9cdba213ffd6154673089cc93fc01ab7a9230b01226bae0bedf0bbaba0670baca"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TBUFFER_STORE<a id="a9cdba213ffd6154673089cc93fc01ab7aeae77549e330ba3f182baf3d4143caf3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLOBAL_LOAD_SADDR<a id="a9cdba213ffd6154673089cc93fc01ab7a19b9308019981514c947a943b99d4f57"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLOBAL_STORE_SADDR<a id="a9cdba213ffd6154673089cc93fc01ab7a3fad5029042f9dbe42f5a269251c8ef6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FLAT_LOAD<a id="a9cdba213ffd6154673089cc93fc01ab7af9c1d0895923665d3f9e96ac853f8b66"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FLAT_STORE<a id="a9cdba213ffd6154673089cc93fc01ab7afb7acc9cad190074fa3d42210c5822aa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLOBAL_LOAD<a id="a9cdba213ffd6154673089cc93fc01ab7a28107d06658472b56ab442f48a3703cd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLOBAL_STORE<a id="a9cdba213ffd6154673089cc93fc01ab7a666565e70bd7fea332dd473ee307b9cf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloadstoreoptimizer-cpp">SILoadStoreOptimizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### getInstClass() {#a51840450ea858bf2bcc5713704034fdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstClassEnum anonymous{SILoadStoreOptimizer.cpp}::getInstClass (unsigned Opc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> &amp; TII)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps instruction opcode to enum <a href="#a9cdba213ffd6154673089cc93fc01ab7">InstClassEnum</a>.</p>

<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloadstoreoptimizer-cpp">SILoadStoreOptimizer.cpp</a>.</p>


<p>References <a href="#a9cdba213ffd6154673089cc93fc01ab7a24241abee844da9a868cb72cea77b61f">BUFFER_LOAD</a>, <a href="#a9cdba213ffd6154673089cc93fc01ab7a84c3d079210d69b19f54d25b11f61352">BUFFER_STORE</a>, <a href="#a9cdba213ffd6154673089cc93fc01ab7a66dbbc43923dc01b699168dd03268f22">DS_READ</a>, <a href="#a9cdba213ffd6154673089cc93fc01ab7a3493feb96a33a365ee4f23f07354721a">DS_WRITE</a>, <a href="#a9cdba213ffd6154673089cc93fc01ab7af9c1d0895923665d3f9e96ac853f8b66">FLAT_LOAD</a>, <a href="#a9cdba213ffd6154673089cc93fc01ab7afb7acc9cad190074fa3d42210c5822aa">FLAT_STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ad144bab75c70002b0b3227acf782ebc3">llvm::AMDGPU::getMIMGBaseOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a688f3c46ebc34c00ea80c22c15a0b0c1">llvm::AMDGPU::getMTBUFBaseOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5f0dcf0fee31f552637de794eef6696e">llvm::AMDGPU::getMUBUFBaseOpcode</a>, <a href="#a9cdba213ffd6154673089cc93fc01ab7a19b9308019981514c947a943b99d4f57">GLOBAL_LOAD_SADDR</a>, <a href="#a9cdba213ffd6154673089cc93fc01ab7a3fad5029042f9dbe42f5a269251c8ef6">GLOBAL_STORE_SADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8f27aa11689bf9b12f6fb0e436e367c7">llvm::AMDGPU::hasNamedOperand</a>, <a href="#a9cdba213ffd6154673089cc93fc01ab7a4c89efbad0ffb61616e70d1126e9e40f">MIMG</a>, <a href="#a9cdba213ffd6154673089cc93fc01ab7ab15fea60c6ebc0b100637d2f328a7dcd">S_BUFFER_LOAD_IMM</a>, <a href="#a9cdba213ffd6154673089cc93fc01ab7a23cc9b82a472c3f9d8647fe0de81fb94">S_BUFFER_LOAD_SGPR_IMM</a>, <a href="#a9cdba213ffd6154673089cc93fc01ab7a4700b9d4628af721191c8175a6d451d4">S_LOAD_IMM</a>, <a href="#a9cdba213ffd6154673089cc93fc01ab7a9230b01226bae0bedf0bbaba0670baca">TBUFFER_LOAD</a>, <a href="#a9cdba213ffd6154673089cc93fc01ab7aeae77549e330ba3f182baf3d4143caf3">TBUFFER_STORE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="#a9cdba213ffd6154673089cc93fc01ab7a1b7c12263a77d8c513dbf1267cefc7fc">UNKNOWN</a>.</p>

</div>
</div>

### getInstSubclass() {#a33b80c3cfb98b829bd9642bfac84d2d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SILoadStoreOptimizer.cpp}::getInstSubclass (unsigned Opc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> &amp; TII)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determines instruction subclass from opcode.</p>


<p>Only instructions of the same subclass can be merged together. The merged instruction may have a different subclass but must have the same class.</p>


<p>Definition at line 584 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloadstoreoptimizer-cpp">SILoadStoreOptimizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a0b5b29d1275f84b9e530fd2419cc03ac">llvm::AMDGPU::getMIMGInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a688f3c46ebc34c00ea80c22c15a0b0c1">llvm::AMDGPU::getMTBUFBaseOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5f0dcf0fee31f552637de794eef6696e">llvm::AMDGPU::getMUBUFBaseOpcode</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### getOpcodeWidth() {#a6ba14064f22753524c51583f271e597f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SILoadStoreOptimizer.cpp}::getOpcodeWidth (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> &amp; TII)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloadstoreoptimizer-cpp">SILoadStoreOptimizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a23d9368d9915a85d5b54f9e0eda046dd">llvm::AMDGPU::getMTBUFElements</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af8ef23452a5c4ddf85e45cc9884ea3f4">llvm::AMDGPU::getMUBUFElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0eea77e7bfa82e0219d2ec7b4efbc94f">llvm::popcount</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### getRegs() {#ac3ab1fbdd7ae62be4c5a351f187e2308}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AddressRegs anonymous{SILoadStoreOptimizer.cpp}::getRegs (unsigned Opc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> &amp; TII)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 685 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloadstoreoptimizer-cpp">SILoadStoreOptimizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ae1884e3318cb1f8a4465b1b4bd4d9827">llvm::AMDGPU::getMIMGBaseOpcodeInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a0b5b29d1275f84b9e530fd2419cc03ac">llvm::AMDGPU::getMIMGInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4d33ed416833f75e97045b3ce8380132">llvm::AMDGPU::getMTBUFHasSoffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a181d2e596332f4062206a62830426b86">llvm::AMDGPU::getMTBUFHasSrsrc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aee6b630ac15f65f731a072177d51207c">llvm::AMDGPU::getMTBUFHasVAddr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa303bfa4cd838f547ba84ab62cd93c95">llvm::AMDGPU::getMUBUFHasSoffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#afd9dbd4307d57a7043f5412176674de4">llvm::AMDGPU::getMUBUFHasSrsrc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a723087d5f4635793f28b71ee6cdafecd">llvm::AMDGPU::getMUBUFHasVAddr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### MaxAddressRegs {#a771977b49f1c5450354b56d43e622f06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{SILoadStoreOptimizer.cpp}::MaxAddressRegs = 12 + 1 + 1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloadstoreoptimizer-cpp">SILoadStoreOptimizer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloadstoreoptimizer-cpp">SILoadStoreOptimizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
