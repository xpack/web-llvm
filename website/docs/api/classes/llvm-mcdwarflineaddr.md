---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcdwarflineaddr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MCDwarfLineAddr` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MCDwarfLineAddr { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">llvm/MC/MCDwarf.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0f19d1d97309d2c250054dae4569622">encode</a> (MCContext &amp;Context, MCDwarfLineTableParams Params, int64_t LineDelta, uint64_t AddrDelta, SmallVectorImpl&lt; char &gt; &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Utility function to encode a Dwarf pair of LineDelta and AddrDeltas. <a href="#ae0f19d1d97309d2c250054dae4569622">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a002e20f504cfcef55b84c4c7e5b2be68">Emit</a> (MCStreamer *MCOS, MCDwarfLineTableParams Params, int64_t LineDelta, uint64_t AddrDelta)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Utility function to emit the encoding to a streamer. <a href="#a002e20f504cfcef55b84c4c7e5b2be68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### Emit() {#a002e20f504cfcef55b84c4c7e5b2be68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCDwarfLineAddr::Emit (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> * MCOS, <a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableparams">MCDwarfLineTableParams</a> Params, int64_t LineDelta, uint64_t AddrDelta)</td>
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

<p>Utility function to emit the encoding to a streamer.</p>

<p>Declaration at line 456 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>, definition at line 701 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#af94e84eca402017c9ce57b7b4c4104e3">llvm::MCStreamer::emitBytes</a>, <a href="#ae0f19d1d97309d2c250054dae4569622">encode</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a79809d23367b5aafd98b71ae67a0d2d4">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitDwarfAdvanceLineAddr</a> and <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectstreamer-cpp/#adad943b5b84c1f1ebef9a2c4e7318052">emitDwarfSetLineAddr</a>.</p>

</div>
</div>

### encode() {#ae0f19d1d97309d2c250054dae4569622}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCDwarfLineAddr::encode (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Context, <a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableparams">MCDwarfLineTableParams</a> Params, int64_t LineDelta, uint64_t AddrDelta, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; OS)</td>
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

<p>Utility function to encode a Dwarf pair of LineDelta and AddrDeltas.</p>

<p>Declaration at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>, definition at line 716 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableparams/#afddded28f79b1eccb3a948a4bdd0f6a3">llvm::MCDwarfLineTableParams::DWARF2LineBase</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableparams/#aa098ab41af3f8cee8b1939003d55a776">llvm::MCDwarfLineTableParams::DWARF2LineOpcodeBase</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableparams/#ac75e30002379b9f61625bc8d2b4b1919">llvm::MCDwarfLineTableParams::DWARF2LineRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac21006e81ffbbc79e8e51e44f7878053">llvm::encodeSLEB128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#ad0d744f05898e32d01f73f8af3cd2071">INT64_MAX</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a3ce1bed1bbcf6373d4bedd7ef53477f2">ScaleAddrDelta</a> and <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a1a45bf6d0fbef0afa6304a0a90d4cc7c">SpecialAddr</a>.</p>


<p>Referenced by <a href="#a002e20f504cfcef55b84c4c7e5b2be68">Emit</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
