---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-simpleremoteepcutils-cpp-/fdmsgheader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `FDMsgHeader` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{SimpleRemoteEPCUtils.cpp}::FDMsgHeader { ... }
</div>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81a6d53d961934bddd156cb6c2e8c571">MsgSizeOffset</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b221cf358d489fe4998b745ad156c6a">OpCOffset</a> = <a href="#a81a6d53d961934bddd156cb6c2e8c571">MsgSizeOffset</a> + sizeof(uint64_t)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5246118d0f6d75ffdf49a042154520fb">SeqNoOffset</a> = <a href="#a0b221cf358d489fe4998b745ad156c6a">OpCOffset</a> + sizeof(uint64_t)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cc8044990b03feadba22ab8164bc3f3">TagAddrOffset</a> = <a href="#a5246118d0f6d75ffdf49a042154520fb">SeqNoOffset</a> + sizeof(uint64_t)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3351496f61747a15f76b763d58d78323">Size</a> = <a href="#a5cc8044990b03feadba22ab8164bc3f3">TagAddrOffset</a> + sizeof(uint64_t)</td>
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


<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/simpleremoteepcutils-cpp">SimpleRemoteEPCUtils.cpp</a>.</p>


<div class="doxySectionDef">

## Public Static Attributes

### MsgSizeOffset {#a81a6d53d961934bddd156cb6c2e8c571}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SimpleRemoteEPCUtils.cpp}::FDMsgHeader::MsgSizeOffset = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/simpleremoteepcutils-cpp">SimpleRemoteEPCUtils.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/fdsimpleremoteepctransport/#ac70eafd527c133cbc9773c9237179b17">llvm::orc::FDSimpleRemoteEPCTransport::sendMessage</a>.</p>

</div>
</div>

### OpCOffset {#a0b221cf358d489fe4998b745ad156c6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SimpleRemoteEPCUtils.cpp}::FDMsgHeader::OpCOffset = <a href="#a81a6d53d961934bddd156cb6c2e8c571">MsgSizeOffset</a> + sizeof(uint64_t)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/simpleremoteepcutils-cpp">SimpleRemoteEPCUtils.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/fdsimpleremoteepctransport/#ac70eafd527c133cbc9773c9237179b17">llvm::orc::FDSimpleRemoteEPCTransport::sendMessage</a>.</p>

</div>
</div>

### SeqNoOffset {#a5246118d0f6d75ffdf49a042154520fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SimpleRemoteEPCUtils.cpp}::FDMsgHeader::SeqNoOffset = <a href="#a0b221cf358d489fe4998b745ad156c6a">OpCOffset</a> + sizeof(uint64_t)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/simpleremoteepcutils-cpp">SimpleRemoteEPCUtils.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/fdsimpleremoteepctransport/#ac70eafd527c133cbc9773c9237179b17">llvm::orc::FDSimpleRemoteEPCTransport::sendMessage</a>.</p>

</div>
</div>

### Size {#a3351496f61747a15f76b763d58d78323}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SimpleRemoteEPCUtils.cpp}::FDMsgHeader::Size = <a href="#a5cc8044990b03feadba22ab8164bc3f3">TagAddrOffset</a> + sizeof(uint64_t)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/simpleremoteepcutils-cpp">SimpleRemoteEPCUtils.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/fdsimpleremoteepctransport/#ac70eafd527c133cbc9773c9237179b17">llvm::orc::FDSimpleRemoteEPCTransport::sendMessage</a>.</p>

</div>
</div>

### TagAddrOffset {#a5cc8044990b03feadba22ab8164bc3f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SimpleRemoteEPCUtils.cpp}::FDMsgHeader::TagAddrOffset = <a href="#a5246118d0f6d75ffdf49a042154520fb">SeqNoOffset</a> + sizeof(uint64_t)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/simpleremoteepcutils-cpp">SimpleRemoteEPCUtils.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/fdsimpleremoteepctransport/#ac70eafd527c133cbc9773c9237179b17">llvm::orc::FDSimpleRemoteEPCTransport::sendMessage</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/simpleremoteepcutils-cpp">SimpleRemoteEPCUtils.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
