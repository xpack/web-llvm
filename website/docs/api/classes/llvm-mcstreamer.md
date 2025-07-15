---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcstreamer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCStreamer` Class Reference

<p>Streaming machine code generation interface. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MCStreamer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">llvm/MC/MCStreamer.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer">MCAsmStreamer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-mcnullstreamer-cpp-/mcnullstreamer">MCNullStreamer</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/recordstreamer">RecordStreamer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22fe36f1318b43e947d6f5e8cf1bb4af">MCStreamer</a> (const MCStreamer &amp;)=delete</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91d427d805fbdbcddd4d6381bee35ba6">MCStreamer</a> (MCContext &amp;Ctx)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c0b98babb5ae78e83a3adffb116ea75">~MCStreamer</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae73a85a70a248f1d7ad6ba6fc749b7e3">operator=</a> (const MCStreamer &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb2fc7b7b30a601f94f8f5a6297ec68f">visitUsedExpr</a> (const MCExpr &amp;Expr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a105fc9d2996ff696bd68db1f9ebce6bb">visitUsedSymbol</a> (const MCSymbol &amp;Sym)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5412ac22218512db53d55eea56777aac">setTargetStreamer</a> (MCTargetStreamer *TS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e1714ce6e48aa49f01169ea3e517661">setStartTokLocPtr</a> (const SMLoc *Loc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62c3894a85886838f32d8d23e003478f">getStartTokLoc</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86cecbfb6ca34c4a8b0dc349949fbba2">reset</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>State management. <a href="#a86cecbfb6ca34c4a8b0dc349949fbba2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61c979932b890df773ce75013b76708b">getContext</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ef5ffac1974b503c8ec1b3172d37335">getAssemblerPtr</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab55c46222643a36d7e303f801ca720f1">setUseAssemblerInfoForParsing</a> (bool v)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ac5e1dcbd59f1f878ea94e03d483e50">getUseAssemblerInfoForParsing</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer">MCTargetStreamer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a901607e60c20148ae701b6e8f43b4647">getTargetStreamer</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84e19f7283c7e529b0762e1fdd4ba8b0">setAllowAutoPadding</a> (bool v)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe6e1da30a7eb4225a89e27462ff6338">getAllowAutoPadding</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03e59500b09326087aab0f3aa60a1491">emitLineTableLabel</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When emitting an object file, create and emit a real label. <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo">WinEH::FrameInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6673eacba606285dd63d8d1669054bd">EnsureValidWinFrameInfo</a> (SMLoc Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve the current frame info if one is available and it is not yet closed. <a href="#ac6673eacba606285dd63d8d1669054bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99c3f13b3e8fb365914125cd27c77ea3">getNumFrameInfos</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo">MCDwarfFrameInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe60a8e0d089fcaec6a2a453f8966105">getDwarfFrameInfos</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29f026c7466847a38f5ca916d666af96">hasUnfinishedDwarfFrameInfo</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29cea003318c9d843e3dd2072ad87e80">getNumWinFrameInfos</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo">WinEH::FrameInfo</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd501c2b93172880cbeaf7e3ab0cc49d">getWinFrameInfos</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b01021cc37aeebcdb85e5e9f955507c">generateCompactUnwindEncodings</a> (MCAsmBackend *MAB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc44b704cc4e507e33afd71ff56a9181">emitFileDirective</a> (StringRef Filename)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Switch to a new logical file. <a href="#adc44b704cc4e507e33afd71ff56a9181">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81434cde0572b8653405b032c0bdf6f0">emitFileDirective</a> (StringRef Filename, StringRef CompilerVersion, StringRef TimeStamp, StringRef Description)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit ".file assembler diretive with additioal info. <a href="#a81434cde0572b8653405b032c0bdf6f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c40663d4b1c9cdffcf2b82fc498cede">emitIdent</a> (StringRef IdentString)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the "identifiers" directive. <a href="#a7c40663d4b1c9cdffcf2b82fc498cede">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a16115d4363f1c16af9cfcb425ce0d5">emitDwarfFileDirective</a> (unsigned FileNo, StringRef Directory, StringRef Filename, std::optional&lt; MD5::MD5Result &gt; Checksum=std::nullopt, std::optional&lt; StringRef &gt; Source=std::nullopt, unsigned CUID=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Associate a filename with a specified logical file number. <a href="#a4a16115d4363f1c16af9cfcb425ce0d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64d1f7d21e406e2796a9bb5afc3aa31e">tryEmitDwarfFileDirective</a> (unsigned FileNo, StringRef Directory, StringRef Filename, std::optional&lt; MD5::MD5Result &gt; Checksum=std::nullopt, std::optional&lt; StringRef &gt; Source=std::nullopt, unsigned CUID=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Associate a filename with a specified logical file number. <a href="#a64d1f7d21e406e2796a9bb5afc3aa31e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc5440a8bfa25645fa1f58ee11a4394d">emitDwarfFile0Directive</a> (StringRef Directory, StringRef Filename, std::optional&lt; MD5::MD5Result &gt; Checksum, std::optional&lt; StringRef &gt; Source, unsigned CUID=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specify the "root" file of the compilation, using the ".file 0" extension. <a href="#afc5440a8bfa25645fa1f58ee11a4394d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18b9227cee7d28b311e88626e31470b3">emitCFIBKeyFrame</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c8bdd2a81dd6498072971ec263d61d3">emitCFIMTETaggedFrame</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43c1c961a6b54da9fccacdf1cf5fc38f">emitDwarfLocDirective</a> (unsigned FileNo, unsigned Line, unsigned Column, unsigned Flags, unsigned Isa, unsigned Discriminator, StringRef FileName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This implements the DWARF2 '.loc fileno lineno ...' assembler directive. <a href="#a43c1c961a6b54da9fccacdf1cf5fc38f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29df2eab11142e7ff1e8ee74b0cb6322">emitDwarfLocLabelDirective</a> (SMLoc Loc, StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This implements the '.loc_label Name' directive. <a href="#a29df2eab11142e7ff1e8ee74b0cb6322">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33c2e7b8c7463f2698a3132452cc4d12">emitCVFileDirective</a> (unsigned FileNo, StringRef Filename, ArrayRef&lt; uint8_t &gt; Checksum, unsigned ChecksumKind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Associate a filename with a specified logical file number, and also specify that file's checksum information. <a href="#a33c2e7b8c7463f2698a3132452cc4d12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13ac5fe9bbe382dd5e366288ba91fa43">emitCVFuncIdDirective</a> (unsigned FunctionId)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Introduces a function id for use with .cv_loc. <a href="#a13ac5fe9bbe382dd5e366288ba91fa43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea7cedf9c3df1534425168ee9969871c">emitCVInlineSiteIdDirective</a> (unsigned FunctionId, unsigned IAFunc, unsigned IAFile, unsigned IALine, unsigned IACol, SMLoc Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Introduces an inline call site id for use with .cv_loc. <a href="#aea7cedf9c3df1534425168ee9969871c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4da31215a8966e8ef4d2f1804a0387d">emitCVLocDirective</a> (unsigned FunctionId, unsigned FileNo, unsigned Line, unsigned Column, bool PrologueEnd, bool IsStmt, StringRef FileName, SMLoc Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This implements the CodeView '.cv_loc' assembler directive. <a href="#ad4da31215a8966e8ef4d2f1804a0387d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8afbb0726c0e3513324fc6bf0c8100a1">emitCVLinetableDirective</a> (unsigned FunctionId, const MCSymbol *FnStart, const MCSymbol *FnEnd)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This implements the CodeView '.cv_linetable' assembler directive. <a href="#a8afbb0726c0e3513324fc6bf0c8100a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af64e1dd74b4eb933d72d30513e283c6f">emitCVInlineLinetableDirective</a> (unsigned PrimaryFunctionId, unsigned SourceFileId, unsigned SourceLineNum, const MCSymbol *FnStartSym, const MCSymbol *FnEndSym)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This implements the CodeView '.cv_inline_linetable' assembler directive. <a href="#af64e1dd74b4eb933d72d30513e283c6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbf7790686251736b5aafca21bae3de9">emitCVDefRangeDirective</a> (ArrayRef&lt; std::pair&lt; const MCSymbol *, const MCSymbol * &gt; &gt; Ranges, StringRef FixedSizePortion)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This implements the CodeView '.cv_def_range' assembler directive. <a href="#acbf7790686251736b5aafca21bae3de9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82c73f0d0e0884350e6de0b3928a75e2">emitCVDefRangeDirective</a> (ArrayRef&lt; std::pair&lt; const MCSymbol *, const MCSymbol * &gt; &gt; Ranges, codeview::DefRangeRegisterRelHeader DRHdr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af444716cb34ad63a956c3d68098af874">emitCVDefRangeDirective</a> (ArrayRef&lt; std::pair&lt; const MCSymbol *, const MCSymbol * &gt; &gt; Ranges, codeview::DefRangeSubfieldRegisterHeader DRHdr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a430e37112215f7ce7208db38075768b6">emitCVDefRangeDirective</a> (ArrayRef&lt; std::pair&lt; const MCSymbol *, const MCSymbol * &gt; &gt; Ranges, codeview::DefRangeRegisterHeader DRHdr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac10e5da4db3a744be65230314f023f54">emitCVDefRangeDirective</a> (ArrayRef&lt; std::pair&lt; const MCSymbol *, const MCSymbol * &gt; &gt; Ranges, codeview::DefRangeFramePointerRelHeader DRHdr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4137f731a9b0131b8983a13ec2d1dd4b">emitCVStringTableDirective</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This implements the CodeView '.cv_stringtable' assembler directive. <a href="#a4137f731a9b0131b8983a13ec2d1dd4b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e4def70d1592dd142143f25efa8770e">emitCVFileChecksumsDirective</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This implements the CodeView '.cv_filechecksums' assembler directive. <a href="#a7e4def70d1592dd142143f25efa8770e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58f3b6dec2de08069e7e8978ae878946">emitCVFileChecksumOffsetDirective</a> (unsigned FileNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This implements the CodeView '.cv_filechecksumoffset' assembler directive. <a href="#a58f3b6dec2de08069e7e8978ae878946">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6554e9f25cfa8f02a2d6e382d527f680">emitCVFPOData</a> (const MCSymbol *ProcSym, SMLoc Loc={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This implements the CodeView '.cv_fpo_data' assembler directive. <a href="#a6554e9f25cfa8f02a2d6e382d527f680">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8061d1e593a8f095f0efe3ba0d793531">emitAbsoluteSymbolDiff</a> (const MCSymbol *Hi, const MCSymbol *Lo, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the absolute difference between two symbols. <a href="#a8061d1e593a8f095f0efe3ba0d793531">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f385d04b05418cfd8b1337ac541256c">emitAbsoluteSymbolDiffAsULEB128</a> (const MCSymbol *Hi, const MCSymbol *Lo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the absolute difference between two symbols encoded with ULEB128. <a href="#a4f385d04b05418cfd8b1337ac541256c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa51d3a6818627c9f45797eeef1f1b91c">getDwarfLineTableSymbol</a> (unsigned CUID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e6d59ce0c2235c1e432aefcd928a1e4">emitCFISections</a> (bool EH, bool Debug)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11eed8ef0a19a4cd80fc06a8488061fd">emitCFIStartProc</a> (bool IsSimple, SMLoc Loc=SMLoc())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9b56ca50fc9b458d7c7b557addaf56e">emitCFIEndProc</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06d947eb9b24c3c09aec7dae8b242d36">emitCFIDefCfa</a> (int64_t Register, int64_t Offset, SMLoc Loc={})</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad00e491df6ac397c2836f4823486b814">emitCFIDefCfaOffset</a> (int64_t Offset, SMLoc Loc={})</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3cb8bdbc2ba4f13b85ae876c8db72c8">emitCFIDefCfaRegister</a> (int64_t Register, SMLoc Loc={})</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd9cd40e1c8cda6d287b38bbbc4a65dd">emitCFILLVMDefAspaceCfa</a> (int64_t Register, int64_t Offset, int64_t AddressSpace, SMLoc Loc={})</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc89f9e1b110cc78d0b3782c7169fee3">emitCFIOffset</a> (int64_t Register, int64_t Offset, SMLoc Loc={})</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3721196eca9702a79c55577d867c8535">emitCFIPersonality</a> (const MCSymbol *Sym, unsigned Encoding)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fdf26af0fa16c740221a0f1492652da">emitCFILsda</a> (const MCSymbol *Sym, unsigned Encoding)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a861747a0f3a48a53fdff7bdc6c1856d8">emitCFIRememberState</a> (SMLoc Loc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca048ea2881b4d098c005349f99bab62">emitCFIRestoreState</a> (SMLoc Loc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30e73886a8c818640b69a5ca9dfe3b60">emitCFISameValue</a> (int64_t Register, SMLoc Loc={})</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5f8c58b6d8f44d96b1f1d02ba7af4af">emitCFIRestore</a> (int64_t Register, SMLoc Loc={})</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac21d03105248455242c40d1b663dfea1">emitCFIRelOffset</a> (int64_t Register, int64_t Offset, SMLoc Loc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab98cdd0259874847cd346b396f87ed29">emitCFIAdjustCfaOffset</a> (int64_t Adjustment, SMLoc Loc={})</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f85a7656080c1cece6d55421409c2ac">emitCFIEscape</a> (StringRef Values, SMLoc Loc={})</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35cbb2583bd074641c370112dc50615c">emitCFIReturnColumn</a> (int64_t Register)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00b5e27ba702e289d1355d83634496e8">emitCFIGnuArgsSize</a> (int64_t Size, SMLoc Loc={})</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee53d30c51fc0e9ca7c57c52a95da789">emitCFISignalFrame</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52d332cc8f6e4738d2b9c3f78ab28f1a">emitCFIUndefined</a> (int64_t Register, SMLoc Loc={})</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa640c4cba0755dc19a91bdb98fec5998">emitCFIRegister</a> (int64_t Register1, int64_t Register2, SMLoc Loc={})</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a396af4f92c9743bcf60f86474c7ebadf">emitCFIWindowSave</a> (SMLoc Loc={})</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e417903a64e0e2e03a881cc22988c03">emitCFINegateRAState</a> (SMLoc Loc={})</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f9a65946cfd95e5fee5434be8061fba">emitCFINegateRAStateWithPC</a> (SMLoc Loc={})</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a886df281f466da825e86d3db00309322">emitCFILabelDirective</a> (SMLoc Loc, StringRef Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0930d72d21ce9df1f3d41b685411bd9">emitCFIValOffset</a> (int64_t Register, int64_t Offset, SMLoc Loc={})</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7787897c604e14c9e152c890e019e3bf">emitWinCFIStartProc</a> (const MCSymbol *Symbol, SMLoc Loc=SMLoc())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d158c6b4a4302d51fd73aac4075086d">emitWinCFIEndProc</a> (SMLoc Loc=SMLoc())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac38128831e5c5377b98fd32d4f53fc9">emitWinCFIFuncletOrFuncEnd</a> (SMLoc Loc=SMLoc())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is used on platforms, such as Windows on ARM64, that require function or funclet sizes to be emitted in .xdata before the End marker is emitted for the frame. <a href="#aac38128831e5c5377b98fd32d4f53fc9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4abf3b216995cecfbe8fcbc05d5b128">emitWinCFIStartChained</a> (SMLoc Loc=SMLoc())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b6d232a4258f0dd9f16ee5b4f558633">emitWinCFIEndChained</a> (SMLoc Loc=SMLoc())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d0c21ad8ad54697f00aab2c37d77e25">emitWinCFIPushReg</a> (MCRegister Register, SMLoc Loc=SMLoc())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd1f092159870d525f916e3296341d92">emitWinCFISetFrame</a> (MCRegister Register, unsigned Offset, SMLoc Loc=SMLoc())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9bb2bc90c804c28497604ae91e27bd7">emitWinCFIAllocStack</a> (unsigned Size, SMLoc Loc=SMLoc())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a30cc0783819b780c3e357162b90aec">emitWinCFISaveReg</a> (MCRegister Register, unsigned Offset, SMLoc Loc=SMLoc())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5755faab671780e6c1abcaa95f05fe0b">emitWinCFISaveXMM</a> (MCRegister Register, unsigned Offset, SMLoc Loc=SMLoc())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c579bc3d70f8f348c3ddf8224a31220">emitWinCFIPushFrame</a> (bool Code, SMLoc Loc=SMLoc())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b9f4aa69270161dc91d76e3080e6dd2">emitWinCFIEndProlog</a> (SMLoc Loc=SMLoc())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26b51b14a3b7ce5cd6abe0c45872dd60">emitWinEHHandler</a> (const MCSymbol *Sym, bool Unwind, bool Except, SMLoc Loc=SMLoc())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e42517f705e57c03ce078fcac4e8f19">emitWinEHHandlerData</a> (SMLoc Loc=SMLoc())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab742e8ccf28ac1233ea708dcb5decf2e">emitCGProfileEntry</a> (const MCSymbolRefExpr *From, const MCSymbolRefExpr *To, uint64_t Count)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28fee3751eb70ba6768349da24ac79d4">getAssociatedPDataSection</a> (const MCSection *TextSec)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the .pdata section used for the given section. <a href="#a28fee3751eb70ba6768349da24ac79d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7304c7ee4dda7ad7b71afed08c070cd8">getAssociatedXDataSection</a> (const MCSection *TextSec)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the .xdata section used for the given section. <a href="#a7304c7ee4dda7ad7b71afed08c070cd8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c521392edcf2a717c4b64f496e6234a">emitSyntaxDirective</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::pair&lt; bool, std::string &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7504912d9010deac6ce9b8303932ec7d">emitRelocDirective</a> (const MCExpr &amp;Offset, StringRef Name, const MCExpr *Expr, SMLoc Loc, const MCSubtargetInfo &amp;STI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> a relocation described by the .reloc directive. <a href="#a7504912d9010deac6ce9b8303932ec7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03e21d8e0d59e0c54851dfe311057aae">emitAddrsig</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa184a3f234071ff7b4a6b0c6cc15a35">emitAddrsigSym</a> (const MCSymbol *Sym)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e263d122b10b0bcc1bbf6c63202208c">emitInstruction</a> (const MCInst &amp;Inst, const MCSubtargetInfo &amp;STI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the given <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a></span> into the current section. <a href="#a2e263d122b10b0bcc1bbf6c63202208c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab314a3ba8aff83e9e0f49248b37993fe">emitPseudoProbe</a> (uint64_t Guid, uint64_t Index, uint64_t Type, uint64_t Attr, uint64_t Discriminator, const MCPseudoProbeInlineStack &amp;InlineStack, MCSymbol *FnSym)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the a pseudo probe into the current section. <a href="#ab314a3ba8aff83e9e0f49248b37993fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7b71f9cb401d7047b0103b9e60cd89e">emitBundleAlignMode</a> (Align Alignment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the bundle alignment mode from now on in the section. <a href="#af7b71f9cb401d7047b0103b9e60cd89e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28cd349f2853a5ef3208819272623b46">emitBundleLock</a> (bool AlignToEnd)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The following instructions are a bundle-locked group. <a href="#a28cd349f2853a5ef3208819272623b46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a630ed2d1311b8a1549af404488a9de4a">emitBundleUnlock</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Ends a bundle-locked group. <a href="#a630ed2d1311b8a1549af404488a9de4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5807cb4b1f712252faa7d31f9d19815">emitRawText</a> (const Twine &amp;String)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this file is backed by a assembly streamer, this dumps the specified string in the output .s file. <a href="#ae5807cb4b1f712252faa7d31f9d19815">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15061bc6db87126d5031f573f723947d">finishImpl</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Streamer specific finalization. <a href="#a15061bc6db87126d5031f573f723947d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa4bd753124bc1895e37282afa974972">finish</a> (SMLoc EndLoc=SMLoc())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finish emission of machine code. <a href="#afa4bd753124bc1895e37282afa974972">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9453735a9b47b98c973c5bfa4b6a9203">mayHaveInstructions</a> (MCSection &amp;Sec) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acde9e2a59908e8d8a4082d1869f6c08e">maybeEmitDwarf64Mark</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a special value of 0xffffffff if producing 64-bit debugging info. <a href="#acde9e2a59908e8d8a4082d1869f6c08e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a392206962fc4ac790aede10497c7e10b">emitDwarfUnitLength</a> (uint64_t Length, const Twine &amp;Comment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a unit length field. <a href="#a392206962fc4ac790aede10497c7e10b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5bed3c2d5a90c1dc5433064c8f25e2d">emitDwarfUnitLength</a> (const Twine &amp;Prefix, const Twine &amp;Comment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a unit length field. <a href="#ad5bed3c2d5a90c1dc5433064c8f25e2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f1677ad2db297b0202a720530693157">emitDwarfLineStartLabel</a> (MCSymbol *StartSym)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the debug line start label. <a href="#a7f1677ad2db297b0202a720530693157">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7d94558076f3c7f1f94497efe6efc9c">emitDwarfLineEndEntry</a> (MCSection *Section, MCSymbol *LastLabel, MCSymbol *EndLabel=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the debug line end entry. <a href="#ae7d94558076f3c7f1f94497efe6efc9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c0dbc9f490b8fd3f66c6a821684408a">emitDwarfAdvanceLineAddr</a> (int64_t LineDelta, const MCSymbol *LastLabel, const MCSymbol *Label, unsigned PointerSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If targets does not support representing debug line section by .loc/.file directives in assembly output, we need to populate debug line section with raw debug line contents. <a href="#a9c0dbc9f490b8fd3f66c6a821684408a">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd46c84fb0f1eef50c7c7d3b1bc23c87">changeSection</a> (MCSection *, uint32_t)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is called by popSection and switchSection, if the current section changes. <a href="#afd46c84fb0f1eef50c7c7d3b1bc23c87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a578add9dde6ca4352c23f00369d1fa78">emitCFIStartProcImpl</a> (MCDwarfFrameInfo &amp;Frame)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa32eb827df6b7817d6c2ab91c47ad1e4">emitCFIEndProcImpl</a> (MCDwarfFrameInfo &amp;CurFrame)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo">WinEH::FrameInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2c1682a7f094bf9534d3461286aa62f">getCurrentWinFrameInfo</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca120b9543ba85dae180419dbe65e88f">emitWindowsUnwindTables</a> (WinEH::FrameInfo *Frame)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21ea491f02f702c611739ad96e9dcf06">emitWindowsUnwindTables</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8a7a5708bc0202abdf986fd3662d5d4">emitRawTextImpl</a> (StringRef String)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitRawText - If this file is backed by an assembly streamer, this dumps the specified string in the output .s file. <a href="#af8a7a5708bc0202abdf986fd3662d5d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79e4fddfcfc0d5ed30a1b811fcd17a6e">checkCVLocSection</a> (unsigned FuncId, unsigned FileNo, SMLoc Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the .cv_loc directive is in the right section. <a href="#a79e4fddfcfc0d5ed30a1b811fcd17a6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo">MCDwarfFrameInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c7ec503acfcaa9dad0339ebf2acdfd0">getCurrentDwarfFrameInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9299fd6e2b7f540daa945aae967ffe47">CurFrag</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa46f882d5f242b6fa0cf4d9ea864bd0a">Context</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer">MCTargetStreamer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accfcffbe239c8404d6454ebb0b129354">TargetStreamer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo">MCDwarfFrameInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab58083a464ba63d8d1f096baaef5f39e">DwarfFrameInfos</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; size_t, <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * &gt;, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d60b06655802fdb80828097cfcf5bf0">FrameInfoStack</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo">WinEH::FrameInfo</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c635366a7a2eb9b7189919df797b193">WinFrameInfos</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar to DwarfFrameInfos, but for SEH unwind info. <a href="#a2c635366a7a2eb9b7189919df797b193">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo">WinEH::FrameInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9942cf8febde001f2e189fc87006d0e8">CurrentWinFrameInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a177c1fb8aba5d3b1f8040662708b7439">CurrentProcWinFrameInfoStartIndex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#adb25a16cd84d8780ea01fde9d7b6d410">MCSectionSubPair</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb25a16cd84d8780ea01fde9d7b6d410">MCSectionSubPair</a> &gt;, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af944d06b31a30672c9808ff2a5d7bc7c">SectionStack</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is stack of current and previous section values saved by pushSection. <a href="#af944d06b31a30672c9808ff2a5d7bc7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a222bc83759c25005a8086be15e7f9986">StartTokLocPtr</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pointer to the parser's <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> if available. <a href="#a222bc83759c25005a8086be15e7f9986">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade99842665ed05fe305d9a6be88e19f2">NextWinCFIID</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The next unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> to use when creating a WinCFI-related section (.pdata or .xdata). <a href="#ade99842665ed05fe305d9a6be88e19f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7a7a4b080a1678499eb2d4b7d085535">UseAssemblerInfoForParsing</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d15514f56f89f8f20ff140f090cdd62">AllowAutoPadding</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is the assembler allowed to insert padding automatically? <a href="#a3d15514f56f89f8f20ff140f090cdd62">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Assembly File Formatting. Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a491d800694537cdc000beb47d6a3edc3">isVerboseAsm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this streamer supports verbose assembly and if it is enabled. <a href="#a491d800694537cdc000beb47d6a3edc3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4166e064169ce7f347f8e7f6379a8d58">hasRawTextSupport</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this asm streamer supports emitting unformatted text to the .s file with EmitRawText. <a href="#a4166e064169ce7f347f8e7f6379a8d58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a562dcaa292a9033237cd5cf3b78a12bb">isIntegratedAssemblerRequired</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is the integrated assembler required for this streamer to function correctly? <a href="#a562dcaa292a9033237cd5cf3b78a12bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64eafd6bed9f342e423e74a93223135c">AddComment</a> (const Twine &amp;T, bool EOL=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a textual comment. <a href="#a64eafd6bed9f342e423e74a93223135c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23e0190c3735e75eb0199bde954c90ac">getCommentOS</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> that comments can be written to. <a href="#a23e0190c3735e75eb0199bde954c90ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a742a4502a505412b1a9e9b2af3900c49">emitRawComment</a> (const Twine &amp;T, bool TabPrefix=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print T and prefix it with the comment string (normally #) and optionally a tab. <a href="#a742a4502a505412b1a9e9b2af3900c49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64e26e6dc161ab7e00bfd821fb39d3dc">addExplicitComment</a> (const Twine &amp;T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add explicit comment T. <a href="#a64e26e6dc161ab7e00bfd821fb39d3dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac56e340bfb6a2a3aea52b5f3caebdc05">emitExplicitComments</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit added explicit comments. <a href="#ac56e340bfb6a2a3aea52b5f3caebdc05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06efd6f3d736ec481ab81ab2c574bbe6">addBlankLine</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a blank line to a .s file to pretty it up. <a href="#a06efd6f3d736ec481ab81ab2c574bbe6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Symbol & Section Management Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#adb25a16cd84d8780ea01fde9d7b6d410">MCSectionSubPair</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad946e0775ff08232ff6dc1bd9a8ed9bb">getCurrentSection</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the current section that the streamer is emitting code to. <a href="#ad946e0775ff08232ff6dc1bd9a8ed9bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1b3cf074436ef5b527071540e13bd58">getCurrentSectionOnly</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#adb25a16cd84d8780ea01fde9d7b6d410">MCSectionSubPair</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b9a264ab7d0fb2c305ab3d0beb4b74c">getPreviousSection</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the previous section that the streamer is emitting code to. <a href="#a1b9a264ab7d0fb2c305ab3d0beb4b74c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f9393965bc0de69da6236c623f79579">getCurrentFragment</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab095568f88bb32f8a744aaeab0d2c4d0">pushSection</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Save the current and previous section on the section stack. <a href="#ab095568f88bb32f8a744aaeab0d2c4d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a216005880453270b48e5d5d7daeec6d4">popSection</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Restore the current and previous section from the section stack. <a href="#a216005880453270b48e5d5d7daeec6d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4f84451dc4abc997c960d484953b1d2">switchSection</a> (MCSection *Section, uint32_t Subsec=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the current section where code is being emitted to <span class="doxyComputerOutput">Section</span>. <a href="#ac4f84451dc4abc997c960d484953b1d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a179d49e133edc4f825fe798450d24458">switchSection</a> (MCSection *Section, const MCExpr *)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b1a7fa3b559a330d9830ec956a8383">switchSectionNoPrint</a> (MCSection *Section)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar to switchSection, but does not print the section directive. <a href="#a05b1a7fa3b559a330d9830ec956a8383">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a203640eb7873f4e1da4c6acd32c6651c">initSections</a> (bool NoExecStack, const MCSubtargetInfo &amp;STI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the default sections and set the initial one. <a href="#a203640eb7873f4e1da4c6acd32c6651c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4c7cbce4c016b12020711970ace1128">endSection</a> (MCSection *Section)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e2414963f9f6105e4f447d751098763">getMnemonic</a> (const MCInst &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the mnemonic for <span class="doxyComputerOutput">MI</span>, if the streamer has access to a instruction printer and returns an empty string otherwise. <a href="#a7e2414963f9f6105e4f447d751098763">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a822ae1a4f19b7b00a297a100749f9b8a">emitLabel</a> (MCSymbol *Symbol, SMLoc Loc=SMLoc())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a label for <span class="doxyComputerOutput">Symbol</span> into the current section. <a href="#a822ae1a4f19b7b00a297a100749f9b8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb990a888b927298c03825efcbfd6e7a">emitEHSymAttributes</a> (const MCSymbol *Symbol, MCSymbol *EHSymbol)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93568bb65eee43117c3c3a3e1e318bf3">emitAssemblerFlag</a> (MCAssemblerFlag Flag)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Note in the output the specified <span class="doxyComputerOutput">Flag</span>. <a href="#a93568bb65eee43117c3c3a3e1e318bf3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac27396eeeea0b7f7842ad7015444f5b9">emitLinkerOptions</a> (ArrayRef&lt; std::string &gt; Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the given list <span class="doxyComputerOutput">Options</span> of strings as linker options into the output. <a href="#ac27396eeeea0b7f7842ad7015444f5b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab93cbe98a85c26f4749096e5fecca2f5">emitDataRegion</a> (MCDataRegionType Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Note in the output the specified region <span class="doxyComputerOutput">Kind</span>. <a href="#ab93cbe98a85c26f4749096e5fecca2f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1e7d99b242b72e77c6265b64f5a4a30">emitVersionMin</a> (MCVersionMinType Type, unsigned Major, unsigned Minor, unsigned Update, VersionTuple SDKVersion)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specify the Mach-O minimum deployment target version. <a href="#af1e7d99b242b72e77c6265b64f5a4a30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcd3ae53e61e2a9304cd12fad993ac6d">emitBuildVersion</a> (unsigned Platform, unsigned Major, unsigned Minor, unsigned Update, VersionTuple SDKVersion)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit/Specify Mach-O build version command. <a href="#afcd3ae53e61e2a9304cd12fad993ac6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93d2f1ced6c7735391e7b442e6fd7713">emitDarwinTargetVariantBuildVersion</a> (unsigned Platform, unsigned Major, unsigned Minor, unsigned Update, VersionTuple SDKVersion)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1789315a3765f97ea5e82e21f4b9e47">emitVersionForTarget</a> (const Triple &amp;Target, const VersionTuple &amp;SDKVersion, const Triple *DarwinTargetVariantTriple, const VersionTuple &amp;DarwinTargetVariantSDKVersion)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac78244fafa28f11ddd2b14133dc2e655">emitThumbFunc</a> (MCSymbol *Func)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Note in the output that the specified <span class="doxyComputerOutput">Func</span> is a Thumb mode function (<a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> target only). <a href="#ac78244fafa28f11ddd2b14133dc2e655">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04736ef5753e5ecda3c29ce902094e68">emitAssignment</a> (MCSymbol *Symbol, const MCExpr *Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an assignment of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> to <span class="doxyComputerOutput">Symbol</span>. <a href="#a04736ef5753e5ecda3c29ce902094e68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af30ac5bb4b7e3d0c5a32aca9e41eac3e">emitConditionalAssignment</a> (MCSymbol *Symbol, const MCExpr *Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an assignment of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> to <span class="doxyComputerOutput">Symbol</span>, but only if <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> is also emitted. <a href="#af30ac5bb4b7e3d0c5a32aca9e41eac3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa4e077ea8a8c1f7e7d6321de4c1acd0">emitWeakReference</a> (MCSymbol *Alias, const MCSymbol *Symbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an weak reference from <span class="doxyComputerOutput">Alias</span> to <span class="doxyComputerOutput">Symbol</span>. <a href="#afa4e077ea8a8c1f7e7d6321de4c1acd0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a321bb307942921d2e598d92e1830b05d">emitSymbolAttribute</a> (MCSymbol *Symbol, MCSymbolAttr Attribute)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the given <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></span> to <span class="doxyComputerOutput">Symbol</span>. <a href="#a321bb307942921d2e598d92e1830b05d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa351ace3a13226477378dd10bd407747">emitSymbolDesc</a> (MCSymbol *Symbol, unsigned DescValue)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the <span class="doxyComputerOutput">DescValue</span> for the <span class="doxyComputerOutput">Symbol</span>. <a href="#aa351ace3a13226477378dd10bd407747">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c068ea06bd2ccfddfdceab7eda111aa">beginCOFFSymbolDef</a> (const MCSymbol *Symbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Start emitting <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> symbol definition. <a href="#a1c068ea06bd2ccfddfdceab7eda111aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af203d2f0f2a64404b03047029069df5e">emitCOFFSymbolStorageClass</a> (int StorageClass)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the storage class of the symbol. <a href="#af203d2f0f2a64404b03047029069df5e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36d6cf82efbf1820a5df485552aa92dd">emitCOFFSymbolType</a> (int Type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the type of the symbol. <a href="#a36d6cf82efbf1820a5df485552aa92dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49798cb55fb8e3a280ca3249704e7dec">endCOFFSymbolDef</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Marks the end of the symbol definition. <a href="#a49798cb55fb8e3a280ca3249704e7dec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7ed79f8ff9174fdf148ca9ad7c04266">emitCOFFSafeSEH</a> (MCSymbol const *Symbol)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e74195180c1fcc6da23dac04b3f733f">emitCOFFSymbolIndex</a> (MCSymbol const *Symbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits the symbol table index of a Symbol into the current section. <a href="#a3e74195180c1fcc6da23dac04b3f733f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a825998894ce032cf0eb7c76df0c1050b">emitCOFFSectionIndex</a> (MCSymbol const *Symbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits a <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> section index. <a href="#a825998894ce032cf0eb7c76df0c1050b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a714de05372be0237bac97ad800dd2b52">emitCOFFSecRel32</a> (MCSymbol const *Symbol, uint64_t Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits a <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> section relative relocation. <a href="#a714de05372be0237bac97ad800dd2b52">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a491fd9123956896fd275562d0393e097">emitCOFFImgRel32</a> (MCSymbol const *Symbol, int64_t Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits a <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> image relative relocation. <a href="#a491fd9123956896fd275562d0393e097">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b04c50b8ffcf3457ed3f374fa5675b7">emitCOFFSecNumber</a> (MCSymbol const *Symbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits the physical number of the section containing the given symbol as assigned during object writing (i.e., this is not a runtime relocation). <a href="#a5b04c50b8ffcf3457ed3f374fa5675b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f098eb17c10b646a3be4fa3ecab690e">emitCOFFSecOffset</a> (MCSymbol const *Symbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits the offset of the symbol from the beginning of the section during object writing (i.e., this is not a runtime relocation). <a href="#a8f098eb17c10b646a3be4fa3ecab690e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a41af9b3e693ce888f34dc67ecb457e">emitXCOFFLocalCommonSymbol</a> (MCSymbol *LabelSym, uint64_t Size, MCSymbol *CsectSym, Align Alignment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits an lcomm directive with <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a> csect information. <a href="#a6a41af9b3e693ce888f34dc67ecb457e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50ff2680cccb848300db07728653a394">emitXCOFFSymbolLinkageWithVisibility</a> (MCSymbol *Symbol, MCSymbolAttr Linkage, MCSymbolAttr Visibility)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a symbol's linkage and visibility with a linkage directive for <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a>. <a href="#a50ff2680cccb848300db07728653a394">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad30724b89cfe985b9aafd0e26b5fa57">emitXCOFFRenameDirective</a> (const MCSymbol *Name, StringRef Rename)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a> .rename directive which creates a synonym for an illegal or undesirable name. <a href="#aad30724b89cfe985b9aafd0e26b5fa57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a810e0bdb5ee0b5c22eda3e47ef26b677">emitXCOFFExceptDirective</a> (const MCSymbol *Symbol, const MCSymbol *Trap, unsigned Lang, unsigned Reason, unsigned FunctionSize, bool hasDebug)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a> .except directive which adds information about a trap instruction to the object file exception section. <a href="#a810e0bdb5ee0b5c22eda3e47ef26b677">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca7f3609c2134cac6f3ebe63f657690e">emitXCOFFRefDirective</a> (const MCSymbol *Symbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a> .ref directive which creates R_REF type entry in the relocation table for one or more symbols. <a href="#aca7f3609c2134cac6f3ebe63f657690e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae19d371578fc3d61f9e1655b2f94c32f">emitXCOFFCInfoSym</a> (StringRef Name, StringRef Metadata)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a C_INFO symbol with <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a> embedded metadata to the .info section. <a href="#ae19d371578fc3d61f9e1655b2f94c32f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a680c60c227c19f83cc4e7e363525151b">emitELFSize</a> (MCSymbol *Symbol, const MCExpr *Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> .size directive. <a href="#a680c60c227c19f83cc4e7e363525151b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1797d09864b58205f4875b49d2536b4">emitELFSymverDirective</a> (const MCSymbol *OriginalSym, StringRef Name, bool KeepOriginalSym)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> .symver directive. <a href="#ae1797d09864b58205f4875b49d2536b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7db4f7bc015f46c9e027ecdb54411ec">emitLOHDirective</a> (MCLOHType Kind, const MCLOHArgs &amp;Args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a <a href="/web-llvm/docs/api/classes/llvm/linker">Linker</a> Optimization Hint (LOH) directive. <a href="#ae7db4f7bc015f46c9e027ecdb54411ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a237e958de04fd14064d0e807a9d6eccc">emitGNUAttribute</a> (unsigned Tag, unsigned Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a .gnu_attribute directive. <a href="#a237e958de04fd14064d0e807a9d6eccc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ea7af1a890d88550e6ec96294c19f95">emitCommonSymbol</a> (MCSymbol *Symbol, uint64_t Size, Align ByteAlignment)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a common symbol. <a href="#a4ea7af1a890d88550e6ec96294c19f95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa407cf6860a31ef5dc7be9df6d738018">emitLocalCommonSymbol</a> (MCSymbol *Symbol, uint64_t Size, Align ByteAlignment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a local common (.lcomm) symbol. <a href="#aa407cf6860a31ef5dc7be9df6d738018">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad490db637a9818eafdae19bdb0ec1334">emitZerofill</a> (MCSection *Section, MCSymbol *Symbol=nullptr, uint64_t Size=0, Align ByteAlignment=Align(1), SMLoc Loc=SMLoc())=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the zerofill section and an optional symbol. <a href="#ad490db637a9818eafdae19bdb0ec1334">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af577f077023eb897b94f2ed2bad79bbc">emitTBSSSymbol</a> (MCSection *Section, MCSymbol *Symbol, uint64_t Size, Align ByteAlignment=Align(1))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a thread local bss (.tbss) symbol. <a href="#af577f077023eb897b94f2ed2bad79bbc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Generating Data Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af94e84eca402017c9ce57b7b4c4104e3">emitBytes</a> (StringRef Data)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the bytes in <span class="doxyComputerOutput">Data</span> into the output. <a href="#af94e84eca402017c9ce57b7b4c4104e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d73c2da2d5410a07113b9f24c640c12">emitBinaryData</a> (StringRef Data)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Functionally identical to EmitBytes. <a href="#a1d73c2da2d5410a07113b9f24c640c12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3d6e5ea7b855357014a16db766dddfd">emitValueImpl</a> (const MCExpr *Value, unsigned Size, SMLoc Loc=SMLoc())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the expression <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> into the output as a native integer of the given <span class="doxyComputerOutput">Size</span> bytes. <a href="#ae3d6e5ea7b855357014a16db766dddfd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7833630c617e5943c0a41755f5d4bdcf">emitValue</a> (const MCExpr *Value, unsigned Size, SMLoc Loc=SMLoc())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a971830cc1546210be8cc86fa568be8d0">emitIntValue</a> (uint64_t Value, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Special case of EmitValue that avoids the client having to pass in a <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> for constant integers. <a href="#a971830cc1546210be8cc86fa568be8d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d36cf8691cdd5195631e8bbd8d38fc2">emitIntValue</a> (const APInt &amp;Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4339a05bb7a7fb9207f2c78644ce4983">emitIntValueInHex</a> (uint64_t Value, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Special case of EmitValue that avoids the client having to pass in a <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> for constant integers &amp; prints in Hex format for certain modes. <a href="#a4339a05bb7a7fb9207f2c78644ce4983">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af47540299db471532b82aba9314f1fc2">emitInt8</a> (uint64_t Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d412a2cef594fc0f45de176d51fee3b">emitInt16</a> (uint64_t Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc3817979bc871dba942b87773da1cc0">emitInt32</a> (uint64_t Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac46413fa6b39176f78fc9621a08af7a5">emitInt64</a> (uint64_t Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91b6cd6682b8cf4374eb1323b81bddc8">emitIntValueInHexWithPadding</a> (uint64_t Value, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Special case of EmitValue that avoids the client having to pass in a <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> for constant integers &amp; prints in Hex format for certain modes, pads the field with leading zeros to Size width. <a href="#a91b6cd6682b8cf4374eb1323b81bddc8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe4c2642ccb651af1def37f17f10bd19">emitULEB128Value</a> (const MCExpr *Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfe511cd5e910ebacc67825d067347da">emitSLEB128Value</a> (const MCExpr *Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc5f738b9471c3ed31b8f1fc7dc8e914">emitULEB128IntValue</a> (uint64_t Value, unsigned PadTo=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Special case of EmitULEB128Value that avoids the client having to pass in a <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> for constant integers. <a href="#abc5f738b9471c3ed31b8f1fc7dc8e914">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9c7bfbd6f1a6b08ebabb1ca16be3d7e">emitSLEB128IntValue</a> (int64_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Special case of EmitSLEB128Value that avoids the client having to pass in a <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> for constant integers. <a href="#ae9c7bfbd6f1a6b08ebabb1ca16be3d7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7865bd61cd2c65b2d94c58dd1523bb75">emitSymbolValue</a> (const MCSymbol *Sym, unsigned Size, bool IsSectionRelative=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Special case of EmitValue that avoids the client having to pass in a <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> for MCSymbols. <a href="#a7865bd61cd2c65b2d94c58dd1523bb75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16c215be8d978c78bd4915e8c7b5be44">emitDTPRel64Value</a> (const MCExpr *Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the expression <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> into the output as a dtprel (64-bit DTP relative) value. <a href="#a16c215be8d978c78bd4915e8c7b5be44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf0a3067291b11ed02cf9658cc100ff1">emitDTPRel32Value</a> (const MCExpr *Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the expression <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> into the output as a dtprel (32-bit DTP relative) value. <a href="#acf0a3067291b11ed02cf9658cc100ff1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e2e9044b6de1aa53fd40d33e4cfe4c7">emitTPRel64Value</a> (const MCExpr *Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the expression <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> into the output as a tprel (64-bit TP relative) value. <a href="#a8e2e9044b6de1aa53fd40d33e4cfe4c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f5a9c52ffa8394dbe016360b4c3379a">emitTPRel32Value</a> (const MCExpr *Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the expression <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> into the output as a tprel (32-bit TP relative) value. <a href="#a6f5a9c52ffa8394dbe016360b4c3379a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fc23f2bb6f6eac3e533bba27f1b48c3">emitGPRel64Value</a> (const MCExpr *Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the expression <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> into the output as a gprel64 (64-bit GP relative) value. <a href="#a2fc23f2bb6f6eac3e533bba27f1b48c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f3171a957932bcebeee529fd209eb29">emitGPRel32Value</a> (const MCExpr *Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the expression <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> into the output as a gprel32 (32-bit GP relative) value. <a href="#a5f3171a957932bcebeee529fd209eb29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6a6f6142b6fd138cdc9e08217577c4d">emitFill</a> (uint64_t NumBytes, uint8_t FillValue)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit NumBytes bytes worth of the value specified by FillValue. <a href="#af6a6f6142b6fd138cdc9e08217577c4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83eaa7813db4a518c595cd260451035a">emitFill</a> (const MCExpr &amp;NumBytes, uint64_t FillValue, SMLoc Loc=SMLoc())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit <span class="doxyComputerOutput">Size</span> bytes worth of the value specified by <span class="doxyComputerOutput">FillValue</span>. <a href="#a83eaa7813db4a518c595cd260451035a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3853464dd3b9c6d976ae24e63eaf2e01">emitFill</a> (const MCExpr &amp;NumValues, int64_t Size, int64_t Expr, SMLoc Loc=SMLoc())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit <span class="doxyComputerOutput">NumValues</span> copies of <span class="doxyComputerOutput">Size</span> bytes. <a href="#a3853464dd3b9c6d976ae24e63eaf2e01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03abb4df5c516e1801f1364c403adfd3">emitNops</a> (int64_t NumBytes, int64_t ControlledNopLength, SMLoc Loc, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae77a5b8d3af591a461aeac723de33240">emitZeros</a> (uint64_t NumBytes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit NumBytes worth of zeros. <a href="#ae77a5b8d3af591a461aeac723de33240">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9488c32df3cb8819f6a07f8c88d72c66">emitValueToAlignment</a> (Align Alignment, int64_t Value=0, unsigned ValueSize=1, unsigned MaxBytesToEmit=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit some number of copies of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> until the byte alignment <span class="doxyComputerOutput">ByteAlignment</span> is reached. <a href="#a9488c32df3cb8819f6a07f8c88d72c66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1dcf543ae68792dfaabeaa31f4ddef2">emitCodeAlignment</a> (Align Alignment, const MCSubtargetInfo *STI, unsigned MaxBytesToEmit=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit nops until the byte alignment <span class="doxyComputerOutput">ByteAlignment</span> is reached. <a href="#aa1dcf543ae68792dfaabeaa31f4ddef2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac28f9bc04d492da0076b2852d4e9dded">emitValueToOffset</a> (const MCExpr *Offset, unsigned char Value, SMLoc Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit some number of copies of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> until the byte offset <span class="doxyComputerOutput">Offset</span> is reached. <a href="#ac28f9bc04d492da0076b2852d4e9dded">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Streaming machine code generation interface.</p>


<p>This interface is intended to provide a programmatic interface that is very similar to the level that an assembler .s file provides. It has callbacks to emit bytes, handle directives, etc. The implementation of this interface retains state to know what the current section is etc.</p>


<p>There are multiple implementations of this interface: one for writing out a .s file, and implementations that write out .o files of various formats.</p>


<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MCStreamer() {#a22fe36f1318b43e947d6f5e8cf1bb4af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCStreamer::MCStreamer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp;)</td>
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



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Reference <a href="#a91d427d805fbdbcddd4d6381bee35ba6">MCStreamer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### MCStreamer() {#a91d427d805fbdbcddd4d6381bee35ba6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCStreamer::MCStreamer (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Declaration at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a528f3b8c204e96bf6a9b2680f22b4af6">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::MCAsmStreamer</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcnullstreamer-cpp-/mcnullstreamer/#a84912b5a6e0a8871b250fec836c3a618">anonymous{MCNullStreamer.cpp}::MCNullStreamer::MCNullStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a9ad1da683a018add519fd96cd22cc785">llvm::MCObjectStreamer::MCObjectStreamer</a>, <a href="#a22fe36f1318b43e947d6f5e8cf1bb4af">MCStreamer</a>, <a href="#ae73a85a70a248f1d7ad6ba6fc749b7e3">operator=</a> and <a href="/web-llvm/docs/api/classes/llvm/recordstreamer/#aa55a7fd09c9524646b504c4623f98bc7">llvm::RecordStreamer::RecordStreamer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MCStreamer() {#a2c0b98babb5ae78e83a3adffb116ea75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCStreamer::~MCStreamer ()</td>
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



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#ae73a85a70a248f1d7ad6ba6fc749b7e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCStreamer &amp; llvm::MCStreamer::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp;)</td>
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



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Reference <a href="#a91d427d805fbdbcddd4d6381bee35ba6">MCStreamer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitAbsoluteSymbolDiff() {#a8061d1e593a8f095f0efe3ba0d793531}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitAbsoluteSymbolDiff (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Hi, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Lo, unsigned Size)</td>
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

<p>Emit the absolute difference between two symbols.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>Offset of <span class="doxyComputerOutput">Hi</span> is greater than the offset <span class="doxyComputerOutput">Lo</span>.</p></dd>
</dl>


<p>Declaration at line 1001 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1172 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#af766134165065939f49fb0662c246f66">llvm::MCBinaryExpr::createSub</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a8c82a9b4ea251d67a47a318d80c6909f">llvm::MCAsmInfo::doesSetDirectiveSuppressReloc</a>, <a href="#a04736ef5753e5ecda3c29ce902094e68">emitAssignment</a>, <a href="#a7865bd61cd2c65b2d94c58dd1523bb75">emitSymbolValue</a>, <a href="#a7833630c617e5943c0a41755f5d4bdcf">emitValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableheader/#a1b87cc4b647fd0f14ea7c46227ae2d58">llvm::MCDwarfLineTableHeader::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#afe30d1dfbe988401ae6ded700dd877bc">llvm::MCObjectStreamer::emitAbsoluteSymbolDiff</a>, <a href="#ad5bed3c2d5a90c1dc5433064c8f25e2d">emitDwarfUnitLength</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer/#a00e4f812d3f229d47f31c41cfddadddc">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::emitFPOData</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpostatemachine/#ac60cbf99d76cbbbbc3c094a7d78fb834">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOStateMachine::emitFrameDataRecord</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcdwarf/#ad32db1a85072666827c900bee74761b1">llvm::mcdwarf::emitListsTableHeaderStart</a>.</p>

</div>
</div>

### emitAbsoluteSymbolDiffAsULEB128() {#a4f385d04b05418cfd8b1337ac541256c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitAbsoluteSymbolDiffAsULEB128 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Hi, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Lo)</td>
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

<p>Emit the absolute difference between two symbols encoded with ULEB128.</p>

<p>Declaration at line 1005 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1191 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#af766134165065939f49fb0662c246f66">llvm::MCBinaryExpr::createSub</a>, <a href="#abe4c2642ccb651af1def37f17f10bd19">emitULEB128Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#aad8d06379b43b4e55d8cfc4908a486a9">llvm::MCObjectStreamer::emitAbsoluteSymbolDiffAsULEB128</a>.</p>

</div>
</div>

### emitAddrsig() {#a03e21d8e0d59e0c54851dfe311057aae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCStreamer::emitAddrsig ()</td>
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



<p>Definition at line 1084 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>

</div>
</div>

### emitAddrsigSym() {#afa184a3f234071ff7b4a6b0c6cc15a35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCStreamer::emitAddrsigSym (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym)</td>
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



<p>Definition at line 1085 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>

</div>
</div>

### emitBundleAlignMode() {#af7b71f9cb401d7047b0103b9e60cd89e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitBundleAlignMode (<a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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

<p>Set the bundle alignment mode from now on in the section.</p>


<p>The value 1 means turn the bundle alignment off.</p>


<p>Declaration at line 1098 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1283 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>

</div>
</div>

### emitBundleLock() {#a28cd349f2853a5ef3208819272623b46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitBundleLock (bool AlignToEnd)</td>
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

<p>The following instructions are a bundle-locked group.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignToEnd</td>
<td class="doxyParamItemDescription"><p>- If true, the bundle-locked group will be aligned to the end of a bundle.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1284 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>

</div>
</div>

### emitBundleUnlock() {#a630ed2d1311b8a1549af404488a9de4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitBundleUnlock ()</td>
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

<p>Ends a bundle-locked group.</p>

<p>Declaration at line 1107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1286 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>

</div>
</div>

### emitCFIAdjustCfaOffset() {#ab98cdd0259874847cd346b396f87ed29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCFIAdjustCfaOffset (int64_t Adjustment, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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



<p>Declaration at line 1025 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#ad6a85756410e7929f561fc1454069563">llvm::MCCFIInstruction::createAdjustCfaOffset</a>, <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a> and <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#ad678a6927d2876e9eb5fba111da70584">llvm::MCDwarfFrameInfo::Instructions</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a9a9f2fcfbe8ff4ef1d2c161af79131d4">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCFIAdjustCfaOffset</a>.</p>

</div>
</div>

### emitCFIBKeyFrame() {#a18b9227cee7d28b311e88626e31470b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCFIBKeyFrame ()</td>
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



<p>Declaration at line 915 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#a433d11c67a32132351c98de2b8065284">llvm::MCDwarfFrameInfo::IsBKeyFrame</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a90418f29973b14097248f7ac471b4601">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCFIBKeyFrame</a>.</p>

</div>
</div>

### emitCFIDefCfa() {#a06d947eb9b24c3c09aec7dae8b242d36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCFIDefCfa (int64_t Register, int64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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



<p>Declaration at line 1012 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 506 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a64fe578753bb594671a8e440e32a2b95">llvm::MCCFIInstruction::cfiDefCfa</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#afc4f9cad50cf910f508ef213f26d539e">llvm::MCDwarfFrameInfo::CurrentCfaRegister</a>, <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#ad678a6927d2876e9eb5fba111da70584">llvm::MCDwarfFrameInfo::Instructions</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a6996bce7ed70cee8ce64cf58b0f67df1">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCFIDefCfa</a>.</p>

</div>
</div>

### emitCFIDefCfaOffset() {#ad00e491df6ac397c2836f4823486b814}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCFIDefCfaOffset (int64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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



<p>Declaration at line 1013 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 517 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#abbe481ab35db0dcfa03f9f5bbabb9def">llvm::MCCFIInstruction::cfiDefCfaOffset</a>, <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#ad678a6927d2876e9eb5fba111da70584">llvm::MCDwarfFrameInfo::Instructions</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a1fd03efd6ce5b55cc6c6bf1afb4fd650">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCFIDefCfaOffset</a>.</p>

</div>
</div>

### emitCFIDefCfaRegister() {#aa3cb8bdbc2ba4f13b85ae876c8db72c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCFIDefCfaRegister (int64_t Register, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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



<p>Declaration at line 1014 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 537 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a03445be1c81520587d5bb31b353f5558">llvm::MCCFIInstruction::createDefCfaRegister</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#afc4f9cad50cf910f508ef213f26d539e">llvm::MCDwarfFrameInfo::CurrentCfaRegister</a>, <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a> and <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#ad678a6927d2876e9eb5fba111da70584">llvm::MCDwarfFrameInfo::Instructions</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a23730892bc6167f3f73277923a986ea7">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCFIDefCfaRegister</a>.</p>

</div>
</div>

### emitCFIEndProc() {#ac9b56ca50fc9b458d7c7b557addaf56e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCFIEndProc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1011 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 472 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="#aa32eb827df6b7817d6c2ab91c47ad1e4">emitCFIEndProcImpl</a>.</p>

</div>
</div>

### emitCFIEscape() {#a7f85a7656080c1cece6d55421409c2ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCFIEscape (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Values, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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



<p>Declaration at line 1026 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 638 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#ac6eb36207cf2c7ebbd9a67e63dcc5568">llvm::MCCFIInstruction::createEscape</a>, <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a> and <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#ad678a6927d2876e9eb5fba111da70584">llvm::MCDwarfFrameInfo::Instructions</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a7fef34027fa50e93af1d29428199df26">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCFIEscape</a>.</p>

</div>
</div>

### emitCFIGnuArgsSize() {#a00b5e27ba702e289d1355d83634496e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCFIGnuArgsSize (int64_t Size, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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



<p>Declaration at line 1028 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 648 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a2097ca045c7251b81f97c5fc3efdcfc8">llvm::MCCFIInstruction::createGnuArgsSize</a>, <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#ad678a6927d2876e9eb5fba111da70584">llvm::MCDwarfFrameInfo::Instructions</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a0ba55c78541fd684b5ccd7eb8aacec66">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCFIGnuArgsSize</a>.</p>

</div>
</div>

### emitCFILabel() {#a2168a8bae9fa55fb113c07c2f66c11f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MCStreamer::emitCFILabel ()</td>
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

<p>When emitting an object file, create and emit a real label.</p>


<p>When emitting textual assembly, this should do nothing to avoid polluting our output.</p>


<p>Declaration at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Referenced by <a href="#ab98cdd0259874847cd346b396f87ed29">emitCFIAdjustCfaOffset</a>, <a href="#a06d947eb9b24c3c09aec7dae8b242d36">emitCFIDefCfa</a>, <a href="#ad00e491df6ac397c2836f4823486b814">emitCFIDefCfaOffset</a>, <a href="#aa3cb8bdbc2ba4f13b85ae876c8db72c8">emitCFIDefCfaRegister</a>, <a href="#a7f85a7656080c1cece6d55421409c2ac">emitCFIEscape</a>, <a href="#a00b5e27ba702e289d1355d83634496e8">emitCFIGnuArgsSize</a>, <a href="#a886df281f466da825e86d3db00309322">emitCFILabelDirective</a>, <a href="#afd9cd40e1c8cda6d287b38bbbc4a65dd">emitCFILLVMDefAspaceCfa</a>, <a href="#a5e417903a64e0e2e03a881cc22988c03">emitCFINegateRAState</a>, <a href="#a2f9a65946cfd95e5fee5434be8061fba">emitCFINegateRAStateWithPC</a>, <a href="#acc89f9e1b110cc78d0b3782c7169fee3">emitCFIOffset</a>, <a href="#aa640c4cba0755dc19a91bdb98fec5998">emitCFIRegister</a>, <a href="#ac21d03105248455242c40d1b663dfea1">emitCFIRelOffset</a>, <a href="#a861747a0f3a48a53fdff7bdc6c1856d8">emitCFIRememberState</a>, <a href="#af5f8c58b6d8f44d96b1f1d02ba7af4af">emitCFIRestore</a>, <a href="#aca048ea2881b4d098c005349f99bab62">emitCFIRestoreState</a>, <a href="#a30e73886a8c818640b69a5ca9dfe3b60">emitCFISameValue</a>, <a href="#a52d332cc8f6e4738d2b9c3f78ab28f1a">emitCFIUndefined</a>, <a href="#ae0930d72d21ce9df1f3d41b685411bd9">emitCFIValOffset</a>, <a href="#a396af4f92c9743bcf60f86474c7ebadf">emitCFIWindowSave</a>, <a href="/web-llvm/docs/api/classes/llvm/win64eh/arm64unwindemitter/#a23e988e2f737319fba0ad0f50b4791c3">llvm::Win64EH::ARM64UnwindEmitter::EmitUnwindInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/win64eh/armunwindemitter/#ae3581e58aa167be222e1d2b9c164b10a">llvm::Win64EH::ARMUnwindEmitter::EmitUnwindInfo</a>, <a href="#ad9bb2bc90c804c28497604ae91e27bd7">emitWinCFIAllocStack</a>, <a href="#a9b6d232a4258f0dd9f16ee5b4f558633">emitWinCFIEndChained</a>, <a href="#a9d158c6b4a4302d51fd73aac4075086d">emitWinCFIEndProc</a>, <a href="#a9b9f4aa69270161dc91d76e3080e6dd2">emitWinCFIEndProlog</a>, <a href="#aac38128831e5c5377b98fd32d4f53fc9">emitWinCFIFuncletOrFuncEnd</a>, <a href="#a4c579bc3d70f8f348c3ddf8224a31220">emitWinCFIPushFrame</a>, <a href="#a1d0c21ad8ad54697f00aab2c37d77e25">emitWinCFIPushReg</a>, <a href="#a9a30cc0783819b780c3e357162b90aec">emitWinCFISaveReg</a>, <a href="#a5755faab671780e6c1abcaa95f05fe0b">emitWinCFISaveXMM</a>, <a href="#acd1f092159870d525f916e3296341d92">emitWinCFISetFrame</a>, <a href="#af4abf3b216995cecfbe8fcbc05d5b128">emitWinCFIStartChained</a> and <a href="#a7787897c604e14c9e152c890e019e3bf">emitWinCFIStartProc</a>.</p>

</div>
</div>

### emitCFILabelDirective() {#a886df281f466da825e86d3db00309322}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCFILabelDirective (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Declaration at line 1036 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 722 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#af806d86ab5b0d3a03de968f53959d056">llvm::MCCFIInstruction::createLabel</a>, <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a61c979932b890df773ce75013b76708b">getContext</a> and <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ac11eef690074972378846024abbe8722">llvm::MCContext::getOrCreateSymbol</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a1368dcd0236358f2e93224d719a5ed4c">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCFILabelDirective</a>.</p>

</div>
</div>

### emitCFILLVMDefAspaceCfa() {#afd9cd40e1c8cda6d287b38bbbc4a65dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCFILLVMDefAspaceCfa (int64_t Register, int64_t Offset, int64_t AddressSpace, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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



<p>Declaration at line 1015 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 548 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a5243e6ada761524b2689a8b52cbe9d0c">llvm::MCCFIInstruction::createLLVMDefAspaceCfa</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#afc4f9cad50cf910f508ef213f26d539e">llvm::MCDwarfFrameInfo::CurrentCfaRegister</a>, <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#ad678a6927d2876e9eb5fba111da70584">llvm::MCDwarfFrameInfo::Instructions</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a719913ede040feaea18c58b51d274fc2">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCFILLVMDefAspaceCfa</a>.</p>

</div>
</div>

### emitCFILsda() {#a5fdf26af0fa16c740221a0f1492652da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCFILsda (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym, unsigned Encoding)</td>
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



<p>Declaration at line 1019 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 589 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#aedbfd737ebf204c167470729f2ec0042">llvm::MCDwarfFrameInfo::Lsda</a> and <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#ad8d9360321fbcbdb17515c2d227f75fa">llvm::MCDwarfFrameInfo::LsdaEncoding</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a83ebec98343071d599da4791ca684669">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCFILsda</a>.</p>

</div>
</div>

### emitCFIMTETaggedFrame() {#a6c8bdd2a81dd6498072971ec263d61d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCFIMTETaggedFrame ()</td>
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



<p>Declaration at line 916 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#ad80999a465c92131481073b2fce9d5ed">llvm::MCDwarfFrameInfo::IsMTETaggedFrame</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a65104a9150bbdbc652e32ba00e45c7a4">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCFIMTETaggedFrame</a>.</p>

</div>
</div>

### emitCFINegateRAState() {#a5e417903a64e0e2e03a881cc22988c03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCFINegateRAState (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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



<p>Declaration at line 1034 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 695 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a897ff5de2f1ce15003e513758c7cf7b1">llvm::MCCFIInstruction::createNegateRAState</a>, <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a> and <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#ad678a6927d2876e9eb5fba111da70584">llvm::MCDwarfFrameInfo::Instructions</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a8bcea8c54481f254291d8b05ef89b468">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCFINegateRAState</a>.</p>

</div>
</div>

### emitCFINegateRAStateWithPC() {#a2f9a65946cfd95e5fee5434be8061fba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCFINegateRAStateWithPC (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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



<p>Declaration at line 1035 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 705 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a8546686a46d43f38c7104b866513fa2e">llvm::MCCFIInstruction::createNegateRAStateWithPC</a>, <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a> and <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#ad678a6927d2876e9eb5fba111da70584">llvm::MCDwarfFrameInfo::Instructions</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a59e34064a47d3e0980a80cb6a48f70f2">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCFINegateRAStateWithPC</a>.</p>

</div>
</div>

### emitCFIOffset() {#acc89f9e1b110cc78d0b3782c7169fee3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCFIOffset (int64_t Register, int64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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



<p>Declaration at line 1017 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 560 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a6a60a82f8cb445e9e7029e38733b2d30">llvm::MCCFIInstruction::createOffset</a>, <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#ad678a6927d2876e9eb5fba111da70584">llvm::MCDwarfFrameInfo::Instructions</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a4e9f218fee0bd6340115d4710ce467a9">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCFIOffset</a>.</p>

</div>
</div>

### emitCFIPersonality() {#a3721196eca9702a79c55577d867c8535}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCFIPersonality (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym, unsigned Encoding)</td>
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



<p>Declaration at line 1018 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 580 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#a3c371b9d29a2da49e836e29ac73b359b">llvm::MCDwarfFrameInfo::Personality</a> and <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#a932960bf69710f1094b4e6d8fc5d627c">llvm::MCDwarfFrameInfo::PersonalityEncoding</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a2e7a2fbd7a50f4bb4db72650d848e706">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCFIPersonality</a>.</p>

</div>
</div>

### emitCFIRegister() {#aa640c4cba0755dc19a91bdb98fec5998}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCFIRegister (int64_t Register1, int64_t Register2, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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



<p>Declaration at line 1031 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 675 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a5efbfe5cee3e83355dec981c2d43611f">llvm::MCCFIInstruction::createRegister</a>, <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a> and <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#ad678a6927d2876e9eb5fba111da70584">llvm::MCDwarfFrameInfo::Instructions</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a7376cdebe10c84e3d70cf0462eaf8527">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCFIRegister</a>.</p>

</div>
</div>

### emitCFIRelOffset() {#ac21d03105248455242c40d1b663dfea1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCFIRelOffset (int64_t Register, int64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Declaration at line 1024 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 570 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#ae4f57b410a806f657695bfb7e19400c0">llvm::MCCFIInstruction::createRelOffset</a>, <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#ad678a6927d2876e9eb5fba111da70584">llvm::MCDwarfFrameInfo::Instructions</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a84d605bf22158345464e37444897dc9b">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCFIRelOffset</a>.</p>

</div>
</div>

### emitCFIRememberState() {#a861747a0f3a48a53fdff7bdc6c1856d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCFIRememberState (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Declaration at line 1020 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 597 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a8c6c95634a9db9cd0fc23175a01afd80">llvm::MCCFIInstruction::createRememberState</a>, <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a> and <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#ad678a6927d2876e9eb5fba111da70584">llvm::MCDwarfFrameInfo::Instructions</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a4950e4dfd8d0686f56fcef68f9ad836a">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCFIRememberState</a>.</p>

</div>
</div>

### emitCFIRestore() {#af5f8c58b6d8f44d96b1f1d02ba7af4af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCFIRestore (int64_t Register, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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



<p>Declaration at line 1023 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 628 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a43cce47857fdb1dfec97aeba83ab82a3">llvm::MCCFIInstruction::createRestore</a>, <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a> and <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#ad678a6927d2876e9eb5fba111da70584">llvm::MCDwarfFrameInfo::Instructions</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a27f3e7dca0f76d616d10398e7a5b4952">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCFIRestore</a>.</p>

</div>
</div>

### emitCFIRestoreState() {#aca048ea2881b4d098c005349f99bab62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCFIRestoreState (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Declaration at line 1021 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 607 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#ae2bed50736717b1120a41c6dcc41428f">llvm::MCCFIInstruction::createRestoreState</a>, <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a> and <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#ad678a6927d2876e9eb5fba111da70584">llvm::MCDwarfFrameInfo::Instructions</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a83eb4cee5005e172b3e90427591eb43b">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCFIRestoreState</a>.</p>

</div>
</div>

### emitCFIReturnColumn() {#a35cbb2583bd074641c370112dc50615c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCFIReturnColumn (int64_t Register)</td>
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



<p>Declaration at line 1027 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 715 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#ac75bed23a3d4eac190a5e9f4c1c7abc0">llvm::MCDwarfFrameInfo::RAReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a9aa19cd6f2863b4b3d8d1658721ce4eb">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCFIReturnColumn</a>.</p>

</div>
</div>

### emitCFISameValue() {#a30e73886a8c818640b69a5ca9dfe3b60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCFISameValue (int64_t Register, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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



<p>Declaration at line 1022 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 618 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#ae43652fadd6c5abd6a6554cd3395baee">llvm::MCCFIInstruction::createSameValue</a>, <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a> and <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#ad678a6927d2876e9eb5fba111da70584">llvm::MCDwarfFrameInfo::Instructions</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#ae6e4ad4e354e26ed7fd0982a83861dd5">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCFISameValue</a>.</p>

</div>
</div>

### emitCFISections() {#a8e6d59ce0c2235c1e432aefcd928a1e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCFISections (bool EH, bool Debug)</td>
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



<p>Declaration at line 1009 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/debug-cpp/#a3fd0c3ac7c0e9187aa5c690ef9c70ebe">Debug</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a724fc73861d0edd1560d8bc919fab367">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCFISections</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#ac8d4f746597451a84912f04002db9e8b">llvm::MCObjectStreamer::emitCFISections</a>.</p>

</div>
</div>

### emitCFISignalFrame() {#aee53d30c51fc0e9ca7c57c52a95da789}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCFISignalFrame ()</td>
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



<p>Declaration at line 1029 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 658 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#a8711bbf8d91d469855854590ab674e15">llvm::MCDwarfFrameInfo::IsSignalFrame</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a9248320d0eb1f90204263d4994606824">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCFISignalFrame</a>.</p>

</div>
</div>

### emitCFIStartProc() {#a11eed8ef0a19a4cd80fc06a8488061fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCFIStartProc (bool IsSimple, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1010 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 444 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#afc4f9cad50cf910f508ef213f26d539e">llvm::MCDwarfFrameInfo::CurrentCfaRegister</a>, <a href="#a578add9dde6ca4352c23f00369d1fa78">emitCFIStartProcImpl</a>, <a href="#a61c979932b890df773ce75013b76708b">getContext</a>, <a href="#ae1b3cf074436ef5b527071540e13bd58">getCurrentSectionOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a3c2da6516abf838b5ed237b05fc9ae57">llvm::MCAsmInfo::getInitialFrameState</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#a1ddd4c949a45e7d0f88d8661584d6798">llvm::MCDwarfFrameInfo::IsSimple</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6ecacbbd41f459c6cea155b66a7ba10f1058">llvm::MCCFIInstruction::OpDefCfa</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca238c64d5f2c2fea57085c0238948b04f">llvm::MCCFIInstruction::OpDefCfaRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca41d79805b057315fb8e3593987b4fe6d">llvm::MCCFIInstruction::OpLLVMDefAspaceCfa</a> and <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aac3107671801e6bb16ef896f382759cd">llvm::MCContext::reportError</a>.</p>

</div>
</div>

### emitCFIUndefined() {#a52d332cc8f6e4738d2b9c3f78ab28f1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCFIUndefined (int64_t Register, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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



<p>Declaration at line 1030 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 665 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a1a4f533e313a1288ce2cad49aa92d5e5">llvm::MCCFIInstruction::createUndefined</a>, <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a> and <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#ad678a6927d2876e9eb5fba111da70584">llvm::MCDwarfFrameInfo::Instructions</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a83cbf7779ed7c37391e64acd29fb26d9">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCFIUndefined</a>.</p>

</div>
</div>

### emitCFIValOffset() {#ae0930d72d21ce9df1f3d41b685411bd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCFIValOffset (int64_t Register, int64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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



<p>Declaration at line 1037 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 729 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a8114c7601abcdb9e9fcf48c8abce7fb9">llvm::MCCFIInstruction::createValOffset</a>, <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#ad678a6927d2876e9eb5fba111da70584">llvm::MCDwarfFrameInfo::Instructions</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#aebd16a157411cf1e93601fde53dd2947">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCFIValOffset</a>.</p>

</div>
</div>

### emitCFIWindowSave() {#a396af4f92c9743bcf60f86474c7ebadf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCFIWindowSave (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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



<p>Declaration at line 1033 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 686 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#acdd3d6ea5364f4dd2460d0e31a191de4">llvm::MCCFIInstruction::createWindowSave</a>, <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a> and <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#ad678a6927d2876e9eb5fba111da70584">llvm::MCDwarfFrameInfo::Instructions</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a3f42c1f466d0e89a35438cb99727bc09">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCFIWindowSave</a>.</p>

</div>
</div>

### emitCGProfileEntry() {#ab742e8ccf28ac1233ea708dcb5decf2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCGProfileEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr">MCSymbolRefExpr</a> * From, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr">MCSymbolRefExpr</a> * To, uint64_t Count)</td>
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



<p>Declaration at line 1063 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 853 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a0483bd140eacb91339ca4e622b98ae04">llvm::TargetLoweringObjectFile::emitCGProfileMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#acb5fd683cbbfb19a2e0d78ee46bb283c">llvm::MCAsmParserExtension::parseDirectiveCGProfile</a>.</p>

</div>
</div>

### emitCVDefRangeDirective() {#acbf7790686251736b5aafca21bae3de9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCVDefRangeDirective (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt; &gt; Ranges, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FixedSizePortion)</td>
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

<p>This implements the CodeView '.cv_def_range' assembler directive.</p>

<p>Declaration at line 965 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a7f014c82821d76aff471c10829f336c6">llvm::MCObjectStreamer::emitCVDefRangeDirective</a>, <a href="#ac10e5da4db3a744be65230314f023f54">emitCVDefRangeDirective</a>, <a href="#a430e37112215f7ce7208db38075768b6">emitCVDefRangeDirective</a>, <a href="#a82c73f0d0e0884350e6de0b3928a75e2">emitCVDefRangeDirective</a> and <a href="#af444716cb34ad63a956c3d68098af874">emitCVDefRangeDirective</a>.</p>

</div>
</div>

### emitCVDefRangeDirective() {#a82c73f0d0e0884350e6de0b3928a75e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCVDefRangeDirective (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt; &gt; Ranges, <a href="/web-llvm/docs/api/structs/llvm/codeview/defrangeregisterrelheader">codeview::DefRangeRegisterRelHeader</a> DRHdr)</td>
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



<p>Declaration at line 969 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp/#a4b504b0bbdb4909cebdc60855bd6fd6a">copyBytesForDefRange</a> and <a href="#acbf7790686251736b5aafca21bae3de9">emitCVDefRangeDirective</a>.</p>

</div>
</div>

### emitCVDefRangeDirective() {#af444716cb34ad63a956c3d68098af874}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCVDefRangeDirective (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt; &gt; Ranges, <a href="/web-llvm/docs/api/structs/llvm/codeview/defrangesubfieldregisterheader">codeview::DefRangeSubfieldRegisterHeader</a> DRHdr)</td>
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



<p>Declaration at line 973 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp/#a4b504b0bbdb4909cebdc60855bd6fd6a">copyBytesForDefRange</a> and <a href="#acbf7790686251736b5aafca21bae3de9">emitCVDefRangeDirective</a>.</p>

</div>
</div>

### emitCVDefRangeDirective() {#a430e37112215f7ce7208db38075768b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCVDefRangeDirective (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt; &gt; Ranges, <a href="/web-llvm/docs/api/structs/llvm/codeview/defrangeregisterheader">codeview::DefRangeRegisterHeader</a> DRHdr)</td>
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



<p>Declaration at line 977 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp/#a4b504b0bbdb4909cebdc60855bd6fd6a">copyBytesForDefRange</a> and <a href="#acbf7790686251736b5aafca21bae3de9">emitCVDefRangeDirective</a>.</p>

</div>
</div>

### emitCVDefRangeDirective() {#ac10e5da4db3a744be65230314f023f54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCVDefRangeDirective (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt; &gt; Ranges, <a href="/web-llvm/docs/api/structs/llvm/codeview/defrangeframepointerrelheader">codeview::DefRangeFramePointerRelHeader</a> DRHdr)</td>
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



<p>Declaration at line 981 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp/#a4b504b0bbdb4909cebdc60855bd6fd6a">copyBytesForDefRange</a> and <a href="#acbf7790686251736b5aafca21bae3de9">emitCVDefRangeDirective</a>.</p>

</div>
</div>

### emitCVFileChecksumOffsetDirective() {#a58f3b6dec2de08069e7e8978ae878946}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCStreamer::emitCVFileChecksumOffsetDirective (unsigned FileNo)</td>
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

<p>This implements the CodeView '.cv_filechecksumoffset' assembler directive.</p>

<p>Definition at line 993 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>

</div>
</div>

### emitCVFileChecksumsDirective() {#a7e4def70d1592dd142143f25efa8770e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCStreamer::emitCVFileChecksumsDirective ()</td>
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

<p>This implements the CodeView '.cv_filechecksums' assembler directive.</p>

<p>Definition at line 989 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>

</div>
</div>

### emitCVFileDirective() {#a33c2e7b8c7463f2698a3132452cc4d12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCStreamer::emitCVFileDirective (unsigned FileNo, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Checksum, unsigned ChecksumKind)</td>
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

<p>Associate a filename with a specified logical file number, and also specify that file's checksum information.</p>


<p>This implements the '.cv_file 4 "foo.c"' assembler directive. Returns true on success.</p>


<p>Declaration at line 931 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#a63aca47ba5a5a2895c8ffd1e262ced59">llvm::CodeViewContext::addFile</a>, <a href="#a61c979932b890df773ce75013b76708b">getContext</a> and <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a7bdf9164b69f96821c0c0269dde3ebf7">llvm::MCContext::getCVContext</a>.</p>

</div>
</div>

### emitCVFPOData() {#a6554e9f25cfa8f02a2d6e382d527f680}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCStreamer::emitCVFPOData (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * ProcSym, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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

<p>This implements the CodeView '.cv_fpo_data' assembler directive.</p>

<p>Definition at line 996 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>

</div>
</div>

### emitCVFuncIdDirective() {#a13ac5fe9bbe382dd5e366288ba91fa43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCStreamer::emitCVFuncIdDirective (unsigned FunctionId)</td>
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

<p>Introduces a function id for use with .cv_loc.</p>

<p>Declaration at line 936 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="#a61c979932b890df773ce75013b76708b">getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a7bdf9164b69f96821c0c0269dde3ebf7">llvm::MCContext::getCVContext</a> and <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#a72b10e7a8e70b8cfea1eb3a1ef21f101">llvm::CodeViewContext::recordFunctionId</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a6177856d4e399300f3940086c56425cb">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCVFuncIdDirective</a>.</p>

</div>
</div>

### emitCVInlineLinetableDirective() {#af64e1dd74b4eb933d72d30513e283c6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCVInlineLinetableDirective (unsigned PrimaryFunctionId, unsigned SourceFileId, unsigned SourceLineNum, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * FnStartSym, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * FnEndSym)</td>
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

<p>This implements the CodeView '.cv_inline_linetable' assembler directive.</p>

<p>Declaration at line 957 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#aa96077a0e4bce1c56fb5c2660e5752df">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCVInlineLinetableDirective</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3590fc09ce2f93b9c19c488fb5cc3645">llvm::MCObjectStreamer::emitCVInlineLinetableDirective</a>.</p>

</div>
</div>

### emitCVInlineSiteIdDirective() {#aea7cedf9c3df1534425168ee9969871c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCStreamer::emitCVInlineSiteIdDirective (unsigned FunctionId, unsigned IAFunc, unsigned IAFile, unsigned IALine, unsigned IACol, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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

<p>Introduces an inline call site id for use with .cv_loc.</p>


<p>Includes extra information for inline line table generation.</p>


<p>Declaration at line 940 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="#a61c979932b890df773ce75013b76708b">getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a7bdf9164b69f96821c0c0269dde3ebf7">llvm::MCContext::getCVContext</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#aa4b7a64fbcdebe1bf6c4ad0bda073df4">llvm::CodeViewContext::recordInlinedCallSiteId</a> and <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aac3107671801e6bb16ef896f382759cd">llvm::MCContext::reportError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a6c677e18b455acc6e512bae0216093d8">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCVInlineSiteIdDirective</a>.</p>

</div>
</div>

### emitCVLinetableDirective() {#a8afbb0726c0e3513324fc6bf0c8100a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCVLinetableDirective (unsigned FunctionId, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * FnStart, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * FnEnd)</td>
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

<p>This implements the CodeView '.cv_linetable' assembler directive.</p>

<p>Declaration at line 951 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a238e59e2af8906f2cfc5155663d7a196">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCVLinetableDirective</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#af86cdbc272816dffaa30c62bdd8ec4b1">llvm::MCObjectStreamer::emitCVLinetableDirective</a>.</p>

</div>
</div>

### emitCVLocDirective() {#ad4da31215a8966e8ef4d2f1804a0387d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCVLocDirective (unsigned FunctionId, unsigned FileNo, unsigned Line, unsigned Column, bool PrologueEnd, bool IsStmt, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileName, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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

<p>This implements the CodeView '.cv_loc' assembler directive.</p>

<p>Declaration at line 945 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>

</div>
</div>

### emitCVStringTableDirective() {#a4137f731a9b0131b8983a13ec2d1dd4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCStreamer::emitCVStringTableDirective ()</td>
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

<p>This implements the CodeView '.cv_stringtable' assembler directive.</p>

<p>Definition at line 986 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>

</div>
</div>

### emitDwarfAdvanceLineAddr() {#a9c0dbc9f490b8fd3f66c6a821684408a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCStreamer::emitDwarfAdvanceLineAddr (int64_t LineDelta, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * LastLabel, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Label, unsigned PointerSize)</td>
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

<p>If targets does not support representing debug line section by .loc/.file directives in assembly output, we need to populate debug line section with raw debug line contents.</p>

<p>Definition at line 1144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#adf60d16739e1ceabb1cee9e9dede7ba5">llvm::MCDwarfLineTable::emitOne</a>.</p>

</div>
</div>

### emitDwarfFile0Directive() {#afc5440a8bfa25645fa1f58ee11a4394d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitDwarfFile0Directive (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directory, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/md5/md5result">MD5::MD5Result</a> &gt; Checksum, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; Source, unsigned CUID=0)</td>
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

<p>Specify the "root" file of the compilation, using the ".file 0" extension.</p>

<p>Declaration at line 910 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="#a61c979932b890df773ce75013b76708b">getContext</a> and <a href="/web-llvm/docs/api/classes/llvm/mccontext/#afa7b9baa221c1a5ea68940b0cf6b5a26">llvm::MCContext::setMCLineTableRootFile</a>.</p>

</div>
</div>

### emitDwarfFileDirective() {#a4a16115d4363f1c16af9cfcb425ce0d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCStreamer::emitDwarfFileDirective (unsigned FileNo, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directory, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/md5/md5result">MD5::MD5Result</a> &gt; Checksum=std::nullopt, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; Source=std::nullopt, unsigned CUID=0)</td>
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

<p>Associate a filename with a specified logical file number.</p>


<p>This implements the DWARF2 '.file 4 "foo.c"' assembler directive.</p>


<p>Definition at line 890 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a> and <a href="#a64d1f7d21e406e2796a9bb5afc3aa31e">tryEmitDwarfFileDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#afaaaf7da6379fe3994da86bf71024ddc">anonymous{AsmParser.cpp}::AsmParser::parseAndMatchAndEmitTargetInstruction</a>.</p>

</div>
</div>

### emitDwarfLineEndEntry() {#ae7d94558076f3c7f1f94497efe6efc9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCStreamer::emitDwarfLineEndEntry (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Section, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * LastLabel, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * EndLabel=nullptr)</td>
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

<p>Emit the debug line end entry.</p>

<p>Definition at line 1138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#adf60d16739e1ceabb1cee9e9dede7ba5">llvm::MCDwarfLineTable::emitOne</a>.</p>

</div>
</div>

### emitDwarfLineStartLabel() {#a7f1677ad2db297b0202a720530693157}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitDwarfLineStartLabel (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * StartSym)</td>
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

<p>Emit the debug line start label.</p>

<p>Declaration at line 1135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1095 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="#a822ae1a4f19b7b00a297a100749f9b8a">emitLabel</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableheader/#a1b87cc4b647fd0f14ea7c46227ae2d58">llvm::MCDwarfLineTableHeader::Emit</a> and <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#abc85cf8fcb99aada0bb615989928b516">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitDwarfLineStartLabel</a>.</p>

</div>
</div>

### emitDwarfLocDirective() {#a43c1c961a6b54da9fccacdf1cf5fc38f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitDwarfLocDirective (unsigned FileNo, unsigned Line, unsigned Column, unsigned Flags, unsigned Isa, unsigned Discriminator, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileName)</td>
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

<p>This implements the DWARF2 '.loc fileno lineno ...' assembler directive.</p>

<p>Declaration at line 920 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="#a61c979932b890df773ce75013b76708b">getContext</a> and <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a8bef0ea056c194d113570558f2c07132">llvm::MCContext::setCurrentDwarfLoc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#afbf8b87c2743700b4bc2f187d06c9a28">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitDwarfLocDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#ac90a78b45f28148cbab53747e0eba695">llvm::MCObjectStreamer::emitDwarfLocDirective</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#afaaaf7da6379fe3994da86bf71024ddc">anonymous{AsmParser.cpp}::AsmParser::parseAndMatchAndEmitTargetInstruction</a>.</p>

</div>
</div>

### emitDwarfLocLabelDirective() {#a29df2eab11142e7ff1e8ee74b0cb6322}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitDwarfLocLabelDirective (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>This implements the '.loc_label Name' directive.</p>

<p>Declaration at line 926 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#a36948c65344166574c860990801dc0a2">llvm::MCDwarfLineTable::endCurrentSeqAndEmitLineStreamLabel</a>, <a href="#a61c979932b890df773ce75013b76708b">getContext</a> and <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a62f7e21c9dac9e7acb4fdd713e712d20">llvm::MCContext::getMCDwarfLineTable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a97a8d7833400582f801ce932f7b59261">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitDwarfLocLabelDirective</a>.</p>

</div>
</div>

### emitDwarfUnitLength() {#a392206962fc4ac790aede10497c7e10b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitDwarfUnitLength (uint64_t Length, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Comment)</td>
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

<p>Emit a unit length field.</p>


<p>The actual format, DWARF32 or DWARF64, is chosen according to the settings.</p>


<p>Declaration at line 1126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1072 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="#a64eafd6bed9f342e423e74a93223135c">AddComment</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#af37a255a9a1f06e51c27b3a5a5c7baf4a8cff646c8838f1f3e3e948bd985ee5f4">llvm::dwarf::DW_LENGTH_lo_reserved</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a34b4d38e06d609b405f4a79c223ed8d2">llvm::dwarf::DWARF64</a>, <a href="#a971830cc1546210be8cc86fa568be8d0">emitIntValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa234436b20c856bcf616330ffcad6939">llvm::dwarf::getDwarfOffsetByteSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a> and <a href="#acde9e2a59908e8d8a4082d1869f6c08e">maybeEmitDwarf64Mark</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableheader/#a1b87cc4b647fd0f14ea7c46227ae2d58">llvm::MCDwarfLineTableHeader::Emit</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#aa5d953a682bfa6d424f05dca8d56b9ed">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitDwarfUnitLength</a> and <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a8f4b96f764a5ad6bcb7a3e0c0e4ee339">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitDwarfUnitLength</a>.</p>

</div>
</div>

### emitDwarfUnitLength() {#ad5bed3c2d5a90c1dc5433064c8f25e2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MCStreamer::emitDwarfUnitLength (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Prefix, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Comment)</td>
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

<p>Emit a unit length field.</p>


<p>The actual format, DWARF32 or DWARF64, is chosen according to the settings. Return the end symbol generated inside, the caller needs to emit it.</p>


<p>Declaration at line 1131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1080 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="#a64eafd6bed9f342e423e74a93223135c">AddComment</a>, <a href="#a8061d1e593a8f095f0efe3ba0d793531">emitAbsoluteSymbolDiff</a>, <a href="#a822ae1a4f19b7b00a297a100749f9b8a">emitLabel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa234436b20c856bcf616330ffcad6939">llvm::dwarf::getDwarfOffsetByteSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a> and <a href="#acde9e2a59908e8d8a4082d1869f6c08e">maybeEmitDwarf64Mark</a>.</p>

</div>
</div>

### emitFileDirective() {#adc44b704cc4e507e33afd71ff56a9181}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitFileDirective (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename)</td>
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

<p>Switch to a new logical file.</p>


<p>This is used to implement the '.file "foo.c"' assembler directive.</p>


<p>Declaration at line 878 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1210 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>

</div>
</div>

### emitFileDirective() {#a81434cde0572b8653405b032c0bdf6f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitFileDirective (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CompilerVersion, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TimeStamp, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Description)</td>
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

<p>Emit ".file assembler diretive with additioal info.</p>

<p>Declaration at line 881 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1211 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>

</div>
</div>

### emitIdent() {#a7c40663d4b1c9cdffcf2b82fc498cede}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCStreamer::emitIdent (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> IdentString)</td>
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

<p>Emit the "identifiers" directive.</p>


<p>This implements the '.ident "version foo"' assembler directive.</p>


<p>Definition at line 886 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>

</div>
</div>

### emitInstruction() {#a2e263d122b10b0bcc1bbf6c63202208c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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

<p>Emit the given <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a></span> into the current section.</p>

<p>Declaration at line 1088 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1145 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ac9408fbc60922d24b01c1efcbd4ba52b">llvm::MCOperand::getExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a3c5c7109f398fdca515509e2284cd8c0">llvm::MCInst::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ae23b2e8269fe15dbe5ebb3394438960c">llvm::MCOperand::isExpr</a> and <a href="#afb2fc7b7b30a601f94f8f5a6297ec68f">visitUsedExpr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcasmprinter-cpp/#aaaec30cb8a497bd67f31b3a32d5e2626">EmitBinary</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp/#a3063fa549eed52187dad621a5646bf4e">emitBinary</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp/#a5e94665a52b9daea5f22841f60760ab2">emitBSIC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcasmprinter-cpp/#a32deff36e6005bee8b6db8bd36353703">EmitCall</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a7ff09aba59d7dcc5dd800735494b14ff">llvm::MipsTargetStreamer::emitII</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp/#acc5831f0eaa7631d3dfeda1204813426">emitLEASLrri</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp/#a58c5b4dc239b80405dfe9abdad268555">emitLEASLzzi</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp/#a3812bc25ff6681233201a4c9187dec75">emitLEAzii</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp/#a9fd6a23b5a2ab5b7dc3f202529479a80">emitLEAzzi</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#ab371721ad31c3a0d4e5eb8fce0e8a13a">emitNop</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a49ba9fd9824c6910d3f66c1ae4469891">llvm::MipsTargetStreamer::emitR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcasmprinter-cpp/#aad58c68abd46a14fdb1cac72bc5b863a">EmitRDPC</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a09e7b7665f50b4338f746a50f6a454b1">llvm::MipsTargetStreamer::emitRRIII</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#abbac3ade2206cc952cf43e2ca4566201">llvm::MipsTargetStreamer::emitRRRX</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a8b10941b3ac644fb3508bc6cdc8aa6d5">llvm::MipsTargetStreamer::emitRRX</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a2b33055c2d9eb274c2d980428f7a1c24">llvm::MipsTargetStreamer::emitRX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcasmprinter-cpp/#a52cbef23880440f08e43fb0818d3ffb4">EmitSETHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp/#a28d8abbfedd338d44a39887939340b91">emitSIC</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#ad227b3ae621f2b01c29ad057c72348e3">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::EmitToStreamer</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a5e63efacfada7893569172b201e4f145">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::EmitToStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1b02eda9bb97934fbcc3d7f29219b931">llvm::AsmPrinter::EmitToStreamer</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a6bffa32d06d1516ee01e79b5a250c72e">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::matchAndEmitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#a25385ca3fbc7a797f0786eb6e4faf8bf">anonymous{ARMAsmParser.cpp}::ARMAsmParser::matchAndEmitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a0b228c0975660d76b206b2f9220b3cc3">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::matchAndEmitInstruction</a> and <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#abeebd6c3e48c1d92d186d8ffafbf5e2b">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::matchAndEmitInstruction</a>.</p>

</div>
</div>

### emitLineTableLabel() {#a03e59500b09326087aab0f3aa60a1491}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MCStreamer::emitLineTableLabel ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mclinesection/#adb3f95e8068932c0460a81a45224d0c5">llvm::MCLineSection::addLineEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a299bf2f0329389424760f4a7c8af75ac">llvm::MCContext::createTempSymbol</a>, <a href="#a61c979932b890df773ce75013b76708b">getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ae2fe3b101fb1f6389502b5d4f99c0640">llvm::MCContext::getCurrentDwarfLoc</a>, <a href="#ae1b3cf074436ef5b527071540e13bd58">getCurrentSectionOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a62f7e21c9dac9e7acb4fdd713e712d20">llvm::MCContext::getMCDwarfLineTable</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#a66906cd74b89bb0c1599d37b1188f820">llvm::MCDwarfLineTable::getMCLineSections</a>.</p>

</div>
</div>

### emitPseudoProbe() {#ab314a3ba8aff83e9e0f49248b37993fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitPseudoProbe (uint64_t Guid, uint64_t Index, uint64_t Type, uint64_t Attr, uint64_t Discriminator, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a79515c0650a49e9a7ae8ed6e228b8816">MCPseudoProbeInlineStack</a> &amp; InlineStack, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * FnSym)</td>
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

<p>Emit the a pseudo probe into the current section.</p>

<p>Declaration at line 1091 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1152 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="#a822ae1a4f19b7b00a297a100749f9b8a">emitLabel</a>, <a href="#a61c979932b890df773ce75013b76708b">getContext</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af59335be18fa802d111a646be658b7d0acb957607a78494ea70db887d1463437c">llvm::Guid</a>.</p>

</div>
</div>

### emitRawText() {#ae5807cb4b1f712252faa7d31f9d19815}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitRawText (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; String)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this file is backed by a assembly streamer, this dumps the specified string in the output .s file.</p>


<p>This capability is indicated by the <a href="#a4166e064169ce7f347f8e7f6379a8d58">hasRawTextSupport()</a> predicate. By default this aborts.</p>


<p>Declaration at line 1112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1042 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="#af8a7a5708bc0202abdf986fd3662d5d4">emitRawTextImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetstreamer/#adb5ac57549aefcb26369577e15a0827e">llvm::NVPTXTargetStreamer::closeLastSection</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#afa88bfe9ae2423322c5a88908de8ba22">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitDwarfFile0Directive</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetstreamer/#a842bdc7907a4a2f22892f197cc10e6ff">llvm::NVPTXTargetStreamer::outputDwarfFileDirectives</a> and <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#aa2807954a9bf3d29ba94545ebaa23584">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::tryEmitDwarfFileDirective</a>.</p>

</div>
</div>

### emitRelocDirective() {#a7504912d9010deac6ce9b8303932ec7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::optional&lt; std::pair&lt; bool, std::string &gt; &gt; llvm::MCStreamer::emitRelocDirective (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> &amp; Offset, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> a relocation described by the .reloc directive.</p>


<p>Return std::nullopt if succeeded. Otherwise, return a pair (Name is invalid, error message).</p>


<p>Definition at line 1079 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsasmprinter-cpp/#a487192753b68b0e4380e9d999a5b1549">emitDirectiveRelocJalr</a>.</p>

</div>
</div>

### emitSyntaxDirective() {#a1c521392edcf2a717c4b64f496e6234a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitSyntaxDirective ()</td>
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



<p>Declaration at line 1074 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 903 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>

</div>
</div>

### emitWinCFIAllocStack() {#ad9bb2bc90c804c28497604ae91e27bd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitWinCFIAllocStack (unsigned Size, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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



<p>Declaration at line 1052 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 943 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/win64eh/instruction/#ae298191528a9da3e5cee7ca83be92ef6">llvm::Win64EH::Instruction::Alloc</a>, <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a>, <a href="#ac6673eacba606285dd63d8d1669054bd">EnsureValidWinFrameInfo</a>, <a href="#a61c979932b890df773ce75013b76708b">getContext</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/#a10bcb4d81ba20e479977a46859383c93">llvm::WinEH::FrameInfo::Instructions</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aac3107671801e6bb16ef896f382759cd">llvm::MCContext::reportError</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#aecf41e0f616b168c70d4d7e1c5b12b19">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitWinCFIAllocStack</a>.</p>

</div>
</div>

### emitWinCFIEndChained() {#a9b6d232a4258f0dd9f16ee5b4f558633}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitWinCFIEndChained (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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



<p>Declaration at line 1048 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 814 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/#ad3a22752aee826b818d5551d6e8223f8">llvm::WinEH::FrameInfo::ChainedParent</a>, <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/#a903feaabd8052ae8912489b117410c0b">llvm::WinEH::FrameInfo::End</a>, <a href="#ac6673eacba606285dd63d8d1669054bd">EnsureValidWinFrameInfo</a>, <a href="#a61c979932b890df773ce75013b76708b">getContext</a> and <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aac3107671801e6bb16ef896f382759cd">llvm::MCContext::reportError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a4606f6d1acb29e734341e0bc78655356">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitWinCFIEndChained</a>.</p>

</div>
</div>

### emitWinCFIEndProc() {#a9d158c6b4a4302d51fd73aac4075086d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitWinCFIEndProc (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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



<p>Declaration at line 1041 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 772 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/#ad3a22752aee826b818d5551d6e8223f8">llvm::WinEH::FrameInfo::ChainedParent</a>, <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a>, <a href="#a21ea491f02f702c611739ad96e9dcf06">emitWindowsUnwindTables</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/#a903feaabd8052ae8912489b117410c0b">llvm::WinEH::FrameInfo::End</a>, <a href="#ac6673eacba606285dd63d8d1669054bd">EnsureValidWinFrameInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/#a7dbf869e6530d63af83a9670c54d5988">llvm::WinEH::FrameInfo::FuncletOrFuncEnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="#a61c979932b890df773ce75013b76708b">getContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aac3107671801e6bb16ef896f382759cd">llvm::MCContext::reportError</a>, <a href="#ac4f84451dc4abc997c960d484953b1d2">switchSection</a> and <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/#a4b99476d993dc06160c03b820cc94b11">llvm::WinEH::FrameInfo::TextSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a0fd5e1b1e4d675662b464bbf587e8054">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitWinCFIEndProc</a>.</p>

</div>
</div>

### emitWinCFIEndProlog() {#a9b9f4aa69270161dc91d76e3080e6dd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitWinCFIEndProlog (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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



<p>Declaration at line 1058 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1006 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a>, <a href="#ac6673eacba606285dd63d8d1669054bd">EnsureValidWinFrameInfo</a> and <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/#a61dd603885e6fe75a133f68362c82c2d">llvm::WinEH::FrameInfo::PrologEnd</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a0ec5db274b0af678a8e45ccf25b89690">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitWinCFIEndProlog</a>.</p>

</div>
</div>

### emitWinCFIFuncletOrFuncEnd() {#aac38128831e5c5377b98fd32d4f53fc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitWinCFIFuncletOrFuncEnd (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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

<p>This is used on platforms, such as Windows on ARM64, that require function or funclet sizes to be emitted in .xdata before the End marker is emitted for the frame.</p>


<p>We cannot use the End marker, as it is not set at the point of emitting .xdata, in order to indicate that the frame is active.</p>


<p>Declaration at line 1046 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 790 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/#ad3a22752aee826b818d5551d6e8223f8">llvm::WinEH::FrameInfo::ChainedParent</a>, <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a>, <a href="#ac6673eacba606285dd63d8d1669054bd">EnsureValidWinFrameInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/#a7dbf869e6530d63af83a9670c54d5988">llvm::WinEH::FrameInfo::FuncletOrFuncEnd</a>, <a href="#a61c979932b890df773ce75013b76708b">getContext</a> and <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aac3107671801e6bb16ef896f382759cd">llvm::MCContext::reportError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#af9a5dce582cf654f096cdad605ea38ce">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitWinCFIFuncletOrFuncEnd</a>.</p>

</div>
</div>

### emitWinCFIPushFrame() {#a4c579bc3d70f8f348c3ddf8224a31220}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitWinCFIPushFrame (bool Code, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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



<p>Declaration at line 1057 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 992 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a>, <a href="#ac6673eacba606285dd63d8d1669054bd">EnsureValidWinFrameInfo</a>, <a href="#a61c979932b890df773ce75013b76708b">getContext</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/#a10bcb4d81ba20e479977a46859383c93">llvm::WinEH::FrameInfo::Instructions</a>, <a href="/web-llvm/docs/api/structs/llvm/win64eh/instruction/#a6259bc5c7b25a62271edf4c462d30c91">llvm::Win64EH::Instruction::PushMachFrame</a> and <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aac3107671801e6bb16ef896f382759cd">llvm::MCContext::reportError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#af38a4d16a207c3672f2e06d2f8897915">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitWinCFIPushFrame</a>.</p>

</div>
</div>

### emitWinCFIPushReg() {#a1d0c21ad8ad54697f00aab2c37d77e25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitWinCFIPushReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Register, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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



<p>Declaration at line 1049 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 909 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp/#aa393c949f47f42880e9be43c46254ffe">encodeSEHRegNum</a>, <a href="#ac6673eacba606285dd63d8d1669054bd">EnsureValidWinFrameInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/#a10bcb4d81ba20e479977a46859383c93">llvm::WinEH::FrameInfo::Instructions</a> and <a href="/web-llvm/docs/api/structs/llvm/win64eh/instruction/#a6162447a68b07ae0c7ac50e0b2152c57">llvm::Win64EH::Instruction::PushNonVol</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a8c2773f2fd46f185d617c084afa98ab6">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitWinCFIPushReg</a>.</p>

</div>
</div>

### emitWinCFISaveReg() {#a9a30cc0783819b780c3e357162b90aec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitWinCFISaveReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Register, unsigned Offset, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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



<p>Declaration at line 1053 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 960 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp/#aa393c949f47f42880e9be43c46254ffe">encodeSEHRegNum</a>, <a href="#ac6673eacba606285dd63d8d1669054bd">EnsureValidWinFrameInfo</a>, <a href="#a61c979932b890df773ce75013b76708b">getContext</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/#a10bcb4d81ba20e479977a46859383c93">llvm::WinEH::FrameInfo::Instructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aac3107671801e6bb16ef896f382759cd">llvm::MCContext::reportError</a> and <a href="/web-llvm/docs/api/structs/llvm/win64eh/instruction/#acdd5a7e265ee374819dc4039e2fae01e">llvm::Win64EH::Instruction::SaveNonVol</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a1dfc20c93c509c1d196cdf0e8e66acae">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitWinCFISaveReg</a>.</p>

</div>
</div>

### emitWinCFISaveXMM() {#a5755faab671780e6c1abcaa95f05fe0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitWinCFISaveXMM (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Register, unsigned Offset, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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



<p>Declaration at line 1055 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 977 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp/#aa393c949f47f42880e9be43c46254ffe">encodeSEHRegNum</a>, <a href="#ac6673eacba606285dd63d8d1669054bd">EnsureValidWinFrameInfo</a>, <a href="#a61c979932b890df773ce75013b76708b">getContext</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/#a10bcb4d81ba20e479977a46859383c93">llvm::WinEH::FrameInfo::Instructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aac3107671801e6bb16ef896f382759cd">llvm::MCContext::reportError</a> and <a href="/web-llvm/docs/api/structs/llvm/win64eh/instruction/#a240406f5d649c95da66daf851f871c01">llvm::Win64EH::Instruction::SaveXMM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#af831d087fdf1bd0af05bb382182593f4">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitWinCFISaveXMM</a>.</p>

</div>
</div>

### emitWinCFISetFrame() {#acd1f092159870d525f916e3296341d92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitWinCFISetFrame (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Register, unsigned Offset, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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



<p>Declaration at line 1050 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 921 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp/#aa393c949f47f42880e9be43c46254ffe">encodeSEHRegNum</a>, <a href="#ac6673eacba606285dd63d8d1669054bd">EnsureValidWinFrameInfo</a>, <a href="#a61c979932b890df773ce75013b76708b">getContext</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/#a10bcb4d81ba20e479977a46859383c93">llvm::WinEH::FrameInfo::Instructions</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/#a34ce7a08ba73569d91074067557badcb">llvm::WinEH::FrameInfo::LastFrameInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aac3107671801e6bb16ef896f382759cd">llvm::MCContext::reportError</a> and <a href="/web-llvm/docs/api/structs/llvm/win64eh/instruction/#aef7a47bd8f81f98a227fd2b620677aac">llvm::Win64EH::Instruction::SetFPReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a99577354457a83f041f80baf798d507e">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitWinCFISetFrame</a>.</p>

</div>
</div>

### emitWinCFIStartChained() {#af4abf3b216995cecfbe8fcbc05d5b128}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitWinCFIStartChained (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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



<p>Declaration at line 1047 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 801 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a>, <a href="#ac6673eacba606285dd63d8d1669054bd">EnsureValidWinFrameInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/#a22c0c4f7c23db94945872dfe14fa32bc">llvm::WinEH::FrameInfo::Function</a> and <a href="#ae1b3cf074436ef5b527071540e13bd58">getCurrentSectionOnly</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a2ce02f7cd680caa9cdc9d19decbec097">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitWinCFIStartChained</a>.</p>

</div>
</div>

### emitWinCFIStartProc() {#a7787897c604e14c9e152c890e019e3bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitWinCFIStartProc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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



<p>Declaration at line 1040 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 754 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="#a2168a8bae9fa55fb113c07c2f66c11f3">emitCFILabel</a>, <a href="#a61c979932b890df773ce75013b76708b">getContext</a>, <a href="#ae1b3cf074436ef5b527071540e13bd58">getCurrentSectionOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aac3107671801e6bb16ef896f382759cd">llvm::MCContext::reportError</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ac158349781823fe8ff9e02d3a3533d55">llvm::MCAsmInfo::usesWindowsCFI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a1f68951e04ae06a7a386f17a3a7d1cb5">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitWinCFIStartProc</a>.</p>

</div>
</div>

### emitWinEHHandler() {#a26b51b14a3b7ce5cd6abe0c45872dd60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitWinEHHandler (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym, bool Unwind, bool Except, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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



<p>Declaration at line 1059 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 828 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/#ad3a22752aee826b818d5551d6e8223f8">llvm::WinEH::FrameInfo::ChainedParent</a>, <a href="#ac6673eacba606285dd63d8d1669054bd">EnsureValidWinFrameInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/#aedf13f4ef70fa51f00bb5630a614a3a2">llvm::WinEH::FrameInfo::ExceptionHandler</a>, <a href="#a61c979932b890df773ce75013b76708b">getContext</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/#a17e287f93ec6896736889b79ee26fe5c">llvm::WinEH::FrameInfo::HandlesExceptions</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/#a7b87fca779478e43ebc01beea784f589">llvm::WinEH::FrameInfo::HandlesUnwind</a> and <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aac3107671801e6bb16ef896f382759cd">llvm::MCContext::reportError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#adb765c6ee407ec7777308406d9fbcf30">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitWinEHHandler</a>.</p>

</div>
</div>

### emitWinEHHandlerData() {#a4e42517f705e57c03ce078fcac4e8f19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitWinEHHandlerData (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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



<p>Declaration at line 1061 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 845 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/#ad3a22752aee826b818d5551d6e8223f8">llvm::WinEH::FrameInfo::ChainedParent</a>, <a href="#ac6673eacba606285dd63d8d1669054bd">EnsureValidWinFrameInfo</a>, <a href="#a61c979932b890df773ce75013b76708b">getContext</a> and <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aac3107671801e6bb16ef896f382759cd">llvm::MCContext::reportError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64wincoffstreamer-cpp-/aarch64wincoffstreamer/#acd5116daf50e7e1c389362e6eb3fdc55">anonymous{AArch64WinCOFFStreamer.cpp}::AArch64WinCOFFStreamer::emitWinEHHandlerData</a>, <a href="/web-llvm/docs/api/classes/anonymous-armwincoffstreamer-cpp-/armwincoffstreamer/#a7b5e7e0450cf8617925650846ac8bcba">anonymous{ARMWinCOFFStreamer.cpp}::ARMWinCOFFStreamer::emitWinEHHandlerData</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a27ab1f18a7bff8a82c03e03302227f0d">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitWinEHHandlerData</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86wincoffstreamer-cpp-/x86wincoffstreamer/#ac9cc92c8097ae0b54e91ea99f5cebec1">anonymous{X86WinCOFFStreamer.cpp}::X86WinCOFFStreamer::emitWinEHHandlerData</a>.</p>

</div>
</div>

### EnsureValidWinFrameInfo() {#ac6673eacba606285dd63d8d1669054bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WinEH::FrameInfo * MCStreamer::EnsureValidWinFrameInfo (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Retrieve the current frame info if one is available and it is not yet closed.</p>


<p>Otherwise, issue an error and return null.</p>


<p>Declaration at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 739 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="#a61c979932b890df773ce75013b76708b">getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aac3107671801e6bb16ef896f382759cd">llvm::MCContext::reportError</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ac158349781823fe8ff9e02d3a3533d55">llvm::MCAsmInfo::usesWindowsCFI</a>.</p>


<p>Referenced by <a href="#ad9bb2bc90c804c28497604ae91e27bd7">emitWinCFIAllocStack</a>, <a href="#a9b6d232a4258f0dd9f16ee5b4f558633">emitWinCFIEndChained</a>, <a href="#a9d158c6b4a4302d51fd73aac4075086d">emitWinCFIEndProc</a>, <a href="#a9b9f4aa69270161dc91d76e3080e6dd2">emitWinCFIEndProlog</a>, <a href="#aac38128831e5c5377b98fd32d4f53fc9">emitWinCFIFuncletOrFuncEnd</a>, <a href="#a4c579bc3d70f8f348c3ddf8224a31220">emitWinCFIPushFrame</a>, <a href="#a1d0c21ad8ad54697f00aab2c37d77e25">emitWinCFIPushReg</a>, <a href="#a9a30cc0783819b780c3e357162b90aec">emitWinCFISaveReg</a>, <a href="#a5755faab671780e6c1abcaa95f05fe0b">emitWinCFISaveXMM</a>, <a href="#acd1f092159870d525f916e3296341d92">emitWinCFISetFrame</a>, <a href="#af4abf3b216995cecfbe8fcbc05d5b128">emitWinCFIStartChained</a>, <a href="#a26b51b14a3b7ce5cd6abe0c45872dd60">emitWinEHHandler</a> and <a href="#a4e42517f705e57c03ce078fcac4e8f19">emitWinEHHandlerData</a>.</p>

</div>
</div>

### finish() {#afa4bd753124bc1895e37282afa974972}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::finish (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> EndLoc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finish emission of machine code.</p>

<p>Declaration at line 1117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1051 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#a7ef22747429dbc0220aa542d347b1cfa">llvm::MCTargetStreamer::finish</a>, <a href="#a15061bc6db87126d5031f573f723947d">finishImpl</a>, <a href="#a61c979932b890df773ce75013b76708b">getContext</a>, <a href="#a901607e60c20148ae701b6e8f43b4647">getTargetStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aac3107671801e6bb16ef896f382759cd">llvm::MCContext::reportError</a>.</p>

</div>
</div>

### finishImpl() {#a15061bc6db87126d5031f573f723947d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::finishImpl ()</td>
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

<p>Declaration at line 1115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1285 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Referenced by <a href="#afa4bd753124bc1895e37282afa974972">finish</a>.</p>

</div>
</div>

### generateCompactUnwindEncodings() {#a1b01021cc37aeebcdb85e5e9f955507c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::generateCompactUnwindEncodings (<a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> * MAB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#af6776c07e68bae2bdd5e9da1b1a9db67">llvm::MCAsmBackend::generateCompactUnwindEncoding</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcdwarfframeemitter/#a6db5460aea8388ba1f9bec6c47f6c741">llvm::MCDwarfFrameEmitter::Emit</a>.</p>

</div>
</div>

### getAllowAutoPadding() {#abe6e1da30a7eb4225a89e27462ff6338}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCStreamer::getAllowAutoPadding ()</td>
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



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>

</div>
</div>

### getAssemblerPtr() {#a4ef5ffac1974b503c8ec1b3172d37335}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MCAssembler * llvm::MCStreamer::getAssemblerPtr ()</td>
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



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Referenced by <a href="#a179d49e133edc4f825fe798450d24458">switchSection</a>.</p>

</div>
</div>

### getAssociatedPDataSection() {#a28fee3751eb70ba6768349da24ac79d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * MCStreamer::getAssociatedPDataSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * TextSec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the .pdata section used for the given section.</p>


<p>Typically the given section is either the main .text section or some other COMDAT .text section, but it may be any section containing code.</p>


<p>Declaration at line 1069 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 891 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="#a61c979932b890df773ce75013b76708b">getContext</a> and <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp/#a95d4c56e1e0262813f1d792a7c3a689b">getWinCFISection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/win64eh/arm64unwindemitter/#af344ffc71b7b9b6972bda73c603051a8">llvm::Win64EH::ARM64UnwindEmitter::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/win64eh/armunwindemitter/#ab428fc29f43b7cfc8e9059f4f3fc09fd">llvm::Win64EH::ARMUnwindEmitter::Emit</a> and <a href="/web-llvm/docs/api/classes/llvm/win64eh/unwindemitter/#a2325284fc9cfe14f9764717f5f0e4fb7">llvm::Win64EH::UnwindEmitter::Emit</a>.</p>

</div>
</div>

### getAssociatedXDataSection() {#a7304c7ee4dda7ad7b71afed08c070cd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * MCStreamer::getAssociatedXDataSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * TextSec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the .xdata section used for the given section.</p>

<p>Declaration at line 1072 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 897 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="#a61c979932b890df773ce75013b76708b">getContext</a> and <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp/#a95d4c56e1e0262813f1d792a7c3a689b">getWinCFISection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/win64eh/arm64unwindemitter/#af344ffc71b7b9b6972bda73c603051a8">llvm::Win64EH::ARM64UnwindEmitter::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/win64eh/armunwindemitter/#ab428fc29f43b7cfc8e9059f4f3fc09fd">llvm::Win64EH::ARMUnwindEmitter::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/win64eh/unwindemitter/#a2325284fc9cfe14f9764717f5f0e4fb7">llvm::Win64EH::UnwindEmitter::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/win64eh/arm64unwindemitter/#a23e988e2f737319fba0ad0f50b4791c3">llvm::Win64EH::ARM64UnwindEmitter::EmitUnwindInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/win64eh/armunwindemitter/#ae3581e58aa167be222e1d2b9c164b10a">llvm::Win64EH::ARMUnwindEmitter::EmitUnwindInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/win64eh/unwindemitter/#aaad7a7f0ae118b34d41f8ceed7136672">llvm::Win64EH::UnwindEmitter::EmitUnwindInfo</a> and <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a27ab1f18a7bff8a82c03e03302227f0d">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitWinEHHandlerData</a>.</p>

</div>
</div>

### getContext() {#a61c979932b890df773ce75013b76708b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext &amp; llvm::MCStreamer::getContext ()</td>
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



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64elfstreamer-cpp-/aarch64elfstreamer/#ab3c1d7ab672f0bd15bc00752eb7f8c4d">anonymous{AArch64ELFStreamer.cpp}::AArch64ELFStreamer::AArch64ELFStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/assemblerconstantpools/#acbc7759a8d05ed32ae7d656282f33545">llvm::AssemblerConstantPools::addEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpool/#a91eb97e39eb4e9b4befd1914be362617">llvm::CSKYConstantPool::addEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#a63aca47ba5a5a2895c8ffd1e262ced59">llvm::CodeViewContext::addFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a66a4df49046ec16dd9c64d36ba3cb62c">ARM64EmitRuntimeFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a6574f704d2fbd168f81e7552695170a8">ARM64EmitUnwindInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a0bd3fbe76161d42d7470f0dd7dd634de">ARM64EmitUnwindInfoForSegment</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a48d2597504af337577491cde138a142b">ARMEmitRuntimeFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#ab831cd4cdeb2330513a8ca4d3ad3f610">ARMEmitUnwindInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectstreamer-cpp/#a4303712ca7aca04be8e4a7d4499c65c9">buildSymbolDiff</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcpseudoprobe-cpp/#ae8c82ca37d5404ad87bfb83a207ea712">buildSymbolDiff</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcmachostreamer-cpp-/mcmachostreamer/#afb372de94b1d4298c2bd4518af8e14bd">anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::changeSection</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetstreamer/#ab7ccb3b4d754b7e2ab62aca1113ab56d">llvm::NVPTXTargetStreamer::changeSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a6f19f34683888bee863e73af9a082535">llvm::MCObjectStreamer::changeSectionImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#aa32035802671dce51123a77b96594506">checkARM64Instructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a1a64f841fb788b307e31f8a70e6c022a">checkARMInstructions</a>, <a href="#a79e4fddfcfc0d5ed30a1b811fcd17a6e">checkCVLocSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarfframeemitter/#a6db5460aea8388ba1f9bec6c47f6c741">llvm::MCDwarfFrameEmitter::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflineaddr/#a002e20f504cfcef55b84c4c7e5b2be68">llvm::MCDwarfLineAddr::Emit</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableheader/#a1b87cc4b647fd0f14ea7c46227ae2d58">llvm::MCDwarfLineTableHeader::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcgendwarfinfo/#af945d198ed58841b8d57f45a11e2987e">llvm::MCGenDwarfInfo::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#a89cdc6ed6476f39c32e5a49327bb692e">llvm::MCDwarfLineTable::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobe/#a4fbe96db8448f1711fd51c4f4601c063">llvm::MCPseudoProbe::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobesections/#a42ea134aa4f428e1a5be9ba304e84f4c">llvm::MCPseudoProbeSections::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobetable/#af165f606b60b68425ab228437d209753">llvm::MCPseudoProbeTable::emit</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#ab68ca7cc744c7d305f655930067e0a64">EmitAbsDifference</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#afe30d1dfbe988401ae6ded700dd877bc">llvm::MCObjectStreamer::emitAbsoluteSymbolDiff</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#aad8d06379b43b4e55d8cfc4908a486a9">llvm::MCObjectStreamer::emitAbsoluteSymbolDiffAsULEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpool/#a504a7be63300c2c61d79be758524a433">llvm::CSKYConstantPool::emitAll</a>, <a href="/web-llvm/docs/api/classes/llvm/mipselfstreamer/#a7a47959229fe5c4aadbc877fc12e4ba6">llvm::MipsELFStreamer::emitCFIEndProcImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mipselfstreamer/#a94cdaca7695af6f6b02f54297384088d">llvm::MipsELFStreamer::emitCFILabel</a>, <a href="#a886df281f466da825e86d3db00309322">emitCFILabelDirective</a>, <a href="#a11eed8ef0a19a4cd80fc06a8488061fd">emitCFIStartProc</a>, <a href="/web-llvm/docs/api/classes/llvm/mipselfstreamer/#a4048731284da0f5852f82e4032569370">llvm::MipsELFStreamer::emitCFIStartProcImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a1b7e117c34782423f4cab2396b42b059">llvm::MCWinCOFFStreamer::emitCOFFImgRel32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a296ba2dbfb0e9605f94744804b1612b9">llvm::MCWinCOFFStreamer::emitCOFFSafeSEH</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#ab111e0970f34dbb0c62ace14e515819c">llvm::MCWinCOFFStreamer::emitCOFFSecNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a4231cebc046e4dba7b742b6d31bd1d01">llvm::MCWinCOFFStreamer::emitCOFFSecOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a6dbbe16f1a57144b250b2b3ba1243e93">llvm::MCWinCOFFStreamer::emitCOFFSecRel32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a0cce678ce28a97e39af6a60a52daac7f">llvm::MCWinCOFFStreamer::emitCOFFSectionIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#ac26c6bea8d31cc52a500469bc470d0b6">llvm::MCWinCOFFStreamer::emitCOFFSymbolIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a29a3c5dc6082aabd411724f33011f795">llvm::MCELFStreamer::emitCommonSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a46ca451d0ba24a1a138f28bd71a72271">llvm::MCWinCOFFStreamer::emitCommonSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a7f014c82821d76aff471c10829f336c6">llvm::MCObjectStreamer::emitCVDefRangeDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#adf42e6aacb6951ef0ed334e1526d7678">llvm::MCObjectStreamer::emitCVFileChecksumOffsetDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#af3ddec166c838e59362d5b7a85f50384">llvm::MCObjectStreamer::emitCVFileChecksumsDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a11b1131686b3d58fdda416597ca504f8">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCVFileDirective</a>, <a href="#a33c2e7b8c7463f2698a3132452cc4d12">emitCVFileDirective</a>, <a href="#a13ac5fe9bbe382dd5e366288ba91fa43">emitCVFuncIdDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3590fc09ce2f93b9c19c488fb5cc3645">llvm::MCObjectStreamer::emitCVInlineLinetableDirective</a>, <a href="#aea7cedf9c3df1534425168ee9969871c">emitCVInlineSiteIdDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#af86cdbc272816dffaa30c62bdd8ec4b1">llvm::MCObjectStreamer::emitCVLinetableDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a61b27602b6cd429e5c1e226117c6da67">llvm::MCObjectStreamer::emitCVLocDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3b37cee5f8e850d8bbe6e9086a4e3733">llvm::MCObjectStreamer::emitCVStringTableDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#abc90108ce5ae990004afa894cc4721c4">llvm::MCObjectStreamer::emitDwarfAdvanceFrameAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a54209b3bf7b60434db4fdeeae0e5695c">llvm::MCObjectStreamer::emitDwarfAdvanceLineAddr</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#afa88bfe9ae2423322c5a88908de8ba22">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitDwarfFile0Directive</a>, <a href="#afc5440a8bfa25645fa1f58ee11a4394d">emitDwarfFile0Directive</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#aa72d5840fe6b92c329861c90b8a7c58c">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitDwarfLineEndEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a916d35fa28fa01868c717ca125a037af">llvm::MCObjectStreamer::emitDwarfLineEndEntry</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#abc85cf8fcb99aada0bb615989928b516">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitDwarfLineStartLabel</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#afbf8b87c2743700b4bc2f187d06c9a28">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitDwarfLocDirective</a>, <a href="#a43c1c961a6b54da9fccacdf1cf5fc38f">emitDwarfLocDirective</a>, <a href="#a29df2eab11142e7ff1e8ee74b0cb6322">emitDwarfLocLabelDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#aa5d953a682bfa6d424f05dca8d56b9ed">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitDwarfUnitLength</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a07c0db5089a287c91b8197cad7f2eeda">emitFDESymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#a73ba925c2a5e09782525ede9dc691059">llvm::CodeViewContext::emitFileChecksumOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#a43decaae146363e80c3ba5b685016bb5">llvm::CodeViewContext::emitFileChecksums</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a0fe2220852635deb479d9b7274750f5f">llvm::MCObjectStreamer::emitFill</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#aa660e7b419602632507f83ec8a1520aa">llvm::MCObjectStreamer::emitFill</a>, <a href="#af6a6f6142b6fd138cdc9e08217577c4d">emitFill</a>, <a href="/web-llvm/docs/api/classes/anonymous-armelfstreamer-cpp-/armelfstreamer/#a64c883532dcb4cc6bb2ef3b3f0ae0cad">anonymous{ARMELFStreamer.cpp}::ARMELFStreamer::emitFnEnd</a>, <a href="/web-llvm/docs/api/classes/anonymous-armelfstreamer-cpp-/armelfstreamer/#a79dfbf2591108f9b5c846187ec905eef">anonymous{ARMELFStreamer.cpp}::ARMELFStreamer::emitFnStart</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer/#a00e4f812d3f229d47f31c41cfddadddc">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::emitFPOData</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpostatemachine/#ac60cbf99d76cbbbbc3c094a7d78fb834">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOStateMachine::emitFrameDataRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#aa07427c984394cc2c4b4cf8b7158def4">llvm::AMDGPUAsmPrinter::emitFunctionBodyEnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#ae3810dff97d2b1f712f053e18a98f383">EmitGenDwarfAbbrev</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a1b98f9e375747640ed4f1f019b0558aa">EmitGenDwarfAranges</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#acd1c7609888ea3462f400dcfbca2e486">emitGenDwarfRanges</a>, <a href="/web-llvm/docs/api/classes/anonymous-armelfstreamer-cpp-/armelfstreamer/#a3076428f827ac1e84c8ffef025bd7d88">anonymous{ARMELFStreamer.cpp}::ARMELFStreamer::emitInst</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetstreamer/#a35fb67d88bdb317b8d0ed132e9403414">llvm::ARMTargetStreamer::emitInst</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a92d2d1c2ac97f1151ed8f38d854e8b34">llvm::MCObjectStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mipselfstreamer/#a4edf55e6bd046a52bbb7867d8a601e3c">llvm::MipsELFStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#a38dcf42330d1efcd03d0686ba7bbaf1d">anonymous{X86AsmBackend.cpp}::X86AsmBackend::emitInstructionBegin</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#a8c9b4bc17f742123fb67a743e46e11bc">anonymous{X86AsmBackend.cpp}::X86AsmBackend::emitInstructionEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a970c047f65898d76cc9a251f32a5b70c">llvm::MCObjectStreamer::emitInstToFragment</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a11156cb1f872cbe35d40c6f36a21d56f">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitIntValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a02ddab75d51b8f46e8e2327dbb0e367b">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitIntValueInHex</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a9e376ffce522c2c85b62c86d18867336">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitIntValueInHexWithPadding</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcmachostreamer-cpp-/mcmachostreamer/#a3a886379efdc1ac575d1a38dd8b01775">anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::emitLabel</a>, <a href="#a822ae1a4f19b7b00a297a100749f9b8a">emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#a3d5b340b9ff61eae3ea229bce6572678">llvm::CodeViewContext::emitLineTableForFunction</a>, <a href="#a03e59500b09326087aab0f3aa60a1491">emitLineTableLabel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcdwarf/#ad32db1a85072666827c900bee74761b1">llvm::mcdwarf::emitListsTableHeaderStart</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetelfstreamer/#a6b2f770d3a95aa3a96fdde70ad59fbbd">llvm::XtensaTargetELFStreamer::emitLiteral</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcmachostreamer-cpp-/mcmachostreamer/#ac361b5e6ec19ddb003ca8d13ad57354d">anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::emitLocalCommonSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a98ffe083ab6ade934683a26a65204179">llvm::MCWinCOFFStreamer::emitLocalCommonSymbol</a>, <a href="/web-llvm/docs/api/classes/anonymous-armelfstreamer-cpp-/armelfstreamer/#a83709b9d2961247a986101cd796eeca7">anonymous{ARMELFStreamer.cpp}::ARMELFStreamer::emitMovSP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armasmprinter-cpp/#a135ddd8bff5dd7ec257b04d1cdc9af2b">emitNonLazySymbolPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86asmprinter-cpp/#a135ddd8bff5dd7ec257b04d1cdc9af2b">emitNonLazySymbolPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3454c2fd75e206584250b36f28cf16e6">llvm::MCObjectStreamer::emitNops</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#ad8a1ae695b98f49601a5986f612da526">llvm::AArch64TargetStreamer::emitNoteSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#adf60d16739e1ceabb1cee9e9dede7ba5">llvm::MCDwarfLineTable::emitOne</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#aa5b673bb0b1684ee529dc9fcafd6167b">EmitPersonality</a>, <a href="#ab314a3ba8aff83e9e0f49248b37993fe">emitPseudoProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinestr/#ad325ab6e610eb8bd1f59534515561fdc">llvm::MCDwarfLineStr::emitRef</a>, <a href="/web-llvm/docs/api/classes/anonymous-armelfstreamer-cpp-/armelfstreamer/#af7b885257ab544caad5ce47c9939079d">anonymous{ARMELFStreamer.cpp}::ARMELFStreamer::emitRegSave</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a8dfc15625ed04fb03d221eaebf38fd56">llvm::MCObjectStreamer::emitRelocDirective</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#aa186dddb4125136ff27007f97e26759a">EmitRuntimeFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinestr/#a1578026c1ceb637e4b37023412f971ac">llvm::MCDwarfLineStr::emitSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a336e9d6670e6116965fdc68d16001f34">llvm::MCObjectStreamer::emitSLEB128Value</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#ad43adc5b7e0fcb43103dfe2e1acac4f2">llvm::CodeViewContext::emitStringTable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#acfe4f94dca14855495d5743fc3e60998">llvm::MCELFStreamer::emitSymbolAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a9387871e1bade9ef3f96c2469ec92fe0">EmitSymbolRefWithOfs</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a70e3e2288f783c384791e314b8e20231">EmitSymbolRefWithOfs</a>, <a href="#a7865bd61cd2c65b2d94c58dd1523bb75">emitSymbolValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3185de2c18363c09c6db8e3e1546c9f8">llvm::MCObjectStreamer::emitULEB128Value</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a5d75ea3f9831315ebdb816d70c58c30b">EmitUnwindInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/avrmcelfstreamer/#aa77f604b9e33cc0e95652bc4da85adae">llvm::AVRMCELFStreamer::emitValueForModiferKind</a>, <a href="/web-llvm/docs/api/classes/anonymous-armelfstreamer-cpp-/armelfstreamer/#afd1e58493361c4e4fee6d7faca43a225">anonymous{ARMELFStreamer.cpp}::ARMELFStreamer::emitValueImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a9ef24f653b777a160537ee3e1d824663">llvm::MCObjectStreamer::emitValueImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a21d70037ecf679b5f8d13af07f8f136a">llvm::MCObjectStreamer::emitValueToAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#afa1710373e558f872820ac40224ddae6">llvm::MCObjectStreamer::emitValueToOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#ac11138742df2a7103190a1955e6b7331">llvm::MCELFStreamer::emitWeakReference</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwasmstreamer/#ac85beb9165822c1f0510c92a3f340b35">llvm::MCWasmStreamer::emitWeakReference</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a24389fc33ea52e268a13e698afe9f718">llvm::MCWinCOFFStreamer::emitWeakReference</a>, <a href="#ad9bb2bc90c804c28497604ae91e27bd7">emitWinCFIAllocStack</a>, <a href="#a9b6d232a4258f0dd9f16ee5b4f558633">emitWinCFIEndChained</a>, <a href="#a9d158c6b4a4302d51fd73aac4075086d">emitWinCFIEndProc</a>, <a href="#aac38128831e5c5377b98fd32d4f53fc9">emitWinCFIFuncletOrFuncEnd</a>, <a href="#a4c579bc3d70f8f348c3ddf8224a31220">emitWinCFIPushFrame</a>, <a href="#a9a30cc0783819b780c3e357162b90aec">emitWinCFISaveReg</a>, <a href="#a5755faab671780e6c1abcaa95f05fe0b">emitWinCFISaveXMM</a>, <a href="#acd1f092159870d525f916e3296341d92">emitWinCFISetFrame</a>, <a href="#a7787897c604e14c9e152c890e019e3bf">emitWinCFIStartProc</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#adb765c6ee407ec7777308406d9fbcf30">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitWinEHHandler</a>, <a href="#a26b51b14a3b7ce5cd6abe0c45872dd60">emitWinEHHandler</a>, <a href="#a4e42517f705e57c03ce078fcac4e8f19">emitWinEHHandlerData</a>, <a href="/web-llvm/docs/api/classes/llvm/mcxcoffstreamer/#a74f3eb9157be6847f5bf0f9cd228ad01">llvm::MCXCOFFStreamer::emitXCOFFRefDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcmachostreamer-cpp-/mcmachostreamer/#af20b6581bfb880b0df6d552b229739f9">anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::emitZerofill</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#a36948c65344166574c860990801dc0a2">llvm::MCDwarfLineTable::endCurrentSeqAndEmitLineStreamLabel</a>, <a href="#ac6673eacba606285dd63d8d1669054bd">EnsureValidWinFrameInfo</a>, <a href="#afa4bd753124bc1895e37282afa974972">finish</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a5333321f84976a4bf06be40827ca62d8">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::finishImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#aa8d1c93368ccaad9bdc429b25633f943">llvm::MCObjectStreamer::finishImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a7f964c60245b61612ddd6509cba7eb74">llvm::MCWinCOFFStreamer::finishImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/recordstreamer/#ae36c2a9293b9a50a2870d02f93d7d202">llvm::RecordStreamer::flushSymverDirectives</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a46eb8d3c0aed8e455691e71a12c142fd">forceExpAbs</a>, <a href="#a28fee3751eb70ba6768349da24ac79d4">getAssociatedPDataSection</a>, <a href="#a7304c7ee4dda7ad7b71afed08c070cd8">getAssociatedXDataSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#ab521cbeeba5f775524447eec5b221d56">getDataAlignmentFactor</a>, <a href="#aa51d3a6818627c9f45797eeef1f1b91c">getDwarfLineTableSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a9e11e3c1ca2c5f957aa7a7a16ff40e24">llvm::MCAsmInfo::getExprForFDESymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcasminfo/#aca03cf4d1b04c7a87ec24725971e2605">llvm::RISCVMCAsmInfo::getExprForFDESymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcelfmcasminfo/#abc43ac9f2d903054af8e134b6eb37a9f">llvm::SparcELFMCAsmInfo::getExprForFDESymbol</a>, <a href="/web-llvm/docs/api/structs/llvm/aarch64mcasminfodarwin/#a1a05057cd3005401418d6bb6f4c53659">llvm::AArch64MCAsmInfoDarwin::getExprForPersonalitySymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcelfmcasminfo/#af21e68297b7ed966f286d8701beed510">llvm::SparcELFMCAsmInfo::getExprForPersonalitySymbol</a>, <a href="/web-llvm/docs/api/structs/llvm/x86-64mcasminfodarwin/#a2718196f3a76adab2b39bcdff3f3cb44">llvm::X86_64MCAsmInfoDarwin::getExprForPersonalitySymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#aa18d22b8d07f4376fcf7c00d5923422a">GetOptionalAbsDifference</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3558114ca72d34962abb28004d864b19">llvm::MCObjectStreamer::getOrCreateDataFragment</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#ae482cc4ee4cf4d5b4bfe6e1dde4f1ed8">getSizeForEncoding</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#aaab77f3694a5bc3b29ffbc6ce87444ad">GetSubDivExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmcelfstreamer/#a64f1accd42a5eb6c0d80c800e63123b9">llvm::HexagonMCELFStreamer::HexagonMCEmitCommonSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#add62de97c76582fbd18c47c44677ca12">llvm::MCELFStreamer::initSections</a>, <a href="#a203640eb7873f4e1da4c6acd32c6651c">initSections</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a28e4c026855f296e926e3feb231b5811">llvm::MCWinCOFFStreamer::initSections</a>, <a href="/web-llvm/docs/api/classes/llvm/mcgendwarflabelentry/#a741d0c6e829f284182bd9bbef0362e2d">llvm::MCGenDwarfLabelEntry::Make</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflineentry/#a7e7c37719e68c7bf9e494110a30cad90">llvm::MCDwarfLineEntry::make</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetelfstreamer/#a08e72085c1973f94f76c4444c65e35e5">llvm::MSP430TargetELFStreamer::MSP430TargetELFStreamer</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a34cd5a64eb935155249865a6f30bdc5d">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::popSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a085ffc1a6ae032696e1a665600f04124">llvm::MCObjectStreamer::reset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonasmprinter-cpp/#a462520f520e196eb7d97d2077f86a8e2">smallData</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetelfstreamer/#a6b855a9517fc684cfa6a43f414122f59">llvm::XtensaTargetELFStreamer::startLiteralSection</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a4712c0b6d11e44d06eea24bc7b786ca9">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::switchSection</a>, <a href="#a179d49e133edc4f825fe798450d24458">switchSection</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#aa2807954a9bf3d29ba94545ebaa23584">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::tryEmitDwarfFileDirective</a>, <a href="#a64d1f7d21e406e2796a9bb5afc3aa31e">tryEmitDwarfFileDirective</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7363e46d4dd6c78affffabaea0de482b">llvm::write</a>.</p>

</div>
</div>

### getDwarfFrameInfos() {#abe60a8e0d089fcaec6a2a453f8966105}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; MCDwarfFrameInfo &gt; MCStreamer::getDwarfFrameInfos ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcdwarfframeemitter/#a6db5460aea8388ba1f9bec6c47f6c741">llvm::MCDwarfFrameEmitter::Emit</a>.</p>

</div>
</div>

### getDwarfLineTableSymbol() {#aa51d3a6818627c9f45797eeef1f1b91c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MCStreamer::getDwarfLineTableSymbol (unsigned CUID)</td>
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



<p>Declaration at line 1008 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="#a61c979932b890df773ce75013b76708b">getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#adaca0ccb049c08dcbdbcb4e83c2e540d">llvm::MCDwarfLineTable::getLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a62f7e21c9dac9e7acb4fdd713e712d20">llvm::MCContext::getMCDwarfLineTable</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#a2c317cba2ab6f522d3ba0ccab353f2d6">llvm::MCDwarfLineTable::setLabel</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcgendwarfinfo/#af945d198ed58841b8d57f45a11e2987e">llvm::MCGenDwarfInfo::Emit</a> and <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a55febacdfb6b6c8b692186d32dbe96c2">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::getDwarfLineTableSymbol</a>.</p>

</div>
</div>

### getNumFrameInfos() {#a99c3f13b3e8fb365914125cd27c77ea3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MCStreamer::getNumFrameInfos ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#ad65b998727eb009e1a448a4aa3f2e1b3">llvm::MCObjectStreamer::emitFrames</a>.</p>

</div>
</div>

### getNumWinFrameInfos() {#a29cea003318c9d843e3dd2072ad87e80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCStreamer::getNumWinFrameInfos ()</td>
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



<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64wincoffstreamer-cpp-/aarch64wincoffstreamer/#a4fea67fe039acc76c5893c493af01847">anonymous{AArch64WinCOFFStreamer.cpp}::AArch64WinCOFFStreamer::emitWindowsUnwindTables</a>, <a href="/web-llvm/docs/api/classes/anonymous-armwincoffstreamer-cpp-/armwincoffstreamer/#af854cb2ae3c7a1e12a8c1dc30192b3a9">anonymous{ARMWinCOFFStreamer.cpp}::ARMWinCOFFStreamer::emitWindowsUnwindTables</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86wincoffstreamer-cpp-/x86wincoffstreamer/#a7f006effe83d65b1222fe3efcdb14973">anonymous{X86WinCOFFStreamer.cpp}::X86WinCOFFStreamer::emitWindowsUnwindTables</a>.</p>

</div>
</div>

### getStartTokLoc() {#a62c3894a85886838f32d8d23e003478f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc llvm::MCStreamer::getStartTokLoc ()</td>
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



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a76008de89dd2e472d78c4a8ca9771d45">llvm::MCELFStreamer::emitELFSymverDirective</a> and <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#acfe4f94dca14855495d5743fc3e60998">llvm::MCELFStreamer::emitSymbolAttribute</a>.</p>

</div>
</div>

### getTargetStreamer() {#a901607e60c20148ae701b6e8f43b4647}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCTargetStreamer * llvm::MCStreamer::getTargetStreamer ()</td>
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



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a39cca2331d86f73af9c4912dd603c70a">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::AArch64AsmParser</a>, <a href="/web-llvm/docs/api/classes/llvm/mipselfstreamer/#ab2beebc6dcbab3b3223a55482805605c">llvm::MipsELFStreamer::createPendingLabelRelocs</a>, <a href="#a04736ef5753e5ecda3c29ce902094e68">emitAssignment</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a807369cf0e8ddbe75c8c4a671bfc4258">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitBytes</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86wincoffstreamer-cpp-/x86wincoffstreamer/#aeb01424e28cb5be0737b318fa19ade93">anonymous{X86WinCOFFStreamer.cpp}::X86WinCOFFStreamer::emitCVFPOData</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#afa88bfe9ae2423322c5a88908de8ba22">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitDwarfFile0Directive</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a161ac460fefc16f98a8dd1a9f019af9a">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitInstruction</a>, <a href="#a822ae1a4f19b7b00a297a100749f9b8a">emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64-elftargetobjectfile/#a50239bad1326b962fc58f1b311e7e255">llvm::AArch64_ELFTargetObjectFile::emitPersonalityValueImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#ae37bcdd18e5b8eb58b8d88effad3fed8">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitValueImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a12f25c5e6e277f9ea32b81e0e871bb9c">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::ensureLocals</a>, <a href="#afa4bd753124bc1895e37282afa974972">finish</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a4712c0b6d11e44d06eea24bc7b786ca9">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::switchSection</a> and <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#aa2807954a9bf3d29ba94545ebaa23584">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::tryEmitDwarfFileDirective</a>.</p>

</div>
</div>

### getUseAssemblerInfoForParsing() {#a5ac5e1dcbd59f1f878ea94e03d483e50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCStreamer::getUseAssemblerInfoForParsing ()</td>
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



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a866922b584e8d73ad86444255886c82c">llvm::MCObjectStreamer::getAssemblerPtr</a>.</p>

</div>
</div>

### getWinFrameInfos() {#acd501c2b93172880cbeaf7e3ab0cc49d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; std::unique_ptr&lt; WinEH::FrameInfo &gt; &gt; llvm::MCStreamer::getWinFrameInfos ()</td>
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



<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/win64eh/arm64unwindemitter/#af344ffc71b7b9b6972bda73c603051a8">llvm::Win64EH::ARM64UnwindEmitter::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/win64eh/armunwindemitter/#ab428fc29f43b7cfc8e9059f4f3fc09fd">llvm::Win64EH::ARMUnwindEmitter::Emit</a> and <a href="/web-llvm/docs/api/classes/llvm/win64eh/unwindemitter/#a2325284fc9cfe14f9764717f5f0e4fb7">llvm::Win64EH::UnwindEmitter::Emit</a>.</p>

</div>
</div>

### hasUnfinishedDwarfFrameInfo() {#a29f026c7466847a38f5ca916d666af96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCStreamer::hasUnfinishedDwarfFrameInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>

</div>
</div>

### maybeEmitDwarf64Mark() {#acde9e2a59908e8d8a4082d1869f6c08e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::maybeEmitDwarf64Mark ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a special value of 0xffffffff if producing 64-bit debugging info.</p>

<p>Declaration at line 1122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1065 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="#a64eafd6bed9f342e423e74a93223135c">AddComment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#af37a255a9a1f06e51c27b3a5a5c7baf4adc3aedef0caeccf6d845a430da6d3f8d">llvm::dwarf::DW_LENGTH_DWARF64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a34b4d38e06d609b405f4a79c223ed8d2">llvm::dwarf::DWARF64</a> and <a href="#acc3817979bc871dba942b87773da1cc0">emitInt32</a>.</p>


<p>Referenced by <a href="#ad5bed3c2d5a90c1dc5433064c8f25e2d">emitDwarfUnitLength</a> and <a href="#a392206962fc4ac790aede10497c7e10b">emitDwarfUnitLength</a>.</p>

</div>
</div>

### mayHaveInstructions() {#a9453735a9b47b98c973c5bfa4b6a9203}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::MCStreamer::mayHaveInstructions (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> &amp; Sec)</td>
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



<p>Definition at line 1119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aa565526e57992a6482d7062b03933b99">llvm::MCContext::finalizeDwarfSections</a>.</p>

</div>
</div>

### reset() {#a86cecbfb6ca34c4a8b0dc349949fbba2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::reset ()</td>
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

<p>State management.</p>

<p>Declaration at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="#a9299fd6e2b7f540daa945aae967ffe47">CurFrag</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a2ae05dfd9a73d466a7c9279380fd3783">llvm::CodeGenTargetMachineImpl::createMCStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a085ffc1a6ae032696e1a665600f04124">llvm::MCObjectStreamer::reset</a>.</p>

</div>
</div>

### setAllowAutoPadding() {#a84e19f7283c7e529b0762e1fdd4ba8b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCStreamer::setAllowAutoPadding (bool v)</td>
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



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a528f3b8c204e96bf6a9b2680f22b4af6">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::MCAsmStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a9ad1da683a018add519fd96cd22cc785">llvm::MCObjectStreamer::MCObjectStreamer</a>.</p>

</div>
</div>

### setStartTokLocPtr() {#a2e1714ce6e48aa49f01169ea3e517661}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCStreamer::setStartTokLocPtr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> * Loc)</td>
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



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>

</div>
</div>

### setTargetStreamer() {#a5412ac22218512db53d55eea56777aac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCStreamer::setTargetStreamer (<a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer">MCTargetStreamer</a> * TS)</td>
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



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#acfff4f9a518231ee043200a694fcbafa">llvm::MCTargetStreamer::MCTargetStreamer</a>.</p>

</div>
</div>

### setUseAssemblerInfoForParsing() {#ab55c46222643a36d7e303f801ca720f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCStreamer::setUseAssemblerInfoForParsing (bool v)</td>
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



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>

</div>
</div>

### tryEmitDwarfFileDirective() {#a64d1f7d21e406e2796a9bb5afc3aa31e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; unsigned &gt; MCStreamer::tryEmitDwarfFileDirective (unsigned FileNo, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directory, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/md5/md5result">MD5::MD5Result</a> &gt; Checksum=std::nullopt, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; Source=std::nullopt, unsigned CUID=0)</td>
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

<p>Associate a filename with a specified logical file number.</p>


<p>Also associate a directory, optional checksum, and optional source text with the logical file. This implements the DWARF2 '.file 4 "dir/foo.c"' assembler directive, and the DWARF5 '.file 4 "dir/foo.c" md5 "..." source "..."' assembler directive.</p>


<p>Declaration at line 904 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="#a61c979932b890df773ce75013b76708b">getContext</a> and <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a3ad186547248b6c5236a8795cce3f477">llvm::MCContext::getDwarfFile</a>.</p>


<p>Referenced by <a href="#a4a16115d4363f1c16af9cfcb425ce0d5">emitDwarfFileDirective</a>.</p>

</div>
</div>

### visitUsedExpr() {#afb2fc7b7b30a601f94f8f5a6297ec68f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::visitUsedExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> &amp; Expr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1119 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606fad39c4375f2de701a811385670a699a51">llvm::MCExpr::Binary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606fa66e286cc65e62341501e5b26feade28d">llvm::MCExpr::Constant</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#af5d6e67c11188675c1309e098afac194">llvm::MCExpr::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a071993fe404ae3387526e7a104b0f38c">llvm::MCBinaryExpr::getLHS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a201920f46caa494d398931ef46788de2">llvm::MCBinaryExpr::getRHS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606fa8cbc19c1660252a30c030fa945999a91">llvm::MCExpr::SymbolRef</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606faa65560b8224a92e80f422df090f07c55">llvm::MCExpr::Target</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606fa5928e5c98f309a381e165e774c09f49e">llvm::MCExpr::Unary</a>, <a href="#afb2fc7b7b30a601f94f8f5a6297ec68f">visitUsedExpr</a> and <a href="#a105fc9d2996ff696bd68db1f9ebce6bb">visitUsedSymbol</a>.</p>


<p>Referenced by <a href="#a04736ef5753e5ecda3c29ce902094e68">emitAssignment</a>, <a href="#a2e263d122b10b0bcc1bbf6c63202208c">emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a8dfc15625ed04fb03d221eaebf38fd56">llvm::MCObjectStreamer::emitRelocDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmcelfstreamer/#a8c8aaade94f26b9991cee49ae53bdadb">llvm::HexagonMCELFStreamer::EmitSymbol</a>, <a href="#ae3d6e5ea7b855357014a16db766dddfd">emitValueImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64authmcexpr/#a93caf33eeff28bfb622085687c51231c">llvm::AArch64AuthMCExpr::visitUsedExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#a5979780bec8026d8fd6cb8bf024b3086">llvm::AArch64MCExpr::visitUsedExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#a3539e01cd4cfb4b9bf60489ae59a370b">llvm::AMDGPUMCExpr::visitUsedExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/armmcexpr/#aafad973d16f3579691084905db7c14ec">llvm::ARMMCExpr::visitUsedExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/avrmcexpr/#a1cbdbf8c7001200fa2399608397e5746">llvm::AVRMCExpr::visitUsedExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcexpr/#a627b3cf30a4dc300e6a3c2b445f1d258">llvm::CSKYMCExpr::visitUsedExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmcexpr/#aec934e512bcd861faf50a32379b571ed">llvm::HexagonMCExpr::visitUsedExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaimcexpr/#ac8a78c8701d31fa5042f12e33e3a29fc">llvm::LanaiMCExpr::visitUsedExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a88ce48054f6c130aef1bbe41be25c289">llvm::LoongArchMCExpr::visitUsedExpr</a>, <a href="#afb2fc7b7b30a601f94f8f5a6297ec68f">visitUsedExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#abbef3f35fd05b8f0929d5e9d00abd8f8">llvm::MipsMCExpr::visitUsedExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#ab93c7ad0736721cafb4eab9d99df20e5">llvm::PPCMCExpr::visitUsedExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a667256edf5e6bcb93ea674af7d41a8ce">llvm::RISCVMCExpr::visitUsedExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#a84606656d540381277112a534617ab22">llvm::SparcMCExpr::visitUsedExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmcexpr/#aacc62af78b3bd71f42ee35601c35a2b6">llvm::SystemZMCExpr::visitUsedExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/vemcexpr/#a9b434b7b50ec9cc59b53879dafc4af83">llvm::VEMCExpr::visitUsedExpr</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensamcexpr/#ab71cf3e5c83deec78c2340fb22ff55db">llvm::XtensaMCExpr::visitUsedExpr</a>.</p>

</div>
</div>

### visitUsedSymbol() {#a105fc9d2996ff696bd68db1f9ebce6bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::visitUsedSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; Sym)</td>
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



<p>Declaration at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1116 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Referenced by <a href="#afb2fc7b7b30a601f94f8f5a6297ec68f">visitUsedExpr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### changeSection() {#afd46c84fb0f1eef50c7c7d3b1bc23c87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::changeSection (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Section, uint32_t)</td>
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

<p>This is called by popSection and switchSection, if the current section changes.</p>

<p>Declaration at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1262 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="#a9299fd6e2b7f540daa945aae967ffe47">CurFrag</a>.</p>


<p>Referenced by <a href="#a216005880453270b48e5d5d7daeec6d4">popSection</a>, <a href="#ac4f84451dc4abc997c960d484953b1d2">switchSection</a> and <a href="#a05b1a7fa3b559a330d9830ec956a8383">switchSectionNoPrint</a>.</p>

</div>
</div>

### checkCVLocSection() {#a79e4fddfcfc0d5ed30a1b811fcd17a6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCStreamer::checkCVLocSection (unsigned FuncId, unsigned FileNo, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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

<p>Returns true if the .cv_loc directive is in the right section.</p>

<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="#a61c979932b890df773ce75013b76708b">getContext</a>, <a href="#ae1b3cf074436ef5b527071540e13bd58">getCurrentSectionOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a7bdf9164b69f96821c0c0269dde3ebf7">llvm::MCContext::getCVContext</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#a6c19ae3d8fe0211fe3ae87659d9ee378">llvm::CodeViewContext::getCVFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aac3107671801e6bb16ef896f382759cd">llvm::MCContext::reportError</a> and <a href="/web-llvm/docs/api/structs/llvm/mccvfunctioninfo/#a5a57622bc8d3165baf9cae9606a20c33">llvm::MCCVFunctionInfo::Section</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#ad0de5f7018dd4bdee0616920178ee0bc">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCVLocDirective</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a61b27602b6cd429e5c1e226117c6da67">llvm::MCObjectStreamer::emitCVLocDirective</a>.</p>

</div>
</div>

### emitCFIEndProcImpl() {#aa32eb827df6b7817d6c2ab91c47ad1e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCFIEndProcImpl (<a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo">MCDwarfFrameInfo</a> &amp; CurFrame)</td>
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



<p>Declaration at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 480 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#a4a28a7bafd6aef6062f253778813f217">llvm::MCDwarfFrameInfo::End</a>.</p>


<p>Referenced by <a href="#ac9b56ca50fc9b458d7c7b557addaf56e">emitCFIEndProc</a>.</p>

</div>
</div>

### emitCFIStartProcImpl() {#a578add9dde6ca4352c23f00369d1fa78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCFIStartProcImpl (<a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo">MCDwarfFrameInfo</a> &amp; Frame)</td>
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



<p>Declaration at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 469 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Referenced by <a href="#a11eed8ef0a19a4cd80fc06a8488061fd">emitCFIStartProc</a>.</p>

</div>
</div>

### emitRawTextImpl() {#af8a7a5708bc0202abdf986fd3662d5d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitRawTextImpl (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> String)</td>
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

<p>EmitRawText - If this file is backed by an assembly streamer, this dumps the specified string in the output .s file.</p>


<p>This capability is indicated by the <a href="#a4166e064169ce7f347f8e7f6379a8d58">hasRawTextSupport()</a> predicate.</p>


<p>Declaration at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1033 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a>.</p>


<p>Referenced by <a href="#ae5807cb4b1f712252faa7d31f9d19815">emitRawText</a>.</p>

</div>
</div>

### emitWindowsUnwindTables() {#aca120b9543ba85dae180419dbe65e88f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitWindowsUnwindTables (<a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo">WinEH::FrameInfo</a> * Frame)</td>
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



<p>Declaration at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1049 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>

</div>
</div>

### emitWindowsUnwindTables() {#a21ea491f02f702c611739ad96e9dcf06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitWindowsUnwindTables ()</td>
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



<p>Declaration at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1047 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Referenced by <a href="#a9d158c6b4a4302d51fd73aac4075086d">emitWinCFIEndProc</a>.</p>

</div>
</div>

### getCurrentWinFrameInfo() {#af2c1682a7f094bf9534d3461286aa62f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WinEH::FrameInfo * llvm::MCStreamer::getCurrentWinFrameInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64wincoffstreamer-cpp-/aarch64wincoffstreamer/#acd5116daf50e7e1c389362e6eb3fdc55">anonymous{AArch64WinCOFFStreamer.cpp}::AArch64WinCOFFStreamer::emitWinEHHandlerData</a>, <a href="/web-llvm/docs/api/classes/anonymous-armwincoffstreamer-cpp-/armwincoffstreamer/#a7b5e7e0450cf8617925650846ac8bcba">anonymous{ARMWinCOFFStreamer.cpp}::ARMWinCOFFStreamer::emitWinEHHandlerData</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a27ab1f18a7bff8a82c03e03302227f0d">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitWinEHHandlerData</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86wincoffstreamer-cpp-/x86wincoffstreamer/#ac9cc92c8097ae0b54e91ea99f5cebec1">anonymous{X86WinCOFFStreamer.cpp}::X86WinCOFFStreamer::emitWinEHHandlerData</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getCurrentDwarfFrameInfo() {#a2c7ec503acfcaa9dad0339ebf2acdfd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCDwarfFrameInfo * MCStreamer::getCurrentDwarfFrameInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### CurFrag {#a9299fd6e2b7f540daa945aae967ffe47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCFragment* llvm::MCStreamer::CurFrag = nullptr</td>
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



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Referenced by <a href="#afd46c84fb0f1eef50c7c7d3b1bc23c87">changeSection</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a161ac460fefc16f98a8dd1a9f019af9a">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitInstruction</a>, <a href="#a2f9393965bc0de69da6236c623f79579">getCurrentFragment</a>, <a href="#ae1b3cf074436ef5b527071540e13bd58">getCurrentSectionOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a941f547c39a7daf0a48452cc945a835c">llvm::MCObjectStreamer::insert</a> and <a href="#a86cecbfb6ca34c4a8b0dc349949fbba2">reset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AllowAutoPadding {#a3d15514f56f89f8f20ff140f090cdd62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCStreamer::AllowAutoPadding = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Is the assembler allowed to insert padding automatically?</p>


<p>For correctness reasons, we sometimes need to ensure instructions aren't separated in unexpected ways. At the moment, this feature is only useable from an integrated assembler, but assembly syntax is under discussion for future inclusion.</p>


<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>

</div>
</div>

### Context {#aa46f882d5f242b6fa0cf4d9ea864bd0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext&amp; llvm::MCStreamer::Context</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>

</div>
</div>

### CurrentProcWinFrameInfoStartIndex {#a177c1fb8aba5d3b1f8040662708b7439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::MCStreamer::CurrentProcWinFrameInfoStartIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>

</div>
</div>

### CurrentWinFrameInfo {#a9942cf8febde001f2e189fc87006d0e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WinEH::FrameInfo* llvm::MCStreamer::CurrentWinFrameInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>

</div>
</div>

### DwarfFrameInfos {#ab58083a464ba63d8d1f096baaef5f39e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MCDwarfFrameInfo&gt; llvm::MCStreamer::DwarfFrameInfos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>

</div>
</div>

### FrameInfoStack {#a3d60b06655802fdb80828097cfcf5bf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::pair&lt;size_t, MCSection *&gt;, 1&gt; llvm::MCStreamer::FrameInfoStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>

</div>
</div>

### NextWinCFIID {#ade99842665ed05fe305d9a6be88e19f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCStreamer::NextWinCFIID = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The next unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> to use when creating a WinCFI-related section (.pdata or .xdata).</p>


<p>This <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> ensures that we have a one-to-one mapping from code section to unwind info section, which MSVC's incremental linker requires.</p>


<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>

</div>
</div>

### SectionStack {#af944d06b31a30672c9808ff2a5d7bc7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::pair&lt;MCSectionSubPair, MCSectionSubPair&gt;, 4&gt; llvm::MCStreamer::SectionStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is stack of current and previous section values saved by pushSection.</p>

<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>

</div>
</div>

### StartTokLocPtr {#a222bc83759c25005a8086be15e7f9986}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SMLoc* llvm::MCStreamer::StartTokLocPtr = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pointer to the parser's <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> if available.</p>


<p>This is used to provide locations for diagnostics.</p>


<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>

</div>
</div>

### TargetStreamer {#accfcffbe239c8404d6454ebb0b129354}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MCTargetStreamer&gt; llvm::MCStreamer::TargetStreamer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>

</div>
</div>

### UseAssemblerInfoForParsing {#af7a7a4b080a1678499eb2d4b7d085535}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCStreamer::UseAssemblerInfoForParsing = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>

</div>
</div>

### WinFrameInfos {#a2c635366a7a2eb9b7189919df797b193}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;WinEH::FrameInfo&gt; &gt; llvm::MCStreamer::WinFrameInfos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Similar to DwarfFrameInfos, but for SEH unwind info.</p>


<p>Chained frames may refer to each other, so use std::unique_ptr to provide pointer stability.</p>


<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Assembly File Formatting.

### addBlankLine {#a06efd6f3d736ec481ab81ab2c574bbe6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCStreamer::addBlankLine ()</td>
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

<p>Emit a blank line to a .s file to pretty it up.</p>

<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a467c9de76e4b351317463d4c803cebc4">llvm::TargetLoweringObjectFileCOFF::emitModuleMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a3a90d46a868772348b417ed1a94b3a94">llvm::TargetLoweringObjectFileELF::emitModuleMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a7bdbc0657e52a4bffa675c290b32840f">llvm::TargetLoweringObjectFileMachO::emitModuleMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86asmprinter-cpp/#acda48e0ba94e27f00cbe44c1585fcfe7">emitNonLazyStubs</a> and <a href="/web-llvm/docs/api/classes/llvm/stackmaps/#a64f17d34c6ec33d574438b69fa43c2e2">llvm::StackMaps::serializeToStackMapSection</a>.</p>

</div>
</div>

### AddComment {#a64eafd6bed9f342e423e74a93223135c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCStreamer::AddComment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; T, bool EOL=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Add a textual comment.</p>


<p>Typically for comments that can be emitted to the generated .s file if applicable as a QoI issue to make the output of the compiler more readable. This only affects the MCAsmStreamer, and only when verbose assembly output is enabled.</p>


<p>If the comment includes embedded 
<br/>
's, they will each get the comment prefix as appropriate. The added comment should not end with a 
<br/>
. By default, each comment is terminated with an end of line, i.e. the EOL param is set to true by default. If one prefers not to end the comment with a new line then the EOL param should be passed with a false value.</p>


<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#a72515d2f0a6b48c9949ac83674b46a89">addConstantComments</a>, <a href="#ad5bed3c2d5a90c1dc5433064c8f25e2d">emitDwarfUnitLength</a>, <a href="#a392206962fc4ac790aede10497c7e10b">emitDwarfUnitLength</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#acd1c7609888ea3462f400dcfbca2e486">emitGenDwarfRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#a3d5b340b9ff61eae3ea229bce6572678">llvm::CodeViewContext::emitLineTableForFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcdwarf/#ad32db1a85072666827c900bee74761b1">llvm::mcdwarf::emitListsTableHeaderStart</a>, <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#af00b13d92054d7b6f7c8b4561f46685b">llvm::BTFTypeBase::emitType</a>, <a href="/web-llvm/docs/api/classes/llvm/btftypeenum64/#aeeff33f4503f3e3724197047123252d1">llvm::BTFTypeEnum64::emitType</a>, <a href="/web-llvm/docs/api/classes/llvm/btftypeint/#a223d1876a944b2ee9c675f502651a8a1">llvm::BTFTypeInt::emitType</a>, <a href="/web-llvm/docs/api/classes/llvm/btftypestruct/#a261288152d81e6ee565d7c68d175624e">llvm::BTFTypeStruct::emitType</a>, <a href="/web-llvm/docs/api/classes/anonymous-erlanggcprinter-cpp-/erlanggcprinter/#a574679a34186d5db3a7b14b0ce5c5078">anonymous{ErlangGCPrinter.cpp}::ErlangGCPrinter::finishAssembly</a>, <a href="#acde9e2a59908e8d8a4082d1869f6c08e">maybeEmitDwarf64Mark</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#a5bd11f377f141eaca592b06fff653370">printBroadcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#a60061d374eb7273d11025f881472a4d8">printExtend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#adf508d7280c5a6d9fb7d0e2cf2f426c4">printZeroExtend</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#a6132fb3423ce0d8846f93102d9658bc4">printZeroUpperMove</a>.</p>

</div>
</div>

### addExplicitComment {#a64e26e6dc161ab7e00bfd821fb39d3dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::addExplicitComment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; T)</td>
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

<p>Add explicit comment T.</p>


<p>T is required to be a valid comment in the output and does not need to be escaped.</p>


<p>Declaration at line 381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### emitExplicitComments {#ac56e340bfb6a2a3aea52b5f3caebdc05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitExplicitComments ()</td>
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

<p>Emit added explicit comments.</p>

<p>Declaration at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>

</div>
</div>

### emitRawComment {#a742a4502a505412b1a9e9b2af3900c49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitRawComment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; T, bool TabPrefix=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Print T and prefix it with the comment string (normally #) and optionally a tab.</p>


<p>This prints the comment immediately, not at the end of the current line. It is basically a safe version of EmitRawText: since it only prints comments, the object streamer ignores it instead of asserting.</p>


<p>Declaration at line 377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### getCommentOS {#a23e0190c3735e75eb0199bde954c90ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; MCStreamer::getCommentOS ()</td>
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

<p>Return a <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> that comments can be written to.</p>


<p>Unlike AddComment, you are required to terminate comments with 
<br/>
 if you use this method.</p>


<p>Declaration at line 371 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a8ad4ae565ad87db4c534952e2c88f310">llvm::nulls</a>.</p>

</div>
</div>

### hasRawTextSupport {#a4166e064169ce7f347f8e7f6379a8d58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::MCStreamer::hasRawTextSupport ()</td>
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

<p>Return true if this asm streamer supports emitting unformatted text to the .s file with EmitRawText.</p>

<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>

</div>
</div>

### isIntegratedAssemblerRequired {#a562dcaa292a9033237cd5cf3b78a12bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::MCStreamer::isIntegratedAssemblerRequired ()</td>
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

<p>Is the integrated assembler required for this streamer to function correctly?</p>

<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>

</div>
</div>

### isVerboseAsm {#a491d800694537cdc000beb47d6a3edc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::MCStreamer::isVerboseAsm ()</td>
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

<p>Return true if this streamer supports verbose assembly and if it is enabled.</p>

<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Symbol & Section Management

### beginCOFFSymbolDef {#a1c068ea06bd2ccfddfdceab7eda111aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::beginCOFFSymbolDef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol)</td>
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

<p>Declaration at line 537 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1204 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### emitAssemblerFlag {#a93568bb65eee43117c3c3a3e1e318bf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitAssemblerFlag (<a href="/web-llvm/docs/api/namespaces/llvm/#aa09571f0b44fd6bd8fae33d6ead290c1">MCAssemblerFlag</a> Flag)</td>
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

<p>Declaration at line 463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1201 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>

</div>
</div>

### emitAssignment {#a04736ef5753e5ecda3c29ce902094e68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitAssignment (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value)</td>
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

<p>Emit an assignment of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> to <span class="doxyComputerOutput">Symbol</span>.</p>


<p>This corresponds to an assembler statement such as: symbol = value</p>


<p>The assignment generates no code, but has the side effect of binding the value in the current context. For the assembly streamer, this prints the binding into the .s file.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Symbol</td>
<td class="doxyParamItemDescription"><p>- The symbol being assigned to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/value"&gt;Value&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- The value for the symbol.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 509 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1100 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#a87267eadd14492e6af82bdb5b98f4d41">llvm::MCTargetStreamer::emitAssignment</a>, <a href="#a901607e60c20148ae701b6e8f43b4647">getTargetStreamer</a> and <a href="#afb2fc7b7b30a601f94f8f5a6297ec68f">visitUsedExpr</a>.</p>


<p>Referenced by <a href="#a8061d1e593a8f095f0efe3ba0d793531">emitAbsoluteSymbolDiff</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#af1d5c7867737745f90d074f16eb1c485">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitAssignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a2cff84e102389b6f127a6051d9ff062a">llvm::MCObjectStreamer::emitAssignment</a>, <a href="/web-llvm/docs/api/classes/llvm/recordstreamer/#a306a23214c9482f62523348c733c6f1c">llvm::RecordStreamer::emitAssignment</a>, <a href="/web-llvm/docs/api/classes/llvm/recordstreamer/#ae36c2a9293b9a50a2870d02f93d7d202">llvm::RecordStreamer::flushSymverDirectives</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a46eb8d3c0aed8e455691e71a12c142fd">forceExpAbs</a> and <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a21aceafe085b9a14a9864954b9fdb14b">llvm::MCContext::setSymbolValue</a>.</p>

</div>
</div>

### emitBuildVersion {#afcd3ae53e61e2a9304cd12fad993ac6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCStreamer::emitBuildVersion (unsigned Platform, unsigned Major, unsigned Minor, unsigned Update, <a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a> SDKVersion)</td>
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

<p>Emit/Specify Mach-O build version command.</p>


<p><span class="doxyComputerOutput">Platform</span> should be one of <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a3cdacd46a54ada4abe329c88c7a92504">MachO::PlatformType</a>.</p>


<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Referenced by <a href="#aa1789315a3765f97ea5e82e21f4b9e47">emitVersionForTarget</a>.</p>

</div>
</div>

### emitCOFFImgRel32 {#a491fd9123956896fd275562d0393e097}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCOFFImgRel32 (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * Symbol, int64_t Offset)</td>
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

<p>Declaration at line 570 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1024 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### emitCOFFSafeSEH {#aa7ed79f8ff9174fdf148ca9ad7c04266}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCOFFSafeSEH (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * Symbol)</td>
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



<p>Declaration at line 552 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1016 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>

</div>
</div>

### emitCOFFSecNumber {#a5b04c50b8ffcf3457ed3f374fa5675b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCOFFSecNumber (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * Symbol)</td>
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

<p>Declaration at line 574 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1026 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>

</div>
</div>

### emitCOFFSecOffset {#a8f098eb17c10b646a3be4fa3ecab690e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCOFFSecOffset (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * Symbol)</td>
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

<p>Declaration at line 578 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1028 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>

</div>
</div>

### emitCOFFSecRel32 {#a714de05372be0237bac97ad800dd2b52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCOFFSecRel32 (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * Symbol, uint64_t Offset)</td>
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

<p>Declaration at line 565 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1022 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#a3d5b340b9ff61eae3ea229bce6572678">llvm::CodeViewContext::emitLineTableForFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinestr/#ad325ab6e610eb8bd1f59534515561fdc">llvm::MCDwarfLineStr::emitRef</a> and <a href="#a7865bd61cd2c65b2d94c58dd1523bb75">emitSymbolValue</a>.</p>

</div>
</div>

### emitCOFFSectionIndex {#a825998894ce032cf0eb7c76df0c1050b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCOFFSectionIndex (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * Symbol)</td>
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

<p>Declaration at line 560 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1020 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#a3d5b340b9ff61eae3ea229bce6572678">llvm::CodeViewContext::emitLineTableForFunction</a>.</p>

</div>
</div>

### emitCOFFSymbolIndex {#a3e74195180c1fcc6da23dac04b3f733f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCOFFSymbolIndex (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * Symbol)</td>
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

<p>Declaration at line 555 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1018 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>

</div>
</div>

### emitCOFFSymbolStorageClass {#af203d2f0f2a64404b03047029069df5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCOFFSymbolStorageClass (int StorageClass)</td>
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

<p>Declaration at line 542 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1215 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### emitCOFFSymbolType {#a36d6cf82efbf1820a5df485552aa92dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCOFFSymbolType (int Type)</td>
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

<p>Declaration at line 547 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1218 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### emitCommonSymbol {#a4ea7af1a890d88550e6ec96294c19f95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCStreamer::emitCommonSymbol (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, uint64_t Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> ByteAlignment)</td>
</tr>
</table>
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

<p>Definition at line 656 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### emitConditionalAssignment {#af30ac5bb4b7e3d0c5a32aca9e41eac3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitConditionalAssignment (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value)</td>
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

<p>Emit an assignment of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> to <span class="doxyComputerOutput">Symbol</span>, but only if <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> is also emitted.</p>

<p>Declaration at line 513 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 439 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>

</div>
</div>

### emitDarwinTargetVariantBuildVersion {#a93d2f1ced6c7735391e7b442e6fd7713}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCStreamer::emitDarwinTargetVariantBuildVersion (unsigned Platform, unsigned Major, unsigned Minor, unsigned Update, <a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a> SDKVersion)</td>
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



<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Referenced by <a href="#aa1789315a3765f97ea5e82e21f4b9e47">emitVersionForTarget</a>.</p>

</div>
</div>

### emitDataRegion {#ab93cbe98a85c26f4749096e5fecca2f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCStreamer::emitDataRegion (<a href="/web-llvm/docs/api/namespaces/llvm/#a515cb4eba75abc2f0e9dbfffb0137008">MCDataRegionType</a> Kind)</td>
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

<p>Note in the output the specified region <span class="doxyComputerOutput">Kind</span>.</p>

<p>Definition at line 470 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpool/#a504a7be63300c2c61d79be758524a433">llvm::CSKYConstantPool::emitAll</a> and <a href="/web-llvm/docs/api/classes/llvm/constantpool/#ac62d870b374d12290edc181c27cdbdf6">llvm::ConstantPool::emitEntries</a>.</p>

</div>
</div>

### emitEHSymAttributes {#acb990a888b927298c03825efcbfd6e7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitEHSymAttributes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * EHSymbol)</td>
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



<p>Declaration at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 412 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>

</div>
</div>

### emitELFSize {#a680c60c227c19f83cc4e7e363525151b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitELFSize (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value)</td>
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

<p>Emit an <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> .size directive.</p>


<p>This corresponds to an assembler statement such as: .size symbol, expression</p>


<p>Declaration at line 635 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1255 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a6d60dc7f70a5ab7a44c79f6bba354c0f">llvm::TargetLoweringObjectFileELF::emitPersonalityValue</a>.</p>

</div>
</div>

### emitELFSymverDirective {#ae1797d09864b58205f4875b49d2536b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitELFSymverDirective (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * OriginalSym, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool KeepOriginalSym)</td>
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

<p>Emit an <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> .symver directive.</p>


<p>This corresponds to an assembler statement such as: .symver _start, foo@SOME_VERSION</p>


<p>Declaration at line 641 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1256 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>

</div>
</div>

### emitGNUAttribute {#a237e958de04fd14064d0e807a9d6eccc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCStreamer::emitGNUAttribute (unsigned Tag, unsigned Value)</td>
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

<p>Emit a .gnu_attribute directive.</p>

<p>Definition at line 649 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a>.</p>

</div>
</div>

### emitLabel {#a822ae1a4f19b7b00a297a100749f9b8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitLabel (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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

<p>Declaration at line 458 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#aeb7db9ffb91e3b1498231b46e539f33b">llvm::MCTargetStreamer::emitLabel</a>, <a href="#a61c979932b890df773ce75013b76708b">getContext</a>, <a href="#ae1b3cf074436ef5b527071540e13bd58">getCurrentSectionOnly</a>, <a href="#a901607e60c20148ae701b6e8f43b4647">getTargetStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aac3107671801e6bb16ef896f382759cd">llvm::MCContext::reportError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a0bd3fbe76161d42d7470f0dd7dd634de">ARM64EmitUnwindInfoForSegment</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#ab831cd4cdeb2330513a8ca4d3ad3f610">ARMEmitUnwindInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarfdwolinetable/#a82e25540fd1ad0e1e37bb2ff79ab9042">llvm::MCDwarfDwoLineTable::Emit</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableheader/#a1b87cc4b647fd0f14ea7c46227ae2d58">llvm::MCDwarfLineTableHeader::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcgendwarfinfo/#af945d198ed58841b8d57f45a11e2987e">llvm::MCGenDwarfInfo::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpool/#a504a7be63300c2c61d79be758524a433">llvm::CSKYConstantPool::emitAll</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp/#a66c9a59a24a4fdac5b800255b1b3f23d">emitAuthenticatedPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#aee4bdac6b07a31391f6b3a351235b11a">llvm::MCDwarfLineTable::emitCU</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a4d9e8e23e14d63569e6f0121aabd33ce">llvm::MipsTargetELFStreamer::emitDirectiveEnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsasmprinter-cpp/#a487192753b68b0e4380e9d999a5b1549">emitDirectiveRelocJalr</a>, <a href="#a7f1677ad2db297b0202a720530693157">emitDwarfLineStartLabel</a>, <a href="#ad5bed3c2d5a90c1dc5433064c8f25e2d">emitDwarfUnitLength</a>, <a href="/web-llvm/docs/api/classes/llvm/constantpool/#ac62d870b374d12290edc181c27cdbdf6">llvm::ConstantPool::emitEntries</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer/#a00e4f812d3f229d47f31c41cfddadddc">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::emitFPOData</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#acd1c7609888ea3462f400dcfbca2e486">emitGenDwarfRanges</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a99306d453eed689739055115d79beeca">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a9924d739e3dc812b561931a1ad6eb5cf">llvm::MCObjectStreamer::emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/recordstreamer/#aa780f89c07fb6ecf894165fba1eddd5f">llvm::RecordStreamer::emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#afa0924c573f9c03cafa5836672cc58cf">llvm::MCObjectStreamer::emitLabelAtPos</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcdwarf/#ad32db1a85072666827c900bee74761b1">llvm::mcdwarf::emitListsTableHeaderStart</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetelfstreamer/#a6b2f770d3a95aa3a96fdde70ad59fbbd">llvm::XtensaTargetELFStreamer::emitLiteral</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a467c9de76e4b351317463d4c803cebc4">llvm::TargetLoweringObjectFileCOFF::emitModuleMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a3a90d46a868772348b417ed1a94b3a94">llvm::TargetLoweringObjectFileELF::emitModuleMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a7bdbc0657e52a4bffa675c290b32840f">llvm::TargetLoweringObjectFileMachO::emitModuleMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armasmprinter-cpp/#a135ddd8bff5dd7ec257b04d1cdc9af2b">emitNonLazySymbolPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86asmprinter-cpp/#a135ddd8bff5dd7ec257b04d1cdc9af2b">emitNonLazySymbolPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#adf60d16739e1ceabb1cee9e9dede7ba5">llvm::MCDwarfLineTable::emitOne</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a6d60dc7f70a5ab7a44c79f6bba354c0f">llvm::TargetLoweringObjectFileELF::emitPersonalityValue</a>, <a href="#ab314a3ba8aff83e9e0f49248b37993fe">emitPseudoProbe</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a5d75ea3f9831315ebdb816d70c58c30b">EmitUnwindInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#a36948c65344166574c860990801dc0a2">llvm::MCDwarfLineTable::endCurrentSeqAndEmitLineStreamLabel</a>, <a href="#ac4c7cbce4c016b12020711970ace1128">endSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a9e11e3c1ca2c5f957aa7a7a16ff40e24">llvm::MCAsmInfo::getExprForFDESymbol</a>, <a href="/web-llvm/docs/api/structs/llvm/aarch64mcasminfodarwin/#a1a05057cd3005401418d6bb6f4c53659">llvm::AArch64MCAsmInfoDarwin::getExprForPersonalitySymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64-machotargetobjectfile/#aab2cc2813c5a774bb4f83b6f9ae5a98b">llvm::AArch64_MachoTargetObjectFile::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64-machotargetobjectfile/#abda04e72e43a3aaef8a55e4ecf91d127">llvm::AArch64_MachoTargetObjectFile::getTTypeGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#ac1cd29692079a1f57202b9947c5f5521">llvm::TargetLoweringObjectFile::getTTypeReference</a>, <a href="/web-llvm/docs/api/classes/llvm/mcgendwarflabelentry/#a741d0c6e829f284182bd9bbef0362e2d">llvm::MCGenDwarfLabelEntry::Make</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflineentry/#a7e7c37719e68c7bf9e494110a30cad90">llvm::MCDwarfLineEntry::make</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a1f9777a39f525bf9f8a85ce9d52cccd9">anonymous{AsmParser.cpp}::AsmParser::Run</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a46449244c1f2d4e4b2022d1126e7c5ab">anonymous{MasmParser.cpp}::MasmParser::Run</a>, <a href="/web-llvm/docs/api/classes/llvm/faultmaps/#a393b0f5b51aef71d44cc36b4e7b048a7">llvm::FaultMaps::serializeToFaultMapSection</a>, <a href="/web-llvm/docs/api/classes/llvm/stackmaps/#a64f17d34c6ec33d574438b69fa43c2e2">llvm::StackMaps::serializeToStackMapSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonasmprinter-cpp/#a462520f520e196eb7d97d2077f86a8e2">smallData</a>, <a href="#ac4f84451dc4abc997c960d484953b1d2">switchSection</a> and <a href="#a05b1a7fa3b559a330d9830ec956a8383">switchSectionNoPrint</a>.</p>

</div>
</div>

### emitLinkerOptions {#ac27396eeeea0b7f7842ad7015444f5b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCStreamer::emitLinkerOptions (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::string &gt; Kind)</td>
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

<p>Emit the given list <span class="doxyComputerOutput">Options</span> of strings as linker options into the output.</p>

<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a4bf617363cf454c0a6e08bb6e78fe55a">llvm::TargetLoweringObjectFileMachO::emitLinkerDirectives</a>.</p>

</div>
</div>

### emitLocalCommonSymbol {#aa407cf6860a31ef5dc7be9df6d738018}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitLocalCommonSymbol (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, uint64_t Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> ByteAlignment)</td>
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

<p>Declaration at line 664 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1258 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### emitLOHDirective {#ae7db4f7bc015f46c9e027ecdb54411ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCStreamer::emitLOHDirective (<a href="/web-llvm/docs/api/namespaces/llvm/#aadff17100a7bcc6ddd2940e098ddbcf5">MCLOHType</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a62129b64f06d9bc8df1c60845451432b">MCLOHArgs</a> &amp; Args)</td>
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

<p>Emit a <a href="/web-llvm/docs/api/classes/llvm/linker">Linker</a> Optimization Hint (LOH) directive.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Args</td>
<td class="doxyParamItemDescription"><p>- Arguments of the LOH.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 646 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>

</div>
</div>

### emitSymbolAttribute {#a321bb307942921d2e598d92e1830b05d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::MCStreamer::emitSymbolAttribute (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243">MCSymbolAttr</a> Attribute)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the given <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></span> to <span class="doxyComputerOutput">Symbol</span>.</p>

<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilfinalizelinkage-cpp/#ae721973516c2b86042a5127b776e2806">Linkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp/#a434449d5a0f4b334aca9163b13b6286ba178e499decd0c21272bc34e4b3056eab">Trap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armasmprinter-cpp/#a135ddd8bff5dd7ec257b04d1cdc9af2b">emitNonLazySymbolPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86asmprinter-cpp/#a135ddd8bff5dd7ec257b04d1cdc9af2b">emitNonLazySymbolPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a6d60dc7f70a5ab7a44c79f6bba354c0f">llvm::TargetLoweringObjectFileELF::emitPersonalityValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonasmprinter-cpp/#a462520f520e196eb7d97d2077f86a8e2">smallData</a>.</p>

</div>
</div>

### emitSymbolDesc {#aa351ace3a13226477378dd10bd407747}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitSymbolDesc (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, unsigned DescValue)</td>
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

<p>Declaration at line 532 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1203 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>

</div>
</div>

### emitTBSSSymbol {#af577f077023eb897b94f2ed2bad79bbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitTBSSSymbol (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Section, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, uint64_t Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> ByteAlignment=<a href="/web-llvm/docs/api/structs/llvm/align">Align</a>(1))</td>
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

<p>Declaration at line 683 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1260 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### emitThumbFunc {#ac78244fafa28f11ddd2b14133dc2e655}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitThumbFunc (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Func)</td>
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

<p>Declaration at line 496 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1202 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>

</div>
</div>

### emitVersionForTarget {#aa1789315a3765f97ea5e82e21f4b9e47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitVersionForTarget (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; Target, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a> &amp; SDKVersion, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> * DarwinTargetVariantTriple, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a> &amp; DarwinTargetVariantSDKVersion)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 489 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1441 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda0824a8c56de913d60c6f55edc0ac3148">llvm::Triple::Darwin</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda600aa0b72f321a0cdf0e4b3f38b9b6c8">llvm::Triple::DriverKit</a>, <a href="#afcd3ae53e61e2a9304cd12fad993ac6d">emitBuildVersion</a>, <a href="#a93d2f1ced6c7735391e7b442e6fd7713">emitDarwinTargetVariantBuildVersion</a>, <a href="#aa1789315a3765f97ea5e82e21f4b9e47">emitVersionForTarget</a>, <a href="#af1e7d99b242b72e77c6265b64f5a4a30">emitVersionMin</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp/#a9e301ba901f8c3ef4e2f13aad44ee1ad">getMachoBuildVersionPlatformType</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp/#a3979fff418a971520363c40327d25f65">getMachoBuildVersionSupportedOS</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp/#a756e7237c531f502872667409836888a">getMachoVersionMinLoadCommandType</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdafad6e6763679be1478d9283a7344d243">llvm::Triple::IOS</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#aa6a7d5d218ef0d2334fe24eaf997bbb6">llvm::Triple::isMacOSX</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda690ddf3bb28281cc7afa9c7de4ff4075">llvm::Triple::MacOSX</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp/#a8f345912dc87cc1bffdc9ba77c1486c6">targetVersionOrMinimumSupportedOSVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda2838cf6df0f09591c50d752d46c4350d">llvm::Triple::TvOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda87a3c8454473c64f6d605ebd757759ad">llvm::Triple::WatchOS</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdabb5225659a201976ce2594df579e3623">llvm::Triple::XROS</a>.</p>


<p>Referenced by <a href="#aa1789315a3765f97ea5e82e21f4b9e47">emitVersionForTarget</a>.</p>

</div>
</div>

### emitVersionMin {#af1e7d99b242b72e77c6265b64f5a4a30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCStreamer::emitVersionMin (<a href="/web-llvm/docs/api/namespaces/llvm/#a7b22b2a20e7587321d17cb029ea8626e">MCVersionMinType</a> Type, unsigned Major, unsigned Minor, unsigned Update, <a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a> SDKVersion)</td>
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

<p>Specify the Mach-O minimum deployment target version.</p>

<p>Definition at line 473 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Referenced by <a href="#aa1789315a3765f97ea5e82e21f4b9e47">emitVersionForTarget</a>.</p>

</div>
</div>

### emitWeakReference {#afa4e077ea8a8c1f7e7d6321de4c1acd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitWeakReference (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Alias, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol)</td>
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

<p>Declaration at line 522 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1265 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>

</div>
</div>

### emitXCOFFCInfoSym {#ae19d371578fc3d61f9e1655b2f94c32f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitXCOFFCInfoSym (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Metadata)</td>
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

<p>Emit a C_INFO symbol with <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a> embedded metadata to the .info section.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>- The embedded metadata name</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/metadata"&gt;Metadata&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- The embedded metadata</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 629 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1250 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### emitXCOFFExceptDirective {#a810e0bdb5ee0b5c22eda3e47ef26b677}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitXCOFFExceptDirective (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Trap, unsigned Lang, unsigned Reason, unsigned FunctionSize, bool hasDebug)</td>
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

<p>Emit an <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a> .except directive which adds information about a trap instruction to the object file exception section.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Symbol</td>
<td class="doxyParamItemDescription"><p>- The function containing the trap.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Lang</td>
<td class="doxyParamItemDescription"><p>- The language code for the exception entry.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Reason</td>
<td class="doxyParamItemDescription"><p>- The reason code for the exception entry.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 614 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1241 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp/#a434449d5a0f4b334aca9163b13b6286ba178e499decd0c21272bc34e4b3056eab">Trap</a>.</p>

</div>
</div>

### emitXCOFFLocalCommonSymbol {#a6a41af9b3e693ce888f34dc67ecb457e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitXCOFFLocalCommonSymbol (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * LabelSym, uint64_t Size, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * CsectSym, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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

<p>Emits an lcomm directive with <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a> csect information.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">LabelSym</td>
<td class="doxyParamItemDescription"><p>- Label on the block of storage.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>- The size of the block of storage.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CsectSym</td>
<td class="doxyParamItemDescription"><p>- Csect name for the block of storage.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Alignment</td>
<td class="doxyParamItemDescription"><p>- The alignment of the symbol in bytes.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 586 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1221 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### emitXCOFFRefDirective {#aca7f3609c2134cac6f3ebe63f657690e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitXCOFFRefDirective (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol)</td>
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

<p>Emit a <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a> .ref directive which creates R_REF type entry in the relocation table for one or more symbols.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Sym</td>
<td class="doxyParamItemDescription"><p>- The symbol on the .ref directive.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 623 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1237 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### emitXCOFFRenameDirective {#aad30724b89cfe985b9aafd0e26b5fa57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitXCOFFRenameDirective (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Rename)</td>
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

<p>Emit a <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a> .rename directive which creates a synonym for an illegal or undesirable name.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>- The name used internally in the assembly for references to the symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Rename</td>
<td class="doxyParamItemDescription"><p>- The value to which the Name parameter is changed at the end of assembly.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1234 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>

</div>
</div>

### emitXCOFFSymbolLinkageWithVisibility {#a50ff2680cccb848300db07728653a394}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitXCOFFSymbolLinkageWithVisibility (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243">MCSymbolAttr</a> Linkage, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243">MCSymbolAttr</a> Visibility)</td>
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

<p>Emit a symbol's linkage and visibility with a linkage directive for <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Symbol</td>
<td class="doxyParamItemDescription"><p>- The symbol to emit.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Linkage</td>
<td class="doxyParamItemDescription"><p>- The linkage of the symbol to emit.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Visibility</td>
<td class="doxyParamItemDescription"><p>- The visibility of the symbol to emit or MCSA_Invalid if the symbol does not have an explicit visibility.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 595 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1227 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### emitZerofill {#ad490db637a9818eafdae19bdb0ec1334}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCStreamer::emitZerofill (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Section, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol=nullptr, uint64_t Size=0, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> ByteAlignment=<a href="/web-llvm/docs/api/structs/llvm/align">Align</a>(1), <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
</tr>
</table>
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

<p>Definition at line 673 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### endCOFFSymbolDef {#a49798cb55fb8e3a280ca3249704e7dec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::endCOFFSymbolDef ()</td>
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

<p>Declaration at line 550 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1207 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### endSection {#ac4c7cbce4c016b12020711970ace1128}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MCStreamer::endSection (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Section)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1345 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="#a822ae1a4f19b7b00a297a100749f9b8a">emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a3214f95c05e3d2af5e3e56667dc54239">llvm::MCSymbol::isInSection</a> and <a href="#ac4f84451dc4abc997c960d484953b1d2">switchSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a916d35fa28fa01868c717ca125a037af">llvm::MCObjectStreamer::emitDwarfLineEndEntry</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#ad8a1ae695b98f49601a5986f612da526">llvm::AArch64TargetStreamer::emitNoteSection</a>.</p>

</div>
</div>

### getCurrentFragment {#a2f9393965bc0de69da6236c623f79579}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCFragment * llvm::MCStreamer::getCurrentFragment ()</td>
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



<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9299fd6e2b7f540daa945aae967ffe47">CurFrag</a> and <a href="#ad946e0775ff08232ff6dc1bd9a8ed9bb">getCurrentSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a1f4f0489eaa2133da3944177f6646130">llvm::MCELFStreamer::changeSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#ad6394338481d436a665bb4572e9e1ffc">llvm::MCObjectStreamer::emitCodeAlignment</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#a38dcf42330d1efcd03d0686ba7bbaf1d">anonymous{X86AsmBackend.cpp}::X86AsmBackend::emitInstructionBegin</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#a8c9b4bc17f742123fb67a743e46e11bc">anonymous{X86AsmBackend.cpp}::X86AsmBackend::emitInstructionEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#ab3fe33399c0b0827431d423b0e4446a7">llvm::MCELFStreamer::finishImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3558114ca72d34962abb28004d864b19">llvm::MCObjectStreamer::getOrCreateDataFragment</a>.</p>

</div>
</div>

### getCurrentSection {#ad946e0775ff08232ff6dc1bd9a8ed9bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSectionSubPair llvm::MCStreamer::getCurrentSection ()</td>
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

<p>Return the current section that the streamer is emitting code to.</p>

<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64elfstreamer-cpp-/aarch64elfstreamer/#ac9a2a9dc08d70f6677c97d0738a021e2">anonymous{AArch64ELFStreamer.cpp}::AArch64ELFStreamer::changeSection</a>, <a href="/web-llvm/docs/api/classes/anonymous-armelfstreamer-cpp-/armelfstreamer/#a09c84cdd5b0e4500ea97797d95dce446">anonymous{ARMELFStreamer.cpp}::ARMELFStreamer::changeSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a29a3c5dc6082aabd411724f33011f795">llvm::MCELFStreamer::emitCommonSymbol</a>, <a href="#a2f9393965bc0de69da6236c623f79579">getCurrentFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmcelfstreamer/#a64f1accd42a5eb6c0d80c800e63123b9">llvm::HexagonMCELFStreamer::HexagonMCEmitCommonSymbol</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a34cd5a64eb935155249865a6f30bdc5d">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::popSection</a>, <a href="#ab095568f88bb32f8a744aaeab0d2c4d0">pushSection</a> and <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a4712c0b6d11e44d06eea24bc7b786ca9">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::switchSection</a>.</p>

</div>
</div>

### getCurrentSectionOnly {#ae1b3cf074436ef5b527071540e13bd58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCStreamer::getCurrentSectionOnly ()</td>
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



<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Reference <a href="#a9299fd6e2b7f540daa945aae967ffe47">CurFrag</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/assemblerconstantpools/#acbc7759a8d05ed32ae7d656282f33545">llvm::AssemblerConstantPools::addEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpool/#a91eb97e39eb4e9b4befd1914be362617">llvm::CSKYConstantPool::addEntry</a>, <a href="#a79e4fddfcfc0d5ed30a1b811fcd17a6e">checkCVLocSection</a>, <a href="/web-llvm/docs/api/classes/llvm/assemblerconstantpools/#a74ada55ccb1288908e7ea2c6ab52bc4f">llvm::AssemblerConstantPools::clearCacheForCurrentSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a03d5b66fb043f263c71b72ed453af330">llvm::MCELFStreamer::emitBundleLock</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a283e6f0c37b443b2002881149730a709">llvm::MCELFStreamer::emitBundleUnlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a807369cf0e8ddbe75c8c4a671bfc4258">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a66d51c3585e4733b99bb8d3e3eb2bb81">llvm::MCObjectStreamer::emitBytes</a>, <a href="#a11eed8ef0a19a4cd80fc06a8488061fd">emitCFIStartProc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#ac26c6bea8d31cc52a500469bc470d0b6">llvm::MCWinCOFFStreamer::emitCOFFSymbolIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#afbf8b87c2743700b4bc2f187d06c9a28">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitDwarfLocDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#ac90a78b45f28148cbab53747e0eba695">llvm::MCObjectStreamer::emitDwarfLocDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a0fe2220852635deb479d9b7274750f5f">llvm::MCObjectStreamer::emitFill</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#aa660e7b419602632507f83ec8a1520aa">llvm::MCObjectStreamer::emitFill</a>, <a href="/web-llvm/docs/api/classes/llvm/assemblerconstantpools/#ab384d9d85bfa8aad47ac23f346b08a87">llvm::AssemblerConstantPools::emitForCurrentSection</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a161ac460fefc16f98a8dd1a9f019af9a">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a92d2d1c2ac97f1151ed8f38d854e8b34">llvm::MCObjectStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#a8c9b4bc17f742123fb67a743e46e11bc">anonymous{X86AsmBackend.cpp}::X86AsmBackend::emitInstructionEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#ac725449b95138e5297b8af02df828882">llvm::MCELFStreamer::emitLabel</a>, <a href="#a822ae1a4f19b7b00a297a100749f9b8a">emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwasmstreamer/#a725829258ed44c50d122fbbadb1ef9b4">llvm::MCWasmStreamer::emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#ae5f734996b90b33b24ba29c814293727">llvm::MCELFStreamer::emitLabelAtPos</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#afa0924c573f9c03cafa5836672cc58cf">llvm::MCObjectStreamer::emitLabelAtPos</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwasmstreamer/#a005d6fde2a7f1c0e542fdce16669d76b">llvm::MCWasmStreamer::emitLabelAtPos</a>, <a href="#a03e59500b09326087aab0f3aa60a1491">emitLineTableLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetelfstreamer/#a6b2f770d3a95aa3a96fdde70ad59fbbd">llvm::XtensaTargetELFStreamer::emitLiteral</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3454c2fd75e206584250b36f28cf16e6">llvm::MCObjectStreamer::emitNops</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#ad8a1ae695b98f49601a5986f612da526">llvm::AArch64TargetStreamer::emitNoteSection</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcmachostreamer-cpp-/mcmachostreamer/#a798fb78a6525095a294fda8d027edeb6">anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::emitSymbolAttribute</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#ae37bcdd18e5b8eb58b8d88effad3fed8">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitValueImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a9ef24f653b777a160537ee3e1d824663">llvm::MCObjectStreamer::emitValueImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a21d70037ecf679b5f8d13af07f8f136a">llvm::MCObjectStreamer::emitValueToAlignment</a>, <a href="#af4abf3b216995cecfbe8fcbc05d5b128">emitWinCFIStartChained</a>, <a href="#a7787897c604e14c9e152c890e019e3bf">emitWinCFIStartProc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#a36948c65344166574c860990801dc0a2">llvm::MCDwarfLineTable::endCurrentSeqAndEmitLineStreamLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcgendwarflabelentry/#a741d0c6e829f284182bd9bbef0362e2d">llvm::MCGenDwarfLabelEntry::Make</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a1f9777a39f525bf9f8a85ce9d52cccd9">anonymous{AsmParser.cpp}::AsmParser::Run</a> and <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a46449244c1f2d4e4b2022d1126e7c5ab">anonymous{MasmParser.cpp}::MasmParser::Run</a>.</p>

</div>
</div>

### getMnemonic {#a7e2414963f9f6105e4f447d751098763}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual StringRef llvm::MCStreamer::getMnemonic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI)</td>
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

<p>Returns the mnemonic for <span class="doxyComputerOutput">MI</span>, if the streamer has access to a instruction printer and returns an empty string otherwise.</p>

<p>Definition at line 446 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a908e716e36451058cc4d148b090565d5">getMIMnemonic</a>.</p>

</div>
</div>

### getPreviousSection {#a1b9a264ab7d0fb2c305ab3d0beb4b74c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSectionSubPair llvm::MCStreamer::getPreviousSection ()</td>
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

<p>Return the previous section that the streamer is emitting code to.</p>

<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvelfstreamer/#a4f98abfe4c9b19f2cfed56234b6257b9">llvm::RISCVELFStreamer::changeSection</a> and <a href="#ab095568f88bb32f8a744aaeab0d2c4d0">pushSection</a>.</p>

</div>
</div>

### initSections {#a203640eb7873f4e1da4c6acd32c6651c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::initSections (bool NoExecStack, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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

<p>Declaration at line 440 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 416 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="#a61c979932b890df773ce75013b76708b">getContext</a> and <a href="#a05b1a7fa3b559a330d9830ec956a8383">switchSectionNoPrint</a>.</p>

</div>
</div>

### popSection {#a216005880453270b48e5d5d7daeec6d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCStreamer::popSection ()</td>
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

<p>Restore the current and previous section from the section stack.</p>


<p>Calls changeSection as needed.</p>


<p>Returns false if the stack was empty.</p>


<p>Declaration at line 427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1288 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="#afd46c84fb0f1eef50c7c7d3b1bc23c87">changeSection</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#a52a02f271d804bdc34f866c95a09e252">llvm::AMDGPUTargetELFStreamer::EmitAMDKernelCodeT</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#a3d5bfc5811bed855825f405f757caf44">llvm::AMDGPUTargetELFStreamer::EmitCodeEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a296ba2dbfb0e9605f94744804b1612b9">llvm::MCWinCOFFStreamer::emitCOFFSafeSEH</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a46ca451d0ba24a1a138f28bd71a72271">llvm::MCWinCOFFStreamer::emitCommonSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a4d9e8e23e14d63569e6f0121aabd33ce">llvm::MipsTargetELFStreamer::emitDirectiveEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a21d50101946fb3648d4d662a0e1d0406">llvm::MCELFStreamer::emitIdent</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetelfstreamer/#a6b2f770d3a95aa3a96fdde70ad59fbbd">llvm::XtensaTargetELFStreamer::emitLiteral</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a98ffe083ab6ade934683a26a65204179">llvm::MCWinCOFFStreamer::emitLocalCommonSymbol</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcmachostreamer-cpp-/mcmachostreamer/#af20b6581bfb880b0df6d552b229739f9">anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::emitZerofill</a> and <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a34cd5a64eb935155249865a6f30bdc5d">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::popSection</a>.</p>

</div>
</div>

### pushSection {#ab095568f88bb32f8a744aaeab0d2c4d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCStreamer::pushSection ()</td>
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

<p>Save the current and previous section on the section stack.</p>

<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>References <a href="#ad946e0775ff08232ff6dc1bd9a8ed9bb">getCurrentSection</a> and <a href="#a1b9a264ab7d0fb2c305ab3d0beb4b74c">getPreviousSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#a52a02f271d804bdc34f866c95a09e252">llvm::AMDGPUTargetELFStreamer::EmitAMDKernelCodeT</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#a3d5bfc5811bed855825f405f757caf44">llvm::AMDGPUTargetELFStreamer::EmitCodeEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a296ba2dbfb0e9605f94744804b1612b9">llvm::MCWinCOFFStreamer::emitCOFFSafeSEH</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a46ca451d0ba24a1a138f28bd71a72271">llvm::MCWinCOFFStreamer::emitCommonSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a4d9e8e23e14d63569e6f0121aabd33ce">llvm::MipsTargetELFStreamer::emitDirectiveEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a21d50101946fb3648d4d662a0e1d0406">llvm::MCELFStreamer::emitIdent</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetelfstreamer/#a6b2f770d3a95aa3a96fdde70ad59fbbd">llvm::XtensaTargetELFStreamer::emitLiteral</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a98ffe083ab6ade934683a26a65204179">llvm::MCWinCOFFStreamer::emitLocalCommonSymbol</a> and <a href="/web-llvm/docs/api/classes/anonymous-mcmachostreamer-cpp-/mcmachostreamer/#af20b6581bfb880b0df6d552b229739f9">anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::emitZerofill</a>.</p>

</div>
</div>

### switchSection {#ac4f84451dc4abc997c960d484953b1d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::switchSection (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Section, uint32_t Subsec=0)</td>
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

<p>Set the current section where code is being emitted to <span class="doxyComputerOutput">Section</span>.</p>


<p>This is required to update CurSection.</p>


<p>This corresponds to assembler directives like .section, .text, etc.</p>


<p>Declaration at line 433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1303 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afd46c84fb0f1eef50c7c7d3b1bc23c87">changeSection</a>, <a href="#a822ae1a4f19b7b00a297a100749f9b8a">emitLabel</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a3214f95c05e3d2af5e3e56667dc54239">llvm::MCSymbol::isInSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/dwp/dwp-cpp/#af2db0d7fc3c09fcac8bfcc6bc3cdbd6c">addAllTypesFromDWP</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwp/dwp-cpp/#a82237aa799c6a24c6bc9f95c01b137d4">addAllTypesFromTypesSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarfdwolinetable/#a82e25540fd1ad0e1e37bb2ff79ab9042">llvm::MCDwarfDwoLineTable::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarfframeemitter/#a6db5460aea8388ba1f9bec6c47f6c741">llvm::MCDwarfFrameEmitter::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcgendwarfinfo/#af945d198ed58841b8d57f45a11e2987e">llvm::MCGenDwarfInfo::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/win64eh/arm64unwindemitter/#af344ffc71b7b9b6972bda73c603051a8">llvm::Win64EH::ARM64UnwindEmitter::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/win64eh/armunwindemitter/#ab428fc29f43b7cfc8e9059f4f3fc09fd">llvm::Win64EH::ARMUnwindEmitter::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/win64eh/unwindemitter/#a2325284fc9cfe14f9764717f5f0e4fb7">llvm::Win64EH::UnwindEmitter::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#a89cdc6ed6476f39c32e5a49327bb692e">llvm::MCDwarfLineTable::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobesections/#a42ea134aa4f428e1a5be9ba304e84f4c">llvm::MCPseudoProbeSections::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpool/#a504a7be63300c2c61d79be758524a433">llvm::CSKYConstantPool::emitAll</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a296ba2dbfb0e9605f94744804b1612b9">llvm::MCWinCOFFStreamer::emitCOFFSafeSEH</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a29a3c5dc6082aabd411724f33011f795">llvm::MCELFStreamer::emitCommonSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a46ca451d0ba24a1a138f28bd71a72271">llvm::MCWinCOFFStreamer::emitCommonSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/constantpools-cpp/#ae61095f365a3433f947863298a0ecbbd">emitConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a4d9e8e23e14d63569e6f0121aabd33ce">llvm::MipsTargetELFStreamer::emitDirectiveEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a916d35fa28fa01868c717ca125a037af">llvm::MCObjectStreamer::emitDwarfLineEndEntry</a>, <a href="/web-llvm/docs/api/classes/anonymous-armelfstreamer-cpp-/armelfstreamer/#a64c883532dcb4cc6bb2ef3b3f0ae0cad">anonymous{ARMELFStreamer.cpp}::ARMELFStreamer::emitFnEnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#ae3810dff97d2b1f712f053e18a98f383">EmitGenDwarfAbbrev</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a1b98f9e375747640ed4f1f019b0558aa">EmitGenDwarfAranges</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#acd1c7609888ea3462f400dcfbca2e486">emitGenDwarfRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a21d50101946fb3648d4d662a0e1d0406">llvm::MCELFStreamer::emitIdent</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a88c088e4fb14a140785c69f3af654b55">llvm::TargetLoweringObjectFileCOFF::emitLinkerDirectives</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a3cd35b2eb52932034ebff3b18e0dcf0a">llvm::TargetLoweringObjectFileELF::emitLinkerDirectives</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetelfstreamer/#a6b2f770d3a95aa3a96fdde70ad59fbbd">llvm::XtensaTargetELFStreamer::emitLiteral</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a98ffe083ab6ade934683a26a65204179">llvm::MCWinCOFFStreamer::emitLocalCommonSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#afeed6d8af2306405a117845c04177102">llvm::MipsTargetELFStreamer::emitMipsAbiFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a467c9de76e4b351317463d4c803cebc4">llvm::TargetLoweringObjectFileCOFF::emitModuleMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a3a90d46a868772348b417ed1a94b3a94">llvm::TargetLoweringObjectFileELF::emitModuleMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a7bdbc0657e52a4bffa675c290b32840f">llvm::TargetLoweringObjectFileMachO::emitModuleMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86asmprinter-cpp/#acda48e0ba94e27f00cbe44c1585fcfe7">emitNonLazyStubs</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#ad8a1ae695b98f49601a5986f612da526">llvm::AArch64TargetStreamer::emitNoteSection</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a6d60dc7f70a5ab7a44c79f6bba354c0f">llvm::TargetLoweringObjectFileELF::emitPersonalityValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinestr/#a1578026c1ceb637e4b37023412f971ac">llvm::MCDwarfLineStr::emitSection</a>, <a href="/web-llvm/docs/api/classes/llvm/win64eh/arm64unwindemitter/#a23e988e2f737319fba0ad0f50b4791c3">llvm::Win64EH::ARM64UnwindEmitter::EmitUnwindInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/win64eh/armunwindemitter/#ae3581e58aa167be222e1d2b9c164b10a">llvm::Win64EH::ARMUnwindEmitter::EmitUnwindInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/win64eh/unwindemitter/#aaad7a7f0ae118b34d41f8ceed7136672">llvm::Win64EH::UnwindEmitter::EmitUnwindInfo</a>, <a href="#a9d158c6b4a4302d51fd73aac4075086d">emitWinCFIEndProc</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcmachostreamer-cpp-/mcmachostreamer/#af20b6581bfb880b0df6d552b229739f9">anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::emitZerofill</a>, <a href="#ac4c7cbce4c016b12020711970ace1128">endSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a94031e736c9e04044ac7181147a54bf6">llvm::MipsTargetELFStreamer::finish</a>, <a href="/web-llvm/docs/api/classes/anonymous-erlanggcprinter-cpp-/erlanggcprinter/#a574679a34186d5db3a7b14b0ce5c5078">anonymous{ErlangGCPrinter.cpp}::ErlangGCPrinter::finishAssembly</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a7f964c60245b61612ddd6509cba7eb74">llvm::MCWinCOFFStreamer::finishImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9918786a0f26fa3b2f43f2a0fe626f7a">llvm::handleSection</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmcelfstreamer/#a64f1accd42a5eb6c0d80c800e63123b9">llvm::HexagonMCELFStreamer::HexagonMCEmitCommonSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#add62de97c76582fbd18c47c44677ca12">llvm::MCELFStreamer::initSections</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a28e4c026855f296e926e3feb231b5811">llvm::MCWinCOFFStreamer::initSections</a>, <a href="/web-llvm/docs/api/classes/llvm/faultmaps/#a393b0f5b51aef71d44cc36b4e7b048a7">llvm::FaultMaps::serializeToFaultMapSection</a>, <a href="/web-llvm/docs/api/classes/llvm/stackmaps/#a64f17d34c6ec33d574438b69fa43c2e2">llvm::StackMaps::serializeToStackMapSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonasmprinter-cpp/#a462520f520e196eb7d97d2077f86a8e2">smallData</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a4712c0b6d11e44d06eea24bc7b786ca9">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::switchSection</a>, <a href="#a179d49e133edc4f825fe798450d24458">switchSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mipselfstreamer/#ac1e42b60da035bc571092183c8954a5c">llvm::MipsELFStreamer::switchSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7363e46d4dd6c78affffabaea0de482b">llvm::write</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2f8e7754bbc7c049946acba12e02f815">llvm::writeIndex</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4f7d4f36e40ebd1e64d3c802976e7225">llvm::writeStringsAndOffsets</a>.</p>

</div>
</div>

### switchSection {#a179d49e133edc4f825fe798450d24458}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCStreamer::switchSection (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Section, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * SubsecExpr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1317 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="#a4ef5ffac1974b503c8ec1b3172d37335">getAssemblerPtr</a>, <a href="#a61c979932b890df773ce75013b76708b">getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#afc4237f50d652cdefff412b2c780c369">llvm::MCExpr::getLoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aac3107671801e6bb16ef896f382759cd">llvm::MCContext::reportError</a> and <a href="#ac4f84451dc4abc997c960d484953b1d2">switchSection</a>.</p>

</div>
</div>

### switchSectionNoPrint {#a05b1a7fa3b559a330d9830ec956a8383}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::switchSectionNoPrint (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Section)</td>
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

<p>Similar to switchSection, but does not print the section directive.</p>

<p>Declaration at line 437 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1336 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="#afd46c84fb0f1eef50c7c7d3b1bc23c87">changeSection</a>, <a href="#a822ae1a4f19b7b00a297a100749f9b8a">emitLabel</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a3214f95c05e3d2af5e3e56667dc54239">llvm::MCSymbol::isInSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a27ab1f18a7bff8a82c03e03302227f0d">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitWinEHHandlerData</a>, <a href="#a203640eb7873f4e1da4c6acd32c6651c">initSections</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#abdcaa3fc744093c3a7104daa885f7d88">llvm::MCObjectStreamer::switchSectionNoPrint</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Generating Data

### emitBinaryData {#a1d73c2da2d5410a07113b9f24c640c12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitBinaryData (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Data)</td>
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

<p>Functionally identical to EmitBytes.</p>


<p>When emitting textual assembly, this method uses .byte directives instead of .ascii or .asciz for readability.</p>


<p>Declaration at line 698 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1267 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="#af94e84eca402017c9ce57b7b4c4104e3">emitBytes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/asmprinter/xrayfunctionentry/#aaf3c3728de7d947c5dda5dc44a67378b">llvm::AsmPrinter::XRayFunctionEntry::emit</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a7f51a5e71249c406f3e5f1dd24201546">emitOneV5FileEntry</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinestr/#a1578026c1ceb637e4b37023412f971ac">llvm::MCDwarfLineStr::emitSection</a>.</p>

</div>
</div>

### emitBytes {#af94e84eca402017c9ce57b7b4c4104e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitBytes (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Data)</td>
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

<p>Emit the bytes in <span class="doxyComputerOutput">Data</span> into the output.</p>


<p>This is used to implement assembler directives such as .byte, .ascii, etc.</p>


<p>Declaration at line 694 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1266 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/dwp/dwp-cpp/#af2db0d7fc3c09fcac8bfcc6bc3cdbd6c">addAllTypesFromDWP</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwp/dwp-cpp/#a82237aa799c6a24c6bc9f95c01b137d4">addAllTypesFromTypesSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflineaddr/#a002e20f504cfcef55b84c4c7e5b2be68">llvm::MCDwarfLineAddr::Emit</a>, <a href="#a1d73c2da2d5410a07113b9f24c640c12">emitBinaryData</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#afa871ee1214ea70bc23abaca212b3ab7">llvm::AArch64TargetStreamer::emitInst</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetstreamer/#a35fb67d88bdb317b8d0ed132e9403414">llvm::ARMTargetStreamer::emitInst</a>, <a href="#a7d36cf8691cdd5195631e8bbd8d38fc2">emitIntValue</a>, <a href="#a971830cc1546210be8cc86fa568be8d0">emitIntValue</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/amdgpumckernelcodet/#a766a8f22f00b2895f373b0328840e760">llvm::AMDGPU::AMDGPUMCKernelCodeT::EmitKernelCodeT</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a88c088e4fb14a140785c69f3af654b55">llvm::TargetLoweringObjectFileCOFF::emitLinkerDirectives</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a3cd35b2eb52932034ebff3b18e0dcf0a">llvm::TargetLoweringObjectFileELF::emitLinkerDirectives</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a3a90d46a868772348b417ed1a94b3a94">llvm::TargetLoweringObjectFileELF::emitModuleMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#ab371721ad31c3a0d4e5eb8fce0e8a13a">emitNop</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#ad8a1ae695b98f49601a5986f612da526">llvm::AArch64TargetStreamer::emitNoteSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp/#a3b4618fc48c7d5c6c6e7df30e56f7ed6">emitNullTerminatedSymbolName</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a7f51a5e71249c406f3e5f1dd24201546">emitOneV5FileEntry</a>, <a href="#ae9c7bfbd6f1a6b08ebabb1ca16be3d7e">emitSLEB128IntValue</a>, <a href="#abc5f738b9471c3ed31b8f1fc7dc8e914">emitULEB128IntValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9918786a0f26fa3b2f43f2a0fe626f7a">llvm::handleSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7363e46d4dd6c78affffabaea0de482b">llvm::write</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4f7d4f36e40ebd1e64d3c802976e7225">llvm::writeStringsAndOffsets</a>.</p>

</div>
</div>

### emitCodeAlignment {#aa1dcf543ae68792dfaabeaa31f4ddef2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitCodeAlignment (<a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI, unsigned MaxBytesToEmit=0)</td>
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

<p>Emit nops until the byte alignment <span class="doxyComputerOutput">ByteAlignment</span> is reached.</p>


<p>This used to align code where the alignment bytes may be executed. This can emit different bytes for different sizes to optimize execution.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Alignment</td>
<td class="doxyParamItemDescription"><p>- The alignment to reach.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">STI</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> in operation when padding is emitted.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MaxBytesToEmit</td>
<td class="doxyParamItemDescription"><p>- The maximum numbers of bytes to emit, or 0. If the alignment cannot be reached in this many bytes, no bytes are emitted.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 860 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1279 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpool/#a504a7be63300c2c61d79be758524a433">llvm::CSKYConstantPool::emitAll</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonasmprinter-cpp/#a462520f520e196eb7d97d2077f86a8e2">smallData</a>.</p>

</div>
</div>

### emitDTPRel32Value {#acf0a3067291b11ed02cf9658cc100ff1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitDTPRel32Value (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value)</td>
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

<p>Emit the expression <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> into the output as a dtprel (32-bit DTP relative) value.</p>


<p>This is used to implement assembler directives such as .dtprelword on targets that support them.</p>


<p>Declaration at line 768 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### emitDTPRel64Value {#a16c215be8d978c78bd4915e8c7b5be44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitDTPRel64Value (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value)</td>
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

<p>Emit the expression <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> into the output as a dtprel (64-bit DTP relative) value.</p>


<p>This is used to implement assembler directives such as .dtpreldword on targets that support them.</p>


<p>Declaration at line 761 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### emitFill {#af6a6f6142b6fd138cdc9e08217577c4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitFill (uint64_t NumBytes, uint8_t FillValue)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit NumBytes bytes worth of the value specified by FillValue.</p>


<p>This implements directives such as '.space'.</p>


<p>Declaration at line 800 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="#af6a6f6142b6fd138cdc9e08217577c4d">emitFill</a> and <a href="#a61c979932b890df773ce75013b76708b">getContext</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#aae6d9fb29c7a596c66c84d2ccb0457dd">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitFill</a>, <a href="#af6a6f6142b6fd138cdc9e08217577c4d">emitFill</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#acd1c7609888ea3462f400dcfbca2e486">emitGenDwarfRanges</a> and <a href="#ae77a5b8d3af591a461aeac723de33240">emitZeros</a>.</p>

</div>
</div>

### emitFill {#a83eaa7813db4a518c595cd260451035a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitFill (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> &amp; NumBytes, uint64_t FillValue, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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

<p>Emit <span class="doxyComputerOutput">Size</span> bytes worth of the value specified by <span class="doxyComputerOutput">FillValue</span>.</p>


<p>This is used to implement assembler directives such as .space or .skip.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumBytes</td>
<td class="doxyParamItemDescription"><p>- The number of bytes to emit.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FillValue</td>
<td class="doxyParamItemDescription"><p>- The value to use when filling bytes.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- The location of the expression for error reporting.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 809 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1273 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>

</div>
</div>

### emitFill {#a3853464dd3b9c6d976ae24e63eaf2e01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitFill (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> &amp; NumValues, int64_t Size, int64_t Expr, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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

<p>Emit <span class="doxyComputerOutput">NumValues</span> copies of <span class="doxyComputerOutput">Size</span> bytes.</p>


<p>Each <span class="doxyComputerOutput">Size</span> bytes is taken from the lowest order 4 bytes of <span class="doxyComputerOutput">Expr</span> expression.</p>


<p>This is used to implement assembler directives such as .fill.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumValues</td>
<td class="doxyParamItemDescription"><p>- The number of copies of <span class="doxyComputerOutput">Size</span> bytes to emit.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>- The size (in bytes) of each repeated value.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Expr</td>
<td class="doxyParamItemDescription"><p>- The expression from which <span class="doxyComputerOutput">Size</span> bytes are used.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 820 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1274 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### emitGPRel32Value {#a5f3171a957932bcebeee529fd209eb29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitGPRel32Value (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value)</td>
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

<p>Emit the expression <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> into the output as a gprel32 (32-bit GP relative) value.</p>


<p>This is used to implement assembler directives such as .gprel32 on targets that support them.</p>


<p>Declaration at line 796 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### emitGPRel64Value {#a2fc23f2bb6f6eac3e533bba27f1b48c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitGPRel64Value (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value)</td>
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

<p>Emit the expression <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> into the output as a gprel64 (64-bit GP relative) value.</p>


<p>This is used to implement assembler directives such as .gpdword on targets that support them.</p>


<p>Declaration at line 789 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### emitInt16 {#a9d412a2cef594fc0f45de176d51fee3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCStreamer::emitInt16 (uint64_t Value)</td>
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



<p>Definition at line 728 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Reference <a href="#a971830cc1546210be8cc86fa568be8d0">emitIntValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableheader/#a1b87cc4b647fd0f14ea7c46227ae2d58">llvm::MCDwarfLineTableHeader::Emit</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpostatemachine/#ac60cbf99d76cbbbbc3c094a7d78fb834">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOStateMachine::emitFrameDataRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a1b98f9e375747640ed4f1f019b0558aa">EmitGenDwarfAranges</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#a3d5b340b9ff61eae3ea229bce6572678">llvm::CodeViewContext::emitLineTableForFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcdwarf/#ad32db1a85072666827c900bee74761b1">llvm::mcdwarf::emitListsTableHeaderStart</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a6144ace1bbb2a8b3fe310225914ee101">EmitUnwindCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a5d75ea3f9831315ebdb816d70c58c30b">EmitUnwindInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/faultmaps/#a393b0f5b51aef71d44cc36b4e7b048a7">llvm::FaultMaps::serializeToFaultMapSection</a>.</p>

</div>
</div>

### emitInt32 {#acc3817979bc871dba942b87773da1cc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCStreamer::emitInt32 (uint64_t Value)</td>
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



<p>Definition at line 729 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Reference <a href="#a971830cc1546210be8cc86fa568be8d0">emitIntValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a66a4df49046ec16dd9c64d36ba3cb62c">ARM64EmitRuntimeFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a0bd3fbe76161d42d7470f0dd7dd634de">ARM64EmitUnwindInfoForSegment</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a48d2597504af337577491cde138a142b">ARMEmitRuntimeFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#ab831cd4cdeb2330513a8ca4d3ad3f610">ARMEmitUnwindInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#a3d5bfc5811bed855825f405f757caf44">llvm::AMDGPUTargetELFStreamer::EmitCodeEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#a43decaae146363e80c3ba5b685016bb5">llvm::CodeViewContext::emitFileChecksums</a>, <a href="/web-llvm/docs/api/classes/anonymous-armelfstreamer-cpp-/armelfstreamer/#a64c883532dcb4cc6bb2ef3b3f0ae0cad">anonymous{ARMELFStreamer.cpp}::ARMELFStreamer::emitFnEnd</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer/#a00e4f812d3f229d47f31c41cfddadddc">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::emitFPOData</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpostatemachine/#ac60cbf99d76cbbbbc3c094a7d78fb834">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOStateMachine::emitFrameDataRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a1b98f9e375747640ed4f1f019b0558aa">EmitGenDwarfAranges</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#acd1c7609888ea3462f400dcfbca2e486">emitGenDwarfRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#a3d5b340b9ff61eae3ea229bce6572678">llvm::CodeViewContext::emitLineTableForFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcdwarf/#ad32db1a85072666827c900bee74761b1">llvm::mcdwarf::emitListsTableHeaderStart</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a467c9de76e4b351317463d4c803cebc4">llvm::TargetLoweringObjectFileCOFF::emitModuleMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a3a90d46a868772348b417ed1a94b3a94">llvm::TargetLoweringObjectFileELF::emitModuleMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a7bdbc0657e52a4bffa675c290b32840f">llvm::TargetLoweringObjectFileMachO::emitModuleMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#ad43adc5b7e0fcb43103dfe2e1acac4f2">llvm::CodeViewContext::emitStringTable</a>, <a href="/web-llvm/docs/api/classes/llvm/btfkinddatasec/#a41b5cfee68732eaed66ef41d9d1a7884">llvm::BTFKindDataSec::emitType</a>, <a href="/web-llvm/docs/api/classes/llvm/btfkindvar/#a6063d7dad9aab202661760a53b2e3ae4">llvm::BTFKindVar::emitType</a>, <a href="/web-llvm/docs/api/classes/llvm/btftypearray/#aa83d212d48328a550dbfc849cba1f2f9">llvm::BTFTypeArray::emitType</a>, <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#af00b13d92054d7b6f7c8b4561f46685b">llvm::BTFTypeBase::emitType</a>, <a href="/web-llvm/docs/api/classes/llvm/btftypedecltag/#adaccf5482045e7dc54c8aa47e00de12b">llvm::BTFTypeDeclTag::emitType</a>, <a href="/web-llvm/docs/api/classes/llvm/btftypeenum64/#aeeff33f4503f3e3724197047123252d1">llvm::BTFTypeEnum64::emitType</a>, <a href="/web-llvm/docs/api/classes/llvm/btftypeenum/#aa0eb99296f676295e86aee38e48b1bed">llvm::BTFTypeEnum::emitType</a>, <a href="/web-llvm/docs/api/classes/llvm/btftypefuncproto/#af65612a676eede846be993d5a1289e4f">llvm::BTFTypeFuncProto::emitType</a>, <a href="/web-llvm/docs/api/classes/llvm/btftypeint/#a223d1876a944b2ee9c675f502651a8a1">llvm::BTFTypeInt::emitType</a>, <a href="/web-llvm/docs/api/classes/llvm/btftypestruct/#a261288152d81e6ee565d7c68d175624e">llvm::BTFTypeStruct::emitType</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a5d75ea3f9831315ebdb816d70c58c30b">EmitUnwindInfo</a>, <a href="#acde9e2a59908e8d8a4082d1869f6c08e">maybeEmitDwarf64Mark</a> and <a href="/web-llvm/docs/api/classes/llvm/faultmaps/#a393b0f5b51aef71d44cc36b4e7b048a7">llvm::FaultMaps::serializeToFaultMapSection</a>.</p>

</div>
</div>

### emitInt64 {#ac46413fa6b39176f78fc9621a08af7a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCStreamer::emitInt64 (uint64_t Value)</td>
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



<p>Definition at line 730 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Reference <a href="#a971830cc1546210be8cc86fa568be8d0">emitIntValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobe/#a4fbe96db8448f1711fd51c4f4601c063">llvm::MCPseudoProbe::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobeinlinetree/#a803da0fccbb98b7ceaf9240f55fa69b6">llvm::MCPseudoProbeInlineTree::emit</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a3a90d46a868772348b417ed1a94b3a94">llvm::TargetLoweringObjectFileELF::emitModuleMetadata</a>.</p>

</div>
</div>

### emitInt8 {#af47540299db471532b82aba9314f1fc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCStreamer::emitInt8 (uint64_t Value)</td>
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



<p>Definition at line 727 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>Reference <a href="#a971830cc1546210be8cc86fa568be8d0">emitIntValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a204614db7296af6e2492c48c3a8ffd03">ARM64EmitUnwindCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a0bd3fbe76161d42d7470f0dd7dd634de">ARM64EmitUnwindInfoForSegment</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a27cc5388854780051ed416ab2901e18e">ARMEmitUnwindCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#ab831cd4cdeb2330513a8ca4d3ad3f610">ARMEmitUnwindInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableheader/#a1b87cc4b647fd0f14ea7c46227ae2d58">llvm::MCDwarfLineTableHeader::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobe/#a4fbe96db8448f1711fd51c4f4601c063">llvm::MCPseudoProbe::emit</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#aabfe51a98519272e0f4ee5e0fdcb90b0">emitEncodingByte</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#a43decaae146363e80c3ba5b685016bb5">llvm::CodeViewContext::emitFileChecksums</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#ae3810dff97d2b1f712f053e18a98f383">EmitGenDwarfAbbrev</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a1b98f9e375747640ed4f1f019b0558aa">EmitGenDwarfAranges</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#acd1c7609888ea3462f400dcfbca2e486">emitGenDwarfRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a21d50101946fb3648d4d662a0e1d0406">llvm::MCELFStreamer::emitIdent</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a3cd35b2eb52932034ebff3b18e0dcf0a">llvm::TargetLoweringObjectFileELF::emitLinkerDirectives</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcdwarf/#ad32db1a85072666827c900bee74761b1">llvm::mcdwarf::emitListsTableHeaderStart</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a3a90d46a868772348b417ed1a94b3a94">llvm::TargetLoweringObjectFileELF::emitModuleMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#adf60d16739e1ceabb1cee9e9dede7ba5">llvm::MCDwarfLineTable::emitOne</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a6144ace1bbb2a8b3fe310225914ee101">EmitUnwindCode</a> and <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a5d75ea3f9831315ebdb816d70c58c30b">EmitUnwindInfo</a>.</p>

</div>
</div>

### emitIntValue {#a971830cc1546210be8cc86fa568be8d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitIntValue (uint64_t Value, unsigned Size)</td>
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

<p>Special case of EmitValue that avoids the client having to pass in a <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> for constant integers.</p>


<p>EmitIntValue - Special case of EmitValue that avoids the client having to pass in a <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> for constant integers.</p>


<p>Declaration at line 717 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbad861877da56b8b4ceb35c8cbfdf65bb4">llvm::big</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a108ca68c609b3e8c00918a68d26905fa">llvm::support::endian::byte_swap</a>, <a href="#af94e84eca402017c9ce57b7b4c4104e3">emitBytes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad80b46c754cc7216244a866ec9b1cb0">llvm::isIntN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a995470163b6d76695cba5bc8dfb529">llvm::isUIntN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#afe30d1dfbe988401ae6ded700dd877bc">llvm::MCObjectStreamer::emitAbsoluteSymbolDiff</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a4d9e8e23e14d63569e6f0121aabd33ce">llvm::MipsTargetELFStreamer::emitDirectiveEnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectstreamer-cpp/#adad943b5b84c1f1ebef9a2c4e7318052">emitDwarfSetLineAddr</a>, <a href="#a392206962fc4ac790aede10497c7e10b">emitDwarfUnitLength</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#aa660e7b419602632507f83ec8a1520aa">llvm::MCObjectStreamer::emitFill</a>, <a href="/web-llvm/docs/api/classes/anonymous-armelfstreamer-cpp-/armelfstreamer/#a64c883532dcb4cc6bb2ef3b3f0ae0cad">anonymous{ARMELFStreamer.cpp}::ARMELFStreamer::emitFnEnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a1b98f9e375747640ed4f1f019b0558aa">EmitGenDwarfAranges</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#acd1c7609888ea3462f400dcfbca2e486">emitGenDwarfRanges</a>, <a href="#a9d412a2cef594fc0f45de176d51fee3b">emitInt16</a>, <a href="#acc3817979bc871dba942b87773da1cc0">emitInt32</a>, <a href="#ac46413fa6b39176f78fc9621a08af7a5">emitInt64</a>, <a href="#af47540299db471532b82aba9314f1fc2">emitInt8</a>, <a href="#a7d36cf8691cdd5195631e8bbd8d38fc2">emitIntValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipselfstreamer/#ad5453aa898813b8ffa313658fa144eb7">llvm::MipsELFStreamer::emitIntValue</a>, <a href="#a4339a05bb7a7fb9207f2c78644ce4983">emitIntValueInHex</a>, <a href="#a91b6cd6682b8cf4374eb1323b81bddc8">emitIntValueInHexWithPadding</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/amdgpumckernelcodet/#a766a8f22f00b2895f373b0328840e760">llvm::AMDGPU::AMDGPUMCKernelCodeT::EmitKernelCodeT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armasmprinter-cpp/#a135ddd8bff5dd7ec257b04d1cdc9af2b">emitNonLazySymbolPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86asmprinter-cpp/#a135ddd8bff5dd7ec257b04d1cdc9af2b">emitNonLazySymbolPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#ad8a1ae695b98f49601a5986f612da526">llvm::AArch64TargetStreamer::emitNoteSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinestr/#ad325ab6e610eb8bd1f59534515561fdc">llvm::MCDwarfLineStr::emitRef</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a9ef24f653b777a160537ee3e1d824663">llvm::MCObjectStreamer::emitValueImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add7950de32faf22d7d5f78a22f14d32f">llvm::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/faultmaps/#a393b0f5b51aef71d44cc36b4e7b048a7">llvm::FaultMaps::serializeToFaultMapSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonasmprinter-cpp/#a462520f520e196eb7d97d2077f86a8e2">smallData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2f8e7754bbc7c049946acba12e02f815">llvm::writeIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaefdd437a2e602d6fa582edfd9057ca8">llvm::writeIndexTable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4534cfa73850f1cfb963ba677f35bdf4">llvm::writeNewOffsetsTo</a>.</p>

</div>
</div>

### emitIntValue {#a7d36cf8691cdd5195631e8bbd8d38fc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitIntValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Value)</td>
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



<p>Declaration at line 718 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a7b68be12c974b6b70bc86062f221a344">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::data</a>, <a href="#af94e84eca402017c9ce57b7b4c4104e3">emitBytes</a>, <a href="#a971830cc1546210be8cc86fa568be8d0">emitIntValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a4ee2015697caec796e59972aadc2f9e2">llvm::sys::IsLittleEndianHost</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a126453035cc98d97d01233bc532b32aa">llvm::StoreIntToMemory</a> and <a href="/web-llvm/docs/api/classes/llvm/smallstring/#af5dd7241878be5eed07736eb156bb10b">llvm::SmallString&lt; InternalLen &gt;::str</a>.</p>

</div>
</div>

### emitIntValueInHex {#a4339a05bb7a7fb9207f2c78644ce4983}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCStreamer::emitIntValueInHex (uint64_t Value, unsigned Size)</td>
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

<p>Special case of EmitValue that avoids the client having to pass in a <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> for constant integers &amp; prints in Hex format for certain modes.</p>

<p>Definition at line 723 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>References <a href="#a971830cc1546210be8cc86fa568be8d0">emitIntValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### emitIntValueInHexWithPadding {#a91b6cd6682b8cf4374eb1323b81bddc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCStreamer::emitIntValueInHexWithPadding (uint64_t Value, unsigned Size)</td>
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

<p>Special case of EmitValue that avoids the client having to pass in a <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> for constant integers &amp; prints in Hex format for certain modes, pads the field with leading zeros to Size width.</p>

<p>Definition at line 735 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>References <a href="#a971830cc1546210be8cc86fa568be8d0">emitIntValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### emitNops {#a03abb4df5c516e1801f1364c403adfd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCStreamer::emitNops (int64_t NumBytes, int64_t ControlledNopLength, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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



<p>Declaration at line 823 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>

</div>
</div>

### emitSLEB128IntValue {#ae9c7bfbd6f1a6b08ebabb1ca16be3d7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MCStreamer::emitSLEB128IntValue (int64_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Special case of EmitSLEB128Value that avoids the client having to pass in a <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> for constant integers.</p>


<p>EmitSLEB128IntValue - Special case of EmitSLEB128Value that avoids the client having to pass in a <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> for constant integers.</p>


<p>Declaration at line 749 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="#af94e84eca402017c9ce57b7b4c4104e3">emitBytes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac21006e81ffbbc79e8e51e44f7878053">llvm::encodeSLEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream/#a9c2cac84e46d3e744aeca03dd3d557d1">llvm::raw_svector_ostream::str</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobe/#a4fbe96db8448f1711fd51c4f4601c063">llvm::MCPseudoProbe::emit</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a79809d23367b5aafd98b71ae67a0d2d4">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitDwarfAdvanceLineAddr</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a398cbd8a4b88d125a501b3f6b5932588">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitSLEB128Value</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a336e9d6670e6116965fdc68d16001f34">llvm::MCObjectStreamer::emitSLEB128Value</a>.</p>

</div>
</div>

### emitSLEB128Value {#adfe511cd5e910ebacc67825d067347da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitSLEB128Value (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value)</td>
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



<p>Declaration at line 741 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1272 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>

</div>
</div>

### emitSymbolValue {#a7865bd61cd2c65b2d94c58dd1523bb75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitSymbolValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym, unsigned Size, bool IsSectionRelative=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Special case of EmitValue that avoids the client having to pass in a <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> for MCSymbols.</p>

<p>Declaration at line 753 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="#a714de05372be0237bac97ad800dd2b52">emitCOFFSecRel32</a>, <a href="#ae3d6e5ea7b855357014a16db766dddfd">emitValueImpl</a>, <a href="#a61c979932b890df773ce75013b76708b">getContext</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a8061d1e593a8f095f0efe3ba0d793531">emitAbsoluteSymbolDiff</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a79809d23367b5aafd98b71ae67a0d2d4">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitDwarfAdvanceLineAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectstreamer-cpp/#adad943b5b84c1f1ebef9a2c4e7318052">emitDwarfSetLineAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#a73ba925c2a5e09782525ede9dc691059">llvm::CodeViewContext::emitFileChecksumOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a1b98f9e375747640ed4f1f019b0558aa">EmitGenDwarfAranges</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#acf36aff5a25265c3165e94a9ba5ab078">llvm::TargetLoweringObjectFileELF::emitPersonalityValueImpl</a>.</p>

</div>
</div>

### emitTPRel32Value {#a6f5a9c52ffa8394dbe016360b4c3379a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitTPRel32Value (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value)</td>
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

<p>Emit the expression <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> into the output as a tprel (32-bit TP relative) value.</p>


<p>This is used to implement assembler directives such as .tprelword on targets that support them.</p>


<p>Declaration at line 782 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### emitTPRel64Value {#a8e2e9044b6de1aa53fd40d33e4cfe4c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitTPRel64Value (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value)</td>
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

<p>Emit the expression <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> into the output as a tprel (64-bit TP relative) value.</p>


<p>This is used to implement assembler directives such as .tpreldword on targets that support them.</p>


<p>Declaration at line 775 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### emitULEB128IntValue {#abc5f738b9471c3ed31b8f1fc7dc8e914}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MCStreamer::emitULEB128IntValue (uint64_t Value, unsigned PadTo=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Special case of EmitULEB128Value that avoids the client having to pass in a <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> for constant integers.</p>


<p>EmitULEB128IntValue - Special case of EmitULEB128Value that avoids the client having to pass in a <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> for constant integers.</p>


<p>Declaration at line 745 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="#af94e84eca402017c9ce57b7b4c4104e3">emitBytes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream/#a9c2cac84e46d3e744aeca03dd3d557d1">llvm::raw_svector_ostream::str</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobe/#a4fbe96db8448f1711fd51c4f4601c063">llvm::MCPseudoProbe::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobeinlinetree/#a803da0fccbb98b7ceaf9240f55fa69b6">llvm::MCPseudoProbeInlineTree::emit</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#aa131aa465a52fed2d70d09bfd862f8da">EmitAbbrev</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#aad8d06379b43b4e55d8cfc4908a486a9">llvm::MCObjectStreamer::emitAbsoluteSymbolDiffAsULEB128</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a79809d23367b5aafd98b71ae67a0d2d4">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitDwarfAdvanceLineAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectstreamer-cpp/#adad943b5b84c1f1ebef9a2c4e7318052">emitDwarfSetLineAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#ae3810dff97d2b1f712f053e18a98f383">EmitGenDwarfAbbrev</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a3a90d46a868772348b417ed1a94b3a94">llvm::TargetLoweringObjectFileELF::emitModuleMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#adf60d16739e1ceabb1cee9e9dede7ba5">llvm::MCDwarfLineTable::emitOne</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a7f51a5e71249c406f3e5f1dd24201546">emitOneV5FileEntry</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a2f652a1af8c13dd04aa1b2ba2cfd80d8">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitULEB128Value</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3185de2c18363c09c6db8e3e1546c9f8">llvm::MCObjectStreamer::emitULEB128Value</a>.</p>

</div>
</div>

### emitULEB128Value {#abe4c2642ccb651af1def37f17f10bd19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitULEB128Value (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value)</td>
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



<p>Declaration at line 739 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1271 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Referenced by <a href="#a4f385d04b05418cfd8b1337ac541256c">emitAbsoluteSymbolDiffAsULEB128</a> and <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#acd1c7609888ea3462f400dcfbca2e486">emitGenDwarfRanges</a>.</p>

</div>
</div>

### emitValue {#a7833630c617e5943c0a41755f5d4bdcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value, unsigned Size, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 713 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="#ae3d6e5ea7b855357014a16db766dddfd">emitValueImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a66a4df49046ec16dd9c64d36ba3cb62c">ARM64EmitRuntimeFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a0bd3fbe76161d42d7470f0dd7dd634de">ARM64EmitUnwindInfoForSegment</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a48d2597504af337577491cde138a142b">ARMEmitRuntimeFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#ab831cd4cdeb2330513a8ca4d3ad3f610">ARMEmitUnwindInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#ab68ca7cc744c7d305f655930067e0a64">EmitAbsDifference</a>, <a href="#a8061d1e593a8f095f0efe3ba0d793531">emitAbsoluteSymbolDiff</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a479c805988e7c9a81faae52757503066">emitAbsValue</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpool/#a504a7be63300c2c61d79be758524a433">llvm::CSKYConstantPool::emitAll</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp/#a66c9a59a24a4fdac5b800255b1b3f23d">emitAuthenticatedPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/constantpool/#ac62d870b374d12290edc181c27cdbdf6">llvm::ConstantPool::emitEntries</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a07c0db5089a287c91b8197cad7f2eeda">emitFDESymbol</a>, <a href="/web-llvm/docs/api/classes/anonymous-armelfstreamer-cpp-/armelfstreamer/#a64c883532dcb4cc6bb2ef3b3f0ae0cad">anonymous{ARMELFStreamer.cpp}::ARMELFStreamer::emitFnEnd</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer/#a00e4f812d3f229d47f31c41cfddadddc">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::emitFPOData</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a1b98f9e375747640ed4f1f019b0558aa">EmitGenDwarfAranges</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#acd1c7609888ea3462f400dcfbca2e486">emitGenDwarfRanges</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a11156cb1f872cbe35d40c6f36a21d56f">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitIntValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a02ddab75d51b8f46e8e2327dbb0e367b">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitIntValueInHex</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a9e376ffce522c2c85b62c86d18867336">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitIntValueInHexWithPadding</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/amdgpumckernelcodet/#a766a8f22f00b2895f373b0328840e760">llvm::AMDGPU::AMDGPUMCKernelCodeT::EmitKernelCodeT</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetelfstreamer/#a6b2f770d3a95aa3a96fdde70ad59fbbd">llvm::XtensaTargetELFStreamer::emitLiteral</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armasmprinter-cpp/#a135ddd8bff5dd7ec257b04d1cdc9af2b">emitNonLazySymbolPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86asmprinter-cpp/#a135ddd8bff5dd7ec257b04d1cdc9af2b">emitNonLazySymbolPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#aa5b673bb0b1684ee529dc9fcafd6167b">EmitPersonality</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinestr/#ad325ab6e610eb8bd1f59534515561fdc">llvm::MCDwarfLineStr::emitRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#aa186dddb4125136ff27007f97e26759a">EmitRuntimeFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a9387871e1bade9ef3f96c2469ec92fe0">EmitSymbolRefWithOfs</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a70e3e2288f783c384791e314b8e20231">EmitSymbolRefWithOfs</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a5d75ea3f9831315ebdb816d70c58c30b">EmitUnwindInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/avrmcelfstreamer/#aa77f604b9e33cc0e95652bc4da85adae">llvm::AVRMCELFStreamer::emitValueForModiferKind</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonasmprinter-cpp/#a462520f520e196eb7d97d2077f86a8e2">smallData</a>.</p>

</div>
</div>

### emitValueImpl {#ae3d6e5ea7b855357014a16db766dddfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitValueImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value, unsigned Size, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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

<p>Emit the expression <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> into the output as a native integer of the given <span class="doxyComputerOutput">Size</span> bytes.</p>


<p>This is used to implement assembler directives such as .word, .quad, etc.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/value"&gt;Value&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- The value to emit.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>- The size of the integer (in bytes) to emit. This must match a native machine width.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- The location of the expression for error reporting.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 710 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1268 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#afb2fc7b7b30a601f94f8f5a6297ec68f">visitUsedExpr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a4d9e8e23e14d63569e6f0121aabd33ce">llvm::MipsTargetELFStreamer::emitDirectiveEnd</a>, <a href="#a7865bd61cd2c65b2d94c58dd1523bb75">emitSymbolValue</a>, <a href="#a7833630c617e5943c0a41755f5d4bdcf">emitValue</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a9ef24f653b777a160537ee3e1d824663">llvm::MCObjectStreamer::emitValueImpl</a>.</p>

</div>
</div>

### emitValueToAlignment {#a9488c32df3cb8819f6a07f8c88d72c66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitValueToAlignment (<a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, int64_t Value=0, unsigned ValueSize=1, unsigned MaxBytesToEmit=0)</td>
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

<p>Emit some number of copies of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> until the byte alignment <span class="doxyComputerOutput">ByteAlignment</span> is reached.</p>


<p>If the number of bytes need to emit for the alignment is not a multiple of <span class="doxyComputerOutput">ValueSize</span>, then the contents of the emitted fill bytes is undefined.</p>


<p>This used to implement the .align assembler directive.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Alignment</td>
<td class="doxyParamItemDescription"><p>- The alignment to reach.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/value"&gt;Value&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- The value to use when filling bytes.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ValueSize</td>
<td class="doxyParamItemDescription"><p>- The size of the integer (in bytes) to emit for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span>. This must match a native machine width.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MaxBytesToEmit</td>
<td class="doxyParamItemDescription"><p>- The maximum numbers of bytes to emit, or 0. If the alignment cannot be reached in this many bytes, no bytes are emitted.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 846 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1276 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a66a4df49046ec16dd9c64d36ba3cb62c">ARM64EmitRuntimeFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a0bd3fbe76161d42d7470f0dd7dd634de">ARM64EmitUnwindInfoForSegment</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a48d2597504af337577491cde138a142b">ARMEmitRuntimeFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#ab831cd4cdeb2330513a8ca4d3ad3f610">ARMEmitUnwindInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#a3d5bfc5811bed855825f405f757caf44">llvm::AMDGPUTargetELFStreamer::EmitCodeEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/constantpool/#ac62d870b374d12290edc181c27cdbdf6">llvm::ConstantPool::emitEntries</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer/#a00e4f812d3f229d47f31c41cfddadddc">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::emitFPOData</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#ad8a1ae695b98f49601a5986f612da526">llvm::AArch64TargetStreamer::emitNoteSection</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a6d60dc7f70a5ab7a44c79f6bba354c0f">llvm::TargetLoweringObjectFileELF::emitPersonalityValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#aa186dddb4125136ff27007f97e26759a">EmitRuntimeFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a5d75ea3f9831315ebdb816d70c58c30b">EmitUnwindInfo</a>.</p>

</div>
</div>

### emitValueToOffset {#ac28f9bc04d492da0076b2852d4e9dded}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitValueToOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Offset, unsigned char Value, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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

<p>Emit some number of copies of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> until the byte offset <span class="doxyComputerOutput">Offset</span> is reached.</p>


<p>This is used to implement assembler directives such as .org.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Offset</td>
<td class="doxyParamItemDescription"><p>- The offset to reach. This may be an expression, but the expression must be associated with the current section.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/value"&gt;Value&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- The value to use when filling bytes.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 871 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 1281 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/mcparserutils/#a71d0c2aeb5e324a4a962bcfa85617f2c">llvm::MCParserUtils::parseAssignmentExpression</a>.</p>

</div>
</div>

### emitZeros {#ae77a5b8d3af591a461aeac723de33240}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCStreamer::emitZeros (uint64_t NumBytes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit NumBytes worth of zeros.</p>


<p>The implementation in this class just redirects to emitFill.</p>


<p>This function properly handles data in virtual sections.</p>


<p>Declaration at line 828 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="#af6a6f6142b6fd138cdc9e08217577c4d">emitFill</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/asmprinter/xrayfunctionentry/#aaf3c3728de7d947c5dda5dc44a67378b">llvm::AsmPrinter::XRayFunctionEntry::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a29a3c5dc6082aabd411724f33011f795">llvm::MCELFStreamer::emitCommonSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcxcoffstreamer/#a3aac14b3e4ad12e94a2d1a3ec2263b93">llvm::MCXCOFFStreamer::emitCommonSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a98ffe083ab6ade934683a26a65204179">llvm::MCWinCOFFStreamer::emitLocalCommonSymbol</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcmachostreamer-cpp-/mcmachostreamer/#af20b6581bfb880b0df6d552b229739f9">anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::emitZerofill</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonmcelfstreamer/#a64f1accd42a5eb6c0d80c800e63123b9">llvm::HexagonMCELFStreamer::HexagonMCEmitCommonSymbol</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
