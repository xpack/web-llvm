---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/lpac
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `LPAC` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::LPAC { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AluCode { <a href="#ab2e8fd263c886a713ccba7505c1b2ee0">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54701527fd88d4bfb1426c2d2e9d1ddd">encodeLanaiAluCode</a> (unsigned AluOp)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12ec23eae67df792dea7a369dced8f6e">getAluOp</a> (unsigned AluOp)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cbb5fce8a0eddbb1a2c3e1e1de932d3">isPreOp</a> (unsigned AluOp)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9561348a5db976ea3ff9e29b8efed89">isPostOp</a> (unsigned AluOp)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a515abd8750ded11310a7ff9d1af34f98">makePreOp</a> (unsigned AluOp)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20f503a5323ba4d764fd7adc57ec1747">makePostOp</a> (unsigned AluOp)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1b67731af52d82eb9854d6db403b621">modifiesOp</a> (unsigned AluOp)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1db568a066a8c3cd4983ad7baf1111cc">lanaiAluCodeToString</a> (unsigned AluOp)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#ab2e8fd263c886a713ccba7505c1b2ee0">AluCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82e423fdc73ec257d71d9881ca6744e8">stringToLanaiAluCode</a> (StringRef S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#ab2e8fd263c886a713ccba7505c1b2ee0">AluCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c194b4d8abdc7470d7b9b50ff3e1b7c">isdToLanaiAluCode</a> (ISD::NodeType Node_type)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae12d6990504e73163b4af0125619d464">Lanai_PRE_OP</a> = 0x40</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96830eb21386800e43af4a53a4ce4d6b">Lanai_POST_OP</a> = 0x80</td>
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

### AluCode {#ab2e8fd263c886a713ccba7505c1b2ee0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::LPAC::AluCode </td>
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
<td class="doxyEnumItemName">ADD<a id="ab2e8fd263c886a713ccba7505c1b2ee0a25d8ba0c31384de6b8eaf87262199804"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADDC<a id="ab2e8fd263c886a713ccba7505c1b2ee0a2813222a12da6ef398266c2772024d0b"></a></td>
<td class="doxyEnumItemDescription"> (= 0x01)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SUB<a id="ab2e8fd263c886a713ccba7505c1b2ee0aeac5360fd57cf828f2c5a7dda5978787"></a></td>
<td class="doxyEnumItemDescription"> (= 0x02)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SUBB<a id="ab2e8fd263c886a713ccba7505c1b2ee0ae42c318d7a1c0e3a733c995a364b79da"></a></td>
<td class="doxyEnumItemDescription"> (= 0x03)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AND<a id="ab2e8fd263c886a713ccba7505c1b2ee0a5d9bd04ccb1bea421a4d8436c59b0b92"></a></td>
<td class="doxyEnumItemDescription"> (= 0x04)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OR<a id="ab2e8fd263c886a713ccba7505c1b2ee0ad9ba23ea041004ef20184368bbb0488c"></a></td>
<td class="doxyEnumItemDescription"> (= 0x05)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XOR<a id="ab2e8fd263c886a713ccba7505c1b2ee0a0aa89b916276a107ae3c5eea86213636"></a></td>
<td class="doxyEnumItemDescription"> (= 0x06)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SPECIAL<a id="ab2e8fd263c886a713ccba7505c1b2ee0a7cc8297cbf4bed78b7c26915bcacb99c"></a></td>
<td class="doxyEnumItemDescription"> (= 0x07)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SHL<a id="ab2e8fd263c886a713ccba7505c1b2ee0a1c925551fe6b6594e1981c73692667c5"></a></td>
<td class="doxyEnumItemDescription"> (= 0x17)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRL<a id="ab2e8fd263c886a713ccba7505c1b2ee0af6a627123e84eb41d500bcb8f9e2f8b6"></a></td>
<td class="doxyEnumItemDescription"> (= 0x27)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRA<a id="ab2e8fd263c886a713ccba7505c1b2ee0a6f47b0d8fbc54652a45b103c20197a4f"></a></td>
<td class="doxyEnumItemDescription"> (= 0x37)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNKNOWN<a id="ab2e8fd263c886a713ccba7505c1b2ee0a9ac6c6caa2e21edbfeba176ac8f78b4d"></a></td>
<td class="doxyEnumItemDescription"> (= 0xFF)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaialucode-h">LanaiAluCode.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### encodeLanaiAluCode() {#a54701527fd88d4bfb1426c2d2e9d1ddd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LPAC::encodeLanaiAluCode (unsigned AluOp)</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaialucode-h">LanaiAluCode.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/anonymous-lanaimccodeemitter-cpp-/lanaimccodeemitter/#abdd107007255b33a321fb54311fbab99">llvm::anonymous{LanaiMCCodeEmitter.cpp}::LanaiMCCodeEmitter::getRrMemoryOpValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/mctargetdesc/lanaiinstprinter-cpp/#a92facff2fd13644a7581642f68ee8113">usesGivenOffset</a>.</p>

</div>
</div>

### getAluOp() {#a12ec23eae67df792dea7a369dced8f6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LPAC::getAluOp (unsigned AluOp)</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaialucode-h">LanaiAluCode.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/anonymous-lanaimccodeemitter-cpp-/lanaimccodeemitter/#a1660300cab17a3aa42a7648d7ef16d59">llvm::anonymous{LanaiMCCodeEmitter.cpp}::LanaiMCCodeEmitter::getRiMemoryOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-lanaimccodeemitter-cpp-/lanaimccodeemitter/#abdd107007255b33a321fb54311fbab99">llvm::anonymous{LanaiMCCodeEmitter.cpp}::LanaiMCCodeEmitter::getRrMemoryOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-lanaimccodeemitter-cpp-/lanaimccodeemitter/#acb6e80d03942494b5ccb861bc69ae7c4">llvm::anonymous{LanaiMCCodeEmitter.cpp}::LanaiMCCodeEmitter::getSplsOpValue</a> and <a href="#a1db568a066a8c3cd4983ad7baf1111cc">lanaiAluCodeToString</a>.</p>

</div>
</div>

### isdToLanaiAluCode() {#a5c194b4d8abdc7470d7b9b50ff3e1b7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AluCode llvm::LPAC::isdToLanaiAluCode (<a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110">ISD::NodeType</a> Node_type)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiiseldagtodag-cpp">LanaiISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="#ab2e8fd263c886a713ccba7505c1b2ee0a25d8ba0c31384de6b8eaf87262199804">ADD</a>, <a href="#ab2e8fd263c886a713ccba7505c1b2ee0a2813222a12da6ef398266c2772024d0b">ADDC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad116e32876f2275acf60ffb1651c9256">llvm::ISD::ADDE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="#ab2e8fd263c886a713ccba7505c1b2ee0a5d9bd04ccb1bea421a4d8436c59b0b92">AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="#ab2e8fd263c886a713ccba7505c1b2ee0ad9ba23ea041004ef20184368bbb0488c">OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="#ab2e8fd263c886a713ccba7505c1b2ee0a1c925551fe6b6594e1981c73692667c5">SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a>, <a href="#ab2e8fd263c886a713ccba7505c1b2ee0a6f47b0d8fbc54652a45b103c20197a4f">SRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="#ab2e8fd263c886a713ccba7505c1b2ee0af6a627123e84eb41d500bcb8f9e2f8b6">SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="#ab2e8fd263c886a713ccba7505c1b2ee0aeac5360fd57cf828f2c5a7dda5978787">SUB</a>, <a href="#ab2e8fd263c886a713ccba7505c1b2ee0ae42c318d7a1c0e3a733c995a364b79da">SUBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac9246c101c0cc9232e37b3941194bb13">llvm::ISD::SUBE</a>, <a href="#ab2e8fd263c886a713ccba7505c1b2ee0a9ac6c6caa2e21edbfeba176ac8f78b4d">UNKNOWN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a> and <a href="#ab2e8fd263c886a713ccba7505c1b2ee0a0aa89b916276a107ae3c5eea86213636">XOR</a>.</p>

</div>
</div>

### isPostOp() {#ac9561348a5db976ea3ff9e29b8efed89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LPAC::isPostOp (unsigned AluOp)</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaialucode-h">LanaiAluCode.h</a>.</p>


<p>Reference <a href="#a96830eb21386800e43af4a53a4ce4d6b">Lanai_POST_OP</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad74efac97a18b61ef91f69e7a25532ce">llvm::adjustPqBits</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-lanaimccodeemitter-cpp-/lanaimccodeemitter/#a1660300cab17a3aa42a7648d7ef16d59">llvm::anonymous{LanaiMCCodeEmitter.cpp}::LanaiMCCodeEmitter::getRiMemoryOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-lanaimccodeemitter-cpp-/lanaimccodeemitter/#abdd107007255b33a321fb54311fbab99">llvm::anonymous{LanaiMCCodeEmitter.cpp}::LanaiMCCodeEmitter::getRrMemoryOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-lanaimccodeemitter-cpp-/lanaimccodeemitter/#acb6e80d03942494b5ccb861bc69ae7c4">llvm::anonymous{LanaiMCCodeEmitter.cpp}::LanaiMCCodeEmitter::getSplsOpValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/mctargetdesc/lanaiinstprinter-cpp/#a1cbfb0929df360bbad7c2c4d0e179081">isPostIncrementForm</a>, <a href="#a515abd8750ded11310a7ff9d1af34f98">makePreOp</a>, <a href="#af1b67731af52d82eb9854d6db403b621">modifiesOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/mctargetdesc/lanaiinstprinter-cpp/#a8313310c9f42f98f1d9e0c7c7df5fbf9">printMemoryBaseRegister</a> and <a href="/web-llvm/docs/api/classes/llvm/lanaiinstprinter/#a129e8be81d8a522c9af10b189279be89">llvm::LanaiInstPrinter::printMemRrOperand</a>.</p>

</div>
</div>

### isPreOp() {#a0cbb5fce8a0eddbb1a2c3e1e1de932d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LPAC::isPreOp (unsigned AluOp)</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaialucode-h">LanaiAluCode.h</a>.</p>


<p>Reference <a href="#ae12d6990504e73163b4af0125619d464">Lanai_PRE_OP</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/anonymous-lanaimccodeemitter-cpp-/lanaimccodeemitter/#a1660300cab17a3aa42a7648d7ef16d59">llvm::anonymous{LanaiMCCodeEmitter.cpp}::LanaiMCCodeEmitter::getRiMemoryOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-lanaimccodeemitter-cpp-/lanaimccodeemitter/#abdd107007255b33a321fb54311fbab99">llvm::anonymous{LanaiMCCodeEmitter.cpp}::LanaiMCCodeEmitter::getRrMemoryOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-lanaimccodeemitter-cpp-/lanaimccodeemitter/#acb6e80d03942494b5ccb861bc69ae7c4">llvm::anonymous{LanaiMCCodeEmitter.cpp}::LanaiMCCodeEmitter::getSplsOpValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/mctargetdesc/lanaiinstprinter-cpp/#acf0ad3b817a397833de756ed9ab05057">isPreIncrementForm</a>, <a href="#a20f503a5323ba4d764fd7adc57ec1747">makePostOp</a>, <a href="#af1b67731af52d82eb9854d6db403b621">modifiesOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/mctargetdesc/lanaiinstprinter-cpp/#a8313310c9f42f98f1d9e0c7c7df5fbf9">printMemoryBaseRegister</a> and <a href="/web-llvm/docs/api/classes/llvm/lanaiinstprinter/#a129e8be81d8a522c9af10b189279be89">llvm::LanaiInstPrinter::printMemRrOperand</a>.</p>

</div>
</div>

### lanaiAluCodeToString() {#a1db568a066a8c3cd4983ad7baf1111cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::LPAC::lanaiAluCodeToString (unsigned AluOp)</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaialucode-h">LanaiAluCode.h</a>.</p>


<p>References <a href="#ab2e8fd263c886a713ccba7505c1b2ee0a25d8ba0c31384de6b8eaf87262199804">ADD</a>, <a href="#ab2e8fd263c886a713ccba7505c1b2ee0a2813222a12da6ef398266c2772024d0b">ADDC</a>, <a href="#ab2e8fd263c886a713ccba7505c1b2ee0a5d9bd04ccb1bea421a4d8436c59b0b92">AND</a>, <a href="#a12ec23eae67df792dea7a369dced8f6e">getAluOp</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#ab2e8fd263c886a713ccba7505c1b2ee0ad9ba23ea041004ef20184368bbb0488c">OR</a>, <a href="#ab2e8fd263c886a713ccba7505c1b2ee0a1c925551fe6b6594e1981c73692667c5">SHL</a>, <a href="#ab2e8fd263c886a713ccba7505c1b2ee0a6f47b0d8fbc54652a45b103c20197a4f">SRA</a>, <a href="#ab2e8fd263c886a713ccba7505c1b2ee0af6a627123e84eb41d500bcb8f9e2f8b6">SRL</a>, <a href="#ab2e8fd263c886a713ccba7505c1b2ee0aeac5360fd57cf828f2c5a7dda5978787">SUB</a>, <a href="#ab2e8fd263c886a713ccba7505c1b2ee0ae42c318d7a1c0e3a733c995a364b79da">SUBB</a> and <a href="#ab2e8fd263c886a713ccba7505c1b2ee0a0aa89b916276a107ae3c5eea86213636">XOR</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lanaiinstprinter/#a129e8be81d8a522c9af10b189279be89">llvm::LanaiInstPrinter::printMemRrOperand</a>.</p>

</div>
</div>

### makePostOp() {#a20f503a5323ba4d764fd7adc57ec1747}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LPAC::makePostOp (unsigned AluOp)</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaialucode-h">LanaiAluCode.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0cbb5fce8a0eddbb1a2c3e1e1de932d3">isPreOp</a> and <a href="#a96830eb21386800e43af4a53a4ce4d6b">Lanai_POST_OP</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp/#ac6749e4cbd2e3405a21f45adbdeb3bea">AluWithPrePost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaimemalucombiner-cpp/#a3d8451ff05b58b604cb87a1623ef73b3">INITIALIZE_PASS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/disassembler/lanaidisassembler-cpp/#a45e407f6e7148030f31c1063d12d25b0">PostOperandDecodeAdjust</a>.</p>

</div>
</div>

### makePreOp() {#a515abd8750ded11310a7ff9d1af34f98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LPAC::makePreOp (unsigned AluOp)</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaialucode-h">LanaiAluCode.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac9561348a5db976ea3ff9e29b8efed89">isPostOp</a> and <a href="#ae12d6990504e73163b4af0125619d464">Lanai_PRE_OP</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp/#ac6749e4cbd2e3405a21f45adbdeb3bea">AluWithPrePost</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiframelowering/#a1cc86e82857e8ff7bceddf8838830577">llvm::LanaiFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaimemalucombiner-cpp/#a3d8451ff05b58b604cb87a1623ef73b3">INITIALIZE_PASS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/disassembler/lanaidisassembler-cpp/#a45e407f6e7148030f31c1063d12d25b0">PostOperandDecodeAdjust</a>.</p>

</div>
</div>

### modifiesOp() {#af1b67731af52d82eb9854d6db403b621}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LPAC::modifiesOp (unsigned AluOp)</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaialucode-h">LanaiAluCode.h</a>.</p>


<p>References <a href="#ac9561348a5db976ea3ff9e29b8efed89">isPostOp</a> and <a href="#a0cbb5fce8a0eddbb1a2c3e1e1de932d3">isPreOp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad74efac97a18b61ef91f69e7a25532ce">llvm::adjustPqBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaimemalucombiner-cpp/#a3d8451ff05b58b604cb87a1623ef73b3">INITIALIZE_PASS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp/#a14c5fa321a079e20b4a884fee7b7788a">IsMemoryAssignmentError</a>.</p>

</div>
</div>

### stringToLanaiAluCode() {#a82e423fdc73ec257d71d9881ca6744e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AluCode llvm::LPAC::stringToLanaiAluCode (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaialucode-h">LanaiAluCode.h</a>.</p>


<p>References <a href="#ab2e8fd263c886a713ccba7505c1b2ee0a25d8ba0c31384de6b8eaf87262199804">ADD</a>, <a href="#ab2e8fd263c886a713ccba7505c1b2ee0a2813222a12da6ef398266c2772024d0b">ADDC</a>, <a href="#ab2e8fd263c886a713ccba7505c1b2ee0a5d9bd04ccb1bea421a4d8436c59b0b92">AND</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="#ab2e8fd263c886a713ccba7505c1b2ee0ad9ba23ea041004ef20184368bbb0488c">OR</a>, <a href="#ab2e8fd263c886a713ccba7505c1b2ee0a1c925551fe6b6594e1981c73692667c5">SHL</a>, <a href="#ab2e8fd263c886a713ccba7505c1b2ee0a6f47b0d8fbc54652a45b103c20197a4f">SRA</a>, <a href="#ab2e8fd263c886a713ccba7505c1b2ee0af6a627123e84eb41d500bcb8f9e2f8b6">SRL</a>, <a href="#ab2e8fd263c886a713ccba7505c1b2ee0aeac5360fd57cf828f2c5a7dda5978787">SUB</a>, <a href="#ab2e8fd263c886a713ccba7505c1b2ee0ae42c318d7a1c0e3a733c995a364b79da">SUBB</a>, <a href="#ab2e8fd263c886a713ccba7505c1b2ee0a9ac6c6caa2e21edbfeba176ac8f78b4d">UNKNOWN</a> and <a href="#ab2e8fd263c886a713ccba7505c1b2ee0a0aa89b916276a107ae3c5eea86213636">XOR</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### Lanai\_POST\_OP {#a96830eb21386800e43af4a53a4ce4d6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int llvm::LPAC::Lanai_POST_OP = 0x80</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaialucode-h">LanaiAluCode.h</a>.</p>


<p>Referenced by <a href="#ac9561348a5db976ea3ff9e29b8efed89">isPostOp</a> and <a href="#a20f503a5323ba4d764fd7adc57ec1747">makePostOp</a>.</p>

</div>
</div>

### Lanai\_PRE\_OP {#ae12d6990504e73163b4af0125619d464}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int llvm::LPAC::Lanai_PRE_OP = 0x40</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaialucode-h">LanaiAluCode.h</a>.</p>


<p>Referenced by <a href="#a0cbb5fce8a0eddbb1a2c3e1e1de932d3">isPreOp</a> and <a href="#a515abd8750ded11310a7ff9d1af34f98">makePreOp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaialucode-h">LanaiAluCode.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiiseldagtodag-cpp">LanaiISelDAGToDAG.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
