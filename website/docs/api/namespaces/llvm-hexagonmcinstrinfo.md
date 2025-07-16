---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/hexagonmcinstrinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `HexagonMCInstrInfo` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::HexagonMCInstrInfo { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hexagonmcinstrinfo/predicateinfo">PredicateInfo</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10e72ca32e8206bcc1a9ec642a797e44">addConstant</a> (MCInst &amp;MI, uint64_t Value, MCContext &amp;Context)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95f7f3602bc5500992d937bd0bb33b3e">addConstExtender</a> (MCContext &amp;Context, MCInstrInfo const &amp;MCII, MCInst &amp;MCB, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/hexagon/packetiterator">Hexagon::PacketIterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a607343a05725b53e0d5bd85a4a44586e">bundleInstructions</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae234776ac492a25df69d7dd394910a20">MCInst::const_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a235887e8341d1afbd5d815a0e9059f23">bundleInstructions</a> (MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a246da06f2e49f678663ae6e21bedffb3">bundleSize</a> (MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab42646dbb9ee42d95ca9d8f05de0daf6">canonicalizePacket</a> (MCInstrInfo const &amp;MCII, MCSubtargetInfo const &amp;STI, MCContext &amp;Context, MCInst &amp;MCB, HexagonMCChecker *Checker, bool AttemptCompatibility=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a268d56105ba2a7d1870fd04a983a2834">IsABranchingInst</a> (MCInstrInfo const &amp;MCII, MCSubtargetInfo const &amp;STI, MCInst const &amp;I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1eda4c3f6c0329af244778af7bd699fa">deriveDuplex</a> (MCContext &amp;Context, unsigned iClass, MCInst const &amp;inst0, MCInst const &amp;inst1)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afef5615be55fa8a93b6a92b8c787aad0">deriveExtender</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;Inst, MCOperand const &amp;MO)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cc69fdbc6fdc191c90bcd0f399dfa3f">deriveSubInst</a> (MCInst const &amp;Inst)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92a5e3cfec25537762fd0102dfeb23af">extenderForIndex</a> (MCInst const &amp;MCB, size_t Index)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac76d914d9d7a5e4e1fb02bd2f1dc02bb">extendIfNeeded</a> (MCContext &amp;Context, MCInstrInfo const &amp;MCII, MCInst &amp;MCB, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1161ecb0b43e7af4846b48a4251f2bcd">getMemAccessSize</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a213afb2c8d115f7e8c72c298e7f54046">getAddrMode</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae89672f809e6b7c989b09f70432e5de5">getDuplexCandidateGroup</a> (MCInst const &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/duplexcandidate">DuplexCandidate</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12bbe632ac24b40e52a6f3dcdef003d5">getDuplexPossibilties</a> (MCInstrInfo const &amp;MCII, MCSubtargetInfo const &amp;STI, MCInst const &amp;MCB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af38036e5099e79ebfc62e46c71deb448">getDuplexRegisterNumbering</a> (MCRegister Reg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72eadd733bd8bd44bd09c2ad0c3d06c0">getExpr</a> (MCExpr const &amp;Expr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned short</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5115f4f0f0213e99431e82c167be0b98">getExtendableOp</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea78a68d4baf2fd4614a3be3a14dd548">getExtendableOperand</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac728d542c58e2a7c3a56cc67b0da9044">getExtentAlignment</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38a8fc225b496e9ed8b4856441e08bba">getExtentBits</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b58bea5a70bbf57fbd2aaf1a7c6f4bb">isExtentSigned</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abae146b364071d25dcd64eebdba8cda0">getMaxValue</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the maximum value of an extendable operand. <a href="#abae146b364071d25dcd64eebdba8cda0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7afe4904cff60da2e4c03067446d3601">getMinValue</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the minimum value of an extendable operand. <a href="#a7afe4904cff60da2e4c03067446d3601">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd45ce6506a97a792fa494d67ca1075c">getName</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned short</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44c5cbb3128220471c20639331ef9356">getNewValueOp</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96d1b18f6b327cd31760f1e6086ab7f8">getNewValueOperand</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned short</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a395ac8e82757af42f2e2c6c78c7e3cdf">getNewValueOp2</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the new value or the newly produced value. <a href="#a395ac8e82757af42f2e2c6c78c7e3cdf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec6caa48fc271621aca9478a1c4a4268">getNewValueOperand2</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94f0ca29631596dfaa69418dd1dd6cbd">getType</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/namespaces/llvm/hexagon">Hexagon</a> ISA class for the insn. <a href="#a94f0ca29631596dfaa69418dd1dd6cbd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2913834d48cd087ac10ba131aae887a4">getCVIResources</a> (MCInstrInfo const &amp;MCII, MCSubtargetInfo const &amp;STI, MCInst const &amp;MCI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the resources used by this instruction. <a href="#a2913834d48cd087ac10ba131aae887a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9211aa0b9d52257601df75d2818dab7c">getUnits</a> (MCInstrInfo const &amp;MCII, MCSubtargetInfo const &amp;STI, MCInst const &amp;MCI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the slots used by the insn. <a href="#a9211aa0b9d52257601df75d2818dab7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab488aa3ae070d9de98e958be991ea9cc">getOtherReservedSlots</a> (MCInstrInfo const &amp;MCII, MCSubtargetInfo const &amp;STI, MCInst const &amp;MCI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the slots this instruction consumes in addition to the slot(s) it can execute out of. <a href="#ab488aa3ae070d9de98e958be991ea9cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80d268275c0dfb3a19a8378750c68bbc">hasDuplex</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad90ed654c772386430919d381f771587">hasExtenderForIndex</a> (MCInst const &amp;MCB, size_t Index)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa49bb12513da4059233afd113f2cd3f0">hasImmExt</a> (MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa5e44937784daa4bb42a20a52ba5da3">hasNewValue</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether the insn produces a value. <a href="#afa5e44937784daa4bb42a20a52ba5da3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7bc69c19bc9f59a5e5c3161d034a71f">hasNewValue2</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether the insn produces a second value. <a href="#aa7bc69c19bc9f59a5e5c3161d034a71f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc1617af84ad9ddfb09c096ad8d8479f">hasTmpDst</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d1d1c4a4b150db06882ccf40ce9bc8c">hasHvxTmp</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa145bda4ca852af7befb41d1bba8f78">iClassOfDuplexPair</a> (unsigned Ga, unsigned Gb)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ca1ea5b42b7c51b90376ec8262db074">minConstant</a> (MCInst const &amp;MCI, size_t Index)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned N, unsigned S&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a174e266390355aa15c8ab81345640235">inRange</a> (MCInst const &amp;MCI, size_t Index)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned N, unsigned S&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a39b1cac0d0f4a1a2a36a74e96c80b368">inSRange</a> (MCInst const &amp;MCI, size_t Index)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned N&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad5851cf4cfe2e127a25a5892d2225157">inRange</a> (MCInst const &amp;MCI, size_t Index)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adda8e3193ca3d31e415a2e4ac6089d50">instruction</a> (MCInst const &amp;MCB, size_t Index)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae08d97008d6d567f2b20287df05d5bd2">isAccumulator</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return where the instruction is an accumulator. <a href="#ae08d97008d6d567f2b20287df05d5bd2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69d33e060c5b0bbfe0f8a2cbeb71f598">isBundle</a> (MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab517da745358f306f00361d8280d020b">isCanon</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cfa6311b09fa20140eec60cccbc2e1d">isCofMax1</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71c43b3f84faa4daee2b2bc80c515c36">isCofRelax1</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd30cb8f783b071d85fc7049b75d157e">isCofRelax2</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52c9eaaaa5bdf33fc16541cff0a6cae4">isCompound</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dc17f36db22a5d62643fdce547bb3ea">isConstExtended</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af674c438c3bb3ad548c387a7b03cab15">isCVINew</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a724a902430ad28036f15612687f46802">isDblRegForSubInst</a> (MCRegister Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26ecf3daf01c489f01b5bf6953827080">isDuplex</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c7a15f9ad4cfeabbdf55ceedffc9821">isDuplexPair</a> (MCInst const &amp;MIa, MCInst const &amp;MIb)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Symmetrical. See if these two instructions are fit for duplex pair. <a href="#a8c7a15f9ad4cfeabbdf55ceedffc9821">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0abe92a949a4e2ed8d9f94ff4488da50">isDuplexPairMatch</a> (unsigned Ga, unsigned Gb)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c525c01df0d371a390190574d22bccc">isExtendable</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af57335bfd112468cfe89cb1bf7f205be">isExtended</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9c1fb4944fcf1d6aadc0f51a69b56e9">isFloat</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether it is a floating-point insn. <a href="#af9c1fb4944fcf1d6aadc0f51a69b56e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f9d7bda03b5f1a77b715e78ee067ee9">isHVX</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95c527167756007a3fb2ab49ec4b2c6d">isImmext</a> (MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4c6bd427b092558b6bf875d8943558d">isInnerLoop</a> (MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ec69ad6054a54a0d7f5e20a303b9bba">isIntReg</a> (MCRegister Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90252d582ff57d9749eb7dc3aac57816">isIntRegForSubInst</a> (MCRegister Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50f29a655ab9a1a5fdf0d476786cbd64">isMemReorderDisabled</a> (MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41c2639831016e233df65de1a6ec6bd3">isNewValue</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether the insn expects newly produced value. <a href="#a41c2639831016e233df65de1a6ec6bd3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cc023a236173fcdb81a1820c1745eb9">isNewValueStore</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the operand is a new-value store insn. <a href="#a5cc023a236173fcdb81a1820c1745eb9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7945fcb6c4dfbf09f0010f52bd73ef24">isOpExtendable</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI, unsigned short)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether the operand is extendable. <a href="#a7945fcb6c4dfbf09f0010f52bd73ef24">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09ddc9ac2f9a0ce92be5565eff4f3869">isOrderedDuplexPair</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MIa, bool ExtendedA, MCInst const &amp;MIb, bool ExtendedB, bool bisReversable, MCSubtargetInfo const &amp;STI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>non-Symmetrical. See if these two instructions are fit for duplex pair. <a href="#a09ddc9ac2f9a0ce92be5565eff4f3869">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15eb1eaa893053e3e1178be7e11f2f59">isOuterLoop</a> (MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97d6571ff5232080bec163cd55377545">isPredicated</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a357d567932941548effd2311bdfcc80b">isPredicateLate</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a136b73813b05ae1deee68a06b4c55f5e">isPredicatedNew</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether the insn is newly predicated. <a href="#a136b73813b05ae1deee68a06b4c55f5e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad81fe27b122fc4b5e48cf9be26d45af8">isPredicatedTrue</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad79ef5bf9d1134049c0f61823fa42be0">isPredReg</a> (MCRegisterInfo const &amp;MRI, MCRegister Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96fa23bebcb8417618bdeb24230bf2d7">isPredRegister</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;Inst, unsigned I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ddcabcb8f48732ec9a2311c1e298d3c">isPrefix</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11e74a6ead98c7237e37c532e411295d">isSolo</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether the insn is solo, i.e., cannot be in a packet. <a href="#a11e74a6ead98c7237e37c532e411295d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4157ec35dc2d6457245b8772cc3c0602">isSoloAX</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether the insn can be packaged only with A and X-type insns. <a href="#a4157ec35dc2d6457245b8772cc3c0602">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d2c795a597e289231bf4d8c1ec7a2ea">isRestrictSlot1AOK</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether the insn can be packaged only with an A-type insn in slot #1. <a href="#a0d2c795a597e289231bf4d8c1ec7a2ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9ae2e328fd6441af81f22bff80c42b0">isRestrictNoSlot1Store</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb3cb6c125bcfdc44c7d3942911616d7">isSubInstruction</a> (MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae72685c5f32e967a3708d52677f1226b">isVector</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae19c50e8978b829dd70b876360c78894">mustExtend</a> (MCExpr const &amp;Expr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ad0644e32da21f9b472af7cdcd6a9d4">mustNotExtend</a> (MCExpr const &amp;Expr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5fca0a3b40921b5bedfa3303b5158f3">requiresSlot</a> (MCSubtargetInfo const &amp;STI, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64c7c69f960b66bee56f0df768811175">LoopNeedsPadding</a> (MCInst const &amp;MCB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbd5d7edb0e9b02e6072243fa310e97b">packetSize</a> (StringRef CPU)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6600c9ef01f540a9d8a3991c2b13d25">packetSizeSlots</a> (MCSubtargetInfo const &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9b5401fd1584e3e51164213c889fd87">slotsConsumed</a> (MCInstrInfo const &amp;MCII, MCSubtargetInfo const &amp;STI, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cb3beb5a3e71a3b94697f7083f2e4be">padEndloop</a> (MCInst &amp;MCI, MCContext &amp;Context)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hexagonmcinstrinfo/predicateinfo">PredicateInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa930f49234de4fd7a469613a1989daf1">predicateInfo</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fb5c7a86107907a7985c93274b02066">prefersSlot3</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd317698bbd34d1cb4e69a49141dab58">replaceDuplex</a> (MCContext &amp;Context, MCInst &amp;MCI, DuplexCandidate Candidate)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa194168067ea8a2c03b1973560ce0904">s27_2_reloc</a> (MCExpr const &amp;Expr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a423fa247fcb4eadd2ba802397a79641b">setInnerLoop</a> (MCInst &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a683b8d4f721f40e4a590b1ab7ac682db">setMemReorderDisabled</a> (MCInst &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedeada7604ef9521d3aec4ec5441811c">setMustExtend</a> (MCExpr const &amp;Expr, bool Val=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3e1f7a4739363ebefca0ac7930c2ccb">setMustNotExtend</a> (MCExpr const &amp;Expr, bool Val=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35d0d6d8b3d10dd3c01582071e1da5da">setS27_2_reloc</a> (MCExpr const &amp;Expr, bool Val=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eae7cb5eae56054e1b89dfbe489a0f1">setOuterLoop</a> (MCInst &amp;MCI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0adeccf7489c053f6a2ee2ecbfe77ea8">subInstWouldBeExtended</a> (MCInst const &amp;potentialDuplex)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d5d784d9e6423800c96623185102095">SubregisterBit</a> (MCRegister Consumer, MCRegister Producer, MCRegister Producer2)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64b03194da15ec0ddafd107ff57dd690">IsVecRegSingle</a> (MCRegister VecReg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56307e938767b5cad81b457fa6b7f3bc">IsVecRegPair</a> (MCRegister VecReg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a150c2ac48d241ceb656546c6c482c03a">IsReverseVecRegPair</a> (MCRegister VecReg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32abefbdb58d94344aae7e32f982b037">IsSingleConsumerRefPairProducer</a> (MCRegister Producer, MCRegister Consumer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; unsigned, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a097363c5ca1d16458abcd7e6a273ade4">GetVecRegPairIndices</a> (MCRegister VecRegPair)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an ordered pair of the constituent register ordinals for each of the elements of <em>VecRegPair</em>. <a href="#a097363c5ca1d16458abcd7e6a273ade4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65fdd614c206400e24b2676a71daac1c">tryCompound</a> (MCInstrInfo const &amp;MCII, MCSubtargetInfo const &amp;STI, MCContext &amp;Context, MCInst &amp;MCI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>tryCompound - Given a bundle check for compound insns when one is found update the contents fo the bundle with the compound insn. <a href="#a65fdd614c206400e24b2676a71daac1c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac9d8fdada61dfe9aca1bdd0ab51df81">innerLoopOffset</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cb9ab22836cb06b3ce84cca5dd1f452">innerLoopMask</a> = 1 &lt;&lt; <a href="#aac9d8fdada61dfe9aca1bdd0ab51df81">innerLoopOffset</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab73790216d7019c4bd442917004a3da5">outerLoopOffset</a> = 1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb33329a6d6debbd79d19dd7927e0b38">outerLoopMask</a> = 1 &lt;&lt; <a href="#ab73790216d7019c4bd442917004a3da5">outerLoopOffset</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66562128eb3b952c96b6432005b8bc47">memReorderDisabledOffset</a> = 2</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d536ccc8c48cdd4f2faebe911832082">memReorderDisabledMask</a> = 1 &lt;&lt; <a href="#a66562128eb3b952c96b6432005b8bc47">memReorderDisabledOffset</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5875e856b0b59a411bf0cea0dcf62f02">splitNoMemOrderOffset</a> = 3</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e5744c4596f2df67d2c874cd0982755">splitNoMemorderMask</a> = 1 &lt;&lt; <a href="#a5875e856b0b59a411bf0cea0dcf62f02">splitNoMemOrderOffset</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a689cd0d0b6cf69804c1877fc9ba3aae4">noShuffleOffset</a> = 4</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91eef8bc25bda8da992af6b279f6663a">noShuffleMask</a> = 1 &lt;&lt; <a href="#a689cd0d0b6cf69804c1877fc9ba3aae4">noShuffleOffset</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa004a7b4f04de8ed59326f54873f7422">bundleInstructionsOffset</a> = 1</td>
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


<div class="doxySectionDef">

## Functions

### addConstant() {#a10e72ca32e8206bcc1a9ec642a797e44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::HexagonMCInstrInfo::addConstant (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, uint64_t Value, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Context)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp/#a20a8e4705041b6319c008c1e981eee45">brtargetDecoder</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hexagondisassembler-cpp-/#a924259105b9cc65caf1525588ae6ca8c">anonymous{HexagonDisassembler.cpp}::signedDecoder</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp/#a42a94b0bc3b45d5b82f8cf8d26dc8449">unsignedImmDecoder</a>.</p>

</div>
</div>

### addConstExtender() {#a95f7f3602bc5500992d937bd0bb33b3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::HexagonMCInstrInfo::addConstExtender (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MCB, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ae86bea5bf6fe3c0a2a9f09f5fdc4a310">llvm::MCOperand::createInst</a>, <a href="#afef5615be55fa8a93b6a92b8c787aad0">deriveExtender</a>, <a href="#a5115f4f0f0213e99431e82c167be0b98">getExtendableOp</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a40c7fb73978096ed317dd71fb8a84cf4">llvm::MCInst::getLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="#a69d33e060c5b0bbfe0f8a2cbeb71f598">isBundle</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a580e2a6e8a248c5a4a814c03186e9241">llvm::MCInst::setLoc</a>.</p>


<p>Referenced by <a href="#ac76d914d9d7a5e4e1fb02bd2f1dc02bb">extendIfNeeded</a>.</p>

</div>
</div>

### bundleInstructions() {#a607343a05725b53e0d5bd85a4a44586e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; Hexagon::PacketIterator &gt; llvm::HexagonMCInstrInfo::bundleInstructions (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a69d33e060c5b0bbfe0f8a2cbeb71f598">isBundle</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonmcelfstreamer/#a706aa084f85cdf448e79ad2d8be30bff">llvm::HexagonMCELFStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmccodeemitter/#afc35abf7d94e2a6c70fe2227fbf2a7ce">llvm::HexagonMCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmccodeemitter/#a8060e25eb66776205e632d4368d1d955">llvm::HexagonMCCodeEmitter::getMachineOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#ab0816f42a174972f6c2b099e9f7b6bc6">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::getSingleInstruction</a>, <a href="#a80d268275c0dfb3a19a8378750c68bbc">hasDuplex</a>, <a href="#aa49bb12513da4059233afd113f2cd3f0">hasImmExt</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstprinter/#aa26f3ffae0b86b636abd35ddeda5d523">llvm::HexagonInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#af22c9938ad82cf97ee6cc8cf00d265cc">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::relaxInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#ad3698352988800e925904a78b2701c04">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::remapInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmcchecker/#ac0b7839d85c05803577cbf09d18c879b">llvm::HexagonMCChecker::reportBranchErrors</a> and <a href="#ab9b5401fd1584e3e51164213c889fd87">slotsConsumed</a>.</p>

</div>
</div>

### bundleInstructions() {#a235887e8341d1afbd5d815a0e9059f23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; MCInst::const_iterator &gt; llvm::HexagonMCInstrInfo::bundleInstructions (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa004a7b4f04de8ed59326f54873f7422">bundleInstructionsOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a> and <a href="#a69d33e060c5b0bbfe0f8a2cbeb71f598">isBundle</a>.</p>

</div>
</div>

### bundleSize() {#a246da06f2e49f678663ae6e21bedffb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::HexagonMCInstrInfo::bundleSize (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="#aa004a7b4f04de8ed59326f54873f7422">bundleInstructionsOffset</a>, <a href="#a69d33e060c5b0bbfe0f8a2cbeb71f598">isBundle</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae534d5d22096b2665d16e5ab600ebbce">llvm::MCInst::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmcinstrinfo-cpp-/#abda7c7a2d206ce064b97412b007ea5af">anonymous{HexagonMCInstrInfo.cpp}::canonicalizePacketImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#a922dc7b28cc9b8895585a602d941b04f">llvm::HexagonAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmcelfstreamer/#a706aa084f85cdf448e79ad2d8be30bff">llvm::HexagonMCELFStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmccodeemitter/#afc35abf7d94e2a6c70fe2227fbf2a7ce">llvm::HexagonMCCodeEmitter::encodeInstruction</a>, <a href="#a92a5e3cfec25537762fd0102dfeb23af">extenderForIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#a11f3e864193e615bb8e8bda2cca24ff3">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::finishLayout</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#aabc01e9899fccd76ffd3a0c7da023fb5">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::fixupNeedsRelaxationAdvanced</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#ab0816f42a174972f6c2b099e9f7b6bc6">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::getSingleInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e62b46a3eb52ccf356ac99f8ebb3c06">llvm::HexagonMCShuffle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59e0da5b8f32f10d8fd69cb090730ecb">llvm::HexagonMCShuffle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7e6dfe0eaf6d1b1720be0390c764cdbd">llvm::HexagonMCShuffle</a>, <a href="#a64c7c69f960b66bee56f0df768811175">LoopNeedsPadding</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonmctargetdesc-cpp-/hexagontargetasmstreamer/#ad17bf01008144e718fa39ffa0ef84733">anonymous{HexagonMCTargetDesc.cpp}::HexagonTargetAsmStreamer::prettyPrintAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstprinter/#aa26f3ffae0b86b636abd35ddeda5d523">llvm::HexagonInstPrinter::printInst</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#af22c9938ad82cf97ee6cc8cf00d265cc">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::relaxInstruction</a>.</p>

</div>
</div>

### canonicalizePacket() {#ab42646dbb9ee42d95ca9d8f05de0daf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::canonicalizePacket (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MCB, <a href="/web-llvm/docs/api/classes/llvm/hexagonmcchecker">HexagonMCChecker</a> * Checker, bool AttemptCompatibility=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#a42d7fe1ef88cc2906006661704af630f">llvm::Hexagon_MC::getArchSubtarget</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#a922dc7b28cc9b8895585a602d941b04f">llvm::HexagonAsmPrinter::emitInstruction</a>.</p>

</div>
</div>

### deriveDuplex() {#a1eda4c3f6c0329af244778af7bd699fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInst * llvm::HexagonMCInstrInfo::deriveDuplex (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Context, unsigned iClass, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; inst0, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; inst1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ae86bea5bf6fe3c0a2a9f09f5fdc4a310">llvm::MCOperand::createInst</a>, <a href="#a0cc69fdbc6fdc191c90bcd0f399dfa3f">deriveSubInst</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>.</p>


<p>Referenced by <a href="#abd317698bbd34d1cb4e69a49141dab58">replaceDuplex</a>.</p>

</div>
</div>

### deriveExtender() {#afef5615be55fa8a93b6a92b8c787aad0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInst llvm::HexagonMCInstrInfo::deriveExtender (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ac9408fbc60922d24b01c1efcbd4ba52b">llvm::MCOperand::getExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a4509c43893edc940979f690c468664c1">llvm::MCOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ae23b2e8269fe15dbe5ebb3394438960c">llvm::MCOperand::isExpr</a>, <a href="#a8c525c01df0d371a390190574d22bccc">isExtendable</a>, <a href="#af57335bfd112468cfe89cb1bf7f205be">isExtended</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a5f639fdcd3fc673fcbdb47f2e88b2b41">llvm::MCOperand::isImm</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>.</p>


<p>Referenced by <a href="#a95f7f3602bc5500992d937bd0bb33b3e">addConstExtender</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#af22c9938ad82cf97ee6cc8cf00d265cc">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::relaxInstruction</a>.</p>

</div>
</div>

### deriveSubInst() {#a0cc69fdbc6fdc191c90bcd0f399dfa3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInst llvm::HexagonMCInstrInfo::deriveSubInst (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 696 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcduplexinfo-cpp">HexagonMCDuplexInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcduplexinfo-cpp/#ae79cf6180b23c65cbc9d3038da706629">addOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ac9408fbc60922d24b01c1efcbd4ba52b">llvm::MCOperand::getExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a40c7fb73978096ed317dd71fb8a84cf4">llvm::MCInst::getLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a94abf618eb8001b802910ab872a7d1d9">llvm::MCOperand::getReg</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="#a6ca1ea5b42b7c51b90376ec8262db074">minConstant</a>.</p>


<p>Referenced by <a href="#a1eda4c3f6c0329af244778af7bd699fa">deriveDuplex</a> and <a href="#a09ddc9ac2f9a0ce92be5565eff4f3869">isOrderedDuplexPair</a>.</p>

</div>
</div>

### extenderForIndex() {#a92a5e3cfec25537762fd0102dfeb23af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInst const  * llvm::HexagonMCInstrInfo::extenderForIndex (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCB, size_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa004a7b4f04de8ed59326f54873f7422">bundleInstructionsOffset</a>, <a href="#a246da06f2e49f678663ae6e21bedffb3">bundleSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ab21fde20666d4c8228c527e0321b2f9b">llvm::MCOperand::getInst</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a> and <a href="#a95c527167756007a3fb2ab49ec4b2c6d">isImmext</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#ab0816f42a174972f6c2b099e9f7b6bc6">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::getSingleInstruction</a> and <a href="#ad90ed654c772386430919d381f771587">hasExtenderForIndex</a>.</p>

</div>
</div>

### extendIfNeeded() {#ac76d914d9d7a5e4e1fb02bd2f1dc02bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::HexagonMCInstrInfo::extendIfNeeded (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MCB, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="#a95f7f3602bc5500992d937bd0bb33b3e">addConstExtender</a> and <a href="#a0dc17f36db22a5d62643fdce547bb3ea">isConstExtended</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a77ac85fa1d774b4d1f5a064e1b8ee8c3">llvm::HexagonLowerToMC</a>.</p>

</div>
</div>

### getAddrMode() {#a213afb2c8d115f7e8c72c298e7f54046}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::HexagonMCInstrInfo::getAddrMode (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64aa5c6e0814e101c20be25f83cc964ce3d">llvm::HexagonII::AddrModeMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a51df7d24dcf6cb9886951e36b2ee83e3">llvm::HexagonII::AddrModePos</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>

</div>
</div>

### getCVIResources() {#a2913834d48cd087ac10ba131aae887a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::HexagonMCInstrInfo::getCVIResources (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the resources used by this instruction.</p>

<p>Declaration at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a03a564c2840cb8d27314596549fc04b8">llvm::MCInstrDesc::getSchedClass</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#af907ecc18c1f4f0bce8a9e2eb449ffb8">llvm::MCSubtargetInfo::getSchedModel</a>, <a href="#a9211aa0b9d52257601df75d2818dab7c">getUnits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad0d833520aa3d3b0fb83d988154991d">llvm::HexagonStages</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#a33e6e84ef828ad8129b514f898fbbf8c">llvm::MCSchedModel::InstrItineraries</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagoncviresource/#a074a6c436e5fb1e2678358e9b5e98f65">llvm::HexagonCVIResource::HexagonCVIResource</a>.</p>

</div>
</div>

### getDesc() {#a5d6d2c647044122707e6ebc1f62f7c67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInstrDesc const  &amp; llvm::HexagonMCInstrInfo::getDesc (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo/#a176ca2c9108a997dcfd8aadf4c0f0fa0">llvm::MCInstrInfo::get</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonmccodeemitter/#a4d0f1b592033820b9a9ab0758a980593">llvm::HexagonMCCodeEmitter::encodeSingleInstruction</a>, <a href="#a213afb2c8d115f7e8c72c298e7f54046">getAddrMode</a>, <a href="#a2913834d48cd087ac10ba131aae887a4">getCVIResources</a>, <a href="#a5115f4f0f0213e99431e82c167be0b98">getExtendableOp</a>, <a href="#ac728d542c58e2a7c3a56cc67b0da9044">getExtentAlignment</a>, <a href="#a38a8fc225b496e9ed8b4856441e08bba">getExtentBits</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmccodeemitter/#a8060e25eb66776205e632d4368d1d955">llvm::HexagonMCCodeEmitter::getMachineOpValue</a>, <a href="#a1161ecb0b43e7af4846b48a4251f2bcd">getMemAccessSize</a>, <a href="#a44c5cbb3128220471c20639331ef9356">getNewValueOp</a>, <a href="#a395ac8e82757af42f2e2c6c78c7e3cdf">getNewValueOp2</a>, <a href="#ab488aa3ae070d9de98e958be991ea9cc">getOtherReservedSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#aafe1b52718a5cd8afd0dbb15e45b5c17">llvm::HexagonShuffler::GetPacketSummary</a>, <a href="#a9211aa0b9d52257601df75d2818dab7c">getUnits</a>, <a href="#a0d1d1c4a4b150db06882ccf40ce9bc8c">hasHvxTmp</a>, <a href="#afa5e44937784daa4bb42a20a52ba5da3">hasNewValue</a>, <a href="#aa7bc69c19bc9f59a5e5c3161d034a71f">hasNewValue2</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoncviresource/#a074a6c436e5fb1e2678358e9b5e98f65">llvm::HexagonCVIResource::HexagonCVIResource</a>, <a href="#a268d56105ba2a7d1870fd04a983a2834">IsABranchingInst</a>, <a href="#ae08d97008d6d567f2b20287df05d5bd2">isAccumulator</a>, <a href="#ab517da745358f306f00361d8280d020b">isCanon</a>, <a href="#a9cfa6311b09fa20140eec60cccbc2e1d">isCofMax1</a>, <a href="#a71c43b3f84faa4daee2b2bc80c515c36">isCofRelax1</a>, <a href="#afd30cb8f783b071d85fc7049b75d157e">isCofRelax2</a>, <a href="#a0dc17f36db22a5d62643fdce547bb3ea">isConstExtended</a>, <a href="#af674c438c3bb3ad548c387a7b03cab15">isCVINew</a>, <a href="#a8c525c01df0d371a390190574d22bccc">isExtendable</a>, <a href="#af57335bfd112468cfe89cb1bf7f205be">isExtended</a>, <a href="#a0b58bea5a70bbf57fbd2aaf1a7c6f4bb">isExtentSigned</a>, <a href="#af9c1fb4944fcf1d6aadc0f51a69b56e9">isFloat</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#a135855aba8ee58019db788042c0d9a54">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::isInstRelaxable</a>, <a href="#a41c2639831016e233df65de1a6ec6bd3">isNewValue</a>, <a href="#a5cc023a236173fcdb81a1820c1745eb9">isNewValueStore</a>, <a href="#a97d6571ff5232080bec163cd55377545">isPredicated</a>, <a href="#a136b73813b05ae1deee68a06b4c55f5e">isPredicatedNew</a>, <a href="#ad81fe27b122fc4b5e48cf9be26d45af8">isPredicatedTrue</a>, <a href="#a357d567932941548effd2311bdfcc80b">isPredicateLate</a>, <a href="#a96fa23bebcb8417618bdeb24230bf2d7">isPredRegister</a>, <a href="#ad9ae2e328fd6441af81f22bff80c42b0">isRestrictNoSlot1Store</a>, <a href="#a0d2c795a597e289231bf4d8c1ec7a2ea">isRestrictSlot1AOK</a>, <a href="#a4157ec35dc2d6457245b8772cc3c0602">isSoloAX</a>, <a href="#ae72685c5f32e967a3708d52677f1226b">isVector</a>, <a href="#aa930f49234de4fd7a469613a1989daf1">predicateInfo</a>, <a href="#a7fb5c7a86107907a7985c93274b02066">prefersSlot3</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#a45bea692e1c1def80eaae16d764ae97e">llvm::HexagonShuffler::restrictNoSlot1Store</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#a7246dfd483f4ca9b7a755c02dbfb0443">llvm::HexagonShuffler::restrictStoreLoadOrder</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#a572425344ad3846264384af43858a5e1">llvm::HexagonShuffler::shuffle</a>.</p>

</div>
</div>

### getDuplexCandidateGroup() {#ae89672f809e6b7c989b09f70432e5de5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::HexagonMCInstrInfo::getDuplexCandidateGroup (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcduplexinfo-cpp">HexagonMCDuplexInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a94abf618eb8001b802910ab872a7d1d9">llvm::MCOperand::getReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a780ec6792abe76b6925d0f2e97c6ef9fa3ff71535a72d86d03242ffd5f2d23e4c">llvm::HexagonII::HSIG_A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a780ec6792abe76b6925d0f2e97c6ef9fa1a7f3c155bdfa994c8913552a6c3f2de">llvm::HexagonII::HSIG_L1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a780ec6792abe76b6925d0f2e97c6ef9fa286b0f049af0ca69b45135a9ce2f455d">llvm::HexagonII::HSIG_L2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a780ec6792abe76b6925d0f2e97c6ef9fa04bc370b14122c63bab19adc7f23432e">llvm::HexagonII::HSIG_None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a780ec6792abe76b6925d0f2e97c6ef9fa6dcfa55970176f718ebc0d5c8ed793f8">llvm::HexagonII::HSIG_S1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a780ec6792abe76b6925d0f2e97c6ef9fa2db44b42ecc6d5f75028163915a228f7">llvm::HexagonII::HSIG_S2</a>, <a href="#a174e266390355aa15c8ab81345640235">inRange</a>, <a href="#a39b1cac0d0f4a1a2a36a74e96c80b368">inSRange</a>, <a href="#a724a902430ad28036f15612687f46802">isDblRegForSubInst</a>, <a href="#a0ec69ad6054a54a0d7f5e20a303b9bba">isIntReg</a>, <a href="#a90252d582ff57d9749eb7dc3aac57816">isIntRegForSubInst</a> and <a href="#a6ca1ea5b42b7c51b90376ec8262db074">minConstant</a>.</p>


<p>Referenced by <a href="#a12bbe632ac24b40e52a6f3dcdef003d5">getDuplexPossibilties</a>, <a href="#a8c7a15f9ad4cfeabbdf55ceedffc9821">isDuplexPair</a> and <a href="#a09ddc9ac2f9a0ce92be5565eff4f3869">isOrderedDuplexPair</a>.</p>

</div>
</div>

### getDuplexPossibilties() {#a12bbe632ac24b40e52a6f3dcdef003d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; DuplexCandidate, 8 &gt; llvm::HexagonMCInstrInfo::getDuplexPossibilties (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 1028 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcduplexinfo-cpp">HexagonMCDuplexInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa004a7b4f04de8ed59326f54873f7422">bundleInstructionsOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ae89672f809e6b7c989b09f70432e5de5">getDuplexCandidateGroup</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ab21fde20666d4c8228c527e0321b2f9b">llvm::MCOperand::getInst</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a3c5c7109f398fdca515509e2284cd8c0">llvm::MCInst::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="#ad90ed654c772386430919d381f771587">hasExtenderForIndex</a>, <a href="#afa145bda4ca852af7befb41d1bba8f78">iClassOfDuplexPair</a>, <a href="#a69d33e060c5b0bbfe0f8a2cbeb71f598">isBundle</a>, <a href="#a50f29a655ab9a1a5fdf0d476786cbd64">isMemReorderDisabled</a>, <a href="#a09ddc9ac2f9a0ce92be5565eff4f3869">isOrderedDuplexPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcduplexinfo-cpp/#afe30dc693eae8207cc7731abcd522493">isStoreInst</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmcinstrinfo-cpp-/#abda7c7a2d206ce064b97412b007ea5af">anonymous{HexagonMCInstrInfo.cpp}::canonicalizePacketImpl</a>.</p>

</div>
</div>

### getDuplexRegisterNumbering() {#af38036e5099e79ebfc62e46c71deb448}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::HexagonMCInstrInfo::getDuplexRegisterNumbering (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h/#a9211f62d8e1e6de999eaa63ec0f6ae02">R2</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h/#a166646d6a4037a236119b6e156051d90">R4</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h/#ace331bebb5bd2780b8dfb7e6e97db7dd">R6</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonmccodeemitter/#a8060e25eb66776205e632d4368d1d955">llvm::HexagonMCCodeEmitter::getMachineOpValue</a>.</p>

</div>
</div>

### getExpr() {#a72eadd733bd8bd44bd09c2ad0c3d06c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCExpr const  &amp; llvm::HexagonMCInstrInfo::getExpr (<a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Expr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-hexagonasmparser-cpp-/hexagonoperand/#ac2aee5b5bd6cf3275da3e9e35895fecc">anonymous{HexagonAsmParser.cpp}::HexagonOperand::CheckImmRange</a>.</p>

</div>
</div>

### getExtendableOp() {#a5115f4f0f0213e99431e82c167be0b98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned short llvm::HexagonMCInstrInfo::getExtendableOp (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a6b9395edba7910b34be8ad16e478b544">llvm::HexagonII::ExtendableOpMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a101c0b668a678cedf02edd310495184c">llvm::HexagonII::ExtendableOpPos</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>


<p>Referenced by <a href="#a95f7f3602bc5500992d937bd0bb33b3e">addConstExtender</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hexagondisassembler-cpp-/#a2e0e4ab18e7fb56c7dbd46fe864243e6">anonymous{HexagonDisassembler.cpp}::fullValue</a>, <a href="#aea78a68d4baf2fd4614a3be3a14dd548">getExtendableOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#a135855aba8ee58019db788042c0d9a54">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::isInstRelaxable</a>, <a href="#a7945fcb6c4dfbf09f0010f52bd73ef24">isOpExtendable</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstprinter/#a6f077221391ce566f9e6601fa571d90a">llvm::HexagonInstPrinter::printBrtarget</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagoninstprinter/#a74044d477e5ae4d2a331370db9bf8576">llvm::HexagonInstPrinter::printOperand</a>.</p>

</div>
</div>

### getExtendableOperand() {#aea78a68d4baf2fd4614a3be3a14dd548}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand const  &amp; llvm::HexagonMCInstrInfo::getExtendableOperand (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5115f4f0f0213e99431e82c167be0b98">getExtendableOp</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ae23b2e8269fe15dbe5ebb3394438960c">llvm::MCOperand::isExpr</a>, <a href="#a8c525c01df0d371a390190574d22bccc">isExtendable</a>, <a href="#af57335bfd112468cfe89cb1bf7f205be">isExtended</a> and <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a5f639fdcd3fc673fcbdb47f2e88b2b41">llvm::MCOperand::isImm</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonmctargetdesc-cpp-/hexagonmcinstranalysis/#abc004e2576e85b8ef606c566bda305e3">anonymous{HexagonMCTargetDesc.cpp}::HexagonMCInstrAnalysis::evaluateBranch</a>, <a href="#a0dc17f36db22a5d62643fdce547bb3ea">isConstExtended</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#af22c9938ad82cf97ee6cc8cf00d265cc">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::relaxInstruction</a>.</p>

</div>
</div>

### getExtentAlignment() {#ac728d542c58e2a7c3a56cc67b0da9044}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::HexagonMCInstrInfo::getExtentAlignment (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64aae2df116267a31e71a1965e367a1afe3">llvm::HexagonII::ExtentAlignMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a2ea507fcd882da176779d25ea0a34712">llvm::HexagonII::ExtentAlignPos</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-hexagondisassembler-cpp-/#a2e0e4ab18e7fb56c7dbd46fe864243e6">anonymous{HexagonDisassembler.cpp}::fullValue</a>.</p>

</div>
</div>

### getExtentBits() {#a38a8fc225b496e9ed8b4856441e08bba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::HexagonMCInstrInfo::getExtentBits (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a9deb65629b93ccf5821688063cf4e7ab">llvm::HexagonII::ExtentBitsMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a8d46cd5f48686ee903c5d568898ec174">llvm::HexagonII::ExtentBitsPos</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp/#a20a8e4705041b6319c008c1e981eee45">brtargetDecoder</a>, <a href="#abae146b364071d25dcd64eebdba8cda0">getMaxValue</a>, <a href="#a7afe4904cff60da2e4c03067446d3601">getMinValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp/#a2a753b4c73b07ef8f90dcada88f6ef4d">s32_0ImmDecoder</a>.</p>

</div>
</div>

### getMaxValue() {#abae146b364071d25dcd64eebdba8cda0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::HexagonMCInstrInfo::getMaxValue (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the maximum value of an extendable operand.</p>

<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a38a8fc225b496e9ed8b4856441e08bba">getExtentBits</a>, <a href="#a8c525c01df0d371a390190574d22bccc">isExtendable</a>, <a href="#af57335bfd112468cfe89cb1bf7f205be">isExtended</a> and <a href="#a0b58bea5a70bbf57fbd2aaf1a7c6f4bb">isExtentSigned</a>.</p>


<p>Referenced by <a href="#a0dc17f36db22a5d62643fdce547bb3ea">isConstExtended</a>.</p>

</div>
</div>

### getMemAccessSize() {#a1161ecb0b43e7af4846b48a4251f2bcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::HexagonMCInstrInfo::getMemAccessSize (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a944d413a83397c066b58e40ae2f105a7">llvm::HexagonII::getMemAccessSizeInBytes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64ab76fe42738fce6ca036d4a56770ea441">llvm::HexagonII::MemAccesSizeMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64ae6ea30822adb1306ae45761254278fc4">llvm::HexagonII::MemAccessSizePos</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>

</div>
</div>

### getMinValue() {#a7afe4904cff60da2e4c03067446d3601}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::HexagonMCInstrInfo::getMinValue (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the minimum value of an extendable operand.</p>

<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 364 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a38a8fc225b496e9ed8b4856441e08bba">getExtentBits</a>, <a href="#a8c525c01df0d371a390190574d22bccc">isExtendable</a>, <a href="#af57335bfd112468cfe89cb1bf7f205be">isExtended</a> and <a href="#a0b58bea5a70bbf57fbd2aaf1a7c6f4bb">isExtentSigned</a>.</p>


<p>Referenced by <a href="#a0dc17f36db22a5d62643fdce547bb3ea">isConstExtended</a>.</p>

</div>
</div>

### getName() {#acd45ce6506a97a792fa494d67ca1075c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::HexagonMCInstrInfo::getName (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo/#abdbb44946a6951b5d90dd5313023156f">llvm::MCInstrInfo::getName</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonmccodeemitter/#a4d0f1b592033820b9a9ab0758a980593">llvm::HexagonMCCodeEmitter::encodeSingleInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#af989f1a0571137412646a2bb7fa4a40f">llvm::HexagonShuffler::tryAuction</a>.</p>

</div>
</div>

### getNewValueOp() {#a44c5cbb3128220471c20639331ef9356}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned short llvm::HexagonMCInstrInfo::getNewValueOp (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64adbbe9d50ce59ef98ed043033f93c21fa">llvm::HexagonII::NewValueOpMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64af169398ad3febf42bfddd6b7c92d5ab0">llvm::HexagonII::NewValueOpPos</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>


<p>Referenced by <a href="#a96d1b18f6b327cd31760f1e6086ab7f8">getNewValueOperand</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#ab0816f42a174972f6c2b099e9f7b6bc6">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::getSingleInstruction</a>.</p>

</div>
</div>

### getNewValueOp2() {#a395ac8e82757af42f2e2c6c78c7e3cdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned short llvm::HexagonMCInstrInfo::getNewValueOp2 (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the new value or the newly produced value.</p>

<p>Declaration at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64af3bac918be586377515378342c664f8e">llvm::HexagonII::NewValueOpMask2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64ae5281f6100623538beeb4cc095fd70ad">llvm::HexagonII::NewValueOpPos2</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>


<p>Referenced by <a href="#aec6caa48fc271621aca9478a1c4a4268">getNewValueOperand2</a>.</p>

</div>
</div>

### getNewValueOperand() {#a96d1b18f6b327cd31760f1e6086ab7f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand const  &amp; llvm::HexagonMCInstrInfo::getNewValueOperand (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#a44c5cbb3128220471c20639331ef9356">getNewValueOp</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="#afa5e44937784daa4bb42a20a52ba5da3">hasNewValue</a>, <a href="#acc1617af84ad9ddfb09c096ad8d8479f">hasTmpDst</a>, <a href="#a41c2639831016e233df65de1a6ec6bd3">isNewValue</a> and <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a7a8c7eea0aa4890f25a4b83e1f0a0b6f">llvm::MCOperand::isReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonmccodeemitter/#a8060e25eb66776205e632d4368d1d955">llvm::HexagonMCCodeEmitter::getMachineOpValue</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#ab0816f42a174972f6c2b099e9f7b6bc6">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::getSingleInstruction</a>.</p>

</div>
</div>

### getNewValueOperand2() {#aec6caa48fc271621aca9478a1c4a4268}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand const  &amp; llvm::HexagonMCInstrInfo::getNewValueOperand2 (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 411 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a395ac8e82757af42f2e2c6c78c7e3cdf">getNewValueOp2</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="#aa7bc69c19bc9f59a5e5c3161d034a71f">hasNewValue2</a>, <a href="#a41c2639831016e233df65de1a6ec6bd3">isNewValue</a> and <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a7a8c7eea0aa4890f25a4b83e1f0a0b6f">llvm::MCOperand::isReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonmccodeemitter/#a8060e25eb66776205e632d4368d1d955">llvm::HexagonMCCodeEmitter::getMachineOpValue</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#ab0816f42a174972f6c2b099e9f7b6bc6">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::getSingleInstruction</a>.</p>

</div>
</div>

### getOtherReservedSlots() {#ab488aa3ae070d9de98e958be991ea9cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::HexagonMCInstrInfo::getOtherReservedSlots (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the slots this instruction consumes in addition to the slot(s) it can execute out of.</p>

<p>Declaration at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 461 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a03a564c2840cb8d27314596549fc04b8">llvm::MCInstrDesc::getSchedClass</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#af907ecc18c1f4f0bce8a9e2eb449ffb8">llvm::MCSubtargetInfo::getSchedModel</a>, <a href="#a9211aa0b9d52257601df75d2818dab7c">getUnits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a506ed2df5b4cd3665278c61b018dd823">llvm::HexagonGetLastSlot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad0d833520aa3d3b0fb83d988154991d">llvm::HexagonStages</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a> and <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#a33e6e84ef828ad8129b514f898fbbf8c">llvm::MCSchedModel::InstrItineraries</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#aafe1b52718a5cd8afd0dbb15e45b5c17">llvm::HexagonShuffler::GetPacketSummary</a>.</p>

</div>
</div>

### getType() {#a94f0ca29631596dfaa69418dd1dd6cbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::HexagonMCInstrInfo::getType (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <a href="/web-llvm/docs/api/namespaces/llvm/hexagon">Hexagon</a> ISA class for the insn.</p>

<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo/#a176ca2c9108a997dcfd8aadf4c0f0fa0">llvm::MCInstrInfo::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a4a0c98b00dab2ae16b8b6f445f1ce2d1">llvm::HexagonII::TypeMask</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a0ff1433f59f41560f99440a22d973fb5">llvm::HexagonII::TypePos</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#aafe1b52718a5cd8afd0dbb15e45b5c17">llvm::HexagonShuffler::GetPacketSummary</a>, <a href="#a0dc17f36db22a5d62643fdce547bb3ea">isConstExtended</a>, <a href="#a26ecf3daf01c489f01b5bf6953827080">isDuplex</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#a135855aba8ee58019db788042c0d9a54">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::isInstRelaxable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcchecker-cpp/#aec42fbce291c77743d74805b379a0558">isNeitherAnorX</a>, <a href="#a2ddcabcb8f48732ec9a2311c1e298d3c">isPrefix</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp/#a060f0d1989564164d0cf3fad101666f4">lookForCompound</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#a5ddcba5b6fe2c4762daa50893c3cfe8c">llvm::HexagonShuffler::restrictSlot1AOK</a>.</p>

</div>
</div>

### getUnits() {#a9211aa0b9d52257601df75d2818dab7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::HexagonMCInstrInfo::getUnits (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the slots used by the insn.</p>


<p>Return the slots this instruction can execute out of.</p>


<p>Declaration at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a03a564c2840cb8d27314596549fc04b8">llvm::MCInstrDesc::getSchedClass</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#af907ecc18c1f4f0bce8a9e2eb449ffb8">llvm::MCSubtargetInfo::getSchedModel</a>, <a href="#a9211aa0b9d52257601df75d2818dab7c">getUnits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad0d833520aa3d3b0fb83d988154991d">llvm::HexagonStages</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a> and <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#a33e6e84ef828ad8129b514f898fbbf8c">llvm::MCSchedModel::InstrItineraries</a>.</p>


<p>Referenced by <a href="#a2913834d48cd087ac10ba131aae887a4">getCVIResources</a>, <a href="#ab488aa3ae070d9de98e958be991ea9cc">getOtherReservedSlots</a> and <a href="#a9211aa0b9d52257601df75d2818dab7c">getUnits</a>.</p>

</div>
</div>

### GetVecRegPairIndices() {#a097363c5ca1d16458abcd7e6a273ade4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; unsigned, unsigned &gt; llvm::HexagonMCInstrInfo::GetVecRegPairIndices (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> VecRegPair)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns an ordered pair of the constituent register ordinals for each of the elements of <em>VecRegPair</em>.</p>


<p>For example, Hexagon::W0 ("v0:1") returns { 0, 1 } and Hexagon::W1 ("v3:2") returns { 3, 2 }.</p>


<p>Declaration at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 708 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a150c2ac48d241ceb656546c6c482c03a">IsReverseVecRegPair</a> and <a href="#a56307e938767b5cad81b457fa6b7f3bc">IsVecRegPair</a>.</p>

</div>
</div>

### hasDuplex() {#a80d268275c0dfb3a19a8378750c68bbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::hasDuplex (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 484 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="#a607343a05725b53e0d5bd85a4a44586e">bundleInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a69d33e060c5b0bbfe0f8a2cbeb71f598">isBundle</a> and <a href="#a26ecf3daf01c489f01b5bf6953827080">isDuplex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a59e0da5b8f32f10d8fd69cb090730ecb">llvm::HexagonMCShuffle</a>.</p>

</div>
</div>

### hasExtenderForIndex() {#ad90ed654c772386430919d381f771587}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::hasExtenderForIndex (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCB, size_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 496 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>Reference <a href="#a92a5e3cfec25537762fd0102dfeb23af">extenderForIndex</a>.</p>


<p>Referenced by <a href="#a12bbe632ac24b40e52a6f3dcdef003d5">getDuplexPossibilties</a>.</p>

</div>
</div>

### hasHvxTmp() {#a0d1d1c4a4b150db06882ccf40ce9bc8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::hasHvxTmp (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 969 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a0eb45162b48fab44538b4bece910a465">llvm::HexagonII::HasHvxTmpMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a43aad254a10b63b7cc85af9a64e7642b">llvm::HexagonII::HasHvxTmpPos</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>

</div>
</div>

### hasImmExt() {#aa49bb12513da4059233afd113f2cd3f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::hasImmExt (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="#a607343a05725b53e0d5bd85a4a44586e">bundleInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a69d33e060c5b0bbfe0f8a2cbeb71f598">isBundle</a> and <a href="#a95c527167756007a3fb2ab49ec4b2c6d">isImmext</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a59e0da5b8f32f10d8fd69cb090730ecb">llvm::HexagonMCShuffle</a>.</p>

</div>
</div>

### hasNewValue() {#afa5e44937784daa4bb42a20a52ba5da3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::hasNewValue (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether the insn produces a value.</p>

<p>Declaration at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 513 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a3a35ec9d813a940e981b399f577dd5a7">llvm::HexagonII::hasNewValueMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a6d594909f1a91264d60491128f516b5a">llvm::HexagonII::hasNewValuePos</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonmccodeemitter/#a8060e25eb66776205e632d4368d1d955">llvm::HexagonMCCodeEmitter::getMachineOpValue</a>, <a href="#a96d1b18f6b327cd31760f1e6086ab7f8">getNewValueOperand</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#ab0816f42a174972f6c2b099e9f7b6bc6">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::getSingleInstruction</a>.</p>

</div>
</div>

### hasNewValue2() {#aa7bc69c19bc9f59a5e5c3161d034a71f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::hasNewValue2 (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether the insn produces a second value.</p>

<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 520 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a4e7462ce9c581d07ccbd692d3b76faec">llvm::HexagonII::hasNewValueMask2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64ae225b150275b735b889aed3d03dd1cbf">llvm::HexagonII::hasNewValuePos2</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonmccodeemitter/#a8060e25eb66776205e632d4368d1d955">llvm::HexagonMCCodeEmitter::getMachineOpValue</a>, <a href="#aec6caa48fc271621aca9478a1c4a4268">getNewValueOperand2</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#ab0816f42a174972f6c2b099e9f7b6bc6">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::getSingleInstruction</a>.</p>

</div>
</div>

### hasTmpDst() {#acc1617af84ad9ddfb09c096ad8d8479f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::hasTmpDst (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 954 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>.</p>


<p>Referenced by <a href="#a96d1b18f6b327cd31760f1e6086ab7f8">getNewValueOperand</a>.</p>

</div>
</div>

### iClassOfDuplexPair() {#afa145bda4ca852af7befb41d1bba8f78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::HexagonMCInstrInfo::iClassOfDuplexPair (unsigned Ga, unsigned Gb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcduplexinfo-cpp">HexagonMCDuplexInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a780ec6792abe76b6925d0f2e97c6ef9fa3ff71535a72d86d03242ffd5f2d23e4c">llvm::HexagonII::HSIG_A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a780ec6792abe76b6925d0f2e97c6ef9fab74fdc47ba8aefc8167cc04d7bd05908">llvm::HexagonII::HSIG_Compound</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a780ec6792abe76b6925d0f2e97c6ef9fa1a7f3c155bdfa994c8913552a6c3f2de">llvm::HexagonII::HSIG_L1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a780ec6792abe76b6925d0f2e97c6ef9fa286b0f049af0ca69b45135a9ce2f455d">llvm::HexagonII::HSIG_L2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a780ec6792abe76b6925d0f2e97c6ef9fa04bc370b14122c63bab19adc7f23432e">llvm::HexagonII::HSIG_None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a780ec6792abe76b6925d0f2e97c6ef9fa6dcfa55970176f718ebc0d5c8ed793f8">llvm::HexagonII::HSIG_S1</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a780ec6792abe76b6925d0f2e97c6ef9fa2db44b42ecc6d5f75028163915a228f7">llvm::HexagonII::HSIG_S2</a>.</p>


<p>Referenced by <a href="#a12bbe632ac24b40e52a6f3dcdef003d5">getDuplexPossibilties</a>.</p>

</div>
</div>

### inRange() {#a174e266390355aa15c8ab81345640235}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned N, unsigned S&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::inRange (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI, size_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#af0d6fc340d84e22e165e7d069b74f3c5">llvm::isShiftedUInt</a> and <a href="#a6ca1ea5b42b7c51b90376ec8262db074">minConstant</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp/#a1c0379352edde54a80bacc7540aee0c7">getCompoundCandidateGroup</a> and <a href="#ae89672f809e6b7c989b09f70432e5de5">getDuplexCandidateGroup</a>.</p>

</div>
</div>

### inRange() {#ad5851cf4cfe2e127a25a5892d2225157}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::inRange (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI, size_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="#a6ca1ea5b42b7c51b90376ec8262db074">minConstant</a>.</p>

</div>
</div>

### inSRange() {#a39b1cac0d0f4a1a2a36a74e96c80b368}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned N, unsigned S&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::inSRange (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI, size_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abcb678e42ef8094f2b744592ec378feb">llvm::isShiftedInt</a> and <a href="#a6ca1ea5b42b7c51b90376ec8262db074">minConstant</a>.</p>


<p>Referenced by <a href="#ae89672f809e6b7c989b09f70432e5de5">getDuplexCandidateGroup</a>.</p>

</div>
</div>

### instruction() {#adda8e3193ca3d31e415a2e4ac6089d50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInst const  &amp; llvm::HexagonMCInstrInfo::instruction (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCB, size_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 526 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa004a7b4f04de8ed59326f54873f7422">bundleInstructionsOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ab21fde20666d4c8228c527e0321b2f9b">llvm::MCOperand::getInst</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h/#ac4997a2808cebb7b14e08a5429558dc1">HEXAGON_PRESHUFFLE_PACKET_SIZE</a> and <a href="#a69d33e060c5b0bbfe0f8a2cbeb71f598">isBundle</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#aabc01e9899fccd76ffd3a0c7da023fb5">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::fixupNeedsRelaxationAdvanced</a>.</p>

</div>
</div>

### IsABranchingInst() {#a268d56105ba2a7d1870fd04a983a2834}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::IsABranchingInst (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 1056 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a69d33e060c5b0bbfe0f8a2cbeb71f598">isBundle</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#aafe1b52718a5cd8afd0dbb15e45b5c17">llvm::HexagonShuffler::GetPacketSummary</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonmcchecker/#ac0b7839d85c05803577cbf09d18c879b">llvm::HexagonMCChecker::reportBranchErrors</a>.</p>

</div>
</div>

### isAccumulator() {#ae08d97008d6d567f2b20287df05d5bd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isAccumulator (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return where the instruction is an accumulator.</p>

<p>Declaration at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 533 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64af49ef77639d071e9ead713400afcdf5f">llvm::HexagonII::AccumulatorMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64ae7cf129a7e0d3f16351f8171afa92f44">llvm::HexagonII::AccumulatorPos</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>

</div>
</div>

### isBundle() {#a69d33e060c5b0bbfe0f8a2cbeb71f598}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isBundle (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 539 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a5f639fdcd3fc673fcbdb47f2e88b2b41">llvm::MCOperand::isImm</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae534d5d22096b2665d16e5ab600ebbce">llvm::MCInst::size</a>.</p>


<p>Referenced by <a href="#a95f7f3602bc5500992d937bd0bb33b3e">addConstExtender</a>, <a href="#a235887e8341d1afbd5d815a0e9059f23">bundleInstructions</a>, <a href="#a607343a05725b53e0d5bd85a4a44586e">bundleInstructions</a>, <a href="#a246da06f2e49f678663ae6e21bedffb3">bundleSize</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmccodeemitter/#afc35abf7d94e2a6c70fe2227fbf2a7ce">llvm::HexagonMCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmccodeemitter/#a4d0f1b592033820b9a9ab0758a980593">llvm::HexagonMCCodeEmitter::encodeSingleInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#aabc01e9899fccd76ffd3a0c7da023fb5">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::fixupNeedsRelaxationAdvanced</a>, <a href="#a12bbe632ac24b40e52a6f3dcdef003d5">getDuplexPossibilties</a>, <a href="#a80d268275c0dfb3a19a8378750c68bbc">hasDuplex</a>, <a href="#aa49bb12513da4059233afd113f2cd3f0">hasImmExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e62b46a3eb52ccf356ac99f8ebb3c06">llvm::HexagonMCShuffle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59e0da5b8f32f10d8fd69cb090730ecb">llvm::HexagonMCShuffle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7e6dfe0eaf6d1b1720be0390c764cdbd">llvm::HexagonMCShuffle</a>, <a href="#adda8e3193ca3d31e415a2e4ac6089d50">instruction</a>, <a href="#a268d56105ba2a7d1870fd04a983a2834">IsABranchingInst</a>, <a href="#aa4c6bd427b092558b6bf875d8943558d">isInnerLoop</a>, <a href="#a50f29a655ab9a1a5fdf0d476786cbd64">isMemReorderDisabled</a>, <a href="#a15eb1eaa893053e3e1178be7e11f2f59">isOuterLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp/#a060f0d1989564164d0cf3fad101666f4">lookForCompound</a>, <a href="#a2cb3beb5a3e71a3b94697f7083f2e4be">padEndloop</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonmctargetdesc-cpp-/hexagontargetasmstreamer/#ad17bf01008144e718fa39ffa0ef84733">anonymous{HexagonMCTargetDesc.cpp}::HexagonTargetAsmStreamer::prettyPrintAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstprinter/#aa26f3ffae0b86b636abd35ddeda5d523">llvm::HexagonInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#af22c9938ad82cf97ee6cc8cf00d265cc">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::relaxInstruction</a>, <a href="#abd317698bbd34d1cb4e69a49141dab58">replaceDuplex</a>, <a href="#a423fa247fcb4eadd2ba802397a79641b">setInnerLoop</a>, <a href="#a683b8d4f721f40e4a590b1ab7ac682db">setMemReorderDisabled</a>, <a href="#a0eae7cb5eae56054e1b89dfbe489a0f1">setOuterLoop</a> and <a href="#a65fdd614c206400e24b2676a71daac1c">tryCompound</a>.</p>

</div>
</div>

### isCanon() {#ab517da745358f306f00361d8280d020b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isCanon (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 587 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a>, <a href="#a2ddcabcb8f48732ec9a2311c1e298d3c">isPrefix</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#afa2cee6d743bcfb8946e6dcc4a6cc443">llvm::MCInstrDesc::isPseudo</a>.</p>

</div>
</div>

### isCofMax1() {#a9cfa6311b09fa20140eec60cccbc2e1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isCofMax1 (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 592 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a3758cfe79abace18a8a07fbbc12b0088">llvm::HexagonII::CofMax1Mask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a78cd7fc34d61a10af0ea79be19247cb1">llvm::HexagonII::CofMax1Pos</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>

</div>
</div>

### isCofRelax1() {#a71c43b3f84faa4daee2b2bc80c515c36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isCofRelax1 (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 597 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a01a510e580d21ec40bdc89e4500e4ad3">llvm::HexagonII::CofRelax1Mask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a0b0cb51609ef83e328f9b0d3dafcebf0">llvm::HexagonII::CofRelax1Pos</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>

</div>
</div>

### isCofRelax2() {#afd30cb8f783b071d85fc7049b75d157e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isCofRelax2 (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 603 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64abd9c087cc07c23a4020b33543e3180ce">llvm::HexagonII::CofRelax2Mask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a50496b47a1a02765483b8ae00f815b09">llvm::HexagonII::CofRelax2Pos</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>

</div>
</div>

### isCompound() {#a52c9eaaaa5bdf33fc16541cff0a6cae4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isCompound (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 609 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807ad720fe766d40e8defad0b11e39ed72cf">llvm::HexagonII::TypeCJ</a>.</p>

</div>
</div>

### isConstExtended() {#a0dc17f36db22a5d62643fdce547bb3ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isConstExtended (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 545 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ac9408fbc60922d24b01c1efcbd4ba52b">llvm::MCOperand::getExpr</a>, <a href="#aea78a68d4baf2fd4614a3be3a14dd548">getExtendableOperand</a>, <a href="#abae146b364071d25dcd64eebdba8cda0">getMaxValue</a>, <a href="#a7afe4904cff60da2e4c03067446d3601">getMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="#a94f0ca29631596dfaa69418dd1dd6cbd">getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp/#a54d7439b3555f2971b6fe775ae65fc13">isBranch</a>, <a href="#a8c525c01df0d371a390190574d22bccc">isExtendable</a>, <a href="#af57335bfd112468cfe89cb1bf7f205be">isExtended</a>, <a href="#a0b58bea5a70bbf57fbd2aaf1a7c6f4bb">isExtentSigned</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a5f639fdcd3fc673fcbdb47f2e88b2b41">llvm::MCOperand::isImm</a>, <a href="#ae19c50e8978b829dd70b876360c78894">mustExtend</a>, <a href="#a5ad0644e32da21f9b472af7cdcd6a9d4">mustNotExtend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807ad720fe766d40e8defad0b11e39ed72cf">llvm::HexagonII::TypeCJ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a26ca54cbeaf9cd797a07ae0c316b73b0">llvm::HexagonII::TypeCR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a9ef44633e8b88d5296c9251b1c9dcb88">llvm::HexagonII::TypeJ</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807ac169e59f59e13ba605133af333a9f62f">llvm::HexagonII::TypeNCJ</a>.</p>


<p>Referenced by <a href="#ac76d914d9d7a5e4e1fb02bd2f1dc02bb">extendIfNeeded</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstprinter/#a6f077221391ce566f9e6601fa571d90a">llvm::HexagonInstPrinter::printBrtarget</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagoninstprinter/#a74044d477e5ae4d2a331370db9bf8576">llvm::HexagonInstPrinter::printOperand</a>.</p>

</div>
</div>

### isCVINew() {#af674c438c3bb3ad548c387a7b03cab15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isCVINew (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 614 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a00576b6d7ede5a1ae90e48a79090bc74">llvm::HexagonII::CVINewMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a338cd5ac538610c3872a291f3fabd719">llvm::HexagonII::CVINewPos</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>

</div>
</div>

### isDblRegForSubInst() {#a724a902430ad28036f15612687f46802}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isDblRegForSubInst (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 619 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="#ae89672f809e6b7c989b09f70432e5de5">getDuplexCandidateGroup</a>.</p>

</div>
</div>

### isDuplex() {#a26ecf3daf01c489f01b5bf6953827080}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isDuplex (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 624 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="#a94f0ca29631596dfaa69418dd1dd6cbd">getType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a27b04989c8ab303f66b288add9bae068">llvm::HexagonII::TypeDUPLEX</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#ab0816f42a174972f6c2b099e9f7b6bc6">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::getSingleInstruction</a>, <a href="#a80d268275c0dfb3a19a8378750c68bbc">hasDuplex</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagon/packetiterator/#aa2a0dda875c44641d039611c617f2a81">llvm::Hexagon::PacketIterator::operator++</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstprinter/#aa26f3ffae0b86b636abd35ddeda5d523">llvm::HexagonInstPrinter::printInst</a> and <a href="#ab9b5401fd1584e3e51164213c889fd87">slotsConsumed</a>.</p>

</div>
</div>

### isDuplexPair() {#a8c7a15f9ad4cfeabbdf55ceedffc9821}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isDuplexPair (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MIa, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MIb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Symmetrical. See if these two instructions are fit for duplex pair.</p>

<p>Declaration at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 651 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcduplexinfo-cpp">HexagonMCDuplexInfo.cpp</a>.</p>


<p>References <a href="#ae89672f809e6b7c989b09f70432e5de5">getDuplexCandidateGroup</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoninstrinfo-cpp/#af04c6a150c026e48309d20f347dde315">isDuplexPairMatch</a>.</p>

</div>
</div>

### isDuplexPairMatch() {#a0abe92a949a4e2ed8d9f94ff4488da50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isDuplexPairMatch (unsigned Ga, unsigned Gb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcduplexinfo-cpp">HexagonMCDuplexInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a780ec6792abe76b6925d0f2e97c6ef9fa3ff71535a72d86d03242ffd5f2d23e4c">llvm::HexagonII::HSIG_A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a780ec6792abe76b6925d0f2e97c6ef9fab74fdc47ba8aefc8167cc04d7bd05908">llvm::HexagonII::HSIG_Compound</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a780ec6792abe76b6925d0f2e97c6ef9fa1a7f3c155bdfa994c8913552a6c3f2de">llvm::HexagonII::HSIG_L1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a780ec6792abe76b6925d0f2e97c6ef9fa286b0f049af0ca69b45135a9ce2f455d">llvm::HexagonII::HSIG_L2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a780ec6792abe76b6925d0f2e97c6ef9fa04bc370b14122c63bab19adc7f23432e">llvm::HexagonII::HSIG_None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a780ec6792abe76b6925d0f2e97c6ef9fa6dcfa55970176f718ebc0d5c8ed793f8">llvm::HexagonII::HSIG_S1</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a780ec6792abe76b6925d0f2e97c6ef9fa2db44b42ecc6d5f75028163915a228f7">llvm::HexagonII::HSIG_S2</a>.</p>

</div>
</div>

### isExtendable() {#a8c525c01df0d371a390190574d22bccc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isExtendable (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 628 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64abd948b9bbf032d9ad8bb5aa6cfbd7654">llvm::HexagonII::ExtendableMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a869131c5aceb68b65a95f68e15284259">llvm::HexagonII::ExtendablePos</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>


<p>Referenced by <a href="#afef5615be55fa8a93b6a92b8c787aad0">deriveExtender</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonmctargetdesc-cpp-/hexagonmcinstranalysis/#abc004e2576e85b8ef606c566bda305e3">anonymous{HexagonMCTargetDesc.cpp}::HexagonMCInstrAnalysis::evaluateBranch</a>, <a href="#aea78a68d4baf2fd4614a3be3a14dd548">getExtendableOperand</a>, <a href="#abae146b364071d25dcd64eebdba8cda0">getMaxValue</a>, <a href="#a7afe4904cff60da2e4c03067446d3601">getMinValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#ab0816f42a174972f6c2b099e9f7b6bc6">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::getSingleInstruction</a>, <a href="#a0dc17f36db22a5d62643fdce547bb3ea">isConstExtended</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#a135855aba8ee58019db788042c0d9a54">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::isInstRelaxable</a>.</p>

</div>
</div>

### isExtended() {#af57335bfd112468cfe89cb1bf7f205be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isExtended (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 634 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a42a927c0bed34510cc1f06a3e43dd3db">llvm::HexagonII::ExtendedMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a91d822d71b33e22815e9ca81b440d28a">llvm::HexagonII::ExtendedPos</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>


<p>Referenced by <a href="#afef5615be55fa8a93b6a92b8c787aad0">deriveExtender</a>, <a href="#aea78a68d4baf2fd4614a3be3a14dd548">getExtendableOperand</a>, <a href="#abae146b364071d25dcd64eebdba8cda0">getMaxValue</a>, <a href="#a7afe4904cff60da2e4c03067446d3601">getMinValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#ab0816f42a174972f6c2b099e9f7b6bc6">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::getSingleInstruction</a> and <a href="#a0dc17f36db22a5d62643fdce547bb3ea">isConstExtended</a>.</p>

</div>
</div>

### isExtentSigned() {#a0b58bea5a70bbf57fbd2aaf1a7c6f4bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isExtentSigned (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a12f419162fc088d4ed007e36fc927c17">llvm::HexagonII::ExtentSignedMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64ab65fb8a83dcd05f093c8426951d4609a">llvm::HexagonII::ExtentSignedPos</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>


<p>Referenced by <a href="#abae146b364071d25dcd64eebdba8cda0">getMaxValue</a>, <a href="#a7afe4904cff60da2e4c03067446d3601">getMinValue</a> and <a href="#a0dc17f36db22a5d62643fdce547bb3ea">isConstExtended</a>.</p>

</div>
</div>

### isFloat() {#af9c1fb4944fcf1d6aadc0f51a69b56e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isFloat (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether it is a floating-point insn.</p>

<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 640 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a7c8e5478c75933627463537456b0c327">llvm::HexagonII::FPMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a79dc0d60d9c2f12e0275f59b4073c04c">llvm::HexagonII::FPPos</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcchecker-cpp/#aec42fbce291c77743d74805b379a0558">isNeitherAnorX</a>.</p>

</div>
</div>

### isHVX() {#a4f9d7bda03b5f1a77b715e78ee067ee9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isHVX (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 645 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a99270c0ea92a6627d8485da741e7dd9a">llvm::HexagonII::TypeCVI_FIRST</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a242e725cea6834f5364d4b9e7d40bea5">llvm::HexagonII::TypeCVI_LAST</a>.</p>

</div>
</div>

### isImmext() {#a95c527167756007a3fb2ab49ec4b2c6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isImmext (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 650 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonmccodeemitter/#afc35abf7d94e2a6c70fe2227fbf2a7ce">llvm::HexagonMCCodeEmitter::encodeInstruction</a>, <a href="#a92a5e3cfec25537762fd0102dfeb23af">extenderForIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmccodeemitter/#a8060e25eb66776205e632d4368d1d955">llvm::HexagonMCCodeEmitter::getMachineOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#ab0816f42a174972f6c2b099e9f7b6bc6">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::getSingleInstruction</a>, <a href="#aa49bb12513da4059233afd113f2cd3f0">hasImmExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp/#a060f0d1989564164d0cf3fad101666f4">lookForCompound</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstprinter/#aa26f3ffae0b86b636abd35ddeda5d523">llvm::HexagonInstPrinter::printInst</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#ac7d91a59f353ae38556450341aea270d">llvm::HexagonShuffler::reportResourceUsage</a>.</p>

</div>
</div>

### isInnerLoop() {#aa4c6bd427b092558b6bf875d8943558d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isInnerLoop (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 654 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a4509c43893edc940979f690c468664c1">llvm::MCOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="#a9cb9ab22836cb06b3ce84cca5dd1f452">innerLoopMask</a> and <a href="#a69d33e060c5b0bbfe0f8a2cbeb71f598">isBundle</a>.</p>


<p>Referenced by <a href="#a64c7c69f960b66bee56f0df768811175">LoopNeedsPadding</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagoninstprinter/#aa26f3ffae0b86b636abd35ddeda5d523">llvm::HexagonInstPrinter::printInst</a>.</p>

</div>
</div>

### isIntReg() {#a0ec69ad6054a54a0d7f5e20a303b9bba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isIntReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 660 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="#ae89672f809e6b7c989b09f70432e5de5">getDuplexCandidateGroup</a>.</p>

</div>
</div>

### isIntRegForSubInst() {#a90252d582ff57d9749eb7dc3aac57816}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isIntRegForSubInst (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 664 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp/#a1c0379352edde54a80bacc7540aee0c7">getCompoundCandidateGroup</a>, <a href="#ae89672f809e6b7c989b09f70432e5de5">getDuplexCandidateGroup</a> and <a href="#a0adeccf7489c053f6a2ee2ecbfe77ea8">subInstWouldBeExtended</a>.</p>

</div>
</div>

### isMemReorderDisabled() {#a50f29a655ab9a1a5fdf0d476786cbd64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isMemReorderDisabled (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 803 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a4509c43893edc940979f690c468664c1">llvm::MCOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="#a69d33e060c5b0bbfe0f8a2cbeb71f598">isBundle</a> and <a href="#a2d536ccc8c48cdd4f2faebe911832082">memReorderDisabledMask</a>.</p>


<p>Referenced by <a href="#a12bbe632ac24b40e52a6f3dcdef003d5">getDuplexPossibilties</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonmctargetdesc-cpp-/hexagontargetasmstreamer/#ad17bf01008144e718fa39ffa0ef84733">anonymous{HexagonMCTargetDesc.cpp}::HexagonTargetAsmStreamer::prettyPrintAsm</a> and <a href="#a683b8d4f721f40e4a590b1ab7ac682db">setMemReorderDisabled</a>.</p>

</div>
</div>

### isNewValue() {#a41c2639831016e233df65de1a6ec6bd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isNewValue (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether the insn expects newly produced value.</p>

<p>Declaration at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 670 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a76f0b757a8ba0684e543de6287e93a3e">llvm::HexagonII::NewValueMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a4d878f7d1e4bbdffe0d891f3e7f3d576">llvm::HexagonII::NewValuePos</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonmccodeemitter/#a8060e25eb66776205e632d4368d1d955">llvm::HexagonMCCodeEmitter::getMachineOpValue</a>, <a href="#a96d1b18f6b327cd31760f1e6086ab7f8">getNewValueOperand</a>, <a href="#aec6caa48fc271621aca9478a1c4a4268">getNewValueOperand2</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#ab0816f42a174972f6c2b099e9f7b6bc6">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::getSingleInstruction</a>.</p>

</div>
</div>

### isNewValueStore() {#a5cc023a236173fcdb81a1820c1745eb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isNewValueStore (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the operand is a new-value store insn.</p>

<p>Declaration at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 676 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a0e300fbb3f8697327c013ac8853b9872">llvm::HexagonII::NVStoreMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a6a13c8e37ceddce5bdc0c24d715b4775">llvm::HexagonII::NVStorePos</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>

</div>
</div>

### isOpExtendable() {#a7945fcb6c4dfbf09f0010f52bd73ef24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isOpExtendable (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI, unsigned short O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether the operand is extendable.</p>

<p>Declaration at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 683 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>Reference <a href="#a5115f4f0f0213e99431e82c167be0b98">getExtendableOp</a>.</p>

</div>
</div>

### isOrderedDuplexPair() {#a09ddc9ac2f9a0ce92be5565eff4f3869}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isOrderedDuplexPair (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MIa, bool ExtendedA, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MIb, bool ExtendedB, bool bisReversable, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>non-Symmetrical. See if these two instructions are fit for duplex pair.</p>

<p>Declaration at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 572 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcduplexinfo-cpp">HexagonMCDuplexInfo.cpp</a>.</p>


<p>References <a href="#a0cc69fdbc6fdc191c90bcd0f399dfa3f">deriveSubInst</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ae46058c90a3c703357331a6501b32f1c">llvm::StringRef::equals_insensitive</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a5d5452528429597f223826cbc63ca867">llvm::MCSubtargetInfo::getCPU</a>, <a href="#ae89672f809e6b7c989b09f70432e5de5">getDuplexCandidateGroup</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a3c5c7109f398fdca515509e2284cd8c0">llvm::MCInst::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a94abf618eb8001b802910ab872a7d1d9">llvm::MCOperand::getReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a780ec6792abe76b6925d0f2e97c6ef9fa286b0f049af0ca69b45135a9ce2f455d">llvm::HexagonII::HSIG_L2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a780ec6792abe76b6925d0f2e97c6ef9fa04bc370b14122c63bab19adc7f23432e">llvm::HexagonII::HSIG_None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a780ec6792abe76b6925d0f2e97c6ef9fa6dcfa55970176f718ebc0d5c8ed793f8">llvm::HexagonII::HSIG_S1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a780ec6792abe76b6925d0f2e97c6ef9fa2db44b42ecc6d5f75028163915a228f7">llvm::HexagonII::HSIG_S2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoninstrinfo-cpp/#af04c6a150c026e48309d20f347dde315">isDuplexPairMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a7a8c7eea0aa4890f25a4b83e1f0a0b6f">llvm::MCOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcduplexinfo-cpp/#abc40bc6679130011f95e653a26e39445">opcodeData</a> and <a href="#a0adeccf7489c053f6a2ee2ecbfe77ea8">subInstWouldBeExtended</a>.</p>


<p>Referenced by <a href="#a12bbe632ac24b40e52a6f3dcdef003d5">getDuplexPossibilties</a>.</p>

</div>
</div>

### isOuterLoop() {#a15eb1eaa893053e3e1178be7e11f2f59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isOuterLoop (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 688 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a4509c43893edc940979f690c468664c1">llvm::MCOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="#a69d33e060c5b0bbfe0f8a2cbeb71f598">isBundle</a> and <a href="#adb33329a6d6debbd79d19dd7927e0b38">outerLoopMask</a>.</p>


<p>Referenced by <a href="#a64c7c69f960b66bee56f0df768811175">LoopNeedsPadding</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagoninstprinter/#aa26f3ffae0b86b636abd35ddeda5d523">llvm::HexagonInstPrinter::printInst</a>.</p>

</div>
</div>

### isPredicated() {#a97d6571ff5232080bec163cd55377545}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isPredicated (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 733 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a30dcf20b0e185e37257f83834ed8c8bd">llvm::HexagonII::PredicatedMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64ab908ef74891dc244d7d87f271b1db9ca">llvm::HexagonII::PredicatedPos</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonmccodeemitter/#a8060e25eb66776205e632d4368d1d955">llvm::HexagonMCCodeEmitter::getMachineOpValue</a> and <a href="#aa930f49234de4fd7a469613a1989daf1">predicateInfo</a>.</p>

</div>
</div>

### isPredicatedNew() {#a136b73813b05ae1deee68a06b4c55f5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isPredicatedNew (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether the insn is newly predicated.</p>

<p>Declaration at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 750 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64ab8c084052508bde5e0c5e504eb39ea87">llvm::HexagonII::PredicatedNewMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a0a7ac197cd78b36296dafcf3f479ceee">llvm::HexagonII::PredicatedNewPos</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>

</div>
</div>

### isPredicatedTrue() {#ad81fe27b122fc4b5e48cf9be26d45af8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isPredicatedTrue (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 756 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64aafc1670bf2e01277addac23a291205fd">llvm::HexagonII::PredicatedFalseMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a7133391540b98eb529b45d78c9f95a34">llvm::HexagonII::PredicatedFalsePos</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonmccodeemitter/#a8060e25eb66776205e632d4368d1d955">llvm::HexagonMCCodeEmitter::getMachineOpValue</a> and <a href="#aa930f49234de4fd7a469613a1989daf1">predicateInfo</a>.</p>

</div>
</div>

### isPredicateLate() {#a357d567932941548effd2311bdfcc80b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isPredicateLate (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 743 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a357709d037b24feba5654ba2870abb4b">llvm::HexagonII::PredicateLateMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a60beb76d672b6f2b364718a3b4760111">llvm::HexagonII::PredicateLatePos</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>

</div>
</div>

### isPredReg() {#ad79ef5bf9d1134049c0f61823fa42be0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isPredReg (<a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 763 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### isPredRegister() {#a96fa23bebcb8417618bdeb24230bf2d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isPredRegister (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Inst, unsigned I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 768 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a7a8c7eea0aa4890f25a4b83e1f0a0b6f">llvm::MCOperand::isReg</a>.</p>

</div>
</div>

### isPrefix() {#a2ddcabcb8f48732ec9a2311c1e298d3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isPrefix (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 739 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="#a94f0ca29631596dfaa69418dd1dd6cbd">getType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a60b35308a0a70166e236a990524eb366">llvm::HexagonII::TypeEXTENDER</a>.</p>


<p>Referenced by <a href="#ab517da745358f306f00361d8280d020b">isCanon</a>.</p>

</div>
</div>

### isRestrictNoSlot1Store() {#ad9ae2e328fd6441af81f22bff80c42b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isRestrictNoSlot1Store (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 790 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a88bf86319390d6ad4bcc618d7fb8f026">llvm::HexagonII::RestrictNoSlot1StoreMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64aa721312c2ab96be5b2a1167bd9b3e501">llvm::HexagonII::RestrictNoSlot1StorePos</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#aafe1b52718a5cd8afd0dbb15e45b5c17">llvm::HexagonShuffler::GetPacketSummary</a>.</p>

</div>
</div>

### isRestrictSlot1AOK() {#a0d2c795a597e289231bf4d8c1ec7a2ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isRestrictSlot1AOK (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether the insn can be packaged only with an A-type insn in slot #1.</p>

<p>Declaration at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 783 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a1327ec8d0c3da1e1503279c682d78893">llvm::HexagonII::RestrictSlot1AOKMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64aaa377f375ec6a36f06a988d6b648ae0d">llvm::HexagonII::RestrictSlot1AOKPos</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#aafe1b52718a5cd8afd0dbb15e45b5c17">llvm::HexagonShuffler::GetPacketSummary</a>.</p>

</div>
</div>

### IsReverseVecRegPair() {#a150c2ac48d241ceb656546c6c482c03a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::IsReverseVecRegPair (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> VecReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 699 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#ab0816f42a174972f6c2b099e9f7b6bc6">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::getSingleInstruction</a>, <a href="#a097363c5ca1d16458abcd7e6a273ade4">GetVecRegPairIndices</a>, <a href="#a32abefbdb58d94344aae7e32f982b037">IsSingleConsumerRefPairProducer</a> and <a href="#a9d5d784d9e6423800c96623185102095">SubregisterBit</a>.</p>

</div>
</div>

### IsSingleConsumerRefPairProducer() {#a32abefbdb58d94344aae7e32f982b037}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::IsSingleConsumerRefPairProducer (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Producer, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Consumer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 720 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="#a150c2ac48d241ceb656546c6c482c03a">IsReverseVecRegPair</a>, <a href="#a56307e938767b5cad81b457fa6b7f3bc">IsVecRegPair</a> and <a href="#a64b03194da15ec0ddafd107ff57dd690">IsVecRegSingle</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#a274bccca247b2503b7fe53c48154e9de">RegisterMatches</a>.</p>

</div>
</div>

### isSolo() {#a11e74a6ead98c7237e37c532e411295d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isSolo (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether the insn is solo, i.e., cannot be in a packet.</p>

<p>Declaration at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 798 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo/#a176ca2c9108a997dcfd8aadf4c0f0fa0">llvm::MCInstrInfo::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a40699f52232ab821dd865f2559f6bddb">llvm::HexagonII::SoloMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64aa8c4786ea43dbfe26d1cd379fa16a144">llvm::HexagonII::SoloPos</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>

</div>
</div>

### isSoloAX() {#a4157ec35dc2d6457245b8772cc3c0602}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isSoloAX (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether the insn can be packaged only with A and X-type insns.</p>

<p>Declaration at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 777 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a7e1d3911b78e1058bb2edd1efe445aeb">llvm::HexagonII::SoloAXMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64ab272cafedff0e7b16e646cdef7c89dbb">llvm::HexagonII::SoloAXPos</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>

</div>
</div>

### isSubInstruction() {#aeb3cb6c125bcfdc44c7d3942911616d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isSubInstruction (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 809 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>.</p>

</div>
</div>

### IsVecRegPair() {#a56307e938767b5cad81b457fa6b7f3bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::IsVecRegPair (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> VecReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 694 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#ab0816f42a174972f6c2b099e9f7b6bc6">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::getSingleInstruction</a>, <a href="#a097363c5ca1d16458abcd7e6a273ade4">GetVecRegPairIndices</a>, <a href="#a32abefbdb58d94344aae7e32f982b037">IsSingleConsumerRefPairProducer</a> and <a href="#a9d5d784d9e6423800c96623185102095">SubregisterBit</a>.</p>

</div>
</div>

### IsVecRegSingle() {#a64b03194da15ec0ddafd107ff57dd690}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::IsVecRegSingle (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> VecReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 703 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="#a32abefbdb58d94344aae7e32f982b037">IsSingleConsumerRefPairProducer</a> and <a href="#a9d5d784d9e6423800c96623185102095">SubregisterBit</a>.</p>

</div>
</div>

### isVector() {#ae72685c5f32e967a3708d52677f1226b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::isVector (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 869 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64a08655f62345d0c726ed494d4e489ba64">llvm::HexagonII::isCVIMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64ad9c76d800b656bc25632f83cd3162cae">llvm::HexagonII::isCVIPos</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonmccodeemitter/#a8060e25eb66776205e632d4368d1d955">llvm::HexagonMCCodeEmitter::getMachineOpValue</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#ab0816f42a174972f6c2b099e9f7b6bc6">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::getSingleInstruction</a>.</p>

</div>
</div>

### LoopNeedsPadding() {#a64c7c69f960b66bee56f0df768811175}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::LoopNeedsPadding (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 1048 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="#a246da06f2e49f678663ae6e21bedffb3">bundleSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h/#a558f9682c979b92bd33ddb69246dac31">HEXAGON_PACKET_INNER_SIZE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h/#a265d3c2f472273a5dd0c00f6472f6852">HEXAGON_PACKET_OUTER_SIZE</a>, <a href="#aa4c6bd427b092558b6bf875d8943558d">isInnerLoop</a> and <a href="#a15eb1eaa893053e3e1178be7e11f2f59">isOuterLoop</a>.</p>


<p>Referenced by <a href="#a2cb3beb5a3e71a3b94697f7083f2e4be">padEndloop</a>.</p>

</div>
</div>

### minConstant() {#a6ca1ea5b42b7c51b90376ec8262db074}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::HexagonMCInstrInfo::minConstant (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI, size_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 874 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ac9408fbc60922d24b01c1efcbd4ba52b">llvm::MCOperand::getExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ae23b2e8269fe15dbe5ebb3394438960c">llvm::MCOperand::isExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae9dabebeb083ad5885642b5e6a84c9c0a7b71dfec5c8dd524069eed634dc0a3a5">llvm::Sentinel</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae534d5d22096b2665d16e5ab600ebbce">llvm::MCInst::size</a>.</p>


<p>Referenced by <a href="#a0cc69fdbc6fdc191c90bcd0f399dfa3f">deriveSubInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp/#a1c0379352edde54a80bacc7540aee0c7">getCompoundCandidateGroup</a>, <a href="#ae89672f809e6b7c989b09f70432e5de5">getDuplexCandidateGroup</a>, <a href="#a174e266390355aa15c8ab81345640235">inRange</a> and <a href="#a39b1cac0d0f4a1a2a36a74e96c80b368">inSRange</a>.</p>

</div>
</div>

### mustExtend() {#ae19c50e8978b829dd70b876360c78894}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::mustExtend (<a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Expr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 893 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonmcexpr/#a7b6727baf4b2e8c33ab3c7063339c4e3">llvm::HexagonMCExpr::mustExtend</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-hexagonasmparser-cpp-/hexagonoperand/#ac2aee5b5bd6cf3275da3e9e35895fecc">anonymous{HexagonAsmParser.cpp}::HexagonOperand::CheckImmRange</a> and <a href="#a0dc17f36db22a5d62643fdce547bb3ea">isConstExtended</a>.</p>

</div>
</div>

### mustNotExtend() {#a5ad0644e32da21f9b472af7cdcd6a9d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::mustNotExtend (<a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Expr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 901 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonmcexpr/#a318bb6449f347e87664f9dec35a831bc">llvm::HexagonMCExpr::mustNotExtend</a>.</p>


<p>Referenced by <a href="#a0dc17f36db22a5d62643fdce547bb3ea">isConstExtended</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#a135855aba8ee58019db788042c0d9a54">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::isInstRelaxable</a>.</p>

</div>
</div>

### packetSize() {#afbd5d7edb0e9b02e6072243fa310e97b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::HexagonMCInstrInfo::packetSize (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 923 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a> and <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>.</p>

</div>
</div>

### packetSizeSlots() {#ad6600c9ef01f540a9d8a3991c2b13d25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::HexagonMCInstrInfo::packetSizeSlots (<a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 917 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a0ad14e9a81239b54fd64089b3290bfde">llvm::MCSubtargetInfo::hasFeature</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h/#a8f76c0f5e34856920717e06ebc5f4dc3">HEXAGON_PACKET_SIZE</a>.</p>

</div>
</div>

### padEndloop() {#a2cb3beb5a3e71a3b94697f7083f2e4be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::HexagonMCInstrInfo::padEndloop (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MCI, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Context)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 929 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ae86bea5bf6fe3c0a2a9f09f5fdc4a310">llvm::MCOperand::createInst</a>, <a href="#a69d33e060c5b0bbfe0f8a2cbeb71f598">isBundle</a>, <a href="#a64c7c69f960b66bee56f0df768811175">LoopNeedsPadding</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmcinstrinfo-cpp-/#abda7c7a2d206ce064b97412b007ea5af">anonymous{HexagonMCInstrInfo.cpp}::canonicalizePacketImpl</a>.</p>

</div>
</div>

### predicateInfo() {#aa930f49234de4fd7a469613a1989daf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HexagonMCInstrInfo::PredicateInfo llvm::HexagonMCInstrInfo::predicateInfo (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 938 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a94abf618eb8001b802910ab872a7d1d9">llvm::MCOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a97d6571ff5232080bec163cd55377545">isPredicated</a>, <a href="#ad81fe27b122fc4b5e48cf9be26d45af8">isPredicatedTrue</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### prefersSlot3() {#a7fb5c7a86107907a7985c93274b02066}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::prefersSlot3 (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 948 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a5d6d2c647044122707e6ebc1f62f7c67">getDesc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64acec820052af608aa5b4ce7ca5a26c333">llvm::HexagonII::PrefersSlot3Mask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a51eb22181de03e7d888b8a141bbc6c64af629d9172756a3eed387a1fd30fae0a1">llvm::HexagonII::PrefersSlot3Pos</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#aafe1b52718a5cd8afd0dbb15e45b5c17">llvm::HexagonShuffler::GetPacketSummary</a>.</p>

</div>
</div>

### replaceDuplex() {#abd317698bbd34d1cb4e69a49141dab58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::HexagonMCInstrInfo::replaceDuplex (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MCI, <a href="/web-llvm/docs/api/classes/llvm/duplexcandidate">DuplexCandidate</a> Candidate)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 1001 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad7df02a018c3a01d74738d5ba3a09e93">llvm::MCInst::begin</a>, <a href="#a1eda4c3f6c0329af244778af7bd699fa">deriveDuplex</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a392c263d0b0a47be4702000f9bca7f16">llvm::MCInst::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ab21fde20666d4c8228c527e0321b2f9b">llvm::MCOperand::getInst</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/duplexcandidate/#a0449235b309f3601156296be9722bf0d">llvm::DuplexCandidate::iClass</a>, <a href="#a69d33e060c5b0bbfe0f8a2cbeb71f598">isBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/duplexcandidate/#addb8ad0ab1a183fa17ab2d9ce840fe7c">llvm::DuplexCandidate::packetIndexI</a>, <a href="/web-llvm/docs/api/classes/llvm/duplexcandidate/#a1b094202dba90f67f1b8712da5f66696">llvm::DuplexCandidate::packetIndexJ</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a8343a62f53002655ce38b4c65a9aace9">llvm::MCOperand::setInst</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae534d5d22096b2665d16e5ab600ebbce">llvm::MCInst::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a7e6dfe0eaf6d1b1720be0390c764cdbd">llvm::HexagonMCShuffle</a>.</p>

</div>
</div>

### requiresSlot() {#ac5fca0a3b40921b5bedfa3303b5158f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::requiresSlot (<a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 974 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a53afee158973a8af8c60263ddb5b2d07">llvm::MCSubtargetInfo::getFeatureBits</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#a4468bd7691e8ea1515151762d24f4085">llvm::HexagonShuffler::permitNonSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#ac7d91a59f353ae38556450341aea270d">llvm::HexagonShuffler::reportResourceUsage</a> and <a href="#ab9b5401fd1584e3e51164213c889fd87">slotsConsumed</a>.</p>

</div>
</div>

### s27\_2\_reloc() {#aa194168067ea8a2c03b1973560ce0904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::s27_2_reloc (<a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Expr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 910 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonmcexpr/#a85e372984bd10356d2313b67a899ced9">llvm::HexagonMCExpr::s27_2_reloc</a>.</p>

</div>
</div>

### setInnerLoop() {#a423fa247fcb4eadd2ba802397a79641b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::HexagonMCInstrInfo::setInnerLoop (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 1015 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a4509c43893edc940979f690c468664c1">llvm::MCOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="#a9cb9ab22836cb06b3ce84cca5dd1f452">innerLoopMask</a>, <a href="#a69d33e060c5b0bbfe0f8a2cbeb71f598">isBundle</a> and <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a170578b62596712cf242f97ea687074b">llvm::MCOperand::setImm</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#ab0816f42a174972f6c2b099e9f7b6bc6">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::getSingleInstruction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a77ac85fa1d774b4d1f5a064e1b8ee8c3">llvm::HexagonLowerToMC</a>.</p>

</div>
</div>

### setMemReorderDisabled() {#a683b8d4f721f40e4a590b1ab7ac682db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::HexagonMCInstrInfo::setMemReorderDisabled (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 1021 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a4509c43893edc940979f690c468664c1">llvm::MCOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="#a69d33e060c5b0bbfe0f8a2cbeb71f598">isBundle</a>, <a href="#a50f29a655ab9a1a5fdf0d476786cbd64">isMemReorderDisabled</a>, <a href="#a2d536ccc8c48cdd4f2faebe911832082">memReorderDisabledMask</a> and <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a170578b62596712cf242f97ea687074b">llvm::MCOperand::setImm</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#a922dc7b28cc9b8895585a602d941b04f">llvm::HexagonAsmPrinter::emitInstruction</a>.</p>

</div>
</div>

### setMustExtend() {#aedeada7604ef9521d3aec4ec5441811c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::HexagonMCInstrInfo::setMustExtend (<a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Expr, bool Val=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 888 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonmcexpr/#a9f09c78f6fc2bf531212eabec2905904">llvm::HexagonMCExpr::setMustExtend</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonmcinstlower-cpp/#a5d48c2fbd54413cd08a7ada69f05e7f2">GetSymbolRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77ac85fa1d774b4d1f5a064e1b8ee8c3">llvm::HexagonLowerToMC</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#ac9c92aad21e10d61c23982f88c094ef3">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseInstruction</a>.</p>

</div>
</div>

### setMustNotExtend() {#ac3e1f7a4739363ebefca0ac7930c2ccb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::HexagonMCInstrInfo::setMustNotExtend (<a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Expr, bool Val=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 355 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 897 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonmcexpr/#a1d94ee4c8ac6b3ec3606c9766c82dcd9">llvm::HexagonMCExpr::setMustNotExtend</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#aee072cd97eb6d078d122611833049aa6">llvm::HexagonAsmPrinter::HexagonProcessInstruction</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#ac9c92aad21e10d61c23982f88c094ef3">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseInstruction</a>.</p>

</div>
</div>

### setOuterLoop() {#a0eae7cb5eae56054e1b89dfbe489a0f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::HexagonMCInstrInfo::setOuterLoop (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 1028 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a4509c43893edc940979f690c468664c1">llvm::MCOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="#a69d33e060c5b0bbfe0f8a2cbeb71f598">isBundle</a>, <a href="#adb33329a6d6debbd79d19dd7927e0b38">outerLoopMask</a> and <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a170578b62596712cf242f97ea687074b">llvm::MCOperand::setImm</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#ab0816f42a174972f6c2b099e9f7b6bc6">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::getSingleInstruction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a77ac85fa1d774b4d1f5a064e1b8ee8c3">llvm::HexagonLowerToMC</a>.</p>

</div>
</div>

### setS27\_2\_reloc() {#a35d0d6d8b3d10dd3c01582071e1da5da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::HexagonMCInstrInfo::setS27_2_reloc (<a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Expr, bool Val=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 905 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonmcexpr/#ab5586106990e946fd835539d8ac11902">llvm::HexagonMCExpr::setS27_2_reloc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#aee072cd97eb6d078d122611833049aa6">llvm::HexagonAsmPrinter::HexagonProcessInstruction</a>.</p>

</div>
</div>

### slotsConsumed() {#ab9b5401fd1584e3e51164213c889fd87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::HexagonMCInstrInfo::slotsConsumed (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 985 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="#a607343a05725b53e0d5bd85a4a44586e">bundleInstructions</a>, <a href="#a26ecf3daf01c489f01b5bf6953827080">isDuplex</a> and <a href="#ac5fca0a3b40921b5bedfa3303b5158f3">requiresSlot</a>.</p>

</div>
</div>

### subInstWouldBeExtended() {#a0adeccf7489c053f6a2ee2ecbfe77ea8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonMCInstrInfo::subInstWouldBeExtended (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; potentialDuplex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 535 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcduplexinfo-cpp">HexagonMCDuplexInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ac9408fbc60922d24b01c1efcbd4ba52b">llvm::MCOperand::getExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a94abf618eb8001b802910ab872a7d1d9">llvm::MCOperand::getReg</a>, <a href="#a90252d582ff57d9749eb7dc3aac57816">isIntRegForSubInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abcb678e42ef8094f2b744592ec378feb">llvm::isShiftedInt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af0d6fc340d84e22e165e7d069b74f3c5">llvm::isShiftedUInt</a>.</p>


<p>Referenced by <a href="#a09ddc9ac2f9a0ce92be5565eff4f3869">isOrderedDuplexPair</a>.</p>

</div>
</div>

### SubregisterBit() {#a9d5d784d9e6423800c96623185102095}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::HexagonMCInstrInfo::SubregisterBit (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Consumer, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Producer, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Producer2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 1034 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a>.</p>


<p>References <a href="#a150c2ac48d241ceb656546c6c482c03a">IsReverseVecRegPair</a>, <a href="#a56307e938767b5cad81b457fa6b7f3bc">IsVecRegPair</a> and <a href="#a64b03194da15ec0ddafd107ff57dd690">IsVecRegSingle</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonmccodeemitter/#a8060e25eb66776205e632d4368d1d955">llvm::HexagonMCCodeEmitter::getMachineOpValue</a>.</p>

</div>
</div>

### tryCompound() {#a65fdd614c206400e24b2676a71daac1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::HexagonMCInstrInfo::tryCompound (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>tryCompound - Given a bundle check for compound insns when one is found update the contents fo the bundle with the compound insn.</p>


<p>If a compound instruction is found then the bundle will have one additional slot.</p>


<p>Declaration at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>, definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp">HexagonMCCompound.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e62b46a3eb52ccf356ac99f8ebb3c06">llvm::HexagonMCShuffle</a>, <a href="#a69d33e060c5b0bbfe0f8a2cbeb71f598">isBundle</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp/#a060f0d1989564164d0cf3fad101666f4">lookForCompound</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae534d5d22096b2665d16e5ab600ebbce">llvm::MCInst::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmcinstrinfo-cpp-/#abda7c7a2d206ce064b97412b007ea5af">anonymous{HexagonMCInstrInfo.cpp}::canonicalizePacketImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### bundleInstructionsOffset {#aa004a7b4f04de8ed59326f54873f7422}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::HexagonMCInstrInfo::bundleInstructionsOffset = 1</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>.</p>


<p>Referenced by <a href="#a235887e8341d1afbd5d815a0e9059f23">bundleInstructions</a>, <a href="#a246da06f2e49f678663ae6e21bedffb3">bundleSize</a>, <a href="#a92a5e3cfec25537762fd0102dfeb23af">extenderForIndex</a>, <a href="#a12bbe632ac24b40e52a6f3dcdef003d5">getDuplexPossibilties</a>, <a href="#adda8e3193ca3d31e415a2e4ac6089d50">instruction</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp/#a060f0d1989564164d0cf3fad101666f4">lookForCompound</a>.</p>

</div>
</div>

### innerLoopMask {#a9cb9ab22836cb06b3ce84cca5dd1f452}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::HexagonMCInstrInfo::innerLoopMask = 1 &lt;&lt; <a href="#aac9d8fdada61dfe9aca1bdd0ab51df81">innerLoopOffset</a></td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>.</p>


<p>Referenced by <a href="#aa4c6bd427b092558b6bf875d8943558d">isInnerLoop</a> and <a href="#a423fa247fcb4eadd2ba802397a79641b">setInnerLoop</a>.</p>

</div>
</div>

### innerLoopOffset {#aac9d8fdada61dfe9aca1bdd0ab51df81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::HexagonMCInstrInfo::innerLoopOffset = 0</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>.</p>

</div>
</div>

### memReorderDisabledMask {#a2d536ccc8c48cdd4f2faebe911832082}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::HexagonMCInstrInfo::memReorderDisabledMask = 1 &lt;&lt; <a href="#a66562128eb3b952c96b6432005b8bc47">memReorderDisabledOffset</a></td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>.</p>


<p>Referenced by <a href="#a50f29a655ab9a1a5fdf0d476786cbd64">isMemReorderDisabled</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#a3b17a068b924e23cc4b879be52707404">llvm::HexagonShuffler::isMemReorderDisabled</a> and <a href="#a683b8d4f721f40e4a590b1ab7ac682db">setMemReorderDisabled</a>.</p>

</div>
</div>

### memReorderDisabledOffset {#a66562128eb3b952c96b6432005b8bc47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::HexagonMCInstrInfo::memReorderDisabledOffset = 2</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>.</p>

</div>
</div>

### noShuffleMask {#a91eef8bc25bda8da992af6b279f6663a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::HexagonMCInstrInfo::noShuffleMask = 1 &lt;&lt; <a href="#a689cd0d0b6cf69804c1877fc9ba3aae4">noShuffleOffset</a></td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>.</p>

</div>
</div>

### noShuffleOffset {#a689cd0d0b6cf69804c1877fc9ba3aae4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::HexagonMCInstrInfo::noShuffleOffset = 4</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>.</p>

</div>
</div>

### outerLoopMask {#adb33329a6d6debbd79d19dd7927e0b38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::HexagonMCInstrInfo::outerLoopMask = 1 &lt;&lt; <a href="#ab73790216d7019c4bd442917004a3da5">outerLoopOffset</a></td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>.</p>


<p>Referenced by <a href="#a15eb1eaa893053e3e1178be7e11f2f59">isOuterLoop</a> and <a href="#a0eae7cb5eae56054e1b89dfbe489a0f1">setOuterLoop</a>.</p>

</div>
</div>

### outerLoopOffset {#ab73790216d7019c4bd442917004a3da5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::HexagonMCInstrInfo::outerLoopOffset = 1</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>.</p>

</div>
</div>

### splitNoMemorderMask {#a9e5744c4596f2df67d2c874cd0982755}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::HexagonMCInstrInfo::splitNoMemorderMask = 1 &lt;&lt; <a href="#a5875e856b0b59a411bf0cea0dcf62f02">splitNoMemOrderOffset</a></td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>.</p>

</div>
</div>

### splitNoMemOrderOffset {#a5875e856b0b59a411bf0cea0dcf62f02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::HexagonMCInstrInfo::splitNoMemOrderOffset = 3</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp">HexagonMCCompound.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcduplexinfo-cpp">HexagonMCDuplexInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-cpp">HexagonMCInstrInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">HexagonMCInstrInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
