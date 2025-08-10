---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-msp430elfobjectwriter-cpp-/msp430elfobjectwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MSP430ELFObjectWriter` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{MSP430ELFObjectWriter.cpp}::MSP430ELFObjectWriter { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcelfobjecttargetwriter">MCELFObjectTargetWriter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1edec5452fea7d8e986de1273495c5c">MSP430ELFObjectWriter</a> (uint8_t OSABI)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad24abda5344544728a0e88585d4b8e0b">~MSP430ELFObjectWriter</a> () override=default</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7381e62ae0123e1999ecc28e141a5431">getRelocType</a> (MCContext &amp;Ctx, const MCValue &amp;Target, const MCFixup &amp;Fixup, bool IsPCRel) const override</td>
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


<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/mctargetdesc/msp430elfobjectwriter-cpp">MSP430ELFObjectWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MSP430ELFObjectWriter() {#ae1edec5452fea7d8e986de1273495c5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MSP430ELFObjectWriter.cpp}::MSP430ELFObjectWriter::MSP430ELFObjectWriter (uint8_t OSABI)</td>
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



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/mctargetdesc/msp430elfobjectwriter-cpp">MSP430ELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcelfobjecttargetwriter/#ae6c6e76c9d8e0c912542fe4f8375e8ce">llvm::MCELFObjectTargetWriter::MCELFObjectTargetWriter</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MSP430ELFObjectWriter() {#ad24abda5344544728a0e88585d4b8e0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MSP430ELFObjectWriter.cpp}::MSP430ELFObjectWriter::~MSP430ELFObjectWriter ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/mctargetdesc/msp430elfobjectwriter-cpp">MSP430ELFObjectWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getRelocType() {#a7381e62ae0123e1999ecc28e141a5431}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{MSP430ELFObjectWriter.cpp}::MSP430ELFObjectWriter::getRelocType (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, bool IsPCRel)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/mctargetdesc/msp430elfobjectwriter-cpp">MSP430ELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msp430/#a6d36616195e58eda9d8157747cf40ee5a244a1ce74fb936deb3b07f67c86aeeeb">llvm::MSP430::fixup_10_pcrel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msp430/#a6d36616195e58eda9d8157747cf40ee5a75df8e867cf99e2c8110846560838220">llvm::MSP430::fixup_16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msp430/#a6d36616195e58eda9d8157747cf40ee5a14dd16bbf13af28134846038349bb09d">llvm::MSP430::fixup_16_byte</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msp430/#a6d36616195e58eda9d8157747cf40ee5ac633c98a5a481da5cb1d6d4e92aedefa">llvm::MSP430::fixup_16_pcrel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msp430/#a6d36616195e58eda9d8157747cf40ee5a348c46fad284bac6fb3bcdc12c7f3db1">llvm::MSP430::fixup_16_pcrel_byte</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msp430/#a6d36616195e58eda9d8157747cf40ee5a85caa2c9c222748d46daea8246df3566">llvm::MSP430::fixup_2x_pcrel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msp430/#a6d36616195e58eda9d8157747cf40ee5a0481bf06e27c83e66ce41bc7c4e78dab">llvm::MSP430::fixup_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msp430/#a6d36616195e58eda9d8157747cf40ee5a547687c75a02113ad079bda11a3ca30e">llvm::MSP430::fixup_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msp430/#a6d36616195e58eda9d8157747cf40ee5a649a821332d427d9883bbbb9916d0abf">llvm::MSP430::fixup_rl_pcrel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msp430/#a6d36616195e58eda9d8157747cf40ee5afc24557fcd7cd9a85274ba3a488acffd">llvm::MSP430::fixup_sym_diff</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a4aee2a3e203379bbb0c9639d4ef31b6e">llvm::FK_Data_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/mctargetdesc/msp430elfobjectwriter-cpp">MSP430ELFObjectWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
