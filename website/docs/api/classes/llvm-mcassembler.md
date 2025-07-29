---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcassembler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MCAssembler` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MCAssembler { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">llvm/MC/MCAssembler.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a100d947951334b8e15c0558a8e4ce7dc">SectionListType</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *, 0 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0ab0a214e553956de28581f3623f373">const_iterator</a> = <a href="/web-llvm/docs/api/structs/llvm/pointee-iterator">pointee_iterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#aa11b903431c1931920939bac6b5293a2">SectionListType::const_iterator</a> &gt;</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6e8cef6c5051dbdff8ebb7d53312d95">MCObjectWriter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab0f3e55fcc3bb2b4c6ae18ca38e6e24">MCAssembler</a> (MCContext &amp;Context, std::unique_ptr&lt; MCAsmBackend &gt; Backend, std::unique_ptr&lt; MCCodeEmitter &gt; Emitter, std::unique_ptr&lt; MCObjectWriter &gt; Writer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a new assembler instance. <a href="#aab0f3e55fcc3bb2b4c6ae18ca38e6e24">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89a1f9804c419e942ca4c5f064f0350d">MCAssembler</a> (const MCAssembler &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b6dcc44b8ca342110669a7d4cb80b19">operator=</a> (const MCAssembler &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc4d6b7d638e45034130bc3ab18e5be6">computeFragmentSize</a> (const MCFragment &amp;F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the effective fragment size. <a href="#abc4d6b7d638e45034130bc3ab18e5be6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fd3ef6690dbde3a5840707d439b5a22">layoutBundle</a> (MCFragment *Prev, MCFragment *F) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a082b39e969e2a698446f8f8b27ddb411">ensureValid</a> (MCSection &amp;Sec) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a4ff084961e27ad1fc9ff6f59d3f8ee">getFragmentOffset</a> (const MCFragment &amp;F) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a087b12083e027a47db241b0b3fbdce28">getSectionAddressSize</a> (const MCSection &amp;Sec) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1f09d354ee1d85dc432472549170b87">getSectionFileSize</a> (const MCSection &amp;Sec) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0798a5faed48d2937c8974af40cebc8b">getSymbolOffset</a> (const MCSymbol &amp;S, uint64_t &amp;Val) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c59aaf4ea314841ff5d61598fdfa477">getSymbolOffset</a> (const MCSymbol &amp;S) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac06af0994b284d9e18c3b90c7c500a03">getBaseSymbol</a> (const MCSymbol &amp;Symbol) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a301492f7142fbc3744cc1c5a86f5ec">writeSectionData</a> (raw_ostream &amp;OS, const MCSection *Section) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the section contents to <span class="doxyComputerOutput">OS</span>. <a href="#a2a301492f7142fbc3744cc1c5a86f5ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf5208586509a15c29239a946b2a1236">isThumbFunc</a> (const MCSymbol *Func) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether a given symbol has been flagged with .thumb_func. <a href="#aaf5208586509a15c29239a946b2a1236">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a202fda2877307a61a19b55fcd18765c1">setIsThumbFunc</a> (const MCSymbol *Func)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag a function symbol as the target of a .thumb_func directive. <a href="#a202fda2877307a61a19b55fcd18765c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad86e6a338edf76035209bf618067cf1d">reset</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reuse an assembler instance. <a href="#ad86e6a338edf76035209bf618067cf1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0675ed1bdbf987d94ef2360cb18c6eae">getContext</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2b513ce2e0d6eddaf628d3f7d7ee57b">getBackendPtr</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a751b495bbd855f8fa28e98a3619c898a">getEmitterPtr</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab01b807c062ac4610366c6772ad5fd16">getBackend</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a923971fae5bb26b2613d5b17ce09ac8e">getEmitter</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter">MCObjectWriter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56c45e3acce6f7b060bed7e40398d207">getWriter</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableparams">MCDwarfLineTableParams</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecd1dfc9a1400558c39c47db568964ca">getDWARFLinetableParams</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b9abcba24c548dbd22f928b184048fe">Finish</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finish - Do final processing and write the object to the output stream. <a href="#a0b9abcba24c548dbd22f928b184048fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4172c40c16e915c478ab94311e76e1a8">layout</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea907130afe6d413ca5898a9350a1175">hasLayout</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a815cbd2043a1094e14315a02e879a7fa">getRelaxAll</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef73095e90bd2b9606c693612c7571cd">setRelaxAll</a> (bool Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1596e2e10c33712e8e3c1bd733bcda1e">isBundlingEnabled</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1228ea3bb214c9c0e513c582ccfd09bf">getBundleAlignSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1af560393c21ce83e6ecea7b8475c428">setBundleAlignSize</a> (unsigned Size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac0ab0a214e553956de28581f3623f373">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04dc085a303532042fddeb1bc2d56a63">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac0ab0a214e553956de28581f3623f373">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab004bdc24b67debe04f555f4277124c0">end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80f8733f1d25b99133339ecb6223ab9f">getSymbols</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/pointee-iterator">pointee_iterator</a>&lt; typename <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, 0 &gt;::const_iterator &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad08c6564acd34ce855c1bb576c9edd6a">symbols</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6760ad43200e0c9da408d84eeb89f64">registerSection</a> (MCSection &amp;Section)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae26e9b713a9b85d7a56343c78794269c">registerSymbol</a> (const MCSymbol &amp;Symbol)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed080c421ef7325c6e04a5bf027d9044">writeFragmentPadding</a> (raw_ostream &amp;OS, const MCEncodedFragment &amp;F, uint64_t FSize) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the necessary bundle padding to <span class="doxyComputerOutput">OS</span>. <a href="#aed080c421ef7325c6e04a5bf027d9044">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a68266def3072d13b2cafb555b9e28c">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34670d9dbd338658ac3fb3b313ba9e31">evaluateFixup</a> (const MCFixup &amp;Fixup, const MCFragment *DF, MCValue &amp;Target, const MCSubtargetInfo *STI, uint64_t &amp;Value, bool &amp;WasForced) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Evaluate a fixup to a relocatable expression and the value which should be placed into the fixup. <a href="#a34670d9dbd338658ac3fb3b313ba9e31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7f1cf34bd94f1fb4c1f59f6d24698ee">fixupNeedsRelaxation</a> (const MCFixup &amp;Fixup, const MCRelaxableFragment *DF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether a fixup can be satisfied, or whether it needs to be relaxed (increased in size, in order to hold its value correctly). <a href="#ae7f1cf34bd94f1fb4c1f59f6d24698ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0203c34dad1ebe514a25fd9fbb64b681">fragmentNeedsRelaxation</a> (const MCRelaxableFragment *IF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the given fragment needs relaxation. <a href="#a0203c34dad1ebe514a25fd9fbb64b681">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1673ed73dc8dc4815a874d398bc402db">layoutOnce</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform one layout iteration and return true if any offsets were adjusted. <a href="#a1673ed73dc8dc4815a874d398bc402db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b3a44c22d40704a26dcad45a076c5b5">relaxFragment</a> (MCFragment &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform relaxation on a single fragment - returns true if the fragment changes as a result of relaxation. <a href="#a2b3a44c22d40704a26dcad45a076c5b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8e12915f4bb57962d001e10842d9554">relaxInstruction</a> (MCRelaxableFragment &amp;IF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b9f0e5bf413ecbd68984a392e89b191">relaxLEB</a> (MCLEBFragment &amp;IF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a712f5df203886badc60ab0240c35f2ac">relaxBoundaryAlign</a> (MCBoundaryAlignFragment &amp;BF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5090576b71802dbdbababc70c24a9978">relaxDwarfLineAddr</a> (MCDwarfLineAddrFragment &amp;DF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c7d0fe369c75cfd577af1eb57d66017">relaxDwarfCallFrameFragment</a> (MCDwarfCallFrameFragment &amp;DF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11e5a9982d680ae5fe110ef05f15dd55">relaxCVInlineLineTable</a> (MCCVInlineLineTableFragment &amp;DF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ab8fb72bab598384afc65e753d66aec">relaxCVDefRange</a> (MCCVDefRangeFragment &amp;DF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab85dff56ce066f571f9ce90aec960b9a">relaxPseudoProbeAddr</a> (MCPseudoProbeAddrFragment &amp;DF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a>, uint64_t, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a609f91b55661d4e220038cf153231f7f">handleFixup</a> (MCFragment &amp;F, const MCFixup &amp;Fixup, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5da6a2ba9b4aac52b51a629d4e609e55">Context</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3f310eeb906d60a70edf997c067f73f">Backend</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b2924018a8b299616f1d713ce584215">Emitter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter">MCObjectWriter</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afea995d073e0180f34b9b664d6bbbda8">Writer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae00418d63f8908d0e81d99b742625411">HasLayout</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3708034c3c7d14df9a3fc9dc45a381ee">RelaxAll</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a100d947951334b8e15c0558a8e4ce7dc">SectionListType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8838836c973494f33dce28de127a6eb">Sections</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af00362186405287071fed8076a33d7fb">Symbols</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableparams">MCDwarfLineTableParams</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8d0eebb1bc1558ee49389ef085e000c">LTParams</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3380917e8a8be39133641e7147867395">ThumbFuncs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of function symbols for which a .thumb_func directive has been seen. <a href="#a3380917e8a8be39133641e7147867395">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accbd40b3bbfdf0a5f8fdaf7d878f001d">BundleAlignSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The bundle alignment size currently set in the assembler. <a href="#accbd40b3bbfdf0a5f8fdaf7d878f001d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#ac0ab0a214e553956de28581f3623f373}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MCAssembler::const_iterator =  pointee_iterator&lt;SectionListType::const_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>

</div>
</div>

### SectionListType {#a100d947951334b8e15c0558a8e4ce7dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MCAssembler::SectionListType =  SmallVector&lt;MCSection *, 0&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### MCObjectWriter {#ad6e8cef6c5051dbdff8ebb7d53312d95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter">MCObjectWriter</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>


<p>Reference <a href="#ad6e8cef6c5051dbdff8ebb7d53312d95">MCObjectWriter</a>.</p>


<p>Referenced by <a href="#a56c45e3acce6f7b060bed7e40398d207">getWriter</a> and <a href="#ad6e8cef6c5051dbdff8ebb7d53312d95">MCObjectWriter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MCAssembler() {#aab0f3e55fcc3bb2b4c6ae18ca38e6e24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAssembler::MCAssembler (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Context, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> &gt; Backend, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> &gt; Emitter, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter">MCObjectWriter</a> &gt; Writer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a new assembler instance.</p>

<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>


<p>Referenced by <a href="#a89a1f9804c419e942ca4c5f064f0350d">MCAssembler</a> and <a href="#a0b6dcc44b8ca342110669a7d4cb80b19">operator=</a>.</p>

</div>
</div>

### MCAssembler() {#a89a1f9804c419e942ca4c5f064f0350d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCAssembler::MCAssembler (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>


<p>Reference <a href="#aab0f3e55fcc3bb2b4c6ae18ca38e6e24">MCAssembler</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a0b6dcc44b8ca342110669a7d4cb80b19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAssembler &amp; llvm::MCAssembler::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#aab0f3e55fcc3bb2b4c6ae18ca38e6e24">MCAssembler</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#a04dc085a303532042fddeb1bc2d56a63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::MCAssembler::begin ()</td>
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



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>

</div>
</div>

### computeFragmentSize() {#abc4d6b7d638e45034130bc3ab18e5be6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MCAssembler::computeFragmentSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the effective fragment size.</p>

<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a07235c25b41769181e0d69078b61d9d4">llvm::MCExpr::evaluateAsValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68a1f3544ccfba8bd153218f9aff934ae23">llvm::MCFragment::FT_Align</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68a79f2f5b7f9eccf921287b14be41f29ac">llvm::MCFragment::FT_BoundaryAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68a99243fc57a7beebaba062a013912846f">llvm::MCFragment::FT_CVDefRange</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68a4c741eccc3322f72bad81e89b70c9382">llvm::MCFragment::FT_CVInlineLines</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68a31f0e4803273f2184e596c87e1e05f80">llvm::MCFragment::FT_Data</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68acd75963af411400a2ed7c133a25d17a3">llvm::MCFragment::FT_Dummy</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68a01473d8036e353978ae750c8dace1a10">llvm::MCFragment::FT_Dwarf</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68a2f12197bbe6c6a91731b3828d033a212">llvm::MCFragment::FT_DwarfFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68a1d46f74bcd87621a62557b9b6fc67c4b">llvm::MCFragment::FT_Fill</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68acdb2608fe021d8fb06cf91d424f5bc53">llvm::MCFragment::FT_LEB</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68afa54da4eb8fe165449fbbd9a300903be">llvm::MCFragment::FT_Nops</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68ac39471f5e9b12943cc8249cddbacd100">llvm::MCFragment::FT_Org</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68adcbefeedb7422d13473a4df6ff1cf964">llvm::MCFragment::FT_PseudoProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68abe5194c45ead6aefe6b0882dcb6f2104">llvm::MCFragment::FT_Relaxable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68a39bf3fdfcea08fc7dc5e927aa5fce3be">llvm::MCFragment::FT_SymbolId</a>, <a href="/web-llvm/docs/api/classes/llvm/mcalignfragment/#a5169ecb5ee59e190bdbf4d08f2e4fc8f">llvm::MCAlignFragment::getAlignment</a>, <a href="#ab01b807c062ac4610366c6772ad5fd16">getBackend</a>, <a href="#ac2b513ce2e0d6eddaf628d3f7d7ee57b">getBackendPtr</a>, <a href="#a0675ed1bdbf987d94ef2360cb18c6eae">getContext</a>, <a href="#a7a4ff084961e27ad1fc9ff6f59d3f8ee">getFragmentOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mcorgfragment/#a2dedb08bc8d6c274b43a0119b41abcdc">llvm::MCOrgFragment::getLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcalignfragment/#a76a55a6f8cab8f12dcab0797f37a6802">llvm::MCAlignFragment::getMaxBytesToEmit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcorgfragment/#ad16da07bcbb71feae82516db897a0ecd">llvm::MCOrgFragment::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#a7b98ffc5ede97acf84a20b7476d3ffff">llvm::MCFragment::getParent</a>, <a href="#a0798a5faed48d2937c8974af40cebc8b">getSymbolOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mcalignfragment/#a7c89c26696bb6f507d07a41013687dbc">llvm::MCAlignFragment::hasEmitNops</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a99cdcecbadc13087f087c61809bb44f1">llvm::offsetToAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aac3107671801e6bb16ef896f382759cd">llvm::MCContext::reportError</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a95b765eaaa37732996b35ff6e60651df">llvm::MCSection::useCodeAlign</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>


<p>Referenced by <a href="#a082b39e969e2a698446f8f8b27ddb411">ensureValid</a>, <a href="#a087b12083e027a47db241b0b3fbdce28">getSectionAddressSize</a> and <a href="#a7fd3ef6690dbde3a5840707d439b5a22">layoutBundle</a>.</p>

</div>
</div>

### dump() {#a3a68266def3072d13b2cafb555b9e28c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void MCAssembler::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 1305 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a139e160072c0a4f8626e4ffaf4aa2af7">llvm::MCSection::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#aca2ff5e9eadc78b9ea7a216595933f86">llvm::MCSymbol::dump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#aab8c6e58e0fb2534a0b6289f30b1d25d">llvm::MCSymbol::getIndex</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#ad08c6564acd34ce855c1bb576c9edd6a">symbols</a>.</p>


<p>Referenced by <a href="#a4172c40c16e915c478ab94311e76e1a8">layout</a>.</p>

</div>
</div>

### end() {#ab004bdc24b67debe04f555f4277124c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::MCAssembler::end ()</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>

</div>
</div>

### ensureValid() {#a082b39e969e2a698446f8f8b27ddb411}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAssembler::ensureValid (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> &amp; Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>


<p>References <a href="#abc4d6b7d638e45034130bc3ab18e5be6">computeFragmentSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a210d8f949ccd98375e076ccd141e5b8b">llvm::MCSection::hasLayout</a>, <a href="#a1596e2e10c33712e8e3c1bd733bcda1e">isBundlingEnabled</a>, <a href="#a7fd3ef6690dbde3a5840707d439b5a22">layoutBundle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsection/#ad2bbb8680cf10b86f2d70a4f02f0334e">llvm::MCSection::setHasLayout</a>.</p>


<p>Referenced by <a href="#a7a4ff084961e27ad1fc9ff6f59d3f8ee">getFragmentOffset</a>.</p>

</div>
</div>

### Finish() {#a0b9abcba24c548dbd22f928b184048fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAssembler::Finish ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finish - Do final processing and write the object to the output stream.</p>


<p><span class="doxyComputerOutput">Writer</span> is used for custom object writer (as the <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> does), if not specified it is automatically created from backend.</p>


<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 1029 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>


<p>References <a href="#a56c45e3acce6f7b060bed7e40398d207">getWriter</a>, <a href="#a4172c40c16e915c478ab94311e76e1a8">layout</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter/#ab1d5b19bf0e12d0f42b937d7e534b797">llvm::MCObjectWriter::writeObject</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#aa8d1c93368ccaad9bdc429b25633f943">llvm::MCObjectStreamer::finishImpl</a>.</p>

</div>
</div>

### getBackend() {#ab01b807c062ac4610366c6772ad5fd16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAsmBackend &amp; llvm::MCAssembler::getBackend ()</td>
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



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#acf7b75691e086935319e3142cb2eb579">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::AddEncodingComment</a>, <a href="#abc4d6b7d638e45034130bc3ab18e5be6">computeFragmentSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a5640d211ec1318d37e76ba1c8e752d87">llvm::MCELFStreamer::emitAssemblerFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwasmstreamer/#af204e5256aa05070c36e83158c0d184f">llvm::MCWasmStreamer::emitAssemblerFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a0fc4ee7b7b03750cf55c97db751764d2">llvm::MCWinCOFFStreamer::emitAssemblerFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/mcxcoffstreamer/#a74f3eb9157be6847f5bf0f9cd228ad01">llvm::MCXCOFFStreamer::emitXCOFFRefDirective</a>, <a href="#a4172c40c16e915c478ab94311e76e1a8">layout</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetelfstreamer/#aedd14021422c2f6fba707ef8188d6d28">llvm::LoongArchTargetELFStreamer::LoongArchTargetELFStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetelfstreamer/#a9c657032eafd38a8fa07606efe9af3a7">llvm::RISCVTargetELFStreamer::RISCVTargetELFStreamer</a> and <a href="#aed080c421ef7325c6e04a5bf027d9044">writeFragmentPadding</a>.</p>

</div>
</div>

### getBackendPtr() {#ac2b513ce2e0d6eddaf628d3f7d7ee57b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAsmBackend * llvm::MCAssembler::getBackendPtr ()</td>
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



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>


<p>Referenced by <a href="#abc4d6b7d638e45034130bc3ab18e5be6">computeFragmentSize</a>, <a href="#a4172c40c16e915c478ab94311e76e1a8">layout</a>, <a href="#ad86e6a338edf76035209bf618067cf1d">reset</a>, <a href="#aed080c421ef7325c6e04a5bf027d9044">writeFragmentPadding</a> and <a href="#a2a301492f7142fbc3744cc1c5a86f5ec">writeSectionData</a>.</p>

</div>
</div>

### getBaseSymbol() {#ac06af0994b284d9e18c3b90c7c500a03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbol * MCAssembler::getBaseSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; Symbol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 506 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a07235c25b41769181e0d69078b61d9d4">llvm::MCExpr::evaluateAsValue</a>, <a href="#a0675ed1bdbf987d94ef2360cb18c6eae">getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#afc4237f50d652cdefff412b2c780c369">llvm::MCExpr::getLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a57c7b2b9784361914262eeb0a6f0b18d">llvm::MCSymbol::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a048f077746d95f142d02e56586862bf2">llvm::MCSymbolRefExpr::getSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a4e87f4e2c6164013059b777bc2b6cf2a">llvm::MCSymbol::isCommon</a> and <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aac3107671801e6bb16ef896f382759cd">llvm::MCContext::reportError</a>.</p>

</div>
</div>

### getBundleAlignSize() {#a1228ea3bb214c9c0e513c582ccfd09bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCAssembler::getBundleAlignSize ()</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>


<p>Referenced by <a href="#a7fd3ef6690dbde3a5840707d439b5a22">layoutBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcelfstreamer-cpp/#a9f2c99c2d4187ac79c172cbf26e6553c">setSectionAlignmentForBundling</a> and <a href="#aed080c421ef7325c6e04a5bf027d9044">writeFragmentPadding</a>.</p>

</div>
</div>

### getContext() {#a0675ed1bdbf987d94ef2360cb18c6eae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext &amp; llvm::MCAssembler::getContext ()</td>
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



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>


<p>Referenced by <a href="#abc4d6b7d638e45034130bc3ab18e5be6">computeFragmentSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a29a3c5dc6082aabd411724f33011f795">llvm::MCELFStreamer::emitCommonSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a1760c43fadfe8ae62e75e7debd68fad5">llvm::MipsTargetELFStreamer::emitDirectiveCpLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a219c7bb0dc91e12b2b43dfc1595ce234">llvm::MipsTargetELFStreamer::emitDirectiveCpsetup</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a4d9e8e23e14d63569e6f0121aabd33ce">llvm::MipsTargetELFStreamer::emitDirectiveEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#aa9fe69c4c82bcd2d3a4b6ea55dd4a806">llvm::MipsTargetELFStreamer::emitFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a21d50101946fb3648d4d662a0e1d0406">llvm::MCELFStreamer::emitIdent</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#afeed6d8af2306405a117845c04177102">llvm::MipsTargetELFStreamer::emitMipsAbiFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a94031e736c9e04044ac7181147a54bf6">llvm::MipsTargetELFStreamer::finish</a>, <a href="#ac06af0994b284d9e18c3b90c7c500a03">getBaseSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmcelfstreamer/#a64f1accd42a5eb6c0d80c800e63123b9">llvm::HexagonMCELFStreamer::HexagonMCEmitCommonSymbol</a>, <a href="#a4172c40c16e915c478ab94311e76e1a8">layout</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a17d3b4679a104b0852f1679b817d2070">llvm::MipsTargetELFStreamer::MipsTargetELFStreamer</a> and <a href="#a2a301492f7142fbc3744cc1c5a86f5ec">writeSectionData</a>.</p>

</div>
</div>

### getDWARFLinetableParams() {#aecd1dfc9a1400558c39c47db568964ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCDwarfLineTableParams llvm::MCAssembler::getDWARFLinetableParams ()</td>
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



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>

</div>
</div>

### getEmitter() {#a923971fae5bb26b2613d5b17ce09ac8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCCodeEmitter &amp; llvm::MCAssembler::getEmitter ()</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#acf7b75691e086935319e3142cb2eb579">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::AddEncodingComment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#ad00d45f3edbea563746d2aaa61931efc">llvm::MCWinCOFFStreamer::emitInstToData</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a970c047f65898d76cc9a251f32a5b70c">llvm::MCObjectStreamer::emitInstToFragment</a>.</p>

</div>
</div>

### getEmitterPtr() {#a751b495bbd855f8fa28e98a3619c898a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCCodeEmitter * llvm::MCAssembler::getEmitterPtr ()</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcelfstreamer/#abd418120b6155f0727d4bbf2dfeafe97">llvm::PPCELFStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcxcoffstreamer/#a8c2e9fc7b5dc34b2dc99e6b7216d7ec2">llvm::PPCXCOFFStreamer::emitInstruction</a>, <a href="#ad86e6a338edf76035209bf618067cf1d">reset</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a931125c9821366d0a4f14a4f8e423f95">llvm::AMDGPUAsmPrinter::runOnMachineFunction</a>.</p>

</div>
</div>

### getFragmentOffset() {#a7a4ff084961e27ad1fc9ff6f59d3f8ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MCAssembler::getFragmentOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 441 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>


<p>References <a href="#a082b39e969e2a698446f8f8b27ddb411">ensureValid</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#abc4d6b7d638e45034130bc3ab18e5be6">computeFragmentSize</a> and <a href="#a087b12083e027a47db241b0b3fbdce28">getSectionAddressSize</a>.</p>

</div>
</div>

### getRelaxAll() {#a815cbd2043a1094e14315a02e879a7fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCAssembler::getRelaxAll ()</td>
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



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>

</div>
</div>

### getSectionAddressSize() {#a087b12083e027a47db241b0b3fbdce28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MCAssembler::getSectionAddressSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> &amp; Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 543 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#abc4d6b7d638e45034130bc3ab18e5be6">computeFragmentSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#ac28ea8ba1e28d8b3a3ca7234e1bc1083">llvm::MCSection::curFragList</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a7a4ff084961e27ad1fc9ff6f59d3f8ee">getFragmentOffset</a> and <a href="/web-llvm/docs/api/structs/llvm/mcsection/fraglist/#adc70069d4b0d003cd6992fd07482d7e2">llvm::MCSection::FragList::Tail</a>.</p>


<p>Referenced by <a href="#ad1f09d354ee1d85dc432472549170b87">getSectionFileSize</a> and <a href="#a2a301492f7142fbc3744cc1c5a86f5ec">writeSectionData</a>.</p>

</div>
</div>

### getSectionFileSize() {#ad1f09d354ee1d85dc432472549170b87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MCAssembler::getSectionFileSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> &amp; Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 550 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>


<p>References <a href="#a087b12083e027a47db241b0b3fbdce28">getSectionAddressSize</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a915b90d97a0e500c99adefff0c22fec3">llvm::MCSection::isVirtualSection</a>.</p>


<p>Referenced by <a href="#a2a301492f7142fbc3744cc1c5a86f5ec">writeSectionData</a>.</p>

</div>
</div>

### getSymbolOffset() {#a0798a5faed48d2937c8974af40cebc8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAssembler::getSymbolOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; S, uint64_t &amp; Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 496 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp/#a447f1f2cd3572d7c1d3317369ed4ea7a">getSymbolOffsetImpl</a>.</p>


<p>Referenced by <a href="#abc4d6b7d638e45034130bc3ab18e5be6">computeFragmentSize</a>.</p>

</div>
</div>

### getSymbolOffset() {#a2c59aaf4ea314841ff5d61598fdfa477}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MCAssembler::getSymbolOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp/#a447f1f2cd3572d7c1d3317369ed4ea7a">getSymbolOffsetImpl</a>.</p>

</div>
</div>

### getSymbols() {#a80f8733f1d25b99133339ecb6223ab9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt; const MCSymbol * &gt; &amp; llvm::MCAssembler::getSymbols ()</td>
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



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>

</div>
</div>

### getWriter() {#a56c45e3acce6f7b060bed7e40398d207}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCObjectWriter &amp; llvm::MCAssembler::getWriter ()</td>
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



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>


<p>Reference <a href="#ad6e8cef6c5051dbdff8ebb7d53312d95">MCObjectWriter</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#aed0ef4e9a209115da9d035efef984bea">llvm::MCObjectStreamer::emitAddrsig</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a8e61900036f1378665d14f185309392a">llvm::MCObjectStreamer::emitAddrsigSym</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#ab6508358ece1c10feb9de803b4d27535">llvm::MCObjectStreamer::emitFileDirective</a>, <a href="#a0b9abcba24c548dbd22f928b184048fe">Finish</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a88517f360c788177b14d3d3d85182145">llvm::MCELFStreamer::getWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a9a8c43fa0cdd016bbe4c5cb73df03bad">llvm::MCWinCOFFStreamer::getWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/mcxcoffstreamer/#a414bcbdab3e76ffd4609ebf292f71bbc">llvm::MCXCOFFStreamer::getWriter</a> and <a href="#a4172c40c16e915c478ab94311e76e1a8">layout</a>.</p>

</div>
</div>

### hasLayout() {#aea907130afe6d413ca5898a9350a1175}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCAssembler::hasLayout ()</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>

</div>
</div>

### isBundlingEnabled() {#a1596e2e10c33712e8e3c1bd733bcda1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCAssembler::isBundlingEnabled ()</td>
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



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectstreamer-cpp/#af0f3550e50b0c66814dea0b4c9338308">canReuseDataFragment</a>, <a href="#a082b39e969e2a698446f8f8b27ddb411">ensureValid</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcelfstreamer-cpp/#a9f2c99c2d4187ac79c172cbf26e6553c">setSectionAlignmentForBundling</a> and <a href="#aed080c421ef7325c6e04a5bf027d9044">writeFragmentPadding</a>.</p>

</div>
</div>

### isThumbFunc() {#aaf5208586509a15c29239a946b2a1236}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAssembler::isThumbFunc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Func)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether a given symbol has been flagged with .thumb_func.</p>

<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#aa770f9e822312cc252ee01659e0bc7d4">llvm::MCExpr::evaluateAsRelocatable</a>, <a href="#aaf5208586509a15c29239a946b2a1236">isThumbFunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>.</p>


<p>Referenced by <a href="#aaf5208586509a15c29239a946b2a1236">isThumbFunc</a>.</p>

</div>
</div>

### layout() {#a4172c40c16e915c478ab94311e76e1a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAssembler::layout ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 893 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#ae38b6e0fdf26adde1fa4ac04e12931f7">llvm::MCAsmBackend::applyFixup</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a3fcdc9f30e5e8b9ea4da99868a8ae4a9">DEBUG_WITH_TYPE</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a9e8fa29f7cb6a03aa586afae7591f6cc">DF</a>, <a href="#a3a68266def3072d13b2cafb555b9e28c">dump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter/#a5fd56e75c2099d48aaf2909705765ac9">llvm::MCObjectWriter::executePostLayoutBinding</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a9e36accae823c19517d056f083199f3f">llvm::MCAsmBackend::finishLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68a1f3544ccfba8bd153218f9aff934ae23">llvm::MCFragment::FT_Align</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68a99243fc57a7beebaba062a013912846f">llvm::MCFragment::FT_CVDefRange</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68a31f0e4803273f2184e596c87e1e05f80">llvm::MCFragment::FT_Data</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68a01473d8036e353978ae750c8dace1a10">llvm::MCFragment::FT_Dwarf</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68a2f12197bbe6c6a91731b3828d033a212">llvm::MCFragment::FT_DwarfFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68acdb2608fe021d8fb06cf91d424f5bc53">llvm::MCFragment::FT_LEB</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68adcbefeedb7422d13473a4df6ff1cf964">llvm::MCFragment::FT_PseudoProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68abe5194c45ead6aefe6b0882dcb6f2104">llvm::MCFragment::FT_Relaxable</a>, <a href="#ab01b807c062ac4610366c6772ad5fd16">getBackend</a>, <a href="#ac2b513ce2e0d6eddaf628d3f7d7ee57b">getBackendPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcencodedfragmentwithfixups/#adeb8e72f8eb5703650627d39457436dd">llvm::MCEncodedFragmentWithFixups&lt; ContentsSize, FixupsSize &gt;::getContents</a>, <a href="#a0675ed1bdbf987d94ef2360cb18c6eae">getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcencodedfragmentwithfixups/#a8a0daac469ed602d68174c8efae89b22">llvm::MCEncodedFragmentWithFixups&lt; ContentsSize, FixupsSize &gt;::getFixups</a>, <a href="/web-llvm/docs/api/classes/llvm/mcencodedfragment/#a2c97dba695c5b5fa2bcc39c47c3b0762">llvm::MCEncodedFragment::getSubtargetInfo</a>, <a href="#a56c45e3acce6f7b060bed7e40398d207">getWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/mcalignfragment/#a7c89c26696bb6f507d07a41013687dbc">llvm::MCAlignFragment::hasEmitNops</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#acd02e61b262530ebe5c9a27ac0a0a693">llvm::MCFragment::hasInstructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8a4ee29ca12c7d126654bd0e5275de6135">llvm::List</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#ad2bbb8680cf10b86f2d70a4f02f0334e">llvm::MCSection::setHasLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a87c843b7d5be00f8abfc1311db9522df">llvm::MCSection::setOrdinal</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a606075cd52290485c49341abf348f715">llvm::MCAsmBackend::shouldInsertFixupForCodeAlign</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cad6e9c0ff694f0fca0222e79e772b647e">llvm::CallingConv::Tail</a>.</p>


<p>Referenced by <a href="#a0b9abcba24c548dbd22f928b184048fe">Finish</a>.</p>

</div>
</div>

### layoutBundle() {#a7fd3ef6690dbde3a5840707d439b5a22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAssembler::layoutBundle (<a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> * Prev, <a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp/#a186e69494dfd4a377b1d48f7c85d78b4">computeBundlePadding</a>, <a href="#abc4d6b7d638e45034130bc3ab18e5be6">computeFragmentSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a9e8fa29f7cb6a03aa586afae7591f6cc">DF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a1228ea3bb214c9c0e513c582ccfd09bf">getBundleAlignSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/classes/llvm/mcencodedfragment/#a74ca9081add78d66b5c6ebfe0f3d2b28">llvm::MCEncodedFragment::setBundlePadding</a>.</p>


<p>Referenced by <a href="#a082b39e969e2a698446f8f8b27ddb411">ensureValid</a>.</p>

</div>
</div>

### registerSection() {#ab6760ad43200e0c9da408d84eeb89f64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAssembler::registerSection (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> &amp; Section)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### registerSymbol() {#ae26e9b713a9b85d7a56343c78794269c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAssembler::registerSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; Symbol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 557 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a6a47a643b51576c0fd4812a911e03fa5">llvm::MCWinCOFFStreamer::changeSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mipselfstreamer/#ab2beebc6dcbab3b3223a55482805605c">llvm::MipsELFStreamer::createPendingLabelRelocs</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a2cff84e102389b6f127a6051d9ff062a">llvm::MCObjectStreamer::emitAssignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a296ba2dbfb0e9605f94744804b1612b9">llvm::MCWinCOFFStreamer::emitCOFFSafeSEH</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#ac26c6bea8d31cc52a500469bc470d0b6">llvm::MCWinCOFFStreamer::emitCOFFSymbolIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#af3100c31fed868b5a87a824ca1e23948">llvm::MCWinCOFFStreamer::emitCOFFSymbolStorageClass</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#aae4faa909b207570b5b690123fe7fb22">llvm::MCWinCOFFStreamer::emitCOFFSymbolType</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a29a3c5dc6082aabd411724f33011f795">llvm::MCELFStreamer::emitCommonSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a46ca451d0ba24a1a138f28bd71a72271">llvm::MCWinCOFFStreamer::emitCommonSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcxcoffstreamer/#a3aac14b3e4ad12e94a2d1a3ec2263b93">llvm::MCXCOFFStreamer::emitCommonSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a1760c43fadfe8ae62e75e7debd68fad5">llvm::MipsTargetELFStreamer::emitDirectiveCpLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetelfstreamer/#aa8d0de86901050c07df09a18aa990b3c">llvm::RISCVTargetELFStreamer::emitDirectiveVariantCC</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a9924d739e3dc812b561931a1ad6eb5cf">llvm::MCObjectStreamer::emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a843ec2afb472e21a5fcdc5480c1dd80c">llvm::MipsTargetELFStreamer::emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#afa0924c573f9c03cafa5836672cc58cf">llvm::MCObjectStreamer::emitLabelAtPos</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a54046180adfd51d0e1d0a4ede51a6bd9">llvm::MCELFStreamer::emitLocalCommonSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#acfe4f94dca14855495d5743fc3e60998">llvm::MCELFStreamer::emitSymbolAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwasmstreamer/#ad671bf8c133f9337366ecdf2c0048d6f">llvm::MCWasmStreamer::emitSymbolAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#ac1410ebb1de1644c3fd7019450373441">llvm::MCWinCOFFStreamer::emitSymbolAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/mcxcoffstreamer/#afc1c68d65e64e951a0f7d2a67dc80719">llvm::MCXCOFFStreamer::emitSymbolAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#ac11138742df2a7103190a1955e6b7331">llvm::MCELFStreamer::emitWeakReference</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwasmstreamer/#ac85beb9165822c1f0510c92a3f340b35">llvm::MCWasmStreamer::emitWeakReference</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a24389fc33ea52e268a13e698afe9f718">llvm::MCWinCOFFStreamer::emitWeakReference</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmcelfstreamer/#a64f1accd42a5eb6c0d80c800e63123b9">llvm::HexagonMCELFStreamer::HexagonMCEmitCommonSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonmcelfstreamer/#a51052f1e0d005332637e592f961d951b">llvm::HexagonMCELFStreamer::HexagonMCEmitLocalCommonSymbol</a>.</p>

</div>
</div>

### reset() {#ad86e6a338edf76035209bf618067cf1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAssembler::reset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reuse an assembler instance.</p>

<p>Declaration at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>


<p>References <a href="#ac2b513ce2e0d6eddaf628d3f7d7ee57b">getBackendPtr</a>, <a href="#a751b495bbd855f8fa28e98a3619c898a">getEmitterPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#ac0fe81b089903ff8c1d8593fee9a0156">llvm::MCAsmBackend::reset</a> and <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter/#a741d220b22e3707c67992b3e19fde103">llvm::MCCodeEmitter::reset</a>.</p>

</div>
</div>

### setBundleAlignSize() {#a1af560393c21ce83e6ecea7b8475c428}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCAssembler::setBundleAlignSize (unsigned Size)</td>
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



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### setIsThumbFunc() {#a202fda2877307a61a19b55fcd18765c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCAssembler::setIsThumbFunc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Func)</td>
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

<p>Flag a function symbol as the target of a .thumb_func directive.</p>

<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armelfstreamer-cpp-/armelfstreamer/#a51936e8a709df3a1eec3e749b2e17e59">anonymous{ARMELFStreamer.cpp}::ARMELFStreamer::emitSymbolAttribute</a>.</p>

</div>
</div>

### setRelaxAll() {#aef73095e90bd2b9606c693612c7571cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCAssembler::setRelaxAll (bool Value)</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>

</div>
</div>

### symbols() {#ad08c6564acd34ce855c1bb576c9edd6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; pointee_iterator&lt; typename SmallVector&lt; const MCSymbol *, 0 &gt;::const_iterator &gt; &gt; llvm::MCAssembler::symbols ()</td>
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



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a651dc9ad820d3c7cdd28f671e0d6d2e2">llvm::make_pointee_range</a>.</p>


<p>Referenced by <a href="#a3a68266def3072d13b2cafb555b9e28c">dump</a>.</p>

</div>
</div>

### writeFragmentPadding() {#aed080c421ef7325c6e04a5bf027d9044}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAssembler::writeFragmentPadding (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcencodedfragment">MCEncodedFragment</a> &amp; F, uint64_t FSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write the necessary bundle padding to <span class="doxyComputerOutput">OS</span>.</p>


<p>Expects a fragment <span class="doxyComputerOutput">F</span> containing instructions and its size <span class="doxyComputerOutput">FSize</span>.</p>


<p>Declaration at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 566 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcencodedfragment/#ab067e7ecede21fc252afdcc1eb282bfa">llvm::MCEncodedFragment::alignToBundleEnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab01b807c062ac4610366c6772ad5fd16">getBackend</a>, <a href="#ac2b513ce2e0d6eddaf628d3f7d7ee57b">getBackendPtr</a>, <a href="#a1228ea3bb214c9c0e513c582ccfd09bf">getBundleAlignSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcencodedfragment/#a890529a26c57ca69093313b4ca758eb7">llvm::MCEncodedFragment::getBundlePadding</a>, <a href="/web-llvm/docs/api/classes/llvm/mcencodedfragment/#a2c97dba695c5b5fa2bcc39c47c3b0762">llvm::MCEncodedFragment::getSubtargetInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#acd02e61b262530ebe5c9a27ac0a0a693">llvm::MCFragment::hasInstructions</a>, <a href="#a1596e2e10c33712e8e3c1bd733bcda1e">isBundlingEnabled</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### writeSectionData() {#a2a301492f7142fbc3744cc1c5a86f5ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAssembler::writeSectionData (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Section)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the section contents to <span class="doxyComputerOutput">OS</span>.</p>

<p>Declaration at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 815 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a9e8fa29f7cb6a03aa586afae7591f6cc">DF</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68a1f3544ccfba8bd153218f9aff934ae23">llvm::MCFragment::FT_Align</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68a31f0e4803273f2184e596c87e1e05f80">llvm::MCFragment::FT_Data</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68a1d46f74bcd87621a62557b9b6fc67c4b">llvm::MCFragment::FT_Fill</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68ac39471f5e9b12943cc8249cddbacd100">llvm::MCFragment::FT_Org</a>, <a href="#ac2b513ce2e0d6eddaf628d3f7d7ee57b">getBackendPtr</a>, <a href="#a0675ed1bdbf987d94ef2360cb18c6eae">getContext</a>, <a href="#a087b12083e027a47db241b0b3fbdce28">getSectionAddressSize</a>, <a href="#ad1f09d354ee1d85dc432472549170b87">getSectionFileSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a915b90d97a0e500c99adefff0c22fec3">llvm::MCSection::isVirtualSection</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aac3107671801e6bb16ef896f382759cd">llvm::MCContext::reportError</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f90ad570f71349466844ee9f2d06cd1">llvm::raw_ostream::tell</a> and <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp/#a6ae6757140194100cc316df00b97773f">writeFragment</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### evaluateFixup() {#a34670d9dbd338658ac3fb3b313ba9e31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAssembler::evaluateFixup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> * DF, <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI, uint64_t &amp; Value, bool &amp; WasForced)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Evaluate a fixup to a relocatable expression and the value which should be placed into the fixup.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Fixup</td>
<td class="doxyParamItemDescription"><p>The fixup to evaluate.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DF</td>
<td class="doxyParamItemDescription"><p>The fragment the fixup is inside.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/target"&gt;Target&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>[out] On return, the relocatable expression the fixup evaluates to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/value"&gt;Value&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>[out] On return, the value of the fixup as currently laid out.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">WasForced</td>
<td class="doxyParamItemDescription"><p>[out] On return, the value in the fixup is set to the correct value if WasForced is true, even if evaluateFixup returns false.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Whether the fixup value was fully resolved. This is true if the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> result is fixed, otherwise the value may change due to relocation.</p></dd>
</dl>


<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>

</div>
</div>

### fixupNeedsRelaxation() {#ae7f1cf34bd94f1fb4c1f59f6d24698ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAssembler::fixupNeedsRelaxation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcrelaxablefragment">MCRelaxableFragment</a> * DF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether a fixup can be satisfied, or whether it needs to be relaxed (increased in size, in order to hold its value correctly).</p>

<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 1038 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>

</div>
</div>

### fragmentNeedsRelaxation() {#a0203c34dad1ebe514a25fd9fbb64b681}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAssembler::fragmentNeedsRelaxation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcrelaxablefragment">MCRelaxableFragment</a> * IF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the given fragment needs relaxation.</p>

<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 1054 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>

</div>
</div>

### handleFixup() {#a609f91b55661d4e220038cf153231f7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::tuple&lt; MCValue, uint64_t, bool &gt; MCAssembler::handleFixup (<a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 876 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>

</div>
</div>

### layoutOnce() {#a1673ed73dc8dc4815a874d398bc402db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAssembler::layoutOnce ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform one layout iteration and return true if any offsets were adjusted.</p>

<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 1293 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>

</div>
</div>

### relaxBoundaryAlign() {#a712f5df203886badc60ab0240c35f2ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAssembler::relaxBoundaryAlign (<a href="/web-llvm/docs/api/classes/llvm/mcboundaryalignfragment">MCBoundaryAlignFragment</a> &amp; BF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 1170 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>

</div>
</div>

### relaxCVDefRange() {#a2ab8fb72bab598384afc65e753d66aec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAssembler::relaxCVDefRange (<a href="/web-llvm/docs/api/classes/llvm/mccvdefrangefragment">MCCVDefRangeFragment</a> &amp; DF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 1246 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>

</div>
</div>

### relaxCVInlineLineTable() {#a11e5a9982d680ae5fe110ef05f15dd55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAssembler::relaxCVInlineLineTable (<a href="/web-llvm/docs/api/classes/llvm/mccvinlinelinetablefragment">MCCVInlineLineTableFragment</a> &amp; DF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 1240 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>

</div>
</div>

### relaxDwarfCallFrameFragment() {#a6c7d0fe369c75cfd577af1eb57d66017}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAssembler::relaxDwarfCallFrameFragment (<a href="/web-llvm/docs/api/classes/llvm/mcdwarfcallframefragment">MCDwarfCallFrameFragment</a> &amp; DF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 1216 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>

</div>
</div>

### relaxDwarfLineAddr() {#a5090576b71802dbdbababc70c24a9978}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAssembler::relaxDwarfLineAddr (<a href="/web-llvm/docs/api/classes/llvm/mcdwarflineaddrfragment">MCDwarfLineAddrFragment</a> &amp; DF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 1194 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>

</div>
</div>

### relaxFragment() {#a2b3a44c22d40704a26dcad45a076c5b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAssembler::relaxFragment (<a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform relaxation on a single fragment - returns true if the fragment changes as a result of relaxation.</p>

<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 1268 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>

</div>
</div>

### relaxInstruction() {#ac8e12915f4bb57962d001e10842d9554}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAssembler::relaxInstruction (<a href="/web-llvm/docs/api/classes/llvm/mcrelaxablefragment">MCRelaxableFragment</a> &amp; IF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 1069 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>

</div>
</div>

### relaxLEB() {#a7b9f0e5bf413ecbd68984a392e89b191}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAssembler::relaxLEB (<a href="/web-llvm/docs/api/classes/llvm/mclebfragment">MCLEBFragment</a> &amp; IF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 1094 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>

</div>
</div>

### relaxPseudoProbeAddr() {#ab85dff56ce066f571f9ce90aec960b9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAssembler::relaxPseudoProbeAddr (<a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobeaddrfragment">MCPseudoProbeAddrFragment</a> &amp; DF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>, definition at line 1252 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Backend {#aa3f310eeb906d60a70edf997c067f73f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MCAsmBackend&gt; llvm::MCAssembler::Backend</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>

</div>
</div>

### BundleAlignSize {#accbd40b3bbfdf0a5f8fdaf7d878f001d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCAssembler::BundleAlignSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The bundle alignment size currently set in the assembler.</p>


<p>By default it's 0, which means bundling is disabled.</p>


<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>

</div>
</div>

### Context {#a5da6a2ba9b4aac52b51a629d4e609e55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext&amp; llvm::MCAssembler::Context</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>

</div>
</div>

### Emitter {#a8b2924018a8b299616f1d713ce584215}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MCCodeEmitter&gt; llvm::MCAssembler::Emitter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>

</div>
</div>

### HasLayout {#ae00418d63f8908d0e81d99b742625411}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCAssembler::HasLayout = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>

</div>
</div>

### LTParams {#aa8d0eebb1bc1558ee49389ef085e000c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCDwarfLineTableParams llvm::MCAssembler::LTParams</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>

</div>
</div>

### RelaxAll {#a3708034c3c7d14df9a3fc9dc45a381ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCAssembler::RelaxAll = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>

</div>
</div>

### Sections {#ab8838836c973494f33dce28de127a6eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionListType llvm::MCAssembler::Sections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>

</div>
</div>

### Symbols {#af00362186405287071fed8076a33d7fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;const MCSymbol *, 0&gt; llvm::MCAssembler::Symbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>

</div>
</div>

### ThumbFuncs {#a3380917e8a8be39133641e7147867395}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;const MCSymbol *, 32&gt; llvm::MCAssembler::ThumbFuncs</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of function symbols for which a .thumb_func directive has been seen.</p>

<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>

</div>
</div>

### Writer {#afea995d073e0180f34b9b664d6bbbda8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MCObjectWriter&gt; llvm::MCAssembler::Writer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">MCAssembler.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp">MCAssembler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
