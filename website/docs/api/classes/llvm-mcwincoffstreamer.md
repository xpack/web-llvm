---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcwincoffstreamer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MCWinCOFFStreamer` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MCWinCOFFStreamer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">llvm/MC/MCWinCOFFStreamer.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer">MCObjectStreamer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Streaming object file generation interface. <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-aarch64wincoffstreamer-cpp-/aarch64wincoffstreamer">AArch64WinCOFFStreamer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-armwincoffstreamer-cpp-/armwincoffstreamer">ARMWinCOFFStreamer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-mipswincoffstreamer-cpp-/mipswincoffstreamer">MipsWinCOFFStreamer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-x86wincoffstreamer-cpp-/x86wincoffstreamer">X86WinCOFFStreamer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c671ab9beefef98e0f4702b91cd96b5">MCWinCOFFStreamer</a> (MCContext &amp;Context, std::unique_ptr&lt; MCAsmBackend &gt; MAB, std::unique_ptr&lt; MCCodeEmitter &gt; CE, std::unique_ptr&lt; MCObjectWriter &gt; OW)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88092bc1676caab9c0c99c580c61922d">reset</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>state management <a href="#a88092bc1676caab9c0c99c580c61922d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/wincoffobjectwriter">WinCOFFObjectWriter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a8c43fa0cdd016bbe4c5cb73df03bad">getWriter</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad00d45f3edbea563746d2aaa61931efc">emitInstToData</a> (const MCInst &amp;Inst, const MCSubtargetInfo &amp;STI) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12d7f7b28045ca28e88138c63c174184">finalizeCGProfileEntry</a> (const MCSymbolRefExpr *&amp;S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afabfb73d23ca0e8482862d4b320ddff7">Error</a> (const Twine &amp;Msg) const</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abde6f25a7f003e4862df94ccdbf91ebd">CurSymbol</a></td>
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

## MCStreamer interface Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28e4c026855f296e926e3feb231b5811">initSections</a> (bool NoExecStack, const MCSubtargetInfo &amp;STI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the default sections and set the initial one. <a href="#a28e4c026855f296e926e3feb231b5811">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a47a643b51576c0fd4812a911e03fa5">changeSection</a> (MCSection *Section, uint32_t Subsection=0) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is called by popSection and switchSection, if the current section changes. <a href="#a6a47a643b51576c0fd4812a911e03fa5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2084737c77dbba4d2b3b67599e914d2c">emitLabel</a> (MCSymbol *Symbol, SMLoc Loc=SMLoc()) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a label for <span class="doxyComputerOutput">Symbol</span> into the current section. <a href="#a2084737c77dbba4d2b3b67599e914d2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fc4ee7b7b03750cf55c97db751764d2">emitAssemblerFlag</a> (MCAssemblerFlag Flag) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Note in the output the specified <span class="doxyComputerOutput">Flag</span>. <a href="#a0fc4ee7b7b03750cf55c97db751764d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1383dab7271c46ee4016329b126bc7f5">emitThumbFunc</a> (MCSymbol *Func) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Note in the output that the specified <span class="doxyComputerOutput">Func</span> is a Thumb mode function (<a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> target only). <a href="#a1383dab7271c46ee4016329b126bc7f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1410ebb1de1644c3fd7019450373441">emitSymbolAttribute</a> (MCSymbol *Symbol, MCSymbolAttr Attribute) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the given <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></span> to <span class="doxyComputerOutput">Symbol</span>. <a href="#ac1410ebb1de1644c3fd7019450373441">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9c9d76e19bb3065a076d1c26e060a11">emitSymbolDesc</a> (MCSymbol *Symbol, unsigned DescValue) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the <span class="doxyComputerOutput">DescValue</span> for the <span class="doxyComputerOutput">Symbol</span>. <a href="#ab9c9d76e19bb3065a076d1c26e060a11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb7487e8cd551f2972040beb219b1dfc">beginCOFFSymbolDef</a> (MCSymbol const *Symbol) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Start emitting <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> symbol definition. <a href="#acb7487e8cd551f2972040beb219b1dfc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3100c31fed868b5a87a824ca1e23948">emitCOFFSymbolStorageClass</a> (int StorageClass) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the storage class of the symbol. <a href="#af3100c31fed868b5a87a824ca1e23948">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae4faa909b207570b5b690123fe7fb22">emitCOFFSymbolType</a> (int Type) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the type of the symbol. <a href="#aae4faa909b207570b5b690123fe7fb22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48c8a92360b68670c3f93cf6e3b6aa41">endCOFFSymbolDef</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Marks the end of the symbol definition. <a href="#a48c8a92360b68670c3f93cf6e3b6aa41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a296ba2dbfb0e9605f94744804b1612b9">emitCOFFSafeSEH</a> (MCSymbol const *Symbol) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac26c6bea8d31cc52a500469bc470d0b6">emitCOFFSymbolIndex</a> (MCSymbol const *Symbol) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits the symbol table index of a Symbol into the current section. <a href="#ac26c6bea8d31cc52a500469bc470d0b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cce678ce28a97e39af6a60a52daac7f">emitCOFFSectionIndex</a> (MCSymbol const *Symbol) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits a <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> section index. <a href="#a0cce678ce28a97e39af6a60a52daac7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dbbe16f1a57144b250b2b3ba1243e93">emitCOFFSecRel32</a> (MCSymbol const *Symbol, uint64_t Offset) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits a <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> section relative relocation. <a href="#a6dbbe16f1a57144b250b2b3ba1243e93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b7e117c34782423f4cab2396b42b059">emitCOFFImgRel32</a> (MCSymbol const *Symbol, int64_t Offset) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits a <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> image relative relocation. <a href="#a1b7e117c34782423f4cab2396b42b059">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab111e0970f34dbb0c62ace14e515819c">emitCOFFSecNumber</a> (MCSymbol const *Symbol) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits the physical number of the section containing the given symbol as assigned during object writing (i.e., this is not a runtime relocation). <a href="#ab111e0970f34dbb0c62ace14e515819c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4231cebc046e4dba7b742b6d31bd1d01">emitCOFFSecOffset</a> (MCSymbol const *Symbol) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits the offset of the symbol from the beginning of the section during object writing (i.e., this is not a runtime relocation). <a href="#a4231cebc046e4dba7b742b6d31bd1d01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46ca451d0ba24a1a138f28bd71a72271">emitCommonSymbol</a> (MCSymbol *Symbol, uint64_t Size, Align ByteAlignment) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a common symbol. <a href="#a46ca451d0ba24a1a138f28bd71a72271">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98ffe083ab6ade934683a26a65204179">emitLocalCommonSymbol</a> (MCSymbol *Symbol, uint64_t Size, Align ByteAlignment) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a local common (.lcomm) symbol. <a href="#a98ffe083ab6ade934683a26a65204179">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24389fc33ea52e268a13e698afe9f718">emitWeakReference</a> (MCSymbol *Alias, const MCSymbol *Symbol) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an weak reference from <span class="doxyComputerOutput">Alias</span> to <span class="doxyComputerOutput">Symbol</span>. <a href="#a24389fc33ea52e268a13e698afe9f718">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2107d440e06a521c8e44631fd31df3fa">emitZerofill</a> (MCSection *Section, MCSymbol *Symbol, uint64_t Size, Align ByteAlignment, SMLoc Loc=SMLoc()) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the zerofill section and an optional symbol. <a href="#a2107d440e06a521c8e44631fd31df3fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6760ebbbb1291b0f9f208dbb046e3397">emitTBSSSymbol</a> (MCSection *Section, MCSymbol *Symbol, uint64_t Size, Align ByteAlignment) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a thread local bss (.tbss) symbol. <a href="#a6760ebbbb1291b0f9f208dbb046e3397">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8250551059ae35939aa31e26bdab5491">emitIdent</a> (StringRef IdentString) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the "identifiers" directive. <a href="#a8250551059ae35939aa31e26bdab5491">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6544307ad2e9c7b8651b9c4f03778b0">emitWinEHHandlerData</a> (SMLoc Loc) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a912942cd73fd3f0a2dfb952fed5c49dc">emitCGProfileEntry</a> (const MCSymbolRefExpr *From, const MCSymbolRefExpr *To, uint64_t Count) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f964c60245b61612ddd6509cba7eb74">finishImpl</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Streamer specific finalization. <a href="#a7f964c60245b61612ddd6509cba7eb74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MCWinCOFFStreamer() {#a5c671ab9beefef98e0f4702b91cd96b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCWinCOFFStreamer::MCWinCOFFStreamer (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Context, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> &gt; MAB, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> &gt; CE, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter">MCObjectWriter</a> &gt; OW)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="#abde6f25a7f003e4862df94ccdbf91ebd">CurSymbol</a>, <a href="#a9a8c43fa0cdd016bbe4c5cb73df03bad">getWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a9ad1da683a018add519fd96cd22cc785">llvm::MCObjectStreamer::MCObjectStreamer</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64wincoffstreamer-cpp-/aarch64wincoffstreamer/#af8b470702843e1ae0d60d8041f2e48c7">anonymous{AArch64WinCOFFStreamer.cpp}::AArch64WinCOFFStreamer::AArch64WinCOFFStreamer</a>, <a href="/web-llvm/docs/api/classes/anonymous-armwincoffstreamer-cpp-/armwincoffstreamer/#a352791d2776deae8e56068dfc2f1d6cc">anonymous{ARMWinCOFFStreamer.cpp}::ARMWinCOFFStreamer::ARMWinCOFFStreamer</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipswincoffstreamer-cpp-/mipswincoffstreamer/#a5665c141727ed80bb6da24aaf2bfc1d2">anonymous{MipsWinCOFFStreamer.cpp}::MipsWinCOFFStreamer::MipsWinCOFFStreamer</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86wincoffstreamer-cpp-/x86wincoffstreamer/#aab1633fd70ac138c0937636187a1fea8">anonymous{X86WinCOFFStreamer.cpp}::X86WinCOFFStreamer::X86WinCOFFStreamer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getWriter() {#a9a8c43fa0cdd016bbe4c5cb73df03bad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WinCOFFObjectWriter &amp; MCWinCOFFStreamer::getWriter ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a> and <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a56c45e3acce6f7b060bed7e40398d207">llvm::MCAssembler::getWriter</a>.</p>


<p>Referenced by <a href="#a912942cd73fd3f0a2dfb952fed5c49dc">emitCGProfileEntry</a>, <a href="#ab111e0970f34dbb0c62ace14e515819c">emitCOFFSecNumber</a> and <a href="#a5c671ab9beefef98e0f4702b91cd96b5">MCWinCOFFStreamer</a>.</p>

</div>
</div>

### reset() {#a88092bc1676caab9c0c99c580c61922d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCWinCOFFStreamer::reset ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>state management</p>

<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>.</p>


<p>References <a href="#abde6f25a7f003e4862df94ccdbf91ebd">CurSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a085ffc1a6ae032696e1a665600f04124">llvm::MCObjectStreamer::reset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### emitInstToData() {#ad00d45f3edbea563746d2aaa61931efc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCWinCOFFStreamer::emitInstToData (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a9e8fa29f7cb6a03aa586afae7591f6cc">DF</a>, <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter/#a65397c092d290f6c8d326e30439460fa">llvm::MCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a923971fae5bb26b2613d5b17ce09ac8e">llvm::MCAssembler::getEmitter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a603eb2d37a31ea2c14318bedeecb8e3c">llvm::getOffset</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3558114ca72d34962abb28004d864b19">llvm::MCObjectStreamer::getOrCreateDataFragment</a>.</p>

</div>
</div>

### finalizeCGProfileEntry() {#a12d7f7b28045ca28e88138c63c174184}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCWinCOFFStreamer::finalizeCGProfileEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr">MCSymbolRefExpr</a> *&amp; S)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a048f077746d95f142d02e56586862bf2">llvm::MCSymbolRefExpr::getSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a41a90289b3b4b0ce7aa1b450fd38607d">llvm::MCSymbol::setExternal</a>.</p>


<p>Referenced by <a href="#a7f964c60245b61612ddd6509cba7eb74">finishImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### Error() {#afabfb73d23ca0e8482862d4b320ddff7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCWinCOFFStreamer::Error (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 509 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### CurSymbol {#abde6f25a7f003e4862df94ccdbf91ebd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbol* llvm::MCWinCOFFStreamer::CurSymbol</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>.</p>


<p>Referenced by <a href="#acb7487e8cd551f2972040beb219b1dfc">beginCOFFSymbolDef</a>, <a href="#af3100c31fed868b5a87a824ca1e23948">emitCOFFSymbolStorageClass</a>, <a href="#aae4faa909b207570b5b690123fe7fb22">emitCOFFSymbolType</a>, <a href="#a48c8a92360b68670c3f93cf6e3b6aa41">endCOFFSymbolDef</a>, <a href="#a5c671ab9beefef98e0f4702b91cd96b5">MCWinCOFFStreamer</a> and <a href="#a88092bc1676caab9c0c99c580c61922d">reset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## MCStreamer interface

### beginCOFFSymbolDef {#acb7487e8cd551f2972040beb219b1dfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCWinCOFFStreamer::beginCOFFSymbolDef (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * Symbol)</td>
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

<p>Start emitting <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> symbol definition.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Symbol</td>
<td class="doxyParamItemDescription"><p>- The symbol to have its External &amp; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> fields set.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#abde6f25a7f003e4862df94ccdbf91ebd">CurSymbol</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>.</p>

</div>
</div>

### changeSection {#a6a47a643b51576c0fd4812a911e03fa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCWinCOFFStreamer::changeSection (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Section, uint32_t)</td>
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

<p>This is called by popSection and switchSection, if the current section changes.</p>

<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a6f19f34683888bee863e73af9a082535">llvm::MCObjectStreamer::changeSectionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a> and <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#ae26e9b713a9b85d7a56343c78794269c">llvm::MCAssembler::registerSymbol</a>.</p>

</div>
</div>

### emitAssemblerFlag {#a0fc4ee7b7b03750cf55c97db751764d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCWinCOFFStreamer::emitAssemblerFlag (<a href="/web-llvm/docs/api/namespaces/llvm/#aa09571f0b44fd6bd8fae33d6ead290c1">MCAssemblerFlag</a> Flag)</td>
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

<p>Note in the output the specified <span class="doxyComputerOutput">Flag</span>.</p>

<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#ab01b807c062ac4610366c6772ad5fd16">llvm::MCAssembler::getBackend</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a3745e4df8defc9a3eafb48786398f8e6">llvm::MCAsmBackend::handleAssemblerFlag</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa09571f0b44fd6bd8fae33d6ead290c1a97f114ed47db100e48185ee6d6ad531b">llvm::MCAF_Code16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa09571f0b44fd6bd8fae33d6ead290c1ad77d445deab9f2715c6d2b48aee116ea">llvm::MCAF_Code32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa09571f0b44fd6bd8fae33d6ead290c1a836c6b17b1d82a5d54d61120d3a99f8a">llvm::MCAF_Code64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa09571f0b44fd6bd8fae33d6ead290c1adeea37757529c5d5cfeb922221d0f6f0">llvm::MCAF_SubsectionsViaSymbols</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa09571f0b44fd6bd8fae33d6ead290c1a4673762188cd819fd32979a26c1c67b5">llvm::MCAF_SyntaxUnified</a>.</p>

</div>
</div>

### emitCGProfileEntry {#a912942cd73fd3f0a2dfb952fed5c49dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCWinCOFFStreamer::emitCGProfileEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr">MCSymbolRefExpr</a> * From, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr">MCSymbolRefExpr</a> * To, uint64_t Count)</td>
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



<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 475 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter/#ad7e57ceba8c8eb8b57d933dc787206c4">llvm::MCObjectWriter::getCGProfile</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a048f077746d95f142d02e56586862bf2">llvm::MCSymbolRefExpr::getSymbol</a>, <a href="#a9a8c43fa0cdd016bbe4c5cb73df03bad">getWriter</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#acb1c818c7e94eb25afce63fc2f91c0e2">llvm::MCSymbol::isTemporary</a>.</p>

</div>
</div>

### emitCOFFImgRel32 {#a1b7e117c34782423f4cab2396b42b059}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCWinCOFFStreamer::emitCOFFImgRel32 (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * Symbol, int64_t Offset)</td>
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

<p>Emits a <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> image relative relocation.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Symbol</td>
<td class="doxyParamItemDescription"><p>- Symbol the image relative relocation should point to.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfixup/#abdf37854fa6eb68017b96486df443a32">llvm::MCFixup::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a3cbe1086ebf00680e8dc374e07305cfb">llvm::MCBinaryExpr::createAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a9e8fa29f7cb6a03aa586afae7591f6cc">DF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3558114ca72d34962abb28004d864b19">llvm::MCObjectStreamer::getOrCreateDataFragment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a9331563ad1532eb718a64639d71c440b">llvm::MCObjectStreamer::visitUsedSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a61907d1fede3c9e9713b6b3a29d35b01">llvm::MCSymbolRefExpr::VK_COFF_IMGREL32</a>.</p>

</div>
</div>

### emitCOFFSafeSEH {#a296ba2dbfb0e9605f94744804b1612b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCWinCOFFStreamer::emitCOFFSafeSEH (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * Symbol)</td>
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



<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a0fa8088b7ca6c8fccd88370bc5be4afa">llvm::MCSection::ensureMinAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a01d6d82d18a5da901c50a546932c4264">llvm::MCContext::getObjectFileInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a4c945f4a60fb9dd0893b1632944dafc3">llvm::MCObjectFileInfo::getSXDataSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#afb00b34885d4708e35781d81eb6e6120aabbef750c1bc8143f79535ea20699385">llvm::COFF::IMAGE_SYM_DTYPE_FUNCTION</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a941f547c39a7daf0a48452cc945a835c">llvm::MCObjectStreamer::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolcoff/#a8f99a95ef446233d0940b18a46321a88">llvm::MCSymbolCOFF::isSafeSEH</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a216005880453270b48e5d5d7daeec6d4">llvm::MCStreamer::popSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ab095568f88bb32f8a744aaeab0d2c4d0">llvm::MCStreamer::pushSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#ae26e9b713a9b85d7a56343c78794269c">llvm::MCAssembler::registerSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#afb00b34885d4708e35781d81eb6e6120af01942289377f5c52c8771699eea5144">llvm::COFF::SCT_COMPLEX_TYPE_SHIFT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolcoff/#a582f0e948a6c830817d56afcc5c8f4bc">llvm::MCSymbolCOFF::setIsSafeSEH</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolcoff/#a78c4747e9872c40666e2e6932dabc8d0">llvm::MCSymbolCOFF::setType</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ac4f84451dc4abc997c960d484953b1d2">llvm::MCStreamer::switchSection</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a0eefa3e53db25b90828e42c64b138648">llvm::Triple::x86</a>.</p>

</div>
</div>

### emitCOFFSecNumber {#ab111e0970f34dbb0c62ace14e515819c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCWinCOFFStreamer::emitCOFFSecNumber (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * Symbol)</td>
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

<p>Emits the physical number of the section containing the given symbol as assigned during object writing (i.e., this is not a runtime relocation).</p>

<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcfixup/#abdf37854fa6eb68017b96486df443a32">llvm::MCFixup::create</a>, <a href="/web-llvm/docs/api/classes/mccoffsectionnumbertargetexpr/#abf533c9fdbd8df604013fb7617d46489">MCCOFFSectionNumberTargetExpr::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a9e8fa29f7cb6a03aa586afae7591f6cc">DF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3558114ca72d34962abb28004d864b19">llvm::MCObjectStreamer::getOrCreateDataFragment</a>, <a href="#a9a8c43fa0cdd016bbe4c5cb73df03bad">getWriter</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a9331563ad1532eb718a64639d71c440b">llvm::MCObjectStreamer::visitUsedSymbol</a>.</p>

</div>
</div>

### emitCOFFSecOffset {#a4231cebc046e4dba7b742b6d31bd1d01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCWinCOFFStreamer::emitCOFFSecOffset (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * Symbol)</td>
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

<p>Emits the offset of the symbol from the beginning of the section during object writing (i.e., this is not a runtime relocation).</p>

<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcfixup/#abdf37854fa6eb68017b96486df443a32">llvm::MCFixup::create</a>, <a href="/web-llvm/docs/api/classes/mccoffsectionoffsettargetexpr/#a2de736eddfcac71de929e418bc16c0ea">MCCOFFSectionOffsetTargetExpr::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a9e8fa29f7cb6a03aa586afae7591f6cc">DF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3558114ca72d34962abb28004d864b19">llvm::MCObjectStreamer::getOrCreateDataFragment</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a9331563ad1532eb718a64639d71c440b">llvm::MCObjectStreamer::visitUsedSymbol</a>.</p>

</div>
</div>

### emitCOFFSecRel32 {#a6dbbe16f1a57144b250b2b3ba1243e93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCWinCOFFStreamer::emitCOFFSecRel32 (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * Symbol, uint64_t Offset)</td>
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

<p>Emits a <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> section relative relocation.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Symbol</td>
<td class="doxyParamItemDescription"><p>- Symbol the section relative relocation should point to.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfixup/#abdf37854fa6eb68017b96486df443a32">llvm::MCFixup::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a3cbe1086ebf00680e8dc374e07305cfb">llvm::MCBinaryExpr::createAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a9e8fa29f7cb6a03aa586afae7591f6cc">DF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a8b2acba82b6d0830ab47d67eb8f1ccf0">llvm::FK_SecRel_4</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3558114ca72d34962abb28004d864b19">llvm::MCObjectStreamer::getOrCreateDataFragment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a9331563ad1532eb718a64639d71c440b">llvm::MCObjectStreamer::visitUsedSymbol</a>.</p>

</div>
</div>

### emitCOFFSectionIndex {#a0cce678ce28a97e39af6a60a52daac7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCWinCOFFStreamer::emitCOFFSectionIndex (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * Symbol)</td>
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

<p>Emits a <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> section index.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Symbol</td>
<td class="doxyParamItemDescription"><p>- Symbol the section number relocation should point to.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcfixup/#abdf37854fa6eb68017b96486df443a32">llvm::MCFixup::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a9e8fa29f7cb6a03aa586afae7591f6cc">DF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a128346d352fde2e704c07867f4d82eef">llvm::FK_SecRel_2</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3558114ca72d34962abb28004d864b19">llvm::MCObjectStreamer::getOrCreateDataFragment</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a9331563ad1532eb718a64639d71c440b">llvm::MCObjectStreamer::visitUsedSymbol</a>.</p>

</div>
</div>

### emitCOFFSymbolIndex {#ac26c6bea8d31cc52a500469bc470d0b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCWinCOFFStreamer::emitCOFFSymbolIndex (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * Symbol)</td>
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

<p>Emits the symbol table index of a Symbol into the current section.</p>

<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a0fa8088b7ca6c8fccd88370bc5be4afa">llvm::MCSection::ensureMinAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ae1b3cf074436ef5b527071540e13bd58">llvm::MCStreamer::getCurrentSectionOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a941f547c39a7daf0a48452cc945a835c">llvm::MCObjectStreamer::insert</a> and <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#ae26e9b713a9b85d7a56343c78794269c">llvm::MCAssembler::registerSymbol</a>.</p>

</div>
</div>

### emitCOFFSymbolStorageClass {#af3100c31fed868b5a87a824ca1e23948}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCWinCOFFStreamer::emitCOFFSymbolStorageClass (int StorageClass)</td>
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

<p>Emit the storage class of the symbol.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70"&gt;StorageClass&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- The storage class the symbol should have.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#abde6f25a7f003e4862df94ccdbf91ebd">CurSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#ae26e9b713a9b85d7a56343c78794269c">llvm::MCAssembler::registerSymbol</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a906c310d62ec1ae55afe3295a4fc2115a34cef2950699983ff5c18a7ae38144fc">llvm::COFF::SSC_Invalid</a>.</p>

</div>
</div>

### emitCOFFSymbolType {#aae4faa909b207570b5b690123fe7fb22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCWinCOFFStreamer::emitCOFFSymbolType (int Type)</td>
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

<p>Emit the type of the symbol.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/type"&gt;Type&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- A <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> type identifier (see COFF::SymbolType in X86COFF.h)</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#abde6f25a7f003e4862df94ccdbf91ebd">CurSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a> and <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#ae26e9b713a9b85d7a56343c78794269c">llvm::MCAssembler::registerSymbol</a>.</p>

</div>
</div>

### emitCommonSymbol {#a46ca451d0ba24a1a138f28bd71a72271}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCWinCOFFStreamer::emitCommonSymbol (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, uint64_t Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> ByteAlignment)</td>
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

<p>Emit a common symbol.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Symbol</td>
<td class="doxyParamItemDescription"><p>- The common symbol to emit.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>- The size of the common symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ByteAlignment</td>
<td class="doxyParamItemDescription"><p>- The alignment of the symbol.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a66d51c3585e4733b99bb8d3e3eb2bb81">llvm::MCObjectStreamer::emitBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a78c3233931fda64aa2d37bce0ccc0f19">llvm::MCObjectFileInfo::getDrectveSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a01d6d82d18a5da901c50a546932c4264">llvm::MCContext::getObjectFileInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#afff5b8282b36f6a0ed50aeafe462250d">llvm::MCContext::getTargetTriple</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a058782b98991f0719657d9008d3df41b">llvm::Log2_32_Ceil</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a216005880453270b48e5d5d7daeec6d4">llvm::MCStreamer::popSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ab095568f88bb32f8a744aaeab0d2c4d0">llvm::MCStreamer::pushSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#ae26e9b713a9b85d7a56343c78794269c">llvm::MCAssembler::registerSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ac4f84451dc4abc997c960d484953b1d2">llvm::MCStreamer::switchSection</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### emitIdent {#a8250551059ae35939aa31e26bdab5491}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCWinCOFFStreamer::emitIdent (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> IdentString)</td>
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

<p>Emit the "identifiers" directive.</p>


<p>This implements the '.ident "version foo"' assembler directive.</p>


<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 467 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### emitLabel {#a2084737c77dbba4d2b3b67599e914d2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCWinCOFFStreamer::emitLabel (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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

<p>Emit a label for <span class="doxyComputerOutput">Symbol</span> into the current section.</p>


<p>This corresponds to an assembler statement such as: foo:</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Symbol</td>
<td class="doxyParamItemDescription"><p>- The symbol to emit. A given symbol should only be emitted as a label once, and symbols emitted as a label should never be used in an assignment.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a9924d739e3dc812b561931a1ad6eb5cf">llvm::MCObjectStreamer::emitLabel</a>.</p>


<p>Referenced by <a href="#a98ffe083ab6ade934683a26a65204179">emitLocalCommonSymbol</a>.</p>

</div>
</div>

### emitLocalCommonSymbol {#a98ffe083ab6ade934683a26a65204179}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCWinCOFFStreamer::emitLocalCommonSymbol (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, uint64_t Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> ByteAlignment)</td>
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

<p>Emit a local common (.lcomm) symbol.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Symbol</td>
<td class="doxyParamItemDescription"><p>- The common symbol to emit.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>- The size of the common symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ByteAlignment</td>
<td class="doxyParamItemDescription"><p>- The alignment of the common symbol in bytes.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 431 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a2084737c77dbba4d2b3b67599e914d2c">emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a21d70037ecf679b5f8d13af07f8f136a">llvm::MCObjectStreamer::emitValueToAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ae77a5b8d3af591a461aeac723de33240">llvm::MCStreamer::emitZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a6de12269943e6388af512d8b96cbd9e8">llvm::MCObjectFileInfo::getBSSSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a01d6d82d18a5da901c50a546932c4264">llvm::MCContext::getObjectFileInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a216005880453270b48e5d5d7daeec6d4">llvm::MCStreamer::popSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ab095568f88bb32f8a744aaeab0d2c4d0">llvm::MCStreamer::pushSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ac4f84451dc4abc997c960d484953b1d2">llvm::MCStreamer::switchSection</a>.</p>

</div>
</div>

### emitSymbolAttribute {#ac1410ebb1de1644c3fd7019450373441}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCWinCOFFStreamer::emitSymbolAttribute (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243">MCSymbolAttr</a> Attribute)</td>
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

<p>Add the given <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></span> to <span class="doxyComputerOutput">Symbol</span>.</p>

<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ac437dcd9750980233a278c48d2515271a3fded6ad3daf3b03a74ee1f3e11e52db">llvm::COFF::IMAGE_WEAK_EXTERN_ANTI_DEPENDENCY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ac437dcd9750980233a278c48d2515271a24243cd03a81991e278a4817b463acdb">llvm::COFF::IMAGE_WEAK_EXTERN_SEARCH_ALIAS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a452eae0b6838f1340eb75102bdfabd47">llvm::MCSA_AltEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243aa1e94c23156e37812e4d6e078af1d728">llvm::MCSA_Global</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a83df6138e7dba38c0c80380486544ea0">llvm::MCSA_Weak</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243aa96e85228ec0460e2b923801660b33f9">llvm::MCSA_WeakAntiDep</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a42ec27e2fd185b27d0fbf1aaf0bfd214">llvm::MCSA_WeakReference</a> and <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#ae26e9b713a9b85d7a56343c78794269c">llvm::MCAssembler::registerSymbol</a>.</p>


<p>Referenced by <a href="#a24389fc33ea52e268a13e698afe9f718">emitWeakReference</a>.</p>

</div>
</div>

### emitSymbolDesc {#ab9c9d76e19bb3065a076d1c26e060a11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCWinCOFFStreamer::emitSymbolDesc (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, unsigned DescValue)</td>
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

<p>Set the <span class="doxyComputerOutput">DescValue</span> for the <span class="doxyComputerOutput">Symbol</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Symbol</td>
<td class="doxyParamItemDescription"><p>- The symbol to have its n_desc field set.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DescValue</td>
<td class="doxyParamItemDescription"><p>- The value to set into the n_desc field.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### emitTBSSSymbol {#a6760ebbbb1291b0f9f208dbb046e3397}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCWinCOFFStreamer::emitTBSSSymbol (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Section, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, uint64_t Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> ByteAlignment)</td>
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

<p>Emit a thread local bss (.tbss) symbol.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Section</td>
<td class="doxyParamItemDescription"><p>- The thread local common section.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Symbol</td>
<td class="doxyParamItemDescription"><p>- The thread local common symbol to emit.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>- The size of the symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ByteAlignment</td>
<td class="doxyParamItemDescription"><p>- The alignment of the thread local common symbol.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 461 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### emitThumbFunc {#a1383dab7271c46ee4016329b126bc7f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCWinCOFFStreamer::emitThumbFunc (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Func)</td>
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

<p>Note in the output that the specified <span class="doxyComputerOutput">Func</span> is a Thumb mode function (<a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> target only).</p>

<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### emitWeakReference {#a24389fc33ea52e268a13e698afe9f718}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCWinCOFFStreamer::emitWeakReference (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Alias, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol)</td>
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

<p>Emit an weak reference from <span class="doxyComputerOutput">Alias</span> to <span class="doxyComputerOutput">Symbol</span>.</p>


<p>This corresponds to an assembler statement such as: .weakref alias, symbol</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Alias</td>
<td class="doxyParamItemDescription"><p>- The alias that is being created.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Symbol</td>
<td class="doxyParamItemDescription"><p>- The symbol being aliased.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 445 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="#ac1410ebb1de1644c3fd7019450373441">emitSymbolAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a83df6138e7dba38c0c80380486544ea0">llvm::MCSA_Weak</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#ae26e9b713a9b85d7a56343c78794269c">llvm::MCAssembler::registerSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a4acec19f33bc45f90643617e00ce9a81">llvm::MCSymbolRefExpr::VK_WEAKREF</a>.</p>

</div>
</div>

### emitWinEHHandlerData {#ab6544307ad2e9c7b8651b9c4f03778b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCWinCOFFStreamer::emitWinEHHandlerData (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 471 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### emitZerofill {#a2107d440e06a521c8e44631fd31df3fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCWinCOFFStreamer::emitZerofill (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Section, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, uint64_t Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> ByteAlignment, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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

<p>Emit the zerofill section and an optional symbol.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Section</td>
<td class="doxyParamItemDescription"><p>- The zerofill section to create and or to put the symbol</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Symbol</td>
<td class="doxyParamItemDescription"><p>- The zerofill symbol to emit, if non-NULL.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>- The size of the zerofill symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ByteAlignment</td>
<td class="doxyParamItemDescription"><p>- The alignment of the zerofill symbol.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 455 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### endCOFFSymbolDef {#a48c8a92360b68670c3f93cf6e3b6aa41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCWinCOFFStreamer::endCOFFSymbolDef ()</td>
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

<p>Marks the end of the symbol definition.</p>

<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="#abde6f25a7f003e4862df94ccdbf91ebd">CurSymbol</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>.</p>

</div>
</div>

### finishImpl {#a7f964c60245b61612ddd6509cba7eb74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCWinCOFFStreamer::finishImpl ()</td>
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

<p>Streamer specific finalization.</p>

<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 489 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="#a12d7f7b28045ca28e88138c63c174184">finalizeCGProfileEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#ad02d00947f1c26cb88d05a8ac9ea8aaa">llvm::CodeViewContext::finish</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#aa8d1c93368ccaad9bdc429b25633f943">llvm::MCObjectStreamer::finishImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a7bdf9164b69f96821c0c0269dde3ebf7">llvm::MCContext::getCVContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa24ac1300caa85825d3526b8baaec159f">llvm::COFF::IMAGE_SCN_LNK_REMOVE</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ac4f84451dc4abc997c960d484953b1d2">llvm::MCStreamer::switchSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64wincoffstreamer-cpp-/aarch64wincoffstreamer/#a2eb3606a403f00ac9653b45f4b246d1d">anonymous{AArch64WinCOFFStreamer.cpp}::AArch64WinCOFFStreamer::finishImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-armwincoffstreamer-cpp-/armwincoffstreamer/#af48e15e5d520ff47c8045588f5911e72">anonymous{ARMWinCOFFStreamer.cpp}::ARMWinCOFFStreamer::finishImpl</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86wincoffstreamer-cpp-/x86wincoffstreamer/#a174dfe9d7cb521bf4ad1cdcc1d7bcbdc">anonymous{X86WinCOFFStreamer.cpp}::X86WinCOFFStreamer::finishImpl</a>.</p>

</div>
</div>

### initSections {#a28e4c026855f296e926e3feb231b5811}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCWinCOFFStreamer::initSections (bool NoExecStack, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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

<p>Create the default sections and set the initial one.</p>

<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a>, definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#ad6394338481d436a665bb4572e9e1ffc">llvm::MCObjectStreamer::emitCodeAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ac4f84451dc4abc997c960d484953b1d2">llvm::MCStreamer::switchSection</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwincoffstreamer-h">MCWinCOFFStreamer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcwincoffstreamer-cpp">MCWinCOFFStreamer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
