---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-micromipssizereduction-cpp-/reduceentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ReduceEntry` Struct Reference

<p>ReduceTable - A static table with information on mapping from wide opcodes to narrow. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{MicroMipsSizeReduction.cpp}::ReduceEntry { ... }
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1bf4c6446d4d039f7674dd4bb3f0cd7">operator&lt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a757310e6aa00031241eed05d1dfb3add">ReduceEntry</a> (enum ReduceType RType, struct OpCodes Op, bool(*F)(ReduceEntryFunArgs *Arguments), struct OpInfo OpInf, struct ImmField Imm)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a214848b49c5afe7c5f92d4c6138f24">operator&lt;</a> (const unsigned int r) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87d6079c8ad46b435d53450cce5582ed">NarrowOpc</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45b8eca011541e3706a78f7e9b167c83">WideOpc</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a866c5ae90df2bcb858862d7a07e639d7">LBound</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a865c88141580386f46ef5621e92df5e1">HBound</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46867ca4e393a327b25ada75469e8e2a">Shift</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6f052936c1a60b53eb8b23f264aa798">ImmField</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum <a href="/web-llvm/docs/api/namespaces/anonymous-micromipssizereduction-cpp-/#ad8ec9cdc8243cb91679297766bfe45e8">OperandTransfer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0817fb55163c5cbc5a30a0959b14f30b">TransferOperands</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum <a href="/web-llvm/docs/api/namespaces/anonymous-micromipssizereduction-cpp-/#a4ff766d0c78a22acfd48f9cbf231130d">ReduceType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89400be1185d13e018c33673f40fad1d">RType</a> () const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum <a href="/web-llvm/docs/api/namespaces/anonymous-micromipssizereduction-cpp-/#a4ff766d0c78a22acfd48f9cbf231130d">ReduceType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade94473471293137b2efe3dcb68b3537">eRType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reduction type. <a href="#ade94473471293137b2efe3dcb68b3537">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool(*</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3dc774867a2c22d517c6d97c6d4aff0">ReduceFunction</a>)(ReduceEntryFunArgs *Arguments)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pointer to reduce function. <a href="#ad3dc774867a2c22d517c6d97c6d4aff0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19f8668d1c9fc42720a6a1101d501b02">Ops</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All relevant <a href="/web-llvm/docs/api/structs/anonymous-micromipssizereduction-cpp-/opcodes">OpCodes</a>. <a href="#a19f8668d1c9fc42720a6a1101d501b02">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1513a6fe10c34a50fa0f7d6c9043cd9">OpInf</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Characteristics of operands. <a href="#aa1513a6fe10c34a50fa0f7d6c9043cd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25631d0146a616702730846b23d3e5cc">Imm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Characteristics of immediate field. <a href="#a25631d0146a616702730846b23d3e5cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>ReduceTable - A static table with information on mapping from wide opcodes to narrow.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp">MicroMipsSizeReduction.cpp</a>.</p>


<div class="doxySectionDef">

## Friends

### operator&lt; {#ac1bf4c6446d4d039f7674dd4bb3f0cd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned int r, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> struct <a href="/web-llvm/docs/api/structs/anonymous-micromipssizereduction-cpp-/reduceentry">ReduceEntry</a> &amp; re</td>
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


<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp">MicroMipsSizeReduction.cpp</a>.</p>


<p>References <a href="#a757310e6aa00031241eed05d1dfb3add">ReduceEntry</a> and <a href="#a45b8eca011541e3706a78f7e9b167c83">WideOpc</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ReduceEntry() {#a757310e6aa00031241eed05d1dfb3add}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MicroMipsSizeReduction.cpp}::ReduceEntry::ReduceEntry (enum <a href="/web-llvm/docs/api/namespaces/anonymous-micromipssizereduction-cpp-/#a4ff766d0c78a22acfd48f9cbf231130d">ReduceType</a> RType, struct <a href="/web-llvm/docs/api/structs/anonymous-micromipssizereduction-cpp-/opcodes">OpCodes</a> Op, bool(*)(<a href="/web-llvm/docs/api/structs/anonymous-micromipssizereduction-cpp-/reduceentryfunargs">ReduceEntryFunArgs</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp/#a1161e5a4e753384aaba3a8e4533c4261">Arguments</a>) F, struct <a href="/web-llvm/docs/api/structs/anonymous-micromipssizereduction-cpp-/opinfo">OpInfo</a> OpInf, struct <a href="/web-llvm/docs/api/structs/anonymous-micromipssizereduction-cpp-/immfield">ImmField</a> Imm)</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp">MicroMipsSizeReduction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp/#a1161e5a4e753384aaba3a8e4533c4261">Arguments</a>, <a href="#ade94473471293137b2efe3dcb68b3537">eRType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a25631d0146a616702730846b23d3e5cc">Imm</a>, <a href="#ad6f052936c1a60b53eb8b23f264aa798">ImmField</a>, <a href="#aa1513a6fe10c34a50fa0f7d6c9043cd9">OpInf</a>, <a href="#a19f8668d1c9fc42720a6a1101d501b02">Ops</a>, <a href="#ad3dc774867a2c22d517c6d97c6d4aff0">ReduceFunction</a> and <a href="#a89400be1185d13e018c33673f40fad1d">RType</a>.</p>


<p>Referenced by <a href="#ac1bf4c6446d4d039f7674dd4bb3f0cd7">operator&lt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator&lt;() {#a6a214848b49c5afe7c5f92d4c6138f24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MicroMipsSizeReduction.cpp}::ReduceEntry::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned int r)</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp">MicroMipsSizeReduction.cpp</a>.</p>


<p>Reference <a href="#a45b8eca011541e3706a78f7e9b167c83">WideOpc</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### HBound() {#a865c88141580386f46ef5621e92df5e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int16_t anonymous{MicroMipsSizeReduction.cpp}::ReduceEntry::HBound ()</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp">MicroMipsSizeReduction.cpp</a>.</p>


<p>Reference <a href="#a25631d0146a616702730846b23d3e5cc">Imm</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp/#aaac99696c5f396905a86fa853f41614f">InRange</a>.</p>

</div>
</div>

### ImmField() {#ad6f052936c1a60b53eb8b23f264aa798}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int8_t anonymous{MicroMipsSizeReduction.cpp}::ReduceEntry::ImmField ()</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp">MicroMipsSizeReduction.cpp</a>.</p>


<p>Reference <a href="#a25631d0146a616702730846b23d3e5cc">Imm</a>.</p>


<p>Referenced by <a href="#a757310e6aa00031241eed05d1dfb3add">ReduceEntry</a>.</p>

</div>
</div>

### LBound() {#a866c5ae90df2bcb858862d7a07e639d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int16_t anonymous{MicroMipsSizeReduction.cpp}::ReduceEntry::LBound ()</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp">MicroMipsSizeReduction.cpp</a>.</p>


<p>Reference <a href="#a25631d0146a616702730846b23d3e5cc">Imm</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp/#aaac99696c5f396905a86fa853f41614f">InRange</a>.</p>

</div>
</div>

### NarrowOpc() {#a87d6079c8ad46b435d53450cce5582ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{MicroMipsSizeReduction.cpp}::ReduceEntry::NarrowOpc ()</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp">MicroMipsSizeReduction.cpp</a>.</p>


<p>Reference <a href="#a19f8668d1c9fc42720a6a1101d501b02">Ops</a>.</p>

</div>
</div>

### RType() {#a89400be1185d13e018c33673f40fad1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum ReduceType anonymous{MicroMipsSizeReduction.cpp}::ReduceEntry::RType ()</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp">MicroMipsSizeReduction.cpp</a>.</p>


<p>Reference <a href="#ade94473471293137b2efe3dcb68b3537">eRType</a>.</p>


<p>Referenced by <a href="#a757310e6aa00031241eed05d1dfb3add">ReduceEntry</a>.</p>

</div>
</div>

### Shift() {#a46867ca4e393a327b25ada75469e8e2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t anonymous{MicroMipsSizeReduction.cpp}::ReduceEntry::Shift ()</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp">MicroMipsSizeReduction.cpp</a>.</p>


<p>Reference <a href="#a25631d0146a616702730846b23d3e5cc">Imm</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp/#aaac99696c5f396905a86fa853f41614f">InRange</a>.</p>

</div>
</div>

### TransferOperands() {#a0817fb55163c5cbc5a30a0959b14f30b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum OperandTransfer anonymous{MicroMipsSizeReduction.cpp}::ReduceEntry::TransferOperands ()</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp">MicroMipsSizeReduction.cpp</a>.</p>


<p>Reference <a href="#aa1513a6fe10c34a50fa0f7d6c9043cd9">OpInf</a>.</p>

</div>
</div>

### WideOpc() {#a45b8eca011541e3706a78f7e9b167c83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{MicroMipsSizeReduction.cpp}::ReduceEntry::WideOpc ()</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp">MicroMipsSizeReduction.cpp</a>.</p>


<p>Reference <a href="#a19f8668d1c9fc42720a6a1101d501b02">Ops</a>.</p>


<p>Referenced by <a href="#a6a214848b49c5afe7c5f92d4c6138f24">operator&lt;</a> and <a href="#ac1bf4c6446d4d039f7674dd4bb3f0cd7">operator&lt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### eRType {#ade94473471293137b2efe3dcb68b3537}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum ReduceType anonymous{MicroMipsSizeReduction.cpp}::ReduceEntry::eRType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reduction type.</p>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp">MicroMipsSizeReduction.cpp</a>.</p>


<p>Referenced by <a href="#a757310e6aa00031241eed05d1dfb3add">ReduceEntry</a> and <a href="#a89400be1185d13e018c33673f40fad1d">RType</a>.</p>

</div>
</div>

### Imm {#a25631d0146a616702730846b23d3e5cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct ImmField anonymous{MicroMipsSizeReduction.cpp}::ReduceEntry::Imm</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Characteristics of immediate field.</p>

<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp">MicroMipsSizeReduction.cpp</a>.</p>


<p>Referenced by <a href="#a865c88141580386f46ef5621e92df5e1">HBound</a>, <a href="#ad6f052936c1a60b53eb8b23f264aa798">ImmField</a>, <a href="#a866c5ae90df2bcb858862d7a07e639d7">LBound</a>, <a href="#a757310e6aa00031241eed05d1dfb3add">ReduceEntry</a> and <a href="#a46867ca4e393a327b25ada75469e8e2a">Shift</a>.</p>

</div>
</div>

### OpInf {#aa1513a6fe10c34a50fa0f7d6c9043cd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct OpInfo anonymous{MicroMipsSizeReduction.cpp}::ReduceEntry::OpInf</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Characteristics of operands.</p>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp">MicroMipsSizeReduction.cpp</a>.</p>


<p>Referenced by <a href="#a757310e6aa00031241eed05d1dfb3add">ReduceEntry</a> and <a href="#a0817fb55163c5cbc5a30a0959b14f30b">TransferOperands</a>.</p>

</div>
</div>

### Ops {#a19f8668d1c9fc42720a6a1101d501b02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct OpCodes anonymous{MicroMipsSizeReduction.cpp}::ReduceEntry::Ops</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All relevant <a href="/web-llvm/docs/api/structs/anonymous-micromipssizereduction-cpp-/opcodes">OpCodes</a>.</p>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp">MicroMipsSizeReduction.cpp</a>.</p>


<p>Referenced by <a href="#a87d6079c8ad46b435d53450cce5582ed">NarrowOpc</a>, <a href="#a757310e6aa00031241eed05d1dfb3add">ReduceEntry</a> and <a href="#a45b8eca011541e3706a78f7e9b167c83">WideOpc</a>.</p>

</div>
</div>

### ReduceFunction {#ad3dc774867a2c22d517c6d97c6d4aff0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool(* anonymous{MicroMipsSizeReduction.cpp}::ReduceEntry::ReduceFunction) (ReduceEntryFunArgs *Arguments)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pointer to reduce function.</p>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp">MicroMipsSizeReduction.cpp</a>.</p>


<p>Referenced by <a href="#a757310e6aa00031241eed05d1dfb3add">ReduceEntry</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp">MicroMipsSizeReduction.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
