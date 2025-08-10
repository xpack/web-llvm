---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/hexagonshuffler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `HexagonShuffler` Class



## Declaration

<div class="doxyDeclaration">
class llvm::HexagonShuffler { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">Target/Hexagon/MCTargetDesc/HexagonShuffler.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hexagonmcshuffler">HexagonMCShuffler</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bf48781a4bc4943575e1b9974e9b327">iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a9eae7ba1448d9866beca95a042de2e11">HexagonPacket::iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af93df62e2cec0460871849d764ad9dbd">const_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#aa11b903431c1931920939bac6b5293a2">HexagonPacket::const_iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a725539af4ead14b55751221f5514866a">packet_range</a> = <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a9eae7ba1448d9866beca95a042de2e11">HexagonPacket::iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc96a82a4a06d0527d4e51778fef409b">const_packet_range</a> = <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#aa11b903431c1931920939bac6b5293a2">HexagonPacket::const_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a335f7f682a937d65f8000be82a17385a">InstPredicate</a> = bool(*)(<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp;)</td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac496b99838b86e0c40df1b389ec8cc22">HexagonPacket</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/hexagoninstr">HexagonInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h/#ac4997a2808cebb7b14e08a5429558dc1">HEXAGON_PRESHUFFLE_PACKET_SIZE</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bea60acdfd80dd427535cbe669f568b">HexagonShuffler</a> (MCContext &amp;Context, bool ReportErrors, MCInstrInfo const &amp;MCII, MCSubtargetInfo const &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3551a59db2db418fd7682f20a3049a19">reset</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50666b23b01ea45d060a07f7e9718b62">check</a> (const bool RequireShuffle=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> that the packet is legal and enforce relative insn order. <a href="#a50666b23b01ea45d060a07f7e9718b62">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a572425344ad3846264384af43858a5e1">shuffle</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ebda228b167d8ea7cc3982c5636cd5b">size</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b17a068b924e23cc4b879be52707404">isMemReorderDisabled</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a8bf48781a4bc4943575e1b9974e9b327">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeba61eef1aab98d3df9c858d69acec86">begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a8bf48781a4bc4943575e1b9974e9b327">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c9bb04fa6e283d18e688dc91543f180">end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af93df62e2cec0460871849d764ad9dbd">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18148551f8767184020ebda8998e33e3">cbegin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af93df62e2cec0460871849d764ad9dbd">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab836a8979104a349893a809967bb0d4c">cend</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a725539af4ead14b55751221f5514866a">packet_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c100d8373654a0eb40d00132ee87377">insts</a> (HexagonPacket &amp;P)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#abc96a82a4a06d0527d4e51778fef409b">const_packet_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7102198a6129316dec9430539349ff56">insts</a> (HexagonPacket const &amp;P) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a725539af4ead14b55751221f5514866a">packet_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07b8ee7062fa43085d66306471c646ed">insts</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#abc96a82a4a06d0527d4e51778fef409b">const_packet_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc991f81a58d6ca06346806d04244879">insts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef6718eb21fbc79c73bc13605c6edc57">HasInstWith</a> (InstPredicate Pred) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcc1832a977723198b2dd224e9d65efa">append</a> (MCInst const &amp;ID, MCInst const *Extender, unsigned S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d49837058a40c9b850e92eac8f19f6e">reportError</a> (Twine const &amp;Msg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b20a8b7424525d8a92b57da076b012f">reportResourceError</a> (HexagonPacketSummary const &amp;Summary, StringRef Err)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7d91a59f353ae38556450341aea270d">reportResourceUsage</a> (HexagonPacketSummary const &amp;Summary)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcd8bc0e86f749f86f549cafcc1e32ad">applySlotRestrictions</a> (HexagonPacketSummary const &amp;Summary, const bool DoShuffle)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ddcba5b6fe2c4762daa50893c3cfe8c">restrictSlot1AOK</a> (HexagonPacketSummary const &amp;Summary)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45bea692e1c1def80eaae16d764ae97e">restrictNoSlot1Store</a> (HexagonPacketSummary const &amp;Summary)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9d908ab3d65e6f5df23ec51e9715cd9">restrictNoSlot1</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7246dfd483f4ca9b7a755c02dbfb0443">restrictStoreLoadOrder</a> (HexagonPacketSummary const &amp;Summary)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9a1fce0d2529096990ec01dcf4f3ecb">restrictBranchOrder</a> (HexagonPacketSummary const &amp;Summary)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae197c24a98a05c2c30b429166a039bb4">restrictPreferSlot3</a> (HexagonPacketSummary const &amp;Summary, const bool DoShuffle)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4468bd7691e8ea1515151762d24f4085">permitNonSlot</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">HexagonPacket</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af989f1a0571137412646a2bb7fa4a40f">tryAuction</a> (HexagonPacketSummary const &amp;Summary)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">HexagonPacketSummary</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafe1b52718a5cd8afd0dbb15e45b5c17">GetPacketSummary</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aded3fef7d013b75faecea45e61838494">ValidPacketMemoryOps</a> (HexagonPacketSummary const &amp;Summary) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5464b66f7393d7dbd8c601305cdbc0b">ValidResourceUsage</a> (HexagonPacketSummary const &amp;Summary)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04e7bcc848338f170b3227b216aec616">Context</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa287ac3a1615e464dacff4aba682d34f">BundleFlags</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>  &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5472a417eff2e300c9e8f08bdee1297">MCII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>  &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab93a83f6136cca7d527d21196676ccc4">STI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb6e75791bd7cfb1b0b26c7a5cc20527">Loc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ec546f90ddb525b6500986e6ac27239">ReportErrors</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e421183afe3f6a1234a85098b1a4782">CheckFailure</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>, std::string &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3c5637df6f10e92c0fadfa921b00d01">AppliedRestrictions</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">HexagonPacket</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6ec280d18eb2e450a9dc9fc8d2ecd2d">Packet</a></td>
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


<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#af93df62e2cec0460871849d764ad9dbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::HexagonShuffler::const_iterator =  HexagonPacket::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>.</p>

</div>
</div>

### const\_packet\_range {#abc96a82a4a06d0527d4e51778fef409b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::HexagonShuffler::const_packet_range =  iterator_range&lt;HexagonPacket::const_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>.</p>

</div>
</div>

### InstPredicate {#a335f7f682a937d65f8000be82a17385a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::HexagonShuffler::InstPredicate =  bool (*)(MCInstrInfo const &amp;, MCInst const &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>.</p>

</div>
</div>

### iterator {#a8bf48781a4bc4943575e1b9974e9b327}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::HexagonShuffler::iterator =  HexagonPacket::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>.</p>

</div>
</div>

### packet\_range {#a725539af4ead14b55751221f5514866a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::HexagonShuffler::packet_range =  iterator_range&lt;HexagonPacket::iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### HexagonPacket {#ac496b99838b86e0c40df1b389ec8cc22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::HexagonShuffler::HexagonPacket = 
      SmallVector&lt;HexagonInstr, HEXAGON_PRESHUFFLE_PACKET_SIZE&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### HexagonShuffler() {#a1bea60acdfd80dd427535cbe669f568b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HexagonShuffler::HexagonShuffler (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Context, bool ReportErrors, <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>, definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp">HexagonShuffler.cpp</a>.</p>


<p>References <a href="#aa287ac3a1615e464dacff4aba682d34f">BundleFlags</a>, <a href="#a1e421183afe3f6a1234a85098b1a4782">CheckFailure</a>, <a href="#a04e7bcc848338f170b3227b216aec616">Context</a>, <a href="#ac5472a417eff2e300c9e8f08bdee1297">MCII</a>, <a href="#a8ec546f90ddb525b6500986e6ac27239">ReportErrors</a>, <a href="#a3551a59db2db418fd7682f20a3049a19">reset</a> and <a href="#ab93a83f6136cca7d527d21196676ccc4">STI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonmcshuffler/#ab828145ae3ee983f06d2efd4ad7a21cb">llvm::HexagonMCShuffler::HexagonMCShuffler</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonmcshuffler/#a09dfd3467401684077720391d3a69ea0">llvm::HexagonMCShuffler::HexagonMCShuffler</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### append() {#abcc1832a977723198b2dd224e9d65efa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonShuffler::append (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; ID, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * Extender, unsigned S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>, definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp">HexagonShuffler.cpp</a>.</p>


<p>References <a href="#ac5472a417eff2e300c9e8f08bdee1297">MCII</a> and <a href="#ab93a83f6136cca7d527d21196676ccc4">STI</a>.</p>

</div>
</div>

### begin() {#aeba61eef1aab98d3df9c858d69acec86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::HexagonShuffler::begin ()</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>.</p>


<p>Referenced by <a href="#aafe1b52718a5cd8afd0dbb15e45b5c17">GetPacketSummary</a>, <a href="#a07b8ee7062fa43085d66306471c646ed">insts</a> and <a href="#a7246dfd483f4ca9b7a755c02dbfb0443">restrictStoreLoadOrder</a>.</p>

</div>
</div>

### cbegin() {#a18148551f8767184020ebda8998e33e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::HexagonShuffler::cbegin ()</td>
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



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>.</p>


<p>Referenced by <a href="#abc991f81a58d6ca06346806d04244879">insts</a>.</p>

</div>
</div>

### cend() {#ab836a8979104a349893a809967bb0d4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::HexagonShuffler::cend ()</td>
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



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>.</p>


<p>Referenced by <a href="#abc991f81a58d6ca06346806d04244879">insts</a>.</p>

</div>
</div>

### check() {#a50666b23b01ea45d060a07f7e9718b62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonShuffler::check (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool RequireShuffle=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> that the packet is legal and enforce relative insn order.</p>

<p>Declaration at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>, definition at line 610 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp">HexagonShuffler.cpp</a>.</p>


<p>References <a href="#abcd8bc0e86f749f86f549cafcc1e32ad">applySlotRestrictions</a>, <a href="#a1e421183afe3f6a1234a85098b1a4782">CheckFailure</a>, <a href="#aafe1b52718a5cd8afd0dbb15e45b5c17">GetPacketSummary</a>, <a href="#a7d49837058a40c9b850e92eac8f19f6e">reportError</a>, <a href="#aded3fef7d013b75faecea45e61838494">ValidPacketMemoryOps</a> and <a href="#ab5464b66f7393d7dbd8c601305cdbc0b">ValidResourceUsage</a>.</p>


<p>Referenced by <a href="#a572425344ad3846264384af43858a5e1">shuffle</a>.</p>

</div>
</div>

### end() {#a0c9bb04fa6e283d18e688dc91543f180}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::HexagonShuffler::end ()</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>.</p>


<p>Referenced by <a href="#aafe1b52718a5cd8afd0dbb15e45b5c17">GetPacketSummary</a>, <a href="#a07b8ee7062fa43085d66306471c646ed">insts</a> and <a href="#a7246dfd483f4ca9b7a755c02dbfb0443">restrictStoreLoadOrder</a>.</p>

</div>
</div>

### HasInstWith() {#aef6718eb21fbc79c73bc13605c6edc57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonShuffler::HasInstWith (<a href="#a335f7f682a937d65f8000be82a17385a">InstPredicate</a> Pred)</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a07b8ee7062fa43085d66306471c646ed">insts</a> and <a href="#ac5472a417eff2e300c9e8f08bdee1297">MCII</a>.</p>

</div>
</div>

### insts() {#a2c100d8373654a0eb40d00132ee87377}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">packet_range llvm::HexagonShuffler::insts (<a href="/web-llvm/docs/api/classes/llvm/smallvector">HexagonPacket</a> &amp; P)</td>
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



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### insts() {#a7102198a6129316dec9430539349ff56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_packet_range llvm::HexagonShuffler::insts (<a href="/web-llvm/docs/api/classes/llvm/smallvector">HexagonPacket</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; P)</td>
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



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### insts() {#a07b8ee7062fa43085d66306471c646ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">packet_range llvm::HexagonShuffler::insts ()</td>
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



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>.</p>


<p>References <a href="#aeba61eef1aab98d3df9c858d69acec86">begin</a>, <a href="#a0c9bb04fa6e283d18e688dc91543f180">end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="#aef6718eb21fbc79c73bc13605c6edc57">HasInstWith</a>, <a href="#a4468bd7691e8ea1515151762d24f4085">permitNonSlot</a>, <a href="#ac7d91a59f353ae38556450341aea270d">reportResourceUsage</a>, <a href="#a45bea692e1c1def80eaae16d764ae97e">restrictNoSlot1Store</a>, <a href="#ae197c24a98a05c2c30b429166a039bb4">restrictPreferSlot3</a>, <a href="#a5ddcba5b6fe2c4762daa50893c3cfe8c">restrictSlot1AOK</a>, <a href="#a7246dfd483f4ca9b7a755c02dbfb0443">restrictStoreLoadOrder</a>, <a href="#a572425344ad3846264384af43858a5e1">shuffle</a> and <a href="#af989f1a0571137412646a2bb7fa4a40f">tryAuction</a>.</p>

</div>
</div>

### insts() {#abc991f81a58d6ca06346806d04244879}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_packet_range llvm::HexagonShuffler::insts ()</td>
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



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>.</p>


<p>References <a href="#a18148551f8767184020ebda8998e33e3">cbegin</a>, <a href="#ab836a8979104a349893a809967bb0d4c">cend</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### isMemReorderDisabled() {#a3b17a068b924e23cc4b879be52707404}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonShuffler::isMemReorderDisabled ()</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>.</p>


<p>References <a href="#aa287ac3a1615e464dacff4aba682d34f">BundleFlags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a2d536ccc8c48cdd4f2faebe911832082">llvm::HexagonMCInstrInfo::memReorderDisabledMask</a>.</p>


<p>Referenced by <a href="#a7246dfd483f4ca9b7a755c02dbfb0443">restrictStoreLoadOrder</a>.</p>

</div>
</div>

### reportError() {#a7d49837058a40c9b850e92eac8f19f6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonShuffler::reportError (<a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Msg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>, definition at line 731 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp">HexagonShuffler.cpp</a>.</p>


<p>References <a href="#af3c5637df6f10e92c0fadfa921b00d01">AppliedRestrictions</a>, <a href="#a1e421183afe3f6a1234a85098b1a4782">CheckFailure</a>, <a href="#a04e7bcc848338f170b3227b216aec616">Context</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777ad5935d1ea3df60ee7ba90b8e23fa6b42">llvm::SourceMgr::DK_Note</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#afb6e75791bd7cfb1b0b26c7a5cc20527">Loc</a> and <a href="#a8ec546f90ddb525b6500986e6ac27239">ReportErrors</a>.</p>


<p>Referenced by <a href="#a50666b23b01ea45d060a07f7e9718b62">check</a>, <a href="#a9b20a8b7424525d8a92b57da076b012f">reportResourceError</a>, <a href="#ab9a1fce0d2529096990ec01dcf4f3ecb">restrictBranchOrder</a>, <a href="#a7246dfd483f4ca9b7a755c02dbfb0443">restrictStoreLoadOrder</a>, <a href="#a572425344ad3846264384af43858a5e1">shuffle</a> and <a href="#ab5464b66f7393d7dbd8c601305cdbc0b">ValidResourceUsage</a>.</p>

</div>
</div>

### reportResourceError() {#a9b20a8b7424525d8a92b57da076b012f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonShuffler::reportResourceError (HexagonPacketSummary <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Summary, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>, definition at line 705 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp">HexagonShuffler.cpp</a>.</p>


<p>References <a href="#a7d49837058a40c9b850e92eac8f19f6e">reportError</a>, <a href="#a8ec546f90ddb525b6500986e6ac27239">ReportErrors</a> and <a href="#ac7d91a59f353ae38556450341aea270d">reportResourceUsage</a>.</p>


<p>Referenced by <a href="#ab9a1fce0d2529096990ec01dcf4f3ecb">restrictBranchOrder</a> and <a href="#ab5464b66f7393d7dbd8c601305cdbc0b">ValidResourceUsage</a>.</p>

</div>
</div>

### reportResourceUsage() {#ac7d91a59f353ae38556450341aea270d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonShuffler::reportResourceUsage (HexagonPacketSummary <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Summary)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>, definition at line 712 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp">HexagonShuffler.cpp</a>.</p>


<p>References <a href="#a04e7bcc848338f170b3227b216aec616">Context</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777ad5935d1ea3df60ee7ba90b8e23fa6b42">llvm::SourceMgr::DK_Note</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a07b8ee7062fa43085d66306471c646ed">insts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a95c527167756007a3fb2ab49ec4b2c6d">llvm::HexagonMCInstrInfo::isImmext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#ac5fca0a3b40921b5bedfa3303b5158f3">llvm::HexagonMCInstrInfo::requiresSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp/#a714f31724f5b3410c7a947afeeb1b0f1">SlotMaskToText</a> and <a href="#ab93a83f6136cca7d527d21196676ccc4">STI</a>.</p>


<p>Referenced by <a href="#a9b20a8b7424525d8a92b57da076b012f">reportResourceError</a>.</p>

</div>
</div>

### reset() {#a3551a59db2db418fd7682f20a3049a19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonShuffler::reset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>, definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp">HexagonShuffler.cpp</a>.</p>


<p>References <a href="#aa287ac3a1615e464dacff4aba682d34f">BundleFlags</a> and <a href="#a1e421183afe3f6a1234a85098b1a4782">CheckFailure</a>.</p>


<p>Referenced by <a href="#a1bea60acdfd80dd427535cbe669f568b">HexagonShuffler</a>.</p>

</div>
</div>

### shuffle() {#a572425344ad3846264384af43858a5e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonShuffler::shuffle ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>, definition at line 652 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp">HexagonShuffler.cpp</a>.</p>


<p>References <a href="#a50666b23b01ea45d060a07f7e9718b62">check</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a5d6d2c647044122707e6ebc1f62f7c67">llvm::HexagonMCInstrInfo::getDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#aee50fcacb786c1fc56168a0c55a4e934">llvm::MCInstrDesc::getOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h/#a8f76c0f5e34856920717e06ebc5f4dc3">HEXAGON_PACKET_SIZE</a>, <a href="#a07b8ee7062fa43085d66306471c646ed">insts</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#ac5472a417eff2e300c9e8f08bdee1297">MCII</a>, <a href="#a7d49837058a40c9b850e92eac8f19f6e">reportError</a>, <a href="#a0ebda228b167d8ea7cc3982c5636cd5b">size</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a37b5dd8a8b82f2818e0f4ea9699d8ae5">llvm::raw_ostream::write_hex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonmcshuffler/#a7acb90dc32e0d7297b6264ab4d25c348">llvm::HexagonMCShuffler::reshuffleTo</a>.</p>

</div>
</div>

### size() {#a0ebda228b167d8ea7cc3982c5636cd5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::HexagonShuffler::size ()</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a7e6dfe0eaf6d1b1720be0390c764cdbd">llvm::HexagonMCShuffle</a> and <a href="#a572425344ad3846264384af43858a5e1">shuffle</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### applySlotRestrictions() {#abcd8bc0e86f749f86f549cafcc1e32ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonShuffler::applySlotRestrictions (HexagonPacketSummary <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Summary, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool DoShuffle)</td>
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



<p>Declaration at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>, definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp">HexagonShuffler.cpp</a>.</p>


<p>References <a href="#a1e421183afe3f6a1234a85098b1a4782">CheckFailure</a>, <a href="#a4468bd7691e8ea1515151762d24f4085">permitNonSlot</a>, <a href="#ab9a1fce0d2529096990ec01dcf4f3ecb">restrictBranchOrder</a>, <a href="#a45bea692e1c1def80eaae16d764ae97e">restrictNoSlot1Store</a>, <a href="#ae197c24a98a05c2c30b429166a039bb4">restrictPreferSlot3</a>, <a href="#a5ddcba5b6fe2c4762daa50893c3cfe8c">restrictSlot1AOK</a> and <a href="#a7246dfd483f4ca9b7a755c02dbfb0443">restrictStoreLoadOrder</a>.</p>


<p>Referenced by <a href="#a50666b23b01ea45d060a07f7e9718b62">check</a>.</p>

</div>
</div>

### GetPacketSummary() {#aafe1b52718a5cd8afd0dbb15e45b5c17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HexagonShuffler::HexagonPacketSummary HexagonShuffler::GetPacketSummary ()</td>
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



<p>Declaration at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>, definition at line 451 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp">HexagonShuffler.cpp</a>.</p>


<p>References <a href="#af3c5637df6f10e92c0fadfa921b00d01">AppliedRestrictions</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aeba61eef1aab98d3df9c858d69acec86">begin</a>, <a href="#a0c9bb04fa6e283d18e688dc91543f180">end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a5d6d2c647044122707e6ebc1f62f7c67">llvm::HexagonMCInstrInfo::getDesc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#ab488aa3ae070d9de98e958be991ea9cc">llvm::HexagonMCInstrInfo::getOtherReservedSlots</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a94f0ca29631596dfaa69418dd1dd6cbd">llvm::HexagonMCInstrInfo::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a268d56105ba2a7d1870fd04a983a2834">llvm::HexagonMCInstrInfo::IsABranchingInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp/#a54d7439b3555f2971b6fe775ae65fc13">isBranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#ad9ae2e328fd6441af81f22bff80c42b0">llvm::HexagonMCInstrInfo::isRestrictNoSlot1Store</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a0d2c795a597e289231bf4d8c1ec7a2ea">llvm::HexagonMCInstrInfo::isRestrictSlot1AOK</a>, <a href="#ac5472a417eff2e300c9e8f08bdee1297">MCII</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a7fb5c7a86107907a7985c93274b02066">llvm::HexagonMCInstrInfo::prefersSlot3</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp/#a714f31724f5b3410c7a947afeeb1b0f1">SlotMaskToText</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp/#a72ca1c35785cb7f8fe65144016c01d9a">slotSingleLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp/#a91bae77add840dc0f0ad940e2127bf06">slotSingleStore</a>, <a href="#ab93a83f6136cca7d527d21196676ccc4">STI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a164b5513f04d48deaa408d128e26331e">llvm::HexagonII::TypeALU64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807ad720fe766d40e8defad0b11e39ed72cf">llvm::HexagonII::TypeCJ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a26ca54cbeaf9cd797a07ae0c316b73b0">llvm::HexagonII::TypeCR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a6dc77d9a24ba7033b48d9b30cf91b0c8">llvm::HexagonII::TypeCVI_GATHER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a157d22dca6752b85d8870804ea09ece5">llvm::HexagonII::TypeCVI_GATHER_DV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807ac181092cd0366eae5b4530e7bd5d7afb">llvm::HexagonII::TypeCVI_GATHER_RST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a92cd53bf13a6c7d16a7bfdc416a72205">llvm::HexagonII::TypeCVI_SCATTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a90785d537b20e6df4ae8399f8dfb7138">llvm::HexagonII::TypeCVI_SCATTER_DV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a6d0cd530ebfee87bc852d82eb008c2ef">llvm::HexagonII::TypeCVI_SCATTER_NEW_RST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807ac534638a746e50962a0d40ae87fbfc87">llvm::HexagonII::TypeCVI_SCATTER_NEW_ST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a059633280af63edbc00542fbeeee7403">llvm::HexagonII::TypeCVI_SCATTER_RST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a52134722cb2ed40bc4769f58689e6337">llvm::HexagonII::TypeCVI_VM_LD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a8c213a24af250baf85b5108103d3ceb1">llvm::HexagonII::TypeCVI_VM_NEW_ST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a4dcd8ba8075ef414eb6cb78c24f6c636">llvm::HexagonII::TypeCVI_VM_ST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a1e1e770d4c913e62d94aae572ee21c43">llvm::HexagonII::TypeCVI_VM_STU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a9da9cbd7a892aa1a3a551704488bd3d1">llvm::HexagonII::TypeCVI_VM_TMP_LD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807afe0d1ba6c98f180ecb8b632b6bfe86a9">llvm::HexagonII::TypeCVI_VM_VP_LDU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a92532ba4e581cd6cf0b961a1bbd54918">llvm::HexagonII::TypeCVI_ZW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a27b04989c8ab303f66b288add9bae068">llvm::HexagonII::TypeDUPLEX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a9ef44633e8b88d5296c9251b1c9dcb88">llvm::HexagonII::TypeJ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807afcfca0ad8004bef54b32fdae3b46c839">llvm::HexagonII::TypeLD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807ac169e59f59e13ba605133af333a9f62f">llvm::HexagonII::TypeNCJ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807ac8da00149d1745b31ed82eae6e24309f">llvm::HexagonII::TypeS_2op</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807adcd6a5ee0158bda659f9cdd5122efeb2">llvm::HexagonII::TypeS_3op</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807af9a1719b939d15e00953948780c673fc">llvm::HexagonII::TypeST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a36cc4da1b01489a8e64e6b6049beff21">llvm::HexagonII::TypeV2LDST</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a7b1720a2612b5ae3e5c7c70c48016a55">llvm::HexagonII::TypeV4LDST</a>.</p>


<p>Referenced by <a href="#a50666b23b01ea45d060a07f7e9718b62">check</a>.</p>

</div>
</div>

### permitNonSlot() {#a4468bd7691e8ea1515151762d24f4085}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonShuffler::permitNonSlot ()</td>
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



<p>Declaration at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>, definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp">HexagonShuffler.cpp</a>.</p>


<p>References <a href="#a07b8ee7062fa43085d66306471c646ed">insts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#ac5fca0a3b40921b5bedfa3303b5158f3">llvm::HexagonMCInstrInfo::requiresSlot</a> and <a href="#ab93a83f6136cca7d527d21196676ccc4">STI</a>.</p>


<p>Referenced by <a href="#abcd8bc0e86f749f86f549cafcc1e32ad">applySlotRestrictions</a>.</p>

</div>
</div>

### restrictBranchOrder() {#ab9a1fce0d2529096990ec01dcf4f3ecb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonShuffler::restrictBranchOrder (HexagonPacketSummary <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Summary)</td>
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



<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>, definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp">HexagonShuffler.cpp</a>.</p>


<p>References <a href="#a7d49837058a40c9b850e92eac8f19f6e">reportError</a>, <a href="#a9b20a8b7424525d8a92b57da076b012f">reportResourceError</a> and <a href="#af989f1a0571137412646a2bb7fa4a40f">tryAuction</a>.</p>


<p>Referenced by <a href="#abcd8bc0e86f749f86f549cafcc1e32ad">applySlotRestrictions</a>.</p>

</div>
</div>

### restrictNoSlot1() {#ad9d908ab3d65e6f5df23ec51e9715cd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::HexagonShuffler::restrictNoSlot1 ()</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>.</p>

</div>
</div>

### restrictNoSlot1Store() {#a45bea692e1c1def80eaae16d764ae97e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonShuffler::restrictNoSlot1Store (HexagonPacketSummary <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Summary)</td>
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



<p>Declaration at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>, definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp">HexagonShuffler.cpp</a>.</p>


<p>References <a href="#af3c5637df6f10e92c0fadfa921b00d01">AppliedRestrictions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a5d6d2c647044122707e6ebc1f62f7c67">llvm::HexagonMCInstrInfo::getDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a40c7fb73978096ed317dd71fb8a84cf4">llvm::MCInst::getLoc</a>, <a href="#a07b8ee7062fa43085d66306471c646ed">insts</a>, <a href="#ac5472a417eff2e300c9e8f08bdee1297">MCII</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp/#a4ad99423c542bf53e50247b5125997c7">Slot1Mask</a>.</p>


<p>Referenced by <a href="#abcd8bc0e86f749f86f549cafcc1e32ad">applySlotRestrictions</a>.</p>

</div>
</div>

### restrictPreferSlot3() {#ae197c24a98a05c2c30b429166a039bb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonShuffler::restrictPreferSlot3 (HexagonPacketSummary <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Summary, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool DoShuffle)</td>
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



<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>, definition at line 584 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp">HexagonShuffler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonresource/#a221461a405e21371879b8093913f931b">llvm::HexagonResource::getUnits</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a07b8ee7062fa43085d66306471c646ed">insts</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonresource/#ad538abdb8f1c5e68c9211f06e5e52c49">llvm::HexagonResource::setUnits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp/#ac16bdf9ae383a9fd66a873824d995783">Slot3Mask</a> and <a href="#af989f1a0571137412646a2bb7fa4a40f">tryAuction</a>.</p>


<p>Referenced by <a href="#abcd8bc0e86f749f86f549cafcc1e32ad">applySlotRestrictions</a>.</p>

</div>
</div>

### restrictSlot1AOK() {#a5ddcba5b6fe2c4762daa50893c3cfe8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonShuffler::restrictSlot1AOK (HexagonPacketSummary <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Summary)</td>
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



<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>, definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp">HexagonShuffler.cpp</a>.</p>


<p>References <a href="#af3c5637df6f10e92c0fadfa921b00d01">AppliedRestrictions</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a40c7fb73978096ed317dd71fb8a84cf4">llvm::MCInst::getLoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a94f0ca29631596dfaa69418dd1dd6cbd">llvm::HexagonMCInstrInfo::getType</a>, <a href="#a07b8ee7062fa43085d66306471c646ed">insts</a>, <a href="#ac5472a417eff2e300c9e8f08bdee1297">MCII</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp/#a4ad99423c542bf53e50247b5125997c7">Slot1Mask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807af587caa3f5623f75f5c70393039bd1d2">llvm::HexagonII::TypeALU32_2op</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a252bb34d9b721a8e353e6dc4deefe5da">llvm::HexagonII::TypeALU32_3op</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a339127cb32340583942dee2cd6883db6">llvm::HexagonII::TypeALU32_ADDI</a>.</p>


<p>Referenced by <a href="#abcd8bc0e86f749f86f549cafcc1e32ad">applySlotRestrictions</a>.</p>

</div>
</div>

### restrictStoreLoadOrder() {#a7246dfd483f4ca9b7a755c02dbfb0443}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonShuffler::restrictStoreLoadOrder (HexagonPacketSummary <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Summary)</td>
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



<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>, definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp">HexagonShuffler.cpp</a>.</p>


<p>References <a href="#aeba61eef1aab98d3df9c858d69acec86">begin</a>, <a href="#a0c9bb04fa6e283d18e688dc91543f180">end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a5d6d2c647044122707e6ebc1f62f7c67">llvm::HexagonMCInstrInfo::getDesc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a07b8ee7062fa43085d66306471c646ed">insts</a>, <a href="#a3b17a068b924e23cc4b879be52707404">isMemReorderDisabled</a>, <a href="#ac5472a417eff2e300c9e8f08bdee1297">MCII</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a>, <a href="#a7d49837058a40c9b850e92eac8f19f6e">reportError</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp/#a5240ad7b79c57753e9728f75795c23f3">Slot0Mask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp/#a4ad99423c542bf53e50247b5125997c7">Slot1Mask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp/#a72ca1c35785cb7f8fe65144016c01d9a">slotSingleLoad</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp/#a91bae77add840dc0f0ad940e2127bf06">slotSingleStore</a>.</p>


<p>Referenced by <a href="#abcd8bc0e86f749f86f549cafcc1e32ad">applySlotRestrictions</a>.</p>

</div>
</div>

### tryAuction() {#af989f1a0571137412646a2bb7fa4a40f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; HexagonShuffler::HexagonPacket &gt; HexagonShuffler::tryAuction (HexagonPacketSummary <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Summary)</td>
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



<p>Declaration at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>, definition at line 627 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp">HexagonShuffler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90c017a4d672e046b7e98f67edf082ec">llvm::format_hex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#acd45ce6506a97a792fa494d67ca1075c">llvm::HexagonMCInstrInfo::getName</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a07b8ee7062fa43085d66306471c646ed">insts</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstr/#a95ee54a78afbd15282b76879937e6bde">llvm::HexagonInstr::lessCore</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#ac5472a417eff2e300c9e8f08bdee1297">MCII</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a076f93c387f454f0db13d4bc7d4e7f9c">llvm::stable_sort</a>.</p>


<p>Referenced by <a href="#ab9a1fce0d2529096990ec01dcf4f3ecb">restrictBranchOrder</a>, <a href="#ae197c24a98a05c2c30b429166a039bb4">restrictPreferSlot3</a> and <a href="#ab5464b66f7393d7dbd8c601305cdbc0b">ValidResourceUsage</a>.</p>

</div>
</div>

### ValidPacketMemoryOps() {#aded3fef7d013b75faecea45e61838494}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonShuffler::ValidPacketMemoryOps (HexagonPacketSummary <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Summary)</td>
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



<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>, definition at line 571 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp">HexagonShuffler.cpp</a>.</p>


<p>Referenced by <a href="#a50666b23b01ea45d060a07f7e9718b62">check</a>.</p>

</div>
</div>

### ValidResourceUsage() {#ab5464b66f7393d7dbd8c601305cdbc0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonShuffler::ValidResourceUsage (HexagonPacketSummary <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Summary)</td>
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



<p>Declaration at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>, definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp">HexagonShuffler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp/#a9b31375abd6555d0b68683aa7238fb8e">checkHVXPipes</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/cviunits/#a5c951a5f55ddf1b7722d73fa715dc5e2">CVIUnits::Lanes</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstr/#ad91d7ffe531f769d90cdafc25fe61238">llvm::HexagonInstr::lessCVI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a7d49837058a40c9b850e92eac8f19f6e">reportError</a>, <a href="#a9b20a8b7424525d8a92b57da076b012f">reportResourceError</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a076f93c387f454f0db13d4bc7d4e7f9c">llvm::stable_sort</a>, <a href="#af989f1a0571137412646a2bb7fa4a40f">tryAuction</a> and <a href="/web-llvm/docs/api/structs/cviunits/#afeb24c666f953bd0a00e3cff4677913d">CVIUnits::Units</a>.</p>


<p>Referenced by <a href="#a50666b23b01ea45d060a07f7e9718b62">check</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### AppliedRestrictions {#af3c5637df6f10e92c0fadfa921b00d01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::pair&lt;SMLoc, std::string&gt; &gt; llvm::HexagonShuffler::AppliedRestrictions</td>
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



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>.</p>


<p>Referenced by <a href="#aafe1b52718a5cd8afd0dbb15e45b5c17">GetPacketSummary</a>, <a href="#a7d49837058a40c9b850e92eac8f19f6e">reportError</a>, <a href="#a45bea692e1c1def80eaae16d764ae97e">restrictNoSlot1Store</a> and <a href="#a5ddcba5b6fe2c4762daa50893c3cfe8c">restrictSlot1AOK</a>.</p>

</div>
</div>

### BundleFlags {#aa287ac3a1615e464dacff4aba682d34f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::HexagonShuffler::BundleFlags</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonmcshuffler/#ad7107b9902252656400f8760c3d657dd">llvm::HexagonMCShuffler::copyTo</a>, <a href="#a1bea60acdfd80dd427535cbe669f568b">HexagonShuffler</a>, <a href="#a3b17a068b924e23cc4b879be52707404">isMemReorderDisabled</a> and <a href="#a3551a59db2db418fd7682f20a3049a19">reset</a>.</p>

</div>
</div>

### CheckFailure {#a1e421183afe3f6a1234a85098b1a4782}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonShuffler::CheckFailure</td>
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



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>.</p>


<p>Referenced by <a href="#abcd8bc0e86f749f86f549cafcc1e32ad">applySlotRestrictions</a>, <a href="#a50666b23b01ea45d060a07f7e9718b62">check</a>, <a href="#a1bea60acdfd80dd427535cbe669f568b">HexagonShuffler</a>, <a href="#a7d49837058a40c9b850e92eac8f19f6e">reportError</a> and <a href="#a3551a59db2db418fd7682f20a3049a19">reset</a>.</p>

</div>
</div>

### Context {#a04e7bcc848338f170b3227b216aec616}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext&amp; llvm::HexagonShuffler::Context</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonmcshuffler/#ab828145ae3ee983f06d2efd4ad7a21cb">llvm::HexagonMCShuffler::HexagonMCShuffler</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmcshuffler/#a09dfd3467401684077720391d3a69ea0">llvm::HexagonMCShuffler::HexagonMCShuffler</a>, <a href="#a1bea60acdfd80dd427535cbe669f568b">HexagonShuffler</a>, <a href="#a7d49837058a40c9b850e92eac8f19f6e">reportError</a> and <a href="#ac7d91a59f353ae38556450341aea270d">reportResourceUsage</a>.</p>

</div>
</div>

### Loc {#afb6e75791bd7cfb1b0b26c7a5cc20527}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc llvm::HexagonShuffler::Loc</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonmcshuffler/#ad7107b9902252656400f8760c3d657dd">llvm::HexagonMCShuffler::copyTo</a> and <a href="#a7d49837058a40c9b850e92eac8f19f6e">reportError</a>.</p>

</div>
</div>

### MCII {#ac5472a417eff2e300c9e8f08bdee1297}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInstrInfo const&amp; llvm::HexagonShuffler::MCII</td>
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



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>.</p>


<p>Referenced by <a href="#abcc1832a977723198b2dd224e9d65efa">append</a>, <a href="#aafe1b52718a5cd8afd0dbb15e45b5c17">GetPacketSummary</a>, <a href="#aef6718eb21fbc79c73bc13605c6edc57">HasInstWith</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmcshuffler/#ab828145ae3ee983f06d2efd4ad7a21cb">llvm::HexagonMCShuffler::HexagonMCShuffler</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmcshuffler/#a09dfd3467401684077720391d3a69ea0">llvm::HexagonMCShuffler::HexagonMCShuffler</a>, <a href="#a1bea60acdfd80dd427535cbe669f568b">HexagonShuffler</a>, <a href="#a45bea692e1c1def80eaae16d764ae97e">restrictNoSlot1Store</a>, <a href="#a5ddcba5b6fe2c4762daa50893c3cfe8c">restrictSlot1AOK</a>, <a href="#a7246dfd483f4ca9b7a755c02dbfb0443">restrictStoreLoadOrder</a>, <a href="#a572425344ad3846264384af43858a5e1">shuffle</a> and <a href="#af989f1a0571137412646a2bb7fa4a40f">tryAuction</a>.</p>

</div>
</div>

### ReportErrors {#a8ec546f90ddb525b6500986e6ac27239}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonShuffler::ReportErrors</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonmcshuffler/#ab828145ae3ee983f06d2efd4ad7a21cb">llvm::HexagonMCShuffler::HexagonMCShuffler</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmcshuffler/#a09dfd3467401684077720391d3a69ea0">llvm::HexagonMCShuffler::HexagonMCShuffler</a>, <a href="#a1bea60acdfd80dd427535cbe669f568b">HexagonShuffler</a>, <a href="#a7d49837058a40c9b850e92eac8f19f6e">reportError</a> and <a href="#a9b20a8b7424525d8a92b57da076b012f">reportResourceError</a>.</p>

</div>
</div>

### STI {#ab93a83f6136cca7d527d21196676ccc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSubtargetInfo const&amp; llvm::HexagonShuffler::STI</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>.</p>


<p>Referenced by <a href="#abcc1832a977723198b2dd224e9d65efa">append</a>, <a href="#aafe1b52718a5cd8afd0dbb15e45b5c17">GetPacketSummary</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmcshuffler/#ab828145ae3ee983f06d2efd4ad7a21cb">llvm::HexagonMCShuffler::HexagonMCShuffler</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmcshuffler/#a09dfd3467401684077720391d3a69ea0">llvm::HexagonMCShuffler::HexagonMCShuffler</a>, <a href="#a1bea60acdfd80dd427535cbe669f568b">HexagonShuffler</a>, <a href="#a4468bd7691e8ea1515151762d24f4085">permitNonSlot</a> and <a href="#ac7d91a59f353ae38556450341aea270d">reportResourceUsage</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Packet {#aa6ec280d18eb2e450a9dc9fc8d2ecd2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HexagonPacket llvm::HexagonShuffler::Packet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp">HexagonShuffler.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-h">HexagonShuffler.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
