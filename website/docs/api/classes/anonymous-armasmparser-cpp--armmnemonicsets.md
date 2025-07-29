---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-armasmparser-cpp-/armmnemonicsets
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ARMMnemonicSets` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{ARMAsmParser.cpp}::ARMMnemonicSets { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfcdbfc29506bc4cd2ff3d2f1226636b">ARMMnemonicSets</a> (const MCSubtargetInfo &amp;STI)</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ab7539d76cfca5b4cbcabaf48d20979">isCDEInstr</a> (StringRef Mnemonic)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true iff a given mnemonic is a CDE instruction. <a href="#a2ab7539d76cfca5b4cbcabaf48d20979">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e2deb9763940058e9a33e4bea668968">isVPTPredicableCDEInstr</a> (StringRef Mnemonic)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true iff a given mnemonic is a VPT-predicable CDE instruction (possibly with a predication suffix "e" or "t") <a href="#a0e2deb9763940058e9a33e4bea668968">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a361ea7963e2fddb89e0eef0d164ef55e">isITPredicableCDEInstr</a> (StringRef Mnemonic)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true iff a given mnemonic is an IT-predicable CDE instruction (possibly with a condition suffix) <a href="#a361ea7963e2fddb89e0eef0d164ef55e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac90a4bbed7a48888b21439ce16b55541">isCDEDualRegInstr</a> (StringRef Mnemonic)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true iff a given mnemonic is an integer CDE instruction with dual-register destination. <a href="#ac90a4bbed7a48888b21439ce16b55541">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringset">StringSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc9d11ca4b00e1f265a7cbad30c35a97">CDE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringset">StringSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d19d5eeef14e3c4118d461ff2f62b3c">CDEWithVPTSuffix</a></td>
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


<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/asmparser/armasmparser-cpp">ARMAsmParser.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ARMMnemonicSets() {#abfcdbfc29506bc4cd2ff3d2f1226636b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ARMAsmParser.cpp}::ARMMnemonicSets::ARMMnemonicSets (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/asmparser/armasmparser-cpp">ARMAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isCDEDualRegInstr() {#ac90a4bbed7a48888b21439ce16b55541}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ARMAsmParser.cpp}::ARMMnemonicSets::isCDEDualRegInstr (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Mnemonic)</td>
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

<p>Return true iff a given mnemonic is an integer CDE instruction with dual-register destination.</p>

<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/asmparser/armasmparser-cpp">ARMAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>.</p>

</div>
</div>

### isCDEInstr() {#a2ab7539d76cfca5b4cbcabaf48d20979}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ARMAsmParser.cpp}::ARMMnemonicSets::isCDEInstr (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Mnemonic)</td>
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

<p>Returns true iff a given mnemonic is a CDE instruction.</p>

<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/asmparser/armasmparser-cpp">ARMAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>.</p>

</div>
</div>

### isITPredicableCDEInstr() {#a361ea7963e2fddb89e0eef0d164ef55e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ARMAsmParser.cpp}::ARMMnemonicSets::isITPredicableCDEInstr (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Mnemonic)</td>
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

<p>Returns true iff a given mnemonic is an IT-predicable CDE instruction (possibly with a condition suffix)</p>

<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/asmparser/armasmparser-cpp">ARMAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>.</p>

</div>
</div>

### isVPTPredicableCDEInstr() {#a0e2deb9763940058e9a33e4bea668968}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ARMAsmParser.cpp}::ARMMnemonicSets::isVPTPredicableCDEInstr (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Mnemonic)</td>
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

<p>Returns true iff a given mnemonic is a VPT-predicable CDE instruction (possibly with a predication suffix "e" or "t")</p>

<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/asmparser/armasmparser-cpp">ARMAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CDE {#acc9d11ca4b00e1f265a7cbad30c35a97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSet anonymous{ARMAsmParser.cpp}::ARMMnemonicSets::CDE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/asmparser/armasmparser-cpp">ARMAsmParser.cpp</a>.</p>

</div>
</div>

### CDEWithVPTSuffix {#a3d19d5eeef14e3c4118d461ff2f62b3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSet anonymous{ARMAsmParser.cpp}::ARMMnemonicSets::CDEWithVPTSuffix</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/asmparser/armasmparser-cpp">ARMAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/asmparser/armasmparser-cpp">ARMAsmParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
