---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-hexagonconstpropagation-cpp-/constantproperties
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ConstantProperties` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{HexagonConstPropagation.cpp}::ConstantProperties { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#af78a969bb965b0f4d2bdb79ce9baf20e">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea4b4c239b71e73a13e281c9b2b623e6">deduce</a> (const Constant *C)</td>
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


<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#af78a969bb965b0f4d2bdb79ce9baf20e}

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
<td class="doxyEnumItemName">Unknown<a id="af78a969bb965b0f4d2bdb79ce9baf20eae39e5aad668b29b247469a47a090f83f"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Zero<a id="af78a969bb965b0f4d2bdb79ce9baf20eaef919e157ce009f336138b8e817db61f"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0001)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NonZero<a id="af78a969bb965b0f4d2bdb79ce9baf20eac255ffe2552a03202a03d622ce4d5216"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0002)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Finite<a id="af78a969bb965b0f4d2bdb79ce9baf20eade64a482e898536df49815e59c181e68"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0004)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Infinity<a id="af78a969bb965b0f4d2bdb79ce9baf20eaa26a53a9462c029ba8f7a3486bcb17c0"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0008)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NaN<a id="af78a969bb965b0f4d2bdb79ce9baf20eaa0cccb008a3914b88dfc26d7763f0179"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0010)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SignedZero<a id="af78a969bb965b0f4d2bdb79ce9baf20eaec489134e07ff79ea55696764dcad4fb"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0020)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NumericProperties<a id="af78a969bb965b0f4d2bdb79ce9baf20eac9b340414f45754c69c996ab70428665"></a></td>
<td class="doxyEnumItemDescription"> (= (Zero|NonZero|Finite|Infinity|NaN|SignedZero))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PosOrZero<a id="af78a969bb965b0f4d2bdb79ce9baf20eadc91a81eb1fbc5305a83ac09843d10f9"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0100)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NegOrZero<a id="af78a969bb965b0f4d2bdb79ce9baf20ea08112154ca09f6cbf19bbbd8b1b3a34c"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0200)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SignProperties<a id="af78a969bb965b0f4d2bdb79ce9baf20eab16adc011819946f59995b60e2a83509"></a></td>
<td class="doxyEnumItemDescription"> (= (PosOrZero|NegOrZero))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Everything<a id="af78a969bb965b0f4d2bdb79ce9baf20ea6cd352a11bb50bebb4af3d4ac782b227"></a></td>
<td class="doxyEnumItemDescription"> (= (NumericProperties|SignProperties))</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### deduce() {#aea4b4c239b71e73a13e281c9b2b623e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t ConstantProperties::deduce (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C)</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#af78a969bb965b0f4d2bdb79ce9baf20eade64a482e898536df49815e59c181e68">Finite</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a32aa14715eeb813d764fcf20f161f0a1">llvm::ConstantFP::getValueAPF</a>, <a href="#af78a969bb965b0f4d2bdb79ce9baf20eaa26a53a9462c029ba8f7a3486bcb17c0">Infinity</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#afdbfe0ba27cece5e333f4a7ae68fa82e">llvm::APFloat::isInfinity</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#ab214f457242ca2716988169778335f1e">llvm::ConstantFP::isNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a684130a8a53c04cbd92881243d6a5ae1">llvm::ConstantFP::isNegative</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a2a8c8be274f3bd351e083ab3828c14c7">llvm::ConstantInt::isNegative</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#ae46c23ed39de6de6cf9ec6e57755e4c5">llvm::ConstantFP::isZero</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a882d55a6aa2028e1a5ad708b275334e0">llvm::ConstantInt::isZero</a>, <a href="#af78a969bb965b0f4d2bdb79ce9baf20eaa0cccb008a3914b88dfc26d7763f0179">NaN</a>, <a href="#af78a969bb965b0f4d2bdb79ce9baf20ea08112154ca09f6cbf19bbbd8b1b3a34c">NegOrZero</a>, <a href="#af78a969bb965b0f4d2bdb79ce9baf20eac255ffe2552a03202a03d622ce4d5216">NonZero</a>, <a href="#af78a969bb965b0f4d2bdb79ce9baf20eac9b340414f45754c69c996ab70428665">NumericProperties</a>, <a href="#af78a969bb965b0f4d2bdb79ce9baf20eadc91a81eb1fbc5305a83ac09843d10f9">PosOrZero</a>, <a href="#af78a969bb965b0f4d2bdb79ce9baf20eae39e5aad668b29b247469a47a090f83f">Unknown</a> and <a href="#af78a969bb965b0f4d2bdb79ce9baf20eaef919e157ce009f336138b8e817db61f">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#ab13878421737db422070f682fda17077">anonymous{HexagonConstPropagation.cpp}::LatticeCell::properties</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
