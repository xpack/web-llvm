---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-memorysanitizer-cpp-/varargaarch64helper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `VarArgAArch64Helper` Struct Reference

<p>AArch64-specific implementation of <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelper">VarArgHelper</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{MemorySanitizer.cpp}::VarArgAArch64Helper { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top">ArgKind { <a href="#a38007828385e24ceef440220046c7862">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa8ec81769a72bb64d2312546928a507">VarArgAArch64Helper</a> (Function &amp;F, MemorySanitizer &amp;MS, MemorySanitizerVisitor &amp;MSV)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="#a38007828385e24ceef440220046c7862">ArgKind</a>, uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c087d0dd7be19eb6d334e3ca9aefd41">classifyArgument</a> (Type *T)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41ca0d5d12f5940de41f29cf08066e00">visitCallBase</a> (CallBase &amp;CB, IRBuilder&lt;&gt; &amp;IRB) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Visit a <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a>. <a href="#a41ca0d5d12f5940de41f29cf08066e00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2252a215cf90d91e6e98e77f42cf7954">getVAField64</a> (IRBuilder&lt;&gt; &amp;IRB, Value *VAListTag, int offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6ff76a12c77a8e0e142fa50f1a5104b">getVAField32</a> (IRBuilder&lt;&gt; &amp;IRB, Value *VAListTag, int offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1984e3e4e68c3ba67dc3dd32b9dfed6c">finalizeInstrumentation</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finalize function instrumentation. <a href="#a1984e3e4e68c3ba67dc3dd32b9dfed6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9f4de9b4ec57edb2438b79673a5ec6a">VAArgTLSCopy</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3316b61edf95b041fdfa4cc5a4a30ca9">VAArgOverflowSize</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a407b0dd82fc5d1d32caa492f2e5c65e4">kAArch64GrArgSize</a> = 64</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88f947cc43504925e3150eb261023f38">kAArch64VrArgSize</a> = 128</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d0152f34bc6602311efba2f6b501840">AArch64GrBegOffset</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a330af6c2b9d9e40ae1485f0a0df71eb9">AArch64GrEndOffset</a> = <a href="#a407b0dd82fc5d1d32caa492f2e5c65e4">kAArch64GrArgSize</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02277a9e3aad98e4c3d36f2378c694b1">AArch64VrBegOffset</a> = <a href="#a330af6c2b9d9e40ae1485f0a0df71eb9">AArch64GrEndOffset</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cfe7112f7120a9309e8549c5704f6b1">AArch64VrEndOffset</a> = ...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22d0152a937a027ca9abebce7e5163f3">AArch64VAEndOffset</a> = <a href="#a8cfe7112f7120a9309e8549c5704f6b1">AArch64VrEndOffset</a></td>
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

<p>AArch64-specific implementation of <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelper">VarArgHelper</a>.</p>

<p>Definition at line 5723 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### ArgKind {#a38007828385e24ceef440220046c7862}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{MemorySanitizer.cpp}::VarArgAArch64Helper::ArgKind </td>
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
<td class="doxyEnumItemName">AK_GeneralPurpose<a id="a38007828385e24ceef440220046c7862a4111bc1ce1c9e9a1455976439aac5985"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AK_FloatingPoint<a id="a38007828385e24ceef440220046c7862a09a2ce3cbc0aade0c64ad0d4225012ab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AK_Memory<a id="a38007828385e24ceef440220046c7862a4ca9efb33354e3126119d56eb1a14021"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 5738 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### VarArgAArch64Helper() {#aaa8ec81769a72bb64d2312546928a507}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MemorySanitizer.cpp}::VarArgAArch64Helper::VarArgAArch64Helper (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/anonymous-memorysanitizer-cpp-/memorysanitizer">MemorySanitizer</a> &amp; MS, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor">MemorySanitizerVisitor</a> &amp; MSV)</td>
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



<p>Definition at line 5740 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#ac623eb128c5461605b2eade89195434a">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::F</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#afe3dd307fd5cf1bb35263184495a00f4">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::MS</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#a3ca4068a52ed23406c810243aea0daa8">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::MSV</a> and <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#a45091e4338a16315424df2082d8e9275">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::VarArgHelperBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### classifyArgument() {#a7c087d0dd7be19eb6d334e3ca9aefd41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; ArgKind, uint64_t &gt; anonymous{MemorySanitizer.cpp}::VarArgAArch64Helper::classifyArgument (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T)</td>
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



<p>Definition at line 5745 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a38007828385e24ceef440220046c7862a09a2ce3cbc0aade0c64ad0d4225012ab">AK_FloatingPoint</a>, <a href="#a38007828385e24ceef440220046c7862a4111bc1ce1c9e9a1455976439aac5985">AK_GeneralPurpose</a>, <a href="#a38007828385e24ceef440220046c7862a4ca9efb33354e3126119d56eb1a14021">AK_Memory</a>, <a href="#a7c087d0dd7be19eb6d334e3ca9aefd41">classifyArgument</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="#a7c087d0dd7be19eb6d334e3ca9aefd41">classifyArgument</a> and <a href="#a41ca0d5d12f5940de41f29cf08066e00">visitCallBase</a>.</p>

</div>
</div>

### finalizeInstrumentation() {#a1984e3e4e68c3ba67dc3dd32b9dfed6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::VarArgAArch64Helper::finalizeInstrumentation ()</td>
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


<p>Definition at line 5848 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a22d0152a937a027ca9abebce7e5163f3">AArch64VAEndOffset</a>, <a href="#a02277a9e3aad98e4c3d36f2378c694b1">AArch64VrBegOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1b30cd686a320a8e5cb4532fd3a552a8">llvm::IRBuilderBase::CreateAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a7e0a0c76340ba1fc52863f538f3e703d">llvm::IRBuilderBase::CreateBinaryIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad9b7f1f880f1c88e6856df87189d50f4">llvm::IRBuilderBase::CreateInBoundsPtrAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a53541ed6f92b18419f937f1f969aa0f6">llvm::IRBuilderBase::CreateIntToPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae9f2730f66215fdb82f4e41e45124811">llvm::IRBuilderBase::CreateMemCpy</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4910aab8d7c5528c1a3ac747856c3186">llvm::IRBuilderBase::CreateMemSet</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a92c83e803f2cf22906da0aaec44ff6d7">llvm::IRBuilderBase::CreateSub</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8246a9e9405ffe2a9d8d020a949c8e96">llvm::IRBuilderBase::getInt32</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a64748b5a9f8d8dd4499f84312e2c1336">llvm::IRBuilderBase::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae7be2e1490f01c049d748436f03760c5">llvm::IRBuilderBase::getInt8Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7ba5de75f50bb4a4ba920698edf39b28">llvm::Type::getInt8Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab73bb6948312ca0f98055c6a74c37045">llvm::IRBuilderBase::getPtrTy</a>, <a href="#ab6ff76a12c77a8e0e142fa50f1a5104b">getVAField32</a>, <a href="#a2252a215cf90d91e6e98e77f42cf7954">getVAField64</a>, <a href="#a407b0dd82fc5d1d32caa492f2e5c65e4">kAArch64GrArgSize</a>, <a href="#a88f947cc43504925e3150eb261023f38">kAArch64VrArgSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#adce9aed4162f58fbab5da93984822c3a">kParamTLSSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a58600da67d1e0fa57a2a70cd3be51d6e">kShadowTLSAlignment</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#afe3dd307fd5cf1bb35263184495a00f4">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::MS</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#a3ca4068a52ed23406c810243aea0daa8">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::MSV</a>, <a href="#a3316b61edf95b041fdfa4cc5a4a30ca9">VAArgOverflowSize</a>, <a href="#ab9f4de9b4ec57edb2438b79673a5ec6a">VAArgTLSCopy</a> and <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#a72c6c644a0fd7b5f440affe2512f8213">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::VAStartInstrumentationList</a>.</p>

</div>
</div>

### getVAField32() {#ab6ff76a12c77a8e0e142fa50f1a5104b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{MemorySanitizer.cpp}::VarArgAArch64Helper::getVAField32 (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * VAListTag, int offset)</td>
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



<p>Definition at line 5839 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a53541ed6f92b18419f937f1f969aa0f6">llvm::IRBuilderBase::CreateIntToPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aae2c1bf70058f3665edaec525457030c">llvm::IRBuilderBase::CreatePtrToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5253081f40ffcad9c0e8ba6a5c437006">llvm::IRBuilderBase::CreateSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5852dc0d180581d34902e8abcbf7e930">llvm::IRBuilderBase::getInt32Ty</a> and <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#afe3dd307fd5cf1bb35263184495a00f4">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::MS</a>.</p>


<p>Referenced by <a href="#a1984e3e4e68c3ba67dc3dd32b9dfed6c">finalizeInstrumentation</a>.</p>

</div>
</div>

### getVAField64() {#a2252a215cf90d91e6e98e77f42cf7954}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{MemorySanitizer.cpp}::VarArgAArch64Helper::getVAField64 (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * VAListTag, int offset)</td>
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



<p>Definition at line 5830 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a53541ed6f92b18419f937f1f969aa0f6">llvm::IRBuilderBase::CreateIntToPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aae2c1bf70058f3665edaec525457030c">llvm::IRBuilderBase::CreatePtrToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a> and <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#afe3dd307fd5cf1bb35263184495a00f4">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::MS</a>.</p>


<p>Referenced by <a href="#a1984e3e4e68c3ba67dc3dd32b9dfed6c">finalizeInstrumentation</a>.</p>

</div>
</div>

### visitCallBase() {#a41ca0d5d12f5940de41f29cf08066e00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::VarArgAArch64Helper::visitCallBase (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB)</td>
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

<p>Definition at line 5776 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a3d0152f34bc6602311efba2f6b501840">AArch64GrBegOffset</a>, <a href="#a330af6c2b9d9e40ae1485f0a0df71eb9">AArch64GrEndOffset</a>, <a href="#a22d0152a937a027ca9abebce7e5163f3">AArch64VAEndOffset</a>, <a href="#a02277a9e3aad98e4c3d36f2378c694b1">AArch64VrBegOffset</a>, <a href="#a8cfe7112f7120a9309e8549c5704f6b1">AArch64VrEndOffset</a>, <a href="#a38007828385e24ceef440220046c7862a09a2ce3cbc0aade0c64ad0d4225012ab">AK_FloatingPoint</a>, <a href="#a38007828385e24ceef440220046c7862a4111bc1ce1c9e9a1455976439aac5985">AK_GeneralPurpose</a>, <a href="#a38007828385e24ceef440220046c7862a4ca9efb33354e3126119d56eb1a14021">AK_Memory</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ad027ea8803d83ee19b9a2e13aec6d655">llvm::CallBase::args</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="#a7c087d0dd7be19eb6d334e3ca9aefd41">classifyArgument</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#ac1c23e8e678cf1f5146ef3005277a59b">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::CleanUnusedTLS</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad4e4b11a1bf18be51b28b7fadfaa97d6">llvm::IRBuilderBase::CreateAlignedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aabfc20af4dcf7d94262824dcac2e7bed">llvm::IRBuilderBase::CreateStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#ac623eb128c5461605b2eade89195434a">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::F</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac3c35bd078a268a207f607d0f57dadba">llvm::CallBase::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a64748b5a9f8d8dd4499f84312e2c1336">llvm::IRBuilderBase::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a104d6154321899b53e40455e71d8e83a">llvm::FunctionType::getNumParams</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#af8b287b4aad36e62604d98184648bc7e">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::getShadowPtrForVAArgument</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#adce9aed4162f58fbab5da93984822c3a">kParamTLSSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a58600da67d1e0fa57a2a70cd3be51d6e">kShadowTLSAlignment</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#afe3dd307fd5cf1bb35263184495a00f4">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::MS</a> and <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#a3ca4068a52ed23406c810243aea0daa8">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::MSV</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### VAArgOverflowSize {#a3316b61edf95b041fdfa4cc5a4a30ca9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* anonymous{MemorySanitizer.cpp}::VarArgAArch64Helper::VAArgOverflowSize = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5736 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a1984e3e4e68c3ba67dc3dd32b9dfed6c">finalizeInstrumentation</a>.</p>

</div>
</div>

### VAArgTLSCopy {#ab9f4de9b4ec57edb2438b79673a5ec6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocaInst* anonymous{MemorySanitizer.cpp}::VarArgAArch64Helper::VAArgTLSCopy = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5735 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a1984e3e4e68c3ba67dc3dd32b9dfed6c">finalizeInstrumentation</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### AArch64GrBegOffset {#a3d0152f34bc6602311efba2f6b501840}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{MemorySanitizer.cpp}::VarArgAArch64Helper::AArch64GrBegOffset = 0</td>
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



<p>Definition at line 5727 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a41ca0d5d12f5940de41f29cf08066e00">visitCallBase</a>.</p>

</div>
</div>

### AArch64GrEndOffset {#a330af6c2b9d9e40ae1485f0a0df71eb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{MemorySanitizer.cpp}::VarArgAArch64Helper::AArch64GrEndOffset = <a href="#a407b0dd82fc5d1d32caa492f2e5c65e4">kAArch64GrArgSize</a></td>
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



<p>Definition at line 5728 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a41ca0d5d12f5940de41f29cf08066e00">visitCallBase</a>.</p>

</div>
</div>

### AArch64VAEndOffset {#a22d0152a937a027ca9abebce7e5163f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{MemorySanitizer.cpp}::VarArgAArch64Helper::AArch64VAEndOffset = <a href="#a8cfe7112f7120a9309e8549c5704f6b1">AArch64VrEndOffset</a></td>
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



<p>Definition at line 5733 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a1984e3e4e68c3ba67dc3dd32b9dfed6c">finalizeInstrumentation</a> and <a href="#a41ca0d5d12f5940de41f29cf08066e00">visitCallBase</a>.</p>

</div>
</div>

### AArch64VrBegOffset {#a02277a9e3aad98e4c3d36f2378c694b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{MemorySanitizer.cpp}::VarArgAArch64Helper::AArch64VrBegOffset = <a href="#a330af6c2b9d9e40ae1485f0a0df71eb9">AArch64GrEndOffset</a></td>
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



<p>Definition at line 5730 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a1984e3e4e68c3ba67dc3dd32b9dfed6c">finalizeInstrumentation</a> and <a href="#a41ca0d5d12f5940de41f29cf08066e00">visitCallBase</a>.</p>

</div>
</div>

### AArch64VrEndOffset {#a8cfe7112f7120a9309e8549c5704f6b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{MemorySanitizer.cpp}::VarArgAArch64Helper::AArch64VrEndOffset</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
      <a href="#a02277a9e3aad98e4c3d36f2378c694b1">AArch64VrBegOffset</a> + <a href="#a88f947cc43504925e3150eb261023f38">kAArch64VrArgSize</a>
</div>
</dd>
</dl>

<p>Definition at line 5731 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a41ca0d5d12f5940de41f29cf08066e00">visitCallBase</a>.</p>

</div>
</div>

### kAArch64GrArgSize {#a407b0dd82fc5d1d32caa492f2e5c65e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{MemorySanitizer.cpp}::VarArgAArch64Helper::kAArch64GrArgSize = 64</td>
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



<p>Definition at line 5724 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a1984e3e4e68c3ba67dc3dd32b9dfed6c">finalizeInstrumentation</a>.</p>

</div>
</div>

### kAArch64VrArgSize {#a88f947cc43504925e3150eb261023f38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{MemorySanitizer.cpp}::VarArgAArch64Helper::kAArch64VrArgSize = 128</td>
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



<p>Definition at line 5725 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a1984e3e4e68c3ba67dc3dd32b9dfed6c">finalizeInstrumentation</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
