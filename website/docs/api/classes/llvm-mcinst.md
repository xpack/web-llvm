---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcinst
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCInst` Class Reference

<p>Instances of this class represent a single low-level machine instruction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MCInst { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">llvm/MC/MCInst.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48b4f98c8f42ed1a9d07419f7df1d855">iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &gt;::iterator</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae234776ac492a25df69d7dd394910a20">const_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &gt;::const_iterator</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fc00691cf17959a625009d21b002f45">MCInst</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae844d6ff99f067e6672e004ed7613c24">setOpcode</a> (unsigned Op)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c26b1db954c27889986dba3b310a8e4">getOpcode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80636f9f710d053d06c8de4f755255a3">setFlags</a> (unsigned F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a518d09ad3fe41943c92e577a98fe374c">getFlags</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a580e2a6e8a248c5a4a814c03186e9241">setLoc</a> (SMLoc loc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40c7fb73978096ed317dd71fb8a84cf4">getLoc</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef5de3ac30fe221c5b4e702574ab46a9">getOperand</a> (unsigned i) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c40cd35f8cf9812d327d6c4d391011e">getOperand</a> (unsigned i)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c5c7109f398fdca515509e2284cd8c0">getNumOperands</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5a79c04398dc86a3acfe7f8713216eb">addOperand</a> (const MCOperand Op)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecd4e9369c30b88c8e528489f69e0c8e">clear</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a392c263d0b0a47be4702000f9bca7f16">erase</a> (iterator I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ceb216bb12f49d64b81f89567af3e30">erase</a> (iterator First, iterator Last)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae534d5d22096b2665d16e5ab600ebbce">size</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a48b4f98c8f42ed1a9d07419f7df1d855">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7df02a018c3a01d74738d5ba3a09e93">begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae234776ac492a25df69d7dd394910a20">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a758d1c99f5e677bbca86b4f70860babf">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a48b4f98c8f42ed1a9d07419f7df1d855">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad815f3f5c7e6106ca7ba4926d143c2cf">end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae234776ac492a25df69d7dd394910a20">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3089b28c8766e9d73fef97277bff4760">end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a48b4f98c8f42ed1a9d07419f7df1d855">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a780fe7b1259c076cd5abef9ce9dda01d">insert</a> (iterator I, const MCOperand &amp;Op)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d101ee8e316d793b1e136a0ee3a7795">print</a> (raw_ostream &amp;OS, const MCRegisterInfo *RegInfo=nullptr) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8aa6b74c6bb82576347afb756807f20">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a230d5dad7ea2d94e1671a4aa222a2e15">dump_pretty</a> (raw_ostream &amp;OS, const MCInstPrinter *Printer=nullptr, StringRef Separator=" ", const MCRegisterInfo *RegInfo=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump the <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> as prettily as possible using the additional MC structures, if given. <a href="#a230d5dad7ea2d94e1671a4aa222a2e15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed3878e91373aaa765f80e2242ed2d00">dump_pretty</a> (raw_ostream &amp;OS, StringRef Name, StringRef Separator=" ", const MCRegisterInfo *RegInfo=nullptr) const</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f21ce68a58349cd2b2b57a3195a08c4">Opcode</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab8ea63e2c999f11dce03739b9e379b9">Flags</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac99e50fe6f794796794a3817e158fbe4">Loc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a>, 6 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7fdc16e0c56a7d8a1867cbd6930773f">Operands</a></td>
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

<p>Instances of this class represent a single low-level machine instruction.</p>

<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#ae234776ac492a25df69d7dd394910a20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MCInst::const_iterator =  SmallVectorImpl&lt;MCOperand&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a>.</p>

</div>
</div>

### iterator {#a48b4f98c8f42ed1a9d07419f7df1d855}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MCInst::iterator =  SmallVectorImpl&lt;MCOperand&gt;::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MCInst() {#a6fc00691cf17959a625009d21b002f45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCInst::MCInst ()</td>
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



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addOperand() {#ad5a79c04398dc86a3acfe7f8713216eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCInst::addOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> Op)</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a3fb809c95f07fa9985fef7e95cf551c8">llvm::X86Operand::addAbsMemOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a1c9da2c1517144cce67c080d549f24fb">anonymous{MipsAsmParser.cpp}::MipsOperand::addACC64DSPAsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aff551f6c57e2bda70f7c58294b662d04">anonymous{ARMAsmParser.cpp}::ARMOperand::addAddrMode2Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a29b2705aeee49d31d232c5ab440f7877">anonymous{ARMAsmParser.cpp}::ARMOperand::addAddrMode3Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aeca538a61ece736dfa6ca68bfcebb401">anonymous{ARMAsmParser.cpp}::ARMOperand::addAddrMode5FP16Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a6b2100e3595ebc052f71501e05bf9ef4">anonymous{ARMAsmParser.cpp}::ARMOperand::addAddrMode5Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#af6a434a23522485bf0d986faf12ee9f8">anonymous{ARMAsmParser.cpp}::ARMOperand::addAdrLabelOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ab44f4b2113b7a3876bd7e61758319c6f">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addAdrpLabelOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a97ec632b3a5e002b1d3d99b8b79c7883">anonymous{MipsAsmParser.cpp}::MipsOperand::addAFGR64AsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a548a79ef6ddd55b914e259d2f957c632">anonymous{ARMAsmParser.cpp}::ARMOperand::addAlignedMemoryOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ab5034e33be4df547034085fd56f5ef7a">anonymous{ARMAsmParser.cpp}::ARMOperand::addAM2OffsetImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a9e51c04c7eea24160648528b9e2867c7">anonymous{ARMAsmParser.cpp}::ARMOperand::addAM3OffsetOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmparser-cpp-/m68koperand/#a0e5767e266948d2da6a968bed7c234af">anonymous{M68kAsmParser.cpp}::M68kOperand::addARIDOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmparser-cpp-/m68koperand/#a8b36bcd58d06ed763e3ff606ef787d61">anonymous{M68kAsmParser.cpp}::M68kOperand::addARIIOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmparser-cpp-/m68koperand/#aef9678d5d40dc29d922920d97fe2e108">anonymous{M68kAsmParser.cpp}::M68kOperand::addARIOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmparser-cpp-/m68koperand/#aa408301e2671cf7040584011da1ca4ee">anonymous{M68kAsmParser.cpp}::M68kOperand::addARIPDOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmparser-cpp-/m68koperand/#a2a6d1110d5731551b614fc041a5e100e">anonymous{M68kAsmParser.cpp}::M68kOperand::addARIPIOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcoperand/#a139c989aebeb47528c3f50d9c97f55e4">anonymous{SparcAsmParser.cpp}::SparcOperand::addASITagOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a10e5ca2afe28615ccce1a071f17d25c1">anonymous{ARMAsmParser.cpp}::ARMOperand::addBankedRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a48edf5070960702e2bdb4809a21e342e">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addBarriernXSOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a591114c0fea921bbe5364d31fbef1b64">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addBarrierOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#a9b9382a69efae30312157561c9935e47">anonymous{SystemZAsmParser.cpp}::SystemZOperand::addBDAddrOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#ac0c2fe3c329a0af3333996cd5f459941">anonymous{SystemZAsmParser.cpp}::SystemZOperand::addBDLAddrOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#a94365cb7b08e65f8c3939b8c6403137c">anonymous{SystemZAsmParser.cpp}::SystemZOperand::addBDRAddrOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#af776389f8f4e4c37da30a66ff260f9f6">anonymous{SystemZAsmParser.cpp}::SystemZOperand::addBDVAddrOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#abf2793ad54a2663ea0dedbaaa2b29cd8">anonymous{SystemZAsmParser.cpp}::SystemZOperand::addBDXAddrOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aecad58f6dbb6b10e480e511a6880d3a8">anonymous{ARMAsmParser.cpp}::ARMOperand::addBitfieldOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#aab7d7b59c23bda548073770ccaaa1f54">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addBranchTarget14Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#aa1448a1c0dc861047a4abeab5dfa3d57">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addBranchTarget26Operands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#ae4e11d80124a79d601e7d34d463ff119">anonymous{PPCAsmParser.cpp}::PPCOperand::addBranchTargetOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-webassemblyasmparser-cpp-/webassemblyoperand/#a8896b0d3d3c22e3b36197de128dd7fd6">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::addBrListOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a8745b3f6e84510f5123c608560d067c3">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addBTIHintOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-webassemblyasmparser-cpp-/webassemblyoperand/#a20abe1ede172e9ba62511e7892a43051">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::addCatchListOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#aecf9ef1555e75bad67a11aabe6d914c5">anonymous{VEAsmParser.cpp}::VEOperand::addCCOpOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aa03e2c6253e6c5b0f0b7b6013e18407f">anonymous{ARMAsmParser.cpp}::ARMOperand::addCCOutOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a9e8be9fe66ed8d207fc58839c24ce8ae">anonymous{MipsAsmParser.cpp}::MipsOperand::addCCRAsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#acd4ed46a8bba14b6e611e0e34a5e02cc">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addComplexRotationEvenOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#afd957e14a6704fe97baef0356550ee54">anonymous{ARMAsmParser.cpp}::ARMOperand::addComplexRotationEvenOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a0e16e22e5918c7110f0f7658b61f53e8">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addComplexRotationOddOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a14c8b64e8fda48fef5220dfb9018fc08">anonymous{ARMAsmParser.cpp}::ARMOperand::addComplexRotationOddOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a5120ff8db5e8098a3f9551e139d8aeaf">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addCondCodeOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a03e3b195e9ccc3d8c840e87f0cba6dbc">anonymous{ARMAsmParser.cpp}::ARMOperand::addCondCodeOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#ac6fc6636f3e516e99df40178e7e06215">anonymous{MipsAsmParser.cpp}::MipsOperand::addConstantSImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a7df0924976dc5e03315428d6d30ace75">anonymous{MipsAsmParser.cpp}::MipsOperand::addConstantUImmOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a95f7f3602bc5500992d937bd0bb33b3e">llvm::HexagonMCInstrInfo::addConstExtender</a>, <a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand/#a4945c8a4072ad73e71889ff2d278625a">anonymous{CSKYAsmParser.cpp}::CSKYOperand::addConstpoolOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a5a5052251d14c5c2dcaba9c28c37da47">anonymous{MipsAsmParser.cpp}::MipsOperand::addCOP0AsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#af5da2d886c9733e83e02b50abeecc30e">anonymous{MipsAsmParser.cpp}::MipsOperand::addCOP2AsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a8d0cb9abd93678d9c6bc6a3a25eec412">anonymous{MipsAsmParser.cpp}::MipsOperand::addCOP3AsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a768efe40ca84546861891d6c31a1fb0b">anonymous{ARMAsmParser.cpp}::ARMOperand::addCoprocNumOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a10de3d0676a377654d69cb821f9d9d34">anonymous{ARMAsmParser.cpp}::ARMOperand::addCoprocOptionOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ad4ba28c8a06374cb1fe25facd4d8081b">anonymous{ARMAsmParser.cpp}::ARMOperand::addCoprocRegOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a5416ccbb01a0d1a87c306aa8f9229cc7">anonymous{PPCAsmParser.cpp}::PPCOperand::addCRBitMaskOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#afd5cd5faa882cb075d2cd166a3cd3222">anonymous{RISCVAsmParser.cpp}::RISCVOperand::addCSRSystemRegisterOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#aa957005d508608716aace06b32aedff5">llvm::X86Operand::addDstIdxOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a9644f19a682324b158710b3222d190eb">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addExactFPImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a30cd1f96ee2fa28938de227cf1b47f02">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aa1ad8d8d8f3e6ec7d484038366b52d56">anonymous{ARMAsmParser.cpp}::ARMOperand::addExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-avrasmparser-cpp-/avroperand/#aa7e1dbb2e69107ec242f6ca449714a16">anonymous{AVRAsmParser.cpp}::AVROperand::addExpr</a>, <a href="/web-llvm/docs/api/structs/anonymous-bpfasmparser-cpp-/bpfoperand/#a131750f951f27d215abe63ea053cd7d6">anonymous{BPFAsmParser.cpp}::BPFOperand::addExpr</a>, <a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand/#af00891539f650560293f19ca17fa9160">anonymous{CSKYAsmParser.cpp}::CSKYOperand::addExpr</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#a852804acbee235af9428694e0e2a1fca">anonymous{LanaiAsmParser.cpp}::LanaiOperand::addExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchoperand/#af7589c38fd0a2e2644d73a92624904d1">anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::addExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmparser-cpp-/m68koperand/#a6e27ec9bcfe6b34b7270dc44cc0cc486">anonymous{M68kAsmParser.cpp}::M68kOperand::addExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a367d806a6fbbc9dfcf3932a721d269bd">anonymous{MipsAsmParser.cpp}::MipsOperand::addExpr</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a6762c005d2c4f50e2ba59d9cdab146a5">anonymous{RISCVAsmParser.cpp}::RISCVOperand::addExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcoperand/#ab57038958e6d694e4dab42f5dbee3459">anonymous{SparcAsmParser.cpp}::SparcOperand::addExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#af56e7fc8fa21980f6b8dab84edfa1bf0">anonymous{VEAsmParser.cpp}::VEOperand::addExpr</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a16fc7281d45e1dfc3a9caf539e564d0f">llvm::X86Operand::addExpr</a>, <a href="/web-llvm/docs/api/structs/xtensaoperand/#a33a1c12d05259bebda8e5ee37fcd9b9e">XtensaOperand::addExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-msp430asmparser-cpp-/msp430operand/#a4b2ddbddfcf39f25f8909b8a9a16312f">anonymous{MSP430AsmParser.cpp}::MSP430Operand::addExprOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a12ebb7021420c49a1338058e4db7f435">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addExtend64Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a8a2b0c34d3cfaf2fa1561bfaf6182700">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addExtendOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a4b1be0b8c60dcebb134703a9676484e8">anonymous{ARMAsmParser.cpp}::ARMOperand::addFBits16Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a2c571f76a5913408475fa986a60ed6f1">anonymous{ARMAsmParser.cpp}::ARMOperand::addFBits32Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a0ef7cd5c70764da83c69359a22b1d8fc">anonymous{MipsAsmParser.cpp}::MipsOperand::addFCCAsmRegOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#aaab805d2778c683124cc4241c4ae522e">anonymous{RISCVAsmParser.cpp}::RISCVOperand::addFenceArgOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a19837d0a63e7e5a0688d838fc824c16e">anonymous{MipsAsmParser.cpp}::MipsOperand::addFGR32AsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a45e61c46f7d86680d3816b090113bc7c">anonymous{MipsAsmParser.cpp}::MipsOperand::addFGR64AsmRegOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-webassemblyasmparser-cpp-/webassemblyoperand/#a897c9e930c31d4b65408c09c73d6a417">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::addFPImmf32Operands</a>, <a href="/web-llvm/docs/api/structs/anonymous-webassemblyasmparser-cpp-/webassemblyoperand/#a3bcb95d1f0d9f65bf8d7fb3e60601c57">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::addFPImmf64Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#aadc0596f177340a6d088aa4b9084263d">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addFPImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#abe2cc7744f5671009687f38923ffd49b">anonymous{ARMAsmParser.cpp}::ARMOperand::addFPImmOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a72b37da283ebf9ecc9ef3b8468b9569d">anonymous{RISCVAsmParser.cpp}::RISCVOperand::addFPImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a693bc5d80a94144221ae8311989c4652">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addFPRasZPRRegOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a852817cd2a9f95112d0f01374ddc156f">anonymous{RISCVAsmParser.cpp}::RISCVOperand::addFRMArgOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ac4f56500894c6c3ca92c54b569cc42a7">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addGPR32as64Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#abd3fc4a45ddc96177fb36555202c66ae">anonymous{MipsAsmParser.cpp}::MipsOperand::addGPR32AsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a816b9264393cb64140de265f504fce83">anonymous{MipsAsmParser.cpp}::MipsOperand::addGPR32NonZeroAsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a83d460a6677f2f149ca35ea1a921a180">anonymous{MipsAsmParser.cpp}::MipsOperand::addGPR32ZeroAsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ac45d96b1d1611280239c5f5ec90e1d22">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addGPR64as32Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a51bf0a531510cc8e16e3226e82f10bcf">anonymous{MipsAsmParser.cpp}::MipsOperand::addGPR64AsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a3527031d5d4e3cb6824564e3a2ac1e76">anonymous{MipsAsmParser.cpp}::MipsOperand::addGPRMM16AsmRegMovePOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#ae58ddc1271c5f3654e0ea31436ff5e0b">anonymous{MipsAsmParser.cpp}::MipsOperand::addGPRMM16AsmRegMovePPairFirstOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#ab2c6ec24d31e5181054f9f6d9469ae79">anonymous{MipsAsmParser.cpp}::MipsOperand::addGPRMM16AsmRegMovePPairSecondOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#aa46096946509f9d61cc4753c3ce9a69a">anonymous{MipsAsmParser.cpp}::MipsOperand::addGPRMM16AsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a3a16376a94d441185b8a8b41c7174b79">anonymous{MipsAsmParser.cpp}::MipsOperand::addGPRMM16AsmRegZeroOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a25127edbfd500680786a7964074d8629">llvm::X86Operand::addGR16orGR32orGR64Operands</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a86467b8eb24fee4d7a713a537685d783">llvm::X86Operand::addGR32orGR64Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a1a0c253d3acd5440394239432c9fd5a1">anonymous{MipsAsmParser.cpp}::MipsOperand::addHI32DSPAsmRegOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#a1d7b8b2f33404bae5609243536427d9b">anonymous{LanaiAsmParser.cpp}::LanaiOperand::addHiImm16AndOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#a1df049e5840d649a327cba55d9ad3f8d">anonymous{LanaiAsmParser.cpp}::LanaiOperand::addHiImm16Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a221fdbf10781b3153f4dbc016a6bb059">anonymous{MipsAsmParser.cpp}::MipsOperand::addHWRegsAsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aa32c68b18eb08b2d2ccd98d101c9b46f">anonymous{ARMAsmParser.cpp}::ARMOperand::addImm0_1020s4Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a9a414428a9327e625a2299744ff564fe">anonymous{ARMAsmParser.cpp}::ARMOperand::addImm0_4095NegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ab4026544d255ebabc8012238640dab5e">anonymous{ARMAsmParser.cpp}::ARMOperand::addImm0_508s4NegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#adfd7a84e908bb0a8dfca3ea459d652db">anonymous{ARMAsmParser.cpp}::ARMOperand::addImm0_508s4Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aa7de9805408dca5ee30579319047181b">anonymous{ARMAsmParser.cpp}::ARMOperand::addImm1_16Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ac442880c4ca40e62e9f8398797ca5ec3">anonymous{ARMAsmParser.cpp}::ARMOperand::addImm1_32Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a361541dc318a3d464e368db2a352e56b">anonymous{ARMAsmParser.cpp}::ARMOperand::addImm7Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#acdafd01d7875d4bf736bae1cc72a36fc">anonymous{ARMAsmParser.cpp}::ARMOperand::addImm7s4Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#af91b5c447e1b5d8cb35d0000b4f48052">anonymous{ARMAsmParser.cpp}::ARMOperand::addImm7Shift0Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#afd8f1642115c7fc6d487ffce63218a32">anonymous{ARMAsmParser.cpp}::ARMOperand::addImm7Shift1Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a81d4ac723e053777bb1b1796dc982098">anonymous{ARMAsmParser.cpp}::ARMOperand::addImm7Shift2Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a78914a4833ee6ecedeace11e730b5cd2">anonymous{ARMAsmParser.cpp}::ARMOperand::addImm8s4Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-avrasmparser-cpp-/avroperand/#aeb9cfed53c597477080d2f8d03cb4442">anonymous{AVRAsmParser.cpp}::AVROperand::addImmCom8Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ab1e3f86f5e35a49ad9969616da8ee130">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addImmNegWithOptionalShiftOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aecc4bcb6c40064c4c0544f55facbb18a">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addImmOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonasmparser-cpp-/hexagonoperand/#a12db185eb8785ef79c995954f5a15bf3">anonymous{HexagonAsmParser.cpp}::HexagonOperand::addImmOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a713d7daafa349daa3ed89e1cf32844ba">anonymous{PPCAsmParser.cpp}::PPCOperand::addImmOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-webassemblyasmparser-cpp-/webassemblyoperand/#a1843f39a0d50d963f92c5f1fe30b633e">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::addImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ad09ecb52e79c8bef77dea3fa313c9a31">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addImmScaledOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a3dfb11dc7e2fe62f40ada900f6e9e176">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addImmScaledRangeOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a94e86034d35c6b76f9910bf56f7b793f">anonymous{ARMAsmParser.cpp}::ARMOperand::addImmThumbSROperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ab6d217a1a1a9c4c03289d555a4404aed">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addImmWithOptionalShiftOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aa1e630839626b7ae31f6abc1d87209e9">anonymous{ARMAsmParser.cpp}::ARMOperand::addInstSyncBarrierOptOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ad43d0a6a64bad5f305bb9ad845bd2096">anonymous{ARMAsmParser.cpp}::ARMOperand::addITCondCodeInvOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ac5e2c8aff96996ab20507dab30f9299b">anonymous{ARMAsmParser.cpp}::ARMOperand::addITCondCodeOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a9680608c6a2d4bde00a5b8b5ebb92bfe">anonymous{ARMAsmParser.cpp}::ARMOperand::addITMaskOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa952aa5bfb51a38178c0d47e0fc7aa7b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addLiteralImmOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a5d3694893cd2e7880c2b77c3230c2865">anonymous{MipsAsmParser.cpp}::MipsOperand::addLO32DSPAsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a9056346261cb779a567f627676c37068">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addLogicalImmNotOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ae997d5e3fd8015241b318c4b0da0c194">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addLogicalImmOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#a9773bf588f5b30ff88274f1ee52e9c9b">anonymous{LanaiAsmParser.cpp}::LanaiOperand::addLoImm16AndOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#a0e06c5e6471e93005516ed8a140c72cb">anonymous{LanaiAsmParser.cpp}::LanaiOperand::addLoImm16Operands</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#a5b3ab698b20fe1832388bb62f71c213e">anonymous{LanaiAsmParser.cpp}::LanaiOperand::addLoImm21Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#aa032e057f6912df64dddaffa3eaadf91">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addLSLImm3ShifterOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#a5adb948f0e1acffb765fb3d36b58635f">anonymous{SystemZAsmParser.cpp}::SystemZOperand::addLXAAddrOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a1411797182fa22f898f4baf0e3eb7298">llvm::X86Operand::addMaskPairOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a52a9b33a2e0d8bab36c2c5cb7b36d610">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addMatrixOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a705e1e39d5002641f1a1a2730612b728">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addMatrixTileListOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ab997fbc3057584e8c726b4d11c18746d">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemBarrierOptOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ac9f0eb14b728a80df813a4da2e6ea7a7">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addMemExtend8Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a4c2a8c70306e9fdd7c8450d043f183e2">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addMemExtendOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#abe5b4923e46ab980bfb612b7a54cde90">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemImm0_1020s4OffsetOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a6dff62db50ccdfe98aff9cb203745a66">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemImm12OffsetOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a9fb937acd028a5bf796c672a0d6c5f75">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemImm7s4OffsetOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a4301f3a2bb78f6f20862ba128f6f52f5">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemImm8s4OffsetOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a80bc470aec6db28b9d04cf11684eb9da">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemImmOffsetOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a2f54ecd20a9f31051c94fae0b156b249">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemNoOffsetOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a1970df12effbecce45e177c7121cea0d">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemNoOffsetT2NoSpOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a24f1bef4c5ea237c5519ac8ea4b0a69e">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemNoOffsetT2Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a0f4b00007fc60d4881752835aa78235f">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemNoOffsetTOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a46908e32f1979cb4f57d7d26df02bbf7">llvm::X86Operand::addMemOffsOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#aaf1abd090a089523ab1f4fa4158734aa">anonymous{MipsAsmParser.cpp}::MipsOperand::addMemOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-msp430asmparser-cpp-/msp430operand/#af6f292c019d2b087fc36a88099ea71a4">anonymous{MSP430AsmParser.cpp}::MSP430Operand::addMemOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#aa68185209b553ccd5de6d4cd21aae0b7">llvm::X86Operand::addMemOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a3e8d637955189e14866f744f29ee8ea5">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemPCRelImm12Operands</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#acacea0c596433796a7a9674ef7d6df1c">anonymous{LanaiAsmParser.cpp}::LanaiOperand::addMemRegImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a97437a291cf5a4acb1a9459466af8637">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemRegOffsetOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#a3bc907003ab69e65230cb39a00390735">anonymous{LanaiAsmParser.cpp}::LanaiOperand::addMemRegRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ab0e32805a18bd96de1be7ab2112092dd">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemRegRQOffsetOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#ac78a8f54f4da2b028a4c513e9646c92a">anonymous{VEAsmParser.cpp}::VEOperand::addMEMriiOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcoperand/#ac20dd2f0350bf18d6fd97ba7ad0a2994">anonymous{SparcAsmParser.cpp}::SparcOperand::addMEMriOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#a4fad1c08c01d149c6d24ae557bcee7d8">anonymous{VEAsmParser.cpp}::VEOperand::addMEMriOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-avrasmparser-cpp-/avroperand/#adf651d75c9923608fead490becd08b33">anonymous{AVRAsmParser.cpp}::AVROperand::addMemriOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#a6c548174c36ceb90c1f77a6c163e80b1">anonymous{VEAsmParser.cpp}::VEOperand::addMEMrriOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcoperand/#aa7bb9d19afdd909845c9e565b833ef93">anonymous{SparcAsmParser.cpp}::SparcOperand::addMEMrrOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a40b064476649a0a56ce95f93aa65c89b">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemTBBOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a98d14559bea78406707287429d722ffe">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemTBHOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a38c9a43be0fe27ac8944c0c8a89bb6b1">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemThumbRIs1Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ad3b02f1b47b3ba6fd451237a1630aab4">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemThumbRIs2Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a8e7c2c39ca9a33a289abd869b71142f7">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemThumbRIs4Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a61729ed00e2b9ac641d162d059f24946">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemThumbRROperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a2b7bc4182080d75de1cb54ed7b5a90f8">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemThumbSPIOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a9f7334fe4a405366c2e73604c925921f">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemUImm12OffsetOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#a9fd8cdace145c937068216b5623d0e22">anonymous{VEAsmParser.cpp}::VEOperand::addMEMziiOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#aa6fbe9cbd311a2636146bafdc021c76c">anonymous{VEAsmParser.cpp}::VEOperand::addMEMziOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#a72fe72f0ed13e4b97e1285d946efe7ec">anonymous{VEAsmParser.cpp}::VEOperand::addMEMzriOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a0d290306e7f76b115cfe75025d92be37">anonymous{MipsAsmParser.cpp}::MipsOperand::addMicroMipsMemOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#a512f8716f6ee88fcef3b08264b744047">anonymous{VEAsmParser.cpp}::VEOperand::addMImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a00f276d60b4213d06f10e1c6965e6982">anonymous{ARMAsmParser.cpp}::ARMOperand::addModImmNegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a25c3c5882ff6060ea26a9a2c6c96e4d9">anonymous{ARMAsmParser.cpp}::ARMOperand::addModImmNotOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a540ca19122e726ab4ca0c7a2f8a38ca8">anonymous{ARMAsmParser.cpp}::ARMOperand::addModImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmparser-cpp-/m68koperand/#a9cd23b62012f429a2e2edb2cb30c21b7">anonymous{M68kAsmParser.cpp}::M68kOperand::addMoveMaskOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a937ca41eef356bc1388ad88f951238b7">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addMOVNMovAliasOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a4e23ebca490a6a436d047976a01e7d2f">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addMOVZMovAliasOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a4beaf9b78d7eb225552cd94b0149b024">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addMRSSystemRegisterOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a30e5904a36614ccc09d784c12b981554">anonymous{MipsAsmParser.cpp}::MipsOperand::addMSA128AsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a32627220d84219d7cd27750d9664f16a">anonymous{MipsAsmParser.cpp}::MipsOperand::addMSACtrlAsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ad4a17494019897f01769f746ad7293d6">anonymous{ARMAsmParser.cpp}::ARMOperand::addMSRMaskOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a1c8b498e080d62622a43e79e74556aa3">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addMSRSystemRegisterOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a572dc8085b30704f8e30e28dccf68e42">anonymous{ARMAsmParser.cpp}::ARMOperand::addMVEPairVectorIndexOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a9cc6b74af0c84b124eb91623d1b97d53">anonymous{ARMAsmParser.cpp}::ARMOperand::addMveSaturateOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a7673cc7bf77bfe4773e263692b64c792">anonymous{ARMAsmParser.cpp}::ARMOperand::addMVEVecListOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a661225f249347ef6b1be3ad7751bedbb">anonymous{ARMAsmParser.cpp}::ARMOperand::addMVEVectorIndexOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp/#a773e13d9361edd4a75124c26e305bf13">addNegOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a8d92ff1355dcb13d00196990471f9139">anonymous{ARMAsmParser.cpp}::ARMOperand::addNEONi16splatNotOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a0940a9f22c8bd87b7fa0a45e012d0516">anonymous{ARMAsmParser.cpp}::ARMOperand::addNEONi16splatOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a4262ad98cb319bdaf2b640bdb0fbd6ff">anonymous{ARMAsmParser.cpp}::ARMOperand::addNEONi32splatNotOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a36daafec1fff81a5867269e34313dc3d">anonymous{ARMAsmParser.cpp}::ARMOperand::addNEONi32splatOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aad748df99e69a972f2c9e52b8cc39d00">anonymous{ARMAsmParser.cpp}::ARMOperand::addNEONi32vmovNegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ac0bf4b69732f350137e1d6ae29cb5c92">anonymous{ARMAsmParser.cpp}::ARMOperand::addNEONi32vmovOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#af385793af30b498ff6359717174370f3">anonymous{ARMAsmParser.cpp}::ARMOperand::addNEONi64splatOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ad77c1ff80909be05a660bdcb161beb65">anonymous{ARMAsmParser.cpp}::ARMOperand::addNEONi8ReplicateOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a14b3322ac32c8b0b4eefae2bb49eda10">anonymous{ARMAsmParser.cpp}::ARMOperand::addNEONi8splatOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#accc1e804755bf43243950da346e4f635">anonymous{ARMAsmParser.cpp}::ARMOperand::addNEONvmovi16ReplicateOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ae9be674e0179e785d1e553d87229da10">anonymous{ARMAsmParser.cpp}::ARMOperand::addNEONvmovi32ReplicateOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a9fafc367cabbdce17ed971f70373c7c9">addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcduplexinfo-cpp/#ae79cf6180b23c65cbc9d3038da706629">addOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp/#a099dfc173455c7f27311d9c9cfa9cd62">addOpsFromMDNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ac9d379c622b78d95b1ecd4823ccb15ac">addOptionalImmOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a94b3cbab03d77b6119bf4ffb8dc5b21d">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addPAuthPCRelLabel16Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmparser-cpp-/m68koperand/#afc5faf5d7c3df5946555e8a6b9e76c33">anonymous{M68kAsmParser.cpp}::M68kOperand::addPCIOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a418048be5c0be53d70dec5000e5d4a7b">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addPCRelLabel19Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#acbecf14320c5f3c8b0156ccc7a9ee39b">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addPCRelLabel9Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ab862de3d6c862e4a282cd88b928b9de4">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addPHintOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#adfe7013951c0588b8fc9bfe4f635aba5">anonymous{ARMAsmParser.cpp}::ARMOperand::addPKHASRImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a6c9931ba36928eed8dcf2595c04ba489">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addPNRasPPRRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#afbe110673f6f1952a6e4e072d2cdd8de">anonymous{ARMAsmParser.cpp}::ARMOperand::addPostIdxImm8Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ad908815e815a5855ae31b84ba9a2720d">anonymous{ARMAsmParser.cpp}::ARMOperand::addPostIdxImm8s4Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aa7d60fa11f086b1e99ef10ce32ce5159">anonymous{ARMAsmParser.cpp}::ARMOperand::addPostIdxRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ac6ffe44b8dc8406f9792b89635c955b1">anonymous{ARMAsmParser.cpp}::ARMOperand::addPostIdxRegShiftedOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a874c0f5a1884183760a4e951c10874d4">anonymous{ARMAsmParser.cpp}::ARMOperand::addPowerTwoOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a5f2b9dd674ec50e06b69b98a88e00317">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addPPRorPNRRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#aba6f3578ca5c81d7b4fdfb0abd1dbfd6">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addPrefetchOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcoperand/#ab8bccadeb3e2ad7db97aaef06ad23f70">anonymous{SparcAsmParser.cpp}::SparcOperand::addPrefetchTagOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a5c9ebbec74b03775cfb34daaac7c2075">anonymous{ARMAsmParser.cpp}::ARMOperand::addProcIFlagsOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#abff9fa54c3161ee17b37acc2b5546ea8">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addPSBHintOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#ad9f45cd35c477b521daca23573ec3fcd">anonymous{VEAsmParser.cpp}::VEOperand::addRDOpOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a12210c238d328df79afbb1bf5b8d330f">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegACCRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#ac9f272922c818ce3d068c8da3b088e51">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegCRBITRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a261bc82cf89578d4cad2017373d2000d">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegCRRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a179ed03cc48e9a5569d66a7f44576942">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegDMRpRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#af033d8ccbf4172c8b4e289ddc6b645f7">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegDMRRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#ad5ff3b4938bbefa984a374310ba12b8e">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegDMRROWpRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a6b9fc1453025fe740abd2314b1edce41">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegDMRROWRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#ae660622f18164d2564fc611c31e5dfe6">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegF4RCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a46e8f65e73a8c1ec486feacbd11b8598">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegF8RCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#adfbd9f9bd8886de9cc1ce69aa19cecce">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegFpRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a4f7c8642744e66352d3f0484f6b9f291">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegG8pRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a6a926e9234ebdc634051a8cc4a884dab">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegG8RCNoX0Operands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#ad8399dd3de3aaf78884b2133c214ec5d">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegG8RCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a9fcff4b5ab16b5126b53e6221f72e4fe">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegGPRCNoR0Operands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#ab6d7068f5331beed20c505ac25bf75e6">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegGPRCOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#af5b3d3386caf9a9425af9379bae1f13f">anonymous{ARMAsmParser.cpp}::ARMOperand::addRegListOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand/#a87ea4b3846e4d8daf60afad674bb0fb0">anonymous{CSKYAsmParser.cpp}::CSKYOperand::addRegListOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a321bb283c53099e773b935a368f7f738">anonymous{MipsAsmParser.cpp}::MipsOperand::addRegListOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a49e5f673f43aedf3325832c920843cc7">anonymous{ARMAsmParser.cpp}::ARMOperand::addRegListWithAPSROperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a834f5cf804b7eb070f1fb2cd8498f7eb">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa66df54e14d6219d63e025455bfe52ae">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a645d5ef26292f8217b0a8822a8f104b4">anonymous{ARMAsmParser.cpp}::ARMOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-avrasmparser-cpp-/avroperand/#a090fbb87261517d19ba5d7dfea66f50e">anonymous{AVRAsmParser.cpp}::AVROperand::addRegOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-bpfasmparser-cpp-/bpfoperand/#ade951bfec69d3a224c97705ba13e1739">anonymous{BPFAsmParser.cpp}::BPFOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand/#a326ed8ed376ee7d1fcd009912f1baadf">anonymous{CSKYAsmParser.cpp}::CSKYOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonasmparser-cpp-/hexagonoperand/#a852b3c58b2b3267848e257b36ec634a7">anonymous{HexagonAsmParser.cpp}::HexagonOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#a938a6ff26f09f87928908d016aa961d8">anonymous{LanaiAsmParser.cpp}::LanaiOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchoperand/#a987343bc203c352faf89653f4e162c8e">anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmparser-cpp-/m68koperand/#a0e9b31563dafd04ae8a3f4c1114e8f75">anonymous{M68kAsmParser.cpp}::M68kOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-msp430asmparser-cpp-/msp430operand/#a52c6549504302b3b1bd7ef56e56b1379">anonymous{MSP430AsmParser.cpp}::MSP430Operand::addRegOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#ab2a8ec62f78c00b33f2cfe5c531366f9">anonymous{RISCVAsmParser.cpp}::RISCVOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcoperand/#a500c52eee2f18bf9ea0c6fd73b20a8d1">anonymous{SparcAsmParser.cpp}::SparcOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#ac5e94fab8baba89e96b19929550f2a21">anonymous{SystemZAsmParser.cpp}::SystemZOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#a6beb2a0c70d355c39054bb56daaf14dd">anonymous{VEAsmParser.cpp}::VEOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#aa8b46050f49c0070718cb24eaf4b44b0">llvm::X86Operand::addRegOperands</a>, <a href="/web-llvm/docs/api/structs/xtensaoperand/#a2d75e0733155cb6186ceb2829b3361dc">XtensaOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a625e5c93b568541975f28a4ad8746c4c">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addRegOrImmWithInputModsOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a1c7c494c84693e0715097e5d9bc23c31">anonymous{RISCVAsmParser.cpp}::RISCVOperand::addRegRegOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand/#af6301f276f11cc6a65a0fa29296aef93">anonymous{CSKYAsmParser.cpp}::CSKYOperand::addRegSeqOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a5c3ccc7ccc252771afe2c5992496a232">anonymous{ARMAsmParser.cpp}::ARMOperand::addRegShiftedImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#acec3b6c59168a1ad077d5aeb5e00a83d">anonymous{ARMAsmParser.cpp}::ARMOperand::addRegShiftedRegOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#ae8a5f120ec6a5723f1f2cfea052f096e">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegSPE4RCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a7ed33a86160f649e381a5e36d2ac0025">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegSPERCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a0746159c32e7ac0c99ed85d5ee328103">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegVFRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#ad06b4630ea0969c8091479fa22a5a5bc">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegVRRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#ae671f24372f1086564183e87fa417d64">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegVSFRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#ae738609c642f9c748c350ac993771f5a">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegVSRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a148f711934b9ce4ad92cedcc83542771">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegVSRpEvenRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a994642f0fa42d7b1ec9557c989e816e5">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegVSRpRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a084aa0e18d26956a3e8c10627318e6d6">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegVSSRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a95631286ee78d31fa6a320bdd65adf1a">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegWACC_HIRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#ad1fb4b2250fe4553fafb1966344239be">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegWACCRCOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a31034030d9e1080963a9033b29df4df8">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addRegWithInputModsOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#af18328b40cba50468c5a380fb0d86eeb">anonymous{RISCVAsmParser.cpp}::RISCVOperand::addRlistOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a4b06a7f3f9931e6b418f61f97b49ba69">anonymous{ARMAsmParser.cpp}::ARMOperand::addRotImmOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#abc4166605fc07257d0de56a87f4b3f0d">anonymous{PPCAsmParser.cpp}::PPCOperand::addS16ImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a9ff8a6126ecd827e2cfd20a38d93575d">anonymous{ARMAsmParser.cpp}::ARMOperand::addShifterImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ad007797dfd6b5c922a9818fd215aebd0">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addShifterOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonasmparser-cpp-/hexagonoperand/#a4664c509547eec1f1063959c2159a6b3">anonymous{HexagonAsmParser.cpp}::HexagonOperand::addSignedImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a275d93f01f3c0461c602869aa89a1fad">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addSIMDImmType10Operands</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a2cd3aa898829c8a5af0f9f8b6c0b369f">anonymous{RISCVAsmParser.cpp}::RISCVOperand::addSpimmOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a49468934edef8e57cda0f8aad36c57e9">llvm::X86Operand::addSrcIdxOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a6daf6a91dc04b3ec1d1c68ea065f8970">anonymous{MipsAsmParser.cpp}::MipsOperand::addStrictlyAFGR64AsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a8dc5d7e426b9a1e3d3d56db70401bde6">anonymous{MipsAsmParser.cpp}::MipsOperand::addStrictlyFGR32AsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#aab29a0e4b7912dd0fd49c5d2fcab3747">anonymous{MipsAsmParser.cpp}::MipsOperand::addStrictlyFGR64AsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#adbe61948d3299303dc25faf037775ae3">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addStridedVectorListOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae7695a0e4d476e4df011486af1bb63e8">llvm::addStringImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#aec0f3af336e424eb47c2d849c53a9c99">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addSVCROperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a32f086ffb95e53ca2321121772ddc00a">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addSysCROperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a536cdad3a9f844e78b6003550707b214">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addSyspXzrPairOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a58b5e0864f1dbb517a90f7e7a92946f5">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addSystemPStateFieldWithImm0_15Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a941d8c4c599c4ae4ed4da18d83b17b72">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addSystemPStateFieldWithImm0_1Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a9564fa88cecc4b7080be2865e0332713">anonymous{ARMAsmParser.cpp}::ARMOperand::addT2MemRegOffsetOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a10da3880ea18d94668327a3a49d65e25">anonymous{ARMAsmParser.cpp}::ARMOperand::addT2SOImmNegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a09aef2e9fa1cc6c6f71dc624d1a0158e">anonymous{ARMAsmParser.cpp}::ARMOperand::addT2SOImmNotOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a31a9eafb0a15b40afecf4445f06dc73e">anonymous{ARMAsmParser.cpp}::ARMOperand::addThumbMemPCOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ac7b319451b0950021d0225105ce5f61e">anonymous{ARMAsmParser.cpp}::ARMOperand::addThumbModImmNeg1_7Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a7b235456f07b4a6c7a67a7a21914ae43">anonymous{ARMAsmParser.cpp}::ARMOperand::addThumbModImmNeg8_255Operands</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a3d9f319c365afc3c199b8d1f179003bd">llvm::X86Operand::addTILEPairOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#ab4ff241ea58ce22b2fb48a3fbb7f1085">anonymous{PPCAsmParser.cpp}::PPCOperand::addTLSRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#acd2d8840bec9db8dc8d26c01be00f78b">anonymous{ARMAsmParser.cpp}::ARMOperand::addTraceSyncBarrierOptOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a25f8f8640a87306d856954ff636e3c54">anonymous{PPCAsmParser.cpp}::PPCOperand::addU16ImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#aade413b77f569da1d358d025182ced99">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addUImm12OffsetOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a3cc87770d7b78bdaebb4b74db9dfd78f">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addUImm6Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a2deb61ee90371c3718447dbe32d0d10a">anonymous{ARMAsmParser.cpp}::ARMOperand::addUnsignedOffset_b8s2Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a2287edccafae1d399ac9338429d056e9">anonymous{ARMAsmParser.cpp}::ARMOperand::addVecListIndexedOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ae6f6ab0591c1d91254dbb0cadecfca8f">anonymous{ARMAsmParser.cpp}::ARMOperand::addVecListOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a66aeb0ab4c553d5333da28689323bdaa">anonymous{ARMAsmParser.cpp}::ARMOperand::addVectorIndex16Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a3108dfa9b9ff61f1e1558e251947d377">anonymous{ARMAsmParser.cpp}::ARMOperand::addVectorIndex32Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a5c3fd94476330f0ba7c87ef6789de4c1">anonymous{ARMAsmParser.cpp}::ARMOperand::addVectorIndex64Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a199259455583be350d9673ed7275bdae">anonymous{ARMAsmParser.cpp}::ARMOperand::addVectorIndex8Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a7d1858fef112dddb614e924ca0c714b4">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addVectorIndexOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a4ec1a2d3550a48035bda06364865c408">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addVectorListOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ac6a4ccdc548344f69822f6914bb40e35">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addVectorReg0to7Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a69eda91bc353715ea7d51bc6d0d2e849">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addVectorReg128Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a1b12b775c6f9e800fb7fd722fd6a5e90">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addVectorReg64Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#aac4e8905e8ea71e68562f82797840d6d">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addVectorRegLoOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ae02dcfe544c083fe2a3949c50b389718">anonymous{ARMAsmParser.cpp}::ARMOperand::addVPTPredNOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a45c157d6c567f135196ef6a2c1571409">anonymous{ARMAsmParser.cpp}::ARMOperand::addVPTPredROperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a5515c4f1f3e9f0e04e83a787020af209">anonymous{RISCVAsmParser.cpp}::RISCVOperand::addVTypeIOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp/#a4386ffb2e777bd2b2f2a30e89decfebc">convertSSEToAVX</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmcshuffler/#ad7107b9902252656400f8760c3d657dd">llvm::HexagonMCShuffler::copyTo</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#adfaf977dc82c560bd265a68c807cd1a0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtDPP</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a38abdd95e7f5b6e9f4fc534bb392f8b8">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtExp</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a4547aa57e2b9056a73e2a8b26cc18d5b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOP3</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a81d4a718e3a11c1c3507fb28db101cf6">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOP3DPP</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#af30bfdcbe6574a1d0de2c2c59c1a8f18">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOP3Interp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#a950119e64de8aa5eb4bfbc37c275e8e1">Decode2RImmInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#a6efa6cced81498c9b0dd1c674f2b715b">Decode2RUSInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#a869e2b76735fa0bbd12f1ac4d87d045c">Decode3RImmInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#ae842ed2431c16fad8837b6eee2963d08">DecodeACC64DSPRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#ac7a3e2082a82dab7a8e4c002bec10269">DecodeAddiur2Simm7</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a01159155e0e1288fdee10e8077d347e4">DecodeAddrMode2IdxInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a748fded8b9c14e77783f32aa13b93af7">DecodeAddrMode3Instruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a1719003051d48a2e0a048a932e7ab2b1">DecodeAddrMode5FP16Operand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a674f8e4f3cc5c0f3c600feac22465ba6">DecodeAddrMode5Operand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a0d5ddcf46b56506e76a27912ea226388">DecodeAddrMode6Operand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#addca720009fe6ab83b7c148342b5f87b">DecodeAddrModeImm12Operand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a30705aebb6dc9b1e06d32247c8eba534">DecodeAddSubERegInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#aab4ee70b44f750a7bee01ca637c183e2">DecodeAddSubImmShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#adbc1eabc89010cc090b6ee89e7fbb61e">DecodeAdrInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#aaa816f0501f605b43ecfba1c1bbbc22a">DecodeAFGR64RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a8f6b082ac25a5bc7c68fa858b9ad7634">DecodeANDI16Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a2d3a2f957bed112cb510b5d278872555">DecodeArmMOVTWInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/disassembler/xtensadisassembler-cpp/#a48c971111ef9bca538397e06dc551e4b">DecodeARRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/disassembler/sparcdisassembler-cpp/#ad4b032c08b7153c8097eaeca022ece1a">DecodeASRRegsRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/disassembler/xtensadisassembler-cpp/#aba841cb45283de020bef4c9dad7b0eb9">decodeB4constOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/disassembler/xtensadisassembler-cpp/#aaff78ea44af63947549576618dc9d36e">decodeB4constuOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aeb91eb31d8c685c04eda5c8a94daed1c">DecodeBankedReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aba20f5ca65beb5f3251c3d98ec925cb0">DecodeBFAfterTargetOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ae32cf891f9f15262436c301330233bad">DecodeBFLabelOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a27e9d06f7e445ced766e065dd4acc072">DecodeBitfieldMaskOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#a3e39bcefbf5be0d67e8de78ee2031694">DecodeBitpOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a36413fd3a08347a6defae0004efa31ba">DecodeBranchImmInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/disassembler/xtensadisassembler-cpp/#ae750695a9783689206fd3324068b93ec">decodeBranchOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a77ab2a2732ef90d68ca7452ceb09cb3a">DecodeBranchTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a8dd71d5217f816af9a5862dd4166b3d6">DecodeBranchTarget10MM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a29a8f200f960b90b8f713ab6108cc8b2">DecodeBranchTarget1SImm16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a1109632992f889dc35741d9560fe9af2">DecodeBranchTarget21</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#aa6db6b74af461d3af0e9728e330c187f">DecodeBranchTarget21MM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a463fd929bdb01571b0d3bd2e214d7417">DecodeBranchTarget26</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#aa89a2cf630a68d313e4d8b39a09614a6">DecodeBranchTarget26MM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#ad73aa30d8165b2e31f91c1b2e9dda7fa">DecodeBranchTarget7MM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a86caf0679f2e2ed87c9403bdd566c589">DecodeBranchTargetMM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#ad2dc21f24745f289fc5e70691052ac9e">DecodeCacheeOp_CacheOpR6</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a4b99d1243931be14e14f7899b31458d4">DecodeCacheOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a179adc6990bb000f20132a4f4388ef12">DecodeCacheOpMM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/disassembler/xtensadisassembler-cpp/#aace6413645f6ffee13afbc5b78a67827">decodeCallOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#a58e18471d35b80cb8e96c3f614963a32">decodeCallTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a00fdbd9ffd6ffec77ca04831f19e9be3">DecodeCCOutOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a1368f2caa6861be3a936552c8d45d5d8">DecodeCCRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp/#a04341f61408b84cf6d7b2b0a0485e437">DecodeCCRU6Instruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/disassembler/loongarchdisassembler-cpp/#a3c7a592d7d7d0a0618034b1183d11112">DecodeCFRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a657d337e3cbb807cf7fae17582be5c60">DecodeCLRMGPRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a716f7b449a7cf38660b6f55858fc2308">decodeCLUIImmOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#aa5419c3888e7adeccf45d102b0dd09d1">decodeCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/disassembler/ppcdisassembler-cpp/#a900319c0f95042268d1650547cc3a78c">decodeCondBrTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a74fa34159304f5cc893d02ae5c7b8e87">DecodeCOP0RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15a9b5c3c2f47acc2bd00680d210f354">DecodeCOP2RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a7b3ca5b536ce1c58a39b853ea79de51b">DecodeCopMemInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a98404df0feb16d383e83461b3b9ac642">DecodeCoprocessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/disassembler/sparcdisassembler-cpp/#a517ec8162d032a3900d824b63c14cb1d">DecodeCoprocPairRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/disassembler/sparcdisassembler-cpp/#ab2cb60ed0bd0e9c7801349baa1a5b791">DecodeCoprocRegsRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a9cf0adb29491a93fac8fe34fd2a70356">DecodeCPSInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/disassembler/ppcdisassembler-cpp/#a2aeb7f3294daf80b26620225cb979478">decodeCRBitMOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp/#ad0a51db33ad8d7fcaf127661514016fb">DecodeCtrRegs64RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp/#a1eafaabd2bbbb4eb856e553cdca85b99">DecodeCtrRegsRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/disassembler/sparcdisassembler-cpp/#a174e2fe8043752fc8b0b96be6c3cc8b7">DecodeDFPRegsRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/disassembler/ppcdisassembler-cpp/#afd4bdc346f33431dc41b1a354823c358">decodeDirectBrTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/disassembler/ppcdisassembler-cpp/#a4b7927ad0c83d37babcfd5d1365f3f39">decodeDispRIHashOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/disassembler/ppcdisassembler-cpp/#aa02fd341367e3212e90de410d563bc9f">decodeDispRIX16Operand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/disassembler/ppcdisassembler-cpp/#aea6b30f8043c9f62a82cccd6bd221060">decodeDispRIXOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/disassembler/ppcdisassembler-cpp/#a6a67a5848b8b1e5d8c74d711ca9e9dd5">decodeDispSPE2Operand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/disassembler/ppcdisassembler-cpp/#a15f2bc0f640ac423b4f426da2168e1b6">decodeDispSPE4Operand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/disassembler/ppcdisassembler-cpp/#a9359f729b438d00da439752f4c6c6d00">decodeDispSPE8Operand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ae70fa52d51302599e262240b105ee645">DecodeDPairRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a008dfba65ec89733657403f21902152d">DecodeDPairSpacedRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aaaf4efcdb434e08e9196bec15ba0d9d3">DecodeDPRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/disassembler/vedisassembler-cpp/#a25e09a35ef1f2bfcc748f53f59d9e9f1">DecodeF128RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/disassembler/vedisassembler-cpp/#abd0f9e6edce55bf345b87ec220c724e5">DecodeF32RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#afcde096b672e6803bbd1dc93eecc6f65">decodeFBRk</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a169bff9f64a6601d3a0cb2316e8328ad">DecodeFCCRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/disassembler/sparcdisassembler-cpp/#aa6b0e7695d5f0ec75d8e6caf9209f6c4">DecodeFCCRegsRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/disassembler/loongarchdisassembler-cpp/#aebbae8434c9fe5eb3cb811493ef2dd3f">DecodeFCSRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a132b5510a16484e499d756f921457217">DecodeFGR32RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#ad762ebb8447883cc06cbcd8680b5e4d0">DecodeFGR64RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#af6fa5d60a1634d3b27cec9dd185b3e35">DecodeFGRCCRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#a4b551520c4790afaae3b181553ba8d0b">decodeFIOARr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#a976dffced44495ff439f2fc6a1f18037">decodeFIOBIT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#a975b91cc45a879ff0dbfb929f08e5a1b">decodeFIORdA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a81de44bb562b3312198ddb0bad029106">DecodeFixedPointScaleImm32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a217cf758bedf14d318ed065179308e72">DecodeFixedPointScaleImm64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#a1ac00c1502d95cb55fc0bce5eeade208">decodeFLPMX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a4a95f69f6c5c027fc46fa94fcd465045">DecodeFMem</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a5506baa3dada53698432a211bb3b4289">DecodeFMem2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a6d0d0fbc04194d17d3039dfd16666715">DecodeFMem3</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a01c88b37f10b149a379442567798c604">DecodeFMemCop2MMR6</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#aeaf09a414c497b64bc8882d42c77f7d0">DecodeFMemCop2R6</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#acfee40040ef185edd60491ec6e58687c">DecodeFMemMMR2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#ad6446846a7c3fa3ae63776aef7ed03df">DecodeFMOVLaneInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#afe0a70f7662c3f654851dbf51ff0fa4a">DecodeForVMRSandVMSR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#aed550a5b0a70ab51519b9fc5ab7ea4d9">DecodeFPR16RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a650d6cb5d9207463a2b420afaff1f488">DecodeFPR32CRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a83b8262d9a6235e7f0707e9eab6b82a6">DecodeFPR32RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/disassembler/cskydisassembler-cpp/#a83a19d129fd20824d7e6f08d2938c354">DecodeFPR32RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/disassembler/loongarchdisassembler-cpp/#a83a19d129fd20824d7e6f08d2938c354">DecodeFPR32RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#abdfa60ed3d8f1a5d58914d275709de02">DecodeFPR64CRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a3d490b02154a9841e63ebb6293176d26">DecodeFPR64RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/disassembler/cskydisassembler-cpp/#a58f0a4693a4eeb9e1b6795899ef6dce4">DecodeFPR64RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/disassembler/loongarchdisassembler-cpp/#a58f0a4693a4eeb9e1b6795899ef6dce4">DecodeFPR64RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/disassembler/sparcdisassembler-cpp/#a009e8c7d882053a25451365cf8e2100c">DecodeFPRegsRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#adc3617a91dd15eebf477e074cf7d57bf">decodeFRMArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp/#aac5afffddb9acd82d70ce8d4d86583ef">DecodeFromCyclicRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#a426cc36e610cb3fefd547ab4e42b8e62">decodeFWRdK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp/#a9deefe6628459b5cbdd92a375df7e139">DecodeGPR32RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a9deefe6628459b5cbdd92a375df7e139">DecodeGPR32RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/disassembler/bpfdisassembler-cpp/#ad5c79fab583fc33e74dccc9bbbbd4d33">DecodeGPR32RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#ad7b416d3b522e21404f78a1eab340af0">DecodeGPR64RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a4c8f426c0be76b0254c93325a82dc870">DecodeGPR64x8ClassRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#a47be71cc7bc04cdbc5dbf9e7e782ee5f">DecodeGPR8RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a3b485500cc5254e9953c767f6cceb455">DecodeGPRCRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a52685adb34dcf188c60c2ba51d525985">DecodeGPRF16RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#ac1ab8132c146da3c4dba810064ac142a">DecodeGPRF32RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a27af225c6500f75cbfd1ebc92bc64187">DecodeGPRMM16MovePRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a1b1ee55c95d75f26f7d9bce0304bace9">DecodeGPRMM16RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a5fa96194d9731f200e8a98eb57cdcdce">DecodeGPRMM16ZeroRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a0546fec39feecc98473391197580ae45">DecodeGPRPairnospRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a92a882831081786f843c7c6576f3f07c">DecodeGPRPairRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/disassembler/cskydisassembler-cpp/#a18e42ac75374f92b3e9f5f14f755b180">DecodeGPRPairRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aa0f92810efd603edbf301992b1851f4d">DecodeGPRPairRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#aedf05d82c0c624910fd446082c570568">DecodeGPRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/disassembler/cskydisassembler-cpp/#a7f80703df72d8a41fad7529e689eb784">DecodeGPRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/disassembler/loongarchdisassembler-cpp/#a7f80703df72d8a41fad7529e689eb784">DecodeGPRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a10af555eb22a4211be63902e97f575e6">DecodeGPRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/disassembler/lanaidisassembler-cpp/#a43536c19f988be653313601406fe7270">DecodeGPRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/disassembler/bpfdisassembler-cpp/#af7b9010056da73f57af323bbbdb484cd">DecodeGPRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#aef924b245b8e7087df6d747fdfd3810d">DecodeGPRSeqPairsClassRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/disassembler/cskydisassembler-cpp/#a7f1ef9a3fa6c2b715b6e1bfd6b0599f7">DecodeGPRSPRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#abb16e03485b2e8968e556823e58595df">DecodeGPRspRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a69e001cb85e959e85980c60d0557bab4">DecodeGPRwithAPSR_NZCVnospRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a3a72488c4dd03c87b64f1e0a25ff3ae9">DecodeGPRwithAPSRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a786e03096ad3a3a0022c0aaadc909fd6">DecodeGPRwithZRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a3064c510d24cadb88ee0ba9bd478b2d5">DecodeGPRX1X5RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#a96ceb8c8ee42497bea9bec3713184d0f">DecodeGRRegsRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp/#ad4fc6b486b45a0f90f1264af35348e56">DecodeGuestRegs64RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp/#a153a3a25ff23af1db43174d338d2156f">DecodeGuestRegsRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#ab3da98e8d7143c8431dba9e82dc2983b">DecodeHI32DSPRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ae96b7f8b4b8e35d28617a90604289b0b">DecodeHINTInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a9ea0f4d7f8af4d3e7996faea0732e153">DecodeHWRegsRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/disassembler/vedisassembler-cpp/#abb036651e7fc27cae114f365379a5f38">DecodeI32RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/disassembler/vedisassembler-cpp/#a6301475864ccf3cb814dc7853cf15341">DecodeI64RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/disassembler/xtensadisassembler-cpp/#a4845d69c5ba8461895bd17d3e6c8c489">decodeImm12Operand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/disassembler/xtensadisassembler-cpp/#a7287c48b7ff49189eda3e03080f21913">decodeImm1_16Operand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/disassembler/xtensadisassembler-cpp/#a1fc51e579d8087eb2b493c931698cecb">decodeImm1n_15Operand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/disassembler/m68kdisassembler-cpp/#afa1548b0f3e2e5c945f4e6ffa8a84de8">DecodeImm32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/disassembler/xtensadisassembler-cpp/#a9d9bbf30efee7fb26265433deeda6476">decodeImm32n_95Operand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/disassembler/xtensadisassembler-cpp/#a33c9ba1fe76d8759aaf0dbed2e164d29">decodeImm8_sh8Operand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/disassembler/xtensadisassembler-cpp/#a366117cb012fc9110a9425fe2c53e55b">decodeImm8Operand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#ae3b01de5051d0d08887e950b27fa6f2b">DecodeImm8OptLsl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/disassembler/cskydisassembler-cpp/#a87256d045a3d16e902931658b737882f">decodeImmShiftOpValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/disassembler/ppcdisassembler-cpp/#a2bffa368d9dd2952529ec79eb82082dc">decodeImmZeroOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#af2e78b5e65ffb6775845fc0212d3145b">DecodeInsSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ad0543413122f30a8c27dfc39fa6e3a38">DecodeInstSyncBarrierOption</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/disassembler/sparcdisassembler-cpp/#a71d42e7809cbdcd913cbebdc2d27ff5e">DecodeIntPairRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/disassembler/sparcdisassembler-cpp/#ab7c8b2ad6feda021ec9b6390f7c2ee26">DecodeIntRegsRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a81a160da998ad8c220a42b326635c347">DecodeIT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/disassembler/cskydisassembler-cpp/#a4d39989f847141bc81ba64c5bc4ab820">decodeJMPIXImmOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/disassembler/xtensadisassembler-cpp/#ae2e785add5cfc4ebf4227b0b5a0477d3">decodeJumpOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#ae70463d5ebd44edcb0f55e8f71ea13cd">DecodeJumpTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#adbc74232b42622af980395b81c707b63">DecodeJumpTargetMM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a12f0fe80f72fa867a56f7656bc69ba82">DecodeJumpTargetXMM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#a34fffc378f5dce35182c9d7d6d90dc91">DecodeL2RUSInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/disassembler/xtensadisassembler-cpp/#a37d2897fee1959befa263fd3c1999632">decodeL32ROperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/disassembler/loongarchdisassembler-cpp/#a40307e3fb75594355b766090df679864">DecodeLASX256RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#afbc53e43e60687c280c643165c8c8a16">DecodeLazyLoadStoreMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#a6ac16eb0f31fc1b885617e76513356a1">DecodeLD8RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp/#aa7956d4781c08702515a296790075c9d">DecodeLdLImmInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp/#a1de0eac0bd3c65f8050ee57e0a004867">DecodeLdRLImmInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/disassembler/systemzdisassembler-cpp/#a8e7afaa00e8d7d683064a09415727e90">decodeLenOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a6a73a7492fd248ce81ca1d8777e9ecd2">DecodeLi16Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#ab311edf9208c4ecffd59d070b28acc9a">DecodeLO32DSPRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a5226be2f481d1b712b374a6106eb05e7">DecodeLoadByte15</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#a2cb3aca8e9408d30eaf90bd4c70e65e4">decodeLoadStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a46b59aec241e0564ca44770f25f2ec71">DecodeLogicalImmInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#afecebd0151d705a1f451129515690010">DecodeLOLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ab8b53ae5388a8928f477d9bd603ec7be">DecodeLongShiftOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/disassembler/cskydisassembler-cpp/#a75f0da4f05d83defe9d306ff7787de68">decodeLRW16Imm8</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/disassembler/loongarchdisassembler-cpp/#a8c62c95b50417b02163b9100f866dff1">DecodeLSX128RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a6d57b9fcd315db5667ba79c86783cd5a">DecodeMatrixTile</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#adad48d9cda0a32212abf5e19c1a4dada">DecodeMatrixTileListRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#af6be4e043e94b84a2f41ca62f43e2c33">DecodeMem</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/disassembler/xtensadisassembler-cpp/#a03a7f7a66ba9ba5e14468db9fc432ca3">decodeMem16Operand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/disassembler/xtensadisassembler-cpp/#a3a5e9a70b730d8ac99ac4b2be373d037">decodeMem32nOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/disassembler/xtensadisassembler-cpp/#a5768903f0a287814cbee9a4df4106b04">decodeMem32Operand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/disassembler/xtensadisassembler-cpp/#a7e1d66d36247f5d06a4cb64348641fe8">decodeMem8Operand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a7cc9374fea73f7cc720fb82fc120ca84">DecodeMemBarrierOption</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a0846cbb46ed7dfb0fe8963f57e4e450c">DecodeMemEVA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#ac78415ed431af9ea8e86360f6ae47a94">DecodeMemExtend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#afc5d4d8f5a682f4c0ea86db0681099f0">DecodeMemMMGPImm7Lsl2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a5cdc282caa88d2f28ce4792ad53d4471">DecodeMemMMImm12</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#ad2f3f439d59b03ed49013e7aeaafd701">DecodeMemMMImm16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a97875810a5d927cedd5b85ab368caf67">DecodeMemMMImm4</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a2a99cbe29aa769217b2e94ed6248575e">DecodeMemMMImm9</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a7bd5fcbe5963096279a236cbdf87e675">DecodeMemMMReglistImm4Lsl2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#ac3bab0bdce9c5d10efa38d46bd79271c">DecodeMemMMSPImm5Lsl2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aee22f63177a59f1c073fc689b38933ae">DecodeMemMultipleWritebackInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/disassembler/bpfdisassembler-cpp/#a337776342a5c26b5f50cb4186114622b">decodeMemoryOpValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#abf5533403c67de41a3b98d96699419ee">decodeMemri</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp/#af48dd6610db11d5275ece9154300e514">DecodeMEMrs9</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/disassembler/cskydisassembler-cpp/#a9b0afa7a6ea53b6c262cfc2c84722e15">DecodemGPRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/disassembler/vedisassembler-cpp/#ae238e3463e82b7b4b67c04c9797c40dd">DecodeMISCRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a3fad9a3a6a6f166a13d42ea4ce4046a6">DecodeModImmInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#afe70774421a4b9960ec659c9c088e2ad">DecodeModImmTiedInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp/#a5920b44a0571dd783dc3257b3d06ec23">DecodeModRegsRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp/#a347760ad409026bf174cb84186f2db33">DecodeMoveHRegInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a472d51a3167cd8c4a324627ccb3d063e">DecodeMoveImmInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#aa330835a309ee0a4f26cc2c67f0d3547">DecodeMovePRegPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aa3c5a904bdb1d7e9f693e63db0454028">DecodeMQPRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a677c767a9bda021b84fb9746f3286acf">DecodeMQQPRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a50c406172cc0588e52496edf179ceac5">DecodeMQQQQPRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#af34944ff20fbc4b23ad91c672dc071c9">DecodeMRSSystemRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a9e6956193b81787eca9d4e84fa07d90d">DecodeMSA128BRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a93216f363b261e0c45c4fbb3c88f3b44">DecodeMSA128DRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#acf3299d43f5d2753e093d84f0d138c07">DecodeMSA128HRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a38cb0684cd1dac98218884dbd1ffbb85">DecodeMSA128Mem</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a461387c78a2a6c203ecbd9979f651a06">DecodeMSA128WRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#ac9553ad4a854ada48e9219742b3829b8">DecodeMSACtrlRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ab4afad02e282888ac65f575a3288b53a">DecodeMSRMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#ab43bf4c7c1ec2adef80d921fd1c24c91">DecodeMSRSystemRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aaa973fa80051d521ca126e6baec9b849">DecodeMveAddrModeQ</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aa6165f97e90eaea7675b635e2d2a1a3a">DecodeMVEModImmInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ace68fb9d35b1e3f7c97175ebeb16e386">DecodeMVEOverlappingLongShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a2a34de4d35269c85641be94e7958f715">DecodeMVEPairVectorIndexOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aec419b455f0b73caa44637f09817ec4f">DecodeMVEVADCInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a111ed526e6e5818e4bd6f7c459c883ab">DecodeMVEVCMP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ac31edd9f4eb883611f651f89005c8878">DecodeMveVCTP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a0dd59a3d5dbf53a9ccf82fa0463a4f6d">DecodeMVEVPNOT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#ae16368dfa2470a873994b0fe3944f232">DecodeNegImmOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a03d54559851ae68e67660bdd39fc0f83">DecodeNEONComplexLane64Instruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/disassembler/cskydisassembler-cpp/#a815d13fbf951ab56c7866d89434a43a4">decodeOImmOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a64316e7222c5bfbf7c8ad81567f8cd0b">DecodePairLdStInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/disassembler/systemzdisassembler-cpp/#a75f4ac701a183d154f7798bf5db43311">decodePCDBLOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a805d26616ccd931aee997c600ff2a046">DecodePCRelLabel16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#abe725b290fe0d33be6a7483438c37794">DecodePCRelLabel19</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a9afb1303f5dc3819057cec727c878bbe">DecodePCRelLabel9</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a012fe853ebf588228df90208129eaa87">DecodePOOL16BEncodedField</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a968efe31b652445ecd031c2d15a1ae31">DecodePostIdxReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a45647e429621e3d8ae8f2d674d9b9d8e">DecodePowerTwoOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a774f1ac41b6d226f946b314616ae6ec5">DecodePPR2Mul2RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ad22d00715292f5cf5d09380b15cb6189">DecodePredicateOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/disassembler/lanaidisassembler-cpp/#ab932e0ade3b042003eb703e6cbd1645d">decodePredicateOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#acbe39bfbca107299d4d4cc87042ae108">DecodePredNoALOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a3d785e380546672d88587a25478a3dc4">DecodePrefeOpMM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#adf13850bfdcd4986cc6b21f227468936">DecodePRFMRegInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/disassembler/sparcdisassembler-cpp/#a010d6e25942dccead008c0cef853b4f0">DecodePRRegsRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/disassembler/sparcdisassembler-cpp/#aff3e7695c4f78d95357eeacbc558b67c">DecodeQFPRegsRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a19413e51b699e49efccf29be3acce8c9">DecodeQPRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/disassembler/m68kdisassembler-cpp/#a807fbd4d93fe4edc17d24610bdc465e8">DecodeRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp/#a8199e9ace5520235a9e3717a7cb5992e">DecodeRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/disassembler/ppcdisassembler-cpp/#a084584c6167990eece3ec663f759829e">decodeRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/disassembler/systemzdisassembler-cpp/#af01d9dae0f312bb738d03133e2dbff38">decodeRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a0e63c91ecc76f4cc56a896dd3ab65f38">DecodeRegListOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#abf0a19aed27d5d513d9891ae3d48bc31">DecodeRegListOperand16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/disassembler/cskydisassembler-cpp/#a6d19a9c5c5e3d0b520f644824fca2fc1">DecodeRegSeqOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/disassembler/cskydisassembler-cpp/#a9816b2ec2408b44c34f866fd38b2b0f6">DecodeRegSeqOperandD1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/disassembler/cskydisassembler-cpp/#a7f045b84588919a766964ff5cb9e68b7">DecodeRegSeqOperandD2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/disassembler/cskydisassembler-cpp/#a7a8011f055877d0a3d1fdbd59fa13bba">DecodeRegSeqOperandF1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/disassembler/cskydisassembler-cpp/#a40f5446f80030bdfaa2d67cfa4a18d2b">DecodeRegSeqOperandF2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ae84c6d1dc0851a81d0493fe6c170dd69">DecodeRestrictedFPPredicateOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a48520ba7e75f202550562068b55c99e8">DecodeRestrictedIPredicateOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a9dd1704cba552d046509c8838b704dfa">DecodeRestrictedSPredicateOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a5f297cb2dc25c4e7eabf1db56921c74f">DecodeRestrictedUPredicateOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aedf86c5895d19485c6219652fdf5bd3d">DecodeRFEInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a27d5f895980d5049799b32f5d4161d4e">DecoderForMRRC2AndMCRR2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/disassembler/lanaidisassembler-cpp/#a4c912311e2594387fe7d03e6346a0d1a">decodeRiMemoryValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#a96b22eb76283ea544bc9c7be79086d62">DecodeRRegsRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/disassembler/lanaidisassembler-cpp/#a2530547533fd87c8f94a6a72164cf4de">decodeRrMemoryValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a4c43a77f2033f99401c30c2f7253e197">decodeRTZArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#a10ccb4290c3d7bd10eec473c054c3612">DecodeRUSInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a4fb3fc8c5d55a1d56d78a9df5741397b">decodeRVCInstrRdRs1ImmZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a19d0efeb7b5278d64f33d0423d2bd8ac">decodeRVCInstrRdRs1Rs2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#adfdd862b7dee084ab03c01966116902b">decodeRVCInstrRdRs1UImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a90702c263ae4dbf20b0f59ef58f13f7c">decodeRVCInstrRdSImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/disassembler/loongarchdisassembler-cpp/#a264527a1e305cb85db460cfc23cdcf9d">DecodeSCRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a4ee0d80338b8a6c928f2322e35a21c37">DecodeSETPANInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/disassembler/cskydisassembler-cpp/#a08b3fcf8de0230910f0c64fd98bfd81f">DecodesFPR128RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/disassembler/cskydisassembler-cpp/#a45214aaca4fd79f22a331e832b76523b">DecodesFPR32RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/disassembler/cskydisassembler-cpp/#a87861f2ce28c57ef81bc8ecb48fa23b7">DecodesFPR64_VRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/disassembler/cskydisassembler-cpp/#aff59f4463fca8356500d70148aa5c9a1">DecodesFPR64RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/disassembler/cskydisassembler-cpp/#a7ed111d853565b3cb84444bfc8e6eba4">DecodesGPRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/disassembler/lanaidisassembler-cpp/#aad4e6692a45bcddab57965902ebb6c3f">decodeShiftImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a127c4779b391afeaa826a0272fe6ee1c">DecodeShiftRight16Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a3b44316902aac6d67323437da5d1df1b">DecodeShiftRight32Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a234caac51a63392a941e589b9e0a2dda">DecodeShiftRight64Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ad42f5559ebf4110d8a1d34d58b079997">DecodeShiftRight8Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/disassembler/xtensadisassembler-cpp/#adc1efd7be812311ce73095c45cf003ef">decodeShimm1_31Operand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#acf5f17b8afe036660d97ba9f2e254c31">DecodeSignedLdStInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp/#aace1f9726acd8d551604f23b4a2181a5">DecodeSignedOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a6eaaa7135c4d4d1336c04d5c53b31c53">DecodeSImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a6bb5a4fe2dd2871aa0b0407277291ce9">DecodeSimm18Lsl3</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a026fc24df0672a9950dcbf77264e7e05">DecodeSimm19Lsl2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a249776a60fa6ebe72af4a50fdb2adfd6">DecodeSimm23Lsl2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a53857c68e589210e0c059cb970577183">DecodeSimm9SP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a27b716d926aba8dc616ab944809a79a6">decodeSImmOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/disassembler/systemzdisassembler-cpp/#a278fbeb45c0401ee58be530a8fef0a3b">decodeSImmOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/disassembler/cskydisassembler-cpp/#ae0e642945615671f3935a33e6611341b">decodeSImmOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/disassembler/loongarchdisassembler-cpp/#ae0e642945615671f3935a33e6611341b">decodeSImmOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/disassembler/ppcdisassembler-cpp/#a6dac5db583b83e0bbab26f05bcd02600">decodeSImmOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a5a9cf05b29f34e3c312f5fae3427022c">decodeSImmOperandAndLsl1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a20657527835c5d8aa804f76dea8f5e15">DecodeSImmWithOffsetAndScale</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#ad9f65cebca060e894d0162012d4e6806">DecodeSimpleRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp/#a746079c286d5e7dfd559520006cdbc82">DecodeSOPwithRS12</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp/#a2197fd22b3d4ec0302f9cc79d12a3402">DecodeSOPwithRU6</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a1742de415bfaad8eb71b09f017c248a9">DecodeSORegImmOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a20e9fffc7ece71cc090e060083bba8a5">DecodeSORegMemOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#af9c9828e7054789502f5b58a859a989e">DecodeSORegRegOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#ab357e7edc71c6ac759f843c8a4d2e525">DecodeSpecial3LlSc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/disassembler/lanaidisassembler-cpp/#a3c110cd89ae07dc4a4a8f88fd316938a">decodeSplsValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a4d6d306c72aa6a70b9ebe66b9c3b448d">DecodeSPRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#adf09a5323307968e37109f843ad1c115">DecodeSR07RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/disassembler/xtensadisassembler-cpp/#acc1a655bd3be92cebaad9f904e63b1d8">DecodeSRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp/#ad49072913256760cce9a52ad08e123a6">DecodeStLImmInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#aa4f2d6ca385a9cc2845fd4c4083d2034">DecodeSVCROp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a80adcf933fbb41ac1f7bbf1bb0395c9d">DecodeSVEIncDecImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a8791e99741e918b4a6dd4de52c238d04">DecodeSVELogicalImmInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp/#ad51be7b10c11546e324f87e8f9a418b6">DecodeSymbolicOperandOff</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#ae431d705509fa5518935c0316e0f7f75">DecodeSyncI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a4d85eac7627a2960509a89db115ee3ea">DecodeSyncI_MM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#ab67a4db8c7b5eee3b7e1a2285a9b04ba">DecodeSynciR6</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#ad5c7a59494e06cea0b126259e25b8402">DecodeSyspXzrInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp/#a581de7d5eb00d0a9a3a4783a68b06604">DecodeSysRegs64RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp/#a825fce70e335e0e3182dbfe04d328e66">DecodeSysRegsRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a7b91a2080aef66711a9a59c0fc2bc78c">DecodeSystemPStateImm0_15Instruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a47610006b53563d90c891dbb2f2a21cf">DecodeSystemPStateImm0_1Instruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a01bd6143a4a986faffacd16015813009">DecodeT2AddrModeImm0_1020s4</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a02d69d029e1221f31502f0ea27919fce">DecodeT2AddrModeImm12</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ad2d2ec79ae9dffdbfb48ad8d5127545e">DecodeT2AddrModeSOReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a5686943937ea2fcb33898d72abca31ef">DecodeT2AddSubSPImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#af29ab03d6050c790ddb78a16ec44a9c8">DecodeT2Adr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aef9eb2cb70ef337f38412e1abbf0dec1">DecodeT2BInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aeb6809e431d0d7be5db2100259b7a938">DecodeT2BROperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a7e582cac45ed6985921e4bb6a2f7d648">DecodeT2CPSInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aded3e7ff6d138e828bcbcce6cb174baf">DecodeT2HintSpaceInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aaaefc503e2bd8ba73867b482991fe437">DecodeT2Imm7</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a45d2abd1294bda98bd14f6c67dacf5a3">DecodeT2Imm7S4</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a90d5418f2e93a2642201029e6ed6a451">DecodeT2Imm8</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a9b92c2d4bea9661967f516f54a39cf71">DecodeT2Imm8S4</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a18ec82d05c3fecd8d313d76aa6cf4d88">DecodeT2LoadLabel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a3d6b4d56448a550e780bcc286defca12">DecodeT2MOVTWInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a9ae92049f767d90a23bb08ac51e6f4a9">DecodeT2ShifterImmOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a07acaaa223de35e67d23b43c9b5fb815">DecodeT2SOImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#acb06a192e3269a823f47cc6117e6b8e7">DecodetcGPRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a853a2c1c2fc5c033da682c5cbbcfd522">DecodeTestAndBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#af3be70a7716c3835f3e3762836706d07">DecodetGPREvenRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#af5849cef21e2e3edfce5cf30f6a1c12b">DecodetGPROddRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#ac34ad1dd79456d25b144337df1117ef9">DecodeThreeAddrSRegInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a43c40604d096e3bab514a393fd825d5f">DecodeThumbAddrModeIS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a2840eccb932fbfb5f1b971418defe0b9">DecodeThumbAddrModePC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a85cff0c6b2dde1fc019651dd70957cfa">DecodeThumbAddrModeSP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a9d49e57d960810a6cdebef656a7d12c1">DecodeThumbAddSpecialReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a9239d3121cc71b12f5345bd426bdd9ac">DecodeThumbAddSPImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a4ff9913a6a8ee09237b7bdb7350f8758">DecodeThumbAddSPReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a7e69a20308151fd035fa4fb846286822">DecodeThumbBCCTargetOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a6ffb59bbbc1842e8c8a269d887115bf2">DecodeThumbBLTargetOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#af1af6cdc0d6226a5bdea6bce3117bf2a">DecodeThumbBLXOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a47d296d739fade98971ad5b86be667a6">DecodeThumbBROperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aabb5f2db0a632ca534c9df07816fd978">DecodeThumbCmpBROperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a9bcf5304e1403680817795f4f0cfbe3a">DecodeThumbCPS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a406420d233c9c21f4c1bfbc6328c7651">DecodeTSBInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/disassembler/xtensadisassembler-cpp/#a587801e4c6457d04f9deaa9878f7057e">decodeUimm4Operand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/disassembler/xtensadisassembler-cpp/#a9d878bf2d6527daaf67b0665b0f9d752">decodeUimm5Operand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a1c3fc03976ed07efe25c98fabf3413a2">decodeUImmLog2XLenOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a7a39f226077952a684f8169aca4f3279">decodeUImmOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/disassembler/systemzdisassembler-cpp/#af11b662d90e080f153bb4ab5f497c530">decodeUImmOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/disassembler/cskydisassembler-cpp/#a76dc4f397a4c050cc1d7e3c82a3380e9">decodeUImmOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/disassembler/loongarchdisassembler-cpp/#a76dc4f397a4c050cc1d7e3c82a3380e9">decodeUImmOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/disassembler/ppcdisassembler-cpp/#aab61bd085f1040a2055be7dad812c7da">decodeUImmOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a5b723faa4ac16e56220d04ccc6992414">DecodeUImmWithOffsetAndScale</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a043df6b81de57c6d77e6753487cb9ca9">DecodeUnconditionalBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a4d0969e62a9d55e7a6b81658aaac2841">DecodeUnsignedLdStInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/disassembler/vedisassembler-cpp/#a088edc17929842ef4841bfdcd36d5369">DecodeV64RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a78802c522ed764cedc1bafcf628dd154">DecodeVCVTD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aa9f76b11681b7d483c31d2108af81914">DecodeVCVTImmOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a9e5902642b306bad7e557cc0030a8c3b">DecodeVCVTQ</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a9524d8d16b066a213bd3f48055fc9275">DecodeVecShiftLImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a88dabd0bc713d4a6ad2dfee37fff7b06">DecodeVecShiftRImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a4bc58a6a4cc485df54316ee63961494a">DecodeVLD1DupInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a88cfc4461fad680d4d3b2dca75c06462">DecodeVLD1LN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#adbfb7c834c41c75925284ebcb3e30a43">DecodeVLD2DupInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a55963f98bd8421645c77a3bc2497015d">DecodeVLD2LN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a7bce2d579f601f86a9e4746623988063">DecodeVLD3DupInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a989cc7ee36e295c4132740950cd1aec8">DecodeVLD3LN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a53b3d214dc2e26fcfb82d711dd7e897f">DecodeVLD4DupInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a241bba0734ea7a40a6fb2b7cfc63f72e">DecodeVLD4LN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aa46c26cc972273e7463a3ebe3a9cedad">DecodeVLDInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/disassembler/vedisassembler-cpp/#ab4e01b6d719158aa7871aff1780be2bf">DecodeVM512RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#af066fcdb24a63946572929dd19609eb7">decodeVMaskReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a41d6edfa220d2050c7c245dd1e5e5fec">DecodeVMOVModImmInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/disassembler/vedisassembler-cpp/#ac9e514c637e3b4a854e5bbdc335bb81e">DecodeVMRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#ab5b7c057ba502808b645d1c15f9c09d3">DecodeVMV0RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#acdaacd5f1068bbea11517190346d652b">DecodeVPTMaskOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a924863953fe38c5075ca2987a071b0b8">DecodeVRM2RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a88ce4565edd9e27d57d87c13811d631b">DecodeVRM4RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a8523dd0b2a00a817ecb488a195ea33cb">DecodeVRM8RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a91950ccc10b9478f3b9a2fb798a9abfe">DecodeVRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aea8ff3695bbef57d56a2d23873b029bf">DecodeVSCCLRM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a0d6877e515e068fc4847049790f9db94">DecodeVSHLMaxInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/disassembler/ppcdisassembler-cpp/#a0ea99b63431f736604494e8436a12a3f">decodeVSRpEvenOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a585fe45145ba2dfdfbddf6544fbcc853">DecodeVST1LN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#acc2c3a559d83ea0fc94b5cd90fa6b774">DecodeVST2LN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a5bc2379dda1ba55eae95c132f3cc5e99">DecodeVST3LN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ac5d71fed959a923e986adb309f260ea9">DecodeVST4LN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a83aef7e6f90ca5e44f3927132a133315">DecodeVSTInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a8ed86ab442732ed8bfdbb259af9edfc6">DecodeVSTRVLDR_SYSREG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a658e7d113d0172f3dad093f32851616c">decodeXTHeadMemPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a1704cc291207f2f9935b995386e3e0c9">decodeZcmpRlist</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a9e6acb172bd3caa13c6927593148a0f0">decodeZcmpSpimm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a7025267acc36901a12f64e8db186b092">DecodeZK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#ab5dbfcd8759c243a87ae147779edc32c">DecodeZPR2Mul2RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#aa83dd17920440747c9af027eeec44dbd">DecodeZPR4Mul4RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a068c567d31464b292cd4a254e0cca751">DecodeZPRMul2_MinMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a1eda4c3f6c0329af244778af7bd699fa">llvm::HexagonMCInstrInfo::deriveDuplex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#afef5615be55fa8a93b6a92b8c787aad0">llvm::HexagonMCInstrInfo::deriveExtender</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcasmprinter-cpp/#aaaec30cb8a497bd67f31b3a32d5e2626">EmitBinary</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp/#a3063fa549eed52187dad621a5646bf4e">emitBinary</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp/#a5e94665a52b9daea5f22841f60760ab2">emitBSIC</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a1760c43fadfe8ae62e75e7debd68fad5">llvm::MipsTargetELFStreamer::emitDirectiveCpLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#ac108b4db53de8c6f7f8d905f4db03722">llvm::MipsTargetELFStreamer::emitDirectiveCpreturn</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a7ff09aba59d7dcc5dd800735494b14ff">llvm::MipsTargetStreamer::emitII</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#acdf3f4cb6342e67c42191cf29984df97">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppclinuxasmprinter/#a4123a254ab36bc97c087331e6cb38665">anonymous{PPCAsmPrinter.cpp}::PPCLinuxAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#ac09670e222cb6d4948119b60fd4f3e6e">llvm::ARMAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#a922dc7b28cc9b8895585a602d941b04f">llvm::HexagonAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp/#acc5831f0eaa7631d3dfeda1204813426">emitLEASLrri</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp/#a58c5b4dc239b80405dfe9abdad268555">emitLEASLzzi</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp/#a3812bc25ff6681233201a4c9187dec75">emitLEAzii</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp/#a9fd6a23b5a2ab5b7dc3f202529479a80">emitLEAzzi</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#a95377c6337c8286d00bfd8a2ff437029">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::emitOpLabel</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a3227bdb52724365458abe5cb94be8766">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::emitPtrauthAuthResign</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a17a879a7a14ff0a9e63980908bc502d9">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::emitPtrauthBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a49ba9fd9824c6910d3f66c1ae4469891">llvm::MipsTargetStreamer::emitR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcasmprinter-cpp/#aad58c68abd46a14fdb1cac72bc5b863a">EmitRDPC</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a09e7b7665f50b4338f746a50f6a454b1">llvm::MipsTargetStreamer::emitRRIII</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#abbac3ade2206cc952cf43e2ca4566201">llvm::MipsTargetStreamer::emitRRRX</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a8b10941b3ac644fb3508bc6cdc8aa6d5">llvm::MipsTargetStreamer::emitRRX</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a2b33055c2d9eb274c2d980428f7a1c24">llvm::MipsTargetStreamer::emitRX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcasmprinter-cpp/#a52cbef23880440f08e43fb0818d3ffb4">EmitSETHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp/#a28d8abbfedd338d44a39887939340b91">emitSIC</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#a4562e6672b8b09e99e8bc49651b20e0c">llvm::HexagonAsmPrinter::EmitSled</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp/#ad635fb338c113f5de9924ceeeb507dca">getCompoundInsn</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstrinfo/#ad900da7454c78d54e25c6fb062c851e5">llvm::ARMInstrInfo::getNop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77ac85fa1d774b4d1f5a064e1b8ee8c3">llvm::HexagonLowerToMC</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#aee072cd97eb6d078d122611833049aa6">llvm::HexagonAsmPrinter::HexagonProcessInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#a3b244792bc2277f0800d9e15c2eb935b">llvm::BTFDebug::InstLower</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a74bd673118d2cbb40d776bb1726d4c95">anonymous{X86MCInstLower.cpp}::X86MCInstLower::Lower</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#ab248027e3bae0d1e5d3a20d8846edb9a">llvm::AArch64MCInstLower::Lower</a>, <a href="/web-llvm/docs/api/classes/llvm/arcmcinstlower/#a80e51b3f855ed903861b58cb8b00e693">llvm::ARCMCInstLower::Lower</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfmcinstlower/#afac72182f48f1b144922b37546a66778">llvm::BPFMCInstLower::Lower</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcinstlower/#a282478f8e3bf69d2fef9f8ce12644ee9">llvm::CSKYMCInstLower::Lower</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaimcinstlower/#ada3cf8f523e66ab2658f5c59e0727ed8">llvm::LanaiMCInstLower::Lower</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kmcinstlower/#aaa1ed5df03c02ae5e378bd14aee41269">llvm::M68kMCInstLower::Lower</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcinstlower/#a2a3cc3a492be3cc4387ef82e0d8dfe0e">llvm::MipsMCInstLower::Lower</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430mcinstlower/#a0da8c32a960fd10c2f6cb034954b3924">llvm::MSP430MCInstLower::Lower</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoremcinstlower/#a8f709fd6f997a78bea1acde1c948f9a1">llvm::XCoreMCInstLower::Lower</a>, <a href="/web-llvm/docs/api/classes/amdgpumcinstlower/#ae4383929e7fb1cdba8806d6f68af926b">AMDGPUMCInstLower::lower</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600mcinstlower-cpp-/r600mcinstlower/#a29af2a29429bdbd8546d4cb8b78daacc">anonymous{R600MCInstLower.cpp}::R600MCInstLower::lower</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvmcinstlower/#a6d050903b1d4eb1403389e782f6cec1c">llvm::SPIRVMCInstLower::lower</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmcinstlower/#a4d03b8ca910d6fc73430a83a0ebb2d74">llvm::SystemZMCInstLower::lower</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblymcinstlower/#a62aefd0bed5ed9cd5a154bf4d4074a22">llvm::WebAssemblyMCInstLower::lower</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzasmprinter-cpp/#a431a7ed17e60d8c815ffab3efbbe0a4b">lowerAlignmentHint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9f28245e9d46c733c5ac7db5a5fbe27e">llvm::LowerARMMachineInstrToMCInst</a>, <a href="/web-llvm/docs/api/classes/llvm/avrmcinstlower/#a984878b12749e1f06574b379915f8524">llvm::AVRMCInstLower::lowerInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a270b87ff1685fe3629f8ad9ed69d7101">llvm::lowerLoongArchMachineInstrToMCInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a75665dd8dc7cd6ec1cb1f06a34ebb042">llvm::LowerPPCMachineInstrToMCInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp/#af3b87eccd7dfd84ba438253014223161">lowerRISCVVMachineInstrToMCInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa50085956029a8612301d43b0c2784f1">llvm::LowerSparcMachineInstrToMCInst</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#a3ee8d8bf08607adec1b75768f39fa399">llvm::XtensaAsmPrinter::lowerToMCInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b171d9e10d6ab46824855e1cc83e737">llvm::LowerVEMachineInstrToMCInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/asmparser/hexagonasmparser-cpp/#a9d6cfc8fde9d13ec8da254c0493603ed">makeCombineInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#aef83676a470a77d6e089737fb024de94">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::outputAnnotations</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#adac6a6f0dd9ecdd7b774da11940ce88b">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::outputDebugSourceAndStrings</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#a26a1086f0aa442d022ef86a57757ef94">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::outputEntryPoints</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#afc046e9fee2ff69250264feef8baaf15">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::outputExecutionMode</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#abc68a425d6211a1b46e2df470bf12439">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::outputExecutionModeFromMDNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#add0594bfc35119c8d898c51bb3697823">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::outputExecutionModeFromNumthreadsAttribute</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#ac9d0742eff167655206896feab35cd4b">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::outputGlobalRequirements</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#a996dc62cedd72ad61d739065da84a232">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::outputOpExtInstImports</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#a4f4a667381f5644b8c90d6e9c78642b9">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::outputOpMemoryModel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a2cb3beb5a3e71a3b94697f7083f2e4be">llvm::HexagonMCInstrInfo::padEndloop</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a97d0066eae87ce228a58774409c88425">llvm::ARMInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmbackend-cpp-/amdgpuasmbackend/#a8731b38926f3641bcc445b9ba27e74be">anonymous{AMDGPUAsmBackend.cpp}::AMDGPUAsmBackend::relaxInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#af22c9938ad82cf97ee6cc8cf00d265cc">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::relaxInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmbackend/#ad50e8c99a8ff188846367ea1a9ae2143">llvm::ARMAsmBackend::relaxInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyasmbackend/#ade0613efda90a350f47392d0b721b1f8">llvm::CSKYAsmBackend::relaxInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a358ac79e04af2c8c34fa5084fa46cfee">llvm::RISCVAsmBackend::relaxInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a4094775b51be5196cd6a6a5254530d6c">translateDstIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a4baeecd8498cfd4ba890951058393621">translateFPRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a409baefdf6be89e38deebefb129c1978">translateImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a39a264ff5629dff4dc2a278f3848b4df">translateMaskRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#aeb806eaaca65c1a593f5af3078798819">translateOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a06e3b1499180a2b92acc66f9203ac920">translateRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ae82674c41a00b35f36f9ecf81932512e">translateRMMemory</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a972b23f3658215b06333703a6099eeb1">translateSrcIndex</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusymbolizer/#a6c8e8592c8a9a236312224fb457fc834">llvm::AMDGPUSymbolizer::tryAddingSymbolicOperand</a>.</p>

</div>
</div>

### begin() {#ad7df02a018c3a01d74738d5ba3a09e93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::MCInst::begin ()</td>
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



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a57878d0e3afa7d6e659b92b9d71c0923">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtSDWA</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a4547aa57e2b9056a73e2a8b26cc18d5b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOP3</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp/#a060f0d1989564164d0cf3fad101666f4">lookForCompound</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a74bd673118d2cbb40d776bb1726d4c95">anonymous{X86MCInstLower.cpp}::X86MCInstLower::Lower</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblymcinstlower/#a62aefd0bed5ed9cd5a154bf4d4074a22">llvm::WebAssemblyMCInstLower::lower</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagon/packetiterator/#aa2a0dda875c44641d039611c617f2a81">llvm::Hexagon::PacketIterator::operator++</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#abd317698bbd34d1cb4e69a49141dab58">llvm::HexagonMCInstrInfo::replaceDuplex</a>.</p>

</div>
</div>

### begin() {#a758d1c99f5e677bbca86b4f70860babf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::MCInst::begin ()</td>
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



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a>.</p>

</div>
</div>

### clear() {#aecd4e9369c30b88c8e528489f69e0c8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCInst::clear ()</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonmcshuffler/#ad7107b9902252656400f8760c3d657dd">llvm::HexagonMCShuffler::copyTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#aaec91c96968a65d0fa1bf2165345258d">DecodeL5RInstructionFail</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a1760c43fadfe8ae62e75e7debd68fad5">llvm::MipsTargetELFStreamer::emitDirectiveCpLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#aee072cd97eb6d078d122611833049aa6">llvm::HexagonAsmPrinter::HexagonProcessInstruction</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ae99d82425a463a5dd5413112fda5ed17">translateInstruction</a>.</p>

</div>
</div>

### dump() {#ab8aa6b74c6bb82576347afb756807f20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void MCInst::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a>, definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcinst-cpp">MCInst.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a3d101ee8e316d793b1e136a0ee3a7795">print</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cskyasmbackend/#ade0613efda90a350f47392d0b721b1f8">llvm::CSKYAsmBackend::relaxInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonmcshuffler/#a7acb90dc32e0d7297b6264ab4d25c348">llvm::HexagonMCShuffler::reshuffleTo</a>.</p>

</div>
</div>

### dump\_pretty() {#a230d5dad7ea2d94e1671a4aa222a2e15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCInst::dump_pretty (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter">MCInstPrinter</a> * Printer=nullptr, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Separator=" ", <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> * RegInfo=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump the <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> as prettily as possible using the additional MC structures, if given.</p>


<p>Operators are separated by the <span class="doxyComputerOutput">Separator</span> string.</p>


<p>Declaration at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a>, definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcinst-cpp">MCInst.cpp</a>.</p>


<p>References <a href="#a230d5dad7ea2d94e1671a4aa222a2e15">dump_pretty</a>, <a href="#a5c26b1db954c27889986dba3b310a8e4">getOpcode</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a>.</p>


<p>Referenced by <a href="#a230d5dad7ea2d94e1671a4aa222a2e15">dump_pretty</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a161ac460fefc16f98a8dd1a9f019af9a">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#a25385ca3fbc7a797f0786eb6e4faf8bf">anonymous{ARMAsmParser.cpp}::ARMAsmParser::matchAndEmitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmbackend-cpp-/m68kasmbackend/#a86fcebca1ff924c7d38226f00c8e3622">anonymous{M68kAsmBackend.cpp}::M68kAsmBackend::relaxInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#a85095bdb81f7b2460ce2b158985cdfa9">anonymous{X86AsmBackend.cpp}::X86AsmBackend::relaxInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/armasmbackend/#ad50e8c99a8ff188846367ea1a9ae2143">llvm::ARMAsmBackend::relaxInstruction</a>.</p>

</div>
</div>

### dump\_pretty() {#aed3878e91373aaa765f80e2242ed2d00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCInst::dump_pretty (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Separator=" ", <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> * RegInfo=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a>, definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcinst-cpp">MCInst.cpp</a>.</p>


<p>References <a href="#a3c5c7109f398fdca515509e2284cd8c0">getNumOperands</a>, <a href="#a5c26b1db954c27889986dba3b310a8e4">getOpcode</a>, <a href="#aef5de3ac30fe221c5b4e702574ab46a9">getOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ab918360fb55bd58c515880d80430df15">llvm::MCOperand::print</a>.</p>

</div>
</div>

### end() {#ad815f3f5c7e6106ca7ba4926d143c2cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::MCInst::end ()</td>
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



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#acde34c306f55bfc47634d259c0115e0d">DecodeRegListOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp/#a060f0d1989564164d0cf3fad101666f4">lookForCompound</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagon/packetiterator/#aa2a0dda875c44641d039611c617f2a81">llvm::Hexagon::PacketIterator::operator++</a>.</p>

</div>
</div>

### end() {#a3089b28c8766e9d73fef97277bff4760}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::MCInst::end ()</td>
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



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a>.</p>

</div>
</div>

### erase() {#a392c263d0b0a47be4702000f9bca7f16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCInst::erase (<a href="#a48b4f98c8f42ed1a9d07419f7df1d855">iterator</a> I)</td>
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



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp/#a060f0d1989564164d0cf3fad101666f4">lookForCompound</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymcinstlower-cpp/#a35043b20e128ef142a010db3ff501a17">removeRegisterOperands</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#abd317698bbd34d1cb4e69a49141dab58">llvm::HexagonMCInstrInfo::replaceDuplex</a>.</p>

</div>
</div>

### erase() {#a6ceb216bb12f49d64b81f89567af3e30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCInst::erase (<a href="#a48b4f98c8f42ed1a9d07419f7df1d855">iterator</a> First, <a href="#a48b4f98c8f42ed1a9d07419f7df1d855">iterator</a> Last)</td>
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



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a>.</p>

</div>
</div>

### getFlags() {#a518d09ad3fe41943c92e577a98fe374c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCInst::getFlags ()</td>
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



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a4eee928f2e1bc161f7ab607fbd993b2a">llvm::mca::hashMCInst</a>.</p>

</div>
</div>

### getLoc() {#a40c7fb73978096ed317dd71fb8a84cf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc llvm::MCInst::getLoc ()</td>
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



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a95f7f3602bc5500992d937bd0bb33b3e">llvm::HexagonMCInstrInfo::addConstExtender</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa952aa5bfb51a38178c0d47e0fc7aa7b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addLiteralImmOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a0cc69fdbc6fdc191c90bcd0f399dfa3f">llvm::HexagonMCInstrInfo::deriveSubInst</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a92d2d1c2ac97f1151ed8f38d854e8b34">llvm::MCObjectStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#a45bea692e1c1def80eaae16d764ae97e">llvm::HexagonShuffler::restrictNoSlot1Store</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#a5ddcba5b6fe2c4762daa50893c3cfe8c">llvm::HexagonShuffler::restrictSlot1AOK</a>.</p>

</div>
</div>

### getNumOperands() {#a3c5c7109f398fdca515509e2284cd8c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCInst::getNumOperands ()</td>
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



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aecc4bcb6c40064c4c0544f55facbb18a">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa952aa5bfb51a38178c0d47e0fc7aa7b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addLiteralImmOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a45c157d6c567f135196ef6a2c1571409">anonymous{ARMAsmParser.cpp}::ARMOperand::addVPTPredROperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/asmparser/armasmparser-cpp/#a8e71614eed98b51939998f17268d534f">checkLowRegisterList</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#a084d3381057e1304b250b664a2b0aa2b">anonymous{ARMAsmParser.cpp}::ARMAsmParser::checkTargetMatchPredicate</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#adfaf977dc82c560bd265a68c807cd1a0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtDPP</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a57878d0e3afa7d6e659b92b9d71c0923">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtSDWA</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ac4e2add1506387486f82ff6117a6a0e4">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVINTERP</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a4547aa57e2b9056a73e2a8b26cc18d5b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOP3</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a81d4a718e3a11c1c3507fb28db101cf6">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOP3DPP</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#af30bfdcbe6574a1d0de2c2c59c1a8f18">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOP3Interp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#ac34073953af52bfb6d10afcfa08233cd">decodeAVLdSt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#af29ab03d6050c790ddb78a16ec44a9c8">DecodeT2Adr</a>, <a href="#aed3878e91373aaa765f80e2242ed2d00">dump_pretty</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a2e263d122b10b0bcc1bbf6c63202208c">llvm::MCStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mipselfstreamer/#a4edf55e6bd046a52bbb7867d8a601e3c">llvm::MipsELFStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmcelfstreamer/#a8c8aaade94f26b9991cee49ae53bdadb">llvm::HexagonMCELFStreamer::EmitSymbol</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64mctargetdesc-cpp-/aarch64mcinstranalysis/#a4c72497e2b74e57f8a4b77ef72eb298c">anonymous{AArch64MCTargetDesc.cpp}::AArch64MCInstrAnalysis::evaluateBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpumctargetdesc-cpp-/amdgpumcinstranalysis/#a990e2fd97840a6e7604129dceaf62323">anonymous{AMDGPUMCTargetDesc.cpp}::AMDGPUMCInstrAnalysis::evaluateBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskymctargetdesc-cpp-/cskymcinstranalysis/#a198bdcf5a8ea9c488caf67463ac4cbe6">anonymous{CSKYMCTargetDesc.cpp}::CSKYMCInstrAnalysis::evaluateBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-lanaimctargetdesc-cpp-/lanaimcinstranalysis/#a9af2b49338eb4861af6c89bd1abfff5c">anonymous{LanaiMCTargetDesc.cpp}::LanaiMCInstrAnalysis::evaluateBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmctargetdesc-cpp-/loongarchmcinstranalysis/#a9bbaa778eb8fe8688ceebefc7cc54125">anonymous{LoongArchMCTargetDesc.cpp}::LoongArchMCInstrAnalysis::evaluateBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsmctargetdesc-cpp-/mipsmcinstranalysis/#a3c80b959e2faf1313a1fd893e98baebf">anonymous{MipsMCTargetDesc.cpp}::MipsMCInstrAnalysis::evaluateBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcmctargetdesc-cpp-/ppcmcinstranalysis/#a18580f96be7b622d5aaee118a569d5f7">anonymous{PPCMCTargetDesc.cpp}::PPCMCInstrAnalysis::evaluateBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/x86-mc/x86mcinstranalysis/#a0a8c4d72c02218eb048aa7eb27af8074">llvm::X86_MC::X86MCInstrAnalysis::evaluateBranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a12bbe632ac24b40e52a6f3dcdef003d5">llvm::HexagonMCInstrInfo::getDuplexPossibilties</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a4eee928f2e1bc161f7ab607fbd993b2a">llvm::mca::hashMCInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a09ddc9ac2f9a0ce92be5565eff4f3869">llvm::HexagonMCInstrInfo::isOrderedDuplexPair</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc6a276f0a40e983e11fe851e818ad01">llvm::isPartOfGOTToPCRelPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/asmparser/armasmparser-cpp/#a77def5524fdc0075b9303cdbb3f01c9e">listContainsReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a74bd673118d2cbb40d776bb1726d4c95">anonymous{X86MCInstLower.cpp}::X86MCInstLower::Lower</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kmcinstlower/#aaa1ed5df03c02ae5e378bd14aee41269">llvm::M68kMCInstLower::Lower</a>, <a href="/web-llvm/docs/api/classes/amdgpumcinstlower/#ae4383929e7fb1cdba8806d6f68af926b">AMDGPUMCInstLower::lower</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmccodeemitter-cpp/#ac23d02bf8c91f40857c9b136d4a1c1a1">LowerLargeShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp/#af3b87eccd7dfd84ba438253014223161">lowerRISCVVMachineInstrToMCInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmbackend-cpp-/m68kasmbackend/#a26dcfc644838c79942839ba61576a919">anonymous{M68kAsmBackend.cpp}::M68kAsmBackend::mayNeedRelaxation</a>, <a href="#a3d101ee8e316d793b1e136a0ee3a7795">print</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymcinstlower-cpp/#a35043b20e128ef142a010db3ff501a17">removeRegisterOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonasmprinter-cpp/#a7e075cc11fc81de8e280e3cdf8560ef3">ScaleVectorOffset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mca/#aef788a4cb082ca5268ed346517eede15">llvm::mca::verifyOperands</a>.</p>

</div>
</div>

### getOpcode() {#a5c26b1db954c27889986dba3b310a8e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCInst::getOpcode ()</td>
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



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aecc4bcb6c40064c4c0544f55facbb18a">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa952aa5bfb51a38178c0d47e0fc7aa7b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addLiteralImmOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ad77c1ff80909be05a660bdcb161beb65">anonymous{ARMAsmParser.cpp}::ARMOperand::addNEONi8ReplicateOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#accc1e804755bf43243950da346e4f635">anonymous{ARMAsmParser.cpp}::ARMOperand::addNEONvmovi16ReplicateOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ae9be674e0179e785d1e553d87229da10">anonymous{ARMAsmParser.cpp}::ARMOperand::addNEONvmovi32ReplicateOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a45c157d6c567f135196ef6a2c1571409">anonymous{ARMAsmParser.cpp}::ARMOperand::addVPTPredROperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#a837cebf4290b760bbe740756cb60d6fe">anonymous{ARMAsmParser.cpp}::ARMAsmParser::checkEarlyTargetMatchPredicate</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ae55539b0211e9bc98123340231aa6902">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::checkTargetMatchPredicate</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#a084d3381057e1304b250b664a2b0aa2b">anonymous{ARMAsmParser.cpp}::ARMAsmParser::checkTargetMatchPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#a0a1753bf36e27b0c54c2aba603a3b9f9">checkWriteLane</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64mctargetdesc-cpp-/aarch64mcinstranalysis/#afc4096fa52a7823c60752ddf56f4356d">anonymous{AArch64MCTargetDesc.cpp}::AArch64MCInstrAnalysis::clearsSuperRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/x86-mc/x86mcinstranalysis/#ac6e094cc98c3bef1145702f8f233d0bf">llvm::X86_MC::X86MCInstrAnalysis::clearsSuperRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel/#adb6e223c45e270c5b14fbdc934d059c4">llvm::TargetSchedModel::computeInstrLatency</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp/#a4386ffb2e777bd2b2f2a30e89decfebc">convertSSEToAVX</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instrbuilder/#afe394be08220c92f22489a0f952d39ee">llvm::mca::InstrBuilder::createInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/riscvinstrumentmanager/#ae0185b56daf5bfb7ebff494d4ade9787">llvm::mca::RISCVInstrumentManager::createInstruments</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#adfaf977dc82c560bd265a68c807cd1a0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtDPP</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a57878d0e3afa7d6e659b92b9d71c0923">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtSDWA</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a238abfd2ac2842861ab322354aec3d64">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtSWMMAC</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ac4e2add1506387486f82ff6117a6a0e4">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVINTERP</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a4547aa57e2b9056a73e2a8b26cc18d5b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOP3</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a81d4a718e3a11c1c3507fb28db101cf6">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOP3DPP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ad3bff1e1b8f6b45aeb994f8ba063dd4e">cvtVOP3DstOpSelOnly</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#af30bfdcbe6574a1d0de2c2c59c1a8f18">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOP3Interp</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a0b9f3d685a06c0789d0e594e044be2b9">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOPD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a01159155e0e1288fdee10e8077d347e4">DecodeAddrMode2IdxInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a748fded8b9c14e77783f32aa13b93af7">DecodeAddrMode3Instruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a30705aebb6dc9b1e06d32247c8eba534">DecodeAddSubERegInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a2d3a2f957bed112cb510b5d278872555">DecodeArmMOVTWInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a60422239523d25de92f9a7d7d6b23cbd">DecodeAuthLoadInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#ac34073953af52bfb6d10afcfa08233cd">decodeAVLdSt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a36413fd3a08347a6defae0004efa31ba">DecodeBranchImmInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/disassembler/xtensadisassembler-cpp/#ae750695a9783689206fd3324068b93ec">decodeBranchOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a7b3ca5b536ce1c58a39b853ea79de51b">DecodeCopMemInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#ad224195417b4e7fff787eaa0ea9eb46f">DecodeExclusiveLdStInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#afe0a70f7662c3f654851dbf51ff0fa4a">DecodeForVMRSandVMSR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a46b59aec241e0564ca44770f25f2ec71">DecodeLogicalImmInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#afecebd0151d705a1f451129515690010">DecodeLOLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#af6be4e043e94b84a2f41ca62f43e2c33">DecodeMem</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a0846cbb46ed7dfb0fe8963f57e4e450c">DecodeMemEVA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a5cdc282caa88d2f28ce4792ad53d4471">DecodeMemMMImm12</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a97875810a5d927cedd5b85ab368caf67">DecodeMemMMImm4</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a2a99cbe29aa769217b2e94ed6248575e">DecodeMemMMImm9</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a7bd5fcbe5963096279a236cbdf87e675">DecodeMemMMReglistImm4Lsl2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aee22f63177a59f1c073fc689b38933ae">DecodeMemMultipleWritebackInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a3fad9a3a6a6f166a13d42ea4ce4046a6">DecodeModImmInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a472d51a3167cd8c4a324627ccb3d063e">DecodeMoveImmInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a38cb0684cd1dac98218884dbd1ffbb85">DecodeMSA128Mem</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ab4afad02e282888ac65f575a3288b53a">DecodeMSRMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aa6165f97e90eaea7675b635e2d2a1a3a">DecodeMVEModImmInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ace68fb9d35b1e3f7c97175ebeb16e386">DecodeMVEOverlappingLongShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a64316e7222c5bfbf7c8ad81567f8cd0b">DecodePairLdStInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#abe725b290fe0d33be6a7483438c37794">DecodePCRelLabel19</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ad22d00715292f5cf5d09380b15cb6189">DecodePredicateOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#adf13850bfdcd4986cc6b21f227468936">DecodePRFMRegInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#acde34c306f55bfc47634d259c0115e0d">DecodeRegListOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#abf0a19aed27d5d513d9891ae3d48bc31">DecodeRegListOperand16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a27d5f895980d5049799b32f5d4161d4e">DecoderForMRRC2AndMCRR2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#acf5f17b8afe036660d97ba9f2e254c31">DecodeSignedLdStInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#ab357e7edc71c6ac759f843c8a4d2e525">DecodeSpecial3LlSc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a8791e99741e918b4a6dd4de52c238d04">DecodeSVELogicalImmInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a02d69d029e1221f31502f0ea27919fce">DecodeT2AddrModeImm12</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a2eaef92ac016b6867cf2e684b5bb76c7">DecodeT2AddrModeImm8</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ad2d2ec79ae9dffdbfb48ad8d5127545e">DecodeT2AddrModeSOReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aa0db3bd9104dd7f086c6f8686f59c288">DecodeT2LdStPre</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a57b019630c1fd92a4bf745e6639f344a">DecodeT2LoadImm12</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aa5cc177b319e4695ef7c2b627ed4a5e6">DecodeT2LoadImm8</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a18ec82d05c3fecd8d313d76aa6cf4d88">DecodeT2LoadLabel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aaab47c414bc9052d5ae109a30036ae38">DecodeT2LoadShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a08bf371630cff66c49e3aaebc6b7337d">DecodeT2LoadT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a3d6b4d56448a550e780bcc286defca12">DecodeT2MOVTWInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ade174bb0481f851b34f77b9f83c5b7ae">DecodeTBLInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#ac34ad1dd79456d25b144337df1117ef9">DecodeThreeAddrSRegInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a9d49e57d960810a6cdebef656a7d12c1">DecodeThumbAddSpecialReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a4ff9913a6a8ee09237b7bdb7350f8758">DecodeThumbAddSPReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a406420d233c9c21f4c1bfbc6328c7651">DecodeTSBInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a4d0969e62a9d55e7a6b81658aaac2841">DecodeUnsignedLdStInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aa9f76b11681b7d483c31d2108af81914">DecodeVCVTImmOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a4bc58a6a4cc485df54316ee63961494a">DecodeVLD1DupInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#adbfb7c834c41c75925284ebcb3e30a43">DecodeVLD2DupInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aa46c26cc972273e7463a3ebe3a9cedad">DecodeVLDInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a41d6edfa220d2050c7c245dd1e5e5fec">DecodeVMOVModImmInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a4ae2e98f9553b452f8c2b5107a8cb16a">llvm::AMDGPUDisassembler::decodeVOPDDstYOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aea8ff3695bbef57d56a2d23873b029bf">DecodeVSCCLRM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a83aef7e6f90ca5e44f3927132a133315">DecodeVSTInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a8ed86ab442732ed8bfdbb259af9edfc6">DecodeVSTRVLDR_SYSREG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a658e7d113d0172f3dad093f32851616c">decodeXTHeadMemPair</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a0cc69fdbc6fdc191c90bcd0f399dfa3f">llvm::HexagonMCInstrInfo::deriveSubInst</a>, <a href="#a230d5dad7ea2d94e1671a4aa222a2e15">dump_pretty</a>, <a href="#aed3878e91373aaa765f80e2242ed2d00">dump_pretty</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a5b7c6daec7e647061052e0947de4703b">llvm::AsmPrinter::emitFunctionBody</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsnaclelfstreamer-cpp-/mipsnaclelfstreamer/#aa58798011dd108a27dfd0734caa2c4eb">anonymous{MipsNaClELFStreamer.cpp}::MipsNaClELFStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmcelfstreamer/#a706aa084f85cdf448e79ad2d8be30bff">llvm::HexagonMCELFStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#a8c9b4bc17f742123fb67a743e46e11bc">anonymous{X86AsmBackend.cpp}::X86AsmBackend::emitInstructionEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#ada77d1fd6603eff06b4da3c2381b84be">llvm::MipsMCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64mctargetdesc-cpp-/aarch64mcinstranalysis/#a4c72497e2b74e57f8a4b77ef72eb298c">anonymous{AArch64MCTargetDesc.cpp}::AArch64MCInstrAnalysis::evaluateBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpumctargetdesc-cpp-/amdgpumcinstranalysis/#a990e2fd97840a6e7604129dceaf62323">anonymous{AMDGPUMCTargetDesc.cpp}::AMDGPUMCInstrAnalysis::evaluateBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmctargetdesc-cpp-/armmcinstranalysis/#abd75f1cc002f438f42d32f12e0326122">anonymous{ARMMCTargetDesc.cpp}::ARMMCInstrAnalysis::evaluateBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpfmctargetdesc-cpp-/bpfmcinstranalysis/#a934b6ec47b45cbb5ce201a83824936eb">anonymous{BPFMCTargetDesc.cpp}::BPFMCInstrAnalysis::evaluateBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskymctargetdesc-cpp-/cskymcinstranalysis/#a198bdcf5a8ea9c488caf67463ac4cbe6">anonymous{CSKYMCTargetDesc.cpp}::CSKYMCInstrAnalysis::evaluateBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-lanaimctargetdesc-cpp-/lanaimcinstranalysis/#a9af2b49338eb4861af6c89bd1abfff5c">anonymous{LanaiMCTargetDesc.cpp}::LanaiMCInstrAnalysis::evaluateBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmctargetdesc-cpp-/loongarchmcinstranalysis/#a9bbaa778eb8fe8688ceebefc7cc54125">anonymous{LoongArchMCTargetDesc.cpp}::LoongArchMCInstrAnalysis::evaluateBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsmctargetdesc-cpp-/mipsmcinstranalysis/#a3c80b959e2faf1313a1fd893e98baebf">anonymous{MipsMCTargetDesc.cpp}::MipsMCInstrAnalysis::evaluateBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcmctargetdesc-cpp-/ppcmcinstranalysis/#a18580f96be7b622d5aaee118a569d5f7">anonymous{PPCMCTargetDesc.cpp}::PPCMCInstrAnalysis::evaluateBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmctargetdesc-cpp-/riscvmcinstranalysis/#a925777a1921196b6a326cecfd4fad1c5">anonymous{RISCVMCTargetDesc.cpp}::RISCVMCInstrAnalysis::evaluateBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/x86-mc/x86mcinstranalysis/#a0a8c4d72c02218eb048aa7eb27af8074">llvm::X86_MC::X86MCInstrAnalysis::evaluateBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmctargetdesc-cpp-/armmcinstranalysis/#a49422093293e285d52290f1491a42f33">anonymous{ARMMCTargetDesc.cpp}::ARMMCInstrAnalysis::evaluateMemoryOperandAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/x86-mc/x86mcinstranalysis/#a1f1d390a3cd743e24f556b00c7afb432">llvm::X86_MC::X86MCInstrAnalysis::evaluateMemoryOperandAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp/#a81470ca50ca4d5d5888f72c1dc2c9993">getCompoundOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a5d6d2c647044122707e6ebc1f62f7c67">llvm::HexagonMCInstrInfo::getDesc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#ae89672f809e6b7c989b09f70432e5de5">llvm::HexagonMCInstrInfo::getDuplexCandidateGroup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a12bbe632ac24b40e52a6f3dcdef003d5">llvm::HexagonMCInstrInfo::getDuplexPossibilties</a>, <a href="/web-llvm/docs/api/classes/llvm/x86-mc/x86mcinstranalysis/#a32469aadc2b1ab4993d6656074d0fa91">llvm::X86_MC::X86MCInstrAnalysis::getMemoryOperandRelocationOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#acd45ce6506a97a792fa494d67ca1075c">llvm::HexagonMCInstrInfo::getName</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#ac080bbec97a31ee8728ca9828700ad45">llvm::MCSchedModel::getReciprocalThroughput</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp/#a6286499931f99f2a37f4a5eb20ecf88a">getRegisterForMxtrDSP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/mctargetdesc/m68kasmbackend-cpp/#aa0d457055111949227e8221dfda24063">getRelaxedOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/mctargetdesc/m68kasmbackend-cpp/#aa0b84ac6bc80cbae5ddfc365f1b0ae26">getRelaxedOpcodeArith</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/mctargetdesc/m68kasmbackend-cpp/#a33850a6d0c712315896ff30c975138cb">getRelaxedOpcodeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instrumentmanager/#a5e6483bc81e9963e00f1d2a0782110ea">llvm::mca::InstrumentManager::getSchedClassID</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/riscvinstrumentmanager/#a565ec0f78fe6a37a593cf626b7d0c334">llvm::mca::RISCVInstrumentManager::getSchedClassID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a94f0ca29631596dfaa69418dd1dd6cbd">llvm::HexagonMCInstrInfo::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a4eee928f2e1bc161f7ab607fbd993b2a">llvm::mca::hashMCInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp/#a727a5341ff53d48d29ff8455b87d880e">hasShortDelaySlot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#acc1617af84ad9ddfb09c096ad8d8479f">llvm::HexagonMCInstrInfo::hasTmpDst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77ac85fa1d774b4d1f5a064e1b8ee8c3">llvm::HexagonLowerToMC</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#aee072cd97eb6d078d122611833049aa6">llvm::HexagonAsmPrinter::HexagonProcessInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/asmparser/armasmparser-cpp/#a23eb98be6e27ac9378025e2e96d7a20a">instIsBreakpoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#afd160d6c9cc947a3c786d83f07f06e71">IsAGPROperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmctargetdesc-cpp-/loongarchmcinstranalysis/#a1432481516dcfa884ae1bd39c921838a">anonymous{LoongArchMCTargetDesc.cpp}::LoongArchMCInstrAnalysis::isBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis/#a1257ef2cd77675ddbbf226a99c13e13e">llvm::MCInstrAnalysis::isBranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a69d33e060c5b0bbfe0f8a2cbeb71f598">llvm::HexagonMCInstrInfo::isBundle</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmctargetdesc-cpp-/loongarchmcinstranalysis/#ad1f46811cb8e3f5bb5a8a4f93b47c246">anonymous{LoongArchMCTargetDesc.cpp}::LoongArchMCInstrAnalysis::isCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmctargetdesc-cpp-/riscvmcinstranalysis/#ab0c01b6ed9b4a5429b4ee987af5d44a9">anonymous{RISCVMCTargetDesc.cpp}::RISCVMCInstrAnalysis::isCall</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis/#a123e3dc956b0dad28841670ee6bd84e4">llvm::MCInstrAnalysis::isCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmctargetdesc-cpp-/armmcinstranalysis/#af9b1c01689e16efd902204d7835455d8">anonymous{ARMMCTargetDesc.cpp}::ARMMCInstrAnalysis::isConditionalBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis/#aabfb496421d3e86668396b0b97d5a431">llvm::MCInstrAnalysis::isConditionalBranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a0dc17f36db22a5d62643fdce547bb3ea">llvm::HexagonMCInstrInfo::isConstExtended</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp/#a819849ddb360be005e7c78fad31f754d">isFirstMacroFusibleInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a95c527167756007a3fb2ab49ec4b2c6d">llvm::HexagonMCInstrInfo::isImmext</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmctargetdesc-cpp-/loongarchmcinstranalysis/#af645c3dac78a7dc182eb8c335bcdf2a1">anonymous{LoongArchMCTargetDesc.cpp}::LoongArchMCInstrAnalysis::isIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmctargetdesc-cpp-/riscvmcinstranalysis/#a6301ef0afc74da2d74cd09ad21ef6e3c">anonymous{RISCVMCTargetDesc.cpp}::RISCVMCInstrAnalysis::isIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis/#af59aa5e676918a7e6f8d5396493bf2e7">llvm::MCInstrAnalysis::isIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#a135855aba8ee58019db788042c0d9a54">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::isInstRelaxable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp/#aaaf1263d3963abf3556875a37c3df8f8">isOrderedCompoundPair</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a09ddc9ac2f9a0ce92be5565eff4f3869">llvm::HexagonMCInstrInfo::isOrderedDuplexPair</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc6a276f0a40e983e11fe851e818ad01">llvm::isPartOfGOTToPCRelPair</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmctargetdesc-cpp-/loongarchmcinstranalysis/#adb0195419efb702f5bcc38d31e0ed25f">anonymous{LoongArchMCTargetDesc.cpp}::LoongArchMCInstrAnalysis::isReturn</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmctargetdesc-cpp-/riscvmcinstranalysis/#aa3ab7d90832965dda539001e98273b0c">anonymous{RISCVMCTargetDesc.cpp}::RISCVMCInstrAnalysis::isReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis/#ab35bd22c3d7674c156ad6601138a0eb5">llvm::MCInstrAnalysis::isReturn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a11e74a6ead98c7237e37c532e411295d">llvm::HexagonMCInstrInfo::isSolo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#aeb3cb6c125bcfdc44c7d3942911616d7">llvm::HexagonMCInstrInfo::isSubInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmctargetdesc-cpp-/loongarchmcinstranalysis/#a4ff2d7a6366b1df40ce83377230ce8b1">anonymous{LoongArchMCTargetDesc.cpp}::LoongArchMCInstrAnalysis::isTerminator</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmctargetdesc-cpp-/riscvmcinstranalysis/#abed0fb0d03618a1ad34160c1eecf7eff">anonymous{RISCVMCTargetDesc.cpp}::RISCVMCInstrAnalysis::isTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis/#a94d1c412a8092f9967816970073ecb74">llvm::MCInstrAnalysis::isTerminator</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmctargetdesc-cpp-/armmcinstranalysis/#ac389d403d77a77be4f5125065acbc9ee">anonymous{ARMMCTargetDesc.cpp}::ARMMCInstrAnalysis::isUnconditionalBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmctargetdesc-cpp-/loongarchmcinstranalysis/#ac00edf85f1a5972a7f8aafa934348ecf">anonymous{LoongArchMCTargetDesc.cpp}::LoongArchMCInstrAnalysis::isUnconditionalBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis/#a4e5be94e4462c129c3b5e4ba2af1c2bc">llvm::MCInstrAnalysis::isUnconditionalBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp/#a060f0d1989564164d0cf3fad101666f4">lookForCompound</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a74bd673118d2cbb40d776bb1726d4c95">anonymous{X86MCInstLower.cpp}::X86MCInstLower::Lower</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#ab248027e3bae0d1e5d3a20d8846edb9a">llvm::AArch64MCInstLower::Lower</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmccodeemitter-cpp/#ac23d02bf8c91f40857c9b136d4a1c1a1">LowerLargeShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp/#af3b87eccd7dfd84ba438253014223161">lowerRISCVVMachineInstrToMCInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#a25385ca3fbc7a797f0786eb6e4faf8bf">anonymous{ARMAsmParser.cpp}::ARMAsmParser::matchAndEmitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#abeebd6c3e48c1d92d186d8ffafbf5e2b">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::matchAndEmitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#ab27e65f978739f8a4075962e72373af5">anonymous{ARMAsmParser.cpp}::ARMAsmParser::MatchInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis/#aafca081ce7f45907550a9313a27dc90a">llvm::MCInstrAnalysis::mayAffectControlFlow</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmbackend-cpp-/amdgpuasmbackend/#a6349367781dae3049ca7dc31906fe3e7">anonymous{AMDGPUAsmBackend.cpp}::AMDGPUAsmBackend::mayNeedRelaxation</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmbackend-cpp-/m68kasmbackend/#a26dcfc644838c79942839ba61576a919">anonymous{M68kAsmBackend.cpp}::M68kAsmBackend::mayNeedRelaxation</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmbackend/#adea9d854579eb622c1be4e9add02180a">llvm::ARMAsmBackend::mayNeedRelaxation</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyasmbackend/#a4315216f104f0f7963b4ba8e6f85d01d">llvm::CSKYAsmBackend::mayNeedRelaxation</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a7c222afc583edb916fd251f05f41d0c8">llvm::RISCVAsmBackend::mayNeedRelaxation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a8ec2b3156d41c3b1409515d1d44ada72">PermitsD32</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/amdgpuinstrpostprocess/#a1a3192dc22bc884155c604947d12e7a7">llvm::mca::AMDGPUInstrPostProcess::postProcessInstruction</a>, <a href="#a3d101ee8e316d793b1e136a0ee3a7795">print</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmbackend-cpp-/amdgpuasmbackend/#a8731b38926f3641bcc445b9ba27e74be">anonymous{AMDGPUAsmBackend.cpp}::AMDGPUAsmBackend::relaxInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmbackend-cpp-/m68kasmbackend/#a86fcebca1ff924c7d38226f00c8e3622">anonymous{M68kAsmBackend.cpp}::M68kAsmBackend::relaxInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#a85095bdb81f7b2460ce2b158985cdfa9">anonymous{X86AsmBackend.cpp}::X86AsmBackend::relaxInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmbackend/#ad50e8c99a8ff188846367ea1a9ae2143">llvm::ARMAsmBackend::relaxInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyasmbackend/#ade0613efda90a350f47392d0b721b1f8">llvm::CSKYAsmBackend::relaxInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a358ac79e04af2c8c34fa5084fa46cfee">llvm::RISCVAsmBackend::relaxInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymcinstlower-cpp/#a35043b20e128ef142a010db3ff501a17">removeRegisterOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#ac5fca0a3b40921b5bedfa3303b5158f3">llvm::HexagonMCInstrInfo::requiresSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonasmprinter-cpp/#a7e075cc11fc81de8e280e3cdf8560ef3">ScaleVectorOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a0adeccf7489c053f6a2ee2ecbfe77ea8">llvm::HexagonMCInstrInfo::subInstWouldBeExtended</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ae99d82425a463a5dd5413112fda5ed17">translateInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmtypecheck/#ad05058e6bb44815e9906be40ff6bb88d">llvm::WebAssemblyAsmTypeCheck::typeCheck</a> and <a href="/web-llvm/docs/api/classes/anonymous-riscvmctargetdesc-cpp-/riscvmcinstranalysis/#a84264be03c1d7950cd4f2dba90dbc0ad">anonymous{RISCVMCTargetDesc.cpp}::RISCVMCInstrAnalysis::updateState</a>.</p>

</div>
</div>

### getOperand() {#aef5de3ac30fe221c5b4e702574ab46a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCOperand &amp; llvm::MCInst::getOperand (unsigned i)</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a95f7f3602bc5500992d937bd0bb33b3e">llvm::HexagonMCInstrInfo::addConstExtender</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcduplexinfo-cpp/#ae79cf6180b23c65cbc9d3038da706629">addOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a45c157d6c567f135196ef6a2c1571409">anonymous{ARMAsmParser.cpp}::ARMOperand::addVPTPredROperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad74efac97a18b61ef91f69e7a25532ce">llvm::adjustPqBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/asmparser/armasmparser-cpp/#a8e71614eed98b51939998f17268d534f">checkLowRegisterList</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ae55539b0211e9bc98123340231aa6902">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::checkTargetMatchPredicate</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#a084d3381057e1304b250b664a2b0aa2b">anonymous{ARMAsmParser.cpp}::ARMAsmParser::checkTargetMatchPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#a0a1753bf36e27b0c54c2aba603a3b9f9">checkWriteLane</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64mctargetdesc-cpp-/aarch64mcinstranalysis/#afc4096fa52a7823c60752ddf56f4356d">anonymous{AArch64MCTargetDesc.cpp}::AArch64MCInstrAnalysis::clearsSuperRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/x86-mc/x86mcinstranalysis/#ac6e094cc98c3bef1145702f8f233d0bf">llvm::X86_MC::X86MCInstrAnalysis::clearsSuperRegisters</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp/#a4386ffb2e777bd2b2f2a30e89decfebc">convertSSEToAVX</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instrbuilder/#afe394be08220c92f22489a0f952d39ee">llvm::mca::InstrBuilder::createInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/riscvinstrumentmanager/#ae0185b56daf5bfb7ebff494d4ade9787">llvm::mca::RISCVInstrumentManager::createInstruments</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#adfaf977dc82c560bd265a68c807cd1a0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtDPP</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a38abdd95e7f5b6e9f4fc534bb392f8b8">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtExp</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a57878d0e3afa7d6e659b92b9d71c0923">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtSDWA</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ac4e2add1506387486f82ff6117a6a0e4">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVINTERP</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a4547aa57e2b9056a73e2a8b26cc18d5b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOP3</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a81d4a718e3a11c1c3507fb28db101cf6">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOP3DPP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ad3bff1e1b8f6b45aeb994f8ba063dd4e">cvtVOP3DstOpSelOnly</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aba20f5ca65beb5f3251c3d98ec925cb0">DecodeBFAfterTargetOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#af2e78b5e65ffb6775845fc0212d3145b">DecodeInsSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a472d51a3167cd8c4a324627ccb3d063e">DecodeMoveImmInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#acde34c306f55bfc47634d259c0115e0d">DecodeRegListOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a4fb3fc8c5d55a1d56d78a9df5741397b">decodeRVCInstrRdRs1ImmZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a19d0efeb7b5278d64f33d0423d2bd8ac">decodeRVCInstrRdRs1Rs2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#adfdd862b7dee084ab03c01966116902b">decodeRVCInstrRdRs1UImm</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a4ae2e98f9553b452f8c2b5107a8cb16a">llvm::AMDGPUDisassembler::decodeVOPDDstYOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a0cc69fdbc6fdc191c90bcd0f399dfa3f">llvm::HexagonMCInstrInfo::deriveSubInst</a>, <a href="#aed3878e91373aaa765f80e2242ed2d00">dump_pretty</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsnaclelfstreamer-cpp-/mipsnaclelfstreamer/#aa58798011dd108a27dfd0734caa2c4eb">anonymous{MipsNaClELFStreamer.cpp}::MipsNaClELFStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a8dce3e9284d907db3457ebbfc74909f7">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a2e263d122b10b0bcc1bbf6c63202208c">llvm::MCStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mipselfstreamer/#a4edf55e6bd046a52bbb7867d8a601e3c">llvm::MipsELFStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmcelfstreamer/#a8c8aaade94f26b9991cee49ae53bdadb">llvm::HexagonMCELFStreamer::EmitSymbol</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64mctargetdesc-cpp-/aarch64mcinstranalysis/#a4c72497e2b74e57f8a4b77ef72eb298c">anonymous{AArch64MCTargetDesc.cpp}::AArch64MCInstrAnalysis::evaluateBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpumctargetdesc-cpp-/amdgpumcinstranalysis/#a990e2fd97840a6e7604129dceaf62323">anonymous{AMDGPUMCTargetDesc.cpp}::AMDGPUMCInstrAnalysis::evaluateBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmctargetdesc-cpp-/armmcinstranalysis/#abd75f1cc002f438f42d32f12e0326122">anonymous{ARMMCTargetDesc.cpp}::ARMMCInstrAnalysis::evaluateBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpfmctargetdesc-cpp-/bpfmcinstranalysis/#a934b6ec47b45cbb5ce201a83824936eb">anonymous{BPFMCTargetDesc.cpp}::BPFMCInstrAnalysis::evaluateBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskymctargetdesc-cpp-/cskymcinstranalysis/#a198bdcf5a8ea9c488caf67463ac4cbe6">anonymous{CSKYMCTargetDesc.cpp}::CSKYMCInstrAnalysis::evaluateBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-lanaimctargetdesc-cpp-/lanaimcinstranalysis/#a9af2b49338eb4861af6c89bd1abfff5c">anonymous{LanaiMCTargetDesc.cpp}::LanaiMCInstrAnalysis::evaluateBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmctargetdesc-cpp-/loongarchmcinstranalysis/#a9bbaa778eb8fe8688ceebefc7cc54125">anonymous{LoongArchMCTargetDesc.cpp}::LoongArchMCInstrAnalysis::evaluateBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsmctargetdesc-cpp-/mipsmcinstranalysis/#a3c80b959e2faf1313a1fd893e98baebf">anonymous{MipsMCTargetDesc.cpp}::MipsMCInstrAnalysis::evaluateBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcmctargetdesc-cpp-/ppcmcinstranalysis/#a18580f96be7b622d5aaee118a569d5f7">anonymous{PPCMCTargetDesc.cpp}::PPCMCInstrAnalysis::evaluateBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmctargetdesc-cpp-/riscvmcinstranalysis/#a925777a1921196b6a326cecfd4fad1c5">anonymous{RISCVMCTargetDesc.cpp}::RISCVMCInstrAnalysis::evaluateBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/x86-mc/x86mcinstranalysis/#a0a8c4d72c02218eb048aa7eb27af8074">llvm::X86_MC::X86MCInstrAnalysis::evaluateBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a3a10338918837225d81648bf78971876">evaluateMemOpAddrForAddrMode3</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a90ccaddf3b14b7a19c3174cd9e5651d9">evaluateMemOpAddrForAddrMode5</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a4ffbbb48662d27de4440a7b157ee9c95">evaluateMemOpAddrForAddrMode5FP16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a03dbfe41dfe176bfe1e76230128d4e4a">evaluateMemOpAddrForAddrMode_i12</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#ad34ddc3f73b297a15a8fdfdd78534fed">evaluateMemOpAddrForAddrModeT2_i8s4</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a74107612c997d67a0fadb5fb642fc61d">evaluateMemOpAddrForAddrModeT2_pc</a>, <a href="/web-llvm/docs/api/classes/llvm/x86-mc/x86mcinstranalysis/#a1f1d390a3cd743e24f556b00c7afb432">llvm::X86_MC::X86MCInstrAnalysis::evaluateMemoryOperandAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a92a5e3cfec25537762fd0102dfeb23af">llvm::HexagonMCInstrInfo::extenderForIndex</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hexagondisassembler-cpp-/#a2e0e4ab18e7fb56c7dbd46fe864243e6">anonymous{HexagonDisassembler.cpp}::fullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-lanaimccodeemitter-cpp-/lanaimccodeemitter/#a6e49231451b0b2b51a7e033254ccb415">llvm::anonymous{LanaiMCCodeEmitter.cpp}::LanaiMCCodeEmitter::getBranchTargetOpValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp/#a81470ca50ca4d5d5888f72c1dc2c9993">getCompoundOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#ae89672f809e6b7c989b09f70432e5de5">llvm::HexagonMCInstrInfo::getDuplexCandidateGroup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a12bbe632ac24b40e52a6f3dcdef003d5">llvm::HexagonMCInstrInfo::getDuplexPossibilties</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#aea78a68d4baf2fd4614a3be3a14dd548">llvm::HexagonMCInstrInfo::getExtendableOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86-mc/x86mcinstranalysis/#a32469aadc2b1ab4993d6656074d0fa91">llvm::X86_MC::X86MCInstrAnalysis::getMemoryOperandRelocationOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a96d1b18f6b327cd31760f1e6086ab7f8">llvm::HexagonMCInstrInfo::getNewValueOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#aec6caa48fc271621aca9478a1c4a4268">llvm::HexagonMCInstrInfo::getNewValueOperand2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp/#ac61e163e670a7faff5589438bb24302f">getRegisterForMxtrC0</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp/#a6286499931f99f2a37f4a5eb20ecf88a">getRegisterForMxtrDSP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp/#ad64c2e8f25d74be3500e0085dcb2c604">getRegisterForMxtrFP</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-lanaimccodeemitter-cpp-/lanaimccodeemitter/#a1660300cab17a3aa42a7648d7ef16d59">llvm::anonymous{LanaiMCCodeEmitter.cpp}::LanaiMCCodeEmitter::getRiMemoryOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-lanaimccodeemitter-cpp-/lanaimccodeemitter/#abdd107007255b33a321fb54311fbab99">llvm::anonymous{LanaiMCCodeEmitter.cpp}::LanaiMCCodeEmitter::getRrMemoryOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-lanaimccodeemitter-cpp-/lanaimccodeemitter/#acb6e80d03942494b5ccb861bc69ae7c4">llvm::anonymous{LanaiMCCodeEmitter.cpp}::LanaiMCCodeEmitter::getSplsOpValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a4eee928f2e1bc161f7ab607fbd993b2a">llvm::mca::hashMCInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp/#a727a5341ff53d48d29ff8455b87d880e">hasShortDelaySlot</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#aee072cd97eb6d078d122611833049aa6">llvm::HexagonAsmPrinter::HexagonProcessInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#adda8e3193ca3d31e415a2e4ac6089d50">llvm::HexagonMCInstrInfo::instruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a67245482e0fb8189af448dfed2bc154a">IsAGPROperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#afd160d6c9cc947a3c786d83f07f06e71">IsAGPROperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmctargetdesc-cpp-/loongarchmcinstranalysis/#a1432481516dcfa884ae1bd39c921838a">anonymous{LoongArchMCTargetDesc.cpp}::LoongArchMCInstrAnalysis::isBranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a69d33e060c5b0bbfe0f8a2cbeb71f598">llvm::HexagonMCInstrInfo::isBundle</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmctargetdesc-cpp-/loongarchmcinstranalysis/#ad1f46811cb8e3f5bb5a8a4f93b47c246">anonymous{LoongArchMCTargetDesc.cpp}::LoongArchMCInstrAnalysis::isCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmctargetdesc-cpp-/riscvmcinstranalysis/#ab0c01b6ed9b4a5429b4ee987af5d44a9">anonymous{RISCVMCTargetDesc.cpp}::RISCVMCInstrAnalysis::isCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmctargetdesc-cpp-/armmcinstranalysis/#af9b1c01689e16efd902204d7835455d8">anonymous{ARMMCTargetDesc.cpp}::ARMMCInstrAnalysis::isConditionalBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmctargetdesc-cpp-/loongarchmcinstranalysis/#af645c3dac78a7dc182eb8c335bcdf2a1">anonymous{LoongArchMCTargetDesc.cpp}::LoongArchMCInstrAnalysis::isIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmctargetdesc-cpp-/riscvmcinstranalysis/#a6301ef0afc74da2d74cd09ad21ef6e3c">anonymous{RISCVMCTargetDesc.cpp}::RISCVMCInstrAnalysis::isIndirectBranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#aa4c6bd427b092558b6bf875d8943558d">llvm::HexagonMCInstrInfo::isInnerLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#a135855aba8ee58019db788042c0d9a54">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::isInstRelaxable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a50f29a655ab9a1a5fdf0d476786cbd64">llvm::HexagonMCInstrInfo::isMemReorderDisabled</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp/#aaaf1263d3963abf3556875a37c3df8f8">isOrderedCompoundPair</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a09ddc9ac2f9a0ce92be5565eff4f3869">llvm::HexagonMCInstrInfo::isOrderedDuplexPair</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a15eb1eaa893053e3e1178be7e11f2f59">llvm::HexagonMCInstrInfo::isOuterLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc6a276f0a40e983e11fe851e818ad01">llvm::isPartOfGOTToPCRelPair</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a96fa23bebcb8417618bdeb24230bf2d7">llvm::HexagonMCInstrInfo::isPredRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmctargetdesc-cpp-/loongarchmcinstranalysis/#adb0195419efb702f5bcc38d31e0ed25f">anonymous{LoongArchMCTargetDesc.cpp}::LoongArchMCInstrAnalysis::isReturn</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmctargetdesc-cpp-/riscvmcinstranalysis/#aa3ab7d90832965dda539001e98273b0c">anonymous{RISCVMCTargetDesc.cpp}::RISCVMCInstrAnalysis::isReturn</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmctargetdesc-cpp-/loongarchmcinstranalysis/#a4ff2d7a6366b1df40ce83377230ce8b1">anonymous{LoongArchMCTargetDesc.cpp}::LoongArchMCInstrAnalysis::isTerminator</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmctargetdesc-cpp-/riscvmcinstranalysis/#abed0fb0d03618a1ad34160c1eecf7eff">anonymous{RISCVMCTargetDesc.cpp}::RISCVMCInstrAnalysis::isTerminator</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmctargetdesc-cpp-/armmcinstranalysis/#ac389d403d77a77be4f5125065acbc9ee">anonymous{ARMMCTargetDesc.cpp}::ARMMCInstrAnalysis::isUnconditionalBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmctargetdesc-cpp-/loongarchmcinstranalysis/#ac00edf85f1a5972a7f8aafa934348ecf">anonymous{LoongArchMCTargetDesc.cpp}::LoongArchMCInstrAnalysis::isUnconditionalBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/asmparser/armasmparser-cpp/#a77def5524fdc0075b9303cdbb3f01c9e">listContainsReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a74bd673118d2cbb40d776bb1726d4c95">anonymous{X86MCInstLower.cpp}::X86MCInstLower::Lower</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmccodeemitter-cpp/#ac23d02bf8c91f40857c9b136d4a1c1a1">LowerLargeShift</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#abeebd6c3e48c1d92d186d8ffafbf5e2b">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::matchAndEmitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#ab27e65f978739f8a4075962e72373af5">anonymous{ARMAsmParser.cpp}::ARMAsmParser::MatchInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmbackend-cpp-/m68kasmbackend/#a26dcfc644838c79942839ba61576a919">anonymous{M68kAsmBackend.cpp}::M68kAsmBackend::mayNeedRelaxation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a6ca1ea5b42b7c51b90376ec8262db074">llvm::HexagonMCInstrInfo::minConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp/#a7ec597eb70645748d7299e7a05faa4a5">needsExpandMemInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#aa930f49234de4fd7a469613a1989daf1">llvm::HexagonMCInstrInfo::predicateInfo</a>, <a href="#a3d101ee8e316d793b1e136a0ee3a7795">print</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstprinter/#aa26f3ffae0b86b636abd35ddeda5d523">llvm::HexagonInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmbackend-cpp-/amdgpuasmbackend/#a8731b38926f3641bcc445b9ba27e74be">anonymous{AMDGPUAsmBackend.cpp}::AMDGPUAsmBackend::relaxInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#af22c9938ad82cf97ee6cc8cf00d265cc">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::relaxInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyasmbackend/#ade0613efda90a350f47392d0b721b1f8">llvm::CSKYAsmBackend::relaxInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a358ac79e04af2c8c34fa5084fa46cfee">llvm::RISCVAsmBackend::relaxInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymcinstlower-cpp/#a35043b20e128ef142a010db3ff501a17">removeRegisterOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#abd317698bbd34d1cb4e69a49141dab58">llvm::HexagonMCInstrInfo::replaceDuplex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonasmprinter-cpp/#a7e075cc11fc81de8e280e3cdf8560ef3">ScaleVectorOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a423fa247fcb4eadd2ba802397a79641b">llvm::HexagonMCInstrInfo::setInnerLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a683b8d4f721f40e4a590b1ab7ac682db">llvm::HexagonMCInstrInfo::setMemReorderDisabled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a0eae7cb5eae56054e1b89dfbe489a0f1">llvm::HexagonMCInstrInfo::setOuterLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a0adeccf7489c053f6a2ee2ecbfe77ea8">llvm::HexagonMCInstrInfo::subInstWouldBeExtended</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmtypecheck/#ad05058e6bb44815e9906be40ff6bb88d">llvm::WebAssemblyAsmTypeCheck::typeCheck</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmctargetdesc-cpp-/riscvmcinstranalysis/#a84264be03c1d7950cd4f2dba90dbc0ad">anonymous{RISCVMCTargetDesc.cpp}::RISCVMCInstrAnalysis::updateState</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mca/#aef788a4cb082ca5268ed346517eede15">llvm::mca::verifyOperands</a>.</p>

</div>
</div>

### getOperand() {#a3c40cd35f8cf9812d327d6c4d391011e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand &amp; llvm::MCInst::getOperand (unsigned i)</td>
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



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a>.</p>

</div>
</div>

### insert() {#a780fe7b1259c076cd5abef9ce9dda01d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::MCInst::insert (<a href="#a48b4f98c8f42ed1a9d07419f7df1d855">iterator</a> I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; Op)</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a57878d0e3afa7d6e659b92b9d71c0923">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtSDWA</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a4547aa57e2b9056a73e2a8b26cc18d5b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOP3</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a74bd673118d2cbb40d776bb1726d4c95">anonymous{X86MCInstLower.cpp}::X86MCInstLower::Lower</a> and <a href="/web-llvm/docs/api/classes/llvm/webassemblymcinstlower/#a62aefd0bed5ed9cd5a154bf4d4074a22">llvm::WebAssemblyMCInstLower::lower</a>.</p>

</div>
</div>

### print() {#a3d101ee8e316d793b1e136a0ee3a7795}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCInst::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> * RegInfo=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a>, definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcinst-cpp">MCInst.cpp</a>.</p>


<p>References <a href="#a3c5c7109f398fdca515509e2284cd8c0">getNumOperands</a>, <a href="#a5c26b1db954c27889986dba3b310a8e4">getOpcode</a>, <a href="#aef5de3ac30fe221c5b4e702574ab46a9">getOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ab918360fb55bd58c515880d80430df15">llvm::MCOperand::print</a>.</p>


<p>Referenced by <a href="#ab8aa6b74c6bb82576347afb756807f20">dump</a>.</p>

</div>
</div>

### setFlags() {#a80636f9f710d053d06c8de4f755255a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCInst::setFlags (unsigned F)</td>
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



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a74bd673118d2cbb40d776bb1726d4c95">anonymous{X86MCInstLower.cpp}::X86MCInstLower::Lower</a> and <a href="/web-llvm/docs/api/classes/llvm/spirvmcinstlower/#a6d050903b1d4eb1403389e782f6cec1c">llvm::SPIRVMCInstLower::lower</a>.</p>

</div>
</div>

### setLoc() {#a580e2a6e8a248c5a4a814c03186e9241}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCInst::setLoc (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> loc)</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a95f7f3602bc5500992d937bd0bb33b3e">llvm::HexagonMCInstrInfo::addConstExtender</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmcshuffler/#ad7107b9902252656400f8760c3d657dd">llvm::HexagonMCShuffler::copyTo</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a7ff09aba59d7dcc5dd800735494b14ff">llvm::MipsTargetStreamer::emitII</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a49ba9fd9824c6910d3f66c1ae4469891">llvm::MipsTargetStreamer::emitR</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a09e7b7665f50b4338f746a50f6a454b1">llvm::MipsTargetStreamer::emitRRIII</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#abbac3ade2206cc952cf43e2ca4566201">llvm::MipsTargetStreamer::emitRRRX</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a8b10941b3ac644fb3508bc6cdc8aa6d5">llvm::MipsTargetStreamer::emitRRX</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a2b33055c2d9eb274c2d980428f7a1c24">llvm::MipsTargetStreamer::emitRX</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a6bffa32d06d1516ee01e79b5a250c72e">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::matchAndEmitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#a25385ca3fbc7a797f0786eb6e4faf8bf">anonymous{ARMAsmParser.cpp}::ARMAsmParser::matchAndEmitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a0b228c0975660d76b206b2f9220b3cc3">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::matchAndEmitInstruction</a> and <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#abeebd6c3e48c1d92d186d8ffafbf5e2b">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::matchAndEmitInstruction</a>.</p>

</div>
</div>

### setOpcode() {#ae844d6ff99f067e6672e004ed7613c24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCInst::setOpcode (unsigned Op)</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp/#a4386ffb2e777bd2b2f2a30e89decfebc">convertSSEToAVX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#ad82f20fea871b64a234b4e8829be924d">Decode2OpInstructionFail</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a36413fd3a08347a6defae0004efa31ba">DecodeBranchImmInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#aa5419c3888e7adeccf45d102b0dd09d1">decodeCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a9cf0adb29491a93fac8fe34fd2a70356">DecodeCPSInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#afcde096b672e6803bbd1dc93eecc6f65">decodeFBRk</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#a57891cd6e61d7d49104b0b2ea382d721">DecodeL2OpInstructionFail</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#aaec91c96968a65d0fa1bf2165345258d">DecodeL5RInstructionFail</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#a2cb3aca8e9408d30eaf90bd4c70e65e4">decodeLoadStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#afecebd0151d705a1f451129515690010">DecodeLOLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aee22f63177a59f1c073fc689b38933ae">DecodeMemMultipleWritebackInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ace68fb9d35b1e3f7c97175ebeb16e386">DecodeMVEOverlappingLongShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a4ee0d80338b8a6c928f2322e35a21c37">DecodeSETPANInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a5686943937ea2fcb33898d72abca31ef">DecodeT2AddSubSPImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#af29ab03d6050c790ddb78a16ec44a9c8">DecodeT2Adr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a7e582cac45ed6985921e4bb6a2f7d648">DecodeT2CPSInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aded3e7ff6d138e828bcbcce6cb174baf">DecodeT2HintSpaceInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aa0db3bd9104dd7f086c6f8686f59c288">DecodeT2LdStPre</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a57b019630c1fd92a4bf745e6639f344a">DecodeT2LoadImm12</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aa5cc177b319e4695ef7c2b627ed4a5e6">DecodeT2LoadImm8</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a18ec82d05c3fecd8d313d76aa6cf4d88">DecodeT2LoadLabel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aaab47c414bc9052d5ae109a30036ae38">DecodeT2LoadShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a08bf371630cff66c49e3aaebc6b7337d">DecodeT2LoadT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a2c2187f74d4f13ec46f8bd522ab7f5e4">DecodeThumb2BCCInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a78802c522ed764cedc1bafcf628dd154">DecodeVCVTD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a9e5902642b306bad7e557cc0030a8c3b">DecodeVCVTQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a1eda4c3f6c0329af244778af7bd699fa">llvm::HexagonMCInstrInfo::deriveDuplex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#afef5615be55fa8a93b6a92b8c787aad0">llvm::HexagonMCInstrInfo::deriveExtender</a>, <a href="/web-llvm/docs/api/classes/llvm/x86asmprinter/#a8e2f7eae9c40b29c9c02e709c680e9db">llvm::X86AsmPrinter::emitBasicBlockEnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcasmprinter-cpp/#aaaec30cb8a497bd67f31b3a32d5e2626">EmitBinary</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp/#a3063fa549eed52187dad621a5646bf4e">emitBinary</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp/#a5e94665a52b9daea5f22841f60760ab2">emitBSIC</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a1760c43fadfe8ae62e75e7debd68fad5">llvm::MipsTargetELFStreamer::emitDirectiveCpLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#ac108b4db53de8c6f7f8d905f4db03722">llvm::MipsTargetELFStreamer::emitDirectiveCpreturn</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a7ff09aba59d7dcc5dd800735494b14ff">llvm::MipsTargetStreamer::emitII</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#acdf3f4cb6342e67c42191cf29984df97">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a8dce3e9284d907db3457ebbfc74909f7">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppclinuxasmprinter/#a4123a254ab36bc97c087331e6cb38665">anonymous{PPCAsmPrinter.cpp}::PPCLinuxAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#ac09670e222cb6d4948119b60fd4f3e6e">llvm::ARMAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#a922dc7b28cc9b8895585a602d941b04f">llvm::HexagonAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp/#acc5831f0eaa7631d3dfeda1204813426">emitLEASLrri</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp/#a58c5b4dc239b80405dfe9abdad268555">emitLEASLzzi</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp/#a3812bc25ff6681233201a4c9187dec75">emitLEAzii</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp/#a9fd6a23b5a2ab5b7dc3f202529479a80">emitLEAzzi</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#a95377c6337c8286d00bfd8a2ff437029">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::emitOpLabel</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a3227bdb52724365458abe5cb94be8766">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::emitPtrauthAuthResign</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a17a879a7a14ff0a9e63980908bc502d9">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::emitPtrauthBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a49ba9fd9824c6910d3f66c1ae4469891">llvm::MipsTargetStreamer::emitR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcasmprinter-cpp/#aad58c68abd46a14fdb1cac72bc5b863a">EmitRDPC</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a09e7b7665f50b4338f746a50f6a454b1">llvm::MipsTargetStreamer::emitRRIII</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#abbac3ade2206cc952cf43e2ca4566201">llvm::MipsTargetStreamer::emitRRRX</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a8b10941b3ac644fb3508bc6cdc8aa6d5">llvm::MipsTargetStreamer::emitRRX</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a2b33055c2d9eb274c2d980428f7a1c24">llvm::MipsTargetStreamer::emitRX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcasmprinter-cpp/#a52cbef23880440f08e43fb0818d3ffb4">EmitSETHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp/#a28d8abbfedd338d44a39887939340b91">emitSIC</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#a4562e6672b8b09e99e8bc49651b20e0c">llvm::HexagonAsmPrinter::EmitSled</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#ada77d1fd6603eff06b4da3c2381b84be">llvm::MipsMCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#a11f3e864193e615bb8e8bda2cca24ff3">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::finishLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp/#ad635fb338c113f5de9924ceeeb507dca">getCompoundInsn</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a908e716e36451058cc4d148b090565d5">getMIMnemonic</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstrinfo/#ad900da7454c78d54e25c6fb062c851e5">llvm::ARMInstrInfo::getNop</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a2f3dc5cc960be4f46fdfc635895535a5">llvm::PPCInstrInfo::getNop</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a6aebc34b52d6a52c5a08dd457716115c">llvm::X86InstrInfo::getNop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77ac85fa1d774b4d1f5a064e1b8ee8c3">llvm::HexagonLowerToMC</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#aee072cd97eb6d078d122611833049aa6">llvm::HexagonAsmPrinter::HexagonProcessInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#a3b244792bc2277f0800d9e15c2eb935b">llvm::BTFDebug::InstLower</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a74bd673118d2cbb40d776bb1726d4c95">anonymous{X86MCInstLower.cpp}::X86MCInstLower::Lower</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#ab248027e3bae0d1e5d3a20d8846edb9a">llvm::AArch64MCInstLower::Lower</a>, <a href="/web-llvm/docs/api/classes/llvm/arcmcinstlower/#a80e51b3f855ed903861b58cb8b00e693">llvm::ARCMCInstLower::Lower</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfmcinstlower/#afac72182f48f1b144922b37546a66778">llvm::BPFMCInstLower::Lower</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcinstlower/#a282478f8e3bf69d2fef9f8ce12644ee9">llvm::CSKYMCInstLower::Lower</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaimcinstlower/#ada3cf8f523e66ab2658f5c59e0727ed8">llvm::LanaiMCInstLower::Lower</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kmcinstlower/#aaa1ed5df03c02ae5e378bd14aee41269">llvm::M68kMCInstLower::Lower</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcinstlower/#a2a3cc3a492be3cc4387ef82e0d8dfe0e">llvm::MipsMCInstLower::Lower</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430mcinstlower/#a0da8c32a960fd10c2f6cb034954b3924">llvm::MSP430MCInstLower::Lower</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoremcinstlower/#a8f709fd6f997a78bea1acde1c948f9a1">llvm::XCoreMCInstLower::Lower</a>, <a href="/web-llvm/docs/api/classes/amdgpumcinstlower/#ae4383929e7fb1cdba8806d6f68af926b">AMDGPUMCInstLower::lower</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600mcinstlower-cpp-/r600mcinstlower/#a29af2a29429bdbd8546d4cb8b78daacc">anonymous{R600MCInstLower.cpp}::R600MCInstLower::lower</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvmcinstlower/#a6d050903b1d4eb1403389e782f6cec1c">llvm::SPIRVMCInstLower::lower</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmcinstlower/#a4d03b8ca910d6fc73430a83a0ebb2d74">llvm::SystemZMCInstLower::lower</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblymcinstlower/#a62aefd0bed5ed9cd5a154bf4d4074a22">llvm::WebAssemblyMCInstLower::lower</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzasmprinter-cpp/#a431a7ed17e60d8c815ffab3efbbe0a4b">lowerAlignmentHint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9f28245e9d46c733c5ac7db5a5fbe27e">llvm::LowerARMMachineInstrToMCInst</a>, <a href="/web-llvm/docs/api/classes/llvm/avrmcinstlower/#a984878b12749e1f06574b379915f8524">llvm::AVRMCInstLower::lowerInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmccodeemitter-cpp/#ac23d02bf8c91f40857c9b136d4a1c1a1">LowerLargeShift</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a270b87ff1685fe3629f8ad9ed69d7101">llvm::lowerLoongArchMachineInstrToMCInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a75665dd8dc7cd6ec1cb1f06a34ebb042">llvm::LowerPPCMachineInstrToMCInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp/#af3b87eccd7dfd84ba438253014223161">lowerRISCVVMachineInstrToMCInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa50085956029a8612301d43b0c2784f1">llvm::LowerSparcMachineInstrToMCInst</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#a3ee8d8bf08607adec1b75768f39fa399">llvm::XtensaAsmPrinter::lowerToMCInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b171d9e10d6ab46824855e1cc83e737">llvm::LowerVEMachineInstrToMCInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/asmparser/hexagonasmparser-cpp/#a9d6cfc8fde9d13ec8da254c0493603ed">makeCombineInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#abeebd6c3e48c1d92d186d8ffafbf5e2b">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::matchAndEmitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#aef83676a470a77d6e089737fb024de94">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::outputAnnotations</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#adac6a6f0dd9ecdd7b774da11940ce88b">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::outputDebugSourceAndStrings</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#afc046e9fee2ff69250264feef8baaf15">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::outputExecutionMode</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#abc68a425d6211a1b46e2df470bf12439">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::outputExecutionModeFromMDNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#add0594bfc35119c8d898c51bb3697823">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::outputExecutionModeFromNumthreadsAttribute</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#ac9d0742eff167655206896feab35cd4b">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::outputGlobalRequirements</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#a996dc62cedd72ad61d739065da84a232">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::outputOpExtInstImports</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#aa9ff97cd854e60b8561792b2b3fd2d0f">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::outputOpFunctionEnd</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#a4f4a667381f5644b8c90d6e9c78642b9">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::outputOpMemoryModel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a2cb3beb5a3e71a3b94697f7083f2e4be">llvm::HexagonMCInstrInfo::padEndloop</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a97d0066eae87ce228a58774409c88425">llvm::ARMInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmbackend-cpp-/amdgpuasmbackend/#a8731b38926f3641bcc445b9ba27e74be">anonymous{AMDGPUAsmBackend.cpp}::AMDGPUAsmBackend::relaxInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#af22c9938ad82cf97ee6cc8cf00d265cc">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::relaxInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmbackend-cpp-/m68kasmbackend/#a86fcebca1ff924c7d38226f00c8e3622">anonymous{M68kAsmBackend.cpp}::M68kAsmBackend::relaxInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#a85095bdb81f7b2460ce2b158985cdfa9">anonymous{X86AsmBackend.cpp}::X86AsmBackend::relaxInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmbackend/#ad50e8c99a8ff188846367ea1a9ae2143">llvm::ARMAsmBackend::relaxInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyasmbackend/#ade0613efda90a350f47392d0b721b1f8">llvm::CSKYAsmBackend::relaxInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a358ac79e04af2c8c34fa5084fa46cfee">llvm::RISCVAsmBackend::relaxInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymcinstlower-cpp/#a35043b20e128ef142a010db3ff501a17">removeRegisterOperands</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ae99d82425a463a5dd5413112fda5ed17">translateInstruction</a>.</p>

</div>
</div>

### size() {#ae534d5d22096b2665d16e5ab600ebbce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::MCInst::size ()</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a246da06f2e49f678663ae6e21bedffb3">llvm::HexagonMCInstrInfo::bundleSize</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a38abdd95e7f5b6e9f4fc534bb392f8b8">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtExp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a69d33e060c5b0bbfe0f8a2cbeb71f598">llvm::HexagonMCInstrInfo::isBundle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a6ca1ea5b42b7c51b90376ec8262db074">llvm::HexagonMCInstrInfo::minConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#abd317698bbd34d1cb4e69a49141dab58">llvm::HexagonMCInstrInfo::replaceDuplex</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a65fdd614c206400e24b2676a71daac1c">llvm::HexagonMCInstrInfo::tryCompound</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Flags {#aab8ea63e2c999f11dce03739b9e379b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCInst::Flags = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a>.</p>

</div>
</div>

### Loc {#ac99e50fe6f794796794a3817e158fbe4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc llvm::MCInst::Loc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a>.</p>

</div>
</div>

### Opcode {#a8f21ce68a58349cd2b2b57a3195a08c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCInst::Opcode = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a>.</p>

</div>
</div>

### Operands {#ae7fdc16e0c56a7d8a1867cbd6930773f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MCOperand, 6&gt; llvm::MCInst::Operands</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">MCInst.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcinst-cpp">MCInst.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
