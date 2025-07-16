---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/msp430isd
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `MSP430ISD` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::MSP430ISD { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">NodeType : unsigned { <a href="#ae7d266ee347b1114156d2e4e36b47f73">...</a> }</td>
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

### NodeType {#ae7d266ee347b1114156d2e4e36b47f73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MSP430ISD::NodeType : unsigned</td>
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
<td class="doxyEnumItemName">FIRST_NUMBER<a id="ae7d266ee347b1114156d2e4e36b47f73ae5d1a9d2fbc06f7d50789644585d145e"></a></td>
<td class="doxyEnumItemDescription"> (= ISD::BUILTIN_OP_END)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RET_GLUE<a id="ae7d266ee347b1114156d2e4e36b47f73ad6830e31fbcc96ab7a97c9c24f45f610"></a></td>
<td class="doxyEnumItemDescription">Return with a glue operand. Operand 0 is the chain operand</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RETI_GLUE<a id="ae7d266ee347b1114156d2e4e36b47f73aa10d97df284584fccd16bb6e5726bfef"></a></td>
<td class="doxyEnumItemDescription">Same as RET_GLUE, but used for returning from ISRs</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RRA<a id="ae7d266ee347b1114156d2e4e36b47f73a1a8aac0ab3dd9efd41309a89185be1b8"></a></td>
<td class="doxyEnumItemDescription">Y = R{R,L}A X, rotate right (left) arithmetically</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RLA<a id="ae7d266ee347b1114156d2e4e36b47f73adfd55b32c5ff0b26a6e10e15fbe0f267"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RRC<a id="ae7d266ee347b1114156d2e4e36b47f73abfaa29bfc6391f3ab04d0728ec65f26c"></a></td>
<td class="doxyEnumItemDescription">Y = RRC X, rotate right via carry</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RRCL<a id="ae7d266ee347b1114156d2e4e36b47f73a5abb0ecf62c9698e84f95292eff99ccf"></a></td>
<td class="doxyEnumItemDescription">Rotate right via carry, carry gets cleared beforehand by clrc</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALL<a id="ae7d266ee347b1114156d2e4e36b47f73a1a745df8676b5173925ea7bbc61b7151"></a></td>
<td class="doxyEnumItemDescription">CALL - These operations represent an abstract call instruction, which includes a bunch of information</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Wrapper<a id="ae7d266ee347b1114156d2e4e36b47f73acec80506eab90924a64f136e0dbfd266"></a></td>
<td class="doxyEnumItemDescription">Wrapper - A wrapper node for TargetConstantPool, TargetExternalSymbol, and TargetGlobalAddress</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMP<a id="ae7d266ee347b1114156d2e4e36b47f73abe1f71803e38f141a54883c9e5677d26"></a></td>
<td class="doxyEnumItemDescription">CMP - Compare instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETCC<a id="ae7d266ee347b1114156d2e4e36b47f73a36303f15bb799b26a32ce381047c7406"></a></td>
<td class="doxyEnumItemDescription">SetCC - Operand 0 is condition code, and operand 1 is the flag operand produced by a CMP instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BR_CC<a id="ae7d266ee347b1114156d2e4e36b47f73a33618f9677136fd47b1fc1e8743afd02"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/msp430">MSP430</a> conditional branches</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SELECT_CC<a id="ae7d266ee347b1114156d2e4e36b47f73aa5969079c845c62591838db9c999c723"></a></td>
<td class="doxyEnumItemDescription">SELECT_CC - Operand 0 and operand 1 are selection variable, operand 3 is condition code and operand 4 is flag operand</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DADD<a id="ae7d266ee347b1114156d2e4e36b47f73a347437d9881883baffd9fca8603992fd"></a></td>
<td class="doxyEnumItemDescription">DADD - Decimal addition with carry TODO Nothing generates a node of this type yet</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/msp430isellowering-h">MSP430ISelLowering.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/msp430isellowering-h">MSP430ISelLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
