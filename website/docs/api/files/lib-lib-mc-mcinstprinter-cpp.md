---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/mc/mcinstprinter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `MCInstPrinter.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">llvm/MC/MCInstPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfo-h">llvm/MC/MCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">llvm/MC/MCInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrinfo-h">llvm/MC/MCInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">llvm/MC/MCRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">llvm/MC/MCSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/format-h">llvm/Support/Format.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cinttypes&gt;
#include &lt;cstdint&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad70fb95e1855cf69dfefcf98e2d5e8b">matchAliasCondition</a> (const MCInst &amp;MI, const MCSubtargetInfo *STI, const MCRegisterInfo &amp;MRI, unsigned &amp;OpIdx, const AliasMatchingData &amp;M, const AliasPatternCond &amp;C, bool &amp;OrPredicateResult)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a84d311db99342342801bebaddc8fd4">needsLeadingZero</a> (uint64_t Value)</td>
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

## Functions

### matchAliasCondition() {#aad70fb95e1855cf69dfefcf98e2d5e8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool matchAliasCondition (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp; MRI, unsigned &amp; OpIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aliasmatchingdata">AliasMatchingData</a> &amp; M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aliaspatterncond">AliasPatternCond</a> &amp; C, bool &amp; OrPredicateResult)</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcinstprinter-cpp">MCInstPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a53afee158973a8af8c60263ddb5b2d07">llvm::MCSubtargetInfo::getFeatureBits</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a4509c43893edc940979f690c468664c1">llvm::MCOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a94abf618eb8001b802910ab872a7d1d9">llvm::MCOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a5f639fdcd3fc673fcbdb47f2e88b2b41">llvm::MCOperand::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a7a8c7eea0aa4890f25a4b83e1f0a0b6f">llvm::MCOperand::isReg</a>, <a href="/web-llvm/docs/api/structs/llvm/aliaspatterncond/#a7ab8001d03aa55f6d918d77e9f857ad4ac2764bc8aea0a09b23bb25af72043ee1">llvm::AliasPatternCond::K_Custom</a>, <a href="/web-llvm/docs/api/structs/llvm/aliaspatterncond/#a7ab8001d03aa55f6d918d77e9f857ad4a5812a60d5c8bb0d46075dacec774e62a">llvm::AliasPatternCond::K_EndOrFeatures</a>, <a href="/web-llvm/docs/api/structs/llvm/aliaspatterncond/#a7ab8001d03aa55f6d918d77e9f857ad4acdd3688fd1049a863d20a3ff063bad94">llvm::AliasPatternCond::K_Feature</a>, <a href="/web-llvm/docs/api/structs/llvm/aliaspatterncond/#a7ab8001d03aa55f6d918d77e9f857ad4ac2c7d224fb90f730e59b259acc6a7529">llvm::AliasPatternCond::K_Ignore</a>, <a href="/web-llvm/docs/api/structs/llvm/aliaspatterncond/#a7ab8001d03aa55f6d918d77e9f857ad4ab6b82747a5c2211d56aaf238b2829413">llvm::AliasPatternCond::K_Imm</a>, <a href="/web-llvm/docs/api/structs/llvm/aliaspatterncond/#a7ab8001d03aa55f6d918d77e9f857ad4a24e1bc1677c49c53174fb1c523f5b4cf">llvm::AliasPatternCond::K_NegFeature</a>, <a href="/web-llvm/docs/api/structs/llvm/aliaspatterncond/#a7ab8001d03aa55f6d918d77e9f857ad4abda9365f1ae3b058efa5ec7b56e039cc">llvm::AliasPatternCond::K_OrFeature</a>, <a href="/web-llvm/docs/api/structs/llvm/aliaspatterncond/#a7ab8001d03aa55f6d918d77e9f857ad4a78dbcc8c7fa75bca7cab094cff219676">llvm::AliasPatternCond::K_OrNegFeature</a>, <a href="/web-llvm/docs/api/structs/llvm/aliaspatterncond/#a7ab8001d03aa55f6d918d77e9f857ad4a8a5385e573c46211979b1fa1d77089f9">llvm::AliasPatternCond::K_Reg</a>, <a href="/web-llvm/docs/api/structs/llvm/aliaspatterncond/#a7ab8001d03aa55f6d918d77e9f857ad4a66819b05997281299f9b61934f5900e6">llvm::AliasPatternCond::K_RegClass</a>, <a href="/web-llvm/docs/api/structs/llvm/aliaspatterncond/#a7ab8001d03aa55f6d918d77e9f857ad4a0eab41855d87b6fb3f02b1d075c19837">llvm::AliasPatternCond::K_TiedReg</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/featurebitset/#a4fce0696a3465a5f24d788288f23f6bf">llvm::FeatureBitset::test</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp/#a106e32122c569cdb42ddf61ecbb0aad1">test</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#ae9677047c398a916ab4a5a6fabeb36e7">llvm::MCInstPrinter::matchAliasPatterns</a>.</p>

</div>
</div>

### needsLeadingZero() {#a3a84d311db99342342801bebaddc8fd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool needsLeadingZero (uint64_t Value)</td>
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



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcinstprinter-cpp">MCInstPrinter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a152eff13caf242abc99d47f5a197a4d9">llvm::MCInstPrinter::formatHex</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#ae984d0ef2a117d681fee8e563786c9b8">llvm::MCInstPrinter::formatHex</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
