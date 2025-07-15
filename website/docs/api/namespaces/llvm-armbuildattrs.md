---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/armbuildattrs
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `ARMBuildAttrs` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::ARMBuildAttrs { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">SpecialAttr { <a href="#a23944060f5e2b649dd87c603205b8dab">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AttrType : unsigned { <a href="#aea10ca6bf098a425d51ac7fe65d30ed6">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CPUArch { <a href="#a6f3569befc20dac7d092acbfc2ecbf04">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CPUArchProfile { <a href="#a5af12287edb52a422e35d2d962d8675e">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a1df37811cd3e1ed487bf9db640daa10d">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a8ba0ebd86185aea94f29ed853c4dd97f">TagNameMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bc717a2163815ca03dcec7cbf4bb7f5">getARMAttributeTags</a> ()</td>
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

### anonymous enum  {#a1df37811cd3e1ed487bf9db640daa10d}

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
<td class="doxyEnumItemName">Not_Allowed<a id="a1df37811cd3e1ed487bf9db640daa10da64723843712f68698dfe9f085d6bd630"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Allowed<a id="a1df37811cd3e1ed487bf9db640daa10daa5cedd7d339a70606b857fc2c498e0fb"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowThumb32<a id="a1df37811cd3e1ed487bf9db640daa10daa0ebd5a6f13bc2b521c53c4c79ecc5ce"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowThumbDerived<a id="a1df37811cd3e1ed487bf9db640daa10da061b8e858a32e88e3ae5ae77d491d64c"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowFPv2<a id="a1df37811cd3e1ed487bf9db640daa10daa4f0a312566760c6e4a8c0245bf85c03"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowFPv3A<a id="a1df37811cd3e1ed487bf9db640daa10dac8a4e98917f7e58a0b6e35512131c037"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowFPv3B<a id="a1df37811cd3e1ed487bf9db640daa10da3f4e89e770367315beca0509389503e9"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowFPv4A<a id="a1df37811cd3e1ed487bf9db640daa10daeccbc32267beb88260d6ef96a4610aab"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowFPv4B<a id="a1df37811cd3e1ed487bf9db640daa10da15e660c4128b82c5af5df82636ecaba5"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowFPARMv8A<a id="a1df37811cd3e1ed487bf9db640daa10da6739e0b4aee9b1d88200237688de5ae8"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowFPARMv8B<a id="a1df37811cd3e1ed487bf9db640daa10da244cf36fb11765c05391d633f4a639f0"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowWMMXv1<a id="a1df37811cd3e1ed487bf9db640daa10da33a68ce366fb2fa46c9bc72776618acf"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowWMMXv2<a id="a1df37811cd3e1ed487bf9db640daa10da9d84551d864c03d71772e35f184a4574"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowNeon<a id="a1df37811cd3e1ed487bf9db640daa10dad0a867e92c26a3ad38f2a1527d945555"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowNeon2<a id="a1df37811cd3e1ed487bf9db640daa10da5b0384586bd087e8869d0eef561b6b5c"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowNeonARMv8<a id="a1df37811cd3e1ed487bf9db640daa10da043049fbf433d3cb7d96ae4f4d51d23b"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowNeonARMv8_1a<a id="a1df37811cd3e1ed487bf9db640daa10da4ca3c026c11f6705d2dffb25b814909c"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowMVEInteger<a id="a1df37811cd3e1ed487bf9db640daa10da96679293f4823264d6d5c5da8adfda30"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowMVEIntegerAndFloat<a id="a1df37811cd3e1ed487bf9db640daa10da1f9a10e7d17b4b0ba4b1f61ad757adb1"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R9IsGPR<a id="a1df37811cd3e1ed487bf9db640daa10daa46a5f145c71d59c3e6a4df30cd54650"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R9IsSB<a id="a1df37811cd3e1ed487bf9db640daa10dada5b18bfc17dd7effca8b1f8075ecc2a"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R9IsTLSPointer<a id="a1df37811cd3e1ed487bf9db640daa10da37f91aa11e4f79dfe208b8fcac844e0c"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R9Reserved<a id="a1df37811cd3e1ed487bf9db640daa10dae09dc76e9d04de0a905d0ff801d44015"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddressRWPCRel<a id="a1df37811cd3e1ed487bf9db640daa10da15b78b8973b6b3dc0a0122fa2686c501"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddressRWSBRel<a id="a1df37811cd3e1ed487bf9db640daa10da6254943794d6e0089635c73ef1be87e7"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddressRWNone<a id="a1df37811cd3e1ed487bf9db640daa10daaa6ad49912b7368a484da2dadd9cdc6b"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddressROPCRel<a id="a1df37811cd3e1ed487bf9db640daa10dac2f83817680becd093125dfefe146273"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddressRONone<a id="a1df37811cd3e1ed487bf9db640daa10da0a1057da42d8551f915a9bf27511edd5"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddressDirect<a id="a1df37811cd3e1ed487bf9db640daa10da6a613cacf2a079761cbc8593bf2b8ad1"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddressGOT<a id="a1df37811cd3e1ed487bf9db640daa10da3c37b38c3e47f07ad6d5fc982c873a20"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WCharProhibited<a id="a1df37811cd3e1ed487bf9db640daa10da5fa519be1c966de0d4b88debf1b47a61"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WCharWidth2Bytes<a id="a1df37811cd3e1ed487bf9db640daa10da0fbc629c8d83984bd56a3f3f968d7408"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WCharWidth4Bytes<a id="a1df37811cd3e1ed487bf9db640daa10daa5d3ebd2e38cae0fd82bf97f1e63b259"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Align8Byte<a id="a1df37811cd3e1ed487bf9db640daa10da62f8e7091318f0d9e53ca97fbfd75346"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Align4Byte<a id="a1df37811cd3e1ed487bf9db640daa10daa9ee40fa74a63c55cd97298153813d91"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AlignReserved<a id="a1df37811cd3e1ed487bf9db640daa10da2b25d75318bab250050a0d2f8281af6a"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AlignNotPreserved<a id="a1df37811cd3e1ed487bf9db640daa10daa6d23a33958d04c8b234d4c0309e4a2e"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AlignPreserve8Byte<a id="a1df37811cd3e1ed487bf9db640daa10da1c8aa13e6ac05efdbb4d750e53d8406d"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AlignPreserveAll<a id="a1df37811cd3e1ed487bf9db640daa10daa9a21e421635fea1b634415f1f30a0c2"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PositiveZero<a id="a1df37811cd3e1ed487bf9db640daa10da0566dea58d3363c65a4873245850f461"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IEEEDenormals<a id="a1df37811cd3e1ed487bf9db640daa10daf0baf6860826b871046d07abf42ffefc"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PreserveFPSign<a id="a1df37811cd3e1ed487bf9db640daa10da2d91784a84cfe7a52c8d01729e3f4819"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowIEEENormal<a id="a1df37811cd3e1ed487bf9db640daa10da826e57af4017ec6ee6496d9476ee77d7"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowRTABI<a id="a1df37811cd3e1ed487bf9db640daa10dab26bd696b8ffacfe048189d7ed757ccc"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowIEEE754<a id="a1df37811cd3e1ed487bf9db640daa10da79b8b7d6d1013b7422a2016f5afa6de5"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EnumProhibited<a id="a1df37811cd3e1ed487bf9db640daa10dad9905d986a8c4f3c1b8a5768bbbd1101"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EnumSmallest<a id="a1df37811cd3e1ed487bf9db640daa10da6c58467bb765f2a3c2d9967f5a8810da"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Enum32Bit<a id="a1df37811cd3e1ed487bf9db640daa10dadcf24a1466b655e07049e40420694106"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Enum32BitABI<a id="a1df37811cd3e1ed487bf9db640daa10da27c34423859b142904f7ce52187ecf06"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HardFPImplied<a id="a1df37811cd3e1ed487bf9db640daa10da7015939a9f8c9528131785205e9cc643"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HardFPSinglePrecision<a id="a1df37811cd3e1ed487bf9db640daa10dad73ca706d2ba8083b257c8aa589ebf2b"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BaseAAPCS<a id="a1df37811cd3e1ed487bf9db640daa10da070c47bf70d438b57a5373b6788a0a37"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HardFPAAPCS<a id="a1df37811cd3e1ed487bf9db640daa10da666eb3826fd1712fae6378f0437122fc"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ToolChainFPPCS<a id="a1df37811cd3e1ed487bf9db640daa10daf405652a56e6b5427c0537273c26317e"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CompatibleFPAAPCS<a id="a1df37811cd3e1ed487bf9db640daa10daa1585ab338eefe6d378f2d2d6d207639"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowHPFP<a id="a1df37811cd3e1ed487bf9db640daa10daeeb461f37b62346d689cdae6447b87f9"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FP16FormatIEEE<a id="a1df37811cd3e1ed487bf9db640daa10da9954ef5ab390e67e4512823d5c9aabbd"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FP16VFP3<a id="a1df37811cd3e1ed487bf9db640daa10da0bb0c5996e4a5f17aac2de8aff24340c"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowMP<a id="a1df37811cd3e1ed487bf9db640daa10da94b7e68702888dee4af6bbb4b9abce3b"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowDIVIfExists<a id="a1df37811cd3e1ed487bf9db640daa10da057c2c2752644287294500c1a3fc432a"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DisallowDIV<a id="a1df37811cd3e1ed487bf9db640daa10dadb3ddb41e5d65fcfae7691ea7fbe49a7"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowDIVExt<a id="a1df37811cd3e1ed487bf9db640daa10da7aa7c494b5c5945a0528dd569525b5f9"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowTZ<a id="a1df37811cd3e1ed487bf9db640daa10da222232593de0262f234323874d198d21"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowVirtualization<a id="a1df37811cd3e1ed487bf9db640daa10da8edb37eae51094e2edd43e941de79a85"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowTZVirtualization<a id="a1df37811cd3e1ed487bf9db640daa10da1043823aeb4de304dbc3eb4e4bae13c4"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DisallowPAC<a id="a1df37811cd3e1ed487bf9db640daa10da8db8ed83d6b9d37d2519041ec760ca07"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowPACInNOPSpace<a id="a1df37811cd3e1ed487bf9db640daa10da9170062f3ff57e2b4b38c19ed1c0dbc6"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowPAC<a id="a1df37811cd3e1ed487bf9db640daa10daf4a50dec80a0d2ac905327c48a289c4a"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DisallowBTI<a id="a1df37811cd3e1ed487bf9db640daa10dac3c5706dd29d7e406cd3f611e0d5f5e5"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowBTIInNOPSpace<a id="a1df37811cd3e1ed487bf9db640daa10da5a093e99b1092207eba6e14599b03221"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowBTI<a id="a1df37811cd3e1ed487bf9db640daa10dabb5d7c315c1217100b7c29cf19d64ca7"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BTINotUsed<a id="a1df37811cd3e1ed487bf9db640daa10daf4e0295bc17a8db91bdd47356177857d"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BTIUsed<a id="a1df37811cd3e1ed487bf9db640daa10dace4d3f10b38c8a12875303947a259e1a"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PACRETNotUsed<a id="a1df37811cd3e1ed487bf9db640daa10da98658da7f99258529425882edeec52c8"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PACRETUsed<a id="a1df37811cd3e1ed487bf9db640daa10da9bb283676fc95afe4da4f2fd0288c5a8"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armbuildattributes-h">ARMBuildAttributes.h</a>.</p>

</div>
</div>

### AttrType {#aea10ca6bf098a425d51ac7fe65d30ed6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ARMBuildAttrs::AttrType : unsigned</td>
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
<td class="doxyEnumItemName">File<a id="aea10ca6bf098a425d51ac7fe65d30ed6aecf09ba70b320e04fec09afb59d502cd"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CPU_raw_name<a id="aea10ca6bf098a425d51ac7fe65d30ed6a0362da29c55d6c2206ecda52ee258ccc"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CPU_name<a id="aea10ca6bf098a425d51ac7fe65d30ed6ae72f5987483e0286f0225c32b27e4441"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CPU_arch<a id="aea10ca6bf098a425d51ac7fe65d30ed6a0279c11a681fcdb5d127fe510b794dae"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CPU_arch_profile<a id="aea10ca6bf098a425d51ac7fe65d30ed6adc480a9854461c31275e13b17a431956"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARM_ISA_use<a id="aea10ca6bf098a425d51ac7fe65d30ed6a32c829f47c3280a9c081198fc927f3c2"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">THUMB_ISA_use<a id="aea10ca6bf098a425d51ac7fe65d30ed6add6bd85d9bcdd64df76ff3ce8ff59282"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FP_arch<a id="aea10ca6bf098a425d51ac7fe65d30ed6acdcbb4288e972e89754d75ae3055c5ad"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WMMX_arch<a id="aea10ca6bf098a425d51ac7fe65d30ed6ab93860980699a6172e0a0732ed64ed9b"></a></td>
<td class="doxyEnumItemDescription"> (= 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Advanced_SIMD_arch<a id="aea10ca6bf098a425d51ac7fe65d30ed6a80cebeb60c235348741536710cd9d899"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PCS_config<a id="aea10ca6bf098a425d51ac7fe65d30ed6a198a89e97d01d780410a4006b0b62c6c"></a></td>
<td class="doxyEnumItemDescription"> (= 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_PCS_R9_use<a id="aea10ca6bf098a425d51ac7fe65d30ed6a0964c14e79a9c2fa99f194c69cc5f336"></a></td>
<td class="doxyEnumItemDescription"> (= 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_PCS_RW_data<a id="aea10ca6bf098a425d51ac7fe65d30ed6accb41d9beb53ac339b0531d97ffdaebc"></a></td>
<td class="doxyEnumItemDescription"> (= 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_PCS_RO_data<a id="aea10ca6bf098a425d51ac7fe65d30ed6a7f6d5031ccd8a14323deed1c0d28609d"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_PCS_GOT_use<a id="aea10ca6bf098a425d51ac7fe65d30ed6ae85cee6326e89db14ad33163ec46cbaa"></a></td>
<td class="doxyEnumItemDescription"> (= 17)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_PCS_wchar_t<a id="aea10ca6bf098a425d51ac7fe65d30ed6ada666cc0d3391912e7a0ff83e679454f"></a></td>
<td class="doxyEnumItemDescription"> (= 18)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_FP_rounding<a id="aea10ca6bf098a425d51ac7fe65d30ed6a8ed6bd6b18bf9d6d628c8e1912ef2f31"></a></td>
<td class="doxyEnumItemDescription"> (= 19)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_FP_denormal<a id="aea10ca6bf098a425d51ac7fe65d30ed6ae1386dbaa759a88292fcc2b68c0d14f4"></a></td>
<td class="doxyEnumItemDescription"> (= 20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_FP_exceptions<a id="aea10ca6bf098a425d51ac7fe65d30ed6a1acf9241c03a844b51e1492c2c2228f0"></a></td>
<td class="doxyEnumItemDescription"> (= 21)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_FP_user_exceptions<a id="aea10ca6bf098a425d51ac7fe65d30ed6a7713bcbae1d309d04be30e80c09af5eb"></a></td>
<td class="doxyEnumItemDescription"> (= 22)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_FP_number_model<a id="aea10ca6bf098a425d51ac7fe65d30ed6aa07c7312c024adf64133e98b59a94db5"></a></td>
<td class="doxyEnumItemDescription"> (= 23)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_align_needed<a id="aea10ca6bf098a425d51ac7fe65d30ed6a458d4988672152c24861c424f2df6942"></a></td>
<td class="doxyEnumItemDescription"> (= 24)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_align_preserved<a id="aea10ca6bf098a425d51ac7fe65d30ed6ad2911b24d0ff493a03bd863a12280946"></a></td>
<td class="doxyEnumItemDescription"> (= 25)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_enum_size<a id="aea10ca6bf098a425d51ac7fe65d30ed6aa9cf068cbe5f0fe5c826c159f9581258"></a></td>
<td class="doxyEnumItemDescription"> (= 26)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_HardFP_use<a id="aea10ca6bf098a425d51ac7fe65d30ed6ac1e2a90ed1ea61e5a9c94403450ffcf0"></a></td>
<td class="doxyEnumItemDescription"> (= 27)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_VFP_args<a id="aea10ca6bf098a425d51ac7fe65d30ed6a9f20129d5b198bbb84eb3debe3a32655"></a></td>
<td class="doxyEnumItemDescription"> (= 28)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_WMMX_args<a id="aea10ca6bf098a425d51ac7fe65d30ed6a649e2334678c104a4fb52d7935de66e6"></a></td>
<td class="doxyEnumItemDescription"> (= 29)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_optimization_goals<a id="aea10ca6bf098a425d51ac7fe65d30ed6a71616e041eed64dc71a644b40ea17a4f"></a></td>
<td class="doxyEnumItemDescription"> (= 30)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_FP_optimization_goals<a id="aea10ca6bf098a425d51ac7fe65d30ed6aa4f690895ab6614ca448254bf99dbe38"></a></td>
<td class="doxyEnumItemDescription"> (= 31)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">compatibility<a id="aea10ca6bf098a425d51ac7fe65d30ed6aee5378bf980643c8d8411fac97ff7cb0"></a></td>
<td class="doxyEnumItemDescription"> (= 32)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CPU_unaligned_access<a id="aea10ca6bf098a425d51ac7fe65d30ed6a2c3301699af6d702cd84e3e67bd8fd38"></a></td>
<td class="doxyEnumItemDescription"> (= 34)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FP_HP_extension<a id="aea10ca6bf098a425d51ac7fe65d30ed6a46d720d15e2beb148b6dc0cbaaf323a8"></a></td>
<td class="doxyEnumItemDescription"> (= 36)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_FP_16bit_format<a id="aea10ca6bf098a425d51ac7fe65d30ed6a0b4b958032823ee1b0b8957808ffb823"></a></td>
<td class="doxyEnumItemDescription"> (= 38)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MPextension_use<a id="aea10ca6bf098a425d51ac7fe65d30ed6aa83f5b2511c84a5080ea185a6f315f05"></a></td>
<td class="doxyEnumItemDescription"> (= 42)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIV_use<a id="aea10ca6bf098a425d51ac7fe65d30ed6a9d2b627f8f8a450a467befb8eee43f8d"></a></td>
<td class="doxyEnumItemDescription"> (= 44)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DSP_extension<a id="aea10ca6bf098a425d51ac7fe65d30ed6ac41e338bd0ebad18ef47c0ef3dd35ddc"></a></td>
<td class="doxyEnumItemDescription"> (= 46)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MVE_arch<a id="aea10ca6bf098a425d51ac7fe65d30ed6a7b8e76f3d836b46eb71f9d78074a8513"></a></td>
<td class="doxyEnumItemDescription"> (= 48)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PAC_extension<a id="aea10ca6bf098a425d51ac7fe65d30ed6ae4ba9f321f9347ac72e200b6c0537ace"></a></td>
<td class="doxyEnumItemDescription"> (= 50)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BTI_extension<a id="aea10ca6bf098a425d51ac7fe65d30ed6a95179de49813a1def4a7bf42db5ef7b1"></a></td>
<td class="doxyEnumItemDescription"> (= 52)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">also_compatible_with<a id="aea10ca6bf098a425d51ac7fe65d30ed6ae7d2fb9ecbaf6f8877339bb00a8aaf97"></a></td>
<td class="doxyEnumItemDescription"> (= 65)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">conformance<a id="aea10ca6bf098a425d51ac7fe65d30ed6afa4f1dc423189339764d245b71668e39"></a></td>
<td class="doxyEnumItemDescription"> (= 67)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Virtualization_use<a id="aea10ca6bf098a425d51ac7fe65d30ed6a3a1243e2ca97bc9f4e4e197693c145d3"></a></td>
<td class="doxyEnumItemDescription"> (= 68)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BTI_use<a id="aea10ca6bf098a425d51ac7fe65d30ed6a46b911d75decdcf20036378053038620"></a></td>
<td class="doxyEnumItemDescription"> (= 74)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PACRET_use<a id="aea10ca6bf098a425d51ac7fe65d30ed6ad0186675a4abca39f2ab7de5fae393a4"></a></td>
<td class="doxyEnumItemDescription"> (= 76)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Section<a id="aea10ca6bf098a425d51ac7fe65d30ed6a69c8a3bdf3f5753779a342f0cd97c090"></a></td>
<td class="doxyEnumItemDescription">Legacy Tags (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Symbol<a id="aea10ca6bf098a425d51ac7fe65d30ed6aa10cda45fcbf7c8c9804e4e4d2e1bcdf"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_align8_needed<a id="aea10ca6bf098a425d51ac7fe65d30ed6a80570452015607245ddcb31c071112fb"></a></td>
<td class="doxyEnumItemDescription"> (= 24)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_align8_preserved<a id="aea10ca6bf098a425d51ac7fe65d30ed6a5171023508299f780c7e122cce97bdc1"></a></td>
<td class="doxyEnumItemDescription"> (= 25)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">nodefaults<a id="aea10ca6bf098a425d51ac7fe65d30ed6af66e1a5d35795c9f4588899cb906d1b4"></a></td>
<td class="doxyEnumItemDescription"> (= 64)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">T2EE_use<a id="aea10ca6bf098a425d51ac7fe65d30ed6a0be4ed5986e31645aea4737dcede7836"></a></td>
<td class="doxyEnumItemDescription"> (= 66)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MPextension_use_old<a id="aea10ca6bf098a425d51ac7fe65d30ed6aa8d513c4095977a67d3749637a5fe5d7"></a></td>
<td class="doxyEnumItemDescription"> (= 70)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armbuildattributes-h">ARMBuildAttributes.h</a>.</p>

</div>
</div>

### CPUArch {#a6f3569befc20dac7d092acbfc2ecbf04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ARMBuildAttrs::CPUArch </td>
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
<td class="doxyEnumItemName">Pre_v4<a id="a6f3569befc20dac7d092acbfc2ecbf04a3f0af4335fc440809ae84871e0aa7982"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">v4<a id="a6f3569befc20dac7d092acbfc2ecbf04aba09d4835b95fc1a37b8883bbbbddbd1"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">v4T<a id="a6f3569befc20dac7d092acbfc2ecbf04a2519f8fd19963254840edfa09c21a565"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">v5T<a id="a6f3569befc20dac7d092acbfc2ecbf04acf263340a2ed14be933a5369f5094447"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">v5TE<a id="a6f3569befc20dac7d092acbfc2ecbf04a5593c6c42fb67cb1f5f62845693a28fa"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">v5TEJ<a id="a6f3569befc20dac7d092acbfc2ecbf04acd8b908686196c4123cdb4251b5661d0"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">v6<a id="a6f3569befc20dac7d092acbfc2ecbf04a08b94165165355a8b5da8663f656b783"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">v6KZ<a id="a6f3569befc20dac7d092acbfc2ecbf04aede0cbf23902a95d419659a1e9064773"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">v6T2<a id="a6f3569befc20dac7d092acbfc2ecbf04ace4bdfa827c96c98399ec299deb3e6d1"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">v6K<a id="a6f3569befc20dac7d092acbfc2ecbf04a6efde281d7e45b5e7af4d5b34c783f4b"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">v7<a id="a6f3569befc20dac7d092acbfc2ecbf04a3cf0cd428f021cea15953922332619e7"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">v6_M<a id="a6f3569befc20dac7d092acbfc2ecbf04ae80353adabcaaf1aa2faec0e0011a351"></a></td>
<td class="doxyEnumItemDescription"> (= 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">v6S_M<a id="a6f3569befc20dac7d092acbfc2ecbf04a4a4933da5591cff473164615859f9558"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">v7E_M<a id="a6f3569befc20dac7d092acbfc2ecbf04a49b5daf5353b4da268f64fef514a443f"></a></td>
<td class="doxyEnumItemDescription"> (= 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">v8_A<a id="a6f3569befc20dac7d092acbfc2ecbf04ae939f53cb580663a92ac0b5ea2a203f6"></a></td>
<td class="doxyEnumItemDescription"> (= 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">v8_R<a id="a6f3569befc20dac7d092acbfc2ecbf04a97beaa983d40bf4220e8c224f68e4578"></a></td>
<td class="doxyEnumItemDescription"> (= 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">v8_M_Base<a id="a6f3569befc20dac7d092acbfc2ecbf04a20ea6e94be6a97156977fe988078462a"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">v8_M_Main<a id="a6f3569befc20dac7d092acbfc2ecbf04a518a8feea596bb0014fd3d0bca83c844"></a></td>
<td class="doxyEnumItemDescription"> (= 17)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">v8_1_M_Main<a id="a6f3569befc20dac7d092acbfc2ecbf04a33780b53b2b0f05453df0d9fdaa4b04f"></a></td>
<td class="doxyEnumItemDescription"> (= 21)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">v9_A<a id="a6f3569befc20dac7d092acbfc2ecbf04a1188f7dc8364dbce20bfa37134594cdf"></a></td>
<td class="doxyEnumItemDescription"> (= 22)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armbuildattributes-h">ARMBuildAttributes.h</a>.</p>

</div>
</div>

### CPUArchProfile {#a5af12287edb52a422e35d2d962d8675e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ARMBuildAttrs::CPUArchProfile </td>
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
<td class="doxyEnumItemName">Not_Applicable<a id="a5af12287edb52a422e35d2d962d8675ea4fb13de8bee363230ca003122c63459c"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ApplicationProfile<a id="a5af12287edb52a422e35d2d962d8675ea4055efd7b4a72be9ddaaaaee12014983"></a></td>
<td class="doxyEnumItemDescription"> (= (0x41))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RealTimeProfile<a id="a5af12287edb52a422e35d2d962d8675eaf8af73196e31a66825ea7db1fd3e49e8"></a></td>
<td class="doxyEnumItemDescription"> (= (0x52))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MicroControllerProfile<a id="a5af12287edb52a422e35d2d962d8675eadd3aa668a94bc1798b0f619d2745e51a"></a></td>
<td class="doxyEnumItemDescription"> (= (0x4D))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SystemProfile<a id="a5af12287edb52a422e35d2d962d8675ea6bf5cd3ef7109fb57ff2db5a07823bf5"></a></td>
<td class="doxyEnumItemDescription"> (= (0x53))</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armbuildattributes-h">ARMBuildAttributes.h</a>.</p>

</div>
</div>

### SpecialAttr {#a23944060f5e2b649dd87c603205b8dab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ARMBuildAttrs::SpecialAttr </td>
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
<td class="doxyEnumItemName">SEL_CPU<a id="a23944060f5e2b649dd87c603205b8dabae97bec997e7affbd8d54de45d65115f7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armbuildattributes-h">ARMBuildAttributes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### getARMAttributeTags() {#a4bc717a2163815ca03dcec7cbf4bb7f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TagNameMap &amp; llvm::ARMBuildAttrs::getARMAttributeTags ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armbuildattributes-h">ARMBuildAttributes.h</a>, definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armbuildattributes-cpp">ARMBuildAttributes.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/armbuildattributes-cpp/#ae54007ba0f7961a33398883034289b50">ARMAttributeTags</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armbuildattributes-h">ARMBuildAttributes.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/armbuildattributes-cpp">ARMBuildAttributes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
