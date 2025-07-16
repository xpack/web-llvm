---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/riscvfprndmode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `RISCVFPRndMode` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::RISCVFPRndMode { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">RoundingMode { <a href="#a9214a4f7f7322f485189dd3726776b76">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedc240e2d2ffbe260190289a8014707d">roundingModeToString</a> (RoundingMode RndMode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a9214a4f7f7322f485189dd3726776b76">RoundingMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a572415830c007d4e57c1733fdc7007a8">stringToRoundingMode</a> (StringRef Str)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4585a4281eeceb0ebb18437056cdfc85">isValidRoundingMode</a> (unsigned Mode)</td>
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

### RoundingMode {#a9214a4f7f7322f485189dd3726776b76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::RISCVFPRndMode::RoundingMode </td>
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
<td class="doxyEnumItemName">RNE<a id="a9214a4f7f7322f485189dd3726776b76af4acf467b6b1c729666f8735cb3f61fb"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RTZ<a id="a9214a4f7f7322f485189dd3726776b76a5bdeddce1d5418fc8d89741d396541ad"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RDN<a id="a9214a4f7f7322f485189dd3726776b76a642e9fcb9dca2d17fb50315e8bb33b34"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RUP<a id="a9214a4f7f7322f485189dd3726776b76a1175f7692ae965210e9b23087b4fa296"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RMM<a id="a9214a4f7f7322f485189dd3726776b76a8718680058d5a8fbbf26279e27976f10"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DYN<a id="a9214a4f7f7322f485189dd3726776b76a399e2c0b0a6d3a36cfcd4471d559bcf8"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Invalid<a id="a9214a4f7f7322f485189dd3726776b76ab65ca7d0410de41623877434a3f1d45f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvbaseinfo-h">RISCVBaseInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### isValidRoundingMode() {#a4585a4281eeceb0ebb18437056cdfc85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVFPRndMode::isValidRoundingMode (unsigned Mode)</td>
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



<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvbaseinfo-h">RISCVBaseInfo.h</a>.</p>


<p>References <a href="#a9214a4f7f7322f485189dd3726776b76a399e2c0b0a6d3a36cfcd4471d559bcf8">DYN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#aef71c4b21823f236e70cc6d62375adcd">Mode</a>, <a href="#a9214a4f7f7322f485189dd3726776b76a642e9fcb9dca2d17fb50315e8bb33b34">RDN</a>, <a href="#a9214a4f7f7322f485189dd3726776b76a8718680058d5a8fbbf26279e27976f10">RMM</a>, <a href="#a9214a4f7f7322f485189dd3726776b76af4acf467b6b1c729666f8735cb3f61fb">RNE</a>, <a href="#a9214a4f7f7322f485189dd3726776b76a5bdeddce1d5418fc8d89741d396541ad">RTZ</a> and <a href="#a9214a4f7f7322f485189dd3726776b76a1175f7692ae965210e9b23087b4fa296">RUP</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#adc3617a91dd15eebf477e074cf7d57bf">decodeFRMArg</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a6643db423ad018f2a7375b8f46e439af">llvm::RISCVInstrInfo::verifyInstruction</a>.</p>

</div>
</div>

### roundingModeToString() {#aedc240e2d2ffbe260190289a8014707d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::RISCVFPRndMode::roundingModeToString (<a href="#a9214a4f7f7322f485189dd3726776b76">RoundingMode</a> RndMode)</td>
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



<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvbaseinfo-h">RISCVBaseInfo.h</a>.</p>


<p>References <a href="#a9214a4f7f7322f485189dd3726776b76a399e2c0b0a6d3a36cfcd4471d559bcf8">DYN</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a9214a4f7f7322f485189dd3726776b76a642e9fcb9dca2d17fb50315e8bb33b34">RDN</a>, <a href="#a9214a4f7f7322f485189dd3726776b76a8718680058d5a8fbbf26279e27976f10">RMM</a>, <a href="#a9214a4f7f7322f485189dd3726776b76af4acf467b6b1c729666f8735cb3f61fb">RNE</a>, <a href="#a9214a4f7f7322f485189dd3726776b76a5bdeddce1d5418fc8d89741d396541ad">RTZ</a> and <a href="#a9214a4f7f7322f485189dd3726776b76a1175f7692ae965210e9b23087b4fa296">RUP</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#a8899a9d651df9e263ab389f5ed6ac5bb">llvm::RISCVInstPrinter::printFRMArg</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#a5ad3ec0afdef915383812a6caec3ba07">llvm::RISCVInstPrinter::printFRMArgLegacy</a>.</p>

</div>
</div>

### stringToRoundingMode() {#a572415830c007d4e57c1733fdc7007a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RoundingMode llvm::RISCVFPRndMode::stringToRoundingMode (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
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



<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvbaseinfo-h">RISCVBaseInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="#a9214a4f7f7322f485189dd3726776b76a399e2c0b0a6d3a36cfcd4471d559bcf8">DYN</a>, <a href="#a9214a4f7f7322f485189dd3726776b76ab65ca7d0410de41623877434a3f1d45f">Invalid</a>, <a href="#a9214a4f7f7322f485189dd3726776b76a642e9fcb9dca2d17fb50315e8bb33b34">RDN</a>, <a href="#a9214a4f7f7322f485189dd3726776b76a8718680058d5a8fbbf26279e27976f10">RMM</a>, <a href="#a9214a4f7f7322f485189dd3726776b76af4acf467b6b1c729666f8735cb3f61fb">RNE</a>, <a href="#a9214a4f7f7322f485189dd3726776b76a5bdeddce1d5418fc8d89741d396541ad">RTZ</a> and <a href="#a9214a4f7f7322f485189dd3726776b76a1175f7692ae965210e9b23087b4fa296">RUP</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvbaseinfo-h">RISCVBaseInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
