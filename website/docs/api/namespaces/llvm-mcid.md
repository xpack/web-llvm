---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/mcid
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `MCID` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::MCID { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Flag { <a href="#ab357441fcd1ea1f9b0d27c12700f6023">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>These should be considered private to the implementation of the <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> class. <a href="#ab357441fcd1ea1f9b0d27c12700f6023">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Enumerations

### Flag {#ab357441fcd1ea1f9b0d27c12700f6023}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MCID::Flag </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>These should be considered private to the implementation of the <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> class.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PreISelOpcode<a id="ab357441fcd1ea1f9b0d27c12700f6023a99de85e8619d9f7237f6434e655aa8af"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Variadic<a id="ab357441fcd1ea1f9b0d27c12700f6023a06448010e7faa3713221a1b768380957"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HasOptionalDef<a id="ab357441fcd1ea1f9b0d27c12700f6023a330ed49df68eb049e1a7f9f331a07d08"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pseudo<a id="ab357441fcd1ea1f9b0d27c12700f6023ab96d69e82db1bb1326a1d12b8a1e0076"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Meta<a id="ab357441fcd1ea1f9b0d27c12700f6023ad6fc37a26e7cdfb78a406be0ecf2f521"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Return<a id="ab357441fcd1ea1f9b0d27c12700f6023a5416d9f1bd5f533efddadf17d713e469"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EHScopeReturn<a id="ab357441fcd1ea1f9b0d27c12700f6023a5e4ba738cf7144b3dfc5ff4947351349"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Call<a id="ab357441fcd1ea1f9b0d27c12700f6023a463baf545246fea9718664d933ffe66f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Barrier<a id="ab357441fcd1ea1f9b0d27c12700f6023a24b6e620b18edd37201fb9c0897835a8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Terminator<a id="ab357441fcd1ea1f9b0d27c12700f6023af121d798d2c14b32e81d537a1f0cff8d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Branch<a id="ab357441fcd1ea1f9b0d27c12700f6023a359237c780f7c8e40645575826da8a3c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IndirectBranch<a id="ab357441fcd1ea1f9b0d27c12700f6023ac3c34b10dadcdbcc85552097cf077393"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Compare<a id="ab357441fcd1ea1f9b0d27c12700f6023a1328ed43be8173506f59f88c9bfd8b8c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MoveImm<a id="ab357441fcd1ea1f9b0d27c12700f6023aaeaafb46babde1143b2fa296b164a5c4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MoveReg<a id="ab357441fcd1ea1f9b0d27c12700f6023a37d39f9011275aa3445928f6b0037246"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Bitcast<a id="ab357441fcd1ea1f9b0d27c12700f6023a1f4c637ab112633eebd0f503b71be732"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Select<a id="ab357441fcd1ea1f9b0d27c12700f6023a32dbd2c72a98eaee90e3ad5ef7b5af16"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DelaySlot<a id="ab357441fcd1ea1f9b0d27c12700f6023a35dba8ebfddf32172dee2f54483c044a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FoldableAsLoad<a id="ab357441fcd1ea1f9b0d27c12700f6023aae43507b1a7708c07602a361936f7de3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MayLoad<a id="ab357441fcd1ea1f9b0d27c12700f6023a530d5e41c3cf67937c373da61c65acd4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MayStore<a id="ab357441fcd1ea1f9b0d27c12700f6023a50b76935e53196d5d0610736ed52386d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MayRaiseFPException<a id="ab357441fcd1ea1f9b0d27c12700f6023a6d8ad5d1cd35c1093591f1eb9512d3e8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Predicable<a id="ab357441fcd1ea1f9b0d27c12700f6023a9222c946b8b605c95952eedf035a7eff"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NotDuplicable<a id="ab357441fcd1ea1f9b0d27c12700f6023a8c84f3a089d61a5e72ba0a166cf74e2c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UnmodeledSideEffects<a id="ab357441fcd1ea1f9b0d27c12700f6023af8bff71a05bf850313aede4b0f0af856"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Commutable<a id="ab357441fcd1ea1f9b0d27c12700f6023a3ef69fec39e2c626336993c9774dc406"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ConvertibleTo3Addr<a id="ab357441fcd1ea1f9b0d27c12700f6023a4dc2f8bf7dec9f3153e6aed4db5cb010"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UsesCustomInserter<a id="ab357441fcd1ea1f9b0d27c12700f6023ad14700fd3b1c636ccbbdac0e94dd8bf9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HasPostISelHook<a id="ab357441fcd1ea1f9b0d27c12700f6023a4dd7557d1d8cb30db26e0e28228c1cc7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Rematerializable<a id="ab357441fcd1ea1f9b0d27c12700f6023a8862ede68c58eb6c127dc1f9fba7c8ab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CheapAsAMove<a id="ab357441fcd1ea1f9b0d27c12700f6023a483f86b4470ddff0e7cf0e94253e07af"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExtraSrcRegAllocReq<a id="ab357441fcd1ea1f9b0d27c12700f6023a986397153989297cba4e0cf19b75412a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExtraDefRegAllocReq<a id="ab357441fcd1ea1f9b0d27c12700f6023a136b35119a9335091735d1faf665281d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RegSequence<a id="ab357441fcd1ea1f9b0d27c12700f6023aabce0250d60b95b97ff41ff41ba030d6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExtractSubreg<a id="ab357441fcd1ea1f9b0d27c12700f6023ade54f56905df7c591ac1baf60adf8ed5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InsertSubreg<a id="ab357441fcd1ea1f9b0d27c12700f6023ad36e4d09ad9fb9f039b446fa505149ad"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Convergent<a id="ab357441fcd1ea1f9b0d27c12700f6023a63a45e5b4f6037c05b07b9dc2c7ded46"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Add<a id="ab357441fcd1ea1f9b0d27c12700f6023a2b016c207343046b2bac45e69e76dcec"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Trap<a id="ab357441fcd1ea1f9b0d27c12700f6023a07f4679af9a7f7ea34150e7f6354c0d2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VariadicOpsAreDefs<a id="ab357441fcd1ea1f9b0d27c12700f6023a3f20b8867db586190253ce9c9399cd3d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Authenticated<a id="ab357441fcd1ea1f9b0d27c12700f6023af08df35a985db315d7e9057ecbdff04d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>Clients should use the predicate methods on <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a>, not use these directly. These all correspond to bitfields in the <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a27d4264231f86aafeaf8fb38e53342ee">MCInstrDesc::Flags</a> field.</p>


<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
