---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/jitlink/aarch64
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `aarch64` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::jitlink::aarch64 { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/aarch64/gottablemanager">GOTTableManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Global Offset Table Builder. <a href="/web-llvm/docs/api/classes/llvm/jitlink/aarch64/gottablemanager/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/aarch64/plttablemanager">PLTTableManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Procedure <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#abee99c9c75d23a0304e5e58e3128a55f">Linkage</a> Table Builder. <a href="/web-llvm/docs/api/classes/llvm/jitlink/aarch64/plttablemanager/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">EdgeKind_aarch64 : <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a> { <a href="#adaafb311352b6b70437034d62373d043">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64">aarch64</a> fixups and other aarch64-specific edge kinds. <a href="#adaafb311352b6b70437034d62373d043">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa80cedc88aa3fa28ac1e91b1515a82ea">getEdgeKindName</a> (Edge::Kind K)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a string name for the given <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64">aarch64</a> edge. <a href="#aa80cedc88aa3fa28ac1e91b1515a82ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8aece3dfdd829a8318dd121de06819d0">isLoadStoreImm12</a> (uint32_t Instr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adecd0bdff8d54d6d6eb59cb909abdc49">isTestAndBranchImm14</a> (uint32_t Instr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ed829f34b9e69176fe3de4882c623d9">isCondBranchImm19</a> (uint32_t Instr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85584875f88a7cddec5b2d6205f327d0">isCompAndBranchImm19</a> (uint32_t Instr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a4973d0e044b2eed09d989b5f5f34ce">isADR</a> (uint32_t Instr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18b270c27d7172e1979be56e8f758876">isLDRLiteral</a> (uint32_t Instr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea82948d63bc3b330d72ad903f0d41a3">getPageOffset12Shift</a> (uint32_t Instr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cfabdcd9c87d8a7b080616c8319e76d">isMoveWideImm16</a> (uint32_t Instr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefd5232906dfb5d0134d5cb86d59cd8d">getMoveWide16Shift</a> (uint32_t Instr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61310b6c90769dc38a55a4b84b1cc054">applyFixup</a> (LinkGraph &amp;G, Block &amp;B, const Edge &amp;E, const Symbol *GOTSymbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply fixup expression for edge to block content. <a href="#a61310b6c90769dc38a55a4b84b1cc054">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab246c2fa3507148bda940a4f0f680f68">createAnonymousPointer</a> (LinkGraph &amp;G, Section &amp;PointerSection, Symbol *InitialTarget=nullptr, uint64_t InitialAddend=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a new pointer block in the given section and returns an Anonymous symbol pointing to it. <a href="#ab246c2fa3507148bda940a4f0f680f68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa9c9aa1ac7e99b9934a23fd0b4702e1">createPointerJumpStubBlock</a> (LinkGraph &amp;G, Section &amp;StubSection, Symbol &amp;PointerSymbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a jump stub block that jumps via the pointer at the given symbol. <a href="#aaa9c9aa1ac7e99b9934a23fd0b4702e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afea59b722159d204506a5a02667bdfe8">createAnonymousPointerJumpStub</a> (LinkGraph &amp;G, Section &amp;StubSection, Symbol &amp;PointerSymbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a jump stub that jumps via the pointer at the given symbol and an anonymous symbol pointing to it. <a href="#afea59b722159d204506a5a02667bdfe8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69bd04f026c43d7e3c5a5903a96877d7">createReentryTrampolineBlock</a> (LinkGraph &amp;G, Section &amp;TrampolineSection, Symbol &amp;ReentrySymbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a block of N reentry trampolines. <a href="#a69bd04f026c43d7e3c5a5903a96877d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad63469562c129c2c06c6e71f82ea37d5">createAnonymousReentryTrampoline</a> (LinkGraph &amp;G, Section &amp;TrampolineSection, Symbol &amp;ReentrySymbol)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aceea9a8cc2d736eb57b2818121c46452">getPointerSigningFunctionSectionName</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the name of the pointer signing function section. <a href="#aceea9a8cc2d736eb57b2818121c46452">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b6a1311d66ca584dd828968ec269156">createEmptyPointerSigningFunction</a> (LinkGraph &amp;G)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a pointer signing function section, block, and symbol to reserve space for a signing function for this <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a>. <a href="#a8b6a1311d66ca584dd828968ec269156">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92e5f360eac04874168e30f0df2bc5bb">lowerPointer64AuthEdgesToSigningFunction</a> (LinkGraph &amp;G)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> containing Pointer64Authenticated edges, transform those edges to Pointer64 and add signing code to the pointer signing function (which must already have been created by the createEmptyPointerSigningFunction pass above). <a href="#a92e5f360eac04874168e30f0df2bc5bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AppendFtor&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5c13edb875d691dffc20e456bdc41538">writeMovRegRegSeq</a> (AppendFtor &amp;Append, uint64_t DstReg, uint64_t SrcReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AppendFtor&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1d7cfdefe09dc42a8d92cdf8e1ba7237">writeMovRegImm64Seq</a> (AppendFtor &amp;Append, uint64_t Reg, uint64_t Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AppendFtor&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af23e2186772c6692361fc0385ebf6012">writePACSignSeq</a> (AppendFtor &amp;Append, unsigned DstReg, orc::ExecutorAddr RawAddr, unsigned RawAddrReg, unsigned DiscriminatorReg, unsigned Key, uint64_t EncodedDiscriminator, bool AddressDiversify)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AppendFtor&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad00be06ff205e2f0ad69e5e100d5e0e6">writeStoreRegSeq</a> (AppendFtor &amp;Append, unsigned DstLocReg, unsigned SrcReg)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54a878e42755b4a0e4cc8709f3f34e51">PointerSize</a> = 8</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64">aarch64</a> pointer size. <a href="#a54a878e42755b4a0e4cc8709f3f34e51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a181cfa45de3ed8d2ddb85568b0c6b016">NullPointerContent</a>[PointerSize] = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> null pointer content. <a href="#a181cfa45de3ed8d2ddb85568b0c6b016">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8977c0dcc341e31e5f7497441b3b5c47">PointerJumpStubContent</a>[12] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38d2666eb61e141f865f2197a8d90a37">ReentryTrampolineContent</a>[8] = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> reentry trampoline. <a href="#a38d2666eb61e141f865f2197a8d90a37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Enumerations

### EdgeKind\_aarch64 {#adaafb311352b6b70437034d62373d043}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::jitlink::aarch64::EdgeKind_aarch64 : <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represents <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64">aarch64</a> fixups and other aarch64-specific edge kinds.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pointer64<a id="adaafb311352b6b70437034d62373d043a9f6ab8a0d2f19948762b78f6d6c5f562"></a></td>
<td class="doxyEnumItemDescription">A plain 64-bit pointer value relocation (= Edge::FirstRelocation)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pointer64Authenticated<a id="adaafb311352b6b70437034d62373d043a109802d2cdabf31aaf8cb2aeac27547a"></a></td>
<td class="doxyEnumItemDescription">An arm64e authenticated pointer relocation</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pointer32<a id="adaafb311352b6b70437034d62373d043aad97367a7201c67ade1c6d15c96f0746"></a></td>
<td class="doxyEnumItemDescription">A plain 32-bit pointer value relocation</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Delta64<a id="adaafb311352b6b70437034d62373d043aa43de9079a03e5cf7ea9c96de2956a47"></a></td>
<td class="doxyEnumItemDescription">A 64-bit delta</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Delta32<a id="adaafb311352b6b70437034d62373d043a8d7dc75674b3fc58ba929cbef0217e4b"></a></td>
<td class="doxyEnumItemDescription">A 32-bit delta</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NegDelta64<a id="adaafb311352b6b70437034d62373d043adec7252c806dda04339c709cd9aec6e0"></a></td>
<td class="doxyEnumItemDescription">A 64-bit negative delta</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NegDelta32<a id="adaafb311352b6b70437034d62373d043ade36f74cb3bddd6f86b25f96238033c3"></a></td>
<td class="doxyEnumItemDescription">A 32-bit negative delta</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Branch26PCRel<a id="adaafb311352b6b70437034d62373d043a71c601f1339f93bc2c5fea1e3a225985"></a></td>
<td class="doxyEnumItemDescription">A 26-bit PC-relative branch</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TestAndBranch14PCRel<a id="adaafb311352b6b70437034d62373d043acb7c5eaf3ed95ac3a2b5dadcccd86829"></a></td>
<td class="doxyEnumItemDescription">A 14-bit PC-relative test and branch</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CondBranch19PCRel<a id="adaafb311352b6b70437034d62373d043a3bd47a01bb7612390e36cca6b1412b28"></a></td>
<td class="doxyEnumItemDescription">A 19-bit PC-relative conditional branch</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MoveWide16<a id="adaafb311352b6b70437034d62373d043abee974069f5d980fe119624159e787fe"></a></td>
<td class="doxyEnumItemDescription">A 16-bit slice of the target address (which slice depends on the instruction at the fixup location)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LDRLiteral19<a id="adaafb311352b6b70437034d62373d043a0014e81d3ba9092cf8b528e9c4976509"></a></td>
<td class="doxyEnumItemDescription">The signed 21-bit delta from the fixup to the target</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADRLiteral21<a id="adaafb311352b6b70437034d62373d043acded784063fe1cacf961152240dbfe8c"></a></td>
<td class="doxyEnumItemDescription">The signed 21-bit delta from the fixup to the target</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Page21<a id="adaafb311352b6b70437034d62373d043a69369335041eac416a42ce8fd039d38e"></a></td>
<td class="doxyEnumItemDescription">The signed 21-bit delta from the fixup page to the page containing the target</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PageOffset12<a id="adaafb311352b6b70437034d62373d043af73aef9a424551ef1049e0bcb3e71ac1"></a></td>
<td class="doxyEnumItemDescription">The 12-bit (potentially shifted) offset of the target within its page</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GotPageOffset15<a id="adaafb311352b6b70437034d62373d043ab6bafbc8841c3ff8d19e709ef4b71609"></a></td>
<td class="doxyEnumItemDescription">The 15-bit offset of the GOT entry from the GOT table</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RequestGOTAndTransformToPage21<a id="adaafb311352b6b70437034d62373d043acdbf75e478b336cc041c86d8c4ec2a81"></a></td>
<td class="doxyEnumItemDescription">A GOT entry getter/constructor, transformed to Page21 pointing at the GOT entry for the original target</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RequestGOTAndTransformToPageOffset12<a id="adaafb311352b6b70437034d62373d043ad9a0f2806d0a2a90cd99edc0e54caf10"></a></td>
<td class="doxyEnumItemDescription">A GOT entry getter/constructor, transformed to Pageoffset12 pointing at the GOT entry for the original target</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RequestGOTAndTransformToPageOffset15<a id="adaafb311352b6b70437034d62373d043a10e93e2b017fdd1a792986be9fec69f4"></a></td>
<td class="doxyEnumItemDescription">A GOT entry getter/constructor, transformed to Pageoffset15 pointing at the GOT entry for the original target</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RequestGOTAndTransformToDelta32<a id="adaafb311352b6b70437034d62373d043ae6ed0aefe60a60c482de8fde088bba9b"></a></td>
<td class="doxyEnumItemDescription">A GOT entry getter/constructor, transformed to Delta32 pointing at the GOT entry for the original target</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RequestTLVPAndTransformToPage21<a id="adaafb311352b6b70437034d62373d043ab08a3e147eb8472939a6ee86abecbdd5"></a></td>
<td class="doxyEnumItemDescription">A TLVP entry getter/constructor, transformed to Page21</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RequestTLVPAndTransformToPageOffset12<a id="adaafb311352b6b70437034d62373d043a5c427ef98778eb60400f10d3d9cdccfd"></a></td>
<td class="doxyEnumItemDescription">A TLVP entry getter/constructor, transformed to PageOffset12</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RequestTLSDescEntryAndTransformToPage21<a id="adaafb311352b6b70437034d62373d043afbe257ada8dca290ade8bf1e3aabb917"></a></td>
<td class="doxyEnumItemDescription">A TLSDesc entry getter/constructor, transformed to Page21</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RequestTLSDescEntryAndTransformToPageOffset12<a id="adaafb311352b6b70437034d62373d043a67f88d116fb2dc50609a16d0f89c8a50"></a></td>
<td class="doxyEnumItemDescription">A TLSDesc entry getter/constructor, transformed to PageOffset12</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### applyFixup() {#a61310b6c90769dc38a55a4b84b1cc054}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::aarch64::applyFixup (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> &amp; E, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> * GOTSymbol)</td>
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

<p>Apply fixup expression for edge to block content.</p>

<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>


<p>References <a href="#adaafb311352b6b70437034d62373d043acded784063fe1cacf961152240dbfe8c">ADRLiteral21</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#adaafb311352b6b70437034d62373d043a71c601f1339f93bc2c5fea1e3a225985">Branch26PCRel</a>, <a href="#adaafb311352b6b70437034d62373d043a3bd47a01bb7612390e36cca6b1412b28">CondBranch19PCRel</a>, <a href="#adaafb311352b6b70437034d62373d043a8d7dc75674b3fc58ba929cbef0217e4b">Delta32</a>, <a href="#adaafb311352b6b70437034d62373d043aa43de9079a03e5cf7ea9c96de2956a47">Delta64</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a4a30a3fae601106b8b33c0871aa3069d">getAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol/#a9266b50b560808e8f69eb394690d79c4">llvm::jitlink::Symbol::getAddress</a>, <a href="#aa80cedc88aa3fa28ac1e91b1515a82ea">getEdgeKindName</a>, <a href="#aefd5232906dfb5d0134d5cb86d59cd8d">getMoveWide16Shift</a>, <a href="#aea82948d63bc3b330d72ad903f0d41a3">getPageOffset12Shift</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr/#a4ee908fb9052f020e3c50e3f1a7d81c5">llvm::orc::ExecutorAddr::getValue</a>, <a href="#adaafb311352b6b70437034d62373d043ab6bafbc8841c3ff8d19e709ef4b71609">GotPageOffset15</a>, <a href="#a2a4973d0e044b2eed09d989b5f5f34ce">isADR</a>, <a href="#a85584875f88a7cddec5b2d6205f327d0">isCompAndBranchImm19</a>, <a href="#a2ed829f34b9e69176fe3de4882c623d9">isCondBranchImm19</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="#a18b270c27d7172e1979be56e8f758876">isLDRLiteral</a>, <a href="#a7cfabdcd9c87d8a7b080616c8319e76d">isMoveWideImm16</a>, <a href="#adecd0bdff8d54d6d6eb59cb909abdc49">isTestAndBranchImm14</a>, <a href="#adaafb311352b6b70437034d62373d043a0014e81d3ba9092cf8b528e9c4976509">LDRLiteral19</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a061c97aa3532f0b4a2390febaa911a65">llvm::jitlink::makeTargetOutOfRangeError</a>, <a href="#adaafb311352b6b70437034d62373d043abee974069f5d980fe119624159e787fe">MoveWide16</a>, <a href="#adaafb311352b6b70437034d62373d043ade36f74cb3bddd6f86b25f96238033c3">NegDelta32</a>, <a href="#adaafb311352b6b70437034d62373d043adec7252c806dda04339c709cd9aec6e0">NegDelta64</a>, <a href="#adaafb311352b6b70437034d62373d043a69369335041eac416a42ce8fd039d38e">Page21</a>, <a href="#adaafb311352b6b70437034d62373d043af73aef9a424551ef1049e0bcb3e71ac1">PageOffset12</a>, <a href="#adaafb311352b6b70437034d62373d043aad97367a7201c67ade1c6d15c96f0746">Pointer32</a>, <a href="#adaafb311352b6b70437034d62373d043a9f6ab8a0d2f19948762b78f6d6c5f562">Pointer64</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="#adaafb311352b6b70437034d62373d043acb7c5eaf3ed95ac3a2b5dadcccd86829">TestAndBranch14PCRel</a>.</p>

</div>
</div>

### createAnonymousPointer() {#ab246c2fa3507148bda940a4f0f680f68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Symbol &amp; llvm::jitlink::aarch64::createAnonymousPointer (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp; PointerSection, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> * InitialTarget=nullptr, uint64_t InitialAddend=0)</td>
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

<p>Creates a new pointer block in the given section and returns an Anonymous symbol pointing to it.</p>


<p>If InitialTarget is given then an Pointer64 relocation will be added to the block pointing at InitialTarget.</p>


<p>The pointer block will have the following default values: alignment: 64-bit alignment-offset: 0 address: highest allowable (~7U)</p>


<p>Definition at line 721 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#a181cfa45de3ed8d2ddb85568b0c6b016">NullPointerContent</a> and <a href="#adaafb311352b6b70437034d62373d043a9f6ab8a0d2f19948762b78f6d6c5f562">Pointer64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/aarch64/gottablemanager/#a59f864b0c47abab716508e5683d3e82a">llvm::jitlink::aarch64::GOTTableManager::createEntry</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#af86dbecbbb47825e36f9af37bd6868ca">llvm::jitlink::getAnonymousPointerCreator</a>.</p>

</div>
</div>

### createAnonymousPointerJumpStub() {#afea59b722159d204506a5a02667bdfe8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Symbol &amp; llvm::jitlink::aarch64::createAnonymousPointerJumpStub (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp; StubSection, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; PointerSymbol)</td>
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

<p>Create a jump stub that jumps via the pointer at the given symbol and an anonymous symbol pointing to it.</p>


<p>Return the anonymous symbol.</p>


<p>The stub block will be created by createPointerJumpStubBlock.</p>


<p>Definition at line 750 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>


<p>References <a href="#aaa9c9aa1ac7e99b9934a23fd0b4702e1">createPointerJumpStubBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="#a8977c0dcc341e31e5f7497441b3b5c47">PointerJumpStubContent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/aarch64/plttablemanager/#aa15da2c9de13f9495f443216bcbd8991">llvm::jitlink::aarch64::PLTTableManager::createEntry</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a6e58d27e8cd9ba5dadc9194100b69be4">llvm::jitlink::getPointerJumpStubCreator</a>.</p>

</div>
</div>

### createAnonymousReentryTrampoline() {#ad63469562c129c2c06c6e71f82ea37d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Symbol &amp; llvm::jitlink::aarch64::createAnonymousReentryTrampoline (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp; TrampolineSection, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; ReentrySymbol)</td>
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



<p>Definition at line 776 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>


<p>References <a href="#a69bd04f026c43d7e3c5a5903a96877d7">createReentryTrampolineBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="#a38d2666eb61e141f865f2197a8d90a37">ReentryTrampolineContent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/jitlinkreentrytrampolines/#a65b27dfd43dad3af09bd244752f7eadf">llvm::orc::JITLinkReentryTrampolines::Create</a>.</p>

</div>
</div>

### createEmptyPointerSigningFunction() {#a8b6a1311d66ca584dd828968ec269156}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::aarch64::createEmptyPointerSigningFunction (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a pointer signing function section, block, and symbol to reserve space for a signing function for this <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a>.</p>


<p>Clients should insert this pass in the post-prune phase, and add the paired lowerPointer64AuthEdgesToSigningFunction pass to the pre-fixup phase.</p>


<p>No new Pointer64Auth edges can be inserted into the graph between when this pass is run and when the pass below runs (since there will not be sufficient space reserved in the signing function to write the signing code for them).</p>


<p>Clients should insert this pass in the post-prune phase, and add the paired lowerPointer64AuthEdgesToSigningFunction pass to the pre-fixup phase.</p>


<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch64-cpp">aarch64.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2fbb59fad28934f72ede7ddc316dfc89a953feeff1e20f40677fb7f77c073b3be">llvm::orc::Exec</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#abdd6ae2070338087f3d5d54200d708d6afd565de81da1c94807c0b80840ba18b0">llvm::orc::Finalize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#aceea9a8cc2d736eb57b2818121c46452">getPointerSigningFunctionSectionName</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#adaafb311352b6b70437034d62373d043a109802d2cdabf31aaf8cb2aeac27547a">Pointer64Authenticated</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2fbb59fad28934f72ede7ddc316dfc89a7a1a5f3e79fdc91edf2f5ead9d66abb4">llvm::orc::Read</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a3a5a64d0c1b7bad36afd4b742f3069db">llvm::jitlink::link_MachO_arm64</a>.</p>

</div>
</div>

### createPointerJumpStubBlock() {#aaa9c9aa1ac7e99b9934a23fd0b4702e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Block &amp; llvm::jitlink::aarch64::createPointerJumpStubBlock (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp; StubSection, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; PointerSymbol)</td>
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

<p>Create a jump stub block that jumps via the pointer at the given symbol.</p>


<p>The stub block will have the following default values: alignment: 32-bit alignment-offset: 0 address: highest allowable: (~11U)</p>


<p>Definition at line 737 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#adaafb311352b6b70437034d62373d043a69369335041eac416a42ce8fd039d38e">Page21</a>, <a href="#adaafb311352b6b70437034d62373d043af73aef9a424551ef1049e0bcb3e71ac1">PageOffset12</a> and <a href="#a8977c0dcc341e31e5f7497441b3b5c47">PointerJumpStubContent</a>.</p>


<p>Referenced by <a href="#afea59b722159d204506a5a02667bdfe8">createAnonymousPointerJumpStub</a>.</p>

</div>
</div>

### createReentryTrampolineBlock() {#a69bd04f026c43d7e3c5a5903a96877d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Block &amp; llvm::jitlink::aarch64::createReentryTrampolineBlock (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp; TrampolineSection, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; ReentrySymbol)</td>
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

<p>Create a block of N reentry trampolines.</p>

<p>Definition at line 767 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#adaafb311352b6b70437034d62373d043a71c601f1339f93bc2c5fea1e3a225985">Branch26PCRel</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="#a38d2666eb61e141f865f2197a8d90a37">ReentryTrampolineContent</a>.</p>


<p>Referenced by <a href="#ad63469562c129c2c06c6e71f82ea37d5">createAnonymousReentryTrampoline</a>.</p>

</div>
</div>

### getEdgeKindName() {#aa80cedc88aa3fa28ac1e91b1515a82ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::jitlink::aarch64::getEdgeKindName (<a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a> K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a string name for the given <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64">aarch64</a> edge.</p>


<p>For debugging purposes only</p>


<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch64-cpp">aarch64.cpp</a>.</p>


<p>References <a href="#adaafb311352b6b70437034d62373d043acded784063fe1cacf961152240dbfe8c">ADRLiteral21</a>, <a href="#adaafb311352b6b70437034d62373d043a71c601f1339f93bc2c5fea1e3a225985">Branch26PCRel</a>, <a href="#adaafb311352b6b70437034d62373d043a3bd47a01bb7612390e36cca6b1412b28">CondBranch19PCRel</a>, <a href="#adaafb311352b6b70437034d62373d043a8d7dc75674b3fc58ba929cbef0217e4b">Delta32</a>, <a href="#adaafb311352b6b70437034d62373d043aa43de9079a03e5cf7ea9c96de2956a47">Delta64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a06eee57acde48953ffd29ae8d337202e">llvm::jitlink::getGenericEdgeKindName</a>, <a href="#adaafb311352b6b70437034d62373d043ab6bafbc8841c3ff8d19e709ef4b71609">GotPageOffset15</a>, <a href="#adaafb311352b6b70437034d62373d043a0014e81d3ba9092cf8b528e9c4976509">LDRLiteral19</a>, <a href="#adaafb311352b6b70437034d62373d043abee974069f5d980fe119624159e787fe">MoveWide16</a>, <a href="#adaafb311352b6b70437034d62373d043ade36f74cb3bddd6f86b25f96238033c3">NegDelta32</a>, <a href="#adaafb311352b6b70437034d62373d043adec7252c806dda04339c709cd9aec6e0">NegDelta64</a>, <a href="#adaafb311352b6b70437034d62373d043a69369335041eac416a42ce8fd039d38e">Page21</a>, <a href="#adaafb311352b6b70437034d62373d043af73aef9a424551ef1049e0bcb3e71ac1">PageOffset12</a>, <a href="#adaafb311352b6b70437034d62373d043aad97367a7201c67ade1c6d15c96f0746">Pointer32</a>, <a href="#adaafb311352b6b70437034d62373d043a9f6ab8a0d2f19948762b78f6d6c5f562">Pointer64</a>, <a href="#adaafb311352b6b70437034d62373d043a109802d2cdabf31aaf8cb2aeac27547a">Pointer64Authenticated</a>, <a href="#adaafb311352b6b70437034d62373d043ae6ed0aefe60a60c482de8fde088bba9b">RequestGOTAndTransformToDelta32</a>, <a href="#adaafb311352b6b70437034d62373d043acdbf75e478b336cc041c86d8c4ec2a81">RequestGOTAndTransformToPage21</a>, <a href="#adaafb311352b6b70437034d62373d043ad9a0f2806d0a2a90cd99edc0e54caf10">RequestGOTAndTransformToPageOffset12</a>, <a href="#adaafb311352b6b70437034d62373d043a10e93e2b017fdd1a792986be9fec69f4">RequestGOTAndTransformToPageOffset15</a>, <a href="#adaafb311352b6b70437034d62373d043afbe257ada8dca290ade8bf1e3aabb917">RequestTLSDescEntryAndTransformToPage21</a>, <a href="#adaafb311352b6b70437034d62373d043a67f88d116fb2dc50609a16d0f89c8a50">RequestTLSDescEntryAndTransformToPageOffset12</a>, <a href="#adaafb311352b6b70437034d62373d043ab08a3e147eb8472939a6ee86abecbdd5">RequestTLVPAndTransformToPage21</a>, <a href="#adaafb311352b6b70437034d62373d043a5c427ef98778eb60400f10d3d9cdccfd">RequestTLVPAndTransformToPageOffset12</a> and <a href="#adaafb311352b6b70437034d62373d043acb7c5eaf3ed95ac3a2b5dadcccd86829">TestAndBranch14PCRel</a>.</p>


<p>Referenced by <a href="#a61310b6c90769dc38a55a4b84b1cc054">applyFixup</a>.</p>

</div>
</div>

### getMoveWide16Shift() {#aefd5232906dfb5d0134d5cb86d59cd8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::jitlink::aarch64::getMoveWide16Shift (uint32_t Instr)</td>
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



<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>


<p>Reference <a href="#a7cfabdcd9c87d8a7b080616c8319e76d">isMoveWideImm16</a>.</p>


<p>Referenced by <a href="#a61310b6c90769dc38a55a4b84b1cc054">applyFixup</a>.</p>

</div>
</div>

### getPageOffset12Shift() {#aea82948d63bc3b330d72ad903f0d41a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::jitlink::aarch64::getPageOffset12Shift (uint32_t Instr)</td>
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



<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>


<p>Reference <a href="#a8aece3dfdd829a8318dd121de06819d0">isLoadStoreImm12</a>.</p>


<p>Referenced by <a href="#a61310b6c90769dc38a55a4b84b1cc054">applyFixup</a>.</p>

</div>
</div>

### getPointerSigningFunctionSectionName() {#aceea9a8cc2d736eb57b2818121c46452}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::jitlink::aarch64::getPointerSigningFunctionSectionName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the name of the pointer signing function section.</p>

<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch64-cpp">aarch64.cpp</a>.</p>


<p>Referenced by <a href="#a8b6a1311d66ca584dd828968ec269156">createEmptyPointerSigningFunction</a> and <a href="#a92e5f360eac04874168e30f0df2bc5bb">lowerPointer64AuthEdgesToSigningFunction</a>.</p>

</div>
</div>

### isADR() {#a2a4973d0e044b2eed09d989b5f5f34ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::jitlink::aarch64::isADR (uint32_t Instr)</td>
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



<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>


<p>Referenced by <a href="#a61310b6c90769dc38a55a4b84b1cc054">applyFixup</a>.</p>

</div>
</div>

### isCompAndBranchImm19() {#a85584875f88a7cddec5b2d6205f327d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::jitlink::aarch64::isCompAndBranchImm19 (uint32_t Instr)</td>
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



<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>


<p>Referenced by <a href="#a61310b6c90769dc38a55a4b84b1cc054">applyFixup</a>.</p>

</div>
</div>

### isCondBranchImm19() {#a2ed829f34b9e69176fe3de4882c623d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::jitlink::aarch64::isCondBranchImm19 (uint32_t Instr)</td>
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



<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>


<p>Referenced by <a href="#a61310b6c90769dc38a55a4b84b1cc054">applyFixup</a>.</p>

</div>
</div>

### isLDRLiteral() {#a18b270c27d7172e1979be56e8f758876}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::jitlink::aarch64::isLDRLiteral (uint32_t Instr)</td>
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



<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>


<p>Referenced by <a href="#a61310b6c90769dc38a55a4b84b1cc054">applyFixup</a>.</p>

</div>
</div>

### isLoadStoreImm12() {#a8aece3dfdd829a8318dd121de06819d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::jitlink::aarch64::isLoadStoreImm12 (uint32_t Instr)</td>
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



<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>


<p>Referenced by <a href="#aea82948d63bc3b330d72ad903f0d41a3">getPageOffset12Shift</a>.</p>

</div>
</div>

### isMoveWideImm16() {#a7cfabdcd9c87d8a7b080616c8319e76d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::jitlink::aarch64::isMoveWideImm16 (uint32_t Instr)</td>
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



<p>Definition at line 476 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>


<p>Referenced by <a href="#a61310b6c90769dc38a55a4b84b1cc054">applyFixup</a> and <a href="#aefd5232906dfb5d0134d5cb86d59cd8d">getMoveWide16Shift</a>.</p>

</div>
</div>

### isTestAndBranchImm14() {#adecd0bdff8d54d6d6eb59cb909abdc49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::jitlink::aarch64::isTestAndBranchImm14 (uint32_t Instr)</td>
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



<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>


<p>Referenced by <a href="#a61310b6c90769dc38a55a4b84b1cc054">applyFixup</a>.</p>

</div>
</div>

### lowerPointer64AuthEdgesToSigningFunction() {#a92e5f360eac04874168e30f0df2bc5bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::aarch64::lowerPointer64AuthEdgesToSigningFunction (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> containing Pointer64Authenticated edges, transform those edges to Pointer64 and add signing code to the pointer signing function (which must already have been created by the createEmptyPointerSigningFunction pass above).</p>


<p>Given a <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> containing Pointer64Auth edges, transform those edges to Pointer64 and add code to sign the pointers in the executor.</p>


<p>This function will add a $__ptrauth_sign section with finalization-lifetime containing an anonymous function that will sign all pointers in the graph. An allocation action will be added to run this function during finalization.</p>


<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch64-cpp">aarch64.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#aceea9a8cc2d736eb57b2818121c46452">getPointerSigningFunctionSectionName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#aa21629cef4aed37ffc47ef8681c46a99aa9b64b2f23ec4cf94410dcbad41796d6">llvm::jitlink::Edge::KeepAlive</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="#adaafb311352b6b70437034d62373d043a109802d2cdabf31aaf8cb2aeac27547a">Pointer64Authenticated</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamwriter/#a344647bc1c4a4b53334296eba145d408">llvm::BinaryStreamWriter::writeInteger</a>, <a href="#a1d7cfdefe09dc42a8d92cdf8e1ba7237">writeMovRegImm64Seq</a>, <a href="#af23e2186772c6692361fc0385ebf6012">writePACSignSeq</a> and <a href="#ad00be06ff205e2f0ad69e5e100d5e0e6">writeStoreRegSeq</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a3a5a64d0c1b7bad36afd4b742f3069db">llvm::jitlink::link_MachO_arm64</a>.</p>

</div>
</div>

### writeMovRegImm64Seq() {#a1d7cfdefe09dc42a8d92cdf8e1ba7237}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AppendFtor&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::aarch64::writeMovRegImm64Seq (AppendFtor &amp; Append, uint64_t Reg, uint64_t Imm)</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch64-cpp">aarch64.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a92e5f360eac04874168e30f0df2bc5bb">lowerPointer64AuthEdgesToSigningFunction</a> and <a href="#af23e2186772c6692361fc0385ebf6012">writePACSignSeq</a>.</p>

</div>
</div>

### writeMovRegRegSeq() {#a5c13edb875d691dffc20e456bdc41538}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AppendFtor&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::aarch64::writeMovRegRegSeq (AppendFtor &amp; Append, uint64_t DstReg, uint64_t SrcReg)</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch64-cpp">aarch64.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#af23e2186772c6692361fc0385ebf6012">writePACSignSeq</a>.</p>

</div>
</div>

### writePACSignSeq() {#af23e2186772c6692361fc0385ebf6012}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AppendFtor&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::aarch64::writePACSignSeq (AppendFtor &amp; Append, unsigned DstReg, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">orc::ExecutorAddr</a> RawAddr, unsigned RawAddrReg, unsigned DiscriminatorReg, unsigned Key, uint64_t EncodedDiscriminator, bool AddressDiversify)</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch64-cpp">aarch64.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="#a1d7cfdefe09dc42a8d92cdf8e1ba7237">writeMovRegImm64Seq</a> and <a href="#a5c13edb875d691dffc20e456bdc41538">writeMovRegRegSeq</a>.</p>


<p>Referenced by <a href="#a92e5f360eac04874168e30f0df2bc5bb">lowerPointer64AuthEdgesToSigningFunction</a>.</p>

</div>
</div>

### writeStoreRegSeq() {#ad00be06ff205e2f0ad69e5e100d5e0e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AppendFtor&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::aarch64::writeStoreRegSeq (AppendFtor &amp; Append, unsigned DstLocReg, unsigned SrcReg)</td>
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



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch64-cpp">aarch64.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a92e5f360eac04874168e30f0df2bc5bb">lowerPointer64AuthEdgesToSigningFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### NullPointerContent {#a181cfa45de3ed8d2ddb85568b0c6b016}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char llvm::jitlink::aarch64::NullPointerContent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> null pointer content.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {0x00, 0x00, 0x00, 0x00,
                                    0x00, 0x00, 0x00, 0x00}
</div>
</dd>
</dl>

<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch64-cpp">aarch64.cpp</a>.</p>


<p>Referenced by <a href="#ab246c2fa3507148bda940a4f0f680f68">createAnonymousPointer</a>.</p>

</div>
</div>

### PointerJumpStubContent {#a8977c0dcc341e31e5f7497441b3b5c47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char llvm::jitlink::aarch64::PointerJumpStubContent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    0x10, 0x00, 0x00, (char)0x90u, 
    0x10, 0x02, 0x40, (char)0xf9u, 
    0x00, 0x02, 0x1f, (char)0xd6u  
}
</div>
</dd>
</dl>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch64-cpp">aarch64.cpp</a>.</p>


<p>Referenced by <a href="#afea59b722159d204506a5a02667bdfe8">createAnonymousPointerJumpStub</a> and <a href="#aaa9c9aa1ac7e99b9934a23fd0b4702e1">createPointerJumpStubBlock</a>.</p>

</div>
</div>

### PointerSize {#a54a878e42755b4a0e4cc8709f3f34e51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::jitlink::aarch64::PointerSize = 8</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64">aarch64</a> pointer size.</p>

<p>Definition at line 697 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/machojitlinker-arm64/#a113f10ffe5b6be0ae401eaad984c4a4a">llvm::jitlink::MachOJITLinker_arm64::JITLinker&lt; MachOJITLinker_arm64 &gt;</a>.</p>

</div>
</div>

### ReentryTrampolineContent {#a38d2666eb61e141f865f2197a8d90a37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char llvm::jitlink::aarch64::ReentryTrampolineContent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> reentry trampoline.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    (char)0xfd, 0x7b, (char)0xbf, (char)0xa9, 
    0x00,       0x00, 0x00,       (char)0x94  
}
</div>
</dd>
</dl>


<p>Contains the instruction sequence for a trampoline that stores its return address (and stack pointer) on the stack and calls the given reentry symbol: STP x29, x30, [sp, #-16]! BL &lt;reentry-symbol&gt;</p>


<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch64-cpp">aarch64.cpp</a>.</p>


<p>Referenced by <a href="#ad63469562c129c2c06c6e71f82ea37d5">createAnonymousReentryTrampoline</a> and <a href="#a69bd04f026c43d7e3c5a5903a96877d7">createReentryTrampolineBlock</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch64-cpp">aarch64.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
