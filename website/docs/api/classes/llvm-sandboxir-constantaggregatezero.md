---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sandboxir/constantaggregatezero
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ConstantAggregateZero` Class



## Declaration

<div class="doxyDeclaration">
class llvm::sandboxir::ConstantAggregateZero { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">llvm/SandboxIR/Constant.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant">Constant</a></td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a></td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a885f2f256d42950c2daffb866ff9a0ff">ConstantAggregateZero</a> (llvm::ConstantAggregateZero *C, Context &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49c1a042d7191adffd285d8e763169ff">getSequentialElement</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this CAZ has array or vector type, return a zero with the right element type. <a href="#a49c1a042d7191adffd285d8e763169ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a800d9894402db8885f0a5c3c274c1002">getStructElement</a> (unsigned Elt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this CAZ has struct type, return a zero with the right element type for the specified element. <a href="#a800d9894402db8885f0a5c3c274c1002">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5ee9034a6c41042c742b5674dbebac3">getElementValue</a> (Constant *C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a zero of the right value for the specified GEP index if we can, otherwise return null (e.g. <a href="#ab5ee9034a6c41042c742b5674dbebac3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e11290cf6eea82cf401adcf53724c36">getElementValue</a> (unsigned Idx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a zero of the right value for the specified GEP index. <a href="#a2e11290cf6eea82cf401adcf53724c36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a199438d671ec3c302c5539666f422651">getElementCount</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of elements in the array, vector, or struct. <a href="#a199438d671ec3c302c5539666f422651">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ed4e2ecb55b50a61450a3a44f33fee3">getUseOperandNo</a> (const Use &amp;Use) const final</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns the operand index of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/use">Use</a></span>. <a href="#a1ed4e2ecb55b50a61450a3a44f33fee3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ed61ba0739e353de9c17915f79541c6">verify</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Should crash if there is something wrong with the instruction. <a href="#a6ed61ba0739e353de9c17915f79541c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac160aa25e33ee624357efaa86e3fdb6e">dumpOS</a> (raw_ostream &amp;OS) const override</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantaggregatezero">ConstantAggregateZero</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09c96c69df3622356393568825d39227">get</a> (Type *Ty)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a202e7cbfd81f72582bdfa1ed465fd664">classof</a> (const sandboxir::Value *From)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For isa/dyn_cast. <a href="#a202e7cbfd81f72582bdfa1ed465fd664">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a>.</p>


<div class="doxySectionDef">

## Friends

### Context {#ac26c806e60ca4a0547680edb68f6e39b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant/#a79434ebb02d4852eb1e8ca58342c1724">llvm::sandboxir::Constant::Constant</a> and <a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a>.</p>


<p>Referenced by <a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### ConstantAggregateZero() {#a885f2f256d42950c2daffb866ff9a0ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::ConstantAggregateZero::ConstantAggregateZero (<a href="/web-llvm/docs/api/classes/llvm/constantaggregatezero">llvm::ConstantAggregateZero</a> * C, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> &amp; Ctx)</td>
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



<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dumpOS() {#ac160aa25e33ee624357efaa86e3fdb6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::ConstantAggregateZero::dumpOS (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 470 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#ac886f508d3441b842e387f062899f3a8">llvm::sandboxir::Value::dumpCommonPrefix</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a294250e6721c14a9a8d934220e6523d0">llvm::sandboxir::Value::dumpCommonSuffix</a>.</p>

</div>
</div>

### getElementCount() {#a199438d671ec3c302c5539666f422651}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ElementCount llvm::sandboxir::ConstantAggregateZero::getElementCount ()</td>
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

<p>Return the number of elements in the array, vector, or struct.</p>

<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### getElementValue() {#ab5ee9034a6c41042c742b5674dbebac3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * llvm::sandboxir::ConstantAggregateZero::getElementValue (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant">Constant</a> * C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a zero of the right value for the specified GEP index if we can, otherwise return null (e.g.</p>


<p>if C is a <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantexpr">ConstantExpr</a>).</p>


<p>Declaration at line 451 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a>, definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/constant-cpp">Constant.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant/#a79434ebb02d4852eb1e8ca58342c1724">llvm::sandboxir::Constant::Constant</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a4705ee51ec0da1ba978f2353d2c47f27">llvm::sandboxir::Value::Ctx</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### getElementValue() {#a2e11290cf6eea82cf401adcf53724c36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * llvm::sandboxir::ConstantAggregateZero::getElementValue (unsigned Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a zero of the right value for the specified GEP index.</p>

<p>Declaration at line 453 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a>, definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/constant-cpp">Constant.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant/#a79434ebb02d4852eb1e8ca58342c1724">llvm::sandboxir::Constant::Constant</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a4705ee51ec0da1ba978f2353d2c47f27">llvm::sandboxir::Value::Ctx</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### getSequentialElement() {#a49c1a042d7191adffd285d8e763169ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * llvm::sandboxir::ConstantAggregateZero::getSequentialElement ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this CAZ has array or vector type, return a zero with the right element type.</p>

<p>Declaration at line 445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a>, definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/constant-cpp">Constant.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant/#a79434ebb02d4852eb1e8ca58342c1724">llvm::sandboxir::Constant::Constant</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a4705ee51ec0da1ba978f2353d2c47f27">llvm::sandboxir::Value::Ctx</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### getStructElement() {#a800d9894402db8885f0a5c3c274c1002}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * llvm::sandboxir::ConstantAggregateZero::getStructElement (unsigned Elt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this CAZ has struct type, return a zero with the right element type for the specified element.</p>

<p>Declaration at line 448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a>, definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/constant-cpp">Constant.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant/#a79434ebb02d4852eb1e8ca58342c1724">llvm::sandboxir::Constant::Constant</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a4705ee51ec0da1ba978f2353d2c47f27">llvm::sandboxir::Value::Ctx</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### getUseOperandNo() {#a1ed4e2ecb55b50a61450a3a44f33fee3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sandboxir::ConstantAggregateZero::getUseOperandNo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/use">Use</a> &amp; Use)</td>
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

<p>\Returns the operand index of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/use">Use</a></span>.</p>

<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### verify() {#a6ed61ba0739e353de9c17915f79541c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::ConstantAggregateZero::verify ()</td>
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

<p>Should crash if there is something wrong with the instruction.</p>

<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a202e7cbfd81f72582bdfa1ed465fd664}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ConstantAggregateZero::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">sandboxir::Value</a> * From)</td>
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

<p>For isa/dyn_cast.</p>

<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a27b9af008c6420f3340805e50297f9fb">llvm::sandboxir::Value::getSubclassID</a>.</p>

</div>
</div>

### get() {#a09c96c69df3622356393568825d39227}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantAggregateZero * llvm::sandboxir::ConstantAggregateZero::get (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a> * Ty)</td>
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



<p>Declaration at line 442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a>, definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/constant-cpp">Constant.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/constantaggregatezero/#abfa1cf8b4348407b167f93bc7c01055f">llvm::ConstantAggregateZero::get</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/constant-cpp">Constant.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
