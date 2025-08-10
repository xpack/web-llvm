---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/valuelatticeelement
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ValueLatticeElement` Class

<p>This class represents lattice values for constants. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ValueLatticeElement { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">llvm/Analysis/ValueLattice.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ValueLatticeElementTy { <a href="#a2016050bbc67219751cea3c3a7029434">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee232a2f47e3b90163a98f12646b946a">ValueLatticeElement</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31bedc80bed78ed13dcdd5db2ebdf74f">ValueLatticeElement</a> (const ValueLatticeElement &amp;Other)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61deeffde48042616233f2498eca42ae">ValueLatticeElement</a> (ValueLatticeElement &amp;&amp;Other)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2be49373b43826bbaf1a3cd8b6277a05">~ValueLatticeElement</a> ()</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement">ValueLatticeElement</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a557dcfc1d84079276e50fedd106696f9">operator=</a> (const ValueLatticeElement &amp;Other)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement">ValueLatticeElement</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9691c32880d7ab39512a94d9530ae78">operator=</a> (ValueLatticeElement &amp;&amp;Other)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04947cf0017de409235dadda5b662c4d">isUndef</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68d7fa33cb79b86841e367ef88c245f8">isUnknown</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab20e06908032fd7028c20c1d2d5a248a">isUnknownOrUndef</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62d37ceb318e78806df7e0a928b0eb1c">isConstant</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e15dd37f1b32b64bf9ff7c7ad03d70d">isNotConstant</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a2c134b14dc9616963c42ceebccc1c7">isConstantRangeIncludingUndef</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ab774f05d02e4bbe7817798cdf19186">isConstantRange</a> (bool UndefAllowed=true) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this value is a constant range. <a href="#a7ab774f05d02e4bbe7817798cdf19186">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a226c3252bd1261be2ff904697586f6d8">isOverdefined</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab79de6040b9a8bacd648c5916fb36cd9">getConstant</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a908b087596156c6a6c61275c49bece7d">getNotConstant</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73e8c58e4d729c42b5f27e3d847c54f8">getConstantRange</a> (bool UndefAllowed=true) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the constant range for this value. <a href="#a73e8c58e4d729c42b5f27e3d847c54f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a414095f3b62e33f0c3113205c44b65fd">asConstantInteger</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b5efcaf6d7833656101e9d19b00775f">asConstantRange</a> (unsigned BW, bool UndefAllowed=false) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5b8cb6678147066f4f3576c4550c386">asConstantRange</a> (Type *Ty, bool UndefAllowed=false) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d17cb6299d749c3e3b1860ea5545c08">markOverdefined</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab32f3bc397a5c669fb5c7320df6de2a7">markUndef</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcc7b385c19a2f07a57bf7351ce25d90">markConstant</a> (Constant *V, bool MayIncludeUndef=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15288f094b6ef51a8cade84175bb9993">markNotConstant</a> (Constant *V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbd26f64ed2e22a81bf690e93aa121a0">markConstantRange</a> (ConstantRange NewR, MergeOptions Opts=MergeOptions())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark the object as constant range with <span class="doxyComputerOutput">NewR</span>. <a href="#afbd26f64ed2e22a81bf690e93aa121a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aceaa5f442dd3df34f51799f2999d237e">mergeIn</a> (const ValueLatticeElement &amp;RHS, MergeOptions Opts=MergeOptions())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Updates this object to approximate both this object and RHS. <a href="#aceaa5f442dd3df34f51799f2999d237e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28425702df856e59142416e70fc6c43a">getCompare</a> (CmpInst::Predicate Pred, Type *Ty, const ValueLatticeElement &amp;Other, const DataLayout &amp;DL) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>true, false or undef constants, or nullptr if the comparison cannot be evaluated. <a href="#a28425702df856e59142416e70fc6c43a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement">ValueLatticeElement</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a975cd575019795ff8714252a22f27c26">intersect</a> (const ValueLatticeElement &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Combine two sets of facts about the same value into a single set of facts. <a href="#a975cd575019795ff8714252a22f27c26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8589b2fc437dff685d325713531f741d">getNumRangeExtensions</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64a82dcbacd27ff1996040ad31c9f36e">setNumRangeExtensions</a> (unsigned N)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a411241a4a0959d6981934d73d3690085">destroy</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Destroy contents of lattice value, without destructing the object. <a href="#a411241a4a0959d6981934d73d3690085">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7290ead3cbacbb12b762c8170e7bebc">ConstVal</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e4bbabfbc657ba3dc53158d93776bd7">Range</a></td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">ValueLatticeElementTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ba7449e3e0b42020f155a1439feb9af">Tag</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2832f021240693703fb0a7133c7ac5e">NumRangeExtensions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of times a constant range has been extended with widening enabled. <a href="#aa2832f021240693703fb0a7133c7ac5e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement">llvm::ValueLatticeElement</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50b4e339429703558421cc2e66a09cdd"></a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The union either stores a pointer to a constant or a constant range, associated to the lattice element. <a href="#a50b4e339429703558421cc2e66a09cdd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement">ValueLatticeElement</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a856d831b6862fb41fffecd00990bcc2c">get</a> (Constant *C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement">ValueLatticeElement</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3347382fc7040a7bc3ed0c7fcf6442c6">getNot</a> (Constant *C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement">ValueLatticeElement</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fa37f9808504c2a3d588ec0aa1532ac">getRange</a> (ConstantRange CR, bool MayIncludeUndef=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement">ValueLatticeElement</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa0befbad06a536ee25c232941a09856">getOverdefined</a> ()</td>
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

<p>This class represents lattice values for constants.</p>


<p>FIXME: This is basically just for bringup, this can be made a lot more rich in the future.</p>


<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### ValueLatticeElementTy {#a2016050bbc67219751cea3c3a7029434}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ValueLatticeElement::ValueLatticeElementTy </td>
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
<td class="doxyEnumItemName">unknown<a id="a2016050bbc67219751cea3c3a7029434aa0ac087e29c2cc6020055baf65e29303"></a></td>
<td class="doxyEnumItemDescription">This <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> has no known value yet</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">undef<a id="a2016050bbc67219751cea3c3a7029434af18061e2b5965aadb6eac8b2732fd8ea"></a></td>
<td class="doxyEnumItemDescription">This <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is an <a href="/web-llvm/docs/api/classes/llvm/undefvalue">UndefValue</a> constant or produces undef</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">constant<a id="a2016050bbc67219751cea3c3a7029434a14f6419cdef20574c66249a990ac99f1"></a></td>
<td class="doxyEnumItemDescription">This <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> has a specific constant value</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">notconstant<a id="a2016050bbc67219751cea3c3a7029434aa201a33487fa062d8cd615aa81beb442"></a></td>
<td class="doxyEnumItemDescription">This <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is known to not have the specified value</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">constantrange<a id="a2016050bbc67219751cea3c3a7029434ab29cd0c72da347e0569dd45581e17834"></a></td>
<td class="doxyEnumItemDescription">The <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> falls within this range</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">constantrange_including_undef<a id="a2016050bbc67219751cea3c3a7029434a73cfb84a2f173fabc28406d6b4f5b5ed"></a></td>
<td class="doxyEnumItemDescription">This <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> falls within this range, but also may be undef</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">overdefined<a id="a2016050bbc67219751cea3c3a7029434ad7904e4577e98ebfacaa783287d321e9"></a></td>
<td class="doxyEnumItemDescription">We can not precisely model the dynamic values this value might take</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ValueLatticeElement() {#aee232a2f47e3b90163a98f12646b946a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ValueLatticeElement::ValueLatticeElement ()</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>Referenced by <a href="#a856d831b6862fb41fffecd00990bcc2c">get</a>, <a href="#a28425702df856e59142416e70fc6c43a">getCompare</a>, <a href="#a3347382fc7040a7bc3ed0c7fcf6442c6">getNot</a>, <a href="#afa0befbad06a536ee25c232941a09856">getOverdefined</a>, <a href="#a1fa37f9808504c2a3d588ec0aa1532ac">getRange</a>, <a href="#a975cd575019795ff8714252a22f27c26">intersect</a>, <a href="#aceaa5f442dd3df34f51799f2999d237e">mergeIn</a>, <a href="#a557dcfc1d84079276e50fedd106696f9">operator=</a>, <a href="#ad9691c32880d7ab39512a94d9530ae78">operator=</a>, <a href="#a31bedc80bed78ed13dcdd5db2ebdf74f">ValueLatticeElement</a> and <a href="#a61deeffde48042616233f2498eca42ae">ValueLatticeElement</a>.</p>

</div>
</div>

### ValueLatticeElement() {#a31bedc80bed78ed13dcdd5db2ebdf74f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ValueLatticeElement::ValueLatticeElement (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement">ValueLatticeElement</a> &amp; Other)</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#aee232a2f47e3b90163a98f12646b946a">ValueLatticeElement</a>.</p>

</div>
</div>

### ValueLatticeElement() {#a61deeffde48042616233f2498eca42ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ValueLatticeElement::ValueLatticeElement (<a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement">ValueLatticeElement</a> &amp;&amp; Other)</td>
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



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#aee232a2f47e3b90163a98f12646b946a">ValueLatticeElement</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ValueLatticeElement() {#a2be49373b43826bbaf1a3cd8b6277a05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ValueLatticeElement::~ValueLatticeElement ()</td>
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



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a557dcfc1d84079276e50fedd106696f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueLatticeElement &amp; llvm::ValueLatticeElement::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement">ValueLatticeElement</a> &amp; Other)</td>
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



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#aee232a2f47e3b90163a98f12646b946a">ValueLatticeElement</a>.</p>

</div>
</div>

### operator=() {#ad9691c32880d7ab39512a94d9530ae78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueLatticeElement &amp; llvm::ValueLatticeElement::operator= (<a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement">ValueLatticeElement</a> &amp;&amp; Other)</td>
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



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#aee232a2f47e3b90163a98f12646b946a">ValueLatticeElement</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### asConstantInteger() {#a414095f3b62e33f0c3113205c44b65fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; APInt &gt; llvm::ValueLatticeElement::asConstantInteger ()</td>
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



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ab79de6040b9a8bacd648c5916fb36cd9">getConstant</a>, <a href="#a73e8c58e4d729c42b5f27e3d847c54f8">getConstantRange</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a1d705f2b7894d43bae1ff46eaf600181">llvm::ConstantRange::getSingleElement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a62d37ceb318e78806df7e0a928b0eb1c">isConstant</a> and <a href="#a7ab774f05d02e4bbe7817798cdf19186">isConstantRange</a>.</p>

</div>
</div>

### asConstantRange() {#a3b5efcaf6d7833656101e9d19b00775f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange llvm::ValueLatticeElement::asConstantRange (unsigned BW, bool UndefAllowed=false)</td>
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



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>References <a href="#ab79de6040b9a8bacd648c5916fb36cd9">getConstant</a>, <a href="#a73e8c58e4d729c42b5f27e3d847c54f8">getConstantRange</a>, <a href="#a62d37ceb318e78806df7e0a928b0eb1c">isConstant</a>, <a href="#a7ab774f05d02e4bbe7817798cdf19186">isConstantRange</a>, <a href="#a68d7fa33cb79b86841e367ef88c245f8">isUnknown</a> and <a href="/web-llvm/docs/api/classes/llvm/constant/#a4af4fe6392d3860167eafedc817ed8b1">llvm::Constant::toConstantRange</a>.</p>


<p>Referenced by <a href="#ab5b8cb6678147066f4f3576c4550c386">asConstantRange</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae573064e881a6a5e07f9904117a9102e">llvm::refineInstruction</a>.</p>

</div>
</div>

### asConstantRange() {#ab5b8cb6678147066f4f3576c4550c386}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange llvm::ValueLatticeElement::asConstantRange (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, bool UndefAllowed=false)</td>
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



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>References <a href="#a3b5efcaf6d7833656101e9d19b00775f">asConstantRange</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getCompare() {#a28425702df856e59142416e70fc6c43a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * llvm::ValueLatticeElement::getCompare (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement">ValueLatticeElement</a> &amp; Other, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>true, false or undef constants, or nullptr if the comparison cannot be evaluated.</p>

<p>Declaration at line 470 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>, definition at line 15 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuelattice-cpp">ValueLattice.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3cd3a3ec28036937ecebe767498ba55d">llvm::ConstantFoldCompareInstOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#ab79de6040b9a8bacd648c5916fb36cd9">getConstant</a>, <a href="#a73e8c58e4d729c42b5f27e3d847c54f8">getConstantRange</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa7cce62ac5cc6df09cce0535874336b7">llvm::ConstantInt::getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa2a54b545d237ecfe450fd1292f7675e">llvm::CmpInst::getInversePredicate</a>, <a href="#a908b087596156c6a6c61275c49bece7d">getNotConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="#a62d37ceb318e78806df7e0a928b0eb1c">isConstant</a>, <a href="#a7ab774f05d02e4bbe7817798cdf19186">isConstantRange</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#abe8988eef2e6fc2baba032cb22afedd7">llvm::ICmpInst::isEquality</a>, <a href="#a3e15dd37f1b32b64bf9ff7c7ad03d70d">isNotConstant</a>, <a href="#a04947cf0017de409235dadda5b662c4d">isUndef</a>, <a href="#a68d7fa33cb79b86841e367ef88c245f8">isUnknown</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#aee232a2f47e3b90163a98f12646b946a">ValueLatticeElement</a>.</p>

</div>
</div>

### getConstant() {#ab79de6040b9a8bacd648c5916fb36cd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * llvm::ValueLatticeElement::getConstant ()</td>
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



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af7290ead3cbacbb12b762c8170e7bebc">ConstVal</a> and <a href="#a62d37ceb318e78806df7e0a928b0eb1c">isConstant</a>.</p>


<p>Referenced by <a href="#a414095f3b62e33f0c3113205c44b65fd">asConstantInteger</a>, <a href="#a3b5efcaf6d7833656101e9d19b00775f">asConstantRange</a>, <a href="#a28425702df856e59142416e70fc6c43a">getCompare</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpinstvisitor/#a267e38911b1fc5417bb5f634ac53a261">llvm::SCCPInstVisitor::getConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ac4cfc0065b09dbea4311561f67c2e3ea">getPredicateResult</a>, <a href="#adcc7b385c19a2f07a57bf7351ce25d90">markConstant</a>, <a href="#afbd26f64ed2e22a81bf690e93aa121a0">markConstantRange</a>, <a href="#aceaa5f442dd3df34f51799f2999d237e">mergeIn</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5a073f05ad3bd5b6b413fcd8cffdf0ed">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### getConstantRange() {#a73e8c58e4d729c42b5f27e3d847c54f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ConstantRange &amp; llvm::ValueLatticeElement::getConstantRange (bool UndefAllowed=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Returns the constant range for this value.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> <span class="doxyComputerOutput">UndefAllowed</span> to exclude non-singleton constant ranges that may also be undef. Note that this function also returns a range if the range may include undef, but only contains a single element. In that case, it can be replaced by a constant.</p>


<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7ab774f05d02e4bbe7817798cdf19186">isConstantRange</a> and <a href="#a5e4bbabfbc657ba3dc53158d93776bd7">Range</a>.</p>


<p>Referenced by <a href="#a414095f3b62e33f0c3113205c44b65fd">asConstantInteger</a>, <a href="#a3b5efcaf6d7833656101e9d19b00775f">asConstantRange</a>, <a href="#a28425702df856e59142416e70fc6c43a">getCompare</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpinstvisitor/#a267e38911b1fc5417bb5f634ac53a261">llvm::SCCPInstVisitor::getConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ac4cfc0065b09dbea4311561f67c2e3ea">getPredicateResult</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#a59121faba668261cf400df39e3592637">hasSingleValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abc80238c61c9232dfd8114e30dbf7c18">llvm::hasSingleValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb708ab48a84e8d45f8b640ffbb395ac">llvm::inferAttribute</a>, <a href="#a975cd575019795ff8714252a22f27c26">intersect</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpsolver/#ad443783793d65506b0b69745c79d26d5">llvm::SCCPSolver::isConstant</a>, <a href="#afbd26f64ed2e22a81bf690e93aa121a0">markConstantRange</a>, <a href="#aceaa5f442dd3df34f51799f2999d237e">mergeIn</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5a073f05ad3bd5b6b413fcd8cffdf0ed">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### getNotConstant() {#a908b087596156c6a6c61275c49bece7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * llvm::ValueLatticeElement::getNotConstant ()</td>
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



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af7290ead3cbacbb12b762c8170e7bebc">ConstVal</a> and <a href="#a3e15dd37f1b32b64bf9ff7c7ad03d70d">isNotConstant</a>.</p>


<p>Referenced by <a href="#a28425702df856e59142416e70fc6c43a">getCompare</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ac4cfc0065b09dbea4311561f67c2e3ea">getPredicateResult</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb708ab48a84e8d45f8b640ffbb395ac">llvm::inferAttribute</a>, <a href="#a15288f094b6ef51a8cade84175bb9993">markNotConstant</a>, <a href="#aceaa5f442dd3df34f51799f2999d237e">mergeIn</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5a073f05ad3bd5b6b413fcd8cffdf0ed">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### getNumRangeExtensions() {#a8589b2fc437dff685d325713531f741d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ValueLatticeElement::getNumRangeExtensions ()</td>
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



<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>

</div>
</div>

### intersect() {#a975cd575019795ff8714252a22f27c26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueLatticeElement llvm::ValueLatticeElement::intersect (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement">ValueLatticeElement</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Combine two sets of facts about the same value into a single set of facts.</p>


<p>Note that this method is not suitable for merging facts along different paths in a CFG; that's what the mergeIn function is for. This is for merging facts gathered about the same value at the same location through two independent means. Notes:</p>


<ul class="doxyList ">
<li>This method does not promise to return the most precise possible lattice value implied by A and B. It is allowed to return any lattice element which is at least as strong as <em>either</em> A or B (unless our facts conflict, see below).</li>
<li>Due to unreachable code, the intersection of two lattice values could be contradictory. If this happens, we return some valid lattice value so as not confuse the rest of LVI. Ideally, we'd always return Undefined, but we do not make this guarantee. TODO: This would be a useful enhancement.</li>
</ul>

<p>Declaration at line 489 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>, definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuelattice-cpp">ValueLattice.cpp</a>.</p>


<p>References <a href="#a73e8c58e4d729c42b5f27e3d847c54f8">getConstantRange</a>, <a href="#a1fa37f9808504c2a3d588ec0aa1532ac">getRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abc80238c61c9232dfd8114e30dbf7c18">llvm::hasSingleValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ac098fe4f07549fb029fbf950dbe78fd3">llvm::ConstantRange::intersectWith</a>, <a href="#a7ab774f05d02e4bbe7817798cdf19186">isConstantRange</a>, <a href="#a2a2c134b14dc9616963c42ceebccc1c7">isConstantRangeIncludingUndef</a>, <a href="#a226c3252bd1261be2ff904697586f6d8">isOverdefined</a>, <a href="#a68d7fa33cb79b86841e367ef88c245f8">isUnknown</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a5e4bbabfbc657ba3dc53158d93776bd7">Range</a> and <a href="#aee232a2f47e3b90163a98f12646b946a">ValueLatticeElement</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfoimpl/#ae5eb92f05b5c0c082472775da1e6cace">llvm::LazyValueInfoImpl::getValueAtUse</a>.</p>

</div>
</div>

### isConstant() {#a62d37ceb318e78806df7e0a928b0eb1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ValueLatticeElement::isConstant ()</td>
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



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>Referenced by <a href="#a414095f3b62e33f0c3113205c44b65fd">asConstantInteger</a>, <a href="#a3b5efcaf6d7833656101e9d19b00775f">asConstantRange</a>, <a href="#a28425702df856e59142416e70fc6c43a">getCompare</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpinstvisitor/#a267e38911b1fc5417bb5f634ac53a261">llvm::SCCPInstVisitor::getConstant</a>, <a href="#ab79de6040b9a8bacd648c5916fb36cd9">getConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ac4cfc0065b09dbea4311561f67c2e3ea">getPredicateResult</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#a59121faba668261cf400df39e3592637">hasSingleValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abc80238c61c9232dfd8114e30dbf7c18">llvm::hasSingleValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpsolver/#ad443783793d65506b0b69745c79d26d5">llvm::SCCPSolver::isConstant</a>, <a href="#adcc7b385c19a2f07a57bf7351ce25d90">markConstant</a>, <a href="#afbd26f64ed2e22a81bf690e93aa121a0">markConstantRange</a> and <a href="#aceaa5f442dd3df34f51799f2999d237e">mergeIn</a>.</p>

</div>
</div>

### isConstantRange() {#a7ab774f05d02e4bbe7817798cdf19186}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ValueLatticeElement::isConstantRange (bool UndefAllowed=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Returns true if this value is a constant range.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> <span class="doxyComputerOutput">UndefAllowed</span> to exclude non-singleton constant ranges that may also be undef. Note that this function also returns true if the range may include undef, but only contains a single element. In that case, it can be replaced by a constant.</p>


<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>Reference <a href="#a5e4bbabfbc657ba3dc53158d93776bd7">Range</a>.</p>


<p>Referenced by <a href="#a414095f3b62e33f0c3113205c44b65fd">asConstantInteger</a>, <a href="#a3b5efcaf6d7833656101e9d19b00775f">asConstantRange</a>, <a href="#a28425702df856e59142416e70fc6c43a">getCompare</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpinstvisitor/#a267e38911b1fc5417bb5f634ac53a261">llvm::SCCPInstVisitor::getConstant</a>, <a href="#a73e8c58e4d729c42b5f27e3d847c54f8">getConstantRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ac4cfc0065b09dbea4311561f67c2e3ea">getPredicateResult</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#a59121faba668261cf400df39e3592637">hasSingleValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abc80238c61c9232dfd8114e30dbf7c18">llvm::hasSingleValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb708ab48a84e8d45f8b640ffbb395ac">llvm::inferAttribute</a>, <a href="#a975cd575019795ff8714252a22f27c26">intersect</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpsolver/#ad443783793d65506b0b69745c79d26d5">llvm::SCCPSolver::isConstant</a>, <a href="#afbd26f64ed2e22a81bf690e93aa121a0">markConstantRange</a>, <a href="#aceaa5f442dd3df34f51799f2999d237e">mergeIn</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5a073f05ad3bd5b6b413fcd8cffdf0ed">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### isConstantRangeIncludingUndef() {#a2a2c134b14dc9616963c42ceebccc1c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ValueLatticeElement::isConstantRangeIncludingUndef ()</td>
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



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#afb708ab48a84e8d45f8b640ffbb395ac">llvm::inferAttribute</a>, <a href="#a975cd575019795ff8714252a22f27c26">intersect</a>, <a href="#afbd26f64ed2e22a81bf690e93aa121a0">markConstantRange</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5a073f05ad3bd5b6b413fcd8cffdf0ed">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### isNotConstant() {#a3e15dd37f1b32b64bf9ff7c7ad03d70d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ValueLatticeElement::isNotConstant ()</td>
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



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>Referenced by <a href="#a28425702df856e59142416e70fc6c43a">getCompare</a>, <a href="#a908b087596156c6a6c61275c49bece7d">getNotConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ac4cfc0065b09dbea4311561f67c2e3ea">getPredicateResult</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb708ab48a84e8d45f8b640ffbb395ac">llvm::inferAttribute</a>, <a href="#a15288f094b6ef51a8cade84175bb9993">markNotConstant</a>, <a href="#aceaa5f442dd3df34f51799f2999d237e">mergeIn</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5a073f05ad3bd5b6b413fcd8cffdf0ed">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### isOverdefined() {#a226c3252bd1261be2ff904697586f6d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ValueLatticeElement::isOverdefined ()</td>
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



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>Referenced by <a href="#a975cd575019795ff8714252a22f27c26">intersect</a>, <a href="#a9d17cb6299d749c3e3b1860ea5545c08">markOverdefined</a>, <a href="#aceaa5f442dd3df34f51799f2999d237e">mergeIn</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5a073f05ad3bd5b6b413fcd8cffdf0ed">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### isUndef() {#a04947cf0017de409235dadda5b662c4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ValueLatticeElement::isUndef ()</td>
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



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>Referenced by <a href="#a28425702df856e59142416e70fc6c43a">getCompare</a>, <a href="#adcc7b385c19a2f07a57bf7351ce25d90">markConstant</a>, <a href="#afbd26f64ed2e22a81bf690e93aa121a0">markConstantRange</a>, <a href="#ab32f3bc397a5c669fb5c7320df6de2a7">markUndef</a>, <a href="#aceaa5f442dd3df34f51799f2999d237e">mergeIn</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5a073f05ad3bd5b6b413fcd8cffdf0ed">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### isUnknown() {#a68d7fa33cb79b86841e367ef88c245f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ValueLatticeElement::isUnknown ()</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>Referenced by <a href="#a3b5efcaf6d7833656101e9d19b00775f">asConstantRange</a>, <a href="#a28425702df856e59142416e70fc6c43a">getCompare</a>, <a href="#a975cd575019795ff8714252a22f27c26">intersect</a>, <a href="#adcc7b385c19a2f07a57bf7351ce25d90">markConstant</a>, <a href="#afbd26f64ed2e22a81bf690e93aa121a0">markConstantRange</a>, <a href="#a15288f094b6ef51a8cade84175bb9993">markNotConstant</a>, <a href="#ab32f3bc397a5c669fb5c7320df6de2a7">markUndef</a>, <a href="#aceaa5f442dd3df34f51799f2999d237e">mergeIn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5a073f05ad3bd5b6b413fcd8cffdf0ed">llvm::operator&lt;&lt;</a> and <a href="/web-llvm/docs/api/classes/llvm/sccpinstvisitor/#a1ba56140e5d65987c0cbc692b05a795f">llvm::SCCPInstVisitor::resolvedUndef</a>.</p>

</div>
</div>

### isUnknownOrUndef() {#ab20e06908032fd7028c20c1d2d5a248a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ValueLatticeElement::isUnknownOrUndef ()</td>
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



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sccpsolver/#ae58f6a2457188593908aae83468858d3">llvm::SCCPSolver::isOverdefined</a>.</p>

</div>
</div>

### markConstant() {#adcc7b385c19a2f07a57bf7351ce25d90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ValueLatticeElement::markConstant (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * V, bool MayIncludeUndef=false)</td>
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



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af7290ead3cbacbb12b762c8170e7bebc">ConstVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ab79de6040b9a8bacd648c5916fb36cd9">getConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a62d37ceb318e78806df7e0a928b0eb1c">isConstant</a>, <a href="#a04947cf0017de409235dadda5b662c4d">isUndef</a>, <a href="#a68d7fa33cb79b86841e367ef88c245f8">isUnknown</a>, <a href="#afbd26f64ed2e22a81bf690e93aa121a0">markConstantRange</a> and <a href="#ab32f3bc397a5c669fb5c7320df6de2a7">markUndef</a>.</p>


<p>Referenced by <a href="#a856d831b6862fb41fffecd00990bcc2c">get</a>, <a href="#aceaa5f442dd3df34f51799f2999d237e">mergeIn</a> and <a href="/web-llvm/docs/api/classes/llvm/sccpinstvisitor/#aea38159494421174efc48de560b11b61">llvm::SCCPInstVisitor::setLatticeValueForSpecializationArguments</a>.</p>

</div>
</div>

### markConstantRange() {#afbd26f64ed2e22a81bf690e93aa121a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ValueLatticeElement::markConstantRange (<a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> NewR, <a href="/web-llvm/docs/api/structs/llvm/valuelatticeelement/mergeoptions">MergeOptions</a> Opts=<a href="/web-llvm/docs/api/structs/llvm/valuelatticeelement/mergeoptions">MergeOptions</a>())</td>
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

<p>Mark the object as constant range with <span class="doxyComputerOutput">NewR</span>.</p>


<p>If the object is already a constant range, nothing changes if the existing range is equal to <span class="doxyComputerOutput">NewR</span> and the tag. Otherwise <span class="doxyComputerOutput">NewR</span> must be a superset of the existing range or the object must be undef. The tag is set to constant_range_including_undef if either the existing value or the new range may include undef.</p>


<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aaca3a4d2b25c24b11179cbd01079b73c">llvm::ConstantRange::contains</a>, <a href="#ab79de6040b9a8bacd648c5916fb36cd9">getConstant</a>, <a href="#a73e8c58e4d729c42b5f27e3d847c54f8">getConstantRange</a>, <a href="#a62d37ceb318e78806df7e0a928b0eb1c">isConstant</a>, <a href="#a7ab774f05d02e4bbe7817798cdf19186">isConstantRange</a>, <a href="#a2a2c134b14dc9616963c42ceebccc1c7">isConstantRangeIncludingUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a5bd6d98b4a7ecc1dcdc571e4352fcc52">llvm::ConstantRange::isEmptySet</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a4f6242fab5145c424cee29230fefe746">llvm::ConstantRange::isFullSet</a>, <a href="#a04947cf0017de409235dadda5b662c4d">isUndef</a>, <a href="#a68d7fa33cb79b86841e367ef88c245f8">isUnknown</a>, <a href="#a9d17cb6299d749c3e3b1860ea5545c08">markOverdefined</a> and <a href="#a5e4bbabfbc657ba3dc53158d93776bd7">Range</a>.</p>


<p>Referenced by <a href="#a1fa37f9808504c2a3d588ec0aa1532ac">getRange</a>, <a href="#adcc7b385c19a2f07a57bf7351ce25d90">markConstant</a>, <a href="#a15288f094b6ef51a8cade84175bb9993">markNotConstant</a> and <a href="#aceaa5f442dd3df34f51799f2999d237e">mergeIn</a>.</p>

</div>
</div>

### markNotConstant() {#a15288f094b6ef51a8cade84175bb9993}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ValueLatticeElement::markNotConstant (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * V)</td>
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



<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af7290ead3cbacbb12b762c8170e7bebc">ConstVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a908b087596156c6a6c61275c49bece7d">getNotConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a3e15dd37f1b32b64bf9ff7c7ad03d70d">isNotConstant</a>, <a href="#a68d7fa33cb79b86841e367ef88c245f8">isUnknown</a> and <a href="#afbd26f64ed2e22a81bf690e93aa121a0">markConstantRange</a>.</p>


<p>Referenced by <a href="#a3347382fc7040a7bc3ed0c7fcf6442c6">getNot</a>.</p>

</div>
</div>

### markOverdefined() {#a9d17cb6299d749c3e3b1860ea5545c08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ValueLatticeElement::markOverdefined ()</td>
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



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>Reference <a href="#a226c3252bd1261be2ff904697586f6d8">isOverdefined</a>.</p>


<p>Referenced by <a href="#afa0befbad06a536ee25c232941a09856">getOverdefined</a>, <a href="#afbd26f64ed2e22a81bf690e93aa121a0">markConstantRange</a> and <a href="#aceaa5f442dd3df34f51799f2999d237e">mergeIn</a>.</p>

</div>
</div>

### markUndef() {#ab32f3bc397a5c669fb5c7320df6de2a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ValueLatticeElement::markUndef ()</td>
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



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a04947cf0017de409235dadda5b662c4d">isUndef</a> and <a href="#a68d7fa33cb79b86841e367ef88c245f8">isUnknown</a>.</p>


<p>Referenced by <a href="#a1fa37f9808504c2a3d588ec0aa1532ac">getRange</a> and <a href="#adcc7b385c19a2f07a57bf7351ce25d90">markConstant</a>.</p>

</div>
</div>

### mergeIn() {#aceaa5f442dd3df34f51799f2999d237e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ValueLatticeElement::mergeIn (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement">ValueLatticeElement</a> &amp; RHS, <a href="/web-llvm/docs/api/structs/llvm/valuelatticeelement/mergeoptions">MergeOptions</a> Opts=<a href="/web-llvm/docs/api/structs/llvm/valuelatticeelement/mergeoptions">MergeOptions</a>())</td>
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

<p>Updates this object to approximate both this object and RHS.</p>


<p>Returns true if this object has been changed.</p>


<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab79de6040b9a8bacd648c5916fb36cd9">getConstant</a>, <a href="#a73e8c58e4d729c42b5f27e3d847c54f8">getConstantRange</a>, <a href="#a908b087596156c6a6c61275c49bece7d">getNotConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>, <a href="#a62d37ceb318e78806df7e0a928b0eb1c">isConstant</a>, <a href="#a7ab774f05d02e4bbe7817798cdf19186">isConstantRange</a>, <a href="#a3e15dd37f1b32b64bf9ff7c7ad03d70d">isNotConstant</a>, <a href="#a226c3252bd1261be2ff904697586f6d8">isOverdefined</a>, <a href="#a04947cf0017de409235dadda5b662c4d">isUndef</a>, <a href="#a68d7fa33cb79b86841e367ef88c245f8">isUnknown</a>, <a href="#adcc7b385c19a2f07a57bf7351ce25d90">markConstant</a>, <a href="#afbd26f64ed2e22a81bf690e93aa121a0">markConstantRange</a>, <a href="#a9d17cb6299d749c3e3b1860ea5545c08">markOverdefined</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a4af4fe6392d3860167eafedc817ed8b1">llvm::Constant::toConstantRange</a> and <a href="#aee232a2f47e3b90163a98f12646b946a">ValueLatticeElement</a>.</p>

</div>
</div>

### setNumRangeExtensions() {#a64a82dcbacd27ff1996040ad31c9f36e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ValueLatticeElement::setNumRangeExtensions (unsigned N)</td>
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



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### destroy() {#a411241a4a0959d6981934d73d3690085}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ValueLatticeElement::destroy ()</td>
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

<p>Destroy contents of lattice value, without destructing the object.</p>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ConstVal {#af7290ead3cbacbb12b762c8170e7bebc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant* llvm::ValueLatticeElement::ConstVal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>Referenced by <a href="#ab79de6040b9a8bacd648c5916fb36cd9">getConstant</a>, <a href="#a908b087596156c6a6c61275c49bece7d">getNotConstant</a>, <a href="#adcc7b385c19a2f07a57bf7351ce25d90">markConstant</a> and <a href="#a15288f094b6ef51a8cade84175bb9993">markNotConstant</a>.</p>

</div>
</div>

### Range {#a5e4bbabfbc657ba3dc53158d93776bd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange llvm::ValueLatticeElement::Range</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>Referenced by <a href="#a73e8c58e4d729c42b5f27e3d847c54f8">getConstantRange</a>, <a href="#a975cd575019795ff8714252a22f27c26">intersect</a>, <a href="#a7ab774f05d02e4bbe7817798cdf19186">isConstantRange</a> and <a href="#afbd26f64ed2e22a81bf690e93aa121a0">markConstantRange</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

###  {#a50b4e339429703558421cc2e66a09cdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::ValueLatticeElement llvm::ValueLatticeElement</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The union either stores a pointer to a constant or a constant range, associated to the lattice element.</p>


<p>We have to ensure that Range is initialized or destroyed when changing state to or from constantrange.</p>


<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>

</div>
</div>

### NumRangeExtensions {#aa2832f021240693703fb0a7133c7ac5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ValueLatticeElement::NumRangeExtensions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of times a constant range has been extended with widening enabled.</p>

<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>

</div>
</div>

### Tag {#a0ba7449e3e0b42020f155a1439feb9af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueLatticeElementTy llvm::ValueLatticeElement::Tag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### get() {#a856d831b6862fb41fffecd00990bcc2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueLatticeElement llvm::ValueLatticeElement::get (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C)</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#adcc7b385c19a2f07a57bf7351ce25d90">markConstant</a> and <a href="#aee232a2f47e3b90163a98f12646b946a">ValueLatticeElement</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfoimpl/#a6aef100d648e62bb628c87faf0ae9534">llvm::LazyValueInfoImpl::getValueAt</a>.</p>

</div>
</div>

### getNot() {#a3347382fc7040a7bc3ed0c7fcf6442c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueLatticeElement llvm::ValueLatticeElement::getNot (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C)</td>
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



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a15288f094b6ef51a8cade84175bb9993">markNotConstant</a> and <a href="#aee232a2f47e3b90163a98f12646b946a">ValueLatticeElement</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sccpinstvisitor/#aa01f1a82f6d38c3f2f070226059e035e">llvm::SCCPInstVisitor::getArgAttributeVL</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp/#a368c19b0d77eb9cc6d3642c1028823af">getValueFromMetadata</a>.</p>

</div>
</div>

### getOverdefined() {#afa0befbad06a536ee25c232941a09856}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueLatticeElement llvm::ValueLatticeElement::getOverdefined ()</td>
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



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>References <a href="#a9d17cb6299d749c3e3b1860ea5545c08">markOverdefined</a> and <a href="#aee232a2f47e3b90163a98f12646b946a">ValueLatticeElement</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#a7467c1c3eff398cd97c3d8a2b2cebac0">constantFoldUser</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpinstvisitor/#aa01f1a82f6d38c3f2f070226059e035e">llvm::SCCPInstVisitor::getArgAttributeVL</a>, <a href="/web-llvm/docs/api/classes/anonymous-lazyvalueinfo-cpp-/lazyvalueinfocache/#a3438d4775f46be4ad02e9b72121afd90">anonymous{LazyValueInfo.cpp}::LazyValueInfoCache::getCachedValueInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#aa116214bf0f5cf6201935447b27334e8">getFromRangeMetadata</a>, <a href="#a1fa37f9808504c2a3d588ec0aa1532ac">getRange</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfoimpl/#a6aef100d648e62bb628c87faf0ae9534">llvm::LazyValueInfoImpl::getValueAt</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#a61c6720db574963baad9d12d32a3c6ad">getValueFromICmpCtpop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp/#a368c19b0d77eb9cc6d3642c1028823af">getValueFromMetadata</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#acb6e73547764d0338afa32e54ad785cf">getValueFromOverflowCondition</a>.</p>

</div>
</div>

### getRange() {#a1fa37f9808504c2a3d588ec0aa1532ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueLatticeElement llvm::ValueLatticeElement::getRange (<a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> CR, bool MayIncludeUndef=false)</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>References <a href="#afa0befbad06a536ee25c232941a09856">getOverdefined</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a5bd6d98b4a7ecc1dcdc571e4352fcc52">llvm::ConstantRange::isEmptySet</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a4f6242fab5145c424cee29230fefe746">llvm::ConstantRange::isFullSet</a>, <a href="#afbd26f64ed2e22a81bf690e93aa121a0">markConstantRange</a>, <a href="#ab32f3bc397a5c669fb5c7320df6de2a7">markUndef</a> and <a href="#aee232a2f47e3b90163a98f12646b946a">ValueLatticeElement</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#a7467c1c3eff398cd97c3d8a2b2cebac0">constantFoldUser</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpinstvisitor/#aa01f1a82f6d38c3f2f070226059e035e">llvm::SCCPInstVisitor::getArgAttributeVL</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#aa116214bf0f5cf6201935447b27334e8">getFromRangeMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#a61c6720db574963baad9d12d32a3c6ad">getValueFromICmpCtpop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp/#a368c19b0d77eb9cc6d3642c1028823af">getValueFromMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#acb6e73547764d0338afa32e54ad785cf">getValueFromOverflowCondition</a> and <a href="#a975cd575019795ff8714252a22f27c26">intersect</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/valuelattice-cpp">ValueLattice.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
