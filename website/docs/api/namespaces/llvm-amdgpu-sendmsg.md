---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/amdgpu/sendmsg
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `SendMsg` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::AMDGPU::SendMsg { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Id { <a href="#a3a326b706ed4c9caaca05063b47c98db">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Op { <a href="#a8594419a4ddfad2c9a79279c490e466d">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">StreamId : unsigned { <a href="#a27adb1199e74a321ab952df3817c34b4">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13482d4b2972a88f2c54171409662b38">getMsgId</a> (StringRef Name, const MCSubtargetInfo &amp;STI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from a symbolic name for a msg_id to the message portion of the immediate encoding. <a href="#a13482d4b2972a88f2c54171409662b38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8655fccc92bfd13e4aa088235c3810ae">getMsgName</a> (uint64_t Encoding, const MCSubtargetInfo &amp;STI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from an encoding to the symbolic name for a msg_id immediate. <a href="#a8655fccc92bfd13e4aa088235c3810ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12c124d8f7356867fb61ba136446ea9a">getMsgOpId</a> (int64_t MsgId, StringRef Name, const MCSubtargetInfo &amp;STI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from a symbolic name for a sendmsg operation to the operation portion of the immediate encoding. <a href="#a12c124d8f7356867fb61ba136446ea9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aced08746b3f2e6f4c5f878cf4793a78f">getMsgOpName</a> (int64_t MsgId, uint64_t Encoding, const MCSubtargetInfo &amp;STI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from an encoding to the symbolic name for a sendmsg operation. <a href="#aced08746b3f2e6f4c5f878cf4793a78f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad109b50d8a6a4f06c89ab2d9d100b668">getMsgIdMask</a> (const MCSubtargetInfo &amp;STI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73a26b602f2fa523f75a842d92f39d84">isValidMsgId</a> (int64_t MsgId, const MCSubtargetInfo &amp;STI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbb10f56f9659f287512e286ededa608">isValidMsgOp</a> (int64_t MsgId, int64_t OpId, const MCSubtargetInfo &amp;STI, bool Strict)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86dc96b598fc9ba95c907742f806948c">isValidMsgStream</a> (int64_t MsgId, int64_t OpId, int64_t StreamId, const MCSubtargetInfo &amp;STI, bool Strict)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad757192191690aa3a61170e7318e4587">msgRequiresOp</a> (int64_t MsgId, const MCSubtargetInfo &amp;STI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b6a03b3419edd2172b652f66d836f67">msgSupportsStream</a> (int64_t MsgId, int64_t OpId, const MCSubtargetInfo &amp;STI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ab7c1da3520b18c5ef9c4de700615ca">decodeMsg</a> (unsigned Val, uint16_t &amp;MsgId, uint16_t &amp;OpId, uint16_t &amp;StreamId, const MCSubtargetInfo &amp;STI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18b32cda4aa104e7092cd79c9c234401">encodeMsg</a> (uint64_t MsgId, uint64_t OpId, uint64_t StreamId)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/structs/llvm/amdgpu/customoperand">CustomOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0ea7680bb15ce711c6fb1283a85be47">MsgOperands</a>[] = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/structs/llvm/amdgpu/customoperand">CustomOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e5a92f3d6e62bc574a514eadded4b8f">SysMsgOperands</a>[] = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/structs/llvm/amdgpu/customoperand">CustomOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57a90b565ebcb15c4751b143a902be3e">StreamMsgOperands</a>[] = ...</td>
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

## Enumerations

### Id {#a3a326b706ed4c9caaca05063b47c98db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AMDGPU::SendMsg::Id </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_INTERRUPT<a id="a3a326b706ed4c9caaca05063b47c98dba255aa2c1bc0f43a997d8bb4c70c69b60"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_GS_PreGFX11<a id="a3a326b706ed4c9caaca05063b47c98dba91e6a407142e17e4bb3b50e7fe8c87dc"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_GS_DONE_PreGFX11<a id="a3a326b706ed4c9caaca05063b47c98dbac1f00b8c9ee08df6cb5378168b3e3353"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_HS_TESSFACTOR_GFX11Plus<a id="a3a326b706ed4c9caaca05063b47c98dbaf0296978b993b0690ad468f1b7cb3ff6"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_DEALLOC_VGPRS_GFX11Plus<a id="a3a326b706ed4c9caaca05063b47c98dbaa6cd8fa6c5997ec2807bb22563d7d179"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_SAVEWAVE<a id="a3a326b706ed4c9caaca05063b47c98dba6f7a1c7e87cb8d3136d11fcc96f8088e"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_STALL_WAVE_GEN<a id="a3a326b706ed4c9caaca05063b47c98dba6ad87210a2f0215e2422bad72cdaa0ba"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_HALT_WAVES<a id="a3a326b706ed4c9caaca05063b47c98dba292d000ab047ef8e8eec003e773a9a72"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_ORDERED_PS_DONE<a id="a3a326b706ed4c9caaca05063b47c98dbaf513d2cb71146b727194f694811ba5c8"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_EARLY_PRIM_DEALLOC<a id="a3a326b706ed4c9caaca05063b47c98dba774b47a3f5f10dcd9087edee73a0a3e6"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_GS_ALLOC_REQ<a id="a3a326b706ed4c9caaca05063b47c98dbafa31a7b9c2cb4e59a4fefa5a14a184f2"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_GET_DOORBELL<a id="a3a326b706ed4c9caaca05063b47c98dba8835ee4332849edaf126016ce45fbbe8"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_GET_DDID<a id="a3a326b706ed4c9caaca05063b47c98dbaa09f34cfc7b832d86c3b500ac3ff2bcd"></a></td>
<td class="doxyEnumItemDescription"> (= 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_SYSMSG<a id="a3a326b706ed4c9caaca05063b47c98dba2ceaee8363897f7b875879de0e6023f5"></a></td>
<td class="doxyEnumItemDescription"> (= 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_RTN_GET_DOORBELL<a id="a3a326b706ed4c9caaca05063b47c98dbade3e6b1afcdf7295a4e9f63595868aa9"></a></td>
<td class="doxyEnumItemDescription"> (= 128)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_RTN_GET_DDID<a id="a3a326b706ed4c9caaca05063b47c98dba6a7f115c7655e8ef804f3f794c16eaa8"></a></td>
<td class="doxyEnumItemDescription"> (= 129)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_RTN_GET_TMA<a id="a3a326b706ed4c9caaca05063b47c98dba5ce5d667ac83c662ced0edba1a5c5d0e"></a></td>
<td class="doxyEnumItemDescription"> (= 130)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_RTN_GET_REALTIME<a id="a3a326b706ed4c9caaca05063b47c98dba4b08efbe7d0bc71bdf2caa0f4ffda0e5"></a></td>
<td class="doxyEnumItemDescription"> (= 131)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_RTN_SAVE_WAVE<a id="a3a326b706ed4c9caaca05063b47c98dbaf44330e0a0229b459277431fea451c53"></a></td>
<td class="doxyEnumItemDescription"> (= 132)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_RTN_GET_TBA<a id="a3a326b706ed4c9caaca05063b47c98dbaddeda531bfc4ee8145e6b03c1c9899ab"></a></td>
<td class="doxyEnumItemDescription"> (= 133)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_RTN_GET_TBA_TO_PC<a id="a3a326b706ed4c9caaca05063b47c98dbab6eda3e588a1b3a4efad282814a8f346"></a></td>
<td class="doxyEnumItemDescription"> (= 134)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_RTN_GET_SE_AID_ID<a id="a3a326b706ed4c9caaca05063b47c98dba4eb33674766bf8c4213a66d9fe03bf35"></a></td>
<td class="doxyEnumItemDescription"> (= 135)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_MASK_PreGFX11_<a id="a3a326b706ed4c9caaca05063b47c98dba2725a8fe1793af838f1f598cf482dd94"></a></td>
<td class="doxyEnumItemDescription"> (= 0xF)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_MASK_GFX11Plus_<a id="a3a326b706ed4c9caaca05063b47c98dbafee02a9601e27b735e56eecfe6d7f343"></a></td>
<td class="doxyEnumItemDescription"> (= 0xFF)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a>.</p>

</div>
</div>

### Op {#a8594419a4ddfad2c9a79279c490e466d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AMDGPU::SendMsg::Op </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OP_SHIFT_<a id="a8594419a4ddfad2c9a79279c490e466da7b5c643b35728e84a4e3eb771a1c0207"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OP_NONE_<a id="a8594419a4ddfad2c9a79279c490e466da4fd68f389956f8ba7df3b7c868a587f1"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OP_WIDTH_<a id="a8594419a4ddfad2c9a79279c490e466daa66f908f1d48a0640bc0225121f2a423"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OP_MASK_<a id="a8594419a4ddfad2c9a79279c490e466daa619ceec748cf1879249f9eab71bae15"></a></td>
<td class="doxyEnumItemDescription"> (= (((1 &lt;&lt; OP_WIDTH_) - 1) &lt;&lt; OP_SHIFT_))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OP_GS_NOP<a id="a8594419a4ddfad2c9a79279c490e466da162b6acf292531412ed38334f95ed09b"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OP_GS_CUT<a id="a8594419a4ddfad2c9a79279c490e466dad0db183b051e2f768f0d71ca27c4c84a"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OP_GS_EMIT<a id="a8594419a4ddfad2c9a79279c490e466da6437805803847a65ec2c1efaecc99957"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OP_GS_EMIT_CUT<a id="a8594419a4ddfad2c9a79279c490e466da8ca0ee972c9e7b0def6f795dd01fdd37"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OP_GS_FIRST_<a id="a8594419a4ddfad2c9a79279c490e466dae4598eaece72c19bb567c97e57889be8"></a></td>
<td class="doxyEnumItemDescription"> (= OP_GS_NOP)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OP_SYS_ECC_ERR_INTERRUPT<a id="a8594419a4ddfad2c9a79279c490e466da9091d0be41c5447915893a72615d7a0a"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OP_SYS_REG_RD<a id="a8594419a4ddfad2c9a79279c490e466da372caf8924b2283cccb8ca6ca6317b96"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OP_SYS_HOST_TRAP_ACK<a id="a8594419a4ddfad2c9a79279c490e466da2cb1aa7d11a6ca3c3bd5cfad7156e970"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OP_SYS_TTRACE_PC<a id="a8594419a4ddfad2c9a79279c490e466da3b8c53b4d3304f322f9ce7e164bf9e43"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OP_SYS_FIRST_<a id="a8594419a4ddfad2c9a79279c490e466da29baa186d96919b2b0a178c7fc14487f"></a></td>
<td class="doxyEnumItemDescription"> (= OP_SYS_ECC_ERR_INTERRUPT)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 471 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a>.</p>

</div>
</div>

### StreamId {#a27adb1199e74a321ab952df3817c34b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AMDGPU::SendMsg::StreamId : unsigned</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STREAM_ID_NONE_<a id="a27adb1199e74a321ab952df3817c34b4afec82ae1bf5379f91bdbb2ebeb7d73b4"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STREAM_ID_DEFAULT_<a id="a27adb1199e74a321ab952df3817c34b4a4d21b48a8a90e76ae8ad143a48cf15ce"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STREAM_ID_LAST_<a id="a27adb1199e74a321ab952df3817c34b4a4a77076f7d09c69bdb019b177bda4452"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STREAM_ID_FIRST_<a id="a27adb1199e74a321ab952df3817c34b4ad981bdbb0307f5825a6c2a2d540b1df3"></a></td>
<td class="doxyEnumItemDescription"> (= STREAM_ID_DEFAULT_)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STREAM_ID_SHIFT_<a id="a27adb1199e74a321ab952df3817c34b4a84523da702070291b39d0a00f285e6ce"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STREAM_ID_WIDTH_<a id="a27adb1199e74a321ab952df3817c34b4a45ed398ceea75d22a7fc33f59bce1566"></a></td>
<td class="doxyEnumItemDescription"> (=  2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STREAM_ID_MASK_<a id="a27adb1199e74a321ab952df3817c34b4afaa91f0dbc4e45dc42bb7bd4bb64a4ce"></a></td>
<td class="doxyEnumItemDescription"> (= (((1 &lt;&lt; STREAM_ID_WIDTH_) - 1) &lt;&lt; STREAM_ID_SHIFT_))</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### decodeMsg() {#a6ab7c1da3520b18c5ef9c4de700615ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPU::SendMsg::decodeMsg (unsigned Val, uint16_t &amp; MsgId, uint16_t &amp; OpId, uint16_t &amp; StreamId, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2002 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="#ad109b50d8a6a4f06c89ab2d9d100b668">getMsgIdMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa5f3cd2ec6af3adbc143654720b1214b">llvm::AMDGPU::isGFX11Plus</a>, <a href="#a8594419a4ddfad2c9a79279c490e466daa619ceec748cf1879249f9eab71bae15">OP_MASK_</a>, <a href="#a8594419a4ddfad2c9a79279c490e466da7b5c643b35728e84a4e3eb771a1c0207">OP_SHIFT_</a>, <a href="#a27adb1199e74a321ab952df3817c34b4afaa91f0dbc4e45dc42bb7bd4bb64a4ce">STREAM_ID_MASK_</a> and <a href="#a27adb1199e74a321ab952df3817c34b4a84523da702070291b39d0a00f285e6ce">STREAM_ID_SHIFT_</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstprinter/#a74ff02d9e2d701854db9c4f86ddbd3d4">llvm::AMDGPUInstPrinter::printSendMsg</a>.</p>

</div>
</div>

### encodeMsg() {#a18b32cda4aa104e7092cd79c9c234401}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_READNONE uint64_t llvm::AMDGPU::SendMsg::encodeMsg (uint64_t MsgId, uint64_t OpId, uint64_t StreamId)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2014 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="#a8594419a4ddfad2c9a79279c490e466da7b5c643b35728e84a4e3eb771a1c0207">OP_SHIFT_</a> and <a href="#a27adb1199e74a321ab952df3817c34b4a84523da702070291b39d0a00f285e6ce">STREAM_ID_SHIFT_</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a7e026648ec951bc9ce02a0e99e31f583">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSendMsg</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstprinter/#a74ff02d9e2d701854db9c4f86ddbd3d4">llvm::AMDGPUInstPrinter::printSendMsg</a>.</p>

</div>
</div>

### getMsgId() {#a13482d4b2972a88f2c54171409662b38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::AMDGPU::SendMsg::getMsgId (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from a symbolic name for a msg_id to the message portion of the immediate encoding.</p>


<p>A negative return value indicates that the Name was unknown or unsupported on this target.</p>


<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpuasmutils-cpp">AMDGPUAsmUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a2ee72f856a2116efe64cf999f14f277d">llvm::AMDGPU::getEncodingFromOperandTable</a> and <a href="#aa0ea7680bb15ce711c6fb1283a85be47">MsgOperands</a>.</p>

</div>
</div>

### getMsgIdMask() {#ad109b50d8a6a4f06c89ab2d9d100b668}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AMDGPU::SendMsg::getMsgIdMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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



<p>Definition at line 1944 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="#a3a326b706ed4c9caaca05063b47c98dbafee02a9601e27b735e56eecfe6d7f343">ID_MASK_GFX11Plus_</a>, <a href="#a3a326b706ed4c9caaca05063b47c98dba2725a8fe1793af838f1f598cf482dd94">ID_MASK_PreGFX11_</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa5f3cd2ec6af3adbc143654720b1214b">llvm::AMDGPU::isGFX11Plus</a>.</p>


<p>Referenced by <a href="#a6ab7c1da3520b18c5ef9c4de700615ca">decodeMsg</a> and <a href="#a73a26b602f2fa523f75a842d92f39d84">isValidMsgId</a>.</p>

</div>
</div>

### getMsgName() {#a8655fccc92bfd13e4aa088235c3810ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::AMDGPU::SendMsg::getMsgName (uint64_t Encoding, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from an encoding to the symbolic name for a msg_id immediate.</p>


<p>This is doing opposite of <a href="#a13482d4b2972a88f2c54171409662b38">getMsgId()</a>.</p>


<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpuasmutils-cpp">AMDGPUAsmUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a89e90b3784550781a7cb87657a8b417f">llvm::AMDGPU::getNameFromOperandTable</a> and <a href="#aa0ea7680bb15ce711c6fb1283a85be47">MsgOperands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstprinter/#a74ff02d9e2d701854db9c4f86ddbd3d4">llvm::AMDGPUInstPrinter::printSendMsg</a>.</p>

</div>
</div>

### getMsgOpId() {#a12c124d8f7356867fb61ba136446ea9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::AMDGPU::SendMsg::getMsgOpId (int64_t MsgId, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from a symbolic name for a sendmsg operation to the operation portion of the immediate encoding.</p>


<p>A negative return value indicates that the Name was unknown or unsupported on this target.</p>


<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpuasmutils-cpp">AMDGPUAsmUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a2ee72f856a2116efe64cf999f14f277d">llvm::AMDGPU::getEncodingFromOperandTable</a>, <a href="#a3a326b706ed4c9caaca05063b47c98dba2ceaee8363897f7b875879de0e6023f5">ID_SYSMSG</a>, <a href="#a57a90b565ebcb15c4751b143a902be3e">StreamMsgOperands</a> and <a href="#a2e5a92f3d6e62bc574a514eadded4b8f">SysMsgOperands</a>.</p>

</div>
</div>

### getMsgOpName() {#aced08746b3f2e6f4c5f878cf4793a78f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::AMDGPU::SendMsg::getMsgOpName (int64_t MsgId, uint64_t Encoding, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from an encoding to the symbolic name for a sendmsg operation.</p>


<p>This is doing opposite of <a href="#a12c124d8f7356867fb61ba136446ea9a">getMsgOpId()</a>.</p>


<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpuasmutils-cpp">AMDGPUAsmUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a89e90b3784550781a7cb87657a8b417f">llvm::AMDGPU::getNameFromOperandTable</a>, <a href="#a3a326b706ed4c9caaca05063b47c98dba2ceaee8363897f7b875879de0e6023f5">ID_SYSMSG</a>, <a href="#ad757192191690aa3a61170e7318e4587">msgRequiresOp</a>, <a href="#a57a90b565ebcb15c4751b143a902be3e">StreamMsgOperands</a> and <a href="#a2e5a92f3d6e62bc574a514eadded4b8f">SysMsgOperands</a>.</p>


<p>Referenced by <a href="#adbb10f56f9659f287512e286ededa608">isValidMsgOp</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstprinter/#a74ff02d9e2d701854db9c4f86ddbd3d4">llvm::AMDGPUInstPrinter::printSendMsg</a>.</p>

</div>
</div>

### isValidMsgId() {#a73a26b602f2fa523f75a842d92f39d84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_READNONE bool llvm::AMDGPU::SendMsg::isValidMsgId (int64_t MsgId, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1948 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>Reference <a href="#ad109b50d8a6a4f06c89ab2d9d100b668">getMsgIdMask</a>.</p>


<p>Referenced by <a href="#adbb10f56f9659f287512e286ededa608">isValidMsgOp</a>.</p>

</div>
</div>

### isValidMsgOp() {#adbb10f56f9659f287512e286ededa608}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_READNONE bool llvm::AMDGPU::SendMsg::isValidMsgOp (int64_t MsgId, int64_t OpId, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, bool Strict)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1952 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="#aced08746b3f2e6f4c5f878cf4793a78f">getMsgOpName</a>, <a href="#a3a326b706ed4c9caaca05063b47c98dba91e6a407142e17e4bb3b50e7fe8c87dc">ID_GS_PreGFX11</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="#a73a26b602f2fa523f75a842d92f39d84">isValidMsgId</a>, <a href="#ad757192191690aa3a61170e7318e4587">msgRequiresOp</a>, <a href="#a8594419a4ddfad2c9a79279c490e466da162b6acf292531412ed38334f95ed09b">OP_GS_NOP</a> and <a href="#a8594419a4ddfad2c9a79279c490e466da4fd68f389956f8ba7df3b7c868a587f1">OP_NONE_</a>.</p>


<p>Referenced by <a href="#a86dc96b598fc9ba95c907742f806948c">isValidMsgStream</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstprinter/#a74ff02d9e2d701854db9c4f86ddbd3d4">llvm::AMDGPUInstPrinter::printSendMsg</a>.</p>

</div>
</div>

### isValidMsgStream() {#a86dc96b598fc9ba95c907742f806948c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_READNONE bool llvm::AMDGPU::SendMsg::isValidMsgStream (int64_t MsgId, int64_t OpId, int64_t StreamId, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, bool Strict)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1969 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3a326b706ed4c9caaca05063b47c98dbac1f00b8c9ee08df6cb5378168b3e3353">ID_GS_DONE_PreGFX11</a>, <a href="#a3a326b706ed4c9caaca05063b47c98dba91e6a407142e17e4bb3b50e7fe8c87dc">ID_GS_PreGFX11</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa5f3cd2ec6af3adbc143654720b1214b">llvm::AMDGPU::isGFX11Plus</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="#adbb10f56f9659f287512e286ededa608">isValidMsgOp</a>, <a href="#a8594419a4ddfad2c9a79279c490e466da162b6acf292531412ed38334f95ed09b">OP_GS_NOP</a>, <a href="#a27adb1199e74a321ab952df3817c34b4ad981bdbb0307f5825a6c2a2d540b1df3">STREAM_ID_FIRST_</a>, <a href="#a27adb1199e74a321ab952df3817c34b4a4a77076f7d09c69bdb019b177bda4452">STREAM_ID_LAST_</a> and <a href="#a27adb1199e74a321ab952df3817c34b4afec82ae1bf5379f91bdbb2ebeb7d73b4">STREAM_ID_NONE_</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstprinter/#a74ff02d9e2d701854db9c4f86ddbd3d4">llvm::AMDGPUInstPrinter::printSendMsg</a>.</p>

</div>
</div>

### msgRequiresOp() {#ad757192191690aa3a61170e7318e4587}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_READNONE bool llvm::AMDGPU::SendMsg::msgRequiresOp (int64_t MsgId, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1989 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="#a3a326b706ed4c9caaca05063b47c98dbac1f00b8c9ee08df6cb5378168b3e3353">ID_GS_DONE_PreGFX11</a>, <a href="#a3a326b706ed4c9caaca05063b47c98dba91e6a407142e17e4bb3b50e7fe8c87dc">ID_GS_PreGFX11</a>, <a href="#a3a326b706ed4c9caaca05063b47c98dba2ceaee8363897f7b875879de0e6023f5">ID_SYSMSG</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa5f3cd2ec6af3adbc143654720b1214b">llvm::AMDGPU::isGFX11Plus</a>.</p>


<p>Referenced by <a href="#aced08746b3f2e6f4c5f878cf4793a78f">getMsgOpName</a>, <a href="#adbb10f56f9659f287512e286ededa608">isValidMsgOp</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstprinter/#a74ff02d9e2d701854db9c4f86ddbd3d4">llvm::AMDGPUInstPrinter::printSendMsg</a>.</p>

</div>
</div>

### msgSupportsStream() {#a3b6a03b3419edd2172b652f66d836f67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_READNONE bool llvm::AMDGPU::SendMsg::msgSupportsStream (int64_t MsgId, int64_t OpId, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1995 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="#a3a326b706ed4c9caaca05063b47c98dbac1f00b8c9ee08df6cb5378168b3e3353">ID_GS_DONE_PreGFX11</a>, <a href="#a3a326b706ed4c9caaca05063b47c98dba91e6a407142e17e4bb3b50e7fe8c87dc">ID_GS_PreGFX11</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa5f3cd2ec6af3adbc143654720b1214b">llvm::AMDGPU::isGFX11Plus</a> and <a href="#a8594419a4ddfad2c9a79279c490e466da162b6acf292531412ed38334f95ed09b">OP_GS_NOP</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstprinter/#a74ff02d9e2d701854db9c4f86ddbd3d4">llvm::AMDGPUInstPrinter::printSendMsg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### MsgOperands {#aa0ea7680bb15ce711c6fb1283a85be47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CustomOperand llvm::AMDGPU::SendMsg::MsgOperands[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {{""}},
  {{"MSG_INTERRUPT"},           <a href="#a3a326b706ed4c9caaca05063b47c98dba255aa2c1bc0f43a997d8bb4c70c69b60">ID_INTERRUPT</a>},
  {{"MSG_GS"},                  <a href="#a3a326b706ed4c9caaca05063b47c98dba91e6a407142e17e4bb3b50e7fe8c87dc">ID_GS_PreGFX11</a>,             <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa546cb0f0b8bab54a22e1fed554f73ee">isNotGFX11Plus</a>},
  {{"MSG_GS_DONE"},             <a href="#a3a326b706ed4c9caaca05063b47c98dbac1f00b8c9ee08df6cb5378168b3e3353">ID_GS_DONE_PreGFX11</a>,        <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa546cb0f0b8bab54a22e1fed554f73ee">isNotGFX11Plus</a>},
  {{"MSG_SAVEWAVE"},            <a href="#a3a326b706ed4c9caaca05063b47c98dba6f7a1c7e87cb8d3136d11fcc96f8088e">ID_SAVEWAVE</a>,                <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a7081f8bd5a4295981c0f2cf7c3acc9f4">isGFX8_GFX9_GFX10</a>},
  {{"MSG_STALL_WAVE_GEN"},      <a href="#a3a326b706ed4c9caaca05063b47c98dba6ad87210a2f0215e2422bad72cdaa0ba">ID_STALL_WAVE_GEN</a>,          <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af756c02b83dad04df46bd8b15c557d61">isGFX9_GFX10_GFX11</a>},
  {{"MSG_HALT_WAVES"},          <a href="#a3a326b706ed4c9caaca05063b47c98dba292d000ab047ef8e8eec003e773a9a72">ID_HALT_WAVES</a>,              <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af756c02b83dad04df46bd8b15c557d61">isGFX9_GFX10_GFX11</a>},
  {{"MSG_ORDERED_PS_DONE"},     <a href="#a3a326b706ed4c9caaca05063b47c98dbaf513d2cb71146b727194f694811ba5c8">ID_ORDERED_PS_DONE</a>,         <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af8a54ac41ca1a9ea47ddf7586896b792">isGFX9_GFX10</a>},
  {{"MSG_EARLY_PRIM_DEALLOC"},  <a href="#a3a326b706ed4c9caaca05063b47c98dba774b47a3f5f10dcd9087edee73a0a3e6">ID_EARLY_PRIM_DEALLOC</a>,      <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af8a54ac41ca1a9ea47ddf7586896b792">isGFX9_GFX10</a>},
  {{"MSG_GS_ALLOC_REQ"},        <a href="#a3a326b706ed4c9caaca05063b47c98dbafa31a7b9c2cb4e59a4fefa5a14a184f2">ID_GS_ALLOC_REQ</a>,            <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ac251a1b5841022f34ff2791b1ce3b690">isGFX9Plus</a>},
  {{"MSG_GET_DOORBELL"},        <a href="#a3a326b706ed4c9caaca05063b47c98dba8835ee4332849edaf126016ce45fbbe8">ID_GET_DOORBELL</a>,            <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af8a54ac41ca1a9ea47ddf7586896b792">isGFX9_GFX10</a>},
  {{"MSG_GET_DDID"},            <a href="#a3a326b706ed4c9caaca05063b47c98dbaa09f34cfc7b832d86c3b500ac3ff2bcd">ID_GET_DDID</a>,                <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27e5626ce22d0cd09916837dc88b7efe">isGFX10</a>},
  {{"MSG_HS_TESSFACTOR"},       <a href="#a3a326b706ed4c9caaca05063b47c98dbaf0296978b993b0690ad468f1b7cb3ff6">ID_HS_TESSFACTOR_GFX11Plus</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa5f3cd2ec6af3adbc143654720b1214b">isGFX11Plus</a>},
  {{"MSG_DEALLOC_VGPRS"},       <a href="#a3a326b706ed4c9caaca05063b47c98dbaa6cd8fa6c5997ec2807bb22563d7d179">ID_DEALLOC_VGPRS_GFX11Plus</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa5f3cd2ec6af3adbc143654720b1214b">isGFX11Plus</a>},
  {{""}},
  {{"MSG_SYSMSG"},              <a href="#a3a326b706ed4c9caaca05063b47c98dba2ceaee8363897f7b875879de0e6023f5">ID_SYSMSG</a>},
  {{"MSG_RTN_GET_DOORBELL"},    <a href="#a3a326b706ed4c9caaca05063b47c98dbade3e6b1afcdf7295a4e9f63595868aa9">ID_RTN_GET_DOORBELL</a>,        <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa5f3cd2ec6af3adbc143654720b1214b">isGFX11Plus</a>},
  {{"MSG_RTN_GET_DDID"},        <a href="#a3a326b706ed4c9caaca05063b47c98dba6a7f115c7655e8ef804f3f794c16eaa8">ID_RTN_GET_DDID</a>,            <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa5f3cd2ec6af3adbc143654720b1214b">isGFX11Plus</a>},
  {{"MSG_RTN_GET_TMA"},         <a href="#a3a326b706ed4c9caaca05063b47c98dba5ce5d667ac83c662ced0edba1a5c5d0e">ID_RTN_GET_TMA</a>,             <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa5f3cd2ec6af3adbc143654720b1214b">isGFX11Plus</a>},
  {{"MSG_RTN_GET_REALTIME"},    <a href="#a3a326b706ed4c9caaca05063b47c98dba4b08efbe7d0bc71bdf2caa0f4ffda0e5">ID_RTN_GET_REALTIME</a>,        <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa5f3cd2ec6af3adbc143654720b1214b">isGFX11Plus</a>},
  {{"MSG_RTN_SAVE_WAVE"},       <a href="#a3a326b706ed4c9caaca05063b47c98dbaf44330e0a0229b459277431fea451c53">ID_RTN_SAVE_WAVE</a>,           <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa5f3cd2ec6af3adbc143654720b1214b">isGFX11Plus</a>},
  {{"MSG_RTN_GET_TBA"},         <a href="#a3a326b706ed4c9caaca05063b47c98dbaddeda531bfc4ee8145e6b03c1c9899ab">ID_RTN_GET_TBA</a>,             <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa5f3cd2ec6af3adbc143654720b1214b">isGFX11Plus</a>},
  {{"MSG_RTN_GET_TBA_TO_PC"},   <a href="#a3a326b706ed4c9caaca05063b47c98dbab6eda3e588a1b3a4efad282814a8f346">ID_RTN_GET_TBA_TO_PC</a>,       <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa5f3cd2ec6af3adbc143654720b1214b">isGFX11Plus</a>},
  {{"MSG_RTN_GET_SE_AID_ID"},   <a href="#a3a326b706ed4c9caaca05063b47c98dba4eb33674766bf8c4213a66d9fe03bf35">ID_RTN_GET_SE_AID_ID</a>,       <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a318d59d6a50364a460b64bb7ad1f17d0">isGFX12Plus</a>},
}
</div>
</dd>
</dl>

<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpuasmutils-cpp">AMDGPUAsmUtils.cpp</a>.</p>


<p>Referenced by <a href="#a13482d4b2972a88f2c54171409662b38">getMsgId</a> and <a href="#a8655fccc92bfd13e4aa088235c3810ae">getMsgName</a>.</p>

</div>
</div>

### StreamMsgOperands {#a57a90b565ebcb15c4751b143a902be3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CustomOperand llvm::AMDGPU::SendMsg::StreamMsgOperands[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {{"GS_OP_NOP"},       <a href="#a8594419a4ddfad2c9a79279c490e466da162b6acf292531412ed38334f95ed09b">OP_GS_NOP</a>},
  {{"GS_OP_CUT"},       <a href="#a8594419a4ddfad2c9a79279c490e466dad0db183b051e2f768f0d71ca27c4c84a">OP_GS_CUT</a>},
  {{"GS_OP_EMIT"},      <a href="#a8594419a4ddfad2c9a79279c490e466da6437805803847a65ec2c1efaecc99957">OP_GS_EMIT</a>},
  {{"GS_OP_EMIT_CUT"},  <a href="#a8594419a4ddfad2c9a79279c490e466da8ca0ee972c9e7b0def6f795dd01fdd37">OP_GS_EMIT_CUT</a>},
}
</div>
</dd>
</dl>

<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpuasmutils-cpp">AMDGPUAsmUtils.cpp</a>.</p>


<p>Referenced by <a href="#a12c124d8f7356867fb61ba136446ea9a">getMsgOpId</a> and <a href="#aced08746b3f2e6f4c5f878cf4793a78f">getMsgOpName</a>.</p>

</div>
</div>

### SysMsgOperands {#a2e5a92f3d6e62bc574a514eadded4b8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CustomOperand llvm::AMDGPU::SendMsg::SysMsgOperands[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {{""}},
  {{"SYSMSG_OP_ECC_ERR_INTERRUPT"},  <a href="#a8594419a4ddfad2c9a79279c490e466da9091d0be41c5447915893a72615d7a0a">OP_SYS_ECC_ERR_INTERRUPT</a>},
  {{"SYSMSG_OP_REG_RD"},             <a href="#a8594419a4ddfad2c9a79279c490e466da372caf8924b2283cccb8ca6ca6317b96">OP_SYS_REG_RD</a>},
  {{"SYSMSG_OP_HOST_TRAP_ACK"},      <a href="#a8594419a4ddfad2c9a79279c490e466da2cb1aa7d11a6ca3c3bd5cfad7156e970">OP_SYS_HOST_TRAP_ACK</a>,      <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab9f1a30ac82f16955847bd30070c7357">isNotGFX9Plus</a>},
  {{"SYSMSG_OP_TTRACE_PC"},          <a href="#a8594419a4ddfad2c9a79279c490e466da3b8c53b4d3304f322f9ce7e164bf9e43">OP_SYS_TTRACE_PC</a>},
}
</div>
</dd>
</dl>

<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpuasmutils-cpp">AMDGPUAsmUtils.cpp</a>.</p>


<p>Referenced by <a href="#a12c124d8f7356867fb61ba136446ea9a">getMsgOpId</a> and <a href="#aced08746b3f2e6f4c5f878cf4793a78f">getMsgOpName</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpuasmutils-cpp">AMDGPUAsmUtils.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
