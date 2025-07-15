---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/aarch64ii
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `AArch64II` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::AArch64II { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TOF { <a href="#ae22a65863fdb02ce99abf9ee08bcbb71">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Operand Flag enum. <a href="#ae22a65863fdb02ce99abf9ee08bcbb71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Enumerations

### TOF {#ae22a65863fdb02ce99abf9ee08bcbb71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AArch64II::TOF </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Operand Flag enum.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_NO_FLAG<a id="ae22a65863fdb02ce99abf9ee08bcbb71a48b42f4ac550b5ae203477aad0eb5e75"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_FRAGMENT<a id="ae22a65863fdb02ce99abf9ee08bcbb71a431b2e3ea036a96be92385e07bfbb0ad"></a></td>
<td class="doxyEnumItemDescription"> (= 0x7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_PAGE<a id="ae22a65863fdb02ce99abf9ee08bcbb71a7f04634c15a04a59d5f234002e613b5b"></a></td>
<td class="doxyEnumItemDescription">MO_PAGE - A symbol operand with this flag represents the pc-relative offset of the 4K page containing the symbol (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_PAGEOFF<a id="ae22a65863fdb02ce99abf9ee08bcbb71a3a5053185998bdf24f3167c234915785"></a></td>
<td class="doxyEnumItemDescription">MO_PAGEOFF - A symbol operand with this flag represents the offset of that symbol within a 4K page (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_G3<a id="ae22a65863fdb02ce99abf9ee08bcbb71af2217d25138eade76a256c4c3dc131bd"></a></td>
<td class="doxyEnumItemDescription">MO_G3 - A symbol operand with this flag (granule 3) represents the high 16-bits of a 64-bit address, used in a MOVZ or MOVK instruction (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_G2<a id="ae22a65863fdb02ce99abf9ee08bcbb71ae048a7c85d8a27195ad9ce1e1282bda9"></a></td>
<td class="doxyEnumItemDescription">MO_G2 - A symbol operand with this flag (granule 2) represents the bits 32-47 of a 64-bit address, used in a MOVZ or MOVK instruction (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_G1<a id="ae22a65863fdb02ce99abf9ee08bcbb71a30eefa1143a0a238486ada4ff95bc34b"></a></td>
<td class="doxyEnumItemDescription">MO_G1 - A symbol operand with this flag (granule 1) represents the bits 16-31 of a 64-bit address, used in a MOVZ or MOVK instruction (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_G0<a id="ae22a65863fdb02ce99abf9ee08bcbb71a6d9cfbe4ea54a3ce9d5308efab7200b9"></a></td>
<td class="doxyEnumItemDescription">MO_G0 - A symbol operand with this flag (granule 0) represents the bits 0-15 of a 64-bit address, used in a MOVZ or MOVK instruction (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_HI12<a id="ae22a65863fdb02ce99abf9ee08bcbb71abb4faac7fe2138d41464b4e802ec103f"></a></td>
<td class="doxyEnumItemDescription">MO_HI12 - This flag indicates that a symbol operand represents the bits 13-24 of a 64-bit address, used in a arithmetic immediate-shifted-left- by-12-bits instruction (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_COFFSTUB<a id="ae22a65863fdb02ce99abf9ee08bcbb71afacfcdd80d8095ce952ab919979f1d2f"></a></td>
<td class="doxyEnumItemDescription">MO_COFFSTUB - On a symbol operand "FOO", this indicates that the reference is actually to the ".refptr.FOO" symbol (= 0x8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOT<a id="ae22a65863fdb02ce99abf9ee08bcbb71a4144c2ee93286fba09bd8f14fb11f27a"></a></td>
<td class="doxyEnumItemDescription">MO_GOT - This flag indicates that a symbol operand represents the address of the GOT entry for the symbol, rather than the address of the symbol itself (= 0x10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_NC<a id="ae22a65863fdb02ce99abf9ee08bcbb71a028a4adc46c746ba1501e1e6fefb54cc"></a></td>
<td class="doxyEnumItemDescription">MO_NC - Indicates whether the linker is expected to check the symbol reference for overflow (= 0x20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_TLS<a id="ae22a65863fdb02ce99abf9ee08bcbb71add46ede0892fdd429e940eb97c1e6e55"></a></td>
<td class="doxyEnumItemDescription">MO_TLS - Indicates that the operand being accessed is some kind of thread-local symbol (= 0x40)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_DLLIMPORT<a id="ae22a65863fdb02ce99abf9ee08bcbb71a014aa77d177f925047f52c27d6dec14e"></a></td>
<td class="doxyEnumItemDescription">MO_DLLIMPORT - On a symbol operand, this represents that the reference to the symbol is for an import stub (= 0x80)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_S<a id="ae22a65863fdb02ce99abf9ee08bcbb71a39261c05ab3afff5126eb55ee51fed44"></a></td>
<td class="doxyEnumItemDescription">MO_S - Indicates that the bits of the symbol operand represented by MO_G0 etc are signed (= 0x100)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_PREL<a id="ae22a65863fdb02ce99abf9ee08bcbb71a4ac8a83c3f27cf2acb3928c64c07f1db"></a></td>
<td class="doxyEnumItemDescription">MO_PREL - Indicates that the bits of the symbol operand represented by MO_G0 etc are PC relative (= 0x200)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_TAGGED<a id="ae22a65863fdb02ce99abf9ee08bcbb71aefb2c1834e49df9715967d4a2c9c99e8"></a></td>
<td class="doxyEnumItemDescription">MO_TAGGED - With MO_PAGE, indicates that the page includes a memory tag in bits 56-63 (= 0x400)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_ARM64EC_CALLMANGLE<a id="ae22a65863fdb02ce99abf9ee08bcbb71a7e1a1b36a7d8530c6b92c03b605b8372"></a></td>
<td class="doxyEnumItemDescription">MO_ARM64EC_CALLMANGLE - Operand refers to the Arm64EC-mangled version of a symbol, not the original (= 0x800)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 780 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64baseinfo-h">AArch64BaseInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64baseinfo-h">AArch64BaseInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
