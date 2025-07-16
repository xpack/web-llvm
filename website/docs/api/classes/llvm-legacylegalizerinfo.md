---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/legacylegalizerinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LegacyLegalizerInfo` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::LegacyLegalizerInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">llvm/CodeGen/GlobalISel/LegacyLegalizerInfo.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae619fa147f84159a8a3f54e480ab2b85">SizeAndAction</a> = std::pair&lt; uint16_t, <a href="/web-llvm/docs/api/namespaces/llvm/legacylegalizeactions/#ad25716c86372dafbf624b34891685078">LegacyLegalizeActions::LegacyLegalizeAction</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a> = std::vector&lt; <a href="#ae619fa147f84159a8a3f54e480ab2b85">SizeAndAction</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2001432f616b09f569d6147c957948c3">SizeChangeStrategy</a> = std::function&lt; <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a>(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a> &amp;v)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a147e06b4a54fdaa78ad3d1fc79869a1a">TypeMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legacylegalizeactions/#ad25716c86372dafbf624b34891685078">LegacyLegalizeActions::LegacyLegalizeAction</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afde846dba0ee6e38964394a16f4aff93">LegacyLegalizerInfo</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b586580f1e35e04ae0f3186fadd6594">computeTables</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute any ancillary tables needed to quickly decide how an operation should be handled. <a href="#a6b586580f1e35e04ae0f3186fadd6594">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ed946c9bc8e7367d6a31582048c8570">setAction</a> (const InstrAspect &amp;Aspect, LegacyLegalizeActions::LegacyLegalizeAction Action)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>More friendly way to set an action for common types that have an <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> representation. <a href="#a9ed946c9bc8e7367d6a31582048c8570">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac118cc8e04f71fc897c5a84874595eb0">setLegalizeScalarToDifferentSizeStrategy</a> (const unsigned Opcode, const unsigned TypeIdx, SizeChangeStrategy S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The setAction calls record the non-size-changing legalization actions to take on specificly-sized types. <a href="#ac118cc8e04f71fc897c5a84874595eb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad67cd16a1da06553bb4936551f67c7d0">setLegalizeVectorElementToDifferentSizeStrategy</a> (const unsigned Opcode, const unsigned TypeIdx, SizeChangeStrategy S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See also setLegalizeScalarToDifferentSizeStrategy. <a href="#ad67cd16a1da06553bb4936551f67c7d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/legacylegalizeactionstep">LegacyLegalizeActionStep</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2df8f41f63c8cd97c9f3b4a6b6374b0">getAction</a> (const LegalityQuery &amp;Query) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a975fc5bd6e0c6d7e357560c987a36cae">getOpcodeIdxForOpcode</a> (unsigned Opcode) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/namespaces/llvm/legacylegalizeactions/#ad25716c86372dafbf624b34891685078">LegacyLegalizeActions::LegacyLegalizeAction</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf4717f556bc474f1425fe0d1c3b93dc">getAspectAction</a> (const InstrAspect &amp;Aspect) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine what action should be taken to legalize the given generic instruction opcode, type-index and type. <a href="#abf4717f556bc474f1425fe0d1c3b93dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27503e2fc0aa8b6c7bf260542a991787">setScalarAction</a> (const unsigned Opcode, const unsigned TypeIndex, const SizeAndActionsVec &amp;SizeAndActions)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a> is a representation mapping between all natural numbers and an Action. <a href="#a27503e2fc0aa8b6c7bf260542a991787">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a339ba5cbfd13a1f9fd84a9a4db96324f">setPointerAction</a> (const unsigned Opcode, const unsigned TypeIndex, const unsigned AddressSpace, const SizeAndActionsVec &amp;SizeAndActions)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f5972b51d9da92512cabe79063c137a">setScalarInVectorAction</a> (const unsigned Opcode, const unsigned TypeIndex, const SizeAndActionsVec &amp;SizeAndActions)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If an operation on a given vector type (say &lt;M x iN&gt;) isn't explicitly specified, we proceed in 2 stages. <a href="#a8f5972b51d9da92512cabe79063c137a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1692cb7a184e2c0eeef39ad958aebe15">setVectorNumElementAction</a> (const unsigned Opcode, const unsigned TypeIndex, const unsigned ElementSize, const SizeAndActionsVec &amp;SizeAndActions)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See also setScalarInVectorAction. <a href="#a1692cb7a184e2c0eeef39ad958aebe15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add0b5d7cec19f0217daa22fa72a4b765">setActions</a> (unsigned TypeIndex, SmallVector&lt; SizeAndActionsVec, 1 &gt; &amp;Actions, const SizeAndActionsVec &amp;SizeAndActions)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets actions for all bit sizes on a particular generic opcode, type index and scalar or pointer type. <a href="#add0b5d7cec19f0217daa22fa72a4b765">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/namespaces/llvm/legacylegalizeactions/#ad25716c86372dafbf624b34891685078">LegacyLegalizeActions::LegacyLegalizeAction</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f93fb284bb858d62aa5e63f29523521">findScalarLegalAction</a> (const InstrAspect &amp;Aspect) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the next action needed to get the scalar or pointer type closer to being legal E.g. <a href="#a4f93fb284bb858d62aa5e63f29523521">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/namespaces/llvm/legacylegalizeactions/#ad25716c86372dafbf624b34891685078">LegacyLegalizeActions::LegacyLegalizeAction</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7937daa26225e695d46905dbccacc8d3">findVectorLegalAction</a> (const InstrAspect &amp;Aspect) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the next action needed towards legalizing the vector type. <a href="#a7937daa26225e695d46905dbccacc8d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/densemap">TypeMap</a>, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa88153e396b204e46576078a5be105a9">SpecifiedActions</a>[LastOp - FirstOp+1]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="#a2001432f616b09f569d6147c957948c3">SizeChangeStrategy</a>, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c9d2bece9035055d74af2cfb0af6f40">ScalarSizeChangeStrategies</a>[LastOp - FirstOp+1]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="#a2001432f616b09f569d6147c957948c3">SizeChangeStrategy</a>, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad510aa243a304e2a6de8546c6102d4f7">VectorElementSizeChangeStrategies</a>[LastOp - FirstOp+1]</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef462d34443de87942245bb9edaf0b04">TablesInitialized</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a>, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89f919347be7235b866410df246c2997">ScalarActions</a>[LastOp - FirstOp+1]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a>, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c14411f135884296966bbab3df2037b">ScalarInVectorActions</a>[LastOp - FirstOp+1]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; uint16_t, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a>, 1 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac48cd2a93be363587df16f9dedcb6ce0">AddrSpace2PointerActions</a>[LastOp - FirstOp+1]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; uint16_t, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a>, 1 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c9088e355cbc383a3f717f423ca85f8">NumElements2Actions</a>[LastOp - FirstOp+1]</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a862586cb2d3bcdcce916162ebd5dda89">needsLegalizingToDifferentSize</a> (const LegacyLegalizeActions::LegacyLegalizeAction Action)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebb0c4b04132fb5bad2a70b2854a1b83">unsupportedForDifferentSizes</a> (const SizeAndActionsVec &amp;v)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="#a2001432f616b09f569d6147c957948c3">SizeChangeStrategy</a> for the common case where legalization for a particular operation consists of only supporting a specific set of type sizes. <a href="#aebb0c4b04132fb5bad2a70b2854a1b83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99b7a87bbd3d7e6dc5c30a0b577d3c76">widenToLargerTypesAndNarrowToLargest</a> (const SizeAndActionsVec &amp;v)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="#a2001432f616b09f569d6147c957948c3">SizeChangeStrategy</a> for the common case where legalization for a particular operation consists of widening the type to a large legal type, unless there is no such type and then instead it should be narrowed to the largest legal type. <a href="#a99b7a87bbd3d7e6dc5c30a0b577d3c76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f1886b5dda7fa57ac21a21f816c9f63">widenToLargerTypesUnsupportedOtherwise</a> (const SizeAndActionsVec &amp;v)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0253e2aef318462a46c42bb6f21c395">narrowToSmallerAndUnsupportedIfTooSmall</a> (const SizeAndActionsVec &amp;v)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a619f20a86e6a67eb6ff2b3bd2dd8d67e">moreToWiderTypesAndLessToWidest</a> (const SizeAndActionsVec &amp;v)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="#a2001432f616b09f569d6147c957948c3">SizeChangeStrategy</a> for the common case where legalization for a particular vector operation consists of having more elements in the vector, to a type that is legal. <a href="#a619f20a86e6a67eb6ff2b3bd2dd8d67e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee07c139c35f051d5306d1c6823dbf0c">increaseToLargerTypesAndDecreaseToLargest</a> (const SizeAndActionsVec &amp;v, LegacyLegalizeActions::LegacyLegalizeAction IncreaseAction, LegacyLegalizeActions::LegacyLegalizeAction DecreaseAction)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function to implement many typical <a href="#a2001432f616b09f569d6147c957948c3">SizeChangeStrategy</a> functions. <a href="#aee07c139c35f051d5306d1c6823dbf0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33c90208d9836a0e4a0125ee7c79c3cf">decreaseToSmallerTypesAndIncreaseToSmallest</a> (const SizeAndActionsVec &amp;v, LegacyLegalizeActions::LegacyLegalizeAction DecreaseAction, LegacyLegalizeActions::LegacyLegalizeAction IncreaseAction)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function to implement many typical <a href="#a2001432f616b09f569d6147c957948c3">SizeChangeStrategy</a> functions. <a href="#a33c90208d9836a0e4a0125ee7c79c3cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a808c33e260b835ffb9adaab321ce7a8a">checkPartialSizeAndActionsVector</a> (const SizeAndActionsVec &amp;v)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A partial <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a> potentially doesn't cover all bit sizes, i.e. <a href="#a808c33e260b835ffb9adaab321ce7a8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeeffd6a5cbdfa239e8e8d257bc5e0311">checkFullSizeAndActionsVector</a> (const SizeAndActionsVec &amp;v)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A full <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a> must cover all bit sizes, i.e. <a href="#aeeffd6a5cbdfa239e8e8d257bc5e0311">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#ae619fa147f84159a8a3f54e480ab2b85">SizeAndAction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23b989eb73497f291dd336148324bbf4">findAction</a> (const SizeAndActionsVec &amp;Vec, const uint32_t Size)</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55beac4fedefe00de9c7f4dce5d28f91">FirstOp</a> = TargetOpcode::PRE_ISEL_GENERIC_OPCODE_START</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42f7b2c652fadf47a21a95c8dbc09b0d">LastOp</a> = TargetOpcode::PRE_ISEL_GENERIC_OPCODE_END</td>
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


<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### SizeAndAction {#ae619fa147f84159a8a3f54e480ab2b85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LegacyLegalizerInfo::SizeAndAction = 
      std::pair&lt;uint16_t, LegacyLegalizeActions::LegacyLegalizeAction&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>

</div>
</div>

### SizeAndActionsVec {#a703c0ed452aea3693d8fe1441a935d5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LegacyLegalizerInfo::SizeAndActionsVec =  std::vector&lt;SizeAndAction&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>

</div>
</div>

### SizeChangeStrategy {#a2001432f616b09f569d6147c957948c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LegacyLegalizerInfo::SizeChangeStrategy = 
      std::function&lt;SizeAndActionsVec(const SizeAndActionsVec &amp;v)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### TypeMap {#a147e06b4a54fdaa78ad3d1fc79869a1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LegacyLegalizerInfo::TypeMap =  DenseMap&lt;LLT, LegacyLegalizeActions::LegacyLegalizeAction&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LegacyLegalizerInfo() {#afde846dba0ee6e38964394a16f4aff93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegacyLegalizerInfo::LegacyLegalizerInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>, definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legacylegalizerinfo-cpp">LegacyLegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#af46430106334db52bfa7a4107e53a0bda8f7357506e00d8cd0694f948f909865d">llvm::IRSimilarity::Legal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0ab75fcdd2d72d9e000beab48622402d93">llvm::Lower</a>, <a href="#af0253e2aef318462a46c42bb6f21c395">narrowToSmallerAndUnsupportedIfTooSmall</a>, <a href="#ac118cc8e04f71fc897c5a84874595eb0">setLegalizeScalarToDifferentSizeStrategy</a>, <a href="#a99b7a87bbd3d7e6dc5c30a0b577d3c76">widenToLargerTypesAndNarrowToLargest</a> and <a href="#a5f1886b5dda7fa57ac21a21f816c9f63">widenToLargerTypesUnsupportedOtherwise</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### computeTables() {#a6b586580f1e35e04ae0f3186fadd6594}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LegacyLegalizerInfo::computeTables ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute any ancillary tables needed to quickly decide how an operation should be handled.</p>


<p>This must be called after all "set*Action"methods but before any query is made or incorrect results may be returned.</p>


<p>Declaration at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legacylegalizerinfo-cpp">LegacyLegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#af46430106334db52bfa7a4107e53a0bda8f7357506e00d8cd0694f948f909865d">llvm::IRSimilarity::Legal</a>, <a href="#a619f20a86e6a67eb6ff2b3bd2dd8d67e">moreToWiderTypesAndLessToWidest</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a> and <a href="#aebb0c4b04132fb5bad2a70b2854a1b83">unsupportedForDifferentSizes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/bpflegalizerinfo/#a6439af2dec3e867282c9b033e8eb11f6">llvm::BPFLegalizerInfo::BPFLegalizerInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/m68klegalizerinfo/#a77a1ff087fb51dfd9397ffc153578c43">llvm::M68kLegalizerInfo::M68kLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a63e981ba0042fbfdd3857f66c82d8d28">llvm::MipsLegalizerInfo::MipsLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ppclegalizerinfo/#ae83d1a82dbe98543ff9238ae236b5e20">llvm::PPCLegalizerInfo::PPCLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvlegalizerinfo/#a6b747313719abb32e3599ab33501ea17">llvm::SPIRVLegalizerInfo::SPIRVLegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/x86legalizerinfo/#abfc562c1c7aebc23222627fa24d11df5">llvm::X86LegalizerInfo::X86LegalizerInfo</a>.</p>

</div>
</div>

### getAction() {#ab2df8f41f63c8cd97c9f3b4a6b6374b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegacyLegalizeActionStep LegacyLegalizerInfo::getAction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/legalityquery">LegalityQuery</a> &amp; Query)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>, definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legacylegalizerinfo-cpp">LegacyLegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#af46430106334db52bfa7a4107e53a0bda8f7357506e00d8cd0694f948f909865d">llvm::IRSimilarity::Legal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/legalityquery/#afd4ab894cdbdc5888a2d10fa5e5f8333">llvm::LegalityQuery::Opcode</a> and <a href="/web-llvm/docs/api/structs/llvm/legalityquery/#ab28fca6f8145be28b70ad89bb0c741b0">llvm::LegalityQuery::Types</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo/#af3687eafb2772c29aa67ce722c2081fd">llvm::LegalizerInfo::getAction</a>.</p>

</div>
</div>

### getOpcodeIdxForOpcode() {#a975fc5bd6e0c6d7e357560c987a36cae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LegacyLegalizerInfo::getOpcodeIdxForOpcode (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>, definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legacylegalizerinfo-cpp">LegacyLegalizerInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### setAction() {#a9ed946c9bc8e7367d6a31582048c8570}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LegacyLegalizerInfo::setAction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/instraspect">InstrAspect</a> &amp; Aspect, <a href="/web-llvm/docs/api/namespaces/llvm/legacylegalizeactions/#ad25716c86372dafbf624b34891685078">LegacyLegalizeActions::LegacyLegalizeAction</a> Action)</td>
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

<p>More friendly way to set an action for common types that have an <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> representation.</p>


<p>The LegacyLegalizeAction must be one for which NeedsLegalizingToDifferentSize returns false.</p>


<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/instraspect/#a356ff22c5336071aac58e00b736a269c">llvm::InstrAspect::Idx</a>, <a href="#a862586cb2d3bcdcce916162ebd5dda89">needsLegalizingToDifferentSize</a>, <a href="/web-llvm/docs/api/structs/llvm/instraspect/#a638726ef52ca6b3b3c100a2da460c26a">llvm::InstrAspect::Opcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> and <a href="/web-llvm/docs/api/structs/llvm/instraspect/#a4bd53ad2aadf9052aa97b22bb1951529">llvm::InstrAspect::Type</a>.</p>

</div>
</div>

### setLegalizeScalarToDifferentSizeStrategy() {#ac118cc8e04f71fc897c5a84874595eb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LegacyLegalizerInfo::setLegalizeScalarToDifferentSizeStrategy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned Opcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned TypeIdx, <a href="#a2001432f616b09f569d6147c957948c3">SizeChangeStrategy</a> S)</td>
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

<p>The setAction calls record the non-size-changing legalization actions to take on specificly-sized types.</p>


<p>The <a href="#a2001432f616b09f569d6147c957948c3">SizeChangeStrategy</a> defines what to do when the size of the type needs to be changed to reach a legally sized type (i.e., one that was defined through a setAction call). e.g. setAction ({G_ADD, 0, LLT::scalar(32)}, Legal); setLegalizeScalarToDifferentSizeStrategy(
  G_ADD, 0, widenToLargerTypesAndNarrowToLargest); will end up defining getAction({G_ADD, 0, T}) to return the following actions for different scalar types T: LLT::scalar(1)..LLT::scalar(31): {WidenScalar, 0, LLT::scalar(32)} LLT::scalar(32): {Legal, 0, LLT::scalar(32)} LLT::scalar(33)..: {NarrowScalar, 0, LLT::scalar(32)}</p>


<p>If no SizeChangeAction gets defined, through this function, the default is unsupportedForDifferentSizes.</p>


<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>


<p>Referenced by <a href="#afde846dba0ee6e38964394a16f4aff93">LegacyLegalizerInfo</a>.</p>

</div>
</div>

### setLegalizeVectorElementToDifferentSizeStrategy() {#ad67cd16a1da06553bb4936551f67c7d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LegacyLegalizerInfo::setLegalizeVectorElementToDifferentSizeStrategy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned Opcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned TypeIdx, <a href="#a2001432f616b09f569d6147c957948c3">SizeChangeStrategy</a> S)</td>
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

<p>See also setLegalizeScalarToDifferentSizeStrategy.</p>


<p>This function allows to set the <a href="#a2001432f616b09f569d6147c957948c3">SizeChangeStrategy</a> for vector elements.</p>


<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### findScalarLegalAction() {#a4f93fb284bb858d62aa5e63f29523521}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; LegacyLegalizeAction, LLT &gt; LegacyLegalizerInfo::findScalarLegalAction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/instraspect">InstrAspect</a> &amp; Aspect)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the next action needed to get the scalar or pointer type closer to being legal E.g.</p>


<p>findLegalAction({G_REM, 13}) should return (WidenScalar, 32). After that, findLegalAction({G_REM, 32}) will probably be called, which should return (Lower, 32). This is assuming the setScalarAction on G_REM was something like: setScalarAction(G_REM, 0, {{1, WidenScalar}, // bit sizes [ 1, 31[ {32, Lower}, // bit sizes [32, 33[ {33, NarrowScalar} // bit sizes [65, +inf[ });</p>


<p>Declaration at line 437 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>, definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legacylegalizerinfo-cpp">LegacyLegalizerInfo.cpp</a>.</p>

</div>
</div>

### findVectorLegalAction() {#a7937daa26225e695d46905dbccacc8d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; LegacyLegalizeAction, LLT &gt; LegacyLegalizerInfo::findVectorLegalAction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/instraspect">InstrAspect</a> &amp; Aspect)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the next action needed towards legalizing the vector type.</p>

<p>Declaration at line 441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>, definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legacylegalizerinfo-cpp">LegacyLegalizerInfo.cpp</a>.</p>

</div>
</div>

### getAspectAction() {#abf4717f556bc474f1425fe0d1c3b93dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; LegacyLegalizeAction, LLT &gt; LegacyLegalizerInfo::getAspectAction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/instraspect">InstrAspect</a> &amp; Aspect)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine what action should be taken to legalize the given generic instruction opcode, type-index and type.</p>


<p>Requires computeTables to have been called.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a pair consisting of the kind of legalization that should be performed and the destination type.</p></dd>
</dl>


<p>Declaration at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>, definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legacylegalizerinfo-cpp">LegacyLegalizerInfo.cpp</a>.</p>

</div>
</div>

### setActions() {#add0b5d7cec19f0217daa22fa72a4b765}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LegacyLegalizerInfo::setActions (unsigned TypeIndex, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a>, 1 &gt; &amp; Actions, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a> &amp; SizeAndActions)</td>
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

<p>Sets actions for all bit sizes on a particular generic opcode, type index and scalar or pointer type.</p>

<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>

</div>
</div>

### setPointerAction() {#a339ba5cbfd13a1f9fd84a9a4db96324f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LegacyLegalizerInfo::setPointerAction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned Opcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned TypeIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned AddressSpace, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a> &amp; SizeAndActions)</td>
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



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>

</div>
</div>

### setScalarAction() {#a27503e2fc0aa8b6c7bf260542a991787}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LegacyLegalizerInfo::setScalarAction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned Opcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned TypeIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a> &amp; SizeAndActions)</td>
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

<p>The <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a> is a representation mapping between all natural numbers and an Action.</p>


<p>The natural number represents the bit size of the <a href="/web-llvm/docs/api/structs/llvm/instraspect">InstrAspect</a>. For example, for a target with native support for 32-bit and 64-bit additions, you'd express that as: setScalarAction(G_ADD, 0, {{1, WidenScalar}, // bit sizes [ 1, 31[ {32, Legal}, // bit sizes [32, 33[ {33, WidenScalar}, // bit sizes [33, 64[ {64, Legal}, // bit sizes [64, 65[ {65, NarrowScalar} // bit sizes [65, +inf[ }); It may be that only 64-bit pointers are supported on your target: setPointerAction(G_PTR_ADD, 0, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>:pointer(1), {{1, Unsupported}, // bit sizes [ 1, 63[ {64, Legal}, // bit sizes [64, 65[ {65, Unsupported}, // bit sizes [65, +inf[ });</p>


<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>

</div>
</div>

### setScalarInVectorAction() {#a8f5972b51d9da92512cabe79063c137a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LegacyLegalizerInfo::setScalarInVectorAction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned Opcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned TypeIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a> &amp; SizeAndActions)</td>
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

<p>If an operation on a given vector type (say &lt;M x iN&gt;) isn't explicitly specified, we proceed in 2 stages.</p>


<p>First we legalize the underlying scalar (so that there's at least one legal vector with that scalar), then we adjust the number of elements in the vector so that it is legal. The desired action in the first step is controlled by this function.</p>


<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>

</div>
</div>

### setVectorNumElementAction() {#a1692cb7a184e2c0eeef39ad958aebe15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LegacyLegalizerInfo::setVectorNumElementAction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned Opcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned TypeIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned ElementSize, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a> &amp; SizeAndActions)</td>
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

<p>See also setScalarInVectorAction.</p>


<p>This function let's you specify the number of elements in a vector that are legal for a legal element size.</p>


<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AddrSpace2PointerActions {#ac48cd2a93be363587df16f9dedcb6ce0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;uint16_t, SmallVector&lt;SizeAndActionsVec, 1&gt; &gt; llvm::LegacyLegalizerInfo::AddrSpace2PointerActions[LastOp - FirstOp+1]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 459 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>

</div>
</div>

### NumElements2Actions {#a7c9088e355cbc383a3f717f423ca85f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;uint16_t, SmallVector&lt;SizeAndActionsVec, 1&gt; &gt; llvm::LegacyLegalizerInfo::NumElements2Actions[LastOp - FirstOp+1]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 461 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>

</div>
</div>

### ScalarActions {#a89f919347be7235b866410df246c2997}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SizeAndActionsVec, 1&gt; llvm::LegacyLegalizerInfo::ScalarActions[LastOp - FirstOp+1]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>

</div>
</div>

### ScalarInVectorActions {#a1c14411f135884296966bbab3df2037b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SizeAndActionsVec, 1&gt; llvm::LegacyLegalizerInfo::ScalarInVectorActions[LastOp - FirstOp+1]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 457 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>

</div>
</div>

### ScalarSizeChangeStrategies {#a9c9d2bece9035055d74af2cfb0af6f40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SizeChangeStrategy, 1&gt; llvm::LegacyLegalizerInfo::ScalarSizeChangeStrategies[LastOp - FirstOp+1]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 450 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>

</div>
</div>

### SpecifiedActions {#aa88153e396b204e46576078a5be105a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;TypeMap, 1&gt; llvm::LegacyLegalizerInfo::SpecifiedActions[LastOp - FirstOp+1]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>

</div>
</div>

### TablesInitialized {#aef462d34443de87942245bb9edaf0b04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LegacyLegalizerInfo::TablesInitialized = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 453 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>

</div>
</div>

### VectorElementSizeChangeStrategies {#ad510aa243a304e2a6de8546c6102d4f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SizeChangeStrategy, 1&gt; llvm::LegacyLegalizerInfo::VectorElementSizeChangeStrategies[LastOp - FirstOp+1]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### decreaseToSmallerTypesAndIncreaseToSmallest() {#a33c90208d9836a0e4a0125ee7c79c3cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegacyLegalizerInfo::SizeAndActionsVec LegacyLegalizerInfo::decreaseToSmallerTypesAndIncreaseToSmallest (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a> &amp; v, <a href="/web-llvm/docs/api/namespaces/llvm/legacylegalizeactions/#ad25716c86372dafbf624b34891685078">LegacyLegalizeActions::LegacyLegalizeAction</a> DecreaseAction, <a href="/web-llvm/docs/api/namespaces/llvm/legacylegalizeactions/#ad25716c86372dafbf624b34891685078">LegacyLegalizeActions::LegacyLegalizeAction</a> IncreaseAction)</td>
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

<p>Helper function to implement many typical <a href="#a2001432f616b09f569d6147c957948c3">SizeChangeStrategy</a> functions.</p>

<p>Declaration at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>, definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legacylegalizerinfo-cpp">LegacyLegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="#af0253e2aef318462a46c42bb6f21c395">narrowToSmallerAndUnsupportedIfTooSmall</a>.</p>

</div>
</div>

### increaseToLargerTypesAndDecreaseToLargest() {#aee07c139c35f051d5306d1c6823dbf0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegacyLegalizerInfo::SizeAndActionsVec LegacyLegalizerInfo::increaseToLargerTypesAndDecreaseToLargest (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a> &amp; v, <a href="/web-llvm/docs/api/namespaces/llvm/legacylegalizeactions/#ad25716c86372dafbf624b34891685078">LegacyLegalizeActions::LegacyLegalizeAction</a> IncreaseAction, <a href="/web-llvm/docs/api/namespaces/llvm/legacylegalizeactions/#ad25716c86372dafbf624b34891685078">LegacyLegalizeActions::LegacyLegalizeAction</a> DecreaseAction)</td>
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

<p>Helper function to implement many typical <a href="#a2001432f616b09f569d6147c957948c3">SizeChangeStrategy</a> functions.</p>

<p>Declaration at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>, definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legacylegalizerinfo-cpp">LegacyLegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="#a619f20a86e6a67eb6ff2b3bd2dd8d67e">moreToWiderTypesAndLessToWidest</a>, <a href="#aebb0c4b04132fb5bad2a70b2854a1b83">unsupportedForDifferentSizes</a>, <a href="#a99b7a87bbd3d7e6dc5c30a0b577d3c76">widenToLargerTypesAndNarrowToLargest</a> and <a href="#a5f1886b5dda7fa57ac21a21f816c9f63">widenToLargerTypesUnsupportedOtherwise</a>.</p>

</div>
</div>

### moreToWiderTypesAndLessToWidest() {#a619f20a86e6a67eb6ff2b3bd2dd8d67e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SizeAndActionsVec llvm::LegacyLegalizerInfo::moreToWiderTypesAndLessToWidest (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a> &amp; v)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A <a href="#a2001432f616b09f569d6147c957948c3">SizeChangeStrategy</a> for the common case where legalization for a particular vector operation consists of having more elements in the vector, to a type that is legal.</p>


<p>Unless there is no such type and then instead it should be legalized towards the widest vector that's still legal. E.g. setAction({G_ADD, LLT::vector(8, 8)}, Legal); setAction({G_ADD, LLT::vector(16, 8)}, Legal); setAction({G_ADD, LLT::vector(2, 32)}, Legal); setAction({G_ADD, LLT::vector(4, 32)}, Legal); setLegalizeVectorElementToDifferentSizeStrategy(
    G_ADD, 0, moreToWiderTypesAndLessToWidest); will result in the following getAction results:</p>


<ul class="doxyList ">
<li>getAction({G_ADD, LLT::vector(8,8)}) returns (Legal, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">vector(8,8)</a>).</li>
<li>getAction({G_ADD, LLT::vector(9,8)}) returns (MoreElements, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">vector(16,8)</a>).</li>
<li>getAction({G_ADD, LLT::vector(8,32)}) returns (FewerElements, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">vector(4,32)</a>).</li>
</ul>

<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>


<p>Reference <a href="#aee07c139c35f051d5306d1c6823dbf0c">increaseToLargerTypesAndDecreaseToLargest</a>.</p>


<p>Referenced by <a href="#a6b586580f1e35e04ae0f3186fadd6594">computeTables</a>.</p>

</div>
</div>

### narrowToSmallerAndUnsupportedIfTooSmall() {#af0253e2aef318462a46c42bb6f21c395}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SizeAndActionsVec llvm::LegacyLegalizerInfo::narrowToSmallerAndUnsupportedIfTooSmall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a> &amp; v)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>


<p>Reference <a href="#a33c90208d9836a0e4a0125ee7c79c3cf">decreaseToSmallerTypesAndIncreaseToSmallest</a>.</p>


<p>Referenced by <a href="#afde846dba0ee6e38964394a16f4aff93">LegacyLegalizerInfo</a>.</p>

</div>
</div>

### needsLegalizingToDifferentSize() {#a862586cb2d3bcdcce916162ebd5dda89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LegacyLegalizerInfo::needsLegalizingToDifferentSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/legacylegalizeactions/#ad25716c86372dafbf624b34891685078">LegacyLegalizeActions::LegacyLegalizeAction</a> Action)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>


<p>Referenced by <a href="#a9ed946c9bc8e7367d6a31582048c8570">setAction</a>.</p>

</div>
</div>

### unsupportedForDifferentSizes() {#aebb0c4b04132fb5bad2a70b2854a1b83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SizeAndActionsVec llvm::LegacyLegalizerInfo::unsupportedForDifferentSizes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a> &amp; v)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A <a href="#a2001432f616b09f569d6147c957948c3">SizeChangeStrategy</a> for the common case where legalization for a particular operation consists of only supporting a specific set of type sizes.</p>


<p>E.g. setAction ({G_DIV, 0, LLT::scalar(32)}, Legal); setAction ({G_DIV, 0, LLT::scalar(64)}, Legal); setLegalizeScalarToDifferentSizeStrategy(
    G_DIV, 0, unsupportedForDifferentSizes); will result in getAction({G_DIV, 0, T}) to return Legal for s32 and s64, and Unsupported for all other scalar types T.</p>


<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>


<p>Reference <a href="#aee07c139c35f051d5306d1c6823dbf0c">increaseToLargerTypesAndDecreaseToLargest</a>.</p>


<p>Referenced by <a href="#a6b586580f1e35e04ae0f3186fadd6594">computeTables</a>.</p>

</div>
</div>

### widenToLargerTypesAndNarrowToLargest() {#a99b7a87bbd3d7e6dc5c30a0b577d3c76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SizeAndActionsVec llvm::LegacyLegalizerInfo::widenToLargerTypesAndNarrowToLargest (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a> &amp; v)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A <a href="#a2001432f616b09f569d6147c957948c3">SizeChangeStrategy</a> for the common case where legalization for a particular operation consists of widening the type to a large legal type, unless there is no such type and then instead it should be narrowed to the largest legal type.</p>

<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aee07c139c35f051d5306d1c6823dbf0c">increaseToLargerTypesAndDecreaseToLargest</a>.</p>


<p>Referenced by <a href="#afde846dba0ee6e38964394a16f4aff93">LegacyLegalizerInfo</a>.</p>

</div>
</div>

### widenToLargerTypesUnsupportedOtherwise() {#a5f1886b5dda7fa57ac21a21f816c9f63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SizeAndActionsVec llvm::LegacyLegalizerInfo::widenToLargerTypesUnsupportedOtherwise (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a> &amp; v)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>


<p>Reference <a href="#aee07c139c35f051d5306d1c6823dbf0c">increaseToLargerTypesAndDecreaseToLargest</a>.</p>


<p>Referenced by <a href="#afde846dba0ee6e38964394a16f4aff93">LegacyLegalizerInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### checkFullSizeAndActionsVector() {#aeeffd6a5cbdfa239e8e8d257bc5e0311}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LegacyLegalizerInfo::checkFullSizeAndActionsVector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a> &amp; v)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A full <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a> must cover all bit sizes, i.e.</p>


<p>must start with from size 1.</p>


<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>

</div>
</div>

### checkPartialSizeAndActionsVector() {#a808c33e260b835ffb9adaab321ce7a8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LegacyLegalizerInfo::checkPartialSizeAndActionsVector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a> &amp; v)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A partial <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a> potentially doesn't cover all bit sizes, i.e.</p>


<p>it's OK if it doesn't start from size 1.</p>


<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>

</div>
</div>

### findAction() {#a23b989eb73497f291dd336148324bbf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegacyLegalizerInfo::SizeAndAction LegacyLegalizerInfo::findAction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a703c0ed452aea3693d8fe1441a935d5a">SizeAndActionsVec</a> &amp; Vec, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t Size)</td>
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



<p>Declaration at line 422 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>, definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legacylegalizerinfo-cpp">LegacyLegalizerInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### FirstOp {#a55beac4fedefe00de9c7f4dce5d28f91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int llvm::LegacyLegalizerInfo::FirstOp = TargetOpcode::PRE_ISEL_GENERIC_OPCODE_START</td>
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



<p>Definition at line 443 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>

</div>
</div>

### LastOp {#a42f7b2c652fadf47a21a95c8dbc09b0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int llvm::LegacyLegalizerInfo::LastOp = TargetOpcode::PRE_ISEL_GENERIC_OPCODE_END</td>
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



<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legacylegalizerinfo-cpp">LegacyLegalizerInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
