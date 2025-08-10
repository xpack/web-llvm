---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/riscvisd
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `RISCVISD` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::RISCVISD { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">NodeType : unsigned { <a href="#ab68e2d65ea9915ffaac8334a3b8bf882">...</a> }</td>
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

### NodeType {#ab68e2d65ea9915ffaac8334a3b8bf882}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::RISCVISD::NodeType : unsigned</td>
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
<td class="doxyEnumItemName">FIRST_NUMBER<a id="ab68e2d65ea9915ffaac8334a3b8bf882a9f3e18a0fc8f727572d80995515c7172"></a></td>
<td class="doxyEnumItemDescription"> (= ISD::BUILTIN_OP_END)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RET_GLUE<a id="ab68e2d65ea9915ffaac8334a3b8bf882a2529f5444ca0d8f4b5dc020e9b62d7fc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRET_GLUE<a id="ab68e2d65ea9915ffaac8334a3b8bf882adf8d1801795610f18042dc7eeb5caf3e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRET_GLUE<a id="ab68e2d65ea9915ffaac8334a3b8bf882ade4f27577199039c9f0fd984d9e6414a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a986caa9afda2b8fd5a8280066c71f63b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TAIL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a35a1690fd8f9d447812d379c8374fc8d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SELECT_CC<a id="ab68e2d65ea9915ffaac8334a3b8bf882a09e6b13077c6bab69bd5253e14e48520"></a></td>
<td class="doxyEnumItemDescription">Select with condition operator - This selects between a true value and a false value (ops #3 and #4) based on the boolean result of comparing the lhs and rhs (ops #0 and #1) of a conditional expression with the condition code in op #2, a XLenVT constant from the <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07">ISD::CondCode</a> enum</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BR_CC<a id="ab68e2d65ea9915ffaac8334a3b8bf882a5cc9db8f9ff5ca0d9b57d6d66006772c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BuildGPRPair<a id="ab68e2d65ea9915ffaac8334a3b8bf882a7ad8eae84b0d5313d06e6662a823dd1e"></a></td>
<td class="doxyEnumItemDescription">Turn a pair of <span class="doxyComputerOutput">i&lt;xlen&gt;</span>s into an even-odd register pair (<span class="doxyComputerOutput">untyped</span>)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SplitGPRPair<a id="ab68e2d65ea9915ffaac8334a3b8bf882aa4911c97824c2f6defbba3953ebbc370"></a></td>
<td class="doxyEnumItemDescription">Turn an even-odd register pair (<span class="doxyComputerOutput">untyped</span>) into a pair of <span class="doxyComputerOutput">i&lt;xlen&gt;</span>s</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BuildPairF64<a id="ab68e2d65ea9915ffaac8334a3b8bf882a706088c700a61880a610f9ba149a6d03"></a></td>
<td class="doxyEnumItemDescription">Turns a pair of <span class="doxyComputerOutput">i32</span>s into an <span class="doxyComputerOutput">f64</span></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SplitF64<a id="ab68e2d65ea9915ffaac8334a3b8bf882a02503efde5e7e2b5b037d10199834356"></a></td>
<td class="doxyEnumItemDescription">Turns a <span class="doxyComputerOutput">f64</span> into a pair of <span class="doxyComputerOutput">i32</span>s</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADD_LO<a id="ab68e2d65ea9915ffaac8334a3b8bf882af67faecb539beaa37dfcfff1252c9c60"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HI<a id="ab68e2d65ea9915ffaac8334a3b8bf882a43d3181277d594b2aea1fd3faa40fde2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLA<a id="ab68e2d65ea9915ffaac8334a3b8bf882a7c3c645c0e4f4f74bec3e2135c5e809f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADD_TPREL<a id="ab68e2d65ea9915ffaac8334a3b8bf882aac83f390569ec0d6b56520217a880bb2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MULHSU<a id="ab68e2d65ea9915ffaac8334a3b8bf882adacfe7d36e22a0f417640d725c995b2c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SHL_ADD<a id="ab68e2d65ea9915ffaac8334a3b8bf882af38d0cbab638b2d3cc6c5303fc3a4911"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SLLW<a id="ab68e2d65ea9915ffaac8334a3b8bf882a0eddf77c4e0287a09acf158c434faf45"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRAW<a id="ab68e2d65ea9915ffaac8334a3b8bf882a64927d70afbf447d7c36fa86496df0a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRLW<a id="ab68e2d65ea9915ffaac8334a3b8bf882a0151fd91dfddcfc99bb01b041c128e5e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIVW<a id="ab68e2d65ea9915ffaac8334a3b8bf882a02a655131d3e2e27d889e16c8af5de89"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIVUW<a id="ab68e2d65ea9915ffaac8334a3b8bf882ad1e822148613208ad3454a5846320c3b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">REMUW<a id="ab68e2d65ea9915ffaac8334a3b8bf882adcdd29ca8504487f10692af6034cb64f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROLW<a id="ab68e2d65ea9915ffaac8334a3b8bf882a2b2dd2bf0e3e0bdfa3ee4ea3fb024cf5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RORW<a id="ab68e2d65ea9915ffaac8334a3b8bf882a3f464ec6c3904381aa268a2d3ac5d41c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CLZW<a id="ab68e2d65ea9915ffaac8334a3b8bf882a58cde65efe901151c99aec10d2171178"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CTZW<a id="ab68e2d65ea9915ffaac8334a3b8bf882a25f265364fd27551b74630b7c3e0cac4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABSW<a id="ab68e2d65ea9915ffaac8334a3b8bf882ae04d54146b7e6a06195765ffcc12e8d5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMV_H_X<a id="ab68e2d65ea9915ffaac8334a3b8bf882a8133bf609ca1e40ecb0622ed5e559fcc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMV_X_ANYEXTH<a id="ab68e2d65ea9915ffaac8334a3b8bf882ab4c9e20a9f1c79840fce2a9045c0045f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMV_X_SIGNEXTH<a id="ab68e2d65ea9915ffaac8334a3b8bf882a40ce5d50efbdb297bda9d5d8aa54223e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMV_W_X_RV64<a id="ab68e2d65ea9915ffaac8334a3b8bf882af4707e0cbdd66af52d6f4ea39d7c2cdf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMV_X_ANYEXTW_RV64<a id="ab68e2d65ea9915ffaac8334a3b8bf882afbbe6bca566a163966259135ca1be0ec"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCVT_X<a id="ab68e2d65ea9915ffaac8334a3b8bf882a9c219dbc3c9d6eb8b1630c28f6d30c78"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCVT_XU<a id="ab68e2d65ea9915ffaac8334a3b8bf882ae70f900772f7bd50faea37b91e7e1d1f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCVT_W_RV64<a id="ab68e2d65ea9915ffaac8334a3b8bf882a618d5a6664a810012dc4e5a6d15b5f02"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCVT_WU_RV64<a id="ab68e2d65ea9915ffaac8334a3b8bf882a682e0436a68e57848468fe29957a9be5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FROUND<a id="ab68e2d65ea9915ffaac8334a3b8bf882a259fee2ccb7dbe4736f8f4252935d0af"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCLASS<a id="ab68e2d65ea9915ffaac8334a3b8bf882a30649dc7c99629664ee5b4eb89706611"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FSGNJX<a id="ab68e2d65ea9915ffaac8334a3b8bf882a1110bcde4a3f6b8b8a181d63842ec459"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMAX<a id="ab68e2d65ea9915ffaac8334a3b8bf882a924130a3118790579f30ba8c88aa632d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMIN<a id="ab68e2d65ea9915ffaac8334a3b8bf882ad26deca50107433732555a23c766a5b1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FLI<a id="ab68e2d65ea9915ffaac8334a3b8bf882ab0845eda3b49e50a0d7361e62d3b9e3a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">READ_COUNTER_WIDE<a id="ab68e2d65ea9915ffaac8334a3b8bf882aa61da52271cc3239abed1ae63deb2717"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BREV8<a id="ab68e2d65ea9915ffaac8334a3b8bf882ae879738808efc95e3ae4a57057c44d37"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ORC_B<a id="ab68e2d65ea9915ffaac8334a3b8bf882a3dfbc04f302b45dfe7b140ffcf619671"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ZIP<a id="ab68e2d65ea9915ffaac8334a3b8bf882ab9d1f1a6e11c8790522300657503b379"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNZIP<a id="ab68e2d65ea9915ffaac8334a3b8bf882aae521306654f6ff44aa4da50c5daaa9b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CLMUL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a2f7f266cf7627e07d5c8af529f51a9a7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CLMULH<a id="ab68e2d65ea9915ffaac8334a3b8bf882adf445963e7cd3a4bb502e7d774a606ed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CLMULR<a id="ab68e2d65ea9915ffaac8334a3b8bf882a42da6c25f288165d75c0972bf78efa70"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SHA256SIG0<a id="ab68e2d65ea9915ffaac8334a3b8bf882a0cf91b8c8ceb92515aad65401c8ee8a6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SHA256SIG1<a id="ab68e2d65ea9915ffaac8334a3b8bf882a7f905fd292cd485eeca6bbb305ff7d9c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SHA256SUM0<a id="ab68e2d65ea9915ffaac8334a3b8bf882a3dac1968f12781ef3373cf639d388e78"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SHA256SUM1<a id="ab68e2d65ea9915ffaac8334a3b8bf882a46c236f86bdc0f65501afe596804ae54"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SM4KS<a id="ab68e2d65ea9915ffaac8334a3b8bf882aa3fe6991449df0c3f5104fb7ce0537f4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SM4ED<a id="ab68e2d65ea9915ffaac8334a3b8bf882a220f4a545d878426ee6256c488f5741c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SM3P0<a id="ab68e2d65ea9915ffaac8334a3b8bf882ad701b8c5e4f4923efc0c3803530da2cc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SM3P1<a id="ab68e2d65ea9915ffaac8334a3b8bf882a87ff277048d6c899dfb5ac088978f423"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOPR<a id="ab68e2d65ea9915ffaac8334a3b8bf882a528464a7694cd1c8fa8548af17d90895"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOPRR<a id="ab68e2d65ea9915ffaac8334a3b8bf882aa9818e42a91f52cebd32c4c719433ff5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIRST_VL_VECTOR_OP<a id="ab68e2d65ea9915ffaac8334a3b8bf882aae20a47c8e61b216d681f61b996c1ff6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMV_V_V_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a91e391136a9fe4639b763f8154e69e54"></a></td>
<td class="doxyEnumItemDescription"> (= FIRST_VL_VECTOR_OP)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMV_V_X_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a127afe58529ef366a343a51786dcc3d4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFMV_V_F_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a3d046b0b663cacd2116c6d35498ab5ab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMV_X_S<a id="ab68e2d65ea9915ffaac8334a3b8bf882a44936a9406f5a7b50871b7d930686f13"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMV_S_X_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a55a5f5a5eb10f4ca81928a4cee11ab52"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFMV_S_F_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a41320aaa5a0fc5f6704fba144635bcab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SPLAT_VECTOR_SPLIT_I64_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882aa282e2548f435b7fdd280b478a3623aa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TRUNCATE_VECTOR_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882aa6e01bc76a36f1f8564b7dc17c32982e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TRUNCATE_VECTOR_VL_SSAT<a id="ab68e2d65ea9915ffaac8334a3b8bf882aacd29c3ee3f3a2e00901869754a15d78"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TRUNCATE_VECTOR_VL_USAT<a id="ab68e2d65ea9915ffaac8334a3b8bf882a3c7e17c2d66bd54551745d4082ca1625"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSLIDEUP_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882afc69d14b3c97070a6831ed1424153c86"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSLIDEDOWN_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a5429b143bb1eec9ca397b7cf0479da00"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSLIDE1UP_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a9272a9ead579ffbef3acd1f4a0cd76bd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSLIDE1DOWN_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a23d14818f81aad300df2209e8d17c916"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFSLIDE1UP_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a3b2d53f124a8796f923c69122f65ec73"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFSLIDE1DOWN_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882aa57643751b4ddd4c60fedd850a3aa02d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VID_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a5d253c7c526ad05ab1dcf364cbf4c356"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFNCVT_ROD_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a8f22643b59196471e2849acbcc77b37e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECREDUCE_ADD_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a441ca94d724759ea0f7d27d9c08591e4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECREDUCE_UMAX_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a35042d77bc98d6ba1c7224cc9c56d759"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECREDUCE_SMAX_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a8670593a003c11a12c4dc798b31132a2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECREDUCE_UMIN_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882acfda1a08113e614b22fb444986ce2d3c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECREDUCE_SMIN_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882ae3df439c9fa3393e4feba13020175f75"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECREDUCE_AND_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a8cf76a89cf1f863ec39c015a17a97b02"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECREDUCE_OR_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a47051b3dc27dbce86fc32966af6267bb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECREDUCE_XOR_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a35dc23cb33ec6981a9dfbbb1ca1e1e41"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECREDUCE_FADD_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a75f87d98f8adfcddcde925073ed1cc66"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECREDUCE_SEQ_FADD_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882aec9c11cf75a9e7379178081bab60e9e5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECREDUCE_FMIN_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882ae497597f831b4bb0d6a48f7834e24388"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECREDUCE_FMAX_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a894c5950a1681e73722df7871782efd8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADD_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882ae31415e16e999fc747eb81e9e48689b1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AND_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882aa1159bbaea3e76d1fd178826d4fc12e0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MUL_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a386e45450adba2e23952cd9b61c99387"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OR_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a3cbea9649efa1b34834872124369b436"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SDIV_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a336c02c0a2b62a6862423c72dd688d1d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SHL_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a7e7efe8f44a6631a42aaaf19a3448d9b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SREM_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a6c31efe51a4db6beab7e7bafd6fbb2ea"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRA_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a87eb4ef5f6fea6a2a78ba058a92d6410"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRL_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882acb304e1d1c5d70db020bc6d4dfbb36d4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROTL_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882acd377aef875f2401f5ba537a2259b3eb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROTR_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a8fd0be9a8b97a2dca833f55b9c68c8d2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SUB_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a14a2c20051cd4652b3ab86b25e931525"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UDIV_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a976461cd91b865eb2716eb1b4ee0bd9c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UREM_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a540ff35c7091fe06878851bbb296bb82"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XOR_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a642410fd45189dbfd73b93471e4528fd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMIN_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a2c237a8c9afee374d7da7a1ae3bdf1fe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMAX_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a604cf9109eda78ed8c83add2976fa35a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UMIN_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882ab46ccc6a148613f625b04ae6e35919a1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UMAX_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a6cf70ce015074642428d3b36b0bead34"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BITREVERSE_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a5291ec2a5e4906a5aef1b967ea5d4c94"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BSWAP_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a944613972c8c09d62ad18a14b3931fab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CTLZ_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a35567006326e74ccfb6481646ee89ee0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CTTZ_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a1b6af3fc67ca169c6827a6793b07369e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CTPOP_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a56830d09c23604057e1dc34cbc2e0706"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SADDSAT_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a917a636bfbd1979ddf8d2e81d6975fae"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UADDSAT_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a176af8b0a32c4ec90011ff207febbd37"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SSUBSAT_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882ad4a2793ab24001ee82e19cfae16e10f8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">USUBSAT_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a8ff3f2a374de7f1e9df808bc305cbbb6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AVGFLOORS_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a4d9f06eefe16e0834833e097dc9a0be4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AVGFLOORU_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a0127fc79fefa79df94dcfeceaa544f65"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AVGCEILS_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882ae9ad8d59d50128393eaf4bf622da9ab9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AVGCEILU_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a631f02d80a350696e4c402c1aa3d80cf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MULHS_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a3b092583f7170b6c506bb695be3bc34e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MULHU_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a188dd2752a6d584e2d2716323e8bacf9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FADD_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882acca75875c0af2b5d293e0d1cfd2075e7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FSUB_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882ab47e9a22d871e8c10e5be7c837d2c698"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMUL_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a2214f5316d8e125ed7d4d20b1cefb182"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FDIV_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a6c7c3622a8c960d2a961314ab441263f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFMIN_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882ae4a609f2eecdef457c0d0823914cabbc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFMAX_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a932304d00de7c59f61544ed3d0db8468"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FNEG_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882af48abd23c08d240016f2290f7087b908"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FABS_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a15c239045d4fc576598d5f4a81b1d3f5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FSQRT_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a7fd2772591ea4a1156d20f8631c61040"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCLASS_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a17f96b71838caa6f2bdcb6b29630f777"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCOPYSIGN_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882ad1671325d433d94577daabeb1b0f8495"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFCVT_RTZ_X_F_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882ae16ea5235735d1dc0164d6efb8ae6c1f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFCVT_RTZ_XU_F_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882ab495b71cbb4592854336ac1cf850c5a2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFROUND_NOEXCEPT_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882ada40025e4ce5f83662473adea6186540"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFCVT_RM_X_F_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a95c7f0037054da1e9e12837c72f3db9c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFCVT_RM_XU_F_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a863f32fbb2ac2aedf1d5984a73d67b87"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SINT_TO_FP_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a58fb9f0403605b8a4c19666c8b31c11e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UINT_TO_FP_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a4d014c137fd643784e543210e6f2d8fa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFCVT_RM_F_X_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a0afdeee32fa4f25bbdaec735366ce6dd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFCVT_RM_F_XU_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882ab67e816d2601aa62413e004fb0cfd9b0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FP_ROUND_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882aff3e72e0413ca96506f3f864fb9ea60e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FP_EXTEND_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a2d9e7f8f372064f120c7102fbc7fdbed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFMADD_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a5157c18d075bbbc3b6ce91de07edcc7f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFNMADD_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882ae73310d12703d3bc8aa5ec0ba9b87d6c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFMSUB_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882ac0ebb4a665039e56d0ae06e6cc83ca9e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFNMSUB_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882abc29e48c549a16883a67a05fc0754f40"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFWMADD_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882ad2c9653aae605a17bc689418fa22ee57"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFWNMADD_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882af6c5203fba9bad8b65e2392faee102b1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFWMSUB_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a912c2473049956164b2789fb9186932d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFWNMSUB_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a85f255c876e7fbea9e885bd2cd22a8a5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VWMUL_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a74afd07429ec343a7cbe1b58790a0d41"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VWMULU_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a0e872ddbd914219b650c1c5856e195e9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VWMULSU_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a84f25091f4381de64087f9bf5906113e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VWADD_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a62edacb6d4d52e4d3206ecffbecd7db3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VWADDU_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a15f31bbcbb2d8da15abfc71db97eb870"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VWSUB_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a852d0a6914208c69c08937b87f1564be"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VWSUBU_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a440b50009035fc04b55074c1417ef2f7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VWADD_W_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a50f274b26dbe5d22c120a51113541af6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VWADDU_W_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882ad4d7b0fd6ff5d187cd6af51af7f44f0e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VWSUB_W_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a147a1fead91935ddd20bff698a5f7e06"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VWSUBU_W_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a6bd80026dd613fdb2f48b7234da832ce"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VWSLL_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a2a577eae33a27da1292c6faf1b9573f7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFWMUL_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a84337401b270768506507b7753d102a7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFWADD_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882ac59f2ed64c2111f79237a4f1ed969988"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFWSUB_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882adfdbbbc6eaecf2917ed49a7aeeb5a2a0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFWADD_W_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882afbb33522f428f63e33c30ea89d6d2864"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFWSUB_W_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a6ede6deabb2a6174ec742114d79041dd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VWMACC_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a84b91f80289999fb97308a69d84bff8c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VWMACCU_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a7b7ddafe2f46cbb5c65923d829d797d8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VWMACCSU_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a9f23e70c88a48eefa33e982ce731db02"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETCC_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882aada01fda854fba264355f84b392b568d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMERGE_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a4a0d217afa7276f9e19fbb2853e7104a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMAND_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a2d7255638787e8e9aba637ccf9971bf8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMOR_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a5fb6a9312a657fb5b468f61a7935474e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMXOR_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a75e266b0693a3cc38e1a300670347fb8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMCLR_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882ad9543f3eeda270a62a4fa25e6e51c14f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMSET_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a149158b42231b59d066b9119b641181c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VRGATHER_VX_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a52484b15ed0610388801f7ec5a183d33"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VRGATHER_VV_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882ad1a6f9d5ee3c4a7c9f77c36bb31ecd64"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VRGATHEREI16_VV_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882ad3c885e1e6f1dd83c08812a37f229885"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSEXT_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a2be5d0001da98e7c524aa9d212419f7d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VZEXT_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882aab563d8b09e3a65dbc2bd73051b074cc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VCPOP_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a975f1dac2018009d4686ca8b947cafe6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFIRST_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a84bb4458abdbc1f5e9d6cbf05c89ad00"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LAST_VL_VECTOR_OP<a id="ab68e2d65ea9915ffaac8334a3b8bf882a8f3850eb72c4366e4025c06c2803e7f2"></a></td>
<td class="doxyEnumItemDescription"> (= VFIRST_VL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">READ_VLENB<a id="ab68e2d65ea9915ffaac8334a3b8bf882a992168b231b64dd1e1cd95a2c48b2091"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">READ_CSR<a id="ab68e2d65ea9915ffaac8334a3b8bf882a9d1bab1c823ae9beb1a89513afa51881"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WRITE_CSR<a id="ab68e2d65ea9915ffaac8334a3b8bf882a10194f64fbe96efea7e35edefc80ae35"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SWAP_CSR<a id="ab68e2d65ea9915ffaac8334a3b8bf882a6b2d4974f33790481c59243261704e13"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CZERO_EQZ<a id="ab68e2d65ea9915ffaac8334a3b8bf882a1c72836a8698f8704b0a0b9f772270c8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CZERO_NEZ<a id="ab68e2d65ea9915ffaac8334a3b8bf882a7bbf41f44bd9e7ce4b83c1da5cc462dc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SW_GUARDED_BRIND<a id="ab68e2d65ea9915ffaac8334a3b8bf882a02a8cc680cd04ccb646bec5795b1ddf0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SW_GUARDED_CALL<a id="ab68e2d65ea9915ffaac8334a3b8bf882adf38852959a17b6fb21c1db0200dc784"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SW_GUARDED_TAIL<a id="ab68e2d65ea9915ffaac8334a3b8bf882afe316e0a0c6560db7a877f7037bd0cdb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_VC_XV_SE<a id="ab68e2d65ea9915ffaac8334a3b8bf882a82081fd5653b7a3ca3cae061275451a7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_VC_IV_SE<a id="ab68e2d65ea9915ffaac8334a3b8bf882ae5bb9b79d69fb374e13d9ed078a9d933"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_VC_VV_SE<a id="ab68e2d65ea9915ffaac8334a3b8bf882ac171456dadbee27b62f1da1241cb354c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_VC_FV_SE<a id="ab68e2d65ea9915ffaac8334a3b8bf882a984d7e9f7626bf314b345289ab0e28ef"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_VC_XVV_SE<a id="ab68e2d65ea9915ffaac8334a3b8bf882ad0e3c1790664113739b8bc4bf17002c7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_VC_IVV_SE<a id="ab68e2d65ea9915ffaac8334a3b8bf882af6fd84506a33cd1ed3bd610c735a1afe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_VC_VVV_SE<a id="ab68e2d65ea9915ffaac8334a3b8bf882a6cac61499af050759fc941c05ad6d896"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_VC_FVV_SE<a id="ab68e2d65ea9915ffaac8334a3b8bf882ae89fc49b4df6460a43d96e9e96477c02"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_VC_XVW_SE<a id="ab68e2d65ea9915ffaac8334a3b8bf882aad602cb62d8774c7636ac8771b7b14a0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_VC_IVW_SE<a id="ab68e2d65ea9915ffaac8334a3b8bf882acc275ce1b9b3804742e8b605cd4d91a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_VC_VVW_SE<a id="ab68e2d65ea9915ffaac8334a3b8bf882ac80185a537f46c048d59c02b6d923a2a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_VC_FVW_SE<a id="ab68e2d65ea9915ffaac8334a3b8bf882a667e598828637b8bc0b4786bb502ee1b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_VC_V_X_SE<a id="ab68e2d65ea9915ffaac8334a3b8bf882a0766beab1973676fc5a02b6ac265d71f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_VC_V_I_SE<a id="ab68e2d65ea9915ffaac8334a3b8bf882a6c5c5ebe8b1de6c2e0e3e7feb9e9e97f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_VC_V_XV_SE<a id="ab68e2d65ea9915ffaac8334a3b8bf882adc3732dacaa9ad355f1a659d8e036153"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_VC_V_IV_SE<a id="ab68e2d65ea9915ffaac8334a3b8bf882ac6d0d511fe2e96a30b20f62fd9aaf574"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_VC_V_VV_SE<a id="ab68e2d65ea9915ffaac8334a3b8bf882a686fbe41e0ff111d2006de5b4da61d74"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_VC_V_FV_SE<a id="ab68e2d65ea9915ffaac8334a3b8bf882a013dabc07571767bbca41a7c68dcc366"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_VC_V_XVV_SE<a id="ab68e2d65ea9915ffaac8334a3b8bf882a5e249b4dfa9a6053a0a98f4f844546c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_VC_V_IVV_SE<a id="ab68e2d65ea9915ffaac8334a3b8bf882a796c6e5a201e0d22a1f79b122de11fd7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_VC_V_VVV_SE<a id="ab68e2d65ea9915ffaac8334a3b8bf882aa9dde2278fcdcba29118f8a24ba65431"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_VC_V_FVV_SE<a id="ab68e2d65ea9915ffaac8334a3b8bf882a49aba62f2403865f6c3bf81f0ed2c45e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_VC_V_XVW_SE<a id="ab68e2d65ea9915ffaac8334a3b8bf882a4eb34fcfe8cd358513f0be14464bd8d4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_VC_V_IVW_SE<a id="ab68e2d65ea9915ffaac8334a3b8bf882a7ad26fcb135c80b741acc2a903abac3d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_VC_V_VVW_SE<a id="ab68e2d65ea9915ffaac8334a3b8bf882a0b679a7d2953400e38663b3e8ed2dcaa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SF_VC_V_FVW_SE<a id="ab68e2d65ea9915ffaac8334a3b8bf882a670a27102d6c614679b0e9a662354929"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PROBED_ALLOCA<a id="ab68e2d65ea9915ffaac8334a3b8bf882ae3ba21c21eca281abe240f8992bbc6a7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TUPLE_INSERT<a id="ab68e2d65ea9915ffaac8334a3b8bf882ae47a7836f9d335899c477da04c5e56f4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TUPLE_EXTRACT<a id="ab68e2d65ea9915ffaac8334a3b8bf882af5cd9f36ca49bedc10a803bc45e3c42b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIRST_STRICTFP_OPCODE<a id="ab68e2d65ea9915ffaac8334a3b8bf882a4c047106e0923c97ce6f348c462d3d49"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FCVT_W_RV64<a id="ab68e2d65ea9915ffaac8334a3b8bf882a6e411d624fa28f7dcdc9884c9b20b465"></a></td>
<td class="doxyEnumItemDescription"> (= FIRST_STRICTFP_OPCODE)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FCVT_WU_RV64<a id="ab68e2d65ea9915ffaac8334a3b8bf882aedc6bc94076e9478c15b9c3fc28be5bb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FADD_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882aacf8d0773be7b46f42ba08b44af89f1e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FSUB_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882ab10d7f9c7e81d83d5467407120fdcc5a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FMUL_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a143fa1ca81c01c10da60ce7cfdcee227"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FDIV_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882ab2a53564d2673992ac7af60ab6326c82"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FSQRT_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882aba089749217172b72a07bd93b6a44b67"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_VFMADD_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a7f6e002556f47535b062912c56017212"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_VFNMADD_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a942ef3fbd0a191505515f351d8b502c2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_VFMSUB_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882ad5465478150b075e4ce9a8ef7b5b5c4b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_VFNMSUB_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a1b4516fb9000b97962044b7e81bc870a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FP_ROUND_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882ace2fb30d24301fbcd86b2c3e9e89fc59"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FP_EXTEND_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882acddd0428f49d36a10f3a36d4502592b4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_VFNCVT_ROD_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882af67e5f1e2eac5e393cdf56e9ef8d09f3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_SINT_TO_FP_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a1bae0ea1635c9e42c8465d0d5e5482c5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_UINT_TO_FP_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a1b4dc1016ec8e6945d393d7a3a77daa0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_VFCVT_RM_X_F_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882ab8d83393c652616433f10b70427d9273"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_VFCVT_RTZ_X_F_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882ab06a01766879e7c59fa73d92adcb3958"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_VFCVT_RTZ_XU_F_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a23d0fa3f5ccf8ab69a3c3f38aee3a867"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FSETCC_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a23dbc2c81ecb298c636087d1d5ae337b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FSETCCS_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a7de8aea51eea015c08bda4ef6e7bfddb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_VFROUND_NOEXCEPT_VL<a id="ab68e2d65ea9915ffaac8334a3b8bf882a907dd0f017d32ccf666c2f5cf2228192"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LAST_STRICTFP_OPCODE<a id="ab68e2d65ea9915ffaac8334a3b8bf882abf4cdbf80af2b303061c05e9548b65b6"></a></td>
<td class="doxyEnumItemDescription"> (= STRICT_VFROUND_NOEXCEPT_VL)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIRST_MEMORY_OPCODE<a id="ab68e2d65ea9915ffaac8334a3b8bf882ac6665067ee013667604399cdab66d75d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TH_LWD<a id="ab68e2d65ea9915ffaac8334a3b8bf882aaa5f3e150f765abe4450dc8121773223"></a></td>
<td class="doxyEnumItemDescription"> (= FIRST_MEMORY_OPCODE)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TH_LWUD<a id="ab68e2d65ea9915ffaac8334a3b8bf882a87faba7d8e18b3361978fded5a3061fd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TH_LDD<a id="ab68e2d65ea9915ffaac8334a3b8bf882afb54f472974e391978cd9f935bc61918"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TH_SWD<a id="ab68e2d65ea9915ffaac8334a3b8bf882a40b78a990ae7613fb7d3e2be92be39b1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TH_SDD<a id="ab68e2d65ea9915ffaac8334a3b8bf882ac33b323edf385572e71666a04670b170"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LAST_MEMORY_OPCODE<a id="ab68e2d65ea9915ffaac8334a3b8bf882a3574507b9d304ae6afcd6f109db53921"></a></td>
<td class="doxyEnumItemDescription"> (= TH_SDD)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-h">RISCVISelLowering.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-h">RISCVISelLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
