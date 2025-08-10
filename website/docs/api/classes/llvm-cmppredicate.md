---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/cmppredicate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CmpPredicate` Class

<p>An abstraction over a floating-point predicate, and a pack of an integer predicate with samesign information. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::CmpPredicate { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/cmppredicate-h">llvm/IR/CmpPredicate.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6157d624270f83ee25470e877469dbe2">CmpPredicate</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default constructor. <a href="#a6157d624270f83ee25470e877469dbe2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73f832a07263966ceb3958de221d25a0">CmpPredicate</a> (CmpInst::Predicate Pred, bool HasSameSign=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructed implictly with a either <a href="/web-llvm/docs/api/classes/predicate">Predicate</a> and samesign information, or just a <a href="/web-llvm/docs/api/classes/predicate">Predicate</a>, dropping samesign information. <a href="#a73f832a07263966ceb3958de221d25a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed941546524e1984490394a106a327d2">operator CmpInst::Predicate</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implictly converts to the underlying <a href="/web-llvm/docs/api/classes/predicate">Predicate</a>, dropping samesign information. <a href="#aed941546524e1984490394a106a327d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f2cdd14e196502b8ccb86d1dc00b24a">operator==</a> (CmpInst::Predicate P) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An operator== on the underlying <a href="/web-llvm/docs/api/classes/predicate">Predicate</a>. <a href="#a6f2cdd14e196502b8ccb86d1dc00b24a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdac8e4977b833701fc38316c2d099fb">operator!=</a> (CmpInst::Predicate P) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a615a04b1da897993fefc2748001295d2">operator==</a> (CmpPredicate) const =delete</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>There is no operator== defined on <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a>. <a href="#a615a04b1da897993fefc2748001295d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8a8ff1847e2c6d32b7eae4309b56c2">operator!=</a> (CmpPredicate) const =delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac07507cbb4db8cb0af59271f433d5d0a">hasSameSign</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Query samesign information, for optimizations. <a href="#ac07507cbb4db8cb0af59271f433d5d0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b25351cc1e7cf7fde5d97eadffad546">getPreferredSignedPredicate</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempts to return a signed <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> from the <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a>. <a href="#a6b25351cc1e7cf7fde5d97eadffad546">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abed98e63a26a44ae192ee9a48f5e1666">Pred</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d57c5c966c6102d1028eaf63e989868">HasSameSign</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c29fdc79aad7e92c7f850bbd0faa208">getMatching</a> (CmpPredicate A, CmpPredicate B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compares two CmpPredicates taking samesign into account and returns the canonicalized <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> if they match. <a href="#a1c29fdc79aad7e92c7f850bbd0faa208">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68d75142cb41d5119af994e4e71c451d">get</a> (const CmpInst *Cmp)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Do a <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a36f67a81e2a4449854771f4e64efe60a">ICmpInst::getCmpPredicate()</a> or <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa7414ba9f658ff1287d22a4b8fe81bcb">CmpInst::getPredicate()</a>, as appropriate. <a href="#a68d75142cb41d5119af994e4e71c451d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad155f02dd1653e10da9e766a5c0a90c7">getSwapped</a> (CmpPredicate P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the swapped predicate of a <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a>. <a href="#ad155f02dd1653e10da9e766a5c0a90c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f157c7b109fc6543a9a60421898f373">getSwapped</a> (const CmpInst *Cmp)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the swapped predicate of a <a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a>. <a href="#a3f157c7b109fc6543a9a60421898f373">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>An abstraction over a floating-point predicate, and a pack of an integer predicate with samesign information.</p>


<p>Some functions in <a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> construct and return this type in place of a <a href="/web-llvm/docs/api/classes/predicate">Predicate</a>.</p>


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/cmppredicate-h">CmpPredicate.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CmpPredicate() {#a6157d624270f83ee25470e877469dbe2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CmpPredicate::CmpPredicate ()</td>
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

<p>Default constructor.</p>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/cmppredicate-h">CmpPredicate.h</a>.</p>


<p>Referenced by <a href="#a68d75142cb41d5119af994e4e71c451d">get</a>, <a href="#a1c29fdc79aad7e92c7f850bbd0faa208">getMatching</a>, <a href="#ad155f02dd1653e10da9e766a5c0a90c7">getSwapped</a>, <a href="#a3f157c7b109fc6543a9a60421898f373">getSwapped</a>, <a href="#a9c8a8ff1847e2c6d32b7eae4309b56c2">operator!=</a> and <a href="#a615a04b1da897993fefc2748001295d2">operator==</a>.</p>

</div>
</div>

### CmpPredicate() {#a73f832a07263966ceb3958de221d25a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CmpPredicate::CmpPredicate (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> Pred, bool HasSameSign=false)</td>
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

<p>Constructed implictly with a either <a href="/web-llvm/docs/api/classes/predicate">Predicate</a> and samesign information, or just a <a href="/web-llvm/docs/api/classes/predicate">Predicate</a>, dropping samesign information.</p>

<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/cmppredicate-h">CmpPredicate.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#ad8c2100cae3093d71e65a48908158e22">llvm::CmpInst::isIntPredicate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator CmpInst::Predicate() {#aed941546524e1984490394a106a327d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CmpPredicate::operator CmpInst::Predicate ()</td>
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

<p>Implictly converts to the underlying <a href="/web-llvm/docs/api/classes/predicate">Predicate</a>, dropping samesign information.</p>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/cmppredicate-h">CmpPredicate.h</a>.</p>

</div>
</div>

### operator!=() {#acdac8e4977b833701fc38316c2d099fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CmpPredicate::operator!= (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> P)</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/cmppredicate-h">CmpPredicate.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### operator!=() {#a9c8a8ff1847e2c6d32b7eae4309b56c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CmpPredicate::operator!= (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/cmppredicate-h">CmpPredicate.h</a>.</p>


<p>References <a href="#a6157d624270f83ee25470e877469dbe2">CmpPredicate</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### operator==() {#a6f2cdd14e196502b8ccb86d1dc00b24a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CmpPredicate::operator== (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> P)</td>
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

<p>An operator== on the underlying <a href="/web-llvm/docs/api/classes/predicate">Predicate</a>.</p>

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/cmppredicate-h">CmpPredicate.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### operator==() {#a615a04b1da897993fefc2748001295d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CmpPredicate::operator== (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>There is no operator== defined on <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a>.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> getMatching instead to get the canonicalized matching <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a>.</p>


<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/cmppredicate-h">CmpPredicate.h</a>.</p>


<p>Reference <a href="#a6157d624270f83ee25470e877469dbe2">CmpPredicate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getPreferredSignedPredicate() {#a6b25351cc1e7cf7fde5d97eadffad546}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CmpInst::Predicate CmpPredicate::getPreferredSignedPredicate ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempts to return a signed <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> from the <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a>.</p>


<p>If the <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> has samesign, return <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a9d5f70171d811078c4d263811f13c121">ICmpInst::getSignedPredicate</a>, dropping samesign information. Otherwise, return the predicate, dropping samesign information.</p>


<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/cmppredicate-h">CmpPredicate.h</a>, definition at line 3953 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a9d5f70171d811078c4d263811f13c121">llvm::ICmpInst::getSignedPredicate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a650658d91a5b32920521b0f2120af053">isImpliedCondICmps</a>.</p>

</div>
</div>

### hasSameSign() {#ac07507cbb4db8cb0af59271f433d5d0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CmpPredicate::hasSameSign ()</td>
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

<p>Query samesign information, for optimizations.</p>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/cmppredicate-h">CmpPredicate.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a4f30233ac0c825f0a38b55470569d7b7">isImpliedCondCommonOperandWithCR</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#ac2b8ad8da7580efe927ce83c1be4ddd5">isImpliedTrueByMatchingCmp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### HasSameSign {#a4d57c5c966c6102d1028eaf63e989868}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CmpPredicate::HasSameSign</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/cmppredicate-h">CmpPredicate.h</a>.</p>

</div>
</div>

### Pred {#abed98e63a26a44ae192ee9a48f5e1666}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CmpInst::Predicate llvm::CmpPredicate::Pred</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/cmppredicate-h">CmpPredicate.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### get() {#a68d75142cb41d5119af994e4e71c451d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CmpPredicate CmpPredicate::get (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a> * Cmp)</td>
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

<p>Do a <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a36f67a81e2a4449854771f4e64efe60a">ICmpInst::getCmpPredicate()</a> or <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa7414ba9f658ff1287d22a4b8fe81bcb">CmpInst::getPredicate()</a>, as appropriate.</p>

<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/cmppredicate-h">CmpPredicate.h</a>, definition at line 3957 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a6157d624270f83ee25470e877469dbe2">CmpPredicate</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="#a3f157c7b109fc6543a9a60421898f373">getSwapped</a>, <a href="/web-llvm/docs/api/structs/llvm/patternmatch/cmpclass-match/#a1fceeb78aaeef3d5d59989489d5a31ac">llvm::PatternMatch::CmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::match</a> and <a href="/web-llvm/docs/api/structs/llvm/patternmatch/specificcmpclass-match/#abdf52120ea04ad8f64878bf7f4e96069">llvm::PatternMatch::SpecificCmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::match</a>.</p>

</div>
</div>

### getMatching() {#a1c29fdc79aad7e92c7f850bbd0faa208}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; CmpPredicate &gt; CmpPredicate::getMatching (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> A, <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> B)</td>
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

<p>Compares two CmpPredicates taking samesign into account and returns the canonicalized <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> if they match.</p>


<p>An alternative to operator==.</p>


<p>For example, samesign ult + samesign ult -&gt; samesign ult samesign ult + ult -&gt; ult samesign ult + slt -&gt; slt ult + ult -&gt; ult ult + slt -&gt; std::nullopt</p>


<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/cmppredicate-h">CmpPredicate.h</a>, definition at line 3938 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a6157d624270f83ee25470e877469dbe2">CmpPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#aab5ed5a6c201467c29ee9de89f80314a">llvm::ICmpInst::getFlippedSignednessPredicate</a> and <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a66c10680694a0184d50e7a8c0d1ea874">llvm::CmpInst::isFPPredicate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bd29d381405675f36964e4a5382dae4">llvm::InstCombinerImpl::foldSelectOpOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a1f669cc640bda295e6c2e2b3c90babb9">hoistMinMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a650658d91a5b32920521b0f2120af053">isImpliedCondICmps</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#ac2b8ad8da7580efe927ce83c1be4ddd5">isImpliedTrueByMatchingCmp</a> and <a href="/web-llvm/docs/api/structs/llvm/patternmatch/specificcmpclass-match/#abdf52120ea04ad8f64878bf7f4e96069">llvm::PatternMatch::SpecificCmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::match</a>.</p>

</div>
</div>

### getSwapped() {#ad155f02dd1653e10da9e766a5c0a90c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CmpPredicate CmpPredicate::getSwapped (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> P)</td>
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

<p>Get the swapped predicate of a <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a>.</p>

<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/cmppredicate-h">CmpPredicate.h</a>, definition at line 3963 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a6157d624270f83ee25470e877469dbe2">CmpPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="#a3f157c7b109fc6543a9a60421898f373">getSwapped</a>, <a href="/web-llvm/docs/api/structs/llvm/patternmatch/cmpclass-match/#a1fceeb78aaeef3d5d59989489d5a31ac">llvm::PatternMatch::CmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::match</a> and <a href="/web-llvm/docs/api/structs/llvm/patternmatch/specificcmpclass-match/#abdf52120ea04ad8f64878bf7f4e96069">llvm::PatternMatch::SpecificCmpClass_match&lt; LHS_t, RHS_t, Class, Commutable &gt;::match</a>.</p>

</div>
</div>

### getSwapped() {#a3f157c7b109fc6543a9a60421898f373}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CmpPredicate CmpPredicate::getSwapped (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a> * Cmp)</td>
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

<p>Get the swapped predicate of a <a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a>.</p>

<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/cmppredicate-h">CmpPredicate.h</a>, definition at line 3967 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a6157d624270f83ee25470e877469dbe2">CmpPredicate</a>, <a href="#a68d75142cb41d5119af994e4e71c451d">get</a> and <a href="#ad155f02dd1653e10da9e766a5c0a90c7">getSwapped</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/cmppredicate-h">CmpPredicate.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
