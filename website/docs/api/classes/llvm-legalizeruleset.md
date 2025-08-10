---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/legalizeruleset
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LegalizeRuleSet` Class



## Declaration

<div class="doxyDeclaration">
class llvm::LegalizeRuleSet { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">llvm/CodeGen/GlobalISel/LegalizerInfo.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79cedeeef6030fcad3e98d2ef47b99a0">isAliasedByAnother</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3b653087a0b463517033883f99368de">setIsAliasedByAnother</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28373d4ba75160e40948a40157cacb5c">aliasTo</a> (unsigned Opcode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac558716370cd7cd96558d5d04508e23b">getAlias</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1f70f6956b2338cfdc8e8316b104078">immIdx</a> (unsigned ImmIdx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6dcfac5a30e4050e3ac204f27062fe6">legalIf</a> (LegalityPredicate Predicate)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The instruction is legal if predicate is true. <a href="#af6dcfac5a30e4050e3ac204f27062fe6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c27c69ac65f9d4937858c10288a17f6">legalFor</a> (std::initializer_list&lt; LLT &gt; Types)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The instruction is legal when type index 0 is any type in the given list. <a href="#a1c27c69ac65f9d4937858c10288a17f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41d38ac5e9c5bb8ec878a41fadcf685f">legalFor</a> (bool Pred, std::initializer_list&lt; LLT &gt; Types)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae97f8857ebeba8f3c96dcd1a2b2d32b">legalFor</a> (std::initializer_list&lt; std::pair&lt; LLT, LLT &gt; &gt; Types)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The instruction is legal when type indexes 0 and 1 is any type pair in the given list. <a href="#aae97f8857ebeba8f3c96dcd1a2b2d32b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2b2a7e8c3015c7ec53c53bcfe673e7d">legalFor</a> (bool Pred, std::initializer_list&lt; std::pair&lt; LLT, LLT &gt; &gt; Types)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a232420dcfc34bce51b5a1590e6e1e6db">legalFor</a> (bool Pred, std::initializer_list&lt; std::tuple&lt; LLT, LLT, LLT &gt; &gt; Types)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaca31f1b00db114db16d186cfeb53135">legalForTypeWithAnyImm</a> (std::initializer_list&lt; LLT &gt; Types)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The instruction is legal when type index 0 is any type in the given list and imm index 0 is anything. <a href="#aaca31f1b00db114db16d186cfeb53135">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62f037f0d9f2c32d319fefcb5f3475e3">legalForTypeWithAnyImm</a> (std::initializer_list&lt; std::pair&lt; LLT, LLT &gt; &gt; Types)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebb3b5876088ebfd2d003d68f7fb4b07">legalForTypesWithMemDesc</a> (std::initializer_list&lt; LegalityPredicates::TypePairAndMemDesc &gt; TypesAndMemDesc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The instruction is legal when type indexes 0 and 1 along with the memory size and minimum alignment is any type and size tuple in the given list. <a href="#aebb3b5876088ebfd2d003d68f7fb4b07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4c02bcf9d3bfdee70f097d0b6aeb9f3">legalForCartesianProduct</a> (std::initializer_list&lt; LLT &gt; Types)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The instruction is legal when type indexes 0 and 1 are both in the given list. <a href="#ae4c02bcf9d3bfdee70f097d0b6aeb9f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a450f90930a4b8e27bdcbc0909b7297cd">legalForCartesianProduct</a> (std::initializer_list&lt; LLT &gt; Types0, std::initializer_list&lt; LLT &gt; Types1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The instruction is legal when type indexes 0 and 1 are both their respective lists. <a href="#a450f90930a4b8e27bdcbc0909b7297cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b2dfae822a01a81c33527832d182e60">legalForCartesianProduct</a> (std::initializer_list&lt; LLT &gt; Types0, std::initializer_list&lt; LLT &gt; Types1, std::initializer_list&lt; LLT &gt; Types2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The instruction is legal when type indexes 0, 1, and 2 are both their respective lists. <a href="#a7b2dfae822a01a81c33527832d182e60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab250f5144d04471b35f7fc229dc9da5c">alwaysLegal</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3128e17013a7e7dd6a855d0b00ad60f9">bitcastIf</a> (LegalityPredicate Predicate, LegalizeMutation Mutation)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The specified type index is coerced if predicate is true. <a href="#a3128e17013a7e7dd6a855d0b00ad60f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a836d4faf3f9f04f1f04cc5f6de3c03">lower</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The instruction is lowered. <a href="#a6a836d4faf3f9f04f1f04cc5f6de3c03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76a7807072af618c3ac80dd8d569deba">lowerIf</a> (LegalityPredicate Predicate)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The instruction is lowered if predicate is true. <a href="#a76a7807072af618c3ac80dd8d569deba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9a56d2d5ddaa43684ecf2194b93e20e">lowerIf</a> (LegalityPredicate Predicate, LegalizeMutation Mutation)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The instruction is lowered if predicate is true. <a href="#ae9a56d2d5ddaa43684ecf2194b93e20e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eec582df34bb1c63e8666b41ff561ec">lowerFor</a> (std::initializer_list&lt; LLT &gt; Types)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The instruction is lowered when type index 0 is any type in the given list. <a href="#a6eec582df34bb1c63e8666b41ff561ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4abfd57207ad9be3316dbed273935db3">lowerFor</a> (std::initializer_list&lt; LLT &gt; Types, LegalizeMutation Mutation)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The instruction is lowered when type index 0 is any type in the given list. <a href="#a4abfd57207ad9be3316dbed273935db3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64906287eb2cff470856bc6710512be4">lowerFor</a> (std::initializer_list&lt; std::pair&lt; LLT, LLT &gt; &gt; Types)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The instruction is lowered when type indexes 0 and 1 is any type pair in the given list. <a href="#a64906287eb2cff470856bc6710512be4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af61696d493cba381e1fbaf2513370ce1">lowerFor</a> (std::initializer_list&lt; std::pair&lt; LLT, LLT &gt; &gt; Types, LegalizeMutation Mutation)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The instruction is lowered when type indexes 0 and 1 is any type pair in the given list. <a href="#af61696d493cba381e1fbaf2513370ce1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae84a4659e822b885098d6ebb11633160">lowerForCartesianProduct</a> (std::initializer_list&lt; LLT &gt; Types0, std::initializer_list&lt; LLT &gt; Types1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The instruction is lowered when type indexes 0 and 1 are both in their respective lists. <a href="#ae84a4659e822b885098d6ebb11633160">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad46ece57d9d8d07b1eb137cd933ff1f">lowerForCartesianProduct</a> (std::initializer_list&lt; LLT &gt; Types0, std::initializer_list&lt; LLT &gt; Types1, std::initializer_list&lt; LLT &gt; Types2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The instruction is lowered when type indexes 0, 1, and 2 are all in their respective lists. <a href="#aad46ece57d9d8d07b1eb137cd933ff1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31342428708a575fd8ed06209949d9dc">libcall</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The instruction is emitted as a library call. <a href="#a31342428708a575fd8ed06209949d9dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec5f2318f80808e02d249d59656da194">libcallIf</a> (LegalityPredicate Predicate)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Like legalIf, but for the Libcall action. <a href="#aec5f2318f80808e02d249d59656da194">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32e4ff098c95890246047dc1ddf5a065">libcallFor</a> (std::initializer_list&lt; LLT &gt; Types)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1737a08f305f7b21fe313048b25f09c">libcallFor</a> (bool Pred, std::initializer_list&lt; LLT &gt; Types)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b66d6f0693aec5949568c067d0db21f">libcallFor</a> (std::initializer_list&lt; std::pair&lt; LLT, LLT &gt; &gt; Types)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1dec3831eac71a7c07af99756fbc459">libcallFor</a> (bool Pred, std::initializer_list&lt; std::pair&lt; LLT, LLT &gt; &gt; Types)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40aebefc69962dcb020706b2829e0159">libcallForCartesianProduct</a> (std::initializer_list&lt; LLT &gt; Types)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a860c7e05708e25e7cf1034f50c21f10e">libcallForCartesianProduct</a> (std::initializer_list&lt; LLT &gt; Types0, std::initializer_list&lt; LLT &gt; Types1)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99e1a648bb3a1018aed19e77cae2203c">widenScalarIf</a> (LegalityPredicate Predicate, LegalizeMutation Mutation)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Widen the scalar to the one selected by the mutation if the predicate is true. <a href="#a99e1a648bb3a1018aed19e77cae2203c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a80f26baa5258688f20cafc7efac05f">narrowScalarIf</a> (LegalityPredicate Predicate, LegalizeMutation Mutation)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Narrow the scalar to the one selected by the mutation if the predicate is true. <a href="#a6a80f26baa5258688f20cafc7efac05f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d4489897a525246ea6f1e924ac20245">narrowScalarFor</a> (std::initializer_list&lt; std::pair&lt; LLT, LLT &gt; &gt; Types, LegalizeMutation Mutation)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Narrow the scalar, specified in mutation, when type indexes 0 and 1 is any type pair in the given list. <a href="#a6d4489897a525246ea6f1e924ac20245">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6baff39b32f5cec5ea417cba89f077ac">moreElementsIf</a> (LegalityPredicate Predicate, LegalizeMutation Mutation)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add more elements to reach the type selected by the mutation if the predicate is true. <a href="#a6baff39b32f5cec5ea417cba89f077ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2650717a05ef92e13ecc9d1f290eabd9">fewerElementsIf</a> (LegalityPredicate Predicate, LegalizeMutation Mutation)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove elements to reach the type selected by the mutation if the predicate is true. <a href="#a2650717a05ef92e13ecc9d1f290eabd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2034405f0aed7259ed9999053c3f591d">unsupported</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The instruction is unsupported. <a href="#a2034405f0aed7259ed9999053c3f591d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a916cd5bc69b2a149600ab1488c047bc7">unsupportedIf</a> (LegalityPredicate Predicate)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4125d6153339fbe5614602c31c5500d3">unsupportedFor</a> (std::initializer_list&lt; LLT &gt; Types)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac87cf76397c445a62260d503afd96cf6">unsupportedIfMemSizeNotPow2</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a479d3f2cd21c2250ae84ec2b06be816f">lowerIfMemSizeNotPow2</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower a memory operation if the memory size, rounded to bytes, is not a power of 2. <a href="#a479d3f2cd21c2250ae84ec2b06be816f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5361d650c0e9459b1dc4c3afec8251ef">lowerIfMemSizeNotByteSizePow2</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower a memory operation if the memory access size is not a round power of 2 byte size. <a href="#a5361d650c0e9459b1dc4c3afec8251ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acda429561493e08ee5cef54f26a1224c">customIf</a> (LegalityPredicate Predicate)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc001d042e6a7093a6954b2d9ff18029">customFor</a> (std::initializer_list&lt; LLT &gt; Types)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2358b8c8275b0a018564c2aad580baf">customFor</a> (bool Pred, std::initializer_list&lt; LLT &gt; Types)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeff7d5df446c2798d2360f5a1a305063">customFor</a> (std::initializer_list&lt; std::pair&lt; LLT, LLT &gt; &gt; Types)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The instruction is custom when type indexes 0 and 1 is any type pair in the given list. <a href="#aeff7d5df446c2798d2360f5a1a305063">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ecf9e98cf230939b28df8866ead625c">customFor</a> (bool Pred, std::initializer_list&lt; std::pair&lt; LLT, LLT &gt; &gt; Types)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ad690ef8db6cd914cef1b3aa39bc15f">customForCartesianProduct</a> (std::initializer_list&lt; LLT &gt; Types)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ad717038b549ad0b3a6d009ab3b4d79">customForCartesianProduct</a> (std::initializer_list&lt; LLT &gt; Types0, std::initializer_list&lt; LLT &gt; Types1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The instruction is custom when type indexes 0 and 1 are both in their respective lists. <a href="#a5ad717038b549ad0b3a6d009ab3b4d79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace6b6d858967a684670864748cbedbea">customForCartesianProduct</a> (std::initializer_list&lt; LLT &gt; Types0, std::initializer_list&lt; LLT &gt; Types1, std::initializer_list&lt; LLT &gt; Types2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The instruction is custom when type indexes 0, 1, and 2 are all in their respective lists. <a href="#ace6b6d858967a684670864748cbedbea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80f41417117f537cd147aaee97aecb1e">custom</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unconditionally custom lower. <a href="#a80f41417117f537cd147aaee97aecb1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adef498f01eb5d7c19ac40cd3b302d09e">widenScalarToNextPow2</a> (unsigned TypeIdx, unsigned MinSize=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Widen the scalar to the next power of two that is at least MinSize. <a href="#adef498f01eb5d7c19ac40cd3b302d09e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afde49505d22ecf8f8b01f47f6eaa0299">widenScalarToNextMultipleOf</a> (unsigned TypeIdx, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Widen the scalar to the next multiple of Size. <a href="#afde49505d22ecf8f8b01f47f6eaa0299">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af52cd47605369d735f4d6e6b24faf003">widenScalarOrEltToNextPow2</a> (unsigned TypeIdx, unsigned MinSize=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Widen the scalar or vector element type to the next power of two that is at least MinSize. <a href="#af52cd47605369d735f4d6e6b24faf003">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a173a5c5c1e9992339faedc21b5954918">widenScalarOrEltToNextPow2OrMinSize</a> (unsigned TypeIdx, unsigned MinSize=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Widen the scalar or vector element type to the next power of two that is at least MinSize. <a href="#a173a5c5c1e9992339faedc21b5954918">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e6eeb6a4185d14eed4d84a59ffa05c2">narrowScalar</a> (unsigned TypeIdx, LegalizeMutation Mutation)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf80c6b70ec078f749c51a5e64b4393d">scalarize</a> (unsigned TypeIdx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7369e2b43abeda933406d7b9ed83500c">scalarizeIf</a> (LegalityPredicate Predicate, unsigned TypeIdx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3453ec1df80a077b489ea76fee965967">minScalarOrElt</a> (unsigned TypeIdx, const LLT Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Ensure the scalar or element is at least as wide as Ty. <a href="#a3453ec1df80a077b489ea76fee965967">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9673f01ba4c77779f3361b426653d257">minScalarOrEltIf</a> (LegalityPredicate Predicate, unsigned TypeIdx, const LLT Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Ensure the scalar or element is at least as wide as Ty. <a href="#a9673f01ba4c77779f3361b426653d257">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a430225b2e66451c27e9f4e9462be7df1">widenVectorEltsToVectorMinSize</a> (unsigned TypeIdx, unsigned VectorSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Ensure the vector size is at least as wide as VectorSize by promoting the element. <a href="#a430225b2e66451c27e9f4e9462be7df1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a009564405d1037574152ee039cd04b9f">minScalar</a> (unsigned TypeIdx, const LLT Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Ensure the scalar is at least as wide as Ty. <a href="#a009564405d1037574152ee039cd04b9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a562998853f3ac3eb154887ff77180c73">minScalar</a> (bool Pred, unsigned TypeIdx, const LLT Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0cb74dd5e94daaea299005867eac63d">minScalarIf</a> (LegalityPredicate Predicate, unsigned TypeIdx, const LLT Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Ensure the scalar is at least as wide as Ty if condition is met. <a href="#af0cb74dd5e94daaea299005867eac63d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefcfce4300cbfd94417983bc6317e27a">maxScalarOrElt</a> (unsigned TypeIdx, const LLT Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Ensure the scalar is at most as wide as Ty. <a href="#aefcfce4300cbfd94417983bc6317e27a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33e181da566d1ebb7556f172888c3b92">maxScalar</a> (unsigned TypeIdx, const LLT Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Ensure the scalar is at most as wide as Ty. <a href="#a33e181da566d1ebb7556f172888c3b92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd56c0d001ca90095d61c52099f90cd3">maxScalarIf</a> (LegalityPredicate Predicate, unsigned TypeIdx, const LLT Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Conditionally limit the maximum size of the scalar. <a href="#acd56c0d001ca90095d61c52099f90cd3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7adc16cc9bc8db5fd3c8a6798a846ab0">clampScalar</a> (unsigned TypeIdx, const LLT MinTy, const LLT MaxTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Limit the range of scalar sizes to MinTy and MaxTy. <a href="#a7adc16cc9bc8db5fd3c8a6798a846ab0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07c410b3089ea0fbcfbffecae19b2abb">clampScalar</a> (bool Pred, unsigned TypeIdx, const LLT MinTy, const LLT MaxTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2660bbe870c09b7a2cc5a24c8bcd97ae">clampScalarOrElt</a> (unsigned TypeIdx, const LLT MinTy, const LLT MaxTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Limit the range of scalar sizes to MinTy and MaxTy. <a href="#a2660bbe870c09b7a2cc5a24c8bcd97ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8abe7c10c8bfc8f9c308c89adc98330c">minScalarSameAs</a> (unsigned TypeIdx, unsigned LargeTypeIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Widen the scalar to match the size of another. <a href="#a8abe7c10c8bfc8f9c308c89adc98330c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d8b8e18977cd5ba53ec89aa06bd7506">maxScalarSameAs</a> (unsigned TypeIdx, unsigned NarrowTypeIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Narrow the scalar to match the size of another. <a href="#a0d8b8e18977cd5ba53ec89aa06bd7506">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a236c4562fff94fbec23fd35c0b5257a1">scalarSameSizeAs</a> (unsigned TypeIdx, unsigned SameSizeIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Change the type <span class="doxyComputerOutput">TypeIdx</span> to have the same scalar size as type <span class="doxyComputerOutput">SameSizeIdx</span>. <a href="#a236c4562fff94fbec23fd35c0b5257a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4aca13e5c1613b22b7c3c9411895fdae">minScalarEltSameAsIf</a> (LegalityPredicate Predicate, unsigned TypeIdx, unsigned LargeTypeIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Conditionally widen the scalar or elt to match the size of another. <a href="#a4aca13e5c1613b22b7c3c9411895fdae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d446dfaa94c6ec0729feaa73d5b6c88">maxScalarEltSameAsIf</a> (LegalityPredicate Predicate, unsigned TypeIdx, unsigned SmallTypeIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Conditionally narrow the scalar or elt to match the size of another. <a href="#a1d446dfaa94c6ec0729feaa73d5b6c88">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a592ea5db9394c272d8354d931134f16c">moreElementsToNextPow2</a> (unsigned TypeIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add more elements to the vector to reach the next power of two. <a href="#a592ea5db9394c272d8354d931134f16c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3da19f78bfc264962a18568ea4b8d6c7">clampMinNumElements</a> (unsigned TypeIdx, const LLT EltTy, unsigned MinElements)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Limit the number of elements in EltTy vectors to at least MinElements. <a href="#a3da19f78bfc264962a18568ea4b8d6c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b80b62a08d65dc70ac57954b7955ca0">alignNumElementsTo</a> (unsigned TypeIdx, const LLT EltTy, unsigned NumElts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set number of elements to nearest larger multiple of NumElts. <a href="#a7b80b62a08d65dc70ac57954b7955ca0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b9d49f459b9596f73c60edab6e92673">clampMaxNumElements</a> (unsigned TypeIdx, const LLT EltTy, unsigned MaxElements)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Limit the number of elements in EltTy vectors to at most MaxElements. <a href="#a3b9d49f459b9596f73c60edab6e92673">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac56e6d7519b8f4f908174aa570bc5e61">clampNumElements</a> (unsigned TypeIdx, const LLT MinTy, const LLT MaxTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Limit the number of elements for the given vectors to at least MinTy's number of elements and at most MaxTy's number of elements. <a href="#ac56e6d7519b8f4f908174aa570bc5e61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a875edaec1f61b358e8026a4b50de8ea8">clampMaxNumElementsStrict</a> (unsigned TypeIdx, const LLT EltTy, unsigned NumElts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Express <span class="doxyComputerOutput">EltTy</span> vectors strictly using vectors with <span class="doxyComputerOutput">NumElts</span> elements (or scalars when <span class="doxyComputerOutput">NumElts</span> equals 1). <a href="#a875edaec1f61b358e8026a4b50de8ea8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3f0867f33edbd5a34f5ed9f23a1975b">fallback</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fallback on the previous implementation. <a href="#aa3f0867f33edbd5a34f5ed9f23a1975b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4a1582478d21b5d91d22fcb5989a0bc">verifyTypeIdxsCoverage</a> (unsigned NumTypeIdxs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if there is no type index which is obviously not handled by the <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> in any way at all. <a href="#af4a1582478d21b5d91d22fcb5989a0bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a333c735ce0e828dfc8e88c8385825b45">verifyImmIdxsCoverage</a> (unsigned NumImmIdxs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if there is no imm index which is obviously not handled by the <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> in any way at all. <a href="#a333c735ce0e828dfc8e88c8385825b45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/legalizeactionstep">LegalizeActionStep</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5b725eb16175a6ebbd75e53d6bc0d2c">apply</a> (const LegalityQuery &amp;Query) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply the ruleset to the given <a href="/web-llvm/docs/api/structs/llvm/legalityquery">LegalityQuery</a>. <a href="#af5b725eb16175a6ebbd75e53d6bc0d2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb8202610e80e780c894a4632998b75f">typeIdx</a> (unsigned TypeIdx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab45d189bce430c639310f764edb724aa">markAllIdxsAsCovered</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa55e44adaf9508fcee1377fa2c13d78d">add</a> (const LegalizeRule &amp;Rule)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9c6bd9030d99996c5529a56a6e3a2d1">actionIf</a> (LegalizeAction Action, LegalityPredicate Predicate)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the given action when the predicate is true. <a href="#af9c6bd9030d99996c5529a56a6e3a2d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1863c137e0a15ad9f2f9ee533ed363a3">actionIf</a> (LegalizeAction Action, LegalityPredicate Predicate, LegalizeMutation Mutation)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the given action when the predicate is true. <a href="#a1863c137e0a15ad9f2f9ee533ed363a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6a933fa6fe21a3ace72c2694bc38e3e">actionFor</a> (LegalizeAction Action, std::initializer_list&lt; LLT &gt; Types)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the given action when type index 0 is any type in the given list. <a href="#ac6a933fa6fe21a3ace72c2694bc38e3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bf495bff8449be06e932ed2c608fc9d">actionFor</a> (LegalizeAction Action, std::initializer_list&lt; LLT &gt; Types, LegalizeMutation Mutation)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the given action when type index 0 is any type in the given list. <a href="#a4bf495bff8449be06e932ed2c608fc9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac431188bd890910c68a37ac300a897d4">actionFor</a> (LegalizeAction Action, std::initializer_list&lt; std::pair&lt; LLT, LLT &gt; &gt; Types)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the given action when type indexes 0 and 1 is any type pair in the given list. <a href="#ac431188bd890910c68a37ac300a897d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b1aa9bb0f97dbf22838835f6d779ede">actionFor</a> (LegalizeAction Action, std::initializer_list&lt; std::tuple&lt; LLT, LLT, LLT &gt; &gt; Types)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbfb41b6245c509daaca5fc9f6082e8f">actionFor</a> (LegalizeAction Action, std::initializer_list&lt; std::pair&lt; LLT, LLT &gt; &gt; Types, LegalizeMutation Mutation)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the given action when type indexes 0 and 1 is any type pair in the given list. <a href="#afbfb41b6245c509daaca5fc9f6082e8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6564543b629d0f2a349dcef0858c4526">actionForTypeWithAnyImm</a> (LegalizeAction Action, std::initializer_list&lt; LLT &gt; Types)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the given action when type index 0 is any type in the given list and imm index 0 is anything. <a href="#a6564543b629d0f2a349dcef0858c4526">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac24b0e82911b564e66957c69535b8d18">actionForTypeWithAnyImm</a> (LegalizeAction Action, std::initializer_list&lt; std::pair&lt; LLT, LLT &gt; &gt; Types)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86c6ea1ba3e831e3a528e0cd7c3fd757">actionForCartesianProduct</a> (LegalizeAction Action, std::initializer_list&lt; LLT &gt; Types)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the given action when type indexes 0 and 1 are both in the given list. <a href="#a86c6ea1ba3e831e3a528e0cd7c3fd757">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa12b8bfce1fe3d2da2385aa7cd1a7b0b">actionForCartesianProduct</a> (LegalizeAction Action, std::initializer_list&lt; LLT &gt; Types0, std::initializer_list&lt; LLT &gt; Types1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the given action when type indexes 0 and 1 are both in their respective lists. <a href="#aa12b8bfce1fe3d2da2385aa7cd1a7b0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6309c6b6eedafa4ed0ccc2ed89e17769">actionForCartesianProduct</a> (LegalizeAction Action, std::initializer_list&lt; LLT &gt; Types0, std::initializer_list&lt; LLT &gt; Types1, std::initializer_list&lt; LLT &gt; Types2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the given action when type indexes 0, 1, and 2 are all in their respective lists. <a href="#a6309c6b6eedafa4ed0ccc2ed89e17769">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7020c49f358e38c5b6ffdffd6b683559">AliasOf</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When non-zero, the opcode we are an alias of. <a href="#a7020c49f358e38c5b6ffdffd6b683559">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcf696bbfa51dbb4ee766ddb653080a0">IsAliasedByAnother</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If true, there is another opcode that aliases this one. <a href="#abcf696bbfa51dbb4ee766ddb653080a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/legalizerule">LegalizeRule</a>, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cda8dd35635913b159a3595f8cb25b8">Rules</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad08bf7bbc8e9c86df9c5074a7ba64082">TypeIdxsCovered</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If bit I is set, this rule set contains a rule that may handle (predicate or perform an action upon (or both)) the type index I. <a href="#ad08bf7bbc8e9c86df9c5074a7ba64082">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cff0f1d59d56ec49f0a1e502eda7afb">ImmIdxsCovered</a> = ...</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34b16ce16c4e92f8d53aa6e0d3c537d3">always</a> (const LegalityQuery &amp;)</td>
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


<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LegalizeRuleSet() {#a39bfb415182d98d5ac687986a2f7a52f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LegalizeRuleSet::LegalizeRuleSet ()</td>
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



<p>Definition at line 586 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Referenced by <a href="#a7b80b62a08d65dc70ac57954b7955ca0">alignNumElementsTo</a>, <a href="#ab250f5144d04471b35f7fc229dc9da5c">alwaysLegal</a>, <a href="#a3128e17013a7e7dd6a855d0b00ad60f9">bitcastIf</a>, <a href="#a3b9d49f459b9596f73c60edab6e92673">clampMaxNumElements</a>, <a href="#a875edaec1f61b358e8026a4b50de8ea8">clampMaxNumElementsStrict</a>, <a href="#a3da19f78bfc264962a18568ea4b8d6c7">clampMinNumElements</a>, <a href="#ac56e6d7519b8f4f908174aa570bc5e61">clampNumElements</a>, <a href="#a07c410b3089ea0fbcfbffecae19b2abb">clampScalar</a>, <a href="#a7adc16cc9bc8db5fd3c8a6798a846ab0">clampScalar</a>, <a href="#a2660bbe870c09b7a2cc5a24c8bcd97ae">clampScalarOrElt</a>, <a href="#a80f41417117f537cd147aaee97aecb1e">custom</a>, <a href="#aa2358b8c8275b0a018564c2aad580baf">customFor</a>, <a href="#a6ecf9e98cf230939b28df8866ead625c">customFor</a>, <a href="#afc001d042e6a7093a6954b2d9ff18029">customFor</a>, <a href="#aeff7d5df446c2798d2360f5a1a305063">customFor</a>, <a href="#a4ad690ef8db6cd914cef1b3aa39bc15f">customForCartesianProduct</a>, <a href="#acda429561493e08ee5cef54f26a1224c">customIf</a>, <a href="#aa3f0867f33edbd5a34f5ed9f23a1975b">fallback</a>, <a href="#a2650717a05ef92e13ecc9d1f290eabd9">fewerElementsIf</a>, <a href="#a41d38ac5e9c5bb8ec878a41fadcf685f">legalFor</a>, <a href="#ab2b2a7e8c3015c7ec53c53bcfe673e7d">legalFor</a>, <a href="#a1c27c69ac65f9d4937858c10288a17f6">legalFor</a>, <a href="#aae97f8857ebeba8f3c96dcd1a2b2d32b">legalFor</a>, <a href="#ae4c02bcf9d3bfdee70f097d0b6aeb9f3">legalForCartesianProduct</a>, <a href="#a450f90930a4b8e27bdcbc0909b7297cd">legalForCartesianProduct</a>, <a href="#a7b2dfae822a01a81c33527832d182e60">legalForCartesianProduct</a>, <a href="#aebb3b5876088ebfd2d003d68f7fb4b07">legalForTypesWithMemDesc</a>, <a href="#aaca31f1b00db114db16d186cfeb53135">legalForTypeWithAnyImm</a>, <a href="#a62f037f0d9f2c32d319fefcb5f3475e3">legalForTypeWithAnyImm</a>, <a href="#af6dcfac5a30e4050e3ac204f27062fe6">legalIf</a>, <a href="#a31342428708a575fd8ed06209949d9dc">libcall</a>, <a href="#ab1737a08f305f7b21fe313048b25f09c">libcallFor</a>, <a href="#a32e4ff098c95890246047dc1ddf5a065">libcallFor</a>, <a href="#aec5f2318f80808e02d249d59656da194">libcallIf</a>, <a href="#a6a836d4faf3f9f04f1f04cc5f6de3c03">lower</a>, <a href="#a6eec582df34bb1c63e8666b41ff561ec">lowerFor</a>, <a href="#a4abfd57207ad9be3316dbed273935db3">lowerFor</a>, <a href="#a64906287eb2cff470856bc6710512be4">lowerFor</a>, <a href="#af61696d493cba381e1fbaf2513370ce1">lowerFor</a>, <a href="#ae84a4659e822b885098d6ebb11633160">lowerForCartesianProduct</a>, <a href="#aad46ece57d9d8d07b1eb137cd933ff1f">lowerForCartesianProduct</a>, <a href="#a76a7807072af618c3ac80dd8d569deba">lowerIf</a>, <a href="#ae9a56d2d5ddaa43684ecf2194b93e20e">lowerIf</a>, <a href="#a5361d650c0e9459b1dc4c3afec8251ef">lowerIfMemSizeNotByteSizePow2</a>, <a href="#a479d3f2cd21c2250ae84ec2b06be816f">lowerIfMemSizeNotPow2</a>, <a href="#a33e181da566d1ebb7556f172888c3b92">maxScalar</a>, <a href="#a1d446dfaa94c6ec0729feaa73d5b6c88">maxScalarEltSameAsIf</a>, <a href="#acd56c0d001ca90095d61c52099f90cd3">maxScalarIf</a>, <a href="#aefcfce4300cbfd94417983bc6317e27a">maxScalarOrElt</a>, <a href="#a0d8b8e18977cd5ba53ec89aa06bd7506">maxScalarSameAs</a>, <a href="#a562998853f3ac3eb154887ff77180c73">minScalar</a>, <a href="#a009564405d1037574152ee039cd04b9f">minScalar</a>, <a href="#a4aca13e5c1613b22b7c3c9411895fdae">minScalarEltSameAsIf</a>, <a href="#af0cb74dd5e94daaea299005867eac63d">minScalarIf</a>, <a href="#a3453ec1df80a077b489ea76fee965967">minScalarOrElt</a>, <a href="#a9673f01ba4c77779f3361b426653d257">minScalarOrEltIf</a>, <a href="#a8abe7c10c8bfc8f9c308c89adc98330c">minScalarSameAs</a>, <a href="#a6baff39b32f5cec5ea417cba89f077ac">moreElementsIf</a>, <a href="#a592ea5db9394c272d8354d931134f16c">moreElementsToNextPow2</a>, <a href="#a6e6eeb6a4185d14eed4d84a59ffa05c2">narrowScalar</a>, <a href="#a6a80f26baa5258688f20cafc7efac05f">narrowScalarIf</a>, <a href="#adf80c6b70ec078f749c51a5e64b4393d">scalarize</a>, <a href="#a7369e2b43abeda933406d7b9ed83500c">scalarizeIf</a>, <a href="#a236c4562fff94fbec23fd35c0b5257a1">scalarSameSizeAs</a>, <a href="#a2034405f0aed7259ed9999053c3f591d">unsupported</a>, <a href="#a4125d6153339fbe5614602c31c5500d3">unsupportedFor</a>, <a href="#a916cd5bc69b2a149600ab1488c047bc7">unsupportedIf</a>, <a href="#ac87cf76397c445a62260d503afd96cf6">unsupportedIfMemSizeNotPow2</a>, <a href="#a99e1a648bb3a1018aed19e77cae2203c">widenScalarIf</a>, <a href="#af52cd47605369d735f4d6e6b24faf003">widenScalarOrEltToNextPow2</a>, <a href="#a173a5c5c1e9992339faedc21b5954918">widenScalarOrEltToNextPow2OrMinSize</a>, <a href="#afde49505d22ecf8f8b01f47f6eaa0299">widenScalarToNextMultipleOf</a>, <a href="#adef498f01eb5d7c19ac40cd3b302d09e">widenScalarToNextPow2</a> and <a href="#a430225b2e66451c27e9f4e9462be7df1">widenVectorEltsToVectorMinSize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### aliasTo() {#a28373d4ba75160e40948a40157cacb5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LegalizeRuleSet::aliasTo (unsigned Opcode)</td>
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



<p>Definition at line 590 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### alignNumElementsTo() {#a7b80b62a08d65dc70ac57954b7955ca0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::alignNumElementsTo (unsigned TypeIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> EltTy, unsigned NumElts)</td>
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

<p>Set number of elements to nearest larger multiple of NumElts.</p>

<p>Definition at line 1222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ad1db89614d919436714d099c99ff12a0">llvm::LLT::isFixedVector</a>, <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a> and <a href="/web-llvm/docs/api/structs/llvm/legalityquery/#ab28fca6f8145be28b70ad89bb0c741b0">llvm::LegalityQuery::Types</a>.</p>


<p>Referenced by <a href="#a875edaec1f61b358e8026a4b50de8ea8">clampMaxNumElementsStrict</a>.</p>

</div>
</div>

### alwaysLegal() {#ab250f5144d04471b35f7fc229dc9da5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::alwaysLegal ()</td>
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



<p>Definition at line 683 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a0c94d0f4f62bd71d26a8020faf70b9f0">llvm::ARMLegalizerInfo::ARMLegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/spirvlegalizerinfo/#a6b747313719abb32e3599ab33501ea17">llvm::SPIRVLegalizerInfo::SPIRVLegalizerInfo</a>.</p>

</div>
</div>

### apply() {#af5b725eb16175a6ebbd75e53d6bc0d2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeActionStep LegalizeRuleSet::apply (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/legalityquery">LegalityQuery</a> &amp; Query)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Apply the ruleset to the given <a href="/web-llvm/docs/api/structs/llvm/legalityquery">LegalityQuery</a>.</p>

<p>Declaration at line 1308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerinfo-cpp">LegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerinfo-cpp/#a629547dc68b8b25d374ecd455b155fbc">hasNoSimpleLoops</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcvsxfmamutate-cpp/#a11cb5628e531251532f100309802a146">Mutation</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerinfo-cpp/#ace2b635ecd7fc6de3eb1f8a95530d08d">mutationIsSane</a> and <a href="/web-llvm/docs/api/structs/llvm/legalityquery/#af17219d2dcf5afc625e5bc40a4483b7d">llvm::LegalityQuery::print</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo/#af3687eafb2772c29aa67ce722c2081fd">llvm::LegalizerInfo::getAction</a>.</p>

</div>
</div>

### bitcastIf() {#a3128e17013a7e7dd6a855d0b00ad60f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::bitcastIf (<a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a> Predicate, <a href="/web-llvm/docs/api/namespaces/llvm/#a31da885e5f80ee375b306057d2a852ab">LegalizeMutation</a> Mutation)</td>
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

<p>The specified type index is coerced if predicate is true.</p>

<p>Definition at line 690 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcvsxfmamutate-cpp/#a11cb5628e531251532f100309802a146">Mutation</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/ppclegalizerinfo/#ae83d1a82dbe98543ff9238ae236b5e20">llvm::PPCLegalizerInfo::PPCLegalizerInfo</a>.</p>

</div>
</div>

### clampMaxNumElements() {#a3b9d49f459b9596f73c60edab6e92673}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::clampMaxNumElements (unsigned TypeIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> EltTy, unsigned MaxElements)</td>
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

<p>Limit the number of elements in EltTy vectors to at most MaxElements.</p>

<p>Definition at line 1241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ad1db89614d919436714d099c99ff12a0">llvm::LLT::isFixedVector</a>, <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae74a60e5edcee0609a1e4fddc62a8a01">llvm::LLT::scalarOrVector</a> and <a href="/web-llvm/docs/api/structs/llvm/legalityquery/#ab28fca6f8145be28b70ad89bb0c741b0">llvm::LegalityQuery::Types</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="#a875edaec1f61b358e8026a4b50de8ea8">clampMaxNumElementsStrict</a>, <a href="#ac56e6d7519b8f4f908174aa570bc5e61">clampNumElements</a> and <a href="/web-llvm/docs/api/classes/llvm/x86legalizerinfo/#abfc562c1c7aebc23222627fa24d11df5">llvm::X86LegalizerInfo::X86LegalizerInfo</a>.</p>

</div>
</div>

### clampMaxNumElementsStrict() {#a875edaec1f61b358e8026a4b50de8ea8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::clampMaxNumElementsStrict (unsigned TypeIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> EltTy, unsigned NumElts)</td>
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

<p>Express <span class="doxyComputerOutput">EltTy</span> vectors strictly using vectors with <span class="doxyComputerOutput">NumElts</span> elements (or scalars when <span class="doxyComputerOutput">NumElts</span> equals 1).</p>


<p>First pad with undef elements to nearest larger multiple of <span class="doxyComputerOutput">NumElts</span>. Then perform split with all sub-instructions having the same type. Using clampMaxNumElements (non-strict) can result in leftover instruction with different type (fewer elements then <span class="doxyComputerOutput">NumElts</span> or scalar). No effect if the type is not a vector.</p>


<p>Definition at line 1285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#a7b80b62a08d65dc70ac57954b7955ca0">alignNumElementsTo</a>, <a href="#a3b9d49f459b9596f73c60edab6e92673">clampMaxNumElements</a> and <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### clampMinNumElements() {#a3da19f78bfc264962a18568ea4b8d6c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::clampMinNumElements (unsigned TypeIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> EltTy, unsigned MinElements)</td>
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

<p>Limit the number of elements in EltTy vectors to at least MinElements.</p>

<p>Definition at line 1203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ad1db89614d919436714d099c99ff12a0">llvm::LLT::isFixedVector</a>, <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a> and <a href="/web-llvm/docs/api/structs/llvm/legalityquery/#ab28fca6f8145be28b70ad89bb0c741b0">llvm::LegalityQuery::Types</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="#ac56e6d7519b8f4f908174aa570bc5e61">clampNumElements</a> and <a href="/web-llvm/docs/api/classes/llvm/x86legalizerinfo/#abfc562c1c7aebc23222627fa24d11df5">llvm::X86LegalizerInfo::X86LegalizerInfo</a>.</p>

</div>
</div>

### clampNumElements() {#ac56e6d7519b8f4f908174aa570bc5e61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::clampNumElements (unsigned TypeIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> MinTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> MaxTy)</td>
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

<p>Limit the number of elements for the given vectors to at least MinTy's number of elements and at most MaxTy's number of elements.</p>


<p>No effect if the type is not a vector or does not have the same element type as the constraints. The element type of MinTy and MaxTy must match.</p>


<p>Definition at line 1265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3b9d49f459b9596f73c60edab6e92673">clampMaxNumElements</a>, <a href="#a3da19f78bfc264962a18568ea4b8d6c7">clampMinNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3016e0f01ad96a198f81f74397b1c0e6">llvm::LLT::isScalableVector</a> and <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/x86legalizerinfo/#abfc562c1c7aebc23222627fa24d11df5">llvm::X86LegalizerInfo::X86LegalizerInfo</a>.</p>

</div>
</div>

### clampScalar() {#a7adc16cc9bc8db5fd3c8a6798a846ab0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::clampScalar (unsigned TypeIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> MinTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> MaxTy)</td>
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

<p>Limit the range of scalar sizes to MinTy and MaxTy.</p>

<p>Definition at line 1107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a>, <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>, <a href="#a33e181da566d1ebb7556f172888c3b92">maxScalar</a> and <a href="#a009564405d1037574152ee039cd04b9f">minScalar</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a0c94d0f4f62bd71d26a8020faf70b9f0">llvm::ARMLegalizerInfo::ARMLegalizerInfo</a>, <a href="#a07c410b3089ea0fbcfbffecae19b2abb">clampScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a63e981ba0042fbfdd3857f66c82d8d28">llvm::MipsLegalizerInfo::MipsLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#af31cf7c3246e88cbfbb4a3dab768a047">llvm::RISCVLegalizerInfo::RISCVLegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/x86legalizerinfo/#abfc562c1c7aebc23222627fa24d11df5">llvm::X86LegalizerInfo::X86LegalizerInfo</a>.</p>

</div>
</div>

### clampScalar() {#a07c410b3089ea0fbcfbffecae19b2abb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::clampScalar (bool Pred, unsigned TypeIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> MinTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> MaxTy)</td>
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



<p>Definition at line 1113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#a7adc16cc9bc8db5fd3c8a6798a846ab0">clampScalar</a> and <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>

</div>
</div>

### clampScalarOrElt() {#a2660bbe870c09b7a2cc5a24c8bcd97ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::clampScalarOrElt (unsigned TypeIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> MinTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> MaxTy)</td>
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

<p>Limit the range of scalar sizes to MinTy and MaxTy.</p>

<p>Definition at line 1121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>, <a href="#aefcfce4300cbfd94417983bc6317e27a">maxScalarOrElt</a> and <a href="#a3453ec1df80a077b489ea76fee965967">minScalarOrElt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### custom() {#a80f41417117f537cd147aaee97aecb1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::custom ()</td>
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

<p>Unconditionally custom lower.</p>

<p>Definition at line 933 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#acda429561493e08ee5cef54f26a1224c">customIf</a> and <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a0c94d0f4f62bd71d26a8020faf70b9f0">llvm::ARMLegalizerInfo::ARMLegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/spirvlegalizerinfo/#a6b747313719abb32e3599ab33501ea17">llvm::SPIRVLegalizerInfo::SPIRVLegalizerInfo</a>.</p>

</div>
</div>

### customFor() {#afc001d042e6a7093a6954b2d9ff18029}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::customFor (std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types)</td>
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



<p>Definition at line 891 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a0c94d0f4f62bd71d26a8020faf70b9f0">llvm::ARMLegalizerInfo::ARMLegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#af31cf7c3246e88cbfbb4a3dab768a047">llvm::RISCVLegalizerInfo::RISCVLegalizerInfo</a>.</p>

</div>
</div>

### customFor() {#aa2358b8c8275b0a018564c2aad580baf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::customFor (bool Pred, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types)</td>
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



<p>Definition at line 894 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>

</div>
</div>

### customFor() {#aeff7d5df446c2798d2360f5a1a305063}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::customFor (std::initializer_list&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; &gt; Types)</td>
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

<p>The instruction is custom when type indexes 0 and 1 is any type pair in the given list.</p>

<p>Definition at line 902 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>

</div>
</div>

### customFor() {#a6ecf9e98cf230939b28df8866ead625c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::customFor (bool Pred, std::initializer_list&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; &gt; Types)</td>
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



<p>Definition at line 905 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>

</div>
</div>

### customForCartesianProduct() {#a4ad690ef8db6cd914cef1b3aa39bc15f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::customForCartesianProduct (std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types)</td>
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



<p>Definition at line 912 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a0c94d0f4f62bd71d26a8020faf70b9f0">llvm::ARMLegalizerInfo::ARMLegalizerInfo</a>.</p>

</div>
</div>

### customForCartesianProduct() {#a5ad717038b549ad0b3a6d009ab3b4d79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::customForCartesianProduct (std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types0, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types1)</td>
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

<p>The instruction is custom when type indexes 0 and 1 are both in their respective lists.</p>

<p>Definition at line 918 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

### customForCartesianProduct() {#ace6b6d858967a684670864748cbedbea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::customForCartesianProduct (std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types0, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types1, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types2)</td>
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

<p>The instruction is custom when type indexes 0, 1, and 2 are all in their respective lists.</p>

<p>Definition at line 925 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

### customIf() {#acda429561493e08ee5cef54f26a1224c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::customIf (<a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a> Predicate)</td>
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



<p>Definition at line 885 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="#a80f41417117f537cd147aaee97aecb1e">custom</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvlegalizerinfo/#a6b747313719abb32e3599ab33501ea17">llvm::SPIRVLegalizerInfo::SPIRVLegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/x86legalizerinfo/#abfc562c1c7aebc23222627fa24d11df5">llvm::X86LegalizerInfo::X86LegalizerInfo</a>.</p>

</div>
</div>

### fallback() {#aa3f0867f33edbd5a34f5ed9f23a1975b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::fallback ()</td>
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

<p>Fallback on the previous implementation.</p>


<p>This should only be used while porting a rule.</p>


<p>Definition at line 1293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>

</div>
</div>

### fewerElementsIf() {#a2650717a05ef92e13ecc9d1f290eabd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::fewerElementsIf (<a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a> Predicate, <a href="/web-llvm/docs/api/namespaces/llvm/#a31da885e5f80ee375b306057d2a852ab">LegalizeMutation</a> Mutation)</td>
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

<p>Remove elements to reach the type selected by the mutation if the predicate is true.</p>

<p>Definition at line 843 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcvsxfmamutate-cpp/#a11cb5628e531251532f100309802a146">Mutation</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### getAlias() {#ac558716370cd7cd96558d5d04508e23b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LegalizeRuleSet::getAlias ()</td>
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



<p>Definition at line 596 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

### immIdx() {#af1f70f6956b2338cfdc8e8316b104078}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LegalizeRuleSet::immIdx (unsigned ImmIdx)</td>
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



<p>Definition at line 598 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96dabc8440cd13a43eecdbd002b4f2779140">llvm::MCOI::OPERAND_FIRST_GENERIC_IMM</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96dac75b98f7dd3d0cfc2a89eed680e66f27">llvm::MCOI::OPERAND_LAST_GENERIC_IMM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>.</p>

</div>
</div>

### isAliasedByAnother() {#a79cedeeef6030fcad3e98d2ef47b99a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LegalizeRuleSet::isAliasedByAnother ()</td>
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



<p>Definition at line 588 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

### legalFor() {#a1c27c69ac65f9d4937858c10288a17f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::legalFor (std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types)</td>
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

<p>The instruction is legal when type index 0 is any type in the given list.</p>

<p>Definition at line 616 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a0c94d0f4f62bd71d26a8020faf70b9f0">llvm::ARMLegalizerInfo::ARMLegalizerInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/m68klegalizerinfo/#a77a1ff087fb51dfd9397ffc153578c43">llvm::M68kLegalizerInfo::M68kLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a63e981ba0042fbfdd3857f66c82d8d28">llvm::MipsLegalizerInfo::MipsLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ppclegalizerinfo/#ae83d1a82dbe98543ff9238ae236b5e20">llvm::PPCLegalizerInfo::PPCLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvlegalizerinfo/#a6b747313719abb32e3599ab33501ea17">llvm::SPIRVLegalizerInfo::SPIRVLegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/x86legalizerinfo/#abfc562c1c7aebc23222627fa24d11df5">llvm::X86LegalizerInfo::X86LegalizerInfo</a>.</p>

</div>
</div>

### legalFor() {#a41d38ac5e9c5bb8ec878a41fadcf685f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::legalFor (bool Pred, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types)</td>
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



<p>Definition at line 619 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>

</div>
</div>

### legalFor() {#aae97f8857ebeba8f3c96dcd1a2b2d32b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::legalFor (std::initializer_list&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; &gt; Types)</td>
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

<p>The instruction is legal when type indexes 0 and 1 is any type pair in the given list.</p>

<p>Definition at line 626 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>

</div>
</div>

### legalFor() {#ab2b2a7e8c3015c7ec53c53bcfe673e7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::legalFor (bool Pred, std::initializer_list&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; &gt; Types)</td>
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



<p>Definition at line 629 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>

</div>
</div>

### legalFor() {#a232420dcfc34bce51b5a1590e6e1e6db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::legalFor (bool Pred, std::initializer_list&lt; std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; &gt; Types)</td>
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



<p>Definition at line 636 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

### legalForCartesianProduct() {#ae4c02bcf9d3bfdee70f097d0b6aeb9f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::legalForCartesianProduct (std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types)</td>
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

<p>The instruction is legal when type indexes 0 and 1 are both in the given list.</p>


<p>That is, the type pair is in the cartesian product of the list.</p>


<p>Definition at line 665 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a0c94d0f4f62bd71d26a8020faf70b9f0">llvm::ARMLegalizerInfo::ARMLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a63e981ba0042fbfdd3857f66c82d8d28">llvm::MipsLegalizerInfo::MipsLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ppclegalizerinfo/#ae83d1a82dbe98543ff9238ae236b5e20">llvm::PPCLegalizerInfo::PPCLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvlegalizerinfo/#a6b747313719abb32e3599ab33501ea17">llvm::SPIRVLegalizerInfo::SPIRVLegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/x86legalizerinfo/#abfc562c1c7aebc23222627fa24d11df5">llvm::X86LegalizerInfo::X86LegalizerInfo</a>.</p>

</div>
</div>

### legalForCartesianProduct() {#a450f90930a4b8e27bdcbc0909b7297cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::legalForCartesianProduct (std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types0, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types1)</td>
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

<p>The instruction is legal when type indexes 0 and 1 are both their respective lists.</p>

<p>Definition at line 670 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>

</div>
</div>

### legalForCartesianProduct() {#a7b2dfae822a01a81c33527832d182e60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::legalForCartesianProduct (std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types0, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types1, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types2)</td>
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

<p>The instruction is legal when type indexes 0, 1, and 2 are both their respective lists.</p>

<p>Definition at line 676 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>

</div>
</div>

### legalForTypesWithMemDesc() {#aebb3b5876088ebfd2d003d68f7fb4b07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::legalForTypesWithMemDesc (std::initializer_list&lt; <a href="/web-llvm/docs/api/structs/llvm/legalitypredicates/typepairandmemdesc">LegalityPredicates::TypePairAndMemDesc</a> &gt; TypesAndMemDesc)</td>
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

<p>The instruction is legal when type indexes 0 and 1 along with the memory size and minimum alignment is any type and size tuple in the given list.</p>

<p>Definition at line 656 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a> and <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#adb6ccbdc579ec9f5c1f838d091b938da">llvm::LegalityPredicates::typePairAndMemDescInSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a0c94d0f4f62bd71d26a8020faf70b9f0">llvm::ARMLegalizerInfo::ARMLegalizerInfo</a>.</p>

</div>
</div>

### legalForTypeWithAnyImm() {#aaca31f1b00db114db16d186cfeb53135}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::legalForTypeWithAnyImm (std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types)</td>
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

<p>The instruction is legal when type index 0 is any type in the given list and imm index 0 is anything.</p>

<p>Definition at line 643 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>

</div>
</div>

### legalForTypeWithAnyImm() {#a62f037f0d9f2c32d319fefcb5f3475e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::legalForTypeWithAnyImm (std::initializer_list&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; &gt; Types)</td>
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



<p>Definition at line 648 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>

</div>
</div>

### legalIf() {#af6dcfac5a30e4050e3ac204f27062fe6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::legalIf (<a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a> Predicate)</td>
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

<p>The instruction is legal if predicate is true.</p>

<p>Definition at line 609 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a63e981ba0042fbfdd3857f66c82d8d28">llvm::MipsLegalizerInfo::MipsLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ppclegalizerinfo/#ae83d1a82dbe98543ff9238ae236b5e20">llvm::PPCLegalizerInfo::PPCLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvlegalizerinfo/#a6b747313719abb32e3599ab33501ea17">llvm::SPIRVLegalizerInfo::SPIRVLegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/x86legalizerinfo/#abfc562c1c7aebc23222627fa24d11df5">llvm::X86LegalizerInfo::X86LegalizerInfo</a>.</p>

</div>
</div>

### libcall() {#a31342428708a575fd8ed06209949d9dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::libcall ()</td>
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

<p>The instruction is emitted as a library call.</p>

<p>Definition at line 763 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86legalizerinfo/#abfc562c1c7aebc23222627fa24d11df5">llvm::X86LegalizerInfo::X86LegalizerInfo</a>.</p>

</div>
</div>

### libcallFor() {#a32e4ff098c95890246047dc1ddf5a065}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::libcallFor (std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types)</td>
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



<p>Definition at line 778 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a0c94d0f4f62bd71d26a8020faf70b9f0">llvm::ARMLegalizerInfo::ARMLegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a63e981ba0042fbfdd3857f66c82d8d28">llvm::MipsLegalizerInfo::MipsLegalizerInfo</a>.</p>

</div>
</div>

### libcallFor() {#ab1737a08f305f7b21fe313048b25f09c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::libcallFor (bool Pred, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types)</td>
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



<p>Definition at line 781 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>

</div>
</div>

### libcallFor() {#a9b66d6f0693aec5949568c067d0db21f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::libcallFor (std::initializer_list&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; &gt; Types)</td>
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



<p>Definition at line 787 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

### libcallFor() {#ab1dec3831eac71a7c07af99756fbc459}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::libcallFor (bool Pred, std::initializer_list&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; &gt; Types)</td>
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



<p>Definition at line 791 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

### libcallForCartesianProduct() {#a40aebefc69962dcb020706b2829e0159}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::libcallForCartesianProduct (std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types)</td>
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



<p>Definition at line 797 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a63e981ba0042fbfdd3857f66c82d8d28">llvm::MipsLegalizerInfo::MipsLegalizerInfo</a>.</p>

</div>
</div>

### libcallForCartesianProduct() {#a860c7e05708e25e7cf1034f50c21f10e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::libcallForCartesianProduct (std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types0, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types1)</td>
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



<p>Definition at line 801 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

### libcallIf() {#aec5f2318f80808e02d249d59656da194}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::libcallIf (<a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a> Predicate)</td>
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

<p>Like legalIf, but for the Libcall action.</p>

<p>Definition at line 772 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>

</div>
</div>

### lower() {#a6a836d4faf3f9f04f1f04cc5f6de3c03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::lower ()</td>
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

<p>The instruction is lowered.</p>

<p>Definition at line 699 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a0c94d0f4f62bd71d26a8020faf70b9f0">llvm::ARMLegalizerInfo::ARMLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a63e981ba0042fbfdd3857f66c82d8d28">llvm::MipsLegalizerInfo::MipsLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ppclegalizerinfo/#ae83d1a82dbe98543ff9238ae236b5e20">llvm::PPCLegalizerInfo::PPCLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#af31cf7c3246e88cbfbb4a3dab768a047">llvm::RISCVLegalizerInfo::RISCVLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvlegalizerinfo/#a6b747313719abb32e3599ab33501ea17">llvm::SPIRVLegalizerInfo::SPIRVLegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/x86legalizerinfo/#abfc562c1c7aebc23222627fa24d11df5">llvm::X86LegalizerInfo::X86LegalizerInfo</a>.</p>

</div>
</div>

### lowerFor() {#a6eec582df34bb1c63e8666b41ff561ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::lowerFor (std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types)</td>
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

<p>The instruction is lowered when type index 0 is any type in the given list.</p>


<p>Keep type index 0 as the same type.</p>


<p>Definition at line 725 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a0c94d0f4f62bd71d26a8020faf70b9f0">llvm::ARMLegalizerInfo::ARMLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a63e981ba0042fbfdd3857f66c82d8d28">llvm::MipsLegalizerInfo::MipsLegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/ppclegalizerinfo/#ae83d1a82dbe98543ff9238ae236b5e20">llvm::PPCLegalizerInfo::PPCLegalizerInfo</a>.</p>

</div>
</div>

### lowerFor() {#a4abfd57207ad9be3316dbed273935db3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::lowerFor (std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types, <a href="/web-llvm/docs/api/namespaces/llvm/#a31da885e5f80ee375b306057d2a852ab">LegalizeMutation</a> Mutation)</td>
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

<p>The instruction is lowered when type index 0 is any type in the given list.</p>

<p>Definition at line 730 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcvsxfmamutate-cpp/#a11cb5628e531251532f100309802a146">Mutation</a>.</p>

</div>
</div>

### lowerFor() {#a64906287eb2cff470856bc6710512be4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::lowerFor (std::initializer_list&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; &gt; Types)</td>
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

<p>The instruction is lowered when type indexes 0 and 1 is any type pair in the given list.</p>


<p>Keep type index 0 as the same type.</p>


<p>Definition at line 736 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>

</div>
</div>

### lowerFor() {#af61696d493cba381e1fbaf2513370ce1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::lowerFor (std::initializer_list&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; &gt; Types, <a href="/web-llvm/docs/api/namespaces/llvm/#a31da885e5f80ee375b306057d2a852ab">LegalizeMutation</a> Mutation)</td>
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

<p>The instruction is lowered when type indexes 0 and 1 is any type pair in the given list.</p>

<p>Definition at line 741 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcvsxfmamutate-cpp/#a11cb5628e531251532f100309802a146">Mutation</a>.</p>

</div>
</div>

### lowerForCartesianProduct() {#ae84a4659e822b885098d6ebb11633160}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::lowerForCartesianProduct (std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types0, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types1)</td>
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

<p>The instruction is lowered when type indexes 0 and 1 are both in their respective lists.</p>

<p>Definition at line 747 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>

</div>
</div>

### lowerForCartesianProduct() {#aad46ece57d9d8d07b1eb137cd933ff1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::lowerForCartesianProduct (std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types0, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types1, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types2)</td>
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

<p>The instruction is lowered when type indexes 0, 1, and 2 are all in their respective lists.</p>

<p>Definition at line 754 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>

</div>
</div>

### lowerIf() {#a76a7807072af618c3ac80dd8d569deba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::lowerIf (<a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a> Predicate)</td>
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

<p>The instruction is lowered if predicate is true.</p>


<p>Keep type index 0 as the same type.</p>


<p>Definition at line 708 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### lowerIf() {#ae9a56d2d5ddaa43684ecf2194b93e20e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::lowerIf (<a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a> Predicate, <a href="/web-llvm/docs/api/namespaces/llvm/#a31da885e5f80ee375b306057d2a852ab">LegalizeMutation</a> Mutation)</td>
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

<p>The instruction is lowered if predicate is true.</p>

<p>Definition at line 716 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcvsxfmamutate-cpp/#a11cb5628e531251532f100309802a146">Mutation</a>.</p>

</div>
</div>

### lowerIfMemSizeNotByteSizePow2() {#a5361d650c0e9459b1dc4c3afec8251ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::lowerIfMemSizeNotByteSizePow2 ()</td>
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

<p>Lower a memory operation if the memory access size is not a round power of 2 byte size.</p>


<p>This is stricter than lowerIfMemSizeNotPow2, and more likely what you want (e.g. this will lower s1, s7 and s24).</p>


<p>Definition at line 880 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a> and <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#a66c37e901bc47ad309a6f13c2edeecd4">llvm::LegalityPredicates::memSizeNotByteSizePow2</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>.</p>

</div>
</div>

### lowerIfMemSizeNotPow2() {#a479d3f2cd21c2250ae84ec2b06be816f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::lowerIfMemSizeNotPow2 ()</td>
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

<p>Lower a memory operation if the memory size, rounded to bytes, is not a power of 2.</p>


<p>For example, this will not trigger for s1 or s7, but will for s24.</p>


<p>Definition at line 872 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a> and <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#a1581af0215e33dd0bc26f84d67aa610a">llvm::LegalityPredicates::memSizeInBytesNotPow2</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>.</p>

</div>
</div>

### maxScalar() {#a33e181da566d1ebb7556f172888c3b92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::maxScalar (unsigned TypeIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
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

<p>Ensure the scalar is at most as wide as Ty.</p>

<p>Definition at line 1080 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a0c94d0f4f62bd71d26a8020faf70b9f0">llvm::ARMLegalizerInfo::ARMLegalizerInfo</a>, <a href="#a7adc16cc9bc8db5fd3c8a6798a846ab0">clampScalar</a> and <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a63e981ba0042fbfdd3857f66c82d8d28">llvm::MipsLegalizerInfo::MipsLegalizerInfo</a>.</p>

</div>
</div>

### maxScalarEltSameAsIf() {#a1d446dfaa94c6ec0729feaa73d5b6c88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::maxScalarEltSameAsIf (<a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a> Predicate, unsigned TypeIdx, unsigned SmallTypeIdx)</td>
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

<p>Conditionally narrow the scalar or elt to match the size of another.</p>

<p>Definition at line 1176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>, <a href="#a6a80f26baa5258688f20cafc7efac05f">narrowScalarIf</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/structs/llvm/legalityquery/#ab28fca6f8145be28b70ad89bb0c741b0">llvm::LegalityQuery::Types</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>.</p>

</div>
</div>

### maxScalarIf() {#acd56c0d001ca90095d61c52099f90cd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::maxScalarIf (<a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a> Predicate, unsigned TypeIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
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

<p>Conditionally limit the maximum size of the scalar.</p>


<p>For example, when the maximum size of one type depends on the size of another such as extracting N bits from an M bit container.</p>


<p>Definition at line 1091 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a>, <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a> and <a href="/web-llvm/docs/api/structs/llvm/legalityquery/#ab28fca6f8145be28b70ad89bb0c741b0">llvm::LegalityQuery::Types</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### maxScalarOrElt() {#aefcfce4300cbfd94417983bc6317e27a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::maxScalarOrElt (unsigned TypeIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
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

<p>Ensure the scalar is at most as wide as Ty.</p>

<p>Definition at line 1071 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>


<p>Referenced by <a href="#a2660bbe870c09b7a2cc5a24c8bcd97ae">clampScalarOrElt</a>.</p>

</div>
</div>

### maxScalarSameAs() {#a0d8b8e18977cd5ba53ec89aa06bd7506}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::maxScalarSameAs (unsigned TypeIdx, unsigned NarrowTypeIdx)</td>
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

<p>Narrow the scalar to match the size of another.</p>

<p>Definition at line 1139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/legalizemutations/#af1ee247ef88b451470210e27a2eefb44">llvm::LegalizeMutations::changeElementSizeTo</a>, <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a> and <a href="/web-llvm/docs/api/structs/llvm/legalityquery/#ab28fca6f8145be28b70ad89bb0c741b0">llvm::LegalityQuery::Types</a>.</p>


<p>Referenced by <a href="#a236c4562fff94fbec23fd35c0b5257a1">scalarSameSizeAs</a>.</p>

</div>
</div>

### minScalar() {#a009564405d1037574152ee039cd04b9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::minScalar (unsigned TypeIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
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

<p>Ensure the scalar is at least as wide as Ty.</p>

<p>Definition at line 1041 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="#a7adc16cc9bc8db5fd3c8a6798a846ab0">clampScalar</a>, <a href="#a562998853f3ac3eb154887ff77180c73">minScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a63e981ba0042fbfdd3857f66c82d8d28">llvm::MipsLegalizerInfo::MipsLegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/x86legalizerinfo/#abfc562c1c7aebc23222627fa24d11df5">llvm::X86LegalizerInfo::X86LegalizerInfo</a>.</p>

</div>
</div>

### minScalar() {#a562998853f3ac3eb154887ff77180c73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::minScalar (bool Pred, unsigned TypeIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
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



<p>Definition at line 1048 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a> and <a href="#a009564405d1037574152ee039cd04b9f">minScalar</a>.</p>

</div>
</div>

### minScalarEltSameAsIf() {#a4aca13e5c1613b22b7c3c9411895fdae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::minScalarEltSameAsIf (<a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a> Predicate, unsigned TypeIdx, unsigned LargeTypeIdx)</td>
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

<p>Conditionally widen the scalar or elt to match the size of another.</p>

<p>Definition at line 1158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/structs/llvm/legalityquery/#ab28fca6f8145be28b70ad89bb0c741b0">llvm::LegalityQuery::Types</a> and <a href="#a99e1a648bb3a1018aed19e77cae2203c">widenScalarIf</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>.</p>

</div>
</div>

### minScalarIf() {#af0cb74dd5e94daaea299005867eac63d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::minScalarIf (<a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a> Predicate, unsigned TypeIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
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

<p>Ensure the scalar is at least as wide as Ty if condition is met.</p>

<p>Definition at line 1055 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a>, <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a> and <a href="/web-llvm/docs/api/structs/llvm/legalityquery/#ab28fca6f8145be28b70ad89bb0c741b0">llvm::LegalityQuery::Types</a>.</p>

</div>
</div>

### minScalarOrElt() {#a3453ec1df80a077b489ea76fee965967}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::minScalarOrElt (unsigned TypeIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
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

<p>Ensure the scalar or element is at least as wide as Ty.</p>

<p>Definition at line 1000 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a> and <a href="#a2660bbe870c09b7a2cc5a24c8bcd97ae">clampScalarOrElt</a>.</p>

</div>
</div>

### minScalarOrEltIf() {#a9673f01ba4c77779f3361b426653d257}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::minScalarOrEltIf (<a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a> Predicate, unsigned TypeIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
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

<p>Ensure the scalar or element is at least as wide as Ty.</p>

<p>Definition at line 1009 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a873403a2506ac332f62ad4c2d7dc1835">llvm::all</a> and <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>.</p>

</div>
</div>

### minScalarSameAs() {#a8abe7c10c8bfc8f9c308c89adc98330c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::minScalarSameAs (unsigned TypeIdx, unsigned LargeTypeIdx)</td>
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

<p>Widen the scalar to match the size of another.</p>

<p>Definition at line 1127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/legalizemutations/#af1ee247ef88b451470210e27a2eefb44">llvm::LegalizeMutations::changeElementSizeTo</a>, <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a> and <a href="/web-llvm/docs/api/structs/llvm/legalityquery/#ab28fca6f8145be28b70ad89bb0c741b0">llvm::LegalityQuery::Types</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a> and <a href="#a236c4562fff94fbec23fd35c0b5257a1">scalarSameSizeAs</a>.</p>

</div>
</div>

### moreElementsIf() {#a6baff39b32f5cec5ea417cba89f077ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::moreElementsIf (<a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a> Predicate, <a href="/web-llvm/docs/api/namespaces/llvm/#a31da885e5f80ee375b306057d2a852ab">LegalizeMutation</a> Mutation)</td>
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

<p>Add more elements to reach the type selected by the mutation if the predicate is true.</p>

<p>Definition at line 834 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcvsxfmamutate-cpp/#a11cb5628e531251532f100309802a146">Mutation</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### moreElementsToNextPow2() {#a592ea5db9394c272d8354d931134f16c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::moreElementsToNextPow2 (unsigned TypeIdx)</td>
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

<p>Add more elements to the vector to reach the next power of two.</p>


<p>No effect if the type is not a vector or the element count is a power of two.</p>


<p>Definition at line 1195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a> and <a href="/web-llvm/docs/api/namespaces/llvm/legalizemutations/#a039bb9a10ad812f936f4325facc13ab3">llvm::LegalizeMutations::moreElementsToNextPow2</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/x86legalizerinfo/#abfc562c1c7aebc23222627fa24d11df5">llvm::X86LegalizerInfo::X86LegalizerInfo</a>.</p>

</div>
</div>

### narrowScalar() {#a6e6eeb6a4185d14eed4d84a59ffa05c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::narrowScalar (unsigned TypeIdx, <a href="/web-llvm/docs/api/namespaces/llvm/#a31da885e5f80ee375b306057d2a852ab">LegalizeMutation</a> Mutation)</td>
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



<p>Definition at line 980 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcvsxfmamutate-cpp/#a11cb5628e531251532f100309802a146">Mutation</a>.</p>

</div>
</div>

### narrowScalarFor() {#a6d4489897a525246ea6f1e924ac20245}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::narrowScalarFor (std::initializer_list&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; &gt; Types, <a href="/web-llvm/docs/api/namespaces/llvm/#a31da885e5f80ee375b306057d2a852ab">LegalizeMutation</a> Mutation)</td>
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

<p>Narrow the scalar, specified in mutation, when type indexes 0 and 1 is any type pair in the given list.</p>

<p>Definition at line 827 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcvsxfmamutate-cpp/#a11cb5628e531251532f100309802a146">Mutation</a>.</p>

</div>
</div>

### narrowScalarIf() {#a6a80f26baa5258688f20cafc7efac05f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::narrowScalarIf (<a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a> Predicate, <a href="/web-llvm/docs/api/namespaces/llvm/#a31da885e5f80ee375b306057d2a852ab">LegalizeMutation</a> Mutation)</td>
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

<p>Narrow the scalar to the one selected by the mutation if the predicate is true.</p>

<p>Definition at line 817 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcvsxfmamutate-cpp/#a11cb5628e531251532f100309802a146">Mutation</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a> and <a href="#a1d446dfaa94c6ec0729feaa73d5b6c88">maxScalarEltSameAsIf</a>.</p>

</div>
</div>

### scalarize() {#adf80c6b70ec078f749c51a5e64b4393d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::scalarize (unsigned TypeIdx)</td>
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



<p>Definition at line 986 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a> and <a href="/web-llvm/docs/api/namespaces/llvm/legalizemutations/#a5574ba0db2a42fa195db009f06f1d731">llvm::LegalizeMutations::scalarize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvlegalizerinfo/#a6b747313719abb32e3599ab33501ea17">llvm::SPIRVLegalizerInfo::SPIRVLegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/x86legalizerinfo/#abfc562c1c7aebc23222627fa24d11df5">llvm::X86LegalizerInfo::X86LegalizerInfo</a>.</p>

</div>
</div>

### scalarizeIf() {#a7369e2b43abeda933406d7b9ed83500c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::scalarizeIf (<a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a> Predicate, unsigned TypeIdx)</td>
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



<p>Definition at line 992 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a873403a2506ac332f62ad4c2d7dc1835">llvm::all</a>, <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a> and <a href="/web-llvm/docs/api/namespaces/llvm/legalizemutations/#a5574ba0db2a42fa195db009f06f1d731">llvm::LegalizeMutations::scalarize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>.</p>

</div>
</div>

### scalarSameSizeAs() {#a236c4562fff94fbec23fd35c0b5257a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::scalarSameSizeAs (unsigned TypeIdx, unsigned SameSizeIdx)</td>
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

<p>Change the type <span class="doxyComputerOutput">TypeIdx</span> to have the same scalar size as type <span class="doxyComputerOutput">SameSizeIdx</span>.</p>

<p>Definition at line 1152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>, <a href="#a0d8b8e18977cd5ba53ec89aa06bd7506">maxScalarSameAs</a> and <a href="#a8abe7c10c8bfc8f9c308c89adc98330c">minScalarSameAs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/x86legalizerinfo/#abfc562c1c7aebc23222627fa24d11df5">llvm::X86LegalizerInfo::X86LegalizerInfo</a>.</p>

</div>
</div>

### setIsAliasedByAnother() {#ae3b653087a0b463517033883f99368de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LegalizeRuleSet::setIsAliasedByAnother ()</td>
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



<p>Definition at line 589 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

### unsupported() {#a2034405f0aed7259ed9999053c3f591d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::unsupported ()</td>
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

<p>The instruction is unsupported.</p>

<p>Definition at line 852 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### unsupportedFor() {#a4125d6153339fbe5614602c31c5500d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::unsupportedFor (std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types)</td>
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



<p>Definition at line 860 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### unsupportedIf() {#a916cd5bc69b2a149600ab1488c047bc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::unsupportedIf (<a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a> Predicate)</td>
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



<p>Definition at line 856 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Reference <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### unsupportedIfMemSizeNotPow2() {#ac87cf76397c445a62260d503afd96cf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::unsupportedIfMemSizeNotPow2 ()</td>
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



<p>Definition at line 864 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a> and <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#a1581af0215e33dd0bc26f84d67aa610a">llvm::LegalityPredicates::memSizeInBytesNotPow2</a>.</p>

</div>
</div>

### verifyImmIdxsCoverage() {#a333c735ce0e828dfc8e88c8385825b45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LegalizeRuleSet::verifyImmIdxsCoverage (unsigned NumImmIdxs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if there is no imm index which is obviously not handled by the <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> in any way at all.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> indices of the opcode form a dense [0, <span class="doxyComputerOutput">NumTypeIdxs</span>) set.</p></dd>
</dl>


<p>Declaration at line 1305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerinfo-cpp">LegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo/#a9801185bc6472dc541877662983e7414">llvm::LegalizerInfo::verify</a>.</p>

</div>
</div>

### verifyTypeIdxsCoverage() {#af4a1582478d21b5d91d22fcb5989a0bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LegalizeRuleSet::verifyTypeIdxsCoverage (unsigned NumTypeIdxs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if there is no type index which is obviously not handled by the <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset">LegalizeRuleSet</a> in any way at all.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> indices of the opcode form a dense [0, <span class="doxyComputerOutput">NumTypeIdxs</span>) set.</p></dd>
</dl>


<p>Declaration at line 1301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerinfo-cpp">LegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo/#a9801185bc6472dc541877662983e7414">llvm::LegalizerInfo::verify</a>.</p>

</div>
</div>

### widenScalarIf() {#a99e1a648bb3a1018aed19e77cae2203c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::widenScalarIf (<a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a> Predicate, <a href="/web-llvm/docs/api/namespaces/llvm/#a31da885e5f80ee375b306057d2a852ab">LegalizeMutation</a> Mutation)</td>
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

<p>Widen the scalar to the one selected by the mutation if the predicate is true.</p>

<p>Definition at line 808 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcvsxfmamutate-cpp/#a11cb5628e531251532f100309802a146">Mutation</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a> and <a href="#a4aca13e5c1613b22b7c3c9411895fdae">minScalarEltSameAsIf</a>.</p>

</div>
</div>

### widenScalarOrEltToNextPow2() {#af52cd47605369d735f4d6e6b24faf003}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::widenScalarOrEltToNextPow2 (unsigned TypeIdx, unsigned MinSize=0)</td>
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

<p>Widen the scalar or vector element type to the next power of two that is at least MinSize.</p>


<p>No effect if the scalar size is a power of two.</p>


<p>Definition at line 960 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a> and <a href="/web-llvm/docs/api/namespaces/llvm/legalizemutations/#ac48512a9f1e26744de1b6940b4adb68f">llvm::LegalizeMutations::widenScalarOrEltToNextPow2</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>.</p>

</div>
</div>

### widenScalarOrEltToNextPow2OrMinSize() {#a173a5c5c1e9992339faedc21b5954918}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::widenScalarOrEltToNextPow2OrMinSize (unsigned TypeIdx, unsigned MinSize=0)</td>
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

<p>Widen the scalar or vector element type to the next power of two that is at least MinSize.</p>


<p>No effect if the scalar size is a power of two.</p>


<p>Definition at line 970 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a> and <a href="/web-llvm/docs/api/namespaces/llvm/legalizemutations/#ac48512a9f1e26744de1b6940b4adb68f">llvm::LegalizeMutations::widenScalarOrEltToNextPow2</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>.</p>

</div>
</div>

### widenScalarToNextMultipleOf() {#afde49505d22ecf8f8b01f47f6eaa0299}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::widenScalarToNextMultipleOf (unsigned TypeIdx, unsigned Size)</td>
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

<p>Widen the scalar to the next multiple of Size.</p>


<p>No effect if the type is not a scalar or is a multiple of Size.</p>


<p>Definition at line 950 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/legalizemutations/#adb23d5b2ee365353f048abead51934e2">llvm::LegalizeMutations::widenScalarOrEltToNextMultipleOf</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### widenScalarToNextPow2() {#adef498f01eb5d7c19ac40cd3b302d09e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::widenScalarToNextPow2 (unsigned TypeIdx, unsigned MinSize=0)</td>
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

<p>Widen the scalar to the next power of two that is at least MinSize.</p>


<p>No effect if the type is a power of two, except if the type is smaller than MinSize, or if the type is a vector type.</p>


<p>Definition at line 940 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a> and <a href="/web-llvm/docs/api/namespaces/llvm/legalizemutations/#ac48512a9f1e26744de1b6940b4adb68f">llvm::LegalizeMutations::widenScalarOrEltToNextPow2</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/m68klegalizerinfo/#a77a1ff087fb51dfd9397ffc153578c43">llvm::M68kLegalizerInfo::M68kLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#af31cf7c3246e88cbfbb4a3dab768a047">llvm::RISCVLegalizerInfo::RISCVLegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/x86legalizerinfo/#abfc562c1c7aebc23222627fa24d11df5">llvm::X86LegalizerInfo::X86LegalizerInfo</a>.</p>

</div>
</div>

### widenVectorEltsToVectorMinSize() {#a430225b2e66451c27e9f4e9462be7df1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::widenVectorEltsToVectorMinSize (unsigned TypeIdx, unsigned VectorSize)</td>
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

<p>Ensure the vector size is at least as wide as VectorSize by promoting the element.</p>

<p>Definition at line 1021 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ad1db89614d919436714d099c99ff12a0">llvm::LLT::isFixedVector</a>, <a href="#a39bfb415182d98d5ac687986a2f7a52f">LegalizeRuleSet</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="/web-llvm/docs/api/structs/llvm/legalityquery/#ab28fca6f8145be28b70ad89bb0c741b0">llvm::LegalityQuery::Types</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### actionFor() {#ac6a933fa6fe21a3ace72c2694bc38e3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::actionFor (<a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654">LegalizeAction</a> Action, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the given action when type index 0 is any type in the given list.</p>


<p>Action should not be an action that requires mutation.</p>


<p>Definition at line 494 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

### actionFor() {#a4bf495bff8449be06e932ed2c608fc9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::actionFor (<a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654">LegalizeAction</a> Action, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types, <a href="/web-llvm/docs/api/namespaces/llvm/#a31da885e5f80ee375b306057d2a852ab">LegalizeMutation</a> Mutation)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the given action when type index 0 is any type in the given list.</p>


<p>Action should be an action that requires mutation.</p>


<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

### actionFor() {#ac431188bd890910c68a37ac300a897d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::actionFor (<a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654">LegalizeAction</a> Action, std::initializer_list&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; &gt; Types)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the given action when type indexes 0 and 1 is any type pair in the given list.</p>


<p>Action should not be an action that requires mutation.</p>


<p>Definition at line 510 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

### actionFor() {#a1b1aa9bb0f97dbf22838835f6d779ede}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::actionFor (<a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654">LegalizeAction</a> Action, std::initializer_list&lt; std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; &gt; Types)</td>
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



<p>Definition at line 517 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

### actionFor() {#afbfb41b6245c509daaca5fc9f6082e8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::actionFor (<a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654">LegalizeAction</a> Action, std::initializer_list&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; &gt; Types, <a href="/web-llvm/docs/api/namespaces/llvm/#a31da885e5f80ee375b306057d2a852ab">LegalizeMutation</a> Mutation)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the given action when type indexes 0 and 1 is any type pair in the given list.</p>


<p>Action should be an action that requires mutation.</p>


<p>Definition at line 527 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

### actionForCartesianProduct() {#a86c6ea1ba3e831e3a528e0cd7c3fd757}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::actionForCartesianProduct (<a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654">LegalizeAction</a> Action, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the given action when type indexes 0 and 1 are both in the given list.</p>


<p>That is, the type pair is in the cartesian product of the list. Action should not be an action that requires mutation.</p>


<p>Definition at line 554 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

### actionForCartesianProduct() {#aa12b8bfce1fe3d2da2385aa7cd1a7b0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::actionForCartesianProduct (<a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654">LegalizeAction</a> Action, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types0, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types1)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the given action when type indexes 0 and 1 are both in their respective lists.</p>


<p>That is, the type pair is in the cartesian product of the lists Action should not be an action that requires mutation.</p>


<p>Definition at line 565 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

### actionForCartesianProduct() {#a6309c6b6eedafa4ed0ccc2ed89e17769}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::actionForCartesianProduct (<a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654">LegalizeAction</a> Action, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types0, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types1, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types2)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the given action when type indexes 0, 1, and 2 are all in their respective lists.</p>


<p>That is, the type triple is in the cartesian product of the lists Action should not be an action that requires mutation.</p>


<p>Definition at line 576 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

### actionForTypeWithAnyImm() {#a6564543b629d0f2a349dcef0858c4526}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::actionForTypeWithAnyImm (<a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654">LegalizeAction</a> Action, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the given action when type index 0 is any type in the given list and imm index 0 is anything.</p>


<p>Action should not be an action that requires mutation.</p>


<p>Definition at line 537 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

### actionForTypeWithAnyImm() {#ac24b0e82911b564e66957c69535b8d18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::actionForTypeWithAnyImm (<a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654">LegalizeAction</a> Action, std::initializer_list&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; &gt; Types)</td>
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



<p>Definition at line 544 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

### actionIf() {#af9c6bd9030d99996c5529a56a6e3a2d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::actionIf (<a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654">LegalizeAction</a> Action, <a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a> Predicate)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the given action when the predicate is true.</p>


<p>Action should not be an action that requires mutation.</p>


<p>Definition at line 480 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

### actionIf() {#a1863c137e0a15ad9f2f9ee533ed363a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeRuleSet &amp; llvm::LegalizeRuleSet::actionIf (<a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654">LegalizeAction</a> Action, <a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a> Predicate, <a href="/web-llvm/docs/api/namespaces/llvm/#a31da885e5f80ee375b306057d2a852ab">LegalizeMutation</a> Mutation)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the given action when the predicate is true.</p>


<p>Action should be an action that requires mutation.</p>


<p>Definition at line 487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

### add() {#aa55e44adaf9508fcee1377fa2c13d78d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LegalizeRuleSet::add (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/legalizerule">LegalizeRule</a> &amp; Rule)</td>
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



<p>Definition at line 470 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

### markAllIdxsAsCovered() {#ab45d189bce430c639310f764edb724aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LegalizeRuleSet::markAllIdxsAsCovered ()</td>
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



<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

### typeIdx() {#abb8202610e80e780c894a4632998b75f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LegalizeRuleSet::typeIdx (unsigned TypeIdx)</td>
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



<p>Definition at line 453 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AliasOf {#a7020c49f358e38c5b6ffdffd6b683559}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LegalizeRuleSet::AliasOf = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When non-zero, the opcode we are an alias of.</p>

<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

### ImmIdxsCovered {#a9cff0f1d59d56ec49f0a1e502eda7afb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallBitVector llvm::LegalizeRuleSet::ImmIdxsCovered</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{<a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96dac75b98f7dd3d0cfc2a89eed680e66f27">MCOI::OPERAND_LAST_GENERIC_IMM</a> -
                                <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96dabc8440cd13a43eecdbd002b4f2779140">MCOI::OPERAND_FIRST_GENERIC_IMM</a> + 2}
</div>
</dd>
</dl>

<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

### IsAliasedByAnother {#abcf696bbfa51dbb4ee766ddb653080a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LegalizeRuleSet::IsAliasedByAnother = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If true, there is another opcode that aliases this one.</p>

<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

### Rules {#a7cda8dd35635913b159a3595f8cb25b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;LegalizeRule, 2&gt; llvm::LegalizeRuleSet::Rules</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

### TypeIdxsCovered {#ad08bf7bbc8e9c86df9c5074a7ba64082}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallBitVector llvm::LegalizeRuleSet::TypeIdxsCovered</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If bit I is set, this rule set contains a rule that may handle (predicate or perform an action upon (or both)) the type index I.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{<a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96da8b1f03c574eba95352f9e531dbad42b4">MCOI::OPERAND_LAST_GENERIC</a> -
                                 <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96da9c1b4fee0481848b7ede086f9bba9ded">MCOI::OPERAND_FIRST_GENERIC</a> + 2}
</div>
</dd>
</dl>


<p>The uncertainty comes from free-form rules executing user-provided lambda functions. We conservatively assume such rules do the right thing and cover all type indices. The bitset is intentionally 1 bit wider than it absolutely needs to be to distinguish such cases from the cases where all type indices are individually handled.</p>


<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### always() {#a34b16ce16c4e92f8d53aa6e0d3c537d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LegalizeRuleSet::always (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/legalityquery">LegalityQuery</a> &amp;)</td>
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



<p>Definition at line 476 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerinfo-cpp">LegalizerInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
