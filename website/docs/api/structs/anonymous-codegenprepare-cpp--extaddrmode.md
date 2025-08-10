---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-codegenprepare-cpp-/extaddrmode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ExtAddrMode` Struct

<p>This is an extended version of TargetLowering::AddrMode which holds actual Value*'s for register values. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{CodeGenPrepare.cpp}::ExtAddrMode { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TargetLowering::AddrMode</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">FieldName { <a href="#a10aef7c4018bbcd7beefca2dcf4e3c3b">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a3bb1311f93a6e5c6db14f9d524f3bb">ExtAddrMode</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13013613b2600aea6438d155a7e4c21b">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af97ad85fa4c9caf49c807470d137a67d">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcc64bfd52afa9a6094a07cc91922630">replaceWith</a> (Value *From, Value *To)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a10aef7c4018bbcd7beefca2dcf4e3c3b">FieldName</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cd7231f32d51864a9e307330e798de9">compare</a> (const ExtAddrMode &amp;other)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af16961a6894c56bc7f08641a2538167d">isTrivial</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98c66d9b5e8ace6575527d88e08fe378">GetFieldAsValue</a> (FieldName Field, Type *IntPtrTy)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af313a30da49e08d08e305c3e72b32619">SetCombinedField</a> (FieldName Field, Value *V, const SmallVectorImpl&lt; ExtAddrMode &gt; &amp;AddrModes)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac35a3a2b34882507f52796fb2b377838">BaseReg</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3efdd9ffd185b09958bdb0f6697c3eb">ScaledReg</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb3608f4d5ddc7a177772e1dbb17f96f">OriginalValue</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e6c6948fceb393f324cbfb318c0b64e">InBounds</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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

<p>This is an extended version of TargetLowering::AddrMode which holds actual Value*'s for register values.</p>

<p>Definition at line 3056 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### FieldName {#a10aef7c4018bbcd7beefca2dcf4e3c3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{CodeGenPrepare.cpp}::ExtAddrMode::FieldName </td>
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
<td class="doxyEnumItemName">NoField<a id="a10aef7c4018bbcd7beefca2dcf4e3c3bade3fdafc2a520488937de65060546976"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BaseRegField<a id="a10aef7c4018bbcd7beefca2dcf4e3c3bafbb3f111d9869fde071cbdd50c50fd9e"></a></td>
<td class="doxyEnumItemDescription"> (= 0x01)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BaseGVField<a id="a10aef7c4018bbcd7beefca2dcf4e3c3baf4d9622b8e7495cb65099c1333085a24"></a></td>
<td class="doxyEnumItemDescription"> (= 0x02)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BaseOffsField<a id="a10aef7c4018bbcd7beefca2dcf4e3c3ba00291a866d6acfad336e7606f1c17c92"></a></td>
<td class="doxyEnumItemDescription"> (= 0x04)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ScaledRegField<a id="a10aef7c4018bbcd7beefca2dcf4e3c3ba1b3ebdf8bae0e1f7aad691b016c5a178"></a></td>
<td class="doxyEnumItemDescription"> (= 0x08)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ScaleField<a id="a10aef7c4018bbcd7beefca2dcf4e3c3bad9eaab024b6516aae7cd2912a8ed4101"></a></td>
<td class="doxyEnumItemDescription"> (= 0x10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MultipleFields<a id="a10aef7c4018bbcd7beefca2dcf4e3c3ba487a1fc3c02e9df7cb63a01968499611"></a></td>
<td class="doxyEnumItemDescription"> (= 0xff)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 3062 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ExtAddrMode() {#a2a3bb1311f93a6e5c6db14f9d524f3bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CodeGenPrepare.cpp}::ExtAddrMode::ExtAddrMode ()</td>
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



<p>Definition at line 3072 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>Referenced by <a href="#a0cd7231f32d51864a9e307330e798de9">compare</a> and <a href="#af313a30da49e08d08e305c3e72b32619">SetCombinedField</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### compare() {#a0cd7231f32d51864a9e307330e798de9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FieldName anonymous{CodeGenPrepare.cpp}::ExtAddrMode::compare (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-codegenprepare-cpp-/extaddrmode">ExtAddrMode</a> &amp; other)</td>
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



<p>Definition at line 3085 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="#a10aef7c4018bbcd7beefca2dcf4e3c3baf4d9622b8e7495cb65099c1333085a24">BaseGVField</a>, <a href="#a10aef7c4018bbcd7beefca2dcf4e3c3ba00291a866d6acfad336e7606f1c17c92">BaseOffsField</a>, <a href="#ac35a3a2b34882507f52796fb2b377838">BaseReg</a>, <a href="#a10aef7c4018bbcd7beefca2dcf4e3c3bafbb3f111d9869fde071cbdd50c50fd9e">BaseRegField</a>, <a href="#a2a3bb1311f93a6e5c6db14f9d524f3bb">ExtAddrMode</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a9e6c6948fceb393f324cbfb318c0b64e">InBounds</a>, <a href="#a10aef7c4018bbcd7beefca2dcf4e3c3ba487a1fc3c02e9df7cb63a01968499611">MultipleFields</a>, <a href="#a10aef7c4018bbcd7beefca2dcf4e3c3bade3fdafc2a520488937de65060546976">NoField</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0eea77e7bfa82e0219d2ec7b4efbc94f">llvm::popcount</a>, <a href="/web-llvm/docs/api/structs/llvm/extaddrmode/#ae20bc007be03337ee451abb60d74260b">llvm::ExtAddrMode::Scale</a>, <a href="#ab3efdd9ffd185b09958bdb0f6697c3eb">ScaledReg</a>, <a href="#a10aef7c4018bbcd7beefca2dcf4e3c3ba1b3ebdf8bae0e1f7aad691b016c5a178">ScaledRegField</a> and <a href="#a10aef7c4018bbcd7beefca2dcf4e3c3bad9eaab024b6516aae7cd2912a8ed4101">ScaleField</a>.</p>

</div>
</div>

### dump() {#af97ad85fa4c9caf49c807470d137a67d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void anonymous{CodeGenPrepare.cpp}::ExtAddrMode::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3075 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a50bf746ca1858c0e272e3a802fc27942">llvm::print</a>.</p>

</div>
</div>

### GetFieldAsValue() {#a98c66d9b5e8ace6575527d88e08fe378}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{CodeGenPrepare.cpp}::ExtAddrMode::GetFieldAsValue (<a href="#a10aef7c4018bbcd7beefca2dcf4e3c3b">FieldName</a> Field, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * IntPtrTy)</td>
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



<p>Definition at line 3132 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="#a10aef7c4018bbcd7beefca2dcf4e3c3baf4d9622b8e7495cb65099c1333085a24">BaseGVField</a>, <a href="#a10aef7c4018bbcd7beefca2dcf4e3c3ba00291a866d6acfad336e7606f1c17c92">BaseOffsField</a>, <a href="#ac35a3a2b34882507f52796fb2b377838">BaseReg</a>, <a href="#a10aef7c4018bbcd7beefca2dcf4e3c3bafbb3f111d9869fde071cbdd50c50fd9e">BaseRegField</a>, <a href="#ab3efdd9ffd185b09958bdb0f6697c3eb">ScaledReg</a> and <a href="#a10aef7c4018bbcd7beefca2dcf4e3c3ba1b3ebdf8bae0e1f7aad691b016c5a178">ScaledRegField</a>.</p>

</div>
</div>

### isTrivial() {#af16961a6894c56bc7f08641a2538167d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CodeGenPrepare.cpp}::ExtAddrMode::isTrivial ()</td>
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



<p>Definition at line 3124 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="#ac35a3a2b34882507f52796fb2b377838">BaseReg</a> and <a href="/web-llvm/docs/api/structs/llvm/extaddrmode/#ae20bc007be03337ee451abb60d74260b">llvm::ExtAddrMode::Scale</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/addressingmodecombiner/#a68677e52356488f3516d001f127588a5">anonymous{CodeGenPrepare.cpp}::AddressingModeCombiner::addNewAddrMode</a>.</p>

</div>
</div>

### print() {#a13013613b2600aea6438d155a7e4c21b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CodeGenPrepare.cpp}::ExtAddrMode::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3074 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="#ac35a3a2b34882507f52796fb2b377838">BaseReg</a>, <a href="#a9e6c6948fceb393f324cbfb318c0b64e">InBounds</a>, <a href="/web-llvm/docs/api/structs/llvm/extaddrmode/#ae20bc007be03337ee451abb60d74260b">llvm::ExtAddrMode::Scale</a> and <a href="#ab3efdd9ffd185b09958bdb0f6697c3eb">ScaledReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-codegenprepare-cpp-/#ab24147fe07c79ebc39df89376d939778">anonymous{CodeGenPrepare.cpp}::operator&lt;&lt;</a>.</p>

</div>
</div>

### replaceWith() {#afcc64bfd52afa9a6094a07cc91922630}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CodeGenPrepare.cpp}::ExtAddrMode::replaceWith (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * From, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * To)</td>
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



<p>Definition at line 3080 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>Reference <a href="#ab3efdd9ffd185b09958bdb0f6697c3eb">ScaledReg</a>.</p>

</div>
</div>

### SetCombinedField() {#af313a30da49e08d08e305c3e72b32619}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CodeGenPrepare.cpp}::ExtAddrMode::SetCombinedField (<a href="#a10aef7c4018bbcd7beefca2dcf4e3c3b">FieldName</a> Field, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-codegenprepare-cpp-/extaddrmode">ExtAddrMode</a> &gt; &amp; AddrModes)</td>
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



<p>Definition at line 3147 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a10aef7c4018bbcd7beefca2dcf4e3c3baf4d9622b8e7495cb65099c1333085a24">BaseGVField</a>, <a href="#a10aef7c4018bbcd7beefca2dcf4e3c3ba00291a866d6acfad336e7606f1c17c92">BaseOffsField</a>, <a href="#ac35a3a2b34882507f52796fb2b377838">BaseReg</a>, <a href="#a10aef7c4018bbcd7beefca2dcf4e3c3bafbb3f111d9869fde071cbdd50c50fd9e">BaseRegField</a>, <a href="#a2a3bb1311f93a6e5c6db14f9d524f3bb">ExtAddrMode</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/extaddrmode/#ae20bc007be03337ee451abb60d74260b">llvm::ExtAddrMode::Scale</a>, <a href="#ab3efdd9ffd185b09958bdb0f6697c3eb">ScaledReg</a> and <a href="#a10aef7c4018bbcd7beefca2dcf4e3c3ba1b3ebdf8bae0e1f7aad691b016c5a178">ScaledRegField</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BaseReg {#ac35a3a2b34882507f52796fb2b377838}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* anonymous{CodeGenPrepare.cpp}::ExtAddrMode::BaseReg = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3057 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>Referenced by <a href="#a0cd7231f32d51864a9e307330e798de9">compare</a>, <a href="#a98c66d9b5e8ace6575527d88e08fe378">GetFieldAsValue</a>, <a href="#af16961a6894c56bc7f08641a2538167d">isTrivial</a>, <a href="#a13013613b2600aea6438d155a7e4c21b">print</a> and <a href="#af313a30da49e08d08e305c3e72b32619">SetCombinedField</a>.</p>

</div>
</div>

### InBounds {#a9e6c6948fceb393f324cbfb318c0b64e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CodeGenPrepare.cpp}::ExtAddrMode::InBounds = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3060 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>Referenced by <a href="#a0cd7231f32d51864a9e307330e798de9">compare</a> and <a href="#a13013613b2600aea6438d155a7e4c21b">print</a>.</p>

</div>
</div>

### OriginalValue {#afb3608f4d5ddc7a177772e1dbb17f96f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* anonymous{CodeGenPrepare.cpp}::ExtAddrMode::OriginalValue = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3059 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### ScaledReg {#ab3efdd9ffd185b09958bdb0f6697c3eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* anonymous{CodeGenPrepare.cpp}::ExtAddrMode::ScaledReg = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3058 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/addressingmodecombiner/#a68677e52356488f3516d001f127588a5">anonymous{CodeGenPrepare.cpp}::AddressingModeCombiner::addNewAddrMode</a>, <a href="#a0cd7231f32d51864a9e307330e798de9">compare</a>, <a href="#a98c66d9b5e8ace6575527d88e08fe378">GetFieldAsValue</a>, <a href="#a13013613b2600aea6438d155a7e4c21b">print</a>, <a href="#afcc64bfd52afa9a6094a07cc91922630">replaceWith</a> and <a href="#af313a30da49e08d08e305c3e72b32619">SetCombinedField</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
