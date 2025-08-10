---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/elfobjectwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ELFObjectWriter` Class



## Declaration

<div class="doxyDeclaration">
class llvm::ELFObjectWriter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">llvm/MC/MCELFObjectWriter.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter">MCObjectWriter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Defines the object file and target independent interfaces used by the assembler backend to write native file format object files. <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a033022b18a55aaa384c6fb1797583cd8">ELFObjectWriter</a> (std::unique_ptr&lt; MCELFObjectTargetWriter &gt; MOTW, raw_pwrite_stream &amp;OS, bool IsLittleEndian)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcfff79efb9dcea8449ea05477576c2a">ELFObjectWriter</a> (std::unique_ptr&lt; MCELFObjectTargetWriter &gt; MOTW, raw_pwrite_stream &amp;OS, raw_pwrite_stream &amp;DwoOS, bool IsLittleEndian)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5162bfa45db4fd05ba9e41044cfc7da9">reset</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>lifetime management <a href="#a5162bfa45db4fd05ba9e41044cfc7da9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a481e97810e8743a7c0f25a51dbcad8c1">executePostLayoutBinding</a> (MCAssembler &amp;Asm) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform any late binding of symbols (for example, to assign symbol indices for use when generating relocations). <a href="#a481e97810e8743a7c0f25a51dbcad8c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73aed7794053594cfb9536d55eac30fd">recordRelocation</a> (MCAssembler &amp;Asm, const MCFragment *Fragment, const MCFixup &amp;Fixup, MCValue Target, uint64_t &amp;FixedValue) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> a relocation entry. <a href="#a73aed7794053594cfb9536d55eac30fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2d01e55341f0be3c3d62a8346dc4807">isSymbolRefDifferenceFullyResolvedImpl</a> (const MCAssembler &amp;Asm, const MCSymbol &amp;SymA, const MCFragment &amp;FB, bool InSet, bool IsPCRel) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4056ea540d0a44a99e87763a256fac2e">writeObject</a> (MCAssembler &amp;Asm) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the object file and returns the number of bytes written. <a href="#a4056ea540d0a44a99e87763a256fac2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac49bf4bfafa56380ee8dccfc4076c290">hasRelocationAddend</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1d4d772f1ae1ed6488491408a1244a4">usesRela</a> (const MCTargetOptions *TO, const MCSectionELF &amp;Sec) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f3abd737c618cd14f32c74a1ac03ef1">shouldRelocateWithSymbol</a> (const MCAssembler &amp;Asm, const MCValue &amp;Val, const MCSymbolELF *Sym, uint64_t C, unsigned Type) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec678d26512f5d62ccedf4941b13c954">checkRelocation</a> (MCContext &amp;Ctx, SMLoc Loc, const MCSectionELF *From, const MCSectionELF *To)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33212890ff45c137c0efbd25f1cdacfc">getELFHeaderEFlags</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d19b60f2ecf6cd909a3b5cd7f8f93a5">setELFHeaderEFlags</a> (unsigned Flags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a286c4bf793b9b65b5ad50051e73e7137">markGnuAbi</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77f03ee1de505d1c93100a537aa83132">seenGnuAbi</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5da90630926c228a4d9740ba2776e353">setOverrideABIVersion</a> (uint8_t V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcelfobjecttargetwriter">MCELFObjectTargetWriter</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02dad1fcfb973d2121b2e7567b598f62">TargetObjectWriter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f1491eb40df95facc4bfbb33c584e0c">OS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec9a6dc0548d7b00708ff53c4bdc78c4">DwoOS</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf">MCSectionELF</a> *, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/elfrelocationentry">ELFRelocationEntry</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a1379734cf96ac1be3f482b563063c9">Relocations</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf">MCSymbolELF</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf">MCSymbolELF</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7cd8330c99457d825d6fbab0bb31bd8">Renames</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e01f143765fc5a890ba733be83e3b63">IsLittleEndian</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a623d9c1149f65288accebd4a5e120de2">SeenGnuAbi</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fec30050565f48e54ef91ab3980d170">OverrideABIVersion</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/elfobjectwriter/symver">Symver</a>, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a763138e66c59d79b02484292292fc5">Symvers</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a382f78ed3144d55e8b75423b6d5a5025">ELFHeaderEFlags</a> = 0</td>
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


<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">MCELFObjectWriter.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ELFObjectWriter() {#a033022b18a55aaa384c6fb1797583cd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ELFObjectWriter::ELFObjectWriter (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcelfobjecttargetwriter">MCELFObjectTargetWriter</a> &gt; MOTW, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> &amp; OS, bool IsLittleEndian)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">MCELFObjectWriter.h</a>, definition at line 1161 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>References <a href="#a8e01f143765fc5a890ba733be83e3b63">IsLittleEndian</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="#a9f1491eb40df95facc4bfbb33c584e0c">OS</a> and <a href="#a02dad1fcfb973d2121b2e7567b598f62">TargetObjectWriter</a>.</p>

</div>
</div>

### ELFObjectWriter() {#adcfff79efb9dcea8449ea05477576c2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ELFObjectWriter::ELFObjectWriter (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcelfobjecttargetwriter">MCELFObjectTargetWriter</a> &gt; MOTW, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> &amp; DwoOS, bool IsLittleEndian)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">MCELFObjectWriter.h</a>, definition at line 1165 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>References <a href="#aec9a6dc0548d7b00708ff53c4bdc78c4">DwoOS</a>, <a href="#a8e01f143765fc5a890ba733be83e3b63">IsLittleEndian</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="#a9f1491eb40df95facc4bfbb33c584e0c">OS</a> and <a href="#a02dad1fcfb973d2121b2e7567b598f62">TargetObjectWriter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### checkRelocation() {#aec678d26512f5d62ccedf4941b13c954}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ELFObjectWriter::checkRelocation (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf">MCSectionELF</a> * From, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf">MCSectionELF</a> * To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">MCELFObjectWriter.h</a>, definition at line 1373 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>References <a href="#aec9a6dc0548d7b00708ff53c4bdc78c4">DwoOS</a> and <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp/#a7ae7754aaf6513bc0ea0bd5f457fe7cc">isDwoSection</a>.</p>


<p>Referenced by <a href="#a73aed7794053594cfb9536d55eac30fd">recordRelocation</a>.</p>

</div>
</div>

### executePostLayoutBinding() {#a481e97810e8743a7c0f25a51dbcad8c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFObjectWriter::executePostLayoutBinding (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
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

<p>Perform any late binding of symbols (for example, to assign symbol indices for use when generating relocations).</p>


<p>This routine is called by the assembler after layout and relaxation is complete.</p>


<p>Declaration at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">MCELFObjectWriter.h</a>, definition at line 1185 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter/#ad8f0d8365474cd2e6ff0e8304ee30383">llvm::MCObjectWriter::AddrsigSyms</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aab312a8386488873bac2eddfc67c22be">llvm::StringRef::find</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a>, <a href="#af7cd8330c99457d825d6fbab0bb31bd8">Renames</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>, <a href="#a9a763138e66c59d79b02484292292fc5">Symvers</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cad6e9c0ff694f0fca0222e79e772b647e">llvm::CallingConv::Tail</a>.</p>

</div>
</div>

### getELFHeaderEFlags() {#a33212890ff45c137c0efbd25f1cdacfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ELFObjectWriter::getELFHeaderEFlags ()</td>
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



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">MCELFObjectWriter.h</a>.</p>

</div>
</div>

### hasRelocationAddend() {#ac49bf4bfafa56380ee8dccfc4076c290}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ELFObjectWriter::hasRelocationAddend ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">MCELFObjectWriter.h</a>, definition at line 1181 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>Reference <a href="#a02dad1fcfb973d2121b2e7567b598f62">TargetObjectWriter</a>.</p>


<p>Referenced by <a href="#a3f3abd737c618cd14f32c74a1ac03ef1">shouldRelocateWithSymbol</a> and <a href="#af1d4d772f1ae1ed6488491408a1244a4">usesRela</a>.</p>

</div>
</div>

### isSymbolRefDifferenceFullyResolvedImpl() {#ac2d01e55341f0be3c3d62a8346dc4807}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ELFObjectWriter::isSymbolRefDifferenceFullyResolvedImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; SymA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> &amp; FB, bool InSet, bool IsPCRel)</td>
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



<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">MCELFObjectWriter.h</a>, definition at line 1487 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#a7b98ffc5ede97acf84a20b7476d3ffff">llvm::MCFragment::getParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77a492b026d2205f6f178f7eb7863018e31">llvm::ELF::STB_LOCAL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a7269ceaea4bf3dbd15caa427598cbcb9">llvm::ELF::STT_GNU_IFUNC</a>.</p>

</div>
</div>

### markGnuAbi() {#a286c4bf793b9b65b5ad50051e73e7137}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ELFObjectWriter::markGnuAbi ()</td>
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



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">MCELFObjectWriter.h</a>.</p>


<p>Reference <a href="#a623d9c1149f65288accebd4a5e120de2">SeenGnuAbi</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a1f4f0489eaa2133da3944177f6646130">llvm::MCELFStreamer::changeSection</a> and <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#acfe4f94dca14855495d5743fc3e60998">llvm::MCELFStreamer::emitSymbolAttribute</a>.</p>

</div>
</div>

### recordRelocation() {#a73aed7794053594cfb9536d55eac30fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFObjectWriter::recordRelocation (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> * Fragment, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> Target, uint64_t &amp; FixedValue)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> a relocation entry.</p>


<p>This routine is called by the assembler after layout and relaxation, and post layout binding. The implementation is responsible for storing information about the relocation so that it can be emitted during <a href="#a4056ea540d0a44a99e87763a256fac2e">writeObject()</a>.</p>


<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">MCELFObjectWriter.h</a>, definition at line 1389 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#aec678d26512f5d62ccedf4941b13c954">checkRelocation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo/#a8f6613f5c0a6dc7dfebce3761963659da9bd8af688090f2f81c405bd995079007">llvm::MCFixupKindInfo::FKF_IsPCRel</a>, <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo/#ae92461ded3785b1595f975afc7d42cb9">llvm::MCFixupKindInfo::Flags</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#ac690da7fe3ddf1862812d82c36a02766">llvm::MCSection::getBeginSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#ad4777f004ef52f665e6ec6defc1cb32a">llvm::MCAsmBackend::getFixupKindInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#a7b98ffc5ede97acf84a20b7476d3ffff">llvm::MCFragment::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a048f077746d95f142d02e56586862bf2">llvm::MCSymbolRefExpr::getSymbol</a>, <a href="#a7a1379734cf96ac1be3f482b563063c9">Relocations</a>, <a href="#af7cd8330c99457d825d6fbab0bb31bd8">Renames</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#a9bbad98aac843f2c52cd716efdde45e5">llvm::MCSymbolELF::setIsWeakrefUsedInReloc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#aa9241f6f7d54c02902a249fb72ea6295">llvm::MCSymbol::setUsedInReloc</a>, <a href="#a3f3abd737c618cd14f32c74a1ac03ef1">shouldRelocateWithSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca3b34c61cc0e95c91405e13c12da52925">llvm::ELF::SHT_LLVM_CALL_GRAPH_PROFILE</a>, <a href="#a02dad1fcfb973d2121b2e7567b598f62">TargetObjectWriter</a>, <a href="#af1d4d772f1ae1ed6488491408a1244a4">usesRela</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a4acec19f33bc45f90643617e00ce9a81">llvm::MCSymbolRefExpr::VK_WEAKREF</a>.</p>

</div>
</div>

### reset() {#a5162bfa45db4fd05ba9e41044cfc7da9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFObjectWriter::reset ()</td>
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

<p>lifetime management</p>

<p>Declaration at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">MCELFObjectWriter.h</a>, definition at line 1171 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>References <a href="#a6fec30050565f48e54ef91ab3980d170">OverrideABIVersion</a>, <a href="#a7a1379734cf96ac1be3f482b563063c9">Relocations</a>, <a href="#af7cd8330c99457d825d6fbab0bb31bd8">Renames</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter/#a9007366cbf9e6c4f72f284ceabb104ad">llvm::MCObjectWriter::reset</a>, <a href="#a623d9c1149f65288accebd4a5e120de2">SeenGnuAbi</a> and <a href="#a9a763138e66c59d79b02484292292fc5">Symvers</a>.</p>

</div>
</div>

### seenGnuAbi() {#a77f03ee1de505d1c93100a537aa83132}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ELFObjectWriter::seenGnuAbi ()</td>
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



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">MCELFObjectWriter.h</a>.</p>


<p>Reference <a href="#a623d9c1149f65288accebd4a5e120de2">SeenGnuAbi</a>.</p>

</div>
</div>

### setELFHeaderEFlags() {#a5d19b60f2ecf6cd909a3b5cd7f8f93a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ELFObjectWriter::setELFHeaderEFlags (unsigned Flags)</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">MCELFObjectWriter.h</a>.</p>

</div>
</div>

### setOverrideABIVersion() {#a5da90630926c228a4d9740ba2776e353}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ELFObjectWriter::setOverrideABIVersion (uint8_t V)</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">MCELFObjectWriter.h</a>.</p>


<p>Reference <a href="#a6fec30050565f48e54ef91ab3980d170">OverrideABIVersion</a>.</p>

</div>
</div>

### shouldRelocateWithSymbol() {#a3f3abd737c618cd14f32c74a1ac03ef1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ELFObjectWriter::shouldRelocateWithSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf">MCSymbolELF</a> * Sym, uint64_t C, unsigned Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">MCELFObjectWriter.h</a>, definition at line 1244 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030da6a266f492c600d97849933aad5356be4">llvm::ELF::EM_386</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030daaf29cd80fceba94e4f48b143fcf354c6">llvm::ELF::EM_MIPS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#ae357568bfa7baaa244f16208924f4637">llvm::MCSymbolELF::getBinding</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#ad860e326e495f296cdee70606908a6b1">llvm::MCSymbolRefExpr::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#ab7d669d1338ce8b4ddf910da10c51607">llvm::MCSymbol::getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#aced07a0d8eb8031ff0c2a6d691277667">llvm::MCValue::getSymA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#a2c716684711cb83467c2138bc4e84454">llvm::MCSymbolELF::getType</a>, <a href="#ac49bf4bfafa56380ee8dccfc4076c290">hasRelocationAddend</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a3214f95c05e3d2af5e3e56667dc54239">llvm::MCSymbol::isInSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#a27d141d83c2f705e53214a5e6bb84e83">llvm::MCSymbolELF::isMemtag</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#aa462dae167e31cac32e97bb0c77ab071">llvm::MCSymbol::isUndefined</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a0e54850eb2f8e74ae549f6dd70926723">llvm::ELF::SHF_MERGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015af09f8799cc15fd856ff2284c7519d6d8">llvm::ELF::SHF_TLS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77a3056225276d5d76c1b142d3505704851">llvm::ELF::STB_GLOBAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77af266d61f5074811ef82444eeeff11c89">llvm::ELF::STB_GNU_UNIQUE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77a492b026d2205f6f178f7eb7863018e31">llvm::ELF::STB_LOCAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77afb3fa0269fc31b10834def07f16c1649">llvm::ELF::STB_WEAK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a7269ceaea4bf3dbd15caa427598cbcb9">llvm::ELF::STT_GNU_IFUNC</a>, <a href="#a02dad1fcfb973d2121b2e7567b598f62">TargetObjectWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aa780672c4378b10a1ef6094a4c46de10">llvm::MCSymbolRefExpr::VK_GOT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a2a25c9a7112bb84b5d93e6ab5d0d8185">llvm::MCSymbolRefExpr::VK_GOTPCREL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a2f5bfabdc7c07641d263e7f3921de0f5">llvm::MCSymbolRefExpr::VK_GOTPCREL_NORELAX</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ab5951d4b3308f406e60e2bf743b14ca4">llvm::MCSymbolRefExpr::VK_PLT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a23004891138ddce80497bebc9e47c3cd">llvm::MCSymbolRefExpr::VK_PPC_GOT_HA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a0adbb1cf9b46d88694e78fad77ebc014">llvm::MCSymbolRefExpr::VK_PPC_GOT_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ad179e874cf4e309b0e9b955967f12371">llvm::MCSymbolRefExpr::VK_PPC_GOT_LO</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a6cd4a312e47b0e61f2dcabb3889abe66">llvm::MCSymbolRefExpr::VK_PPC_TOCBASE</a>.</p>


<p>Referenced by <a href="#a73aed7794053594cfb9536d55eac30fd">recordRelocation</a>.</p>

</div>
</div>

### usesRela() {#af1d4d772f1ae1ed6488491408a1244a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ELFObjectWriter::usesRela (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions">MCTargetOptions</a> * TO, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf">MCSectionELF</a> &amp; Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">MCELFObjectWriter.h</a>, definition at line 1480 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions/#a3c88d87144f11ed223126c42717b91c3">llvm::MCTargetOptions::Crel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf/#adeff0e0ca239da330d94098c50b6cbdd">llvm::MCSectionELF::getType</a>, <a href="#ac49bf4bfafa56380ee8dccfc4076c290">hasRelocationAddend</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca3b34c61cc0e95c91405e13c12da52925">llvm::ELF::SHT_LLVM_CALL_GRAPH_PROFILE</a>.</p>


<p>Referenced by <a href="#a73aed7794053594cfb9536d55eac30fd">recordRelocation</a>.</p>

</div>
</div>

### writeObject() {#a4056ea540d0a44a99e87763a256fac2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t ELFObjectWriter::writeObject (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
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

<p>Write the object file and returns the number of bytes written.</p>


<p>This routine is called by the assembler after layout and relaxation is complete, fixups have been evaluated and applied, and relocations generated.</p>


<p>Declaration at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">MCELFObjectWriter.h</a>, definition at line 1500 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#a42c738c6458b934218c327bf6be7b60dac7a0514ed65ec7e07a8516a4502882e3">anonymous{ELFObjectWriter.cpp}::ELFWriter::AllSections</a>, <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#a42c738c6458b934218c327bf6be7b60da2f5553c6916ebe158aa60fe17820139d">anonymous{ELFObjectWriter.cpp}::ELFWriter::DwoOnly</a>, <a href="#aec9a6dc0548d7b00708ff53c4bdc78c4">DwoOS</a>, <a href="#a8e01f143765fc5a890ba733be83e3b63">IsLittleEndian</a>, <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#a42c738c6458b934218c327bf6be7b60da6fa36e4733e59cacece4264d2e291dc5">anonymous{ELFObjectWriter.cpp}::ELFWriter::NonDwoOnly</a>, <a href="#a9f1491eb40df95facc4bfbb33c584e0c">OS</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DwoOS {#aec9a6dc0548d7b00708ff53c4bdc78c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_pwrite_stream* llvm::ELFObjectWriter::DwoOS = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">MCELFObjectWriter.h</a>.</p>


<p>Referenced by <a href="#aec678d26512f5d62ccedf4941b13c954">checkRelocation</a>, <a href="#adcfff79efb9dcea8449ea05477576c2a">ELFObjectWriter</a> and <a href="#a4056ea540d0a44a99e87763a256fac2e">writeObject</a>.</p>

</div>
</div>

### IsLittleEndian {#a8e01f143765fc5a890ba733be83e3b63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ELFObjectWriter::IsLittleEndian = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">MCELFObjectWriter.h</a>.</p>


<p>Referenced by <a href="#a033022b18a55aaa384c6fb1797583cd8">ELFObjectWriter</a>, <a href="#adcfff79efb9dcea8449ea05477576c2a">ELFObjectWriter</a> and <a href="#a4056ea540d0a44a99e87763a256fac2e">writeObject</a>.</p>

</div>
</div>

### OS {#a9f1491eb40df95facc4bfbb33c584e0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_pwrite_stream&amp; llvm::ELFObjectWriter::OS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">MCELFObjectWriter.h</a>.</p>


<p>Referenced by <a href="#a033022b18a55aaa384c6fb1797583cd8">ELFObjectWriter</a>, <a href="#adcfff79efb9dcea8449ea05477576c2a">ELFObjectWriter</a> and <a href="#a4056ea540d0a44a99e87763a256fac2e">writeObject</a>.</p>

</div>
</div>

### OverrideABIVersion {#a6fec30050565f48e54ef91ab3980d170}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint8_t&gt; llvm::ELFObjectWriter::OverrideABIVersion</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">MCELFObjectWriter.h</a>.</p>


<p>Referenced by <a href="#a5162bfa45db4fd05ba9e41044cfc7da9">reset</a> and <a href="#a5da90630926c228a4d9740ba2776e353">setOverrideABIVersion</a>.</p>

</div>
</div>

### Relocations {#a7a1379734cf96ac1be3f482b563063c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MCSectionELF *, std::vector&lt;ELFRelocationEntry&gt; &gt; llvm::ELFObjectWriter::Relocations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">MCELFObjectWriter.h</a>.</p>


<p>Referenced by <a href="#a73aed7794053594cfb9536d55eac30fd">recordRelocation</a> and <a href="#a5162bfa45db4fd05ba9e41044cfc7da9">reset</a>.</p>

</div>
</div>

### Renames {#af7cd8330c99457d825d6fbab0bb31bd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MCSymbolELF *, const MCSymbolELF *&gt; llvm::ELFObjectWriter::Renames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">MCELFObjectWriter.h</a>.</p>


<p>Referenced by <a href="#a481e97810e8743a7c0f25a51dbcad8c1">executePostLayoutBinding</a>, <a href="#a73aed7794053594cfb9536d55eac30fd">recordRelocation</a> and <a href="#a5162bfa45db4fd05ba9e41044cfc7da9">reset</a>.</p>

</div>
</div>

### SeenGnuAbi {#a623d9c1149f65288accebd4a5e120de2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ELFObjectWriter::SeenGnuAbi = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">MCELFObjectWriter.h</a>.</p>


<p>Referenced by <a href="#a286c4bf793b9b65b5ad50051e73e7137">markGnuAbi</a>, <a href="#a5162bfa45db4fd05ba9e41044cfc7da9">reset</a> and <a href="#a77f03ee1de505d1c93100a537aa83132">seenGnuAbi</a>.</p>

</div>
</div>

### Symvers {#a9a763138e66c59d79b02484292292fc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Symver, 0&gt; llvm::ELFObjectWriter::Symvers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">MCELFObjectWriter.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a76008de89dd2e472d78c4a8ca9771d45">llvm::MCELFStreamer::emitELFSymverDirective</a>, <a href="#a481e97810e8743a7c0f25a51dbcad8c1">executePostLayoutBinding</a> and <a href="#a5162bfa45db4fd05ba9e41044cfc7da9">reset</a>.</p>

</div>
</div>

### TargetObjectWriter {#a02dad1fcfb973d2121b2e7567b598f62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MCELFObjectTargetWriter&gt; llvm::ELFObjectWriter::TargetObjectWriter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">MCELFObjectWriter.h</a>.</p>


<p>Referenced by <a href="#a033022b18a55aaa384c6fb1797583cd8">ELFObjectWriter</a>, <a href="#adcfff79efb9dcea8449ea05477576c2a">ELFObjectWriter</a>, <a href="#ac49bf4bfafa56380ee8dccfc4076c290">hasRelocationAddend</a>, <a href="#a73aed7794053594cfb9536d55eac30fd">recordRelocation</a> and <a href="#a3f3abd737c618cd14f32c74a1ac03ef1">shouldRelocateWithSymbol</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ELFHeaderEFlags {#a382f78ed3144d55e8b75423b6d5a5025}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ELFObjectWriter::ELFHeaderEFlags = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">MCELFObjectWriter.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">MCELFObjectWriter.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
