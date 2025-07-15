---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/hexagonisd
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `HexagonISD` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::HexagonISD { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">NodeType : unsigned { <a href="#ab37bf6c49bc26c43ddd958218f63ba00">...</a> }</td>
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

### NodeType {#ab37bf6c49bc26c43ddd958218f63ba00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::HexagonISD::NodeType : unsigned</td>
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
<td class="doxyEnumItemName">OP_BEGIN<a id="ab37bf6c49bc26c43ddd958218f63ba00a42a4d8847f708b6084f1207747794e0a"></a></td>
<td class="doxyEnumItemDescription"> (= ISD::BUILTIN_OP_END)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONST32<a id="ab37bf6c49bc26c43ddd958218f63ba00abea5e5eaade21ea47b95e7e1536d6a73"></a></td>
<td class="doxyEnumItemDescription"> (= OP_BEGIN)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONST32_GP<a id="ab37bf6c49bc26c43ddd958218f63ba00ade8c9de814bdf20764d9930c5374a9c7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADDC<a id="ab37bf6c49bc26c43ddd958218f63ba00a58e2f927d956dd0f74358ceb6d5078d4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SUBC<a id="ab37bf6c49bc26c43ddd958218f63ba00a003738d2a76deeb84506b57b4d1f19e7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ALLOCA<a id="ab37bf6c49bc26c43ddd958218f63ba00ac65e616bc5472be645d8f5719202780e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AT_GOT<a id="ab37bf6c49bc26c43ddd958218f63ba00af4a5183d563766330a1ef01df49b690f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AT_PCREL<a id="ab37bf6c49bc26c43ddd958218f63ba00af72f773a8d564c91dcc37f7809237719"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALL<a id="ab37bf6c49bc26c43ddd958218f63ba00a109011f80617f2e9bf78738572b50cdf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALLnr<a id="ab37bf6c49bc26c43ddd958218f63ba00a81a74c97712a71cdbc3843eca60af1fd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALLR<a id="ab37bf6c49bc26c43ddd958218f63ba00a404e34d11c2b8e99702168e99d8cfd3e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RET_GLUE<a id="ab37bf6c49bc26c43ddd958218f63ba00a8918514b062987505ade0c92e82c918d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BARRIER<a id="ab37bf6c49bc26c43ddd958218f63ba00a99f208cc4f28eb5bb77b21daec292be9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">JT<a id="ab37bf6c49bc26c43ddd958218f63ba00a6aef1658dc627ec13f4fc59382463d9e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CP<a id="ab37bf6c49bc26c43ddd958218f63ba00a2ee9b253b17d18db5307d47d1051e0ff"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COMBINE<a id="ab37bf6c49bc26c43ddd958218f63ba00a430e420ba3e875cc93a5ca1a2e0d5323"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VASL<a id="ab37bf6c49bc26c43ddd958218f63ba00a8e2c8e471897af4c1a0de9fd9a6cb916"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VASR<a id="ab37bf6c49bc26c43ddd958218f63ba00a37726c3aba6f07d05bcc852246709a55"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VLSR<a id="ab37bf6c49bc26c43ddd958218f63ba00a70e0cc746ef86326b61e9e5ac551a7f3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MFSHL<a id="ab37bf6c49bc26c43ddd958218f63ba00a0d21bdd1c458dab044e01d539e818f57"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MFSHR<a id="ab37bf6c49bc26c43ddd958218f63ba00a0397d04a173e4db9e622a1141662892f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SSAT<a id="ab37bf6c49bc26c43ddd958218f63ba00abfd30bd98f06d1b15f09baa6f7268d1d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">USAT<a id="ab37bf6c49bc26c43ddd958218f63ba00a9388d8cfccb9211cf35a745958b24fa0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMUL_LOHI<a id="ab37bf6c49bc26c43ddd958218f63ba00a4090432aaa3ba62553b0e9d2daff0c11"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UMUL_LOHI<a id="ab37bf6c49bc26c43ddd958218f63ba00a4977490ccdba9f9422517795ef5ea402"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">USMUL_LOHI<a id="ab37bf6c49bc26c43ddd958218f63ba00a19d50617fc363fd215aaf24dfa2524cd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TSTBIT<a id="ab37bf6c49bc26c43ddd958218f63ba00af3fe95001bc213eb3d119514db3d3fdc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">INSERT<a id="ab37bf6c49bc26c43ddd958218f63ba00a4b889b7215dd50d9053dc5dc05d5510a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EXTRACTU<a id="ab37bf6c49bc26c43ddd958218f63ba00acc7057ec94dbad75e20e354472144060"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VEXTRACTW<a id="ab37bf6c49bc26c43ddd958218f63ba00aa9c35b54e1d744687ad7b214555ce902"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VINSERTW0<a id="ab37bf6c49bc26c43ddd958218f63ba00af959aca9df8083bbf483798487389ae1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VROR<a id="ab37bf6c49bc26c43ddd958218f63ba00a4a1e3d57d3e0a19f7166057857741d65"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TC_RETURN<a id="ab37bf6c49bc26c43ddd958218f63ba00a06155db8fed367ffea8ffaa7824dd1c3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EH_RETURN<a id="ab37bf6c49bc26c43ddd958218f63ba00ad218b254d05c0c38a59fd091da438ccb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DCFETCH<a id="ab37bf6c49bc26c43ddd958218f63ba00a184fa8af8a7717ce3db342566d267552"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">READCYCLE<a id="ab37bf6c49bc26c43ddd958218f63ba00ae0571abb5f22498fadb10de8c1d2b8e2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">READTIMER<a id="ab37bf6c49bc26c43ddd958218f63ba00a1a48bb6e3e883193d879d812ee0c4916"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PTRUE<a id="ab37bf6c49bc26c43ddd958218f63ba00a0876995f35aa88104344e0a09a750174"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PFALSE<a id="ab37bf6c49bc26c43ddd958218f63ba00ab5369d4484aebe3d84017e4cb5d9dc29"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">D2P<a id="ab37bf6c49bc26c43ddd958218f63ba00a3360cb42f11fb63b13786b0200aec9c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">P2D<a id="ab37bf6c49bc26c43ddd958218f63ba00a53f79035e9c27af7ce35d9ed6ccc538b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">V2Q<a id="ab37bf6c49bc26c43ddd958218f63ba00a034950f263ca9df98ed6a9dca4e2df13"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Q2V<a id="ab37bf6c49bc26c43ddd958218f63ba00a56ff9046d0f0aeec19b4c075657b99c6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">QCAT<a id="ab37bf6c49bc26c43ddd958218f63ba00aae4eba6d6f3f9c32ce014896eb3f6376"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">QTRUE<a id="ab37bf6c49bc26c43ddd958218f63ba00aa46bf38915c101b10ff407106c332f21"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">QFALSE<a id="ab37bf6c49bc26c43ddd958218f63ba00aa7e6df8b19cc29e61783c31f4804299f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TL_EXTEND<a id="ab37bf6c49bc26c43ddd958218f63ba00ab52dd654ebff7c32e8d079ec53e58df0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TL_TRUNCATE<a id="ab37bf6c49bc26c43ddd958218f63ba00a662d9d1c3bdd6545232f81a3eaeceae5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPECAST<a id="ab37bf6c49bc26c43ddd958218f63ba00abc78d6c7742c7d8ccc67946b78f2ba68"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VALIGN<a id="ab37bf6c49bc26c43ddd958218f63ba00aae603a996b86accb519e1b2ba0f40461"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VALIGNADDR<a id="ab37bf6c49bc26c43ddd958218f63ba00a8c1abada2f3e5b50b93fed048f4e67ec"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ISEL<a id="ab37bf6c49bc26c43ddd958218f63ba00a0fbe77e798cb4b9c9a3e62f4d2085395"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OP_END<a id="ab37bf6c49bc26c43ddd958218f63ba00a85e56e243be25ece4e149f9af2344848"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonisellowering-h">HexagonISelLowering.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonisellowering-h">HexagonISelLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
