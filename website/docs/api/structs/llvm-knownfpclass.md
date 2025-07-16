---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/knownfpclass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `KnownFPClass` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::KnownFPClass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">llvm/Analysis/ValueTracking.h</a>"
</div>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc8217e29c481acbf29146b541785128">operator==</a> (KnownFPClass Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/knownfpclass">KnownFPClass</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a3df02b0009994281307116977ee86a">operator|=</a> (const KnownFPClass &amp;RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0fbe688ffb115395a2665499c0639a2">isKnownNever</a> (FPClassTest Mask) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it's known this can never be one of the mask entries. <a href="#aa0fbe688ffb115395a2665499c0639a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4310641c3708a7ea863829e1841cd707">isKnownAlways</a> (FPClassTest Mask) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a91c2235d984a1d9d19df3cc1bedd9c">isUnknown</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ace8a5baa7d3c3ad3639fc1e71558bb">isKnownNeverNaN</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it's known this can never be a nan. <a href="#a9ace8a5baa7d3c3ad3639fc1e71558bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a009e9523110c79d3cc8fae67e9026562">isKnownAlwaysNaN</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it's known this must always be a nan. <a href="#a009e9523110c79d3cc8fae67e9026562">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a027c4727dcc8065b37e16d710869faea">isKnownNeverInfinity</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it's known this can never be an infinity. <a href="#a027c4727dcc8065b37e16d710869faea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accb142befbb571f6388b1e5d6360095d">isKnownNeverPosInfinity</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it's known this can never be +infinity. <a href="#accb142befbb571f6388b1e5d6360095d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90ee18f9caf7e7885f6cc1cd526f4ae4">isKnownNeverNegInfinity</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it's known this can never be -infinity. <a href="#a90ee18f9caf7e7885f6cc1cd526f4ae4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c951d72721a5640003806474c07f73d">isKnownNeverSubnormal</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it's known this can never be a subnormal. <a href="#a2c951d72721a5640003806474c07f73d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbfd19ed4794030f4e05a6558d4aba0f">isKnownNeverPosSubnormal</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it's known this can never be a positive subnormal. <a href="#afbfd19ed4794030f4e05a6558d4aba0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a925cfb1289b0d1de226f826d5f036cd8">isKnownNeverNegSubnormal</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it's known this can never be a negative subnormal. <a href="#a925cfb1289b0d1de226f826d5f036cd8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c00cb98413fb8b5178256b0ceaf8387">isKnownNeverZero</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it's known this can never be a zero. <a href="#a1c00cb98413fb8b5178256b0ceaf8387">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94dcc8e868472796e4448759abde299f">isKnownNeverPosZero</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it's known this can never be a literal positive zero. <a href="#a94dcc8e868472796e4448759abde299f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0028c1e6f393070ccfd9e65c6c41633">isKnownNeverNegZero</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it's known this can never be a negative zero. <a href="#ab0028c1e6f393070ccfd9e65c6c41633">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb9838786d5dc284bd667d28c1ee1004">isKnownNeverLogicalZero</a> (const Function &amp;F, Type *Ty) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it's know this can never be interpreted as a zero. <a href="#abb9838786d5dc284bd667d28c1ee1004">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a470d18ba72758ba86e30c5d46de5e2d7">isKnownNeverLogicalNegZero</a> (const Function &amp;F, Type *Ty) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it's know this can never be interpreted as a negative zero. <a href="#a470d18ba72758ba86e30c5d46de5e2d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a506835c101376856be7c584e0e63fbb8">isKnownNeverLogicalPosZero</a> (const Function &amp;F, Type *Ty) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it's know this can never be interpreted as a positive zero. <a href="#a506835c101376856be7c584e0e63fbb8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac068bb13883a326befa8b10d45cb52a2">cannotBeOrderedLessThanZero</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we can prove that the analyzed floating-point value is either NaN or never less than -0.0. <a href="#ac068bb13883a326befa8b10d45cb52a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d341e86d22b4ec6b4eca5642d0ed20d">cannotBeOrderedGreaterThanZero</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we can prove that the analyzed floating-point value is either NaN or never greater than -0.0. <a href="#a0d341e86d22b4ec6b4eca5642d0ed20d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a186c609abd2d8d453e0889b0c0cd7549">knownNot</a> (FPClassTest RuleOut)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61b974f96f2e5ccbf86376dc849e065d">fneg</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb65a04b87935b43786ff09f17840ac0">fabs</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef3eb6ab7234059d2b26da34c604a752">signBitIsZeroOrNaN</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the sign bit must be 0, ignoring the sign of nans. <a href="#aef3eb6ab7234059d2b26da34c604a752">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5ff8a86f05bd1277209099b7cd6c46b">signBitMustBeZero</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assume the sign bit is zero. <a href="#ac5ff8a86f05bd1277209099b7cd6c46b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1a2e2775908a5f77b301701a53d6830">signBitMustBeOne</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assume the sign bit is one. <a href="#ac1a2e2775908a5f77b301701a53d6830">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21ba2e0b3e29866fac506873ee5c1a60">copysign</a> (const KnownFPClass &amp;Sign)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd6308f41af5228d2cf1f03104be6613">propagateNaN</a> (const KnownFPClass &amp;Src, bool PreserveSign=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a832be183f243ae315e8bdd00b9d9acd0">propagateDenormal</a> (const KnownFPClass &amp;Src, const Function &amp;F, Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Propagate knowledge from a source value that could be a denormal or zero. <a href="#a832be183f243ae315e8bdd00b9d9acd0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c8dbd5978c087ccc28ed20be2c63cab">propagateCanonicalizingSrc</a> (const KnownFPClass &amp;Src, const Function &amp;F, Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Report known classes if <span class="doxyComputerOutput">Src</span> is evaluated through a potentially canonicalizing operation. <a href="#a7c8dbd5978c087ccc28ed20be2c63cab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11eb035a176c001e90e4ff6e242155e5">resetAll</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1d">FPClassTest</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0200a1522bbde43a85224153d1bb08fe">KnownFPClasses</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dabf7829a22591343ad790b1357955a7df">fcAllFlags</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Floating-point classes the value could be one of. <a href="#a0200a1522bbde43a85224153d1bb08fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98b802f50f0dfde19089adfd2f4f2f7b">SignBit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>std::nullopt if the sign bit is unknown, true if the sign bit is definitely set or false if the sign bit is definitely unset. <a href="#a98b802f50f0dfde19089adfd2f4f2f7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1d">FPClassTest</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a166b63a9217b936dc956f6b65de7602a">OrderedLessThanZeroMask</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1d">FPClassTest</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1520514ea4aab2457884e02e3c90c05b">OrderedGreaterThanZeroMask</a> = ...</td>
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


<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<div class="doxySectionDef">

## Public Operators

### operator==() {#adc8217e29c481acbf29146b541785128}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::KnownFPClass::operator== (<a href="/web-llvm/docs/api/structs/llvm/knownfpclass">KnownFPClass</a> Other)</td>
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



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>References <a href="#a0200a1522bbde43a85224153d1bb08fe">KnownFPClasses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a98b802f50f0dfde19089adfd2f4f2f7b">SignBit</a>.</p>

</div>
</div>

### operator|=() {#a5a3df02b0009994281307116977ee86a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownFPClass &amp; llvm::KnownFPClass::operator|= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownfpclass">KnownFPClass</a> &amp; RHS)</td>
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



<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>References <a href="#a0200a1522bbde43a85224153d1bb08fe">KnownFPClasses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a98b802f50f0dfde19089adfd2f4f2f7b">SignBit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### cannotBeOrderedGreaterThanZero() {#a0d341e86d22b4ec6b4eca5642d0ed20d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::KnownFPClass::cannotBeOrderedGreaterThanZero ()</td>
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

<p>Return true if we can prove that the analyzed floating-point value is either NaN or never greater than -0.0.</p>


<p>NaN --&gt; true +0 --&gt; true -0 --&gt; true x &gt; +0 --&gt; false x &lt; -0 --&gt; true</p>


<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>References <a href="#aa0fbe688ffb115395a2665499c0639a2">isKnownNever</a> and <a href="#a1520514ea4aab2457884e02e3c90c05b">OrderedGreaterThanZeroMask</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>.</p>

</div>
</div>

### cannotBeOrderedLessThanZero() {#ac068bb13883a326befa8b10d45cb52a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::KnownFPClass::cannotBeOrderedLessThanZero ()</td>
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

<p>Return true if we can prove that the analyzed floating-point value is either NaN or never less than -0.0.</p>



<pre><code> NaN --&gt; true
  +0 --&gt; true
  -0 --&gt; true
</code></pre>


<p>x &gt; +0 --&gt; true x &lt; -0 --&gt; false</p>


<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>References <a href="#aa0fbe688ffb115395a2665499c0639a2">isKnownNever</a> and <a href="#a166b63a9217b936dc956f6b65de7602a">OrderedLessThanZeroMask</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad164187e4f9f1fc16a86d166b9793ac3">llvm::cannotBeOrderedLessThanZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a89dba3d15d8a7ca93983e8779f315b6b">computeKnownFPClassForFPTrunc</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a110a350e37f3cc2ed2c603c3efde0a30">simplifyFCmpInst</a>.</p>

</div>
</div>

### copysign() {#a21ba2e0b3e29866fac506873ee5c1a60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::KnownFPClass::copysign (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownfpclass">KnownFPClass</a> &amp; Sign)</td>
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



<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da00a4419741933f5cb7ec001aaa6e6bb5">llvm::fcInf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dafe1646e5477c571f7791c524b54b11fe">llvm::fcNan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dabd5ff30619fc341f566f44037f42587e">llvm::fcNegative</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dadb8c9ce3197adf47c7f889bab120b77c">llvm::fcNormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da4c071eac84ba221262ca010533f643db">llvm::fcPositive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da449c8fca7f540cc314102a67944fcd6e">llvm::fcSubnormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dab6ede72b2b2219068b9bb89732d24e2f">llvm::fcZero</a>, <a href="#aa0fbe688ffb115395a2665499c0639a2">isKnownNever</a>, <a href="#a0200a1522bbde43a85224153d1bb08fe">KnownFPClasses</a> and <a href="#a98b802f50f0dfde19089adfd2f4f2f7b">SignBit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a98e8d1806c78a1e84fa32e50a41a8a62">llvm::InstCombinerImpl::SimplifyDemandedUseFPClass</a>.</p>

</div>
</div>

### fabs() {#acb65a04b87935b43786ff09f17840ac0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::KnownFPClass::fabs ()</td>
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



<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da3ab665df1666568d7eac3b1373106638">llvm::fcNegInf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dab003a118cd0b76a814ba4dfc7077034a">llvm::fcNegNormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da023ad3d9b33a1af5eb90b8b543fb3ccb">llvm::fcNegSubnormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da1e8072411cd3959aa091c3cae8006dc0">llvm::fcNegZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dada0d259988860d7a2f882aa40b25fee1">llvm::fcPosInf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da052ace75708c251359ff22dd036417a6">llvm::fcPosNormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dad0940edb5f5bf512669b72928b527d0c">llvm::fcPosSubnormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da7ace586671df3e62fa392d5144a8b3da">llvm::fcPosZero</a>, <a href="#a0200a1522bbde43a85224153d1bb08fe">KnownFPClasses</a> and <a href="#ac5ff8a86f05bd1277209099b7cd6c46b">signBitMustBeZero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a98e8d1806c78a1e84fa32e50a41a8a62">llvm::InstCombinerImpl::SimplifyDemandedUseFPClass</a>.</p>

</div>
</div>

### fneg() {#a61b974f96f2e5ccbf86376dc849e065d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::KnownFPClass::fneg ()</td>
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



<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0e0cdeab86f6a5fdb02a954e526a7a">llvm::fneg</a>, <a href="#a0200a1522bbde43a85224153d1bb08fe">KnownFPClasses</a> and <a href="#a98b802f50f0dfde19089adfd2f4f2f7b">SignBit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a98e8d1806c78a1e84fa32e50a41a8a62">llvm::InstCombinerImpl::SimplifyDemandedUseFPClass</a>.</p>

</div>
</div>

### isKnownAlways() {#a4310641c3708a7ea863829e1841cd707}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::KnownFPClass::isKnownAlways (<a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1d">FPClassTest</a> Mask)</td>
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



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>Reference <a href="#aa0fbe688ffb115395a2665499c0639a2">isKnownNever</a>.</p>


<p>Referenced by <a href="#a009e9523110c79d3cc8fae67e9026562">isKnownAlwaysNaN</a>.</p>

</div>
</div>

### isKnownAlwaysNaN() {#a009e9523110c79d3cc8fae67e9026562}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::KnownFPClass::isKnownAlwaysNaN ()</td>
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

<p>Return true if it's known this must always be a nan.</p>

<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dafe1646e5477c571f7791c524b54b11fe">llvm::fcNan</a> and <a href="#a4310641c3708a7ea863829e1841cd707">isKnownAlways</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a110a350e37f3cc2ed2c603c3efde0a30">simplifyFCmpInst</a>.</p>

</div>
</div>

### isKnownNever() {#aa0fbe688ffb115395a2665499c0639a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::KnownFPClass::isKnownNever (<a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1d">FPClassTest</a> Mask)</td>
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

<p>Return true if it's known this can never be one of the mask entries.</p>

<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da4759a508982cd525d9f17024f09aea22">llvm::fcNone</a> and <a href="#a0200a1522bbde43a85224153d1bb08fe">KnownFPClasses</a>.</p>


<p>Referenced by <a href="#a0d341e86d22b4ec6b4eca5642d0ed20d">cannotBeOrderedGreaterThanZero</a>, <a href="#ac068bb13883a326befa8b10d45cb52a2">cannotBeOrderedLessThanZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="#a21ba2e0b3e29866fac506873ee5c1a60">copysign</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a568e85197421e091a259bf80e19c6765">foldFPtoI</a>, <a href="#a4310641c3708a7ea863829e1841cd707">isKnownAlways</a>, <a href="#a027c4727dcc8065b37e16d710869faea">isKnownNeverInfinity</a>, <a href="#a9ace8a5baa7d3c3ad3639fc1e71558bb">isKnownNeverNaN</a>, <a href="#a90ee18f9caf7e7885f6cc1cd526f4ae4">isKnownNeverNegInfinity</a>, <a href="#a925cfb1289b0d1de226f826d5f036cd8">isKnownNeverNegSubnormal</a>, <a href="#ab0028c1e6f393070ccfd9e65c6c41633">isKnownNeverNegZero</a>, <a href="#accb142befbb571f6388b1e5d6360095d">isKnownNeverPosInfinity</a>, <a href="#afbfd19ed4794030f4e05a6558d4aba0f">isKnownNeverPosSubnormal</a>, <a href="#a94dcc8e868472796e4448759abde299f">isKnownNeverPosZero</a>, <a href="#a2c951d72721a5640003806474c07f73d">isKnownNeverSubnormal</a>, <a href="#a1c00cb98413fb8b5178256b0ceaf8387">isKnownNeverZero</a>, <a href="#a186c609abd2d8d453e0889b0c0cd7549">knownNot</a>, <a href="#aef3eb6ab7234059d2b26da34c604a752">signBitIsZeroOrNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a98e8d1806c78a1e84fa32e50a41a8a62">llvm::InstCombinerImpl::SimplifyDemandedUseFPClass</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a5b47854a993004418cb56068fe2dd9dd">simplifyFMAFMul</a>.</p>

</div>
</div>

### isKnownNeverInfinity() {#a027c4727dcc8065b37e16d710869faea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::KnownFPClass::isKnownNeverInfinity ()</td>
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

<p>Return true if it's known this can never be an infinity.</p>

<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da00a4419741933f5cb7ec001aaa6e6bb5">llvm::fcInf</a> and <a href="#aa0fbe688ffb115395a2665499c0639a2">isKnownNever</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a982e49c60a2c0180bce8a7f0914c9ce3">llvm::InstCombinerImpl::fmulByZeroIsZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b69550d2c0e2d57f3886757ac41567">llvm::isKnownNeverInfinity</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a42c8f0b3d870c96030032b8ed8a2a1e3">llvm::isKnownNeverInfOrNaN</a>.</p>

</div>
</div>

### isKnownNeverLogicalNegZero() {#a470d18ba72758ba86e30c5d46de5e2d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool KnownFPClass::isKnownNeverLogicalNegZero (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if it's know this can never be interpreted as a negative zero.</p>

<p>Declaration at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>, definition at line 4425 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp">ValueTracking.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ad4ffc03696c5fb25276e989e15970960">inputDenormalIsIEEEOrPosZero</a>, <a href="#a925cfb1289b0d1de226f826d5f036cd8">isKnownNeverNegSubnormal</a> and <a href="#ab0028c1e6f393070ccfd9e65c6c41633">isKnownNeverNegZero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>.</p>

</div>
</div>

### isKnownNeverLogicalPosZero() {#a506835c101376856be7c584e0e63fbb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool KnownFPClass::isKnownNeverLogicalPosZero (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if it's know this can never be interpreted as a positive zero.</p>

<p>Declaration at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>, definition at line 4431 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp">ValueTracking.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/structs/llvm/denormalmode/#a29b26e3ae30f3f6ec4106ff181282893ad6fd23eb0b98a2d4551582753191b6da">llvm::DenormalMode::IEEE</a>, <a href="#afbfd19ed4794030f4e05a6558d4aba0f">isKnownNeverPosSubnormal</a>, <a href="#a94dcc8e868472796e4448759abde299f">isKnownNeverPosZero</a>, <a href="#a2c951d72721a5640003806474c07f73d">isKnownNeverSubnormal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/denormalmode/#a29b26e3ae30f3f6ec4106ff181282893a7de61db082dcdc6e8d34d1c5fd2e9757">llvm::DenormalMode::PositiveZero</a> and <a href="/web-llvm/docs/api/structs/llvm/denormalmode/#a29b26e3ae30f3f6ec4106ff181282893a40bc80ae1d362a1461703637e946cbd8">llvm::DenormalMode::PreserveSign</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>.</p>

</div>
</div>

### isKnownNeverLogicalZero() {#abb9838786d5dc284bd667d28c1ee1004}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool KnownFPClass::isKnownNeverLogicalZero (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if it's know this can never be interpreted as a zero.</p>


<p>This extends isKnownNeverZero to cover the case where the assumed floating-point mode for the function interprets denormals as zero.</p>


<p>Declaration at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>, definition at line 4420 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp">ValueTracking.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a1e4abcca994509a418f46ea73cad6d54">inputDenormalIsIEEE</a>, <a href="#a2c951d72721a5640003806474c07f73d">isKnownNeverSubnormal</a> and <a href="#a1c00cb98413fb8b5178256b0ceaf8387">isKnownNeverZero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>.</p>

</div>
</div>

### isKnownNeverNaN() {#a9ace8a5baa7d3c3ad3639fc1e71558bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::KnownFPClass::isKnownNeverNaN ()</td>
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

<p>Return true if it's known this can never be a nan.</p>

<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dafe1646e5477c571f7791c524b54b11fe">llvm::fcNan</a> and <a href="#aa0fbe688ffb115395a2665499c0639a2">isKnownNever</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a982e49c60a2c0180bce8a7f0914c9ce3">llvm::InstCombinerImpl::fmulByZeroIsZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a42c8f0b3d870c96030032b8ed8a2a1e3">llvm::isKnownNeverInfOrNaN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb004c066abda7e0738004a08bc1827f">llvm::isKnownNeverNaN</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a110a350e37f3cc2ed2c603c3efde0a30">simplifyFCmpInst</a>.</p>

</div>
</div>

### isKnownNeverNegInfinity() {#a90ee18f9caf7e7885f6cc1cd526f4ae4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::KnownFPClass::isKnownNeverNegInfinity ()</td>
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

<p>Return true if it's known this can never be -infinity.</p>

<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da3ab665df1666568d7eac3b1373106638">llvm::fcNegInf</a> and <a href="#aa0fbe688ffb115395a2665499c0639a2">isKnownNever</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>.</p>

</div>
</div>

### isKnownNeverNegSubnormal() {#a925cfb1289b0d1de226f826d5f036cd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::KnownFPClass::isKnownNeverNegSubnormal ()</td>
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

<p>Return true if it's known this can never be a negative subnormal.</p>

<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da023ad3d9b33a1af5eb90b8b543fb3ccb">llvm::fcNegSubnormal</a> and <a href="#aa0fbe688ffb115395a2665499c0639a2">isKnownNever</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a> and <a href="#a470d18ba72758ba86e30c5d46de5e2d7">isKnownNeverLogicalNegZero</a>.</p>

</div>
</div>

### isKnownNeverNegZero() {#ab0028c1e6f393070ccfd9e65c6c41633}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::KnownFPClass::isKnownNeverNegZero ()</td>
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

<p>Return true if it's known this can never be a negative zero.</p>


<p>This means a literal -0 and does not include denormal inputs implicitly treated as -0.</p>


<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da1e8072411cd3959aa091c3cae8006dc0">llvm::fcNegZero</a> and <a href="#aa0fbe688ffb115395a2665499c0639a2">isKnownNever</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad6e2d414c6580430f5f84ee467630f65">llvm::cannotBeNegativeZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a> and <a href="#a470d18ba72758ba86e30c5d46de5e2d7">isKnownNeverLogicalNegZero</a>.</p>

</div>
</div>

### isKnownNeverPosInfinity() {#accb142befbb571f6388b1e5d6360095d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::KnownFPClass::isKnownNeverPosInfinity ()</td>
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

<p>Return true if it's known this can never be +infinity.</p>

<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dada0d259988860d7a2f882aa40b25fee1">llvm::fcPosInf</a> and <a href="#aa0fbe688ffb115395a2665499c0639a2">isKnownNever</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>.</p>

</div>
</div>

### isKnownNeverPosSubnormal() {#afbfd19ed4794030f4e05a6558d4aba0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::KnownFPClass::isKnownNeverPosSubnormal ()</td>
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

<p>Return true if it's known this can never be a positive subnormal.</p>

<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dad0940edb5f5bf512669b72928b527d0c">llvm::fcPosSubnormal</a> and <a href="#aa0fbe688ffb115395a2665499c0639a2">isKnownNever</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a> and <a href="#a506835c101376856be7c584e0e63fbb8">isKnownNeverLogicalPosZero</a>.</p>

</div>
</div>

### isKnownNeverPosZero() {#a94dcc8e868472796e4448759abde299f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::KnownFPClass::isKnownNeverPosZero ()</td>
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

<p>Return true if it's known this can never be a literal positive zero.</p>

<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da7ace586671df3e62fa392d5144a8b3da">llvm::fcPosZero</a> and <a href="#aa0fbe688ffb115395a2665499c0639a2">isKnownNever</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a> and <a href="#a506835c101376856be7c584e0e63fbb8">isKnownNeverLogicalPosZero</a>.</p>

</div>
</div>

### isKnownNeverSubnormal() {#a2c951d72721a5640003806474c07f73d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::KnownFPClass::isKnownNeverSubnormal ()</td>
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

<p>Return true if it's known this can never be a subnormal.</p>

<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da449c8fca7f540cc314102a67944fcd6e">llvm::fcSubnormal</a> and <a href="#aa0fbe688ffb115395a2665499c0639a2">isKnownNever</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a84e5cad6b96b065fe2b8f1df5fcfb82c">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::canIgnoreDenormalInput</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="#a506835c101376856be7c584e0e63fbb8">isKnownNeverLogicalPosZero</a> and <a href="#abb9838786d5dc284bd667d28c1ee1004">isKnownNeverLogicalZero</a>.</p>

</div>
</div>

### isKnownNeverZero() {#a1c00cb98413fb8b5178256b0ceaf8387}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::KnownFPClass::isKnownNeverZero ()</td>
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

<p>Return true if it's known this can never be a zero.</p>


<p>This means a literal [+-]0, and does not include denormal inputs implicitly treated as [+-]0.</p>


<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dab6ede72b2b2219068b9bb89732d24e2f">llvm::fcZero</a> and <a href="#aa0fbe688ffb115395a2665499c0639a2">isKnownNever</a>.</p>


<p>Referenced by <a href="#abb9838786d5dc284bd667d28c1ee1004">isKnownNeverLogicalZero</a>.</p>

</div>
</div>

### isUnknown() {#a8a91c2235d984a1d9d19df3cc1bedd9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::KnownFPClass::isUnknown ()</td>
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



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dabf7829a22591343ad790b1357955a7df">llvm::fcAllFlags</a>, <a href="#a0200a1522bbde43a85224153d1bb08fe">KnownFPClasses</a> and <a href="#a98b802f50f0dfde19089adfd2f4f2f7b">SignBit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>.</p>

</div>
</div>

### knownNot() {#a186c609abd2d8d453e0889b0c0cd7549}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::KnownFPClass::knownNot (<a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1d">FPClassTest</a> RuleOut)</td>
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



<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dafe1646e5477c571f7791c524b54b11fe">llvm::fcNan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dabd5ff30619fc341f566f44037f42587e">llvm::fcNegative</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da4c071eac84ba221262ca010533f643db">llvm::fcPositive</a>, <a href="#aa0fbe688ffb115395a2665499c0639a2">isKnownNever</a>, <a href="#a0200a1522bbde43a85224153d1bb08fe">KnownFPClasses</a> and <a href="#a98b802f50f0dfde19089adfd2f4f2f7b">SignBit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a89dba3d15d8a7ca93983e8779f315b6b">computeKnownFPClassForFPTrunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a62d1d406e2f2d0fa764c636a1fe7e38a">computeKnownFPClassFromCond</a> and <a href="#abd6308f41af5228d2cf1f03104be6613">propagateNaN</a>.</p>

</div>
</div>

### propagateCanonicalizingSrc() {#a7c8dbd5978c087ccc28ed20be2c63cab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void KnownFPClass::propagateCanonicalizingSrc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownfpclass">KnownFPClass</a> &amp; Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Report known classes if <span class="doxyComputerOutput">Src</span> is evaluated through a potentially canonicalizing operation.</p>


<p>We can assume signaling nans will not be introduced, but cannot assume a denormal will be flushed under FTZ/DAZ.</p>


<p>This assumes a copy-like operation and will replace any currently known information.</p>


<p>Declaration at line 483 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>, definition at line 4485 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp">ValueTracking.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a832be183f243ae315e8bdd00b9d9acd0">propagateDenormal</a> and <a href="#abd6308f41af5228d2cf1f03104be6613">propagateNaN</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>.</p>

</div>
</div>

### propagateDenormal() {#a832be183f243ae315e8bdd00b9d9acd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void KnownFPClass::propagateDenormal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownfpclass">KnownFPClass</a> &amp; Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Propagate knowledge from a source value that could be a denormal or zero.</p>


<p>We have to be conservative since output flushing is not guaranteed, so known-never-zero may not hold.</p>


<p>This assumes a copy-like operation and will replace any currently known information.</p>


<p>Declaration at line 475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>, definition at line 4456 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp">ValueTracking.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/denormalmode/#a29b26e3ae30f3f6ec4106ff181282893ab6083e266013055b6c2ef85b1e47444c">llvm::DenormalMode::Dynamic</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da1e8072411cd3959aa091c3cae8006dc0">llvm::fcNegZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da7ace586671df3e62fa392d5144a8b3da">llvm::fcPosZero</a>, <a href="/web-llvm/docs/api/structs/llvm/denormalmode/#afc06bc91a5873ec7efe616b733f2c5c8">llvm::DenormalMode::getIEEE</a>, <a href="/web-llvm/docs/api/structs/llvm/denormalmode/#a3c136ee901a0b48c5bf4be4b29d58b58">llvm::DenormalMode::getPositiveZero</a>, <a href="#a0200a1522bbde43a85224153d1bb08fe">KnownFPClasses</a> and <a href="/web-llvm/docs/api/structs/llvm/denormalmode/#a29b26e3ae30f3f6ec4106ff181282893a7de61db082dcdc6e8d34d1c5fd2e9757">llvm::DenormalMode::PositiveZero</a>.</p>


<p>Referenced by <a href="#a7c8dbd5978c087ccc28ed20be2c63cab">propagateCanonicalizingSrc</a>.</p>

</div>
</div>

### propagateNaN() {#abd6308f41af5228d2cf1f03104be6613}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::KnownFPClass::propagateNaN (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownfpclass">KnownFPClass</a> &amp; Src, bool PreserveSign=false)</td>
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



<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dafe1646e5477c571f7791c524b54b11fe">llvm::fcNan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da9d366dced7a639841b0ced40c82ccb28">llvm::fcSNan</a>, <a href="#a186c609abd2d8d453e0889b0c0cd7549">knownNot</a> and <a href="#a98b802f50f0dfde19089adfd2f4f2f7b">SignBit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a89dba3d15d8a7ca93983e8779f315b6b">computeKnownFPClassForFPTrunc</a> and <a href="#a7c8dbd5978c087ccc28ed20be2c63cab">propagateCanonicalizingSrc</a>.</p>

</div>
</div>

### resetAll() {#a11eb035a176c001e90e4ff6e242155e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::KnownFPClass::resetAll ()</td>
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



<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>.</p>

</div>
</div>

### signBitIsZeroOrNaN() {#aef3eb6ab7234059d2b26da34c604a752}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::KnownFPClass::signBitIsZeroOrNaN ()</td>
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

<p>Return true if the sign bit must be 0, ignoring the sign of nans.</p>

<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dabd5ff30619fc341f566f44037f42587e">llvm::fcNegative</a> and <a href="#aa0fbe688ffb115395a2665499c0639a2">isKnownNever</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a982e49c60a2c0180bce8a7f0914c9ce3">llvm::InstCombinerImpl::fmulByZeroIsZero</a>.</p>

</div>
</div>

### signBitMustBeOne() {#ac1a2e2775908a5f77b301701a53d6830}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::KnownFPClass::signBitMustBeOne ()</td>
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

<p>Assume the sign bit is one.</p>

<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dafe1646e5477c571f7791c524b54b11fe">llvm::fcNan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dabd5ff30619fc341f566f44037f42587e">llvm::fcNegative</a>, <a href="#a0200a1522bbde43a85224153d1bb08fe">KnownFPClasses</a> and <a href="#a98b802f50f0dfde19089adfd2f4f2f7b">SignBit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a62d1d406e2f2d0fa764c636a1fe7e38a">computeKnownFPClassFromCond</a>.</p>

</div>
</div>

### signBitMustBeZero() {#ac5ff8a86f05bd1277209099b7cd6c46b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::KnownFPClass::signBitMustBeZero ()</td>
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

<p>Assume the sign bit is zero.</p>

<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dafe1646e5477c571f7791c524b54b11fe">llvm::fcNan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da4c071eac84ba221262ca010533f643db">llvm::fcPositive</a>, <a href="#a0200a1522bbde43a85224153d1bb08fe">KnownFPClasses</a> and <a href="#a98b802f50f0dfde19089adfd2f4f2f7b">SignBit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a62d1d406e2f2d0fa764c636a1fe7e38a">computeKnownFPClassFromCond</a> and <a href="#acb65a04b87935b43786ff09f17840ac0">fabs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### KnownFPClasses {#a0200a1522bbde43a85224153d1bb08fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FPClassTest llvm::KnownFPClass::KnownFPClasses = <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dabf7829a22591343ad790b1357955a7df">fcAllFlags</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Floating-point classes the value could be one of.</p>

<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="#a21ba2e0b3e29866fac506873ee5c1a60">copysign</a>, <a href="#acb65a04b87935b43786ff09f17840ac0">fabs</a>, <a href="#a61b974f96f2e5ccbf86376dc849e065d">fneg</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanofpclassimpl/#a15b5bdf6941d33266e2377777aebb9d8">anonymous{AttributorAttributes.cpp}::AANoFPClassImpl::initialize</a>, <a href="#aa0fbe688ffb115395a2665499c0639a2">isKnownNever</a>, <a href="#a8a91c2235d984a1d9d19df3cc1bedd9c">isUnknown</a>, <a href="#a186c609abd2d8d453e0889b0c0cd7549">knownNot</a>, <a href="#adc8217e29c481acbf29146b541785128">operator==</a>, <a href="#a5a3df02b0009994281307116977ee86a">operator|=</a>, <a href="#a832be183f243ae315e8bdd00b9d9acd0">propagateDenormal</a>, <a href="#ac1a2e2775908a5f77b301701a53d6830">signBitMustBeOne</a>, <a href="#ac5ff8a86f05bd1277209099b7cd6c46b">signBitMustBeZero</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a98e8d1806c78a1e84fa32e50a41a8a62">llvm::InstCombinerImpl::SimplifyDemandedUseFPClass</a>.</p>

</div>
</div>

### SignBit {#a98b802f50f0dfde19089adfd2f4f2f7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;bool&gt; llvm::KnownFPClass::SignBit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>std::nullopt if the sign bit is unknown, true if the sign bit is definitely set or false if the sign bit is definitely unset.</p>

<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ace654b9b621b04f88a6611c00e815880">llvm::computeKnownFPSignBit</a>, <a href="#a21ba2e0b3e29866fac506873ee5c1a60">copysign</a>, <a href="#a61b974f96f2e5ccbf86376dc849e065d">fneg</a>, <a href="#a8a91c2235d984a1d9d19df3cc1bedd9c">isUnknown</a>, <a href="#a186c609abd2d8d453e0889b0c0cd7549">knownNot</a>, <a href="#adc8217e29c481acbf29146b541785128">operator==</a>, <a href="#a5a3df02b0009994281307116977ee86a">operator|=</a>, <a href="#abd6308f41af5228d2cf1f03104be6613">propagateNaN</a>, <a href="#ac1a2e2775908a5f77b301701a53d6830">signBitMustBeOne</a>, <a href="#ac5ff8a86f05bd1277209099b7cd6c46b">signBitMustBeZero</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a5b47854a993004418cb56068fe2dd9dd">simplifyFMAFMul</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### OrderedGreaterThanZeroMask {#a1520514ea4aab2457884e02e3c90c05b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FPClassTest llvm::KnownFPClass::OrderedGreaterThanZeroMask</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
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
      <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dad0940edb5f5bf512669b72928b527d0c">fcPosSubnormal</a> | <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da052ace75708c251359ff22dd036417a6">fcPosNormal</a> | <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dada0d259988860d7a2f882aa40b25fee1">fcPosInf</a>
</div>
</dd>
</dl>

<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>Referenced by <a href="#a0d341e86d22b4ec6b4eca5642d0ed20d">cannotBeOrderedGreaterThanZero</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>.</p>

</div>
</div>

### OrderedLessThanZeroMask {#a166b63a9217b936dc956f6b65de7602a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FPClassTest llvm::KnownFPClass::OrderedLessThanZeroMask</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
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
      <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da023ad3d9b33a1af5eb90b8b543fb3ccb">fcNegSubnormal</a> | <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dab003a118cd0b76a814ba4dfc7077034a">fcNegNormal</a> | <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da3ab665df1666568d7eac3b1373106638">fcNegInf</a>
</div>
</dd>
</dl>

<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad164187e4f9f1fc16a86d166b9793ac3">llvm::cannotBeOrderedLessThanZero</a>, <a href="#ac068bb13883a326befa8b10d45cb52a2">cannotBeOrderedLessThanZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a89dba3d15d8a7ca93983e8779f315b6b">computeKnownFPClassForFPTrunc</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a110a350e37f3cc2ed2c603c3efde0a30">simplifyFCmpInst</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp">ValueTracking.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
