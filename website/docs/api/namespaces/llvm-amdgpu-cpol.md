---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/amdgpu/cpol
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `CPol` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::AMDGPU::CPol { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CPol { <a href="#a7d79a4b341da8ac60b91c1f4b1ea42c4">...</a> }</td>
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

### CPol {#a7d79a4b341da8ac60b91c1f4b1ea42c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AMDGPU::CPol::CPol </td>
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
<td class="doxyEnumItemName">GLC<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4a54ef769ac24b3f9c29d7f0dc5433fecd"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SLC<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4a3a23f03bffa1237fdd6821059886a6a0"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DLC<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4a2d8942c601cf6ab6e7ee6dcfddf7e4f2"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCC<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4aca1659af59093b2b14c2f8aad41e8e2a"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SC0<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4a39cdb386c8e6358db46b658828960381"></a></td>
<td class="doxyEnumItemDescription"> (= GLC)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SC1<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4a4690b39a9275d5b009ecf78b08cfd27c"></a></td>
<td class="doxyEnumItemDescription"> (= SCC)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NT<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4a3795a38ac6eb8cb14191aaba99205a87"></a></td>
<td class="doxyEnumItemDescription"> (= SLC)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ALL_pregfx12<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4ae6823a3df416bbde6f403b6fabd691f4"></a></td>
<td class="doxyEnumItemDescription"> (= GLC | SLC | DLC | SCC)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SWZ_pregfx12<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4a56778fac94bc8b090c94eafb6638771e"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TH<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4ada8257c4b012c0b7ec22b9b95d8ce960"></a></td>
<td class="doxyEnumItemDescription"> (= 0x7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TH_RT<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4a7bd735c6eb6c7d5dba48fed697dfe1f9"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TH_NT<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4aaef85254998537aca69557f206ae1583"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TH_HT<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4ace018baf0cbdb988694819bfee3e56f2"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TH_LU<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4a8154ff62ee9b4a9eaca3572120081634"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TH_RT_WB<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4abbf66453708eb862964d6b60073c529b"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TH_NT_RT<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4a6b9df5d911ce3782abe88c21c637b0d7"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TH_RT_NT<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4a3918171dcff01b95c474c6a9580f9fc4"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TH_NT_HT<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4a8a6ed7cfa54389ce147314d0ac1937c5"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TH_NT_WB<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4a0b5420229ddf44fe3e38da83afcfb778"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TH_BYPASS<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4a943e8db97b9a05f4680b59c7560f83f7"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TH_RESERVED<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4aabb8f44bfe93d622a12472e1e3554a58"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TH_ATOMIC_RETURN<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4a2e92f3bb1fbe1699bbc5a048f05bc71c"></a></td>
<td class="doxyEnumItemDescription"> (= GLC)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TH_ATOMIC_NT<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4a26903d9581af4af246f494648dafc69b"></a></td>
<td class="doxyEnumItemDescription"> (= SLC)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TH_ATOMIC_CASCADE<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4addb25eae45a1a3aebb6a89356a12a274"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCOPE<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4aa8e9e83bd8766765cd8143ebfa384962"></a></td>
<td class="doxyEnumItemDescription"> (= 0x3 &lt;&lt; 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCOPE_CU<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4a5058ee66fad10c33b4b4444dd2686b7e"></a></td>
<td class="doxyEnumItemDescription"> (= 0 &lt;&lt; 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCOPE_SE<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4a7dc2e69975fb9894a38e613ae389fd2a"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCOPE_DEV<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4a824fd28203d9969e65c6b03a75509ef3"></a></td>
<td class="doxyEnumItemDescription"> (= 2 &lt;&lt; 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCOPE_SYS<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4a642542075686ad680d6c3e477dc6eebd"></a></td>
<td class="doxyEnumItemDescription"> (= 3 &lt;&lt; 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SWZ<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4a948baa02c7d133a6f922eacc99fa487d"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ALL<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4a6180464a3b68ceb5491256aeef23553a"></a></td>
<td class="doxyEnumItemDescription"> (= TH | SCOPE)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TH_TYPE_LOAD<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4aeeb5b956d3b600a2c0203104cbedac83"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TH_TYPE_STORE<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4a120170f2992da8e04d8809ba48de4c23"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TH_TYPE_ATOMIC<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4aef781227c1057999bb260e756ae9f107"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TH_REAL_BYPASS<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4aef4b0079f425ae147002d32dac402226"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VOLATILE<a id="a7d79a4b341da8ac60b91c1f4b1ea42c4ae9234788773753045755ef99552134e4"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 31)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
