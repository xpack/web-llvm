---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-memorysanitizer-cpp-/varargsystemzhelper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `VarArgSystemZHelper` Struct Reference

<p>SystemZ-specific implementation of <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelper">VarArgHelper</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{MemorySanitizer.cpp}::VarArgSystemZHelper { ... }
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ArgKind { <a href="#a468b1486c4619f3b7f6f7e12d277cc6e">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ShadowExtension { <a href="#a63c66175e1929cc19e1d92352595ebe1">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20caa6e1947b3736ad8ff941dc4d6dff">VarArgSystemZHelper</a> (Function &amp;F, MemorySanitizer &amp;MS, MemorySanitizerVisitor &amp;MSV)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a468b1486c4619f3b7f6f7e12d277cc6e">ArgKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af68ee6d3a8b0476f78254a7c6a888ade">classifyArgument</a> (Type *T)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a63c66175e1929cc19e1d92352595ebe1">ShadowExtension</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d1221047aae479ec27a751236ae95e6">getShadowExtension</a> (const CallBase &amp;CB, unsigned ArgNo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0bc023f29f779469e5e8e3f92b9db0f">visitCallBase</a> (CallBase &amp;CB, IRBuilder&lt;&gt; &amp;IRB) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Visit a <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a>. <a href="#af0bc023f29f779469e5e8e3f92b9db0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a831a9764856351a89b415e39b0557d06">copyRegSaveArea</a> (IRBuilder&lt;&gt; &amp;IRB, Value *VAListTag)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91f4aecc323597d1fa23c01644950f45">copyOverflowArea</a> (IRBuilder&lt;&gt; &amp;IRB, Value *VAListTag)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeff71653a760718fea2a9b166f8df1b4">finalizeInstrumentation</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finalize function instrumentation. <a href="#aeff71653a760718fea2a9b166f8df1b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54780572278b47a95960b82e110aa9dc">IsSoftFloatABI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a033823c3841f3579f00dda619f50d1c7">VAArgTLSCopy</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f5a7330ff27331bd15a76329168a8e6">VAArgTLSOriginCopy</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a929d0ca0dbbae04dc8d4174acc5c86ab">VAArgOverflowSize</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff472fcaf889bcefd1c94f80effd1a13">SystemZGpOffset</a> = 16</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad34aa743948bff9da779883e57d545d2">SystemZGpEndOffset</a> = 56</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49c9c4e4cabab591afe0ba76354dfe04">SystemZFpOffset</a> = 128</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf7e4e2588c60fec47997b4c8874b3a0">SystemZFpEndOffset</a> = 160</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeefbb6207e17c525b2afad2b3aa24ffb">SystemZMaxVrArgs</a> = 8</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8b9c78abe59bfab0b87c5d9c2e2fc7a">SystemZRegSaveAreaSize</a> = 160</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69a54dd62aa091a615c4d850d0372c51">SystemZOverflowOffset</a> = 160</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c2bd17808c0303e7a2724883b78ec04">SystemZVAListTagSize</a> = 32</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3e457b655994d6a120c6b827a6524a8">SystemZOverflowArgAreaPtrOffset</a> = 16</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09688e5a25f0cecec43287360c897501">SystemZRegSaveAreaPtrOffset</a> = 24</td>
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

<p>SystemZ-specific implementation of <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelper">VarArgHelper</a>.</p>

<p>Definition at line 6118 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### ArgKind {#a468b1486c4619f3b7f6f7e12d277cc6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class anonymous{MemorySanitizer.cpp}::VarArgSystemZHelper::ArgKind </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">GeneralPurpose<a id="a468b1486c4619f3b7f6f7e12d277cc6eab7f023dbb86242b37e451d0b36dde93d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FloatingPoint<a id="a468b1486c4619f3b7f6f7e12d277cc6ea072f02cab92dcb89792657037629ac66"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Vector<a id="a468b1486c4619f3b7f6f7e12d277cc6ea57dea6f5039281b7fee517fc43bf3110"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Memory<a id="a468b1486c4619f3b7f6f7e12d277cc6ea4789f23283b3a61f858b641a1bef19a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Indirect<a id="a468b1486c4619f3b7f6f7e12d277cc6ea0b5ca9d0c6dbcbb3e299361cd4e4a79c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 6135 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>

</div>
</div>

### ShadowExtension {#a63c66175e1929cc19e1d92352595ebe1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class anonymous{MemorySanitizer.cpp}::VarArgSystemZHelper::ShadowExtension </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">None<a id="a63c66175e1929cc19e1d92352595ebe1a6adf97f83acf6453d4a6a4b1070f3754"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Zero<a id="a63c66175e1929cc19e1d92352595ebe1ad7ed4ee1df437474d005188535f74875"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sign<a id="a63c66175e1929cc19e1d92352595ebe1a31c6b3fdfaaa80dba2dbf92a4600524c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 6143 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### VarArgSystemZHelper() {#a20caa6e1947b3736ad8ff941dc4d6dff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MemorySanitizer.cpp}::VarArgSystemZHelper::VarArgSystemZHelper (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/anonymous-memorysanitizer-cpp-/memorysanitizer">MemorySanitizer</a> &amp; MS, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor">MemorySanitizerVisitor</a> &amp; MSV)</td>
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



<p>Definition at line 6145 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#ac623eb128c5461605b2eade89195434a">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::F</a>, <a href="#a54780572278b47a95960b82e110aa9dc">IsSoftFloatABI</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#afe3dd307fd5cf1bb35263184495a00f4">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::MS</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#a3ca4068a52ed23406c810243aea0daa8">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::MSV</a>, <a href="#a4c2bd17808c0303e7a2724883b78ec04">SystemZVAListTagSize</a> and <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#a45091e4338a16315424df2082d8e9275">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::VarArgHelperBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### classifyArgument() {#af68ee6d3a8b0476f78254a7c6a888ade}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgKind anonymous{MemorySanitizer.cpp}::VarArgSystemZHelper::classifyArgument (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T)</td>
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



<p>Definition at line 6150 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a468b1486c4619f3b7f6f7e12d277cc6ea072f02cab92dcb89792657037629ac66">FloatingPoint</a>, <a href="#a468b1486c4619f3b7f6f7e12d277cc6eab7f023dbb86242b37e451d0b36dde93d">GeneralPurpose</a>, <a href="#a468b1486c4619f3b7f6f7e12d277cc6ea0b5ca9d0c6dbcbb3e299361cd4e4a79c">Indirect</a>, <a href="#a54780572278b47a95960b82e110aa9dc">IsSoftFloatABI</a>, <a href="#a468b1486c4619f3b7f6f7e12d277cc6ea4789f23283b3a61f858b641a1bef19a3">Memory</a> and <a href="#a468b1486c4619f3b7f6f7e12d277cc6ea57dea6f5039281b7fee517fc43bf3110">Vector</a>.</p>


<p>Referenced by <a href="#af0bc023f29f779469e5e8e3f92b9db0f">visitCallBase</a>.</p>

</div>
</div>

### copyOverflowArea() {#a91f4aecc323597d1fa23c01644950f45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::VarArgSystemZHelper::copyOverflowArea (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * VAListTag)</td>
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



<p>Definition at line 6333 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1ac3f0b68c9c78c4f9e1eb09cd415db8">llvm::IRBuilderBase::CreateConstGEP1_32</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a53541ed6f92b18419f937f1f969aa0f6">llvm::IRBuilderBase::CreateIntToPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae9f2730f66215fdb82f4e41e45124811">llvm::IRBuilderBase::CreateMemCpy</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aae2c1bf70058f3665edaec525457030c">llvm::IRBuilderBase::CreatePtrToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae7be2e1490f01c049d748436f03760c5">llvm::IRBuilderBase::getInt8Ty</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#afe3dd307fd5cf1bb35263184495a00f4">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::MS</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#a3ca4068a52ed23406c810243aea0daa8">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::MSV</a>, <a href="#ac3e457b655994d6a120c6b827a6524a8">SystemZOverflowArgAreaPtrOffset</a>, <a href="#a69a54dd62aa091a615c4d850d0372c51">SystemZOverflowOffset</a>, <a href="#a929d0ca0dbbae04dc8d4174acc5c86ab">VAArgOverflowSize</a>, <a href="#a033823c3841f3579f00dda619f50d1c7">VAArgTLSCopy</a> and <a href="#a1f5a7330ff27331bd15a76329168a8e6">VAArgTLSOriginCopy</a>.</p>


<p>Referenced by <a href="#aeff71653a760718fea2a9b166f8df1b4">finalizeInstrumentation</a>.</p>

</div>
</div>

### copyRegSaveArea() {#a831a9764856351a89b415e39b0557d06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::VarArgSystemZHelper::copyRegSaveArea (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * VAListTag)</td>
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



<p>Definition at line 6307 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a53541ed6f92b18419f937f1f969aa0f6">llvm::IRBuilderBase::CreateIntToPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae9f2730f66215fdb82f4e41e45124811">llvm::IRBuilderBase::CreateMemCpy</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aae2c1bf70058f3665edaec525457030c">llvm::IRBuilderBase::CreatePtrToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae7be2e1490f01c049d748436f03760c5">llvm::IRBuilderBase::getInt8Ty</a>, <a href="#a54780572278b47a95960b82e110aa9dc">IsSoftFloatABI</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#afe3dd307fd5cf1bb35263184495a00f4">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::MS</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#a3ca4068a52ed23406c810243aea0daa8">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::MSV</a>, <a href="#ad34aa743948bff9da779883e57d545d2">SystemZGpEndOffset</a>, <a href="#a09688e5a25f0cecec43287360c897501">SystemZRegSaveAreaPtrOffset</a>, <a href="#ab8b9c78abe59bfab0b87c5d9c2e2fc7a">SystemZRegSaveAreaSize</a>, <a href="#a033823c3841f3579f00dda619f50d1c7">VAArgTLSCopy</a> and <a href="#a1f5a7330ff27331bd15a76329168a8e6">VAArgTLSOriginCopy</a>.</p>


<p>Referenced by <a href="#aeff71653a760718fea2a9b166f8df1b4">finalizeInstrumentation</a>.</p>

</div>
</div>

### finalizeInstrumentation() {#aeff71653a760718fea2a9b166f8df1b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::VarArgSystemZHelper::finalizeInstrumentation ()</td>
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


<p>Definition at line 6357 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a91f4aecc323597d1fa23c01644950f45">copyOverflowArea</a>, <a href="#a831a9764856351a89b415e39b0557d06">copyRegSaveArea</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1b30cd686a320a8e5cb4532fd3a552a8">llvm::IRBuilderBase::CreateAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a7e0a0c76340ba1fc52863f538f3e703d">llvm::IRBuilderBase::CreateBinaryIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae9f2730f66215fdb82f4e41e45124811">llvm::IRBuilderBase::CreateMemCpy</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4910aab8d7c5528c1a3ac747856c3186">llvm::IRBuilderBase::CreateMemSet</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a64748b5a9f8d8dd4499f84312e2c1336">llvm::IRBuilderBase::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae7be2e1490f01c049d748436f03760c5">llvm::IRBuilderBase::getInt8Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7ba5de75f50bb4a4ba920698edf39b28">llvm::Type::getInt8Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#adce9aed4162f58fbab5da93984822c3a">kParamTLSSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a58600da67d1e0fa57a2a70cd3be51d6e">kShadowTLSAlignment</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#afe3dd307fd5cf1bb35263184495a00f4">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::MS</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#a3ca4068a52ed23406c810243aea0daa8">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::MSV</a>, <a href="#a69a54dd62aa091a615c4d850d0372c51">SystemZOverflowOffset</a>, <a href="#a929d0ca0dbbae04dc8d4174acc5c86ab">VAArgOverflowSize</a>, <a href="#a033823c3841f3579f00dda619f50d1c7">VAArgTLSCopy</a>, <a href="#a1f5a7330ff27331bd15a76329168a8e6">VAArgTLSOriginCopy</a> and <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#a72c6c644a0fd7b5f440affe2512f8213">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::VAStartInstrumentationList</a>.</p>

</div>
</div>

### getShadowExtension() {#a7d1221047aae479ec27a751236ae95e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ShadowExtension anonymous{MemorySanitizer.cpp}::VarArgSystemZHelper::getShadowExtension (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, unsigned ArgNo)</td>
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



<p>Definition at line 6168 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a63c66175e1929cc19e1d92352595ebe1a6adf97f83acf6453d4a6a4b1070f3754">None</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a4cbb2344996abd4332716e76178ad4f4">llvm::CallBase::paramHasAttr</a>, <a href="#a63c66175e1929cc19e1d92352595ebe1a31c6b3fdfaaa80dba2dbf92a4600524c">Sign</a> and <a href="#a63c66175e1929cc19e1d92352595ebe1ad7ed4ee1df437474d005188535f74875">Zero</a>.</p>


<p>Referenced by <a href="#af0bc023f29f779469e5e8e3f92b9db0f">visitCallBase</a>.</p>

</div>
</div>

### visitCallBase() {#af0bc023f29f779469e5e8e3f92b9db0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::VarArgSystemZHelper::visitCallBase (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB)</td>
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

<p>Definition at line 6187 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ad027ea8803d83ee19b9a2e13aec6d655">llvm::CallBase::args</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af68ee6d3a8b0476f78254a7c6a888ade">classifyArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a53541ed6f92b18419f937f1f969aa0f6">llvm::IRBuilderBase::CreateIntToPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aabfc20af4dcf7d94262824dcac2e7bed">llvm::IRBuilderBase::CreateStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#ac623eb128c5461605b2eade89195434a">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::F</a>, <a href="#a468b1486c4619f3b7f6f7e12d277cc6ea072f02cab92dcb89792657037629ac66">FloatingPoint</a>, <a href="#a468b1486c4619f3b7f6f7e12d277cc6eab7f023dbb86242b37e451d0b36dde93d">GeneralPurpose</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac3c35bd078a268a207f607d0f57dadba">llvm::CallBase::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a64748b5a9f8d8dd4499f84312e2c1336">llvm::IRBuilderBase::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a104d6154321899b53e40455e71d8e83a">llvm::FunctionType::getNumParams</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#a50558d965872bd6791f30891dbf84487">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::getOriginPtrForVAArgument</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#a44ec33d41f2d1ca12b7b6aa206877a5a">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::getShadowAddrForVAArgument</a>, <a href="#a7d1221047aae479ec27a751236ae95e6">getShadowExtension</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a468b1486c4619f3b7f6f7e12d277cc6ea0b5ca9d0c6dbcbb3e299361cd4e4a79c">Indirect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a0760acbb386bfe440e697587140561cc">kMinOriginAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#adce9aed4162f58fbab5da93984822c3a">kParamTLSSize</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a468b1486c4619f3b7f6f7e12d277cc6ea4789f23283b3a61f858b641a1bef19a3">Memory</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#afe3dd307fd5cf1bb35263184495a00f4">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::MS</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#a3ca4068a52ed23406c810243aea0daa8">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::MSV</a>, <a href="#a63c66175e1929cc19e1d92352595ebe1a6adf97f83acf6453d4a6a4b1070f3754">None</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a4cbb2344996abd4332716e76178ad4f4">llvm::CallBase::paramHasAttr</a>, <a href="#a63c66175e1929cc19e1d92352595ebe1a31c6b3fdfaaa80dba2dbf92a4600524c">Sign</a>, <a href="#aaf7e4e2588c60fec47997b4c8874b3a0">SystemZFpEndOffset</a>, <a href="#a49c9c4e4cabab591afe0ba76354dfe04">SystemZFpOffset</a>, <a href="#ad34aa743948bff9da779883e57d545d2">SystemZGpEndOffset</a>, <a href="#aff472fcaf889bcefd1c94f80effd1a13">SystemZGpOffset</a>, <a href="#aeefbb6207e17c525b2afad2b3aa24ffb">SystemZMaxVrArgs</a>, <a href="#a69a54dd62aa091a615c4d850d0372c51">SystemZOverflowOffset</a> and <a href="#a468b1486c4619f3b7f6f7e12d277cc6ea57dea6f5039281b7fee517fc43bf3110">Vector</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### IsSoftFloatABI {#a54780572278b47a95960b82e110aa9dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MemorySanitizer.cpp}::VarArgSystemZHelper::IsSoftFloatABI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 6130 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#af68ee6d3a8b0476f78254a7c6a888ade">classifyArgument</a>, <a href="#a831a9764856351a89b415e39b0557d06">copyRegSaveArea</a> and <a href="#a20caa6e1947b3736ad8ff941dc4d6dff">VarArgSystemZHelper</a>.</p>

</div>
</div>

### VAArgOverflowSize {#a929d0ca0dbbae04dc8d4174acc5c86ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* anonymous{MemorySanitizer.cpp}::VarArgSystemZHelper::VAArgOverflowSize = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 6133 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a91f4aecc323597d1fa23c01644950f45">copyOverflowArea</a> and <a href="#aeff71653a760718fea2a9b166f8df1b4">finalizeInstrumentation</a>.</p>

</div>
</div>

### VAArgTLSCopy {#a033823c3841f3579f00dda619f50d1c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocaInst* anonymous{MemorySanitizer.cpp}::VarArgSystemZHelper::VAArgTLSCopy = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 6131 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a91f4aecc323597d1fa23c01644950f45">copyOverflowArea</a>, <a href="#a831a9764856351a89b415e39b0557d06">copyRegSaveArea</a> and <a href="#aeff71653a760718fea2a9b166f8df1b4">finalizeInstrumentation</a>.</p>

</div>
</div>

### VAArgTLSOriginCopy {#a1f5a7330ff27331bd15a76329168a8e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocaInst* anonymous{MemorySanitizer.cpp}::VarArgSystemZHelper::VAArgTLSOriginCopy = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 6132 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a91f4aecc323597d1fa23c01644950f45">copyOverflowArea</a>, <a href="#a831a9764856351a89b415e39b0557d06">copyRegSaveArea</a> and <a href="#aeff71653a760718fea2a9b166f8df1b4">finalizeInstrumentation</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### SystemZFpEndOffset {#aaf7e4e2588c60fec47997b4c8874b3a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{MemorySanitizer.cpp}::VarArgSystemZHelper::SystemZFpEndOffset = 160</td>
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



<p>Definition at line 6122 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#af0bc023f29f779469e5e8e3f92b9db0f">visitCallBase</a>.</p>

</div>
</div>

### SystemZFpOffset {#a49c9c4e4cabab591afe0ba76354dfe04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{MemorySanitizer.cpp}::VarArgSystemZHelper::SystemZFpOffset = 128</td>
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



<p>Definition at line 6121 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#af0bc023f29f779469e5e8e3f92b9db0f">visitCallBase</a>.</p>

</div>
</div>

### SystemZGpEndOffset {#ad34aa743948bff9da779883e57d545d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{MemorySanitizer.cpp}::VarArgSystemZHelper::SystemZGpEndOffset = 56</td>
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



<p>Definition at line 6120 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a831a9764856351a89b415e39b0557d06">copyRegSaveArea</a> and <a href="#af0bc023f29f779469e5e8e3f92b9db0f">visitCallBase</a>.</p>

</div>
</div>

### SystemZGpOffset {#aff472fcaf889bcefd1c94f80effd1a13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{MemorySanitizer.cpp}::VarArgSystemZHelper::SystemZGpOffset = 16</td>
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



<p>Definition at line 6119 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#af0bc023f29f779469e5e8e3f92b9db0f">visitCallBase</a>.</p>

</div>
</div>

### SystemZMaxVrArgs {#aeefbb6207e17c525b2afad2b3aa24ffb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{MemorySanitizer.cpp}::VarArgSystemZHelper::SystemZMaxVrArgs = 8</td>
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



<p>Definition at line 6123 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#af0bc023f29f779469e5e8e3f92b9db0f">visitCallBase</a>.</p>

</div>
</div>

### SystemZOverflowArgAreaPtrOffset {#ac3e457b655994d6a120c6b827a6524a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{MemorySanitizer.cpp}::VarArgSystemZHelper::SystemZOverflowArgAreaPtrOffset = 16</td>
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



<p>Definition at line 6127 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a91f4aecc323597d1fa23c01644950f45">copyOverflowArea</a>.</p>

</div>
</div>

### SystemZOverflowOffset {#a69a54dd62aa091a615c4d850d0372c51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{MemorySanitizer.cpp}::VarArgSystemZHelper::SystemZOverflowOffset = 160</td>
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



<p>Definition at line 6125 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a91f4aecc323597d1fa23c01644950f45">copyOverflowArea</a>, <a href="#aeff71653a760718fea2a9b166f8df1b4">finalizeInstrumentation</a> and <a href="#af0bc023f29f779469e5e8e3f92b9db0f">visitCallBase</a>.</p>

</div>
</div>

### SystemZRegSaveAreaPtrOffset {#a09688e5a25f0cecec43287360c897501}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{MemorySanitizer.cpp}::VarArgSystemZHelper::SystemZRegSaveAreaPtrOffset = 24</td>
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



<p>Definition at line 6128 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a831a9764856351a89b415e39b0557d06">copyRegSaveArea</a>.</p>

</div>
</div>

### SystemZRegSaveAreaSize {#ab8b9c78abe59bfab0b87c5d9c2e2fc7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{MemorySanitizer.cpp}::VarArgSystemZHelper::SystemZRegSaveAreaSize = 160</td>
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



<p>Definition at line 6124 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a831a9764856351a89b415e39b0557d06">copyRegSaveArea</a>.</p>

</div>
</div>

### SystemZVAListTagSize {#a4c2bd17808c0303e7a2724883b78ec04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{MemorySanitizer.cpp}::VarArgSystemZHelper::SystemZVAListTagSize = 32</td>
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



<p>Definition at line 6126 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a20caa6e1947b3736ad8ff941dc4d6dff">VarArgSystemZHelper</a>.</p>

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
