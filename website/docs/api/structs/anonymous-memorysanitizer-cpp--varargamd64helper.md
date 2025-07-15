---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-memorysanitizer-cpp-/varargamd64helper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `VarArgAMD64Helper` Struct Reference

<p>AMD64-specific implementation of <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelper">VarArgHelper</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{MemorySanitizer.cpp}::VarArgAMD64Helper { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase">VarArgHelperBase</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">ArgKind { <a href="#a18a7ddc93f80d96322c3bc1370d5e2cb">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c27d77da2f70625cd4b5861b924e403">VarArgAMD64Helper</a> (Function &amp;F, MemorySanitizer &amp;MS, MemorySanitizerVisitor &amp;MSV)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a18a7ddc93f80d96322c3bc1370d5e2cb">ArgKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52e566979db5e4a27df0ac914873e024">classifyArgument</a> (Value *arg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc81d19554e4eb245d659a89a2fd6f37">visitCallBase</a> (CallBase &amp;CB, IRBuilder&lt;&gt; &amp;IRB) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Visit a <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a>. <a href="#acc81d19554e4eb245d659a89a2fd6f37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86760d872237617ac5d36a58fd894bcc">finalizeInstrumentation</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finalize function instrumentation. <a href="#a86760d872237617ac5d36a58fd894bcc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a178a45caafd8f48868cd64f459732c">AMD64FpEndOffset</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b2f47a5ab632b00f73a516126b9f15a">VAArgTLSCopy</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c7a1e99affb9844d81614a13f72ec0b">VAArgTLSOriginCopy</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87ab2b1e864fa227226cbf537d6de081">VAArgOverflowSize</a> = nullptr</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe5b0a5857a28d5091b49eab545ce881">AMD64GpEndOffset</a> = 48</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c53315378e00c295afdd0950d0070b4">AMD64FpEndOffsetSSE</a> = 176</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb8062a12cfb2b5de7c22d45215adcbb">AMD64FpEndOffsetNoSSE</a> = <a href="#abe5b0a5857a28d5091b49eab545ce881">AMD64GpEndOffset</a></td>
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

<p>AMD64-specific implementation of <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelper">VarArgHelper</a>.</p>

<p>Definition at line 5498 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### ArgKind {#a18a7ddc93f80d96322c3bc1370d5e2cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{MemorySanitizer.cpp}::VarArgAMD64Helper::ArgKind </td>
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
<td class="doxyEnumItemName">AK_GeneralPurpose<a id="a18a7ddc93f80d96322c3bc1370d5e2cba3c5fadca157121de5518695854950554"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AK_FloatingPoint<a id="a18a7ddc93f80d96322c3bc1370d5e2cba0336c86e8431634202d38e3620f24437"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AK_Memory<a id="a18a7ddc93f80d96322c3bc1370d5e2cba378dce66ca62d1b45a926cbc1a0fed20"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 5511 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### VarArgAMD64Helper() {#a7c27d77da2f70625cd4b5861b924e403}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MemorySanitizer.cpp}::VarArgAMD64Helper::VarArgAMD64Helper (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/anonymous-memorysanitizer-cpp-/memorysanitizer">MemorySanitizer</a> &amp; MS, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor">MemorySanitizerVisitor</a> &amp; MSV)</td>
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



<p>Definition at line 5513 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a1a178a45caafd8f48868cd64f459732c">AMD64FpEndOffset</a>, <a href="#a4c53315378e00c295afdd0950d0070b4">AMD64FpEndOffsetSSE</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#ac623eb128c5461605b2eade89195434a">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::F</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#afe3dd307fd5cf1bb35263184495a00f4">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::MS</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#a3ca4068a52ed23406c810243aea0daa8">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::MSV</a> and <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#a45091e4338a16315424df2082d8e9275">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::VarArgHelperBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### classifyArgument() {#a52e566979db5e4a27df0ac914873e024}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgKind anonymous{MemorySanitizer.cpp}::VarArgAMD64Helper::classifyArgument (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * arg)</td>
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



<p>Definition at line 5527 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a18a7ddc93f80d96322c3bc1370d5e2cba0336c86e8431634202d38e3620f24437">AK_FloatingPoint</a>, <a href="#a18a7ddc93f80d96322c3bc1370d5e2cba3c5fadca157121de5518695854950554">AK_GeneralPurpose</a>, <a href="#a18a7ddc93f80d96322c3bc1370d5e2cba378dce66ca62d1b45a926cbc1a0fed20">AK_Memory</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="#acc81d19554e4eb245d659a89a2fd6f37">visitCallBase</a>.</p>

</div>
</div>

### finalizeInstrumentation() {#a86760d872237617ac5d36a58fd894bcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::VarArgAMD64Helper::finalizeInstrumentation ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finalize function instrumentation.</p>


<p>This method is called after visiting all interesting (see above) instructions in a function.</p>


<p>Definition at line 5648 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a1a178a45caafd8f48868cd64f459732c">AMD64FpEndOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1b30cd686a320a8e5cb4532fd3a552a8">llvm::IRBuilderBase::CreateAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a7e0a0c76340ba1fc52863f538f3e703d">llvm::IRBuilderBase::CreateBinaryIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1ac3f0b68c9c78c4f9e1eb09cd415db8">llvm::IRBuilderBase::CreateConstGEP1_32</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a53541ed6f92b18419f937f1f969aa0f6">llvm::IRBuilderBase::CreateIntToPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae9f2730f66215fdb82f4e41e45124811">llvm::IRBuilderBase::CreateMemCpy</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4910aab8d7c5528c1a3ac747856c3186">llvm::IRBuilderBase::CreateMemSet</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aae2c1bf70058f3665edaec525457030c">llvm::IRBuilderBase::CreatePtrToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a64748b5a9f8d8dd4499f84312e2c1336">llvm::IRBuilderBase::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae7be2e1490f01c049d748436f03760c5">llvm::IRBuilderBase::getInt8Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7ba5de75f50bb4a4ba920698edf39b28">llvm::Type::getInt8Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#adce9aed4162f58fbab5da93984822c3a">kParamTLSSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a58600da67d1e0fa57a2a70cd3be51d6e">kShadowTLSAlignment</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#afe3dd307fd5cf1bb35263184495a00f4">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::MS</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#a3ca4068a52ed23406c810243aea0daa8">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::MSV</a>, <a href="#a87ab2b1e864fa227226cbf537d6de081">VAArgOverflowSize</a>, <a href="#a5b2f47a5ab632b00f73a516126b9f15a">VAArgTLSCopy</a>, <a href="#a5c7a1e99affb9844d81614a13f72ec0b">VAArgTLSOriginCopy</a> and <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#a72c6c644a0fd7b5f440affe2512f8213">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::VAStartInstrumentationList</a>.</p>

</div>
</div>

### visitCallBase() {#acc81d19554e4eb245d659a89a2fd6f37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::VarArgAMD64Helper::visitCallBase (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Visit a <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a>.</p>

<p>Definition at line 5549 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a18a7ddc93f80d96322c3bc1370d5e2cba0336c86e8431634202d38e3620f24437">AK_FloatingPoint</a>, <a href="#a18a7ddc93f80d96322c3bc1370d5e2cba3c5fadca157121de5518695854950554">AK_GeneralPurpose</a>, <a href="#a18a7ddc93f80d96322c3bc1370d5e2cba378dce66ca62d1b45a926cbc1a0fed20">AK_Memory</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="#a1a178a45caafd8f48868cd64f459732c">AMD64FpEndOffset</a>, <a href="#abe5b0a5857a28d5091b49eab545ce881">AMD64GpEndOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ad027ea8803d83ee19b9a2e13aec6d655">llvm::CallBase::args</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a52e566979db5e4a27df0ac914873e024">classifyArgument</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#ac1c23e8e678cf1f5146ef3005277a59b">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::CleanUnusedTLS</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad4e4b11a1bf18be51b28b7fadfaa97d6">llvm::IRBuilderBase::CreateAlignedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae9f2730f66215fdb82f4e41e45124811">llvm::IRBuilderBase::CreateMemCpy</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aabfc20af4dcf7d94262824dcac2e7bed">llvm::IRBuilderBase::CreateStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#ac623eb128c5461605b2eade89195434a">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::F</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac3c35bd078a268a207f607d0f57dadba">llvm::CallBase::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a64748b5a9f8d8dd4499f84312e2c1336">llvm::IRBuilderBase::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae7be2e1490f01c049d748436f03760c5">llvm::IRBuilderBase::getInt8Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a104d6154321899b53e40455e71d8e83a">llvm::FunctionType::getNumParams</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#a50558d965872bd6791f30891dbf84487">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::getOriginPtrForVAArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a88cc5fa65ff17e62b49dc5fb4401f813">llvm::CallBase::getParamByValType</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#af8b287b4aad36e62604d98184648bc7e">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::getShadowPtrForVAArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a0760acbb386bfe440e697587140561cc">kMinOriginAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#adce9aed4162f58fbab5da93984822c3a">kParamTLSSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a58600da67d1e0fa57a2a70cd3be51d6e">kShadowTLSAlignment</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#afe3dd307fd5cf1bb35263184495a00f4">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::MS</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#a3ca4068a52ed23406c810243aea0daa8">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::MSV</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#a4cbb2344996abd4332716e76178ad4f4">llvm::CallBase::paramHasAttr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AMD64FpEndOffset {#a1a178a45caafd8f48868cd64f459732c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{MemorySanitizer.cpp}::VarArgAMD64Helper::AMD64FpEndOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5506 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a86760d872237617ac5d36a58fd894bcc">finalizeInstrumentation</a>, <a href="#a7c27d77da2f70625cd4b5861b924e403">VarArgAMD64Helper</a> and <a href="#acc81d19554e4eb245d659a89a2fd6f37">visitCallBase</a>.</p>

</div>
</div>

### VAArgOverflowSize {#a87ab2b1e864fa227226cbf537d6de081}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* anonymous{MemorySanitizer.cpp}::VarArgAMD64Helper::VAArgOverflowSize = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5509 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a86760d872237617ac5d36a58fd894bcc">finalizeInstrumentation</a>.</p>

</div>
</div>

### VAArgTLSCopy {#a5b2f47a5ab632b00f73a516126b9f15a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocaInst* anonymous{MemorySanitizer.cpp}::VarArgAMD64Helper::VAArgTLSCopy = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5507 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a86760d872237617ac5d36a58fd894bcc">finalizeInstrumentation</a>.</p>

</div>
</div>

### VAArgTLSOriginCopy {#a5c7a1e99affb9844d81614a13f72ec0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocaInst* anonymous{MemorySanitizer.cpp}::VarArgAMD64Helper::VAArgTLSOriginCopy = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5508 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a86760d872237617ac5d36a58fd894bcc">finalizeInstrumentation</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### AMD64FpEndOffsetNoSSE {#acb8062a12cfb2b5de7c22d45215adcbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{MemorySanitizer.cpp}::VarArgAMD64Helper::AMD64FpEndOffsetNoSSE = <a href="#abe5b0a5857a28d5091b49eab545ce881">AMD64GpEndOffset</a></td>
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



<p>Definition at line 5504 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>

</div>
</div>

### AMD64FpEndOffsetSSE {#a4c53315378e00c295afdd0950d0070b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{MemorySanitizer.cpp}::VarArgAMD64Helper::AMD64FpEndOffsetSSE = 176</td>
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



<p>Definition at line 5502 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a7c27d77da2f70625cd4b5861b924e403">VarArgAMD64Helper</a>.</p>

</div>
</div>

### AMD64GpEndOffset {#abe5b0a5857a28d5091b49eab545ce881}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{MemorySanitizer.cpp}::VarArgAMD64Helper::AMD64GpEndOffset = 48</td>
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



<p>Definition at line 5501 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#acc81d19554e4eb245d659a89a2fd6f37">visitCallBase</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
