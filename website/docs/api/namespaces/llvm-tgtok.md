---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/tgtok
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `tgtok` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::tgtok { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TokKind { <a href="#abbc5259d649363016626e2529fabe0c5">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a430288ce6f4ab3a067e165aa0645ee3b">isBangOperator</a> (tgtok::TokKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isBangOperator - Return true if this is a bang operator. <a href="#a430288ce6f4ab3a067e165aa0645ee3b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adedca5779d9bfd003dcd9b878aa8c406">isObjectStart</a> (tgtok::TokKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isObjectStart - Return true if this is a valid first token for a statement. <a href="#adedca5779d9bfd003dcd9b878aa8c406">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb202308092eb993646d3f969e18e463">isStringValue</a> (tgtok::TokKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isStringValue - Return true if this is a string value. <a href="#aeb202308092eb993646d3f969e18e463">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Enumerations

### TokKind {#abbc5259d649363016626e2529fabe0c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::tgtok::TokKind </td>
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
<td class="doxyEnumItemName">Eof<a id="abbc5259d649363016626e2529fabe0c5ad5504ffda0efa1de5ca3294f5ea86bbf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Error<a id="abbc5259d649363016626e2529fabe0c5a857bb78262fafbb375c8ddb3bbb40786"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">minus<a id="abbc5259d649363016626e2529fabe0c5ab6518ad1edafb12d97dfa4c6fcdca405"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">plus<a id="abbc5259d649363016626e2529fabe0c5af7dfdb0abdda5fcfe131bb1c1c6ccb71"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">l_square<a id="abbc5259d649363016626e2529fabe0c5a40cabdc4be4733e64eac9c7f83132f03"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">r_square<a id="abbc5259d649363016626e2529fabe0c5a010c75d9fc7a8d85a674d2dddf5d54ad"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">l_brace<a id="abbc5259d649363016626e2529fabe0c5a35420167961de464fb47ec9732841a3d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">r_brace<a id="abbc5259d649363016626e2529fabe0c5ad02542660854e784e7c214a8dba6c234"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">l_paren<a id="abbc5259d649363016626e2529fabe0c5a7ca2031967b9994e99508bf0b78520e7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">r_paren<a id="abbc5259d649363016626e2529fabe0c5a2f1ba4b878badcae8ff5c8abf15c31eb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">less<a id="abbc5259d649363016626e2529fabe0c5af4971765146e9eb55e9536e3017b3457"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">greater<a id="abbc5259d649363016626e2529fabe0c5af4368dbd4f5a6192fa1b7a17f220677e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">colon<a id="abbc5259d649363016626e2529fabe0c5ac289b529b3eac246daa84b6029a8f32a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">semi<a id="abbc5259d649363016626e2529fabe0c5aa7ef6093191c7af59ccbc6ee4a3c5551"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">comma<a id="abbc5259d649363016626e2529fabe0c5a31b3f98cff1881ed369ffe28cef4efaf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">dot<a id="abbc5259d649363016626e2529fabe0c5a89e8c5a65289a09adf80db3d1775bb3a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">equal<a id="abbc5259d649363016626e2529fabe0c5a7b38b5f9458ca8aa4eafb3b72b91cbe3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">question<a id="abbc5259d649363016626e2529fabe0c5af32d4b104ac8d76f0ba9bd78ef3bd567"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">paste<a id="abbc5259d649363016626e2529fabe0c5a1dfc4cdbd750836b37c136d241f19ddd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">dotdotdot<a id="abbc5259d649363016626e2529fabe0c5aefd642499efb3e0e79077ba5623968f4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TrueVal<a id="abbc5259d649363016626e2529fabe0c5a58b95af1ca96e109f85a0646a05fceb7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FalseVal<a id="abbc5259d649363016626e2529fabe0c5aeb5a2908109c763377832cbb4726b6d4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IntVal<a id="abbc5259d649363016626e2529fabe0c5a3a7597ca475c0fcf10856ef36351d1ac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BinaryIntVal<a id="abbc5259d649363016626e2529fabe0c5a97d8c4bae82b44ebea73f7288c51fdc6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Ifdef<a id="abbc5259d649363016626e2529fabe0c5a591ae45c1a766f301b271d4b6c6ae309"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Ifndef<a id="abbc5259d649363016626e2529fabe0c5ab5f689dca655bd115c72494630f3c79a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Else<a id="abbc5259d649363016626e2529fabe0c5af9f9662bb78e64d7db00b19d61e41655"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Endif<a id="abbc5259d649363016626e2529fabe0c5ac30621b04c693439dc7bb717136677f1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Define<a id="abbc5259d649363016626e2529fabe0c5aa5473621006ceb72a609eef2452e3b1b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Bit<a id="abbc5259d649363016626e2529fabe0c5a1ef22e535a2fc701cdafaffe74fc7490"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Bits<a id="abbc5259d649363016626e2529fabe0c5a3c0710aa6b054662f67b480712fa2b95"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Code<a id="abbc5259d649363016626e2529fabe0c5a4a6621856674f376740a1ba6efd809e3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Dag<a id="abbc5259d649363016626e2529fabe0c5ada09b995722faae2fac3dacfddd27999"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ElseKW<a id="abbc5259d649363016626e2529fabe0c5add6c7668426aa0bcce9f65adf90b78cd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Field<a id="abbc5259d649363016626e2529fabe0c5a746bc3776b8e263c46912952f7e3d544"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">In<a id="abbc5259d649363016626e2529fabe0c5a5fa7b4069ef3bd1ceb9f2caa315cf5ac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Include<a id="abbc5259d649363016626e2529fabe0c5ab9183e80a75491fb03dafb5c7334b206"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Int<a id="abbc5259d649363016626e2529fabe0c5abb824e612ba80ddfd262b018bf537595"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">List<a id="abbc5259d649363016626e2529fabe0c5afef9bccea014fbcc9d61070cb7dbb5ff"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">String<a id="abbc5259d649363016626e2529fabe0c5a394bf05139245f8e3ee22865dc9c1caf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Then<a id="abbc5259d649363016626e2529fabe0c5a0a3f5b60adefd865c58eacd375747316"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OBJECT_START_FIRST<a id="abbc5259d649363016626e2529fabe0c5add9085f1928d88045ae5348048f238a6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Assert<a id="abbc5259d649363016626e2529fabe0c5ab912134084f850ecf68862955821dcf0"></a></td>
<td class="doxyEnumItemDescription"> (= OBJECT_START_FIRST)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Class<a id="abbc5259d649363016626e2529fabe0c5ada3eb06ada644390db065d37b3fd87ac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Def<a id="abbc5259d649363016626e2529fabe0c5aceb138f68fe183995736614928e3394a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Defm<a id="abbc5259d649363016626e2529fabe0c5a7c24995e74158e2cb811f4ce442ba449"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Defset<a id="abbc5259d649363016626e2529fabe0c5a637350b60045090af105b1b2e6abdbe9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Deftype<a id="abbc5259d649363016626e2529fabe0c5a15e5c36c836815898cc9bcb823d133aa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Defvar<a id="abbc5259d649363016626e2529fabe0c5a28ac3fa09ce02c46bed697187add17a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Dump<a id="abbc5259d649363016626e2529fabe0c5a91b51d65bb7702eb087fb2cd735cc6a1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Foreach<a id="abbc5259d649363016626e2529fabe0c5aeadc4b3f44e71024da7f69e73a36df24"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">If<a id="abbc5259d649363016626e2529fabe0c5ab2ceb2a4ac0a01535be896234ce2d83c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Let<a id="abbc5259d649363016626e2529fabe0c5a8fafa1ff59af00a783108ebda48f52d2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MultiClass<a id="abbc5259d649363016626e2529fabe0c5a9705ec9113e3e375159a057a77325c8f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OBJECT_START_LAST<a id="abbc5259d649363016626e2529fabe0c5ad244467eb69de582e14f882fccfcf845"></a></td>
<td class="doxyEnumItemDescription"> (= MultiClass)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BANG_OPERATOR_FIRST<a id="abbc5259d649363016626e2529fabe0c5a13878ee469c6403100a398bca60a7638"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XConcat<a id="abbc5259d649363016626e2529fabe0c5a5e619bfe6e3576f4e30762fcd89fd981"></a></td>
<td class="doxyEnumItemDescription"> (= BANG_OPERATOR_FIRST)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XADD<a id="abbc5259d649363016626e2529fabe0c5ab53bfc4906c64a77a8b949d00dcdf36c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XSUB<a id="abbc5259d649363016626e2529fabe0c5a2b9baa42404e3df8c4dbddade04ad66c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XMUL<a id="abbc5259d649363016626e2529fabe0c5ad60fbbbf853f7d784cfd7e3a6139eedd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XDIV<a id="abbc5259d649363016626e2529fabe0c5a059111ec9a7cc3ba37cd6d5be02a6c56"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XNOT<a id="abbc5259d649363016626e2529fabe0c5a92af337ba38baeea36f7af17bd14d912"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XLOG2<a id="abbc5259d649363016626e2529fabe0c5a012f44802ed5e19c1e3f268b5304c3e8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XAND<a id="abbc5259d649363016626e2529fabe0c5a26e3ebb5bd26ece3dc4588ecc884f9a8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XOR<a id="abbc5259d649363016626e2529fabe0c5a1558fb27f0970c668a59c38f4776a302"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XXOR<a id="abbc5259d649363016626e2529fabe0c5a69d1696a733ea65dfdcbeb0dcb24751a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XSRA<a id="abbc5259d649363016626e2529fabe0c5a04e02115deb25646a5a71e3dc7daa2b6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XSRL<a id="abbc5259d649363016626e2529fabe0c5a2227887607391bafde87d2c39bec627b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XSHL<a id="abbc5259d649363016626e2529fabe0c5a783b904d2c5fb798308c44578713a591"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XListConcat<a id="abbc5259d649363016626e2529fabe0c5ada3fe9c96e771169e5601b9e2f2de059"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XListFlatten<a id="abbc5259d649363016626e2529fabe0c5ae3f27171e0a6e52067df8cdf3cda2287"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XListSplat<a id="abbc5259d649363016626e2529fabe0c5a061cbb7cb46a6ea2ab680ef745260bae"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XStrConcat<a id="abbc5259d649363016626e2529fabe0c5adf79c943252727b9f695adec3dbf9096"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XInterleave<a id="abbc5259d649363016626e2529fabe0c5a4f0dff20fb79f023de450b7a75e98146"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XSubstr<a id="abbc5259d649363016626e2529fabe0c5a9132373e72b422a9bbcde7d79d7358af"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XFind<a id="abbc5259d649363016626e2529fabe0c5a1a88673f7d9d5fe1cb1ff5abe81d04d8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XCast<a id="abbc5259d649363016626e2529fabe0c5a9a2b9bc9f58163e9594cdbca2448f19c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XSubst<a id="abbc5259d649363016626e2529fabe0c5af80adbb301e62db3df43b2591807d8d5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XForEach<a id="abbc5259d649363016626e2529fabe0c5ac95ec699302d8ea43b1fa32ade62bddb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XFilter<a id="abbc5259d649363016626e2529fabe0c5ac82edff85e70ceb4687a5af61d0bf9a7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XFoldl<a id="abbc5259d649363016626e2529fabe0c5a1a92764432d67b2c80bbe39054bbcc64"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XHead<a id="abbc5259d649363016626e2529fabe0c5a6d18a6a370bbcfdb80a8c6516ffef947"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XTail<a id="abbc5259d649363016626e2529fabe0c5ab0d63c95f25378bcf829978ea8aaf45b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XSize<a id="abbc5259d649363016626e2529fabe0c5a6ff0ea0d2e2ece39281bd4cd1d741e85"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XEmpty<a id="abbc5259d649363016626e2529fabe0c5a51720d5c279ad0688523616f55dc26a0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XInitialized<a id="abbc5259d649363016626e2529fabe0c5adaeef1552cd410e48b032159230a6f2d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XIf<a id="abbc5259d649363016626e2529fabe0c5a0667c742c86523e3b48cfb03351aec58"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XCond<a id="abbc5259d649363016626e2529fabe0c5a898ba94826d66cc34c19eea1c38b632f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XEq<a id="abbc5259d649363016626e2529fabe0c5afb9e21731f9e22d3c5b51dcd60d4203b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XIsA<a id="abbc5259d649363016626e2529fabe0c5a3ea4c99e29e170aa71dbf5cd16a7ea65"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XDag<a id="abbc5259d649363016626e2529fabe0c5ad9323d384b6bdf153725fcae7ba68b88"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XNe<a id="abbc5259d649363016626e2529fabe0c5a0d009a8dd4a144b766cd32fdf0df6126"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XLe<a id="abbc5259d649363016626e2529fabe0c5a87e256ba6a0db9ba76d47722d5c8b7fb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XLt<a id="abbc5259d649363016626e2529fabe0c5a8e13db1427a9f584205a110026e71ca1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XGe<a id="abbc5259d649363016626e2529fabe0c5aa8a82d026433b1a0bd216c111cf30080"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XGt<a id="abbc5259d649363016626e2529fabe0c5aebcfd1627a6b9d014813aa0fc0ff5bff"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XSetDagOp<a id="abbc5259d649363016626e2529fabe0c5adf3df8b056ec419c6aec01babb7ab45a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XGetDagOp<a id="abbc5259d649363016626e2529fabe0c5ab0f5e378f6e1d05637f03dcc08c47020"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XExists<a id="abbc5259d649363016626e2529fabe0c5a1c9cbe43d63fa3bfead18de065d125f1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XListRemove<a id="abbc5259d649363016626e2529fabe0c5aff87ae80027691451cb7bc26cf73d409"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XToLower<a id="abbc5259d649363016626e2529fabe0c5aa690c885ddaf9bf97665afc059763c38"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XToUpper<a id="abbc5259d649363016626e2529fabe0c5abd5cef2dbd542f3d8be008b9dd5a858f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XRange<a id="abbc5259d649363016626e2529fabe0c5a332b5bbabaf5bbe0e68e96445ce23261"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XGetDagArg<a id="abbc5259d649363016626e2529fabe0c5ad8efe2bb2935c415fb2eab0ae99df2ae"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XGetDagName<a id="abbc5259d649363016626e2529fabe0c5a31b6a116ea01f970b57b090efc1f476b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XSetDagArg<a id="abbc5259d649363016626e2529fabe0c5a0eb00767dc58be83b2f3b4c809021d82"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XSetDagName<a id="abbc5259d649363016626e2529fabe0c5aa0f2b471ae03bcbbd308ac4c920dc619"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XRepr<a id="abbc5259d649363016626e2529fabe0c5af8073683f4c7c5eb22f558a0e5ae307c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BANG_OPERATOR_LAST<a id="abbc5259d649363016626e2529fabe0c5abf0a8a44603218c4ba56be75626be18f"></a></td>
<td class="doxyEnumItemDescription"> (= XRepr)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRING_VALUE_FIRST<a id="abbc5259d649363016626e2529fabe0c5a3d6901abc28f6eea27dc3fe5dbff8d84"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Id<a id="abbc5259d649363016626e2529fabe0c5aca8a950a42e5a08dff888aeb505e685c"></a></td>
<td class="doxyEnumItemDescription"> (= STRING_VALUE_FIRST)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">StrVal<a id="abbc5259d649363016626e2529fabe0c5ada54f15a981c262b714e3278e0831e86"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VarName<a id="abbc5259d649363016626e2529fabe0c5a218a3df235546fc092fe0f463e6b714d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CodeFragment<a id="abbc5259d649363016626e2529fabe0c5a4e37458f80fae3c44a7e38f137713536"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRING_VALUE_LAST<a id="abbc5259d649363016626e2529fabe0c5ad8a2161ab6531c2a24ac491674e07f1f"></a></td>
<td class="doxyEnumItemDescription"> (= CodeFragment)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### isBangOperator() {#a430288ce6f4ab3a067e165aa0645ee3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::tgtok::isBangOperator (<a href="#abbc5259d649363016626e2529fabe0c5">tgtok::TokKind</a> Kind)</td>
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

<p>isBangOperator - Return true if this is a bang operator.</p>

<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>.</p>


<p>References <a href="#abbc5259d649363016626e2529fabe0c5a13878ee469c6403100a398bca60a7638">BANG_OPERATOR_FIRST</a> and <a href="#abbc5259d649363016626e2529fabe0c5abf0a8a44603218c4ba56be75626be18f">BANG_OPERATOR_LAST</a>.</p>

</div>
</div>

### isObjectStart() {#adedca5779d9bfd003dcd9b878aa8c406}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::tgtok::isObjectStart (<a href="#abbc5259d649363016626e2529fabe0c5">tgtok::TokKind</a> Kind)</td>
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

<p>isObjectStart - Return true if this is a valid first token for a statement.</p>

<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>.</p>


<p>References <a href="#abbc5259d649363016626e2529fabe0c5add9085f1928d88045ae5348048f238a6">OBJECT_START_FIRST</a> and <a href="#abbc5259d649363016626e2529fabe0c5ad244467eb69de582e14f882fccfcf845">OBJECT_START_LAST</a>.</p>

</div>
</div>

### isStringValue() {#aeb202308092eb993646d3f969e18e463}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::tgtok::isStringValue (<a href="#abbc5259d649363016626e2529fabe0c5">tgtok::TokKind</a> Kind)</td>
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

<p>isStringValue - Return true if this is a string value.</p>

<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>.</p>


<p>References <a href="#abbc5259d649363016626e2529fabe0c5a3d6901abc28f6eea27dc3fe5dbff8d84">STRING_VALUE_FIRST</a> and <a href="#abbc5259d649363016626e2529fabe0c5ad8a2161ab6531c2a24ac491674e07f1f">STRING_VALUE_LAST</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/tglexer/#a9fbd2a869619122ccc00185227129c6e">llvm::TGLexer::getCurStrVal</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
