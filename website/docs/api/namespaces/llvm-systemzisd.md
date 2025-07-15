---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/systemzisd
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `SystemZISD` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::SystemZISD { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">NodeType : unsigned { <a href="#a24fe7decb4ebdd8b4c7a774d65fcaa7e">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b2598d0a47629b8b3d160c0f17c58d0">isPCREL</a> (unsigned Opcode)</td>
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

### NodeType {#a24fe7decb4ebdd8b4c7a774d65fcaa7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::SystemZISD::NodeType : unsigned</td>
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
<td class="doxyEnumItemName">FIRST_NUMBER<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eaf84d26f373783d9aa468bf3145eb5a20"></a></td>
<td class="doxyEnumItemDescription"> (= ISD::BUILTIN_OP_END)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RET_GLUE<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea47b4f2b94d532bbbd05cd8f19df6bf9d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALL<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ead1cbddae021bff7a8397506361b3aeb3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SIBCALL<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea5795d03079652d1e1c5d61a3dfb3d456"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TLS_GDCALL<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eab9aa68e97e9e4a044c783be302ec2f3d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TLS_LDCALL<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea14811e54cd42d7db17732f77cacd0223"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PCREL_WRAPPER<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea83726d5e1511048f397e726b7f61b109"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PCREL_OFFSET<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eaafe7d84d44aa03acb19fee9d9deb6e4d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICMP<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea492cf44e417890c9ec7a8138e26d23a7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCMP<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea953306a1f2d027e6b76aea6c045bd9cc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TM<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea68ace50a32835aa0562cf8f9694ba510"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BR_CCMASK<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eaa97a16094015d4b1074989bc92fca007"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SELECT_CCMASK<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eaad70b711d89890454ad6cbae8669f02f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADJDYNALLOC<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea7cc4d76410ab83f7f6b9d4953f0a23a5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PROBED_ALLOCA<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eaeccf0727bd03f9b84f17b6e43c8a91e7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">POPCNT<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea444c94d94b53b6c8177662aa9693ae08"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMUL_LOHI<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea00b0a8008be56552268b375927c4404b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UMUL_LOHI<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ead45b2c4c8cbc1b8391256bbcef4ffbd0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SDIVREM<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea21fc3e338a7edf9f8dfd0b3a1a0bbad4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UDIVREM<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eabf518fec3f797e5292f2bca8993b88ae"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SADDO<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea2e34629beda8908a34628d502cb6043f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SSUBO<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eafa1b07345e47c0b5d21cdf16cef007a9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UADDO<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea3a718a0464f33ec597a5622090d7c242"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">USUBO<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eaae49057ad8e68e50e3853f594a1d0f80"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADDCARRY<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eabdb92feb1779053c3dddfa1ad8d4c446"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SUBCARRY<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eab95580374548aeff114859881b693eea"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GET_CCMASK<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eac3df8a574c55bfeb555f09b30e3cf2e9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MVC<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ead36cb2203fdbacca879ada09db0b0a85"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NC<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea759e5ccb2f3482b90674d4289cf147b7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OC<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea6908fddc602ce5a12ea10c07af44a9ef"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XC<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea9cac76531875c59c8d879507bc72e282"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CLC<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea4bad211a26808864fb8f06f4e7d52035"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEMSET_MVC<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eae2c528e66350d03bf0fe7e2d40ab62cf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STPCPY<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eaafca0314124e4aa31b2d9c49a7f582d5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRCMP<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea911be528010d96a9935f856bd0bc4beb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SEARCH_STRING<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea3dc1a332d83e53ff1697d24420fe81dd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IPM<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea6d440313d2fc4fe1aefe580a1ebca98c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TBEGIN<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea06585117cad61e4558049d568736a665"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TBEGIN_NOFLOAT<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea170dfc3831e53f01cfef80f26ebd49d0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TEND<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea99876414c508c4d64d0b3ddb051f8e47"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BYTE_MASK<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea7bafe6b273a2e646673197555986f636"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROTATE_MASK<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea39e1c54eb43a73221817d060bf5f27a1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">REPLICATE<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea6ec607d4e1a29496a13bf2c88943e010"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">JOIN_DWORDS<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eaac77c7db1e1031a04b6f2ff55dca841d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SPLAT<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea78513267bb51e11895f2049870129857"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MERGE_HIGH<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea61c7d2c626a5e07acd6fea7f82bc10af"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MERGE_LOW<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea5205edbb39546c930b65481b7b4988ac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SHL_DOUBLE<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea1292e7941033038c6394c6dcbf6f842c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PERMUTE_DWORDS<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea34d70f9f8a0e747c1df775097bffa7ac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PERMUTE<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea36e0a594befa35302fd75225b5663a7a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PACK<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea2de796f751ab625e6fb313aca2375e98"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PACKS_CC<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea3c15f374e58d8fb156b02515fbe645ce"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PACKLS_CC<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea3cf71c91cd5b0d7b39330daac62d4d7f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNPACK_HIGH<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea8fe96abc026cb9c226576dc9963fa8de"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNPACKL_HIGH<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea74190ce96d6b42555298672988c10aec"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNPACK_LOW<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eadda8ba4eca9493367d60774ee0e29ac2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNPACKL_LOW<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea7faafd78c677ec1f7ef030d26e6055b2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSHL_BY_SCALAR<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea951445438fde4d895c27991417c70735"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSRL_BY_SCALAR<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eadd4cb11a38a48435a2d3922f2d15a415"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSRA_BY_SCALAR<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea49a446caf91acd22a0cbf2161997da65"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VROTL_BY_SCALAR<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eaf7c47e515d651e2639a6f8e87d38ebc1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSUM<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eaa787878750f9f5fa36127e06f906cf5e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VACC<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eafe913659f9dc8ebe21eced30e13ec524"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSCBI<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea791838d9dce72a5f67ed900924765e89"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VAC<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea9b93811bc755fd2e8ebacad7277af236"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSBI<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea5b1e2bfad8150ce845f6767c1b0f7eba"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VACCC<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eafd556b244066f2a93a428f2bb268a5ad"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSBCBI<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea2988e80c0cf405fd1f2154c9b71d6427"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VICMPE<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ead48016bf0e16628681e66b8bbd343265"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VICMPH<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea3937a9b45893ab29ea31d756132ff245"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VICMPHL<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea8790139ef46ca2c93fc2c0420b752bef"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VICMPES<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea010dc6febab09af375d40d42767d4a7f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VICMPHS<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea8fe84aca6c13d00a37ead5eb6fc3c796"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VICMPHLS<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea88c9c5ca59563f88dba13e85cef233d3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFCMPE<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eae313e2b60e3b9c464b6edb5467db7361"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFCMPH<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea105e999bd9b5b103567fe22edb12bb85"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFCMPHE<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea3dc1b0d6ca98f21f2c1651b5614cf4dd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFCMPES<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea318caa6c938260ed18240d0c74d7a2e3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFCMPHS<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eae8663bd372acf7fead0355f13b765c7b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFCMPHES<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ead9cf1fe08375829da31b8d39ac4d8cf6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFTCI<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eae9931fa5e9e6d9a87ab97b2754862abe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VEXTEND<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea2d73c0273407d7abc13910355dd1ed9a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VROUND<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eaf66f7a827254d8907df7d5bed37dffbe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VTM<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ead4d16a07d2c584273ab7195e1f09a4f4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCMP128HI<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea96acce1fe4615de8ba877c8ff546c91e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UCMP128HI<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eadcf90199fad103e6b3325b4e15abdf4c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFAE_CC<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eaececc0bac40077a33393c0e45c15db88"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFAEZ_CC<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eaa6b5511940e0acaec80c87c36b5d7be4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFEE_CC<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea4283ef44dbe96aa5d273e30bd851630e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFEEZ_CC<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea533ed7ae4c0153e322b359267fe344bb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFENE_CC<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eae203e19afc9683f9ad529e99d507ffb9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFENEZ_CC<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea188006f9abb586e28ffea9acaff40333"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VISTR_CC<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eab321c52d82a5776fe6859eb333dfc155"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSTRC_CC<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eaefd3c88f8c78fe6332e62b21f88ef5c4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSTRCZ_CC<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea3c997d8e91445f1a8d3c2875f56fcfb4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSTRS_CC<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea4ba65a4285f149925b0f1f0bf204f076"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSTRSZ_CC<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eadc641be288d6e771f679da42f34a355a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TDC<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea3aae0d17b59ddc5732db8fbebc8e9bca"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADA_ENTRY<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eadf7d8e59ae67b53c55695e082d943b0a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIRST_STRICTFP_OPCODE<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea7f1cb1c62d0c00979a0a710510b1ff1a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FCMP<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea8fa8793b5c9f78d8afd33599526c89e0"></a></td>
<td class="doxyEnumItemDescription"> (= FIRST_STRICTFP_OPCODE)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FCMPS<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea953db4bd4e3f8f6b0339f0cb6bad7b4e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_VFCMPE<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea049e8d73537f0c6923934098cd21fe37"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_VFCMPH<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea5d51fffbbd28177f573222e3f272b08a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_VFCMPHE<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea57204372483168853e5ff6fc15c00e9c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_VFCMPES<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eaed638be1b8ac3a076c94e8a6c2788a30"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_VFCMPHS<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea36242aeee059dc72c5fd8c7f257ff87e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_VFCMPHES<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea082859556cebd4b23c14792ffafcddbc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_VEXTEND<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea5792d88de7f3f5db191a38bf8903e7ec"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_VROUND<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea922ad40f7bf9cf341b42e2b3ce6d4699"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LAST_STRICTFP_OPCODE<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ead16915efb4b00c9c30e3077ede3ec40f"></a></td>
<td class="doxyEnumItemDescription"> (= STRICT_VROUND)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIRST_MEMORY_OPCODE<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea150e711c3247b64e333f71c3ae7447bb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_SWAPW<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea5c6a8c30d309b7d185c808946abb15a5"></a></td>
<td class="doxyEnumItemDescription"> (= FIRST_MEMORY_OPCODE)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_LOADW_ADD<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eab7f95ba529b4c10bbcf8bd1602a3f62f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_LOADW_SUB<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea72da9d1d453cd4597248d9f7438d5d3d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_LOADW_AND<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea4b47e34d6a6eea607bb9c1fad496fd72"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_LOADW_OR<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea11fe3ed339f75f26dd08fd79fedd8727"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_LOADW_XOR<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eaadb79ffeaf6c7a9ef0f6149105f5f12e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_LOADW_NAND<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea3be350fd3d03096b7c8139f5103560e0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_LOADW_MIN<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea74aaff84bdfedd96b073aab2bdd2c5bd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_LOADW_MAX<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea18503f8a305a329c3d53fd2f2ff4cc59"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_LOADW_UMIN<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea464ff8138693e57c4e247f771aa366dc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_LOADW_UMAX<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea1870a94186abd301017bcb7fa7ea2e93"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_CMP_SWAPW<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eac29643ffd97b5dbd495a345eaf4abd48"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_CMP_SWAP<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea5da965231accfa7468bc318b1d1e4a51"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_LOAD_128<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eab5005d5eef577f27c7037601011330cf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_STORE_128<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eaefb484dc8dcb49d69910c571b6662535"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_CMP_SWAP_128<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7eadf4b84eddd2fd4ea00a4857965af9ba0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LRV<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea77f44d4c42b3be43f834a4221609320c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRV<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea94e3f30850d84e2a0c63124fb612ebc5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VLER<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea872f993c4606d5e214f3ac75617aa5d2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSTER<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea5080800ee5ba7faf99345429b690f738"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STCKF<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea1a30b88a424b94ac8fb9fb99dbd62821"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PREFETCH<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea3ed31904708d1cea83e603c1b58e9617"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LAST_MEMORY_OPCODE<a id="a24fe7decb4ebdd8b4c7a774d65fcaa7ea1da234b421f77ebf1ef82eb64c9719d1"></a></td>
<td class="doxyEnumItemDescription"> (= PREFETCH)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-h">SystemZISelLowering.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### isPCREL() {#a1b2598d0a47629b8b3d160c0f17c58d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SystemZISD::isPCREL (unsigned Opcode)</td>
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



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-h">SystemZISelLowering.h</a>.</p>


<p>References <a href="#a24fe7decb4ebdd8b4c7a774d65fcaa7eaafe7d84d44aa03acb19fee9d9deb6e4d">PCREL_OFFSET</a> and <a href="#a24fe7decb4ebdd8b4c7a774d65fcaa7ea83726d5e1511048f397e726b7f61b109">PCREL_WRAPPER</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-h">SystemZISelLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
