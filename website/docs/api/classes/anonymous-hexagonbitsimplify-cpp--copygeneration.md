---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-hexagonbitsimplify-cpp-/copygeneration
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CopyGeneration` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{HexagonBitSimplify.cpp}::CopyGeneration { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/transformation">Transformation</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfa763a3bdbca3a29f00217b7349c950">CopyGeneration</a> (BitTracker &amp;bt, const HexagonInstrInfo &amp;hii, const HexagonRegisterInfo &amp;hri, MachineRegisterInfo &amp;mri)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add974c22e80e417ae81566ae9ed683a6">processBlock</a> (MachineBasicBlock &amp;B, const RegisterSet &amp;AVs) override</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b8cb111a75b0c8fef08ff7ba8285b21">findMatch</a> (const BitTracker::RegisterRef &amp;Inp, BitTracker::RegisterRef &amp;Out, const RegisterSet &amp;AVs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if there is a register in AVs that is identical to Inp. <a href="#a3b8cb111a75b0c8fef08ff7ba8285b21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo">HexagonInstrInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65aa5490a8bdca74f2b29dc5c0f09544">HII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo">HexagonRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41899fc52b64546ddc42de63763599ac">HRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16c0e5acc73835faed6225d2c91e1d5d">MRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker">BitTracker</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a764a62d608d7a38afe61a698d44c5551">BT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-hexagonbitsimplify-cpp-/registerset">RegisterSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34f89c16d876d4449b0f0cfd653acfb9">Forbidden</a></td>
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


<p>Definition at line 1532 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CopyGeneration() {#abfa763a3bdbca3a29f00217b7349c950}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{HexagonBitSimplify.cpp}::CopyGeneration::CopyGeneration (<a href="/web-llvm/docs/api/structs/llvm/bittracker">BitTracker</a> &amp; bt, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo">HexagonInstrInfo</a> &amp; hii, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo">HexagonRegisterInfo</a> &amp; hri, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; mri)</td>
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



<p>Definition at line 1534 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/transformation/#a567b376259e3121b97947982911e59e7">anonymous{HexagonBitSimplify.cpp}::Transformation::Transformation</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### processBlock() {#add974c22e80e417ae81566ae9ed683a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CopyGeneration::processBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagonbitsimplify-cpp-/registerset">RegisterSet</a> &amp; AVs)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1538 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonbitsimplify-cpp-/registerset/#a98ae15330522474ced863e56cb500a05">anonymous{HexagonBitSimplify.cpp}::RegisterSet::clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonbitsimplify-cpp-/registerset/#ae3d850c608f19809634e515ff3b3a691">anonymous{HexagonBitSimplify.cpp}::RegisterSet::find_first</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonbitsimplify-cpp-/registerset/#a2e9db2ebf86de743c9ce2e6ee265b98d">anonymous{HexagonBitSimplify.cpp}::RegisterSet::find_next</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/hexagonbitsimplify/#a8e3ebf47bfdde7c6ce8235ca71190e1b">anonymous{HexagonBitSimplify.cpp}::HexagonBitSimplify::getFinalVRegClass</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/hexagonbitsimplify/#ac6e875574acc456304c0d27912219536">anonymous{HexagonBitSimplify.cpp}::HexagonBitSimplify::getInstrDefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonbitsimplify-cpp-/registerset/#a91e9ba1c1c62c8534678e831d695ff41">anonymous{HexagonBitSimplify.cpp}::RegisterSet::insert</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/copypropagation/#a0d75dfd4e77664fa490154c96f9af205">anonymous{HexagonBitSimplify.cpp}::CopyPropagation::isCopyReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/constgeneration/#a1f84757fb15a43a0427b56953d6b3705">anonymous{HexagonBitSimplify.cpp}::ConstGeneration::isTfrConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3ad01fd9b01e9dde8bd3dc247afbfb7218">ML</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#acf8436e28b183b48eecf6b8564536c7aa7e62627fded515ebb9ff5d0ec9571d95">llvm::Hexagon::ps_sub_hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#acf8436e28b183b48eecf6b8564536c7aa4c96233dec1eedf779c37f230f6d8c10">llvm::Hexagon::ps_sub_lo</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registerref/#a83d460802fba9c074af90710d239f516">llvm::BitTracker::RegisterRef::Reg</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/hexagonbitsimplify/#ac3f3d9a5627dfe20e78c7c97be2f994f">anonymous{HexagonBitSimplify.cpp}::HexagonBitSimplify::replaceReg</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/registerref/#afd26bd676aebea77891d6d204dd804d5">llvm::BitTracker::RegisterRef::Sub</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### findMatch() {#a3b8cb111a75b0c8fef08ff7ba8285b21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CopyGeneration::findMatch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registerref">BitTracker::RegisterRef</a> &amp; Inp, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registerref">BitTracker::RegisterRef</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagonbitsimplify-cpp-/registerset">RegisterSet</a> &amp; AVs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check if there is a register in AVs that is identical to Inp.</p>


<p>If so, set Out to the found register. The output may be a pair Reg:Sub.</p>


<p>Definition at line 1541 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BT {#a764a62d608d7a38afe61a698d44c5551}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitTracker&amp; anonymous{HexagonBitSimplify.cpp}::CopyGeneration::BT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1547 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>

</div>
</div>

### Forbidden {#a34f89c16d876d4449b0f0cfd653acfb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterSet anonymous{HexagonBitSimplify.cpp}::CopyGeneration::Forbidden</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1548 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>

</div>
</div>

### HII {#a65aa5490a8bdca74f2b29dc5c0f09544}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const HexagonInstrInfo&amp; anonymous{HexagonBitSimplify.cpp}::CopyGeneration::HII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1544 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>

</div>
</div>

### HRI {#a41899fc52b64546ddc42de63763599ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const HexagonRegisterInfo&amp; anonymous{HexagonBitSimplify.cpp}::CopyGeneration::HRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1545 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>

</div>
</div>

### MRI {#a16c0e5acc73835faed6225d2c91e1d5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo&amp; anonymous{HexagonBitSimplify.cpp}::CopyGeneration::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1546 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
