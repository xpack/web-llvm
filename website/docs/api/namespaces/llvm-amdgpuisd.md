---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/amdgpuisd
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `AMDGPUISD` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::AMDGPUISD { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">NodeType : unsigned { <a href="#a739d53294bc38cd6b0b23332f9994c0e">...</a> }</td>
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

### NodeType {#a739d53294bc38cd6b0b23332f9994c0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AMDGPUISD::NodeType : unsigned</td>
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
<td class="doxyEnumItemName">FIRST_NUMBER<a id="a739d53294bc38cd6b0b23332f9994c0ea902721e90278dbb693ebec556f0718a3"></a></td>
<td class="doxyEnumItemDescription"> (= ISD::BUILTIN_OP_END)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BRANCH_COND<a id="a739d53294bc38cd6b0b23332f9994c0ea3710f7b2b548ead08130e71d2d63edef"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALL<a id="a739d53294bc38cd6b0b23332f9994c0ea73af676f5d9efdc09939270c55edff90"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TC_RETURN<a id="a739d53294bc38cd6b0b23332f9994c0ea94ca5748ef974a95fe92f90774617d92"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TC_RETURN_GFX<a id="a739d53294bc38cd6b0b23332f9994c0eaf327486e149f6dcb9bcf1d9fd6fc8d52"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TC_RETURN_CHAIN<a id="a739d53294bc38cd6b0b23332f9994c0ea225d900100a1e02744d46cc266b1c433"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TRAP<a id="a739d53294bc38cd6b0b23332f9994c0ea86c25f116c7caed40b1cf3c083ca08e1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IF<a id="a739d53294bc38cd6b0b23332f9994c0eac5f4a93ee302ab324b2d6be4da7d1995"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ELSE<a id="a739d53294bc38cd6b0b23332f9994c0ea0173ca5cd8965ff549096df6c0869f0c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LOOP<a id="a739d53294bc38cd6b0b23332f9994c0ea60d5ad554c76e8f21403ebedf166f15c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ENDPGM<a id="a739d53294bc38cd6b0b23332f9994c0ea9f20403af085ff34136c8c284d6fad8c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ENDPGM_TRAP<a id="a739d53294bc38cd6b0b23332f9994c0eaf099be6496682e994a62e74bff9667c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SIMULATED_TRAP<a id="a739d53294bc38cd6b0b23332f9994c0ea5188e478e6689c123b7f5d64dfaaed63"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RETURN_TO_EPILOG<a id="a739d53294bc38cd6b0b23332f9994c0eabb3b51ac8e54e86b5464018c02939c55"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RET_GLUE<a id="a739d53294bc38cd6b0b23332f9994c0ea4cbd4dc4742ccef757e33f0752a15e69"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WAVE_ADDRESS<a id="a739d53294bc38cd6b0b23332f9994c0eafc9e8f6f7cbd326bc7d7456f711ea223"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DWORDADDR<a id="a739d53294bc38cd6b0b23332f9994c0ea6166b5d53cc9816ecd1223614b964fd9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FRACT<a id="a739d53294bc38cd6b0b23332f9994c0ea79067f8d6a2c24f4d33fc9da493a2037"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CLAMP<a id="a739d53294bc38cd6b0b23332f9994c0eafcbfa7a671e1486a0322c51bdcdb0d7c"></a></td>
<td class="doxyEnumItemDescription">CLAMP value between 0.0 and 1.0</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETCC<a id="a739d53294bc38cd6b0b23332f9994c0ea4abad462fa316c06e5d0c9c80e5490ec"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DENORM_MODE<a id="a739d53294bc38cd6b0b23332f9994c0eab0d1573559f78092c7c0bf946ef9b10c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMA_W_CHAIN<a id="a739d53294bc38cd6b0b23332f9994c0ea6ea93bd531619261a61f34eb59c5e7d2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMUL_W_CHAIN<a id="a739d53294bc38cd6b0b23332f9994c0eaa9b6b15abc704da34341aa029217d8a5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COS_HW<a id="a739d53294bc38cd6b0b23332f9994c0ea4d3421b2a779f5f0c5970c8f5f550c76"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SIN_HW<a id="a739d53294bc38cd6b0b23332f9994c0eadc97b8e5166b4d4370009a552c0f1f73"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMAX_LEGACY<a id="a739d53294bc38cd6b0b23332f9994c0ea74d570da8b86d1a5f225daca0bd5f56a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMIN_LEGACY<a id="a739d53294bc38cd6b0b23332f9994c0eabaf5be9cbc3336e4d547efa4ac1c9c6d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMAX3<a id="a739d53294bc38cd6b0b23332f9994c0eae964dd93e7a7fdbbe3e2ded767b6743e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMAX3<a id="a739d53294bc38cd6b0b23332f9994c0eaf7d331417b4676e475fa1a9c6c556b0b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UMAX3<a id="a739d53294bc38cd6b0b23332f9994c0ea15d564e330de468ec9ec7869c4906c45"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMIN3<a id="a739d53294bc38cd6b0b23332f9994c0ea9d3121f4e456879833fdb42c71707495"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMIN3<a id="a739d53294bc38cd6b0b23332f9994c0eae580f8cbe220058dba91ec0d8976727e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UMIN3<a id="a739d53294bc38cd6b0b23332f9994c0eabe3bfee03d3544d92d8b5a4f180f15e5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMED3<a id="a739d53294bc38cd6b0b23332f9994c0ea95a3a9fcf85d6bfad93662a37fdea331"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMED3<a id="a739d53294bc38cd6b0b23332f9994c0eaab46dcb22e0120027336ef02f78080ba"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UMED3<a id="a739d53294bc38cd6b0b23332f9994c0ea421b46b3ade824d5fbf027a3f674db46"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMAXIMUM3<a id="a739d53294bc38cd6b0b23332f9994c0ea35b28e52da90578ab45a3fcf521d1383"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMINIMUM3<a id="a739d53294bc38cd6b0b23332f9994c0eafaa1281d8a0144afb7fcbc03366af1fc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FDOT2<a id="a739d53294bc38cd6b0b23332f9994c0ea9274b426ddcae6f57d1e4ae38e81bdc1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">URECIP<a id="a739d53294bc38cd6b0b23332f9994c0ea1be6f435b11e6bd74678117ccadc9117"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIV_SCALE<a id="a739d53294bc38cd6b0b23332f9994c0ea0819f8cbdd0851cea7a14606204c92fa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIV_FMAS<a id="a739d53294bc38cd6b0b23332f9994c0ea41ea4b5f98221f62807712205a8d37f7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIV_FIXUP<a id="a739d53294bc38cd6b0b23332f9994c0ea5b23f9813222573c51bc3a8a616494a0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMAD_FTZ<a id="a739d53294bc38cd6b0b23332f9994c0ea509df107f0a734f8d545ad3f7af30831"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RCP<a id="a739d53294bc38cd6b0b23332f9994c0ea480770519d97b188b42a1a0aa660a3db"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RSQ<a id="a739d53294bc38cd6b0b23332f9994c0ea6bf36266eccc139178a6078daefaf934"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RCP_LEGACY<a id="a739d53294bc38cd6b0b23332f9994c0eaf0f4e4ad0fa467f574bf5f983a81d202"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RCP_IFLAG<a id="a739d53294bc38cd6b0b23332f9994c0ea51178790d7c73b373338c52de42b4e96"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LOG<a id="a739d53294bc38cd6b0b23332f9994c0ea142323a51f7893d2ea77cc7f55580b0a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EXP<a id="a739d53294bc38cd6b0b23332f9994c0ea811ea7900036498b8e776687544ef03a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMUL_LEGACY<a id="a739d53294bc38cd6b0b23332f9994c0ea2aea035f778d5c12c6350fa76de35941"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RSQ_CLAMP<a id="a739d53294bc38cd6b0b23332f9994c0ea41c8322a0c1353beca047ee2d6c0742d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FP_CLASS<a id="a739d53294bc38cd6b0b23332f9994c0ea91ac5439df5245511c113f8833356321"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DOT4<a id="a739d53294bc38cd6b0b23332f9994c0ea51d107fa5c507cf013b59ff5a25749ae"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CARRY<a id="a739d53294bc38cd6b0b23332f9994c0ea2e4d87084baa45989bef5935e3ed9e5d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BORROW<a id="a739d53294bc38cd6b0b23332f9994c0eae2ed13c5c040dbec79e93f11c09c4d57"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BFE_U32<a id="a739d53294bc38cd6b0b23332f9994c0eacb028e9739d033de026de0a3b2ac9f9e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BFE_I32<a id="a739d53294bc38cd6b0b23332f9994c0ea9d8dde2474ce68109f2472f204072c80"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BFI<a id="a739d53294bc38cd6b0b23332f9994c0eafbca76f7875e080d97cee761de04d996"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BFM<a id="a739d53294bc38cd6b0b23332f9994c0eaa257ce6c70a5ceadfc079dfcd101db51"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FFBH_U32<a id="a739d53294bc38cd6b0b23332f9994c0ea47a3e4d50c2a91fd380b7ecb92260117"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FFBH_I32<a id="a739d53294bc38cd6b0b23332f9994c0ea1ccdf175d98c6185d058929850b208c6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FFBL_B32<a id="a739d53294bc38cd6b0b23332f9994c0ea15b0c32f5da14cffc6456d659d784e06"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MUL_U24<a id="a739d53294bc38cd6b0b23332f9994c0eace5b3b15d1d5f95bee02434672f45f4f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MUL_I24<a id="a739d53294bc38cd6b0b23332f9994c0ea05cf29ebf61481e1e9b60c16421956cc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MULHI_U24<a id="a739d53294bc38cd6b0b23332f9994c0ea1ec402986ec4e0050c9cd092877ebb86"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MULHI_I24<a id="a739d53294bc38cd6b0b23332f9994c0eacf88f212c148563537f24c48e1fedd5a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MAD_U24<a id="a739d53294bc38cd6b0b23332f9994c0ea3104e83ec08c0571b350e451f19efb50"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MAD_I24<a id="a739d53294bc38cd6b0b23332f9994c0eadfc6f671e6046a1b1e1158b16920b168"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MAD_U64_U32<a id="a739d53294bc38cd6b0b23332f9994c0ea760ece3c08b02521b09f90ee5a5e4fdb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MAD_I64_I32<a id="a739d53294bc38cd6b0b23332f9994c0eae110f734779ea7435c1f89a1b019e8e9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PERM<a id="a739d53294bc38cd6b0b23332f9994c0ea5af8d311a572d1aba24e25c20d1d7923"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TEXTURE_FETCH<a id="a739d53294bc38cd6b0b23332f9994c0ea125765d08e486bffa41af032e3a062ce"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R600_EXPORT<a id="a739d53294bc38cd6b0b23332f9994c0eaea1bac367b725a5cd386b26f1e620535"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONST_ADDRESS<a id="a739d53294bc38cd6b0b23332f9994c0ea20107c0b2289fd8e2cebba28080bd69c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">REGISTER_LOAD<a id="a739d53294bc38cd6b0b23332f9994c0ea2e28f6b19f1c6e68e785e50f8feb9114"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">REGISTER_STORE<a id="a739d53294bc38cd6b0b23332f9994c0ea02ebe2c9b7c32f3b603a174ff8f74df8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVT_F32_UBYTE0<a id="a739d53294bc38cd6b0b23332f9994c0eadfc7703ef955db9b67f92a2d9450f29f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVT_F32_UBYTE1<a id="a739d53294bc38cd6b0b23332f9994c0ea884cb7fa9f25c9231c3b0a7a25e96bb9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVT_F32_UBYTE2<a id="a739d53294bc38cd6b0b23332f9994c0eaba0b6153fdfc6ac440d378e6d1e9d3ca"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVT_F32_UBYTE3<a id="a739d53294bc38cd6b0b23332f9994c0eade9e553a6f004b4bd01abcb57712208a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVT_PKRTZ_F16_F32<a id="a739d53294bc38cd6b0b23332f9994c0ea05e199d247b019380b4c5a6f24d95381"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVT_PKNORM_I16_F32<a id="a739d53294bc38cd6b0b23332f9994c0ea39c851d59f2dedcf582022a24daf1cf5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVT_PKNORM_U16_F32<a id="a739d53294bc38cd6b0b23332f9994c0eaf372b02c7f2eb214586b79418da259d3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVT_PK_I16_I32<a id="a739d53294bc38cd6b0b23332f9994c0ea9326abce64225b1fcaf656b06d5819ad"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CVT_PK_U16_U32<a id="a739d53294bc38cd6b0b23332f9994c0ea61c1f4bb39a8d5172f7a4f2b50d8b290"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FP_TO_FP16<a id="a739d53294bc38cd6b0b23332f9994c0eaa784d8576110776c7284f1dea2a938b1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUILD_VERTICAL_VECTOR<a id="a739d53294bc38cd6b0b23332f9994c0ea197d5d152271b9cbd5105723bd534c0e"></a></td>
<td class="doxyEnumItemDescription">This node is for VLIW targets and it is used to represent a vector that is stored in consecutive registers with the same channel</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONST_DATA_PTR<a id="a739d53294bc38cd6b0b23332f9994c0ea80f5fc1f3bed4cfad825b92969f636f6"></a></td>
<td class="doxyEnumItemDescription">Pointer to the start of the shader's constant data</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PC_ADD_REL_OFFSET<a id="a739d53294bc38cd6b0b23332f9994c0ea7d48c98e21f25f9fc5fdd89d7b2666ba"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LDS<a id="a739d53294bc38cd6b0b23332f9994c0ea273be28bf4b8170125b34f1567c7be16"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DUMMY_CHAIN<a id="a739d53294bc38cd6b0b23332f9994c0eac87492f7d9abbb3d8929def4abf83e6d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIRST_MEMORY_OPCODE<a id="a739d53294bc38cd6b0b23332f9994c0eac8403be1afcc2fd8e573d2188bc1ce3c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LOAD_D16_HI<a id="a739d53294bc38cd6b0b23332f9994c0eaaf3ef4daab9db871926a727d7cca444a"></a></td>
<td class="doxyEnumItemDescription"> (= FIRST_MEMORY_OPCODE)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LOAD_D16_LO<a id="a739d53294bc38cd6b0b23332f9994c0ea9d9d3af4d64c8851bed302606264cf64"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LOAD_D16_HI_I8<a id="a739d53294bc38cd6b0b23332f9994c0ea8a604d758e44ad80fc6c79fdcfde3424"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LOAD_D16_HI_U8<a id="a739d53294bc38cd6b0b23332f9994c0ea76dae89c9d37a7d4a007589e236d7579"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LOAD_D16_LO_I8<a id="a739d53294bc38cd6b0b23332f9994c0ea62d5df7316428469ea4d31d893d2bffe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LOAD_D16_LO_U8<a id="a739d53294bc38cd6b0b23332f9994c0eac344911a086691a209bc2cfa6a7d29ee"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STORE_MSKOR<a id="a739d53294bc38cd6b0b23332f9994c0eaa40bae61060fd33b205ccbe936f4e772"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TBUFFER_STORE_FORMAT<a id="a739d53294bc38cd6b0b23332f9994c0ea7afea8c7ed507e3d6034758e07591a37"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TBUFFER_STORE_FORMAT_D16<a id="a739d53294bc38cd6b0b23332f9994c0ea3b82847282be27a34224531d39c58ec2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TBUFFER_LOAD_FORMAT<a id="a739d53294bc38cd6b0b23332f9994c0eae974d9c3847accca9ff270a7efd8938d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TBUFFER_LOAD_FORMAT_D16<a id="a739d53294bc38cd6b0b23332f9994c0ea13b59d6355b86eea11f514c7c89e0f5f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DS_ORDERED_COUNT<a id="a739d53294bc38cd6b0b23332f9994c0eabf84d249106fbef805c08aae16f19968"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_CMP_SWAP<a id="a739d53294bc38cd6b0b23332f9994c0eab9af213d8b7040b495c9e909a65099e6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_LOAD<a id="a739d53294bc38cd6b0b23332f9994c0ea3804b23b929a6df413cedc6e5dac099e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_LOAD_UBYTE<a id="a739d53294bc38cd6b0b23332f9994c0ea55ee7bc063408b722f1f13fa3e82944d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_LOAD_USHORT<a id="a739d53294bc38cd6b0b23332f9994c0eadffe91c8dd7ef6f1218a91e3af8b3838"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_LOAD_BYTE<a id="a739d53294bc38cd6b0b23332f9994c0eaf886dbc3fed73308c35df90948fd14e1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_LOAD_SHORT<a id="a739d53294bc38cd6b0b23332f9994c0ea5973ca171c5051b92e2555a7a94029ac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_LOAD_TFE<a id="a739d53294bc38cd6b0b23332f9994c0eac1ac4d562ca43d214843ab56b12ed01d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_LOAD_UBYTE_TFE<a id="a739d53294bc38cd6b0b23332f9994c0ea449d1de15381f80aae2b11204cbbb1f1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_LOAD_USHORT_TFE<a id="a739d53294bc38cd6b0b23332f9994c0eaeb42dc396142b9ea21e426960efbfb7e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_LOAD_BYTE_TFE<a id="a739d53294bc38cd6b0b23332f9994c0eabc67563096310a4105515add8178bdbf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_LOAD_SHORT_TFE<a id="a739d53294bc38cd6b0b23332f9994c0ea69f221d7c50efd76248f6d22581a06a9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_LOAD_FORMAT<a id="a739d53294bc38cd6b0b23332f9994c0ea397fbad92288743379962b2f204a21e8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_LOAD_FORMAT_TFE<a id="a739d53294bc38cd6b0b23332f9994c0ea9488cb4a648ea7900362a755d6323a6c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_LOAD_FORMAT_D16<a id="a739d53294bc38cd6b0b23332f9994c0ea267cae256d19873b48b90feeeca0b146"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SBUFFER_LOAD<a id="a739d53294bc38cd6b0b23332f9994c0eaca625a65c81f340ce675d97fa2f92c5d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SBUFFER_LOAD_BYTE<a id="a739d53294bc38cd6b0b23332f9994c0ea97efbb28a210a14fb9cce7c5011e4414"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SBUFFER_LOAD_UBYTE<a id="a739d53294bc38cd6b0b23332f9994c0ea33fc8ba82518b79697c7632b0615ebdd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SBUFFER_LOAD_SHORT<a id="a739d53294bc38cd6b0b23332f9994c0ead111f805510079df29cdaee7443d8fc4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SBUFFER_LOAD_USHORT<a id="a739d53294bc38cd6b0b23332f9994c0ea37e207c1d2f3cfa79cd9bc178c11ddc4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SBUFFER_PREFETCH_DATA<a id="a739d53294bc38cd6b0b23332f9994c0ea877ebce225da8e814f62c22ea3d3457f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_STORE<a id="a739d53294bc38cd6b0b23332f9994c0ea0195497770dcd5d8648a4e1b5e86f6bf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_STORE_BYTE<a id="a739d53294bc38cd6b0b23332f9994c0ea69791e003c63fd1d623a4a0a0fe6019c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_STORE_SHORT<a id="a739d53294bc38cd6b0b23332f9994c0ea66151a58e581052270c1f5f1e4351b12"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_STORE_FORMAT<a id="a739d53294bc38cd6b0b23332f9994c0ea80b445d8d2089b140ef7b9cda3e145b2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_STORE_FORMAT_D16<a id="a739d53294bc38cd6b0b23332f9994c0eaa7dcbcd6712c75ebca0b128c80aa1833"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_ATOMIC_SWAP<a id="a739d53294bc38cd6b0b23332f9994c0ea9fb788aeadfb9e90d318a51288a9cc85"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_ATOMIC_ADD<a id="a739d53294bc38cd6b0b23332f9994c0eae4ba5a5da88430e3bf45a7b6ff095da8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_ATOMIC_SUB<a id="a739d53294bc38cd6b0b23332f9994c0ea63ac508ae6d2c882d467bb6bff691b6d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_ATOMIC_SMIN<a id="a739d53294bc38cd6b0b23332f9994c0eae9def8ccf97465c0a54665fb00c169d3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_ATOMIC_UMIN<a id="a739d53294bc38cd6b0b23332f9994c0ea50d648baad4b2414da6e203fe0e5f552"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_ATOMIC_SMAX<a id="a739d53294bc38cd6b0b23332f9994c0ea3f02f120ade645c2bf98928f3f6aca9c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_ATOMIC_UMAX<a id="a739d53294bc38cd6b0b23332f9994c0eac19d50cfe33aa037a604c5451f1e83e1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_ATOMIC_AND<a id="a739d53294bc38cd6b0b23332f9994c0eab4ff3c00844c2479d1c13ec401821abe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_ATOMIC_OR<a id="a739d53294bc38cd6b0b23332f9994c0ea55eacee704bb2135f121813f23d2ba69"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_ATOMIC_XOR<a id="a739d53294bc38cd6b0b23332f9994c0ea9b787e6ece8b1012cb25ec1a17181ab1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_ATOMIC_INC<a id="a739d53294bc38cd6b0b23332f9994c0eac85de0a339386668e1ffda411b04262a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_ATOMIC_DEC<a id="a739d53294bc38cd6b0b23332f9994c0eaafcb7b0a5198f48ef6e725d16391c441"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_ATOMIC_CMPSWAP<a id="a739d53294bc38cd6b0b23332f9994c0ea68e59381ccf440cab3528edb5a3428e8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_ATOMIC_CSUB<a id="a739d53294bc38cd6b0b23332f9994c0eabcf922c2dec28d67086ce8dfb65c3d41"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_ATOMIC_FADD<a id="a739d53294bc38cd6b0b23332f9994c0eaa661bb901c8c2f1d44e558f2c997241d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_ATOMIC_FMIN<a id="a739d53294bc38cd6b0b23332f9994c0ea5716f43a1b7e8c29814ccb92ee2dd2e8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_ATOMIC_FMAX<a id="a739d53294bc38cd6b0b23332f9994c0ea7361757891331bf4d8bfeddfc100691d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_ATOMIC_COND_SUB_U32<a id="a739d53294bc38cd6b0b23332f9994c0ea0dea54491f8105561fad64ec68004af5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LAST_MEMORY_OPCODE<a id="a739d53294bc38cd6b0b23332f9994c0ea95357fd8fa9c9bc68195ab09c56092ba"></a></td>
<td class="doxyEnumItemDescription"> (= BUFFER_ATOMIC_COND_SUB_U32)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuisellowering-h">AMDGPUISelLowering.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuisellowering-h">AMDGPUISelLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
