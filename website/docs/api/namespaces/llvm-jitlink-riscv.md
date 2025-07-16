---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/jitlink/riscv
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `riscv` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::jitlink::riscv { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">EdgeKind_riscv : <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a> { <a href="#a7e8800193a803fbffb29c072afe09ab7">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents riscv fixups. <a href="#a7e8800193a803fbffb29c072afe09ab7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f023b538bb6748eea141022bd74dce4">getEdgeKindName</a> (Edge::Kind K)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a string name for the given riscv edge. <a href="#a8f023b538bb6748eea141022bd74dce4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Enumerations

### EdgeKind\_riscv {#a7e8800193a803fbffb29c072afe09ab7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::jitlink::riscv::EdgeKind_riscv : <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represents riscv fixups.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RISCV_32<a id="a7e8800193a803fbffb29c072afe09ab7a8ecf251fe8eb3fd8d3f4b136feaaec06"></a></td>
<td class="doxyEnumItemDescription">A plain 32-bit pointer value relocation (= Edge::FirstRelocation)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RISCV_64<a id="a7e8800193a803fbffb29c072afe09ab7a9a66674bae2c0fac22e4070ab792b196"></a></td>
<td class="doxyEnumItemDescription">A plain 64-bit pointer value relocation</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RISCV_BRANCH<a id="a7e8800193a803fbffb29c072afe09ab7a7a6ff665010dd91d3422ab48c0737d11"></a></td>
<td class="doxyEnumItemDescription">PC-relative branch pointer value relocation</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RISCV_JAL<a id="a7e8800193a803fbffb29c072afe09ab7a170b240f17feb4d34b711ece12392547"></a></td>
<td class="doxyEnumItemDescription">High 20 bits of PC-relative jump pointer value relocation</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RISCV_CALL<a id="a7e8800193a803fbffb29c072afe09ab7a6bb3584479526a49e01e8c909072a467"></a></td>
<td class="doxyEnumItemDescription">PC relative call</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RISCV_CALL_PLT<a id="a7e8800193a803fbffb29c072afe09ab7a5e9772200453ea0af2a6e0e4016704a1"></a></td>
<td class="doxyEnumItemDescription">PC relative call by PLT</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RISCV_GOT_HI20<a id="a7e8800193a803fbffb29c072afe09ab7af72744cd81f5b758df3c36303fc06a82"></a></td>
<td class="doxyEnumItemDescription">PC relative GOT offset</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RISCV_PCREL_HI20<a id="a7e8800193a803fbffb29c072afe09ab7ada157a5fb3fa171970dcda67ba91e95c"></a></td>
<td class="doxyEnumItemDescription">High 20 bits of PC relative relocation</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RISCV_PCREL_LO12_I<a id="a7e8800193a803fbffb29c072afe09ab7a38126555db343f59eee39db2cd6595a5"></a></td>
<td class="doxyEnumItemDescription">Low 12 bits of PC relative relocation, used by I type instruction format</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RISCV_PCREL_LO12_S<a id="a7e8800193a803fbffb29c072afe09ab7a7e0a456eee867e2ffbc939a961b805a1"></a></td>
<td class="doxyEnumItemDescription">Low 12 bits of PC relative relocation, used by S type instruction format</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RISCV_HI20<a id="a7e8800193a803fbffb29c072afe09ab7a3808228fc1838c5d6b724b9e3b139ae6"></a></td>
<td class="doxyEnumItemDescription">High 20 bits of 32-bit pointer value relocation</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RISCV_LO12_I<a id="a7e8800193a803fbffb29c072afe09ab7aa631dcbbb336c262014bc097e8f66434"></a></td>
<td class="doxyEnumItemDescription">Low 12 bits of 32-bit pointer value relocation</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RISCV_LO12_S<a id="a7e8800193a803fbffb29c072afe09ab7a14ec91a6ed01aecddca9341cd1d91703"></a></td>
<td class="doxyEnumItemDescription">Low 12 bits of 32-bit pointer value relocation, used by S type instruction format</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RISCV_ADD8<a id="a7e8800193a803fbffb29c072afe09ab7a37a5dee16a6020cce660620121e287ba"></a></td>
<td class="doxyEnumItemDescription">8 bits label addition</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RISCV_ADD16<a id="a7e8800193a803fbffb29c072afe09ab7aff1188819c87d0b013da8d003d3303de"></a></td>
<td class="doxyEnumItemDescription">16 bits label addition</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RISCV_ADD32<a id="a7e8800193a803fbffb29c072afe09ab7aea136d6e408b143b33bcb83feab9ad15"></a></td>
<td class="doxyEnumItemDescription">32 bits label addition</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RISCV_ADD64<a id="a7e8800193a803fbffb29c072afe09ab7aded579b35d2d2917f15243dc42c7b619"></a></td>
<td class="doxyEnumItemDescription">64 bits label addition</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RISCV_SUB8<a id="a7e8800193a803fbffb29c072afe09ab7a403842352a64212584bb4d06a368b4ca"></a></td>
<td class="doxyEnumItemDescription">8 bits label subtraction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RISCV_SUB16<a id="a7e8800193a803fbffb29c072afe09ab7afb4904f592f763064389ae4683687bf5"></a></td>
<td class="doxyEnumItemDescription">16 bits label subtraction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RISCV_SUB32<a id="a7e8800193a803fbffb29c072afe09ab7a0318a127e11e18b1be2a8c8eb8929369"></a></td>
<td class="doxyEnumItemDescription">32 bits label subtraction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RISCV_SUB64<a id="a7e8800193a803fbffb29c072afe09ab7aff133630333018c2eca26ae5d923d27a"></a></td>
<td class="doxyEnumItemDescription">64 bits label subtraction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RISCV_RVC_BRANCH<a id="a7e8800193a803fbffb29c072afe09ab7a9a0569b95988af0fe9e29924cb68c0f8"></a></td>
<td class="doxyEnumItemDescription">8-bit PC-relative branch offset</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RISCV_RVC_JUMP<a id="a7e8800193a803fbffb29c072afe09ab7a62639af1aa173f258d1535be64cb978a"></a></td>
<td class="doxyEnumItemDescription">11-bit PC-relative jump offset</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RISCV_SUB6<a id="a7e8800193a803fbffb29c072afe09ab7a6779bd3df1b34942efda1b56939681a0"></a></td>
<td class="doxyEnumItemDescription">6 bits label subtraction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RISCV_SET6<a id="a7e8800193a803fbffb29c072afe09ab7a5e7185739eb60d3466d0182ee34f4c51"></a></td>
<td class="doxyEnumItemDescription">Local label assignment</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RISCV_SET8<a id="a7e8800193a803fbffb29c072afe09ab7afc68dee61dcba825e69274f9ba85d1e2"></a></td>
<td class="doxyEnumItemDescription">Local label assignment</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RISCV_SET16<a id="a7e8800193a803fbffb29c072afe09ab7abcf7adb8ce78cbb5d5bb5e8d3da21063"></a></td>
<td class="doxyEnumItemDescription">Local label assignment</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RISCV_SET32<a id="a7e8800193a803fbffb29c072afe09ab7a61d298af2c527214727c910e1a98a3d9"></a></td>
<td class="doxyEnumItemDescription">Local label assignment</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RISCV_32_PCREL<a id="a7e8800193a803fbffb29c072afe09ab7aaaed10dfde225bc6672d153fa2616d49"></a></td>
<td class="doxyEnumItemDescription">32 bits PC relative relocation</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CallRelaxable<a id="a7e8800193a803fbffb29c072afe09ab7a71c292a54dd4ab86706ecc96fc124d9e"></a></td>
<td class="doxyEnumItemDescription">An auipc/jalr pair eligible for linker relaxation</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AlignRelaxable<a id="a7e8800193a803fbffb29c072afe09ab7ac2e63bb05e50bf29c6a660c4478e03f4"></a></td>
<td class="doxyEnumItemDescription">Alignment requirement used by linker relaxation</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NegDelta32<a id="a7e8800193a803fbffb29c072afe09ab7aa90fd435eb52c9ce714f92442615b472"></a></td>
<td class="doxyEnumItemDescription">32-bit negative delta</td>
</tr>

</table>
</dd>
</dl>


<p>Ordered in the same way as the relocations in include/llvm/BinaryFormat/ELFRelocs/RISCV.def.</p>


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/riscv-h">riscv.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### getEdgeKindName() {#a8f023b538bb6748eea141022bd74dce4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::jitlink::riscv::getEdgeKindName (<a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a> K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a string name for the given riscv edge.</p>


<p>For debugging purposes only</p>


<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/riscv-cpp">riscv.cpp</a>.</p>


<p>References <a href="#a7e8800193a803fbffb29c072afe09ab7ac2e63bb05e50bf29c6a660c4478e03f4">AlignRelaxable</a>, <a href="#a7e8800193a803fbffb29c072afe09ab7a71c292a54dd4ab86706ecc96fc124d9e">CallRelaxable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a06eee57acde48953ffd29ae8d337202e">llvm::jitlink::getGenericEdgeKindName</a>, <a href="#a7e8800193a803fbffb29c072afe09ab7aa90fd435eb52c9ce714f92442615b472">NegDelta32</a>, <a href="#a7e8800193a803fbffb29c072afe09ab7a8ecf251fe8eb3fd8d3f4b136feaaec06">R_RISCV_32</a>, <a href="#a7e8800193a803fbffb29c072afe09ab7aaaed10dfde225bc6672d153fa2616d49">R_RISCV_32_PCREL</a>, <a href="#a7e8800193a803fbffb29c072afe09ab7a9a66674bae2c0fac22e4070ab792b196">R_RISCV_64</a>, <a href="#a7e8800193a803fbffb29c072afe09ab7aff1188819c87d0b013da8d003d3303de">R_RISCV_ADD16</a>, <a href="#a7e8800193a803fbffb29c072afe09ab7aea136d6e408b143b33bcb83feab9ad15">R_RISCV_ADD32</a>, <a href="#a7e8800193a803fbffb29c072afe09ab7aded579b35d2d2917f15243dc42c7b619">R_RISCV_ADD64</a>, <a href="#a7e8800193a803fbffb29c072afe09ab7a37a5dee16a6020cce660620121e287ba">R_RISCV_ADD8</a>, <a href="#a7e8800193a803fbffb29c072afe09ab7a7a6ff665010dd91d3422ab48c0737d11">R_RISCV_BRANCH</a>, <a href="#a7e8800193a803fbffb29c072afe09ab7a6bb3584479526a49e01e8c909072a467">R_RISCV_CALL</a>, <a href="#a7e8800193a803fbffb29c072afe09ab7a5e9772200453ea0af2a6e0e4016704a1">R_RISCV_CALL_PLT</a>, <a href="#a7e8800193a803fbffb29c072afe09ab7af72744cd81f5b758df3c36303fc06a82">R_RISCV_GOT_HI20</a>, <a href="#a7e8800193a803fbffb29c072afe09ab7a3808228fc1838c5d6b724b9e3b139ae6">R_RISCV_HI20</a>, <a href="#a7e8800193a803fbffb29c072afe09ab7a170b240f17feb4d34b711ece12392547">R_RISCV_JAL</a>, <a href="#a7e8800193a803fbffb29c072afe09ab7aa631dcbbb336c262014bc097e8f66434">R_RISCV_LO12_I</a>, <a href="#a7e8800193a803fbffb29c072afe09ab7a14ec91a6ed01aecddca9341cd1d91703">R_RISCV_LO12_S</a>, <a href="#a7e8800193a803fbffb29c072afe09ab7ada157a5fb3fa171970dcda67ba91e95c">R_RISCV_PCREL_HI20</a>, <a href="#a7e8800193a803fbffb29c072afe09ab7a38126555db343f59eee39db2cd6595a5">R_RISCV_PCREL_LO12_I</a>, <a href="#a7e8800193a803fbffb29c072afe09ab7a7e0a456eee867e2ffbc939a961b805a1">R_RISCV_PCREL_LO12_S</a>, <a href="#a7e8800193a803fbffb29c072afe09ab7a9a0569b95988af0fe9e29924cb68c0f8">R_RISCV_RVC_BRANCH</a>, <a href="#a7e8800193a803fbffb29c072afe09ab7a62639af1aa173f258d1535be64cb978a">R_RISCV_RVC_JUMP</a>, <a href="#a7e8800193a803fbffb29c072afe09ab7abcf7adb8ce78cbb5d5bb5e8d3da21063">R_RISCV_SET16</a>, <a href="#a7e8800193a803fbffb29c072afe09ab7a61d298af2c527214727c910e1a98a3d9">R_RISCV_SET32</a>, <a href="#a7e8800193a803fbffb29c072afe09ab7a5e7185739eb60d3466d0182ee34f4c51">R_RISCV_SET6</a>, <a href="#a7e8800193a803fbffb29c072afe09ab7afc68dee61dcba825e69274f9ba85d1e2">R_RISCV_SET8</a>, <a href="#a7e8800193a803fbffb29c072afe09ab7afb4904f592f763064389ae4683687bf5">R_RISCV_SUB16</a>, <a href="#a7e8800193a803fbffb29c072afe09ab7a0318a127e11e18b1be2a8c8eb8929369">R_RISCV_SUB32</a>, <a href="#a7e8800193a803fbffb29c072afe09ab7a6779bd3df1b34942efda1b56939681a0">R_RISCV_SUB6</a>, <a href="#a7e8800193a803fbffb29c072afe09ab7aff133630333018c2eca26ae5d923d27a">R_RISCV_SUB64</a> and <a href="#a7e8800193a803fbffb29c072afe09ab7a403842352a64212584bb4d06a368b4ca">R_RISCV_SUB8</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilder-riscv/#a297f45e62b904349a932f3923358bf50">llvm::jitlink::ELFLinkGraphBuilder_riscv&lt; ELFT &gt;::ELFLinkGraphBuilder_riscv</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/riscv-h">riscv.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/riscv-cpp">riscv.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
