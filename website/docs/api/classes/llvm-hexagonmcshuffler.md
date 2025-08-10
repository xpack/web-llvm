---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/hexagonmcshuffler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `HexagonMCShuffler` Class



## Declaration

<div class="doxyDeclaration">
class llvm::HexagonMCShuffler { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcshuffler-h">Target/Hexagon/MCTargetDesc/HexagonMCShuffler.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler">HexagonShuffler</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab828145ae3ee983f06d2efd4ad7a21cb">HexagonMCShuffler</a> (MCContext &amp;Context, bool ReportErrors, MCInstrInfo const &amp;MCII, MCSubtargetInfo const &amp;STI, MCInst &amp;MCB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09dfd3467401684077720391d3a69ea0">HexagonMCShuffler</a> (MCContext &amp;Context, bool ReportErrors, MCInstrInfo const &amp;MCII, MCSubtargetInfo const &amp;STI, MCInst &amp;MCB, MCInst const &amp;AddMI, bool InsertAtFront)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7107b9902252656400f8760c3d657dd">copyTo</a> (MCInst &amp;MCB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7acb90dc32e0d7297b6264ab4d25c348">reshuffleTo</a> (MCInst &amp;MCB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97c89bae6a43b89e9057a37a8105880b">init</a> (MCInst &amp;MCB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3a032a9dd4be4b67bbd18178fb5c143">init</a> (MCInst &amp;MCB, MCInst const &amp;AddMI, bool InsertAtFront)</td>
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


<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcshuffler-h">HexagonMCShuffler.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### HexagonMCShuffler() {#ab828145ae3ee983f06d2efd4ad7a21cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::HexagonMCShuffler::HexagonMCShuffler (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Context, bool ReportErrors, <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MCB)</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcshuffler-h">HexagonMCShuffler.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#a04e7bcc848338f170b3227b216aec616">llvm::HexagonShuffler::Context</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#a1bea60acdfd80dd427535cbe669f568b">llvm::HexagonShuffler::HexagonShuffler</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#ac5472a417eff2e300c9e8f08bdee1297">llvm::HexagonShuffler::MCII</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#a8ec546f90ddb525b6500986e6ac27239">llvm::HexagonShuffler::ReportErrors</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#ab93a83f6136cca7d527d21196676ccc4">llvm::HexagonShuffler::STI</a>.</p>

</div>
</div>

### HexagonMCShuffler() {#a09dfd3467401684077720391d3a69ea0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::HexagonMCShuffler::HexagonMCShuffler (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Context, bool ReportErrors, <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MCB, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; AddMI, bool InsertAtFront)</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcshuffler-h">HexagonMCShuffler.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#a04e7bcc848338f170b3227b216aec616">llvm::HexagonShuffler::Context</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#a1bea60acdfd80dd427535cbe669f568b">llvm::HexagonShuffler::HexagonShuffler</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#ac5472a417eff2e300c9e8f08bdee1297">llvm::HexagonShuffler::MCII</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#a8ec546f90ddb525b6500986e6ac27239">llvm::HexagonShuffler::ReportErrors</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#ab93a83f6136cca7d527d21196676ccc4">llvm::HexagonShuffler::STI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### copyTo() {#ad7107b9902252656400f8760c3d657dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonMCShuffler::copyTo (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MCB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcshuffler-h">HexagonMCShuffler.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcshuffler-cpp">HexagonMCShuffler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#aa287ac3a1615e464dacff4aba682d34f">llvm::HexagonShuffler::BundleFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aecd4e9369c30b88c8e528489f69e0c8e">llvm::MCInst::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ae86bea5bf6fe3c0a2a9f09f5fdc4a310">llvm::MCOperand::createInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#afb6e75791bd7cfb1b0b26c7a5cc20527">llvm::HexagonShuffler::Loc</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a580e2a6e8a248c5a4a814c03186e9241">llvm::MCInst::setLoc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a7e6dfe0eaf6d1b1720be0390c764cdbd">llvm::HexagonMCShuffle</a> and <a href="#a7acb90dc32e0d7297b6264ab4d25c348">reshuffleTo</a>.</p>

</div>
</div>

### reshuffleTo() {#a7acb90dc32e0d7297b6264ab4d25c348}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonMCShuffler::reshuffleTo (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MCB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcshuffler-h">HexagonMCShuffler.h</a>, definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcshuffler-cpp">HexagonMCShuffler.cpp</a>.</p>


<p>References <a href="#ad7107b9902252656400f8760c3d657dd">copyTo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ab8aa6b74c6bb82576347afb756807f20">llvm::MCInst::dump</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#a572425344ad3846264384af43858a5e1">llvm::HexagonShuffler::shuffle</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a2e62b46a3eb52ccf356ac99f8ebb3c06">llvm::HexagonMCShuffle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59e0da5b8f32f10d8fd69cb090730ecb">llvm::HexagonMCShuffle</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7e6dfe0eaf6d1b1720be0390c764cdbd">llvm::HexagonMCShuffle</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### init() {#a97c89bae6a43b89e9057a37a8105880b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonMCShuffler::init (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MCB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcshuffler-h">HexagonMCShuffler.h</a>, definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcshuffler-cpp">HexagonMCShuffler.cpp</a>.</p>

</div>
</div>

### init() {#ac3a032a9dd4be4b67bbd18178fb5c143}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonMCShuffler::init (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MCB, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; AddMI, bool InsertAtFront)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcshuffler-h">HexagonMCShuffler.h</a>, definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcshuffler-cpp">HexagonMCShuffler.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcshuffler-cpp">HexagonMCShuffler.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcshuffler-h">HexagonMCShuffler.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
