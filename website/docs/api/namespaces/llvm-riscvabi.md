---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/riscvabi
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `RISCVABI` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::RISCVABI { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ABI { <a href="#a11c6ee2d4e18ec16c570243cc285c7e9">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a11c6ee2d4e18ec16c570243cc285c7e9">ABI</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28e75155ea06a5ad70d3a662be05e350">computeTargetABI</a> (const Triple &amp;TT, const FeatureBitset &amp;FeatureBits, StringRef ABIName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a11c6ee2d4e18ec16c570243cc285c7e9">ABI</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16d139f36eb6a2d61dd1c79a4503ecb0">getTargetABI</a> (StringRef ABIName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c75dbf1bd34c20b6265e6af91a32a06">getBPReg</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7554ec1d1735879427a93276e4de1a38">getSCSPReg</a> ()</td>
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

### ABI {#a11c6ee2d4e18ec16c570243cc285c7e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::RISCVABI::ABI </td>
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
<td class="doxyEnumItemName">ABI_ILP32<a id="a11c6ee2d4e18ec16c570243cc285c7e9a8f2e55f34742f82eeaa55cbd79d44c0e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_ILP32F<a id="a11c6ee2d4e18ec16c570243cc285c7e9a8bd020c98ec18f175789493ef90eb66a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_ILP32D<a id="a11c6ee2d4e18ec16c570243cc285c7e9a45fb6ea6c36157d00ae8a43dfedcc260"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_ILP32E<a id="a11c6ee2d4e18ec16c570243cc285c7e9a9e062b1814798f2a29e2b28e74a36bc1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_LP64<a id="a11c6ee2d4e18ec16c570243cc285c7e9ae72b691ee57f47810281dffc97cbde06"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_LP64F<a id="a11c6ee2d4e18ec16c570243cc285c7e9a8a401ce2fcb2329054c1e93cc57cb91e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_LP64D<a id="a11c6ee2d4e18ec16c570243cc285c7e9af5a5e31fdfed05fc333fd92b488670f8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_LP64E<a id="a11c6ee2d4e18ec16c570243cc285c7e9adc7da95e1193beba354466672c1cdb38"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_Unknown<a id="a11c6ee2d4e18ec16c570243cc285c7e9a8f595b6bd8825688b9ac7939a949c829"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 503 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvbaseinfo-h">RISCVBaseInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### computeTargetABI() {#a28e75155ea06a5ad70d3a662be05e350}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ABI llvm::RISCVABI::computeTargetABI (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp; FeatureBits, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ABIName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvbaseinfo-cpp">RISCVBaseInfo.cpp</a>.</p>


<p>References <a href="#a11c6ee2d4e18ec16c570243cc285c7e9a9e062b1814798f2a29e2b28e74a36bc1">ABI_ILP32E</a>, <a href="#a11c6ee2d4e18ec16c570243cc285c7e9adc7da95e1193beba354466672c1cdb38">ABI_LP64E</a>, <a href="#a11c6ee2d4e18ec16c570243cc285c7e9a8f595b6bd8825688b9ac7939a949c829">ABI_Unknown</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="#a16d139f36eb6a2d61dd1c79a4503ecb0">getTargetABI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvfeatures/#aeff18ccfe73c98dd2078d7523eb4db04">llvm::RISCVFeatures::parseFeatureBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-riscvasmparser-cpp-/riscvasmparser/#af34b3385ad6d2dc040f431e84cd822eb">anonymous{RISCVAsmParser.cpp}::RISCVAsmParser::RISCVAsmParser</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvtargetelfstreamer/#a9c657032eafd38a8fa07606efe9af3a7">llvm::RISCVTargetELFStreamer::RISCVTargetELFStreamer</a>.</p>

</div>
</div>

### getBPReg() {#a3c75dbf1bd34c20b6265e6af91a32a06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister llvm::RISCVABI::getBPReg ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvbaseinfo-cpp">RISCVBaseInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#aa2e3cf793a3ed0af11da73a0bfbb5ad1">llvm::RISCVFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a131316d63f21b59d27d82ae95b91bfc7">llvm::RISCVFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a9258a9f50df17d6b3c064af9bf06c2bf">llvm::RISCVFrameLowering::getFrameIndexReference</a> and <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a277355964aa533df56cf3e0de6701b3d">llvm::RISCVRegisterInfo::getReservedRegs</a>.</p>

</div>
</div>

### getSCSPReg() {#a7554ec1d1735879427a93276e4de1a38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister llvm::RISCVABI::getSCSPReg ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvbaseinfo-cpp">RISCVBaseInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#adcff3487a7ab24e32ed892aedf767cf1">emitSCSEpilogue</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#acf179a5b6cfdcd80b458b93d503e0ed0">emitSCSPrologue</a>.</p>

</div>
</div>

### getTargetABI() {#a16d139f36eb6a2d61dd1c79a4503ecb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ABI llvm::RISCVABI::getTargetABI (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ABIName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvbaseinfo-cpp">RISCVBaseInfo.cpp</a>.</p>


<p>References <a href="#a11c6ee2d4e18ec16c570243cc285c7e9a8f2e55f34742f82eeaa55cbd79d44c0e">ABI_ILP32</a>, <a href="#a11c6ee2d4e18ec16c570243cc285c7e9a45fb6ea6c36157d00ae8a43dfedcc260">ABI_ILP32D</a>, <a href="#a11c6ee2d4e18ec16c570243cc285c7e9a9e062b1814798f2a29e2b28e74a36bc1">ABI_ILP32E</a>, <a href="#a11c6ee2d4e18ec16c570243cc285c7e9a8bd020c98ec18f175789493ef90eb66a">ABI_ILP32F</a>, <a href="#a11c6ee2d4e18ec16c570243cc285c7e9ae72b691ee57f47810281dffc97cbde06">ABI_LP64</a>, <a href="#a11c6ee2d4e18ec16c570243cc285c7e9af5a5e31fdfed05fc333fd92b488670f8">ABI_LP64D</a>, <a href="#a11c6ee2d4e18ec16c570243cc285c7e9adc7da95e1193beba354466672c1cdb38">ABI_LP64E</a>, <a href="#a11c6ee2d4e18ec16c570243cc285c7e9a8a401ce2fcb2329054c1e93cc57cb91e">ABI_LP64F</a>, <a href="#a11c6ee2d4e18ec16c570243cc285c7e9a8f595b6bd8825688b9ac7939a949c829">ABI_Unknown</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a> and <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>.</p>


<p>Referenced by <a href="#a28e75155ea06a5ad70d3a662be05e350">computeTargetABI</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#ada96d67c594bff6ca1c65fb281f82ca5">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::emitStartOfAsmFile</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvtargetmachine/#a3303f4528ff6f8538d036d62e3d25751">llvm::RISCVTargetMachine::getSubtargetImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvbaseinfo-cpp">RISCVBaseInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvbaseinfo-h">RISCVBaseInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
