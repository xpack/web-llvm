---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/mcdwarfframeinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `MCDwarfFrameInfo` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::MCDwarfFrameInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">llvm/MC/MCDwarf.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39ce4e91dce930ce6317cf7157ce6464">MCDwarfFrameInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca389e403a6d34682ba72a9120c3f83c">Begin</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a28a7bafd6aef6062f253778813f217">End</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c371b9d29a2da49e836e29ac73b359b">Personality</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedbfd737ebf204c167470729f2ec0042">Lsda</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction">MCCFIInstruction</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad678a6927d2876e9eb5fba111da70584">Instructions</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc4f9cad50cf910f508ef213f26d539e">CurrentCfaRegister</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a932960bf69710f1094b4e6d8fc5d627c">PersonalityEncoding</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8d9360321fbcbdb17515c2d227f75fa">LsdaEncoding</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba0776b50178c515003db66042e730e6">CompactUnwindEncoding</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8711bbf8d91d469855854590ab674e15">IsSignalFrame</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ddd4c949a45e7d0f88d8661584d6798">IsSimple</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac75bed23a3d4eac190a5e9f4c1c7abc0">RAReg</a> = static_cast&lt;unsigned&gt;(INT_MAX)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a433d11c67a32132351c98de2b8065284">IsBKeyFrame</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad80999a465c92131481073b2fce9d5ed">IsMTETaggedFrame</a> = false</td>
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


<p>Definition at line 759 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MCDwarfFrameInfo() {#a39ce4e91dce930ce6317cf7157ce6464}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCDwarfFrameInfo::MCDwarfFrameInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 760 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Begin {#aca389e403a6d34682ba72a9120c3f83c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* llvm::MCDwarfFrameInfo::Begin = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 762 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipselfstreamer/#a4048731284da0f5852f82e4032569370">llvm::MipsELFStreamer::emitCFIStartProcImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a53a38280a7cf030655d4ad153dcf8cc1">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCompactUnwind</a> and <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a3d9503972de494ac87e3025a25bbbbb6">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitFDE</a>.</p>

</div>
</div>

### CompactUnwindEncoding {#aba0776b50178c515003db66042e730e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::MCDwarfFrameInfo::CompactUnwindEncoding = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 770 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcdwarfframeemitter/#a6db5460aea8388ba1f9bec6c47f6c741">llvm::MCDwarfFrameEmitter::Emit</a> and <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a53a38280a7cf030655d4ad153dcf8cc1">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCompactUnwind</a>.</p>

</div>
</div>

### CurrentCfaRegister {#afc4f9cad50cf910f508ef213f26d539e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCDwarfFrameInfo::CurrentCfaRegister = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 767 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a06d947eb9b24c3c09aec7dae8b242d36">llvm::MCStreamer::emitCFIDefCfa</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#aa3cb8bdbc2ba4f13b85ae876c8db72c8">llvm::MCStreamer::emitCFIDefCfaRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#afd9cd40e1c8cda6d287b38bbbc4a65dd">llvm::MCStreamer::emitCFILLVMDefAspaceCfa</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a11eed8ef0a19a4cd80fc06a8488061fd">llvm::MCStreamer::emitCFIStartProc</a>.</p>

</div>
</div>

### End {#a4a28a7bafd6aef6062f253778813f217}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* llvm::MCDwarfFrameInfo::End = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 763 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#aa32eb827df6b7817d6c2ab91c47ad1e4">llvm::MCStreamer::emitCFIEndProcImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mipselfstreamer/#a7a47959229fe5c4aadbc877fc12e4ba6">llvm::MipsELFStreamer::emitCFIEndProcImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a53a38280a7cf030655d4ad153dcf8cc1">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCompactUnwind</a> and <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a3d9503972de494ac87e3025a25bbbbb6">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitFDE</a>.</p>

</div>
</div>

### Instructions {#ad678a6927d2876e9eb5fba111da70584}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MCCFIInstruction&gt; llvm::MCDwarfFrameInfo::Instructions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 766 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ab98cdd0259874847cd346b396f87ed29">llvm::MCStreamer::emitCFIAdjustCfaOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a06d947eb9b24c3c09aec7dae8b242d36">llvm::MCStreamer::emitCFIDefCfa</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ad00e491df6ac397c2836f4823486b814">llvm::MCStreamer::emitCFIDefCfaOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#aa3cb8bdbc2ba4f13b85ae876c8db72c8">llvm::MCStreamer::emitCFIDefCfaRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7f85a7656080c1cece6d55421409c2ac">llvm::MCStreamer::emitCFIEscape</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a00b5e27ba702e289d1355d83634496e8">llvm::MCStreamer::emitCFIGnuArgsSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#afd9cd40e1c8cda6d287b38bbbc4a65dd">llvm::MCStreamer::emitCFILLVMDefAspaceCfa</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a5e417903a64e0e2e03a881cc22988c03">llvm::MCStreamer::emitCFINegateRAState</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a2f9a65946cfd95e5fee5434be8061fba">llvm::MCStreamer::emitCFINegateRAStateWithPC</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#acc89f9e1b110cc78d0b3782c7169fee3">llvm::MCStreamer::emitCFIOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#aa640c4cba0755dc19a91bdb98fec5998">llvm::MCStreamer::emitCFIRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ac21d03105248455242c40d1b663dfea1">llvm::MCStreamer::emitCFIRelOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a861747a0f3a48a53fdff7bdc6c1856d8">llvm::MCStreamer::emitCFIRememberState</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#af5f8c58b6d8f44d96b1f1d02ba7af4af">llvm::MCStreamer::emitCFIRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#aca048ea2881b4d098c005349f99bab62">llvm::MCStreamer::emitCFIRestoreState</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a30e73886a8c818640b69a5ca9dfe3b60">llvm::MCStreamer::emitCFISameValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a52d332cc8f6e4738d2b9c3f78ab28f1a">llvm::MCStreamer::emitCFIUndefined</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ae0930d72d21ce9df1f3d41b685411bd9">llvm::MCStreamer::emitCFIValOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a396af4f92c9743bcf60f86474c7ebadf">llvm::MCStreamer::emitCFIWindowSave</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a3d9503972de494ac87e3025a25bbbbb6">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitFDE</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmbackend-cpp-/darwinaarch64asmbackend/#a26e5b6731c22761e5c4e7abe1dc13a21">anonymous{AArch64AsmBackend.cpp}::DarwinAArch64AsmBackend::generateCompactUnwindEncoding</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/darwinx86asmbackend/#a0423592792c76af41a0db8233e30bf45">anonymous{X86AsmBackend.cpp}::DarwinX86AsmBackend::generateCompactUnwindEncoding</a> and <a href="/web-llvm/docs/api/classes/llvm/armasmbackenddarwin/#a0734a023f800982945eec5cff4e9fb22">llvm::ARMAsmBackendDarwin::generateCompactUnwindEncoding</a>.</p>

</div>
</div>

### IsBKeyFrame {#a433d11c67a32132351c98de2b8065284}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCDwarfFrameInfo::IsBKeyFrame = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 774 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a18b9227cee7d28b311e88626e31470b3">llvm::MCStreamer::emitCFIBKeyFrame</a> and <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a06884c9e11f3d8bb503abfb8dc03586b">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCIE</a>.</p>

</div>
</div>

### IsMTETaggedFrame {#ad80999a465c92131481073b2fce9d5ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCDwarfFrameInfo::IsMTETaggedFrame = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 775 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a6c8bdd2a81dd6498072971ec263d61d3">llvm::MCStreamer::emitCFIMTETaggedFrame</a> and <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a06884c9e11f3d8bb503abfb8dc03586b">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCIE</a>.</p>

</div>
</div>

### IsSignalFrame {#a8711bbf8d91d469855854590ab674e15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCDwarfFrameInfo::IsSignalFrame = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 771 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#aee53d30c51fc0e9ca7c57c52a95da789">llvm::MCStreamer::emitCFISignalFrame</a> and <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a06884c9e11f3d8bb503abfb8dc03586b">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCIE</a>.</p>

</div>
</div>

### IsSimple {#a1ddd4c949a45e7d0f88d8661584d6798}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCDwarfFrameInfo::IsSimple = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 772 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a11eed8ef0a19a4cd80fc06a8488061fd">llvm::MCStreamer::emitCFIStartProc</a> and <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a06884c9e11f3d8bb503abfb8dc03586b">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCIE</a>.</p>

</div>
</div>

### Lsda {#aedbfd737ebf204c167470729f2ec0042}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbol* llvm::MCDwarfFrameInfo::Lsda = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 765 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a5fdf26af0fa16c740221a0f1492652da">llvm::MCStreamer::emitCFILsda</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a06884c9e11f3d8bb503abfb8dc03586b">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCIE</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a53a38280a7cf030655d4ad153dcf8cc1">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCompactUnwind</a> and <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a3d9503972de494ac87e3025a25bbbbb6">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitFDE</a>.</p>

</div>
</div>

### LsdaEncoding {#ad8d9360321fbcbdb17515c2d227f75fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCDwarfFrameInfo::LsdaEncoding = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 769 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a5fdf26af0fa16c740221a0f1492652da">llvm::MCStreamer::emitCFILsda</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a06884c9e11f3d8bb503abfb8dc03586b">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCIE</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a53a38280a7cf030655d4ad153dcf8cc1">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCompactUnwind</a> and <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a3d9503972de494ac87e3025a25bbbbb6">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitFDE</a>.</p>

</div>
</div>

### Personality {#a3c371b9d29a2da49e836e29ac73b359b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbol* llvm::MCDwarfFrameInfo::Personality = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 764 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a3721196eca9702a79c55577d867c8535">llvm::MCStreamer::emitCFIPersonality</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a06884c9e11f3d8bb503abfb8dc03586b">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCIE</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a53a38280a7cf030655d4ad153dcf8cc1">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCompactUnwind</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmbackend-cpp-/darwinaarch64asmbackend/#a26e5b6731c22761e5c4e7abe1dc13a21">anonymous{AArch64AsmBackend.cpp}::DarwinAArch64AsmBackend::generateCompactUnwindEncoding</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/darwinx86asmbackend/#a0423592792c76af41a0db8233e30bf45">anonymous{X86AsmBackend.cpp}::DarwinX86AsmBackend::generateCompactUnwindEncoding</a> and <a href="/web-llvm/docs/api/classes/llvm/armasmbackenddarwin/#a0734a023f800982945eec5cff4e9fb22">llvm::ARMAsmBackendDarwin::generateCompactUnwindEncoding</a>.</p>

</div>
</div>

### PersonalityEncoding {#a932960bf69710f1094b4e6d8fc5d627c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCDwarfFrameInfo::PersonalityEncoding = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 768 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a3721196eca9702a79c55577d867c8535">llvm::MCStreamer::emitCFIPersonality</a> and <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a06884c9e11f3d8bb503abfb8dc03586b">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCIE</a>.</p>

</div>
</div>

### RAReg {#ac75bed23a3d4eac190a5e9f4c1c7abc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCDwarfFrameInfo::RAReg = static_cast&lt;unsigned&gt;(INT_MAX)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 773 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a35cbb2583bd074641c370112dc50615c">llvm::MCStreamer::emitCFIReturnColumn</a> and <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a06884c9e11f3d8bb503abfb8dc03586b">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCIE</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
