---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/avr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `AVR` Namespace Reference

<p>Contains the <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> backend. <a href="#details">More...</a></p>

## Definition

<div class="doxyDefinition">
namespace llvm::AVR { ... }
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/avr/fixups">fixups</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AddressSpace { <a href="#ab7fa9bb927a227efb1a38db426c5aaf6">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An integer that identifies all of the supported <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> address spaces. <a href="#ab7fa9bb927a227efb1a38db426c5aaf6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Fixups { <a href="#ae093893769f0a31accd70fbf3fd419b1">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of supported fixups. <a href="#ae093893769f0a31accd70fbf3fd419b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaef9228fcde19f54da2a08e85cbb25af">isProgramMemoryAddress</a> (T *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if a given type is a pointer to program memory. <a href="#aaef9228fcde19f54da2a08e85cbb25af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ab7fa9bb927a227efb1a38db426c5aaf6">AddressSpace</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a72f5caee7436dfc130b92f2545cf727b">getAddressSpace</a> (T *V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c128ac074d92126c8983e21aadbd9e4">isProgramMemoryAccess</a> (MemSDNode const *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa04c08d1a30024d2dc3de761ff3167d">getProgramMemoryBank</a> (MemSDNode const *N)</td>
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

## Description {#details}

<p>Contains the <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> backend.</p>

<div class="doxySectionDef">

## Enumerations

### AddressSpace {#ab7fa9bb927a227efb1a38db426c5aaf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AVR::AddressSpace </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An integer that identifies all of the supported <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> address spaces.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DataMemory<a id="ab7fa9bb927a227efb1a38db426c5aaf6a15965363d5b3196779a2758b5f4ea777"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ProgramMemory<a id="ab7fa9bb927a227efb1a38db426c5aaf6a467a127a5b333ac481886bc438195f39"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ProgramMemory1<a id="ab7fa9bb927a227efb1a38db426c5aaf6a7f665801fc3404179d216811ff0e078e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ProgramMemory2<a id="ab7fa9bb927a227efb1a38db426c5aaf6a50e0252b5e7ef8f8436a17833c68e129"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ProgramMemory3<a id="ab7fa9bb927a227efb1a38db426c5aaf6afc31612b630161a10ae6136e5269a838"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ProgramMemory4<a id="ab7fa9bb927a227efb1a38db426c5aaf6a7c223f9bbe2b2c14ae004a7881ce50b0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ProgramMemory5<a id="ab7fa9bb927a227efb1a38db426c5aaf6ab548472c1931ea8aab10863b9976bbec"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NumAddrSpaces<a id="ab7fa9bb927a227efb1a38db426c5aaf6a3fdfc200e0c408e424e4988735b1de58"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avr-h">AVR.h</a>.</p>

</div>
</div>

### Fixups {#ae093893769f0a31accd70fbf3fd419b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AVR::Fixups </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of supported fixups.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_32<a id="ae093893769f0a31accd70fbf3fd419b1a500fa30f51cc74e5a90492f6b302334a"></a></td>
<td class="doxyEnumItemDescription">A 32-bit <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> fixup (= FirstTargetFixupKind)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_7_pcrel<a id="ae093893769f0a31accd70fbf3fd419b1a60e6a283e3c8cbea62c15d290b3b7230"></a></td>
<td class="doxyEnumItemDescription">A 7-bit PC-relative fixup for the family of conditional branches which take 7-bit targets (BRNE,BRGT,etc)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_13_pcrel<a id="ae093893769f0a31accd70fbf3fd419b1aef7dfebd31b781d8947b5ee86ea8344b"></a></td>
<td class="doxyEnumItemDescription">A 12-bit PC-relative fixup for the family of branches which take 12-bit targets (RJMP,RCALL,etc)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_16<a id="ae093893769f0a31accd70fbf3fd419b1a1988574074630219dd0822e790327356"></a></td>
<td class="doxyEnumItemDescription">A 16-bit address</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_16_pm<a id="ae093893769f0a31accd70fbf3fd419b1a0a7ad8e9592283440f485e0c10e944f2"></a></td>
<td class="doxyEnumItemDescription">A 16-bit program memory address</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_ldi<a id="ae093893769f0a31accd70fbf3fd419b1a6b7175a9e13966bf2bebe7d0f196b462"></a></td>
<td class="doxyEnumItemDescription">Replaces the 8-bit immediate with another value</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_lo8_ldi<a id="ae093893769f0a31accd70fbf3fd419b1a72001e129a73846ac51da1bc606f8c2d"></a></td>
<td class="doxyEnumItemDescription">Replaces the immediate operand of a 16-bit <span class="doxyComputerOutput">Rd, K</span> instruction with the lower 8 bits of a 16-bit value (bits 0-7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_hi8_ldi<a id="ae093893769f0a31accd70fbf3fd419b1a78ac987d603e1af3517bd49dacc5ee34"></a></td>
<td class="doxyEnumItemDescription">Replaces the immediate operand of a 16-bit <span class="doxyComputerOutput">Rd, K</span> instruction with the upper 8 bits of a 16-bit value (bits 8-15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_hh8_ldi<a id="ae093893769f0a31accd70fbf3fd419b1a382b86a3e3c868e6ddd9475944d8d1cd"></a></td>
<td class="doxyEnumItemDescription">Replaces the immediate operand of a 16-bit <span class="doxyComputerOutput">Rd, K</span> instruction with the upper 8 bits of a 24-bit value (bits 16-23)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_ms8_ldi<a id="ae093893769f0a31accd70fbf3fd419b1a5a57de6d17ac1d7fe855d0bdf7420b7e"></a></td>
<td class="doxyEnumItemDescription">Replaces the immediate operand of a 16-bit <span class="doxyComputerOutput">Rd, K</span> instruction with the upper 8 bits of a 32-bit value (bits 24-31)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_lo8_ldi_neg<a id="ae093893769f0a31accd70fbf3fd419b1a58d3467e8ce0a23f1b6085534f4abf28"></a></td>
<td class="doxyEnumItemDescription">Replaces the immediate operand of a 16-bit <span class="doxyComputerOutput">Rd, K</span> instruction with the lower 8 bits of a negated 16-bit value (bits 0-7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_hi8_ldi_neg<a id="ae093893769f0a31accd70fbf3fd419b1aefc20853a2c98d2ef8a07255a98a6a22"></a></td>
<td class="doxyEnumItemDescription">Replaces the immediate operand of a 16-bit <span class="doxyComputerOutput">Rd, K</span> instruction with the upper 8 bits of a negated 16-bit value (bits 8-15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_hh8_ldi_neg<a id="ae093893769f0a31accd70fbf3fd419b1a99d632ff5fa83e7b6ad4bf40eb108cbb"></a></td>
<td class="doxyEnumItemDescription">Replaces the immediate operand of a 16-bit <span class="doxyComputerOutput">Rd, K</span> instruction with the upper 8 bits of a negated 24-bit value (bits 16-23)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_ms8_ldi_neg<a id="ae093893769f0a31accd70fbf3fd419b1a46b76675cc30a160bdc1efdfa54c26f2"></a></td>
<td class="doxyEnumItemDescription">Replaces the immediate operand of a 16-bit <span class="doxyComputerOutput">Rd, K</span> instruction with the upper 8 bits of a negated 32-bit value (bits 24-31)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_lo8_ldi_pm<a id="ae093893769f0a31accd70fbf3fd419b1a86089f48a39009fba6b797d64a5c3e38"></a></td>
<td class="doxyEnumItemDescription">Replaces the immediate operand of a 16-bit <span class="doxyComputerOutput">Rd, K</span> instruction with the lower 8 bits of a 16-bit program memory address value (bits 0-7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_hi8_ldi_pm<a id="ae093893769f0a31accd70fbf3fd419b1ab13e48e1103a86880bd207573da528e9"></a></td>
<td class="doxyEnumItemDescription">Replaces the immediate operand of a 16-bit <span class="doxyComputerOutput">Rd, K</span> instruction with the upper 8 bits of a 16-bit program memory address value (bits 8-15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_hh8_ldi_pm<a id="ae093893769f0a31accd70fbf3fd419b1a9ee8f8e04076fa4bb138a15c7c28691f"></a></td>
<td class="doxyEnumItemDescription">Replaces the immediate operand of a 16-bit <span class="doxyComputerOutput">Rd, K</span> instruction with the upper 8 bits of a 24-bit program memory address value (bits 16-23)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_lo8_ldi_pm_neg<a id="ae093893769f0a31accd70fbf3fd419b1aa45c22f2c30f421e4b2efbefde64a2b8"></a></td>
<td class="doxyEnumItemDescription">Replaces the immediate operand of a 16-bit <span class="doxyComputerOutput">Rd, K</span> instruction with the lower 8 bits of a negated 16-bit program memory address value (bits 0-7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_hi8_ldi_pm_neg<a id="ae093893769f0a31accd70fbf3fd419b1a766028df6cd5759254edcfea42e8296d"></a></td>
<td class="doxyEnumItemDescription">Replaces the immediate operand of a 16-bit <span class="doxyComputerOutput">Rd, K</span> instruction with the upper 8 bits of a negated 16-bit program memory address value (bits 8-15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_hh8_ldi_pm_neg<a id="ae093893769f0a31accd70fbf3fd419b1ac8e2243f3ba6ba72cdea9d6e5d86a504"></a></td>
<td class="doxyEnumItemDescription">Replaces the immediate operand of a 16-bit <span class="doxyComputerOutput">Rd, K</span> instruction with the upper 8 bits of a negated 24-bit program memory address value (bits 16-23)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_call<a id="ae093893769f0a31accd70fbf3fd419b1a223843ea9d717c21dd80bf8124e9a16e"></a></td>
<td class="doxyEnumItemDescription">A 22-bit fixup for the target of a <span class="doxyComputerOutput">CALL k</span> or <span class="doxyComputerOutput">JMP k</span> instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_6<a id="ae093893769f0a31accd70fbf3fd419b1afdbb8a9b4206897c419c5a93db879478"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_6_adiw<a id="ae093893769f0a31accd70fbf3fd419b1a5a35c5fe666b4d94dd0fec1399e3e46f"></a></td>
<td class="doxyEnumItemDescription">A symbol+addr fixup for the `LDD &lt;x&gt;+&lt;n&gt;, &lt;r&gt;" family of instructions</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_lo8_ldi_gs<a id="ae093893769f0a31accd70fbf3fd419b1aa925266a218e48fd76747c51bd83615d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_hi8_ldi_gs<a id="ae093893769f0a31accd70fbf3fd419b1a1edd771e4ceba008a0aa03ca9aee683f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_8<a id="ae093893769f0a31accd70fbf3fd419b1acdd0f7dd8821f18836309748e0502b09"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_8_lo8<a id="ae093893769f0a31accd70fbf3fd419b1aa2d2fe99786c5857ad6ea10e4d3cd980"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_8_hi8<a id="ae093893769f0a31accd70fbf3fd419b1ac41084f0958f15695b00ec1f6421d5f1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_8_hlo8<a id="ae093893769f0a31accd70fbf3fd419b1a5c874e004c307eb67afd5ea9a301f9c3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_diff8<a id="ae093893769f0a31accd70fbf3fd419b1a5a2eeb2fb2811f245cbf30d2c48abc1c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_diff16<a id="ae093893769f0a31accd70fbf3fd419b1a085e8b08c76da2d683bd83bd15f6f6be"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_diff32<a id="ae093893769f0a31accd70fbf3fd419b1aebac1fc0b48d2ccc07a425d70025d74f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_lds_sts_16<a id="ae093893769f0a31accd70fbf3fd419b1afffc03deb9be0873e82f17212493795e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_port6<a id="ae093893769f0a31accd70fbf3fd419b1a8bfdf34483b345245854a23f35888527"></a></td>
<td class="doxyEnumItemDescription">A 6-bit port address</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_port5<a id="ae093893769f0a31accd70fbf3fd419b1aa417f149a7d5fd39ca8e72197c12b4d8"></a></td>
<td class="doxyEnumItemDescription">A 5-bit port address</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LastTargetFixupKind<a id="ae093893769f0a31accd70fbf3fd419b1a3a1fa3eef584b35a695f93fb7e85a3a7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NumTargetFixupKinds<a id="ae093893769f0a31accd70fbf3fd419b1a6499d178b9964b2fc7b26cd8ebb82d24"></a></td>
<td class="doxyEnumItemDescription"> (= LastTargetFixupKind - FirstTargetFixupKind)</td>
</tr>

</table>
</dd>
</dl>


<p>Although most of the current fixup types reflect a unique relocation one can have multiple fixup types for a given relocation and thus need to be uniquely named.</p>



:::info
<p>This table <em>must</em> be in the same order of <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo">MCFixupKindInfo</a> Infos[<a href="#ae093893769f0a31accd70fbf3fd419b1a6499d178b9964b2fc7b26cd8ebb82d24">AVR::NumTargetFixupKinds</a>] in <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-cpp">AVRAsmBackend.cpp</a></span>.</p>
:::


<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrfixupkinds-h">AVRFixupKinds.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### getAddressSpace() {#a72f5caee7436dfc130b92f2545cf727b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AddressSpace llvm::AVR::getAddressSpace (T * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avr-h">AVR.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ab7fa9bb927a227efb1a38db426c5aaf6a3fdfc200e0c408e424e4988735b1de58">NumAddrSpaces</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#aaa04c08d1a30024d2dc3de761ff3167d">getProgramMemoryBank</a> and <a href="/web-llvm/docs/api/classes/llvm/avrtargetobjectfile/#a2ac5016664f09fbfd8b97a954fccd664">llvm::AVRTargetObjectFile::SelectSectionForGlobal</a>.</p>

</div>
</div>

### getProgramMemoryBank() {#aaa04c08d1a30024d2dc3de761ff3167d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AVR::getProgramMemoryBank (<a href="/web-llvm/docs/api/classes/llvm/memsdnode">MemSDNode</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * N)</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avr-h">AVR.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a72f5caee7436dfc130b92f2545cf727b">getAddressSpace</a>, <a href="#aaef9228fcde19f54da2a08e85cbb25af">isProgramMemoryAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#ab7fa9bb927a227efb1a38db426c5aaf6a467a127a5b333ac481886bc438195f39">ProgramMemory</a> and <a href="#ab7fa9bb927a227efb1a38db426c5aaf6ab548472c1931ea8aab10863b9976bbec">ProgramMemory5</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avriseldagtodag-cpp/#a566a922274e3694fe81033c9abce79a2">AVRDAGToDAGISel::select&lt; ISD::LOAD &gt;</a>.</p>

</div>
</div>

### isProgramMemoryAccess() {#a2c128ac074d92126c8983e21aadbd9e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AVR::isProgramMemoryAccess (<a href="/web-llvm/docs/api/classes/llvm/memsdnode">MemSDNode</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * N)</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avr-h">AVR.h</a>.</p>


<p>References <a href="#aaef9228fcde19f54da2a08e85cbb25af">isProgramMemoryAddress</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avriseldagtodag-cpp/#a566a922274e3694fe81033c9abce79a2">AVRDAGToDAGISel::select&lt; ISD::LOAD &gt;</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#af736164122434ca6fc3a5ac01ef739fd">llvm::AVRTargetLowering::getPostIndexedAddressParts</a> and <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#a2639a31c0222a806fa852121053d535c">llvm::AVRTargetLowering::getPreIndexedAddressParts</a>.</p>

</div>
</div>

### isProgramMemoryAddress() {#aaef9228fcde19f54da2a08e85cbb25af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AVR::isProgramMemoryAddress (T * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks if a given type is a pointer to program memory.</p>

<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avr-h">AVR.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ab7fa9bb927a227efb1a38db426c5aaf6a467a127a5b333ac481886bc438195f39">ProgramMemory</a>, <a href="#ab7fa9bb927a227efb1a38db426c5aaf6a7f665801fc3404179d216811ff0e078e">ProgramMemory1</a>, <a href="#ab7fa9bb927a227efb1a38db426c5aaf6a50e0252b5e7ef8f8436a17833c68e129">ProgramMemory2</a>, <a href="#ab7fa9bb927a227efb1a38db426c5aaf6afc31612b630161a10ae6136e5269a838">ProgramMemory3</a>, <a href="#ab7fa9bb927a227efb1a38db426c5aaf6a7c223f9bbe2b2c14ae004a7881ce50b0">ProgramMemory4</a>, <a href="#ab7fa9bb927a227efb1a38db426c5aaf6ab548472c1931ea8aab10863b9976bbec">ProgramMemory5</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#aaa04c08d1a30024d2dc3de761ff3167d">getProgramMemoryBank</a>, <a href="#a2c128ac074d92126c8983e21aadbd9e4">isProgramMemoryAccess</a> and <a href="/web-llvm/docs/api/classes/llvm/avrtargetobjectfile/#a2ac5016664f09fbfd8b97a954fccd664">llvm::AVRTargetObjectFile::SelectSectionForGlobal</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avr-h">AVR.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrfixupkinds-h">AVRFixupKinds.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
