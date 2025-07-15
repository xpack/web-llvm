---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-hexagonmctargetdesc-cpp-/hexagonmcinstranalysis
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `HexagonMCInstrAnalysis` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{HexagonMCTargetDesc.cpp}::HexagonMCInstrAnalysis { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis">MCInstrAnalysis</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a554432bd6d3bd40c1347e6f7cca80e67">HexagonMCInstrAnalysis</a> (MCInstrInfo const *Info)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2affb39ac7e9de50b831b688de5aedb">isUnconditionalBranch</a> (MCInst const &amp;Inst) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98bf833fadfc0be66c16e8a1cd8cfe71">isConditionalBranch</a> (MCInst const &amp;Inst) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc004e2576e85b8ef606c566bda305e3">evaluateBranch</a> (MCInst const &amp;Inst, uint64_t Addr, uint64_t Size, uint64_t &amp;Target) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a branch instruction try to get the address the branch targets. <a href="#abc004e2576e85b8ef606c566bda305e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 706 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### HexagonMCInstrAnalysis() {#a554432bd6d3bd40c1347e6f7cca80e67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{HexagonMCTargetDesc.cpp}::HexagonMCInstrAnalysis::HexagonMCInstrAnalysis (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * Info)</td>
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



<p>Definition at line 708 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis/#ad26d74f7a49154af0b73be4e105d361b">llvm::MCInstrAnalysis::Info</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis/#ad3b05756e9ba8f98ac91be359f4ea275">llvm::MCInstrAnalysis::MCInstrAnalysis</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#a40aeb85e7cc10164273a5372093b2d20">createHexagonMCInstrAnalysis</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### evaluateBranch() {#abc004e2576e85b8ef606c566bda305e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{HexagonMCTargetDesc.cpp}::HexagonMCInstrAnalysis::evaluateBranch (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Inst, uint64_t Addr, uint64_t Size, uint64_t &amp; Target)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a branch instruction try to get the address the branch targets.</p>


<p>Return true on success, and the address in Target.</p>


<p>Definition at line 720 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#aea78a68d4baf2fd4614a3be3a14dd548">llvm::HexagonMCInstrInfo::getExtendableOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis/#ad26d74f7a49154af0b73be4e105d361b">llvm::MCInstrAnalysis::Info</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis/#a123e3dc956b0dad28841670ee6bd84e4">llvm::MCInstrAnalysis::isCall</a>, <a href="#a98bf833fadfc0be66c16e8a1cd8cfe71">isConditionalBranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a8c525c01df0d371a390190574d22bccc">llvm::HexagonMCInstrInfo::isExtendable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp/#a35875e97a48f3ef88fe48e8b81ad3b53">isUnconditionalBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis/#aaec4eb5c2964764409c3ecc82bb90f57">llvm::MCInstrAnalysis::Target</a>.</p>

</div>
</div>

### isConditionalBranch() {#a98bf833fadfc0be66c16e8a1cd8cfe71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{HexagonMCTargetDesc.cpp}::HexagonMCInstrAnalysis::isConditionalBranch (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Inst)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 715 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis/#aabfb496421d3e86668396b0b97d5a431">llvm::MCInstrAnalysis::isConditionalBranch</a>.</p>


<p>Referenced by <a href="#abc004e2576e85b8ef606c566bda305e3">evaluateBranch</a>.</p>

</div>
</div>

### isUnconditionalBranch() {#af2affb39ac7e9de50b831b688de5aedb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{HexagonMCTargetDesc.cpp}::HexagonMCInstrAnalysis::isUnconditionalBranch (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Inst)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 710 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis/#a4e5be94e4462c129c3b5e4ba2af1c2bc">llvm::MCInstrAnalysis::isUnconditionalBranch</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
