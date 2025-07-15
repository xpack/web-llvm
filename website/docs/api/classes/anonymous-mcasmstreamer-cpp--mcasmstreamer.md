---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCAsmStreamer` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{MCAsmStreamer.cpp}::MCAsmStreamer { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Streaming machine code generation interface. <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a528f3b8c204e96bf6a9b2680f22b4af6">MCAsmStreamer</a> (MCContext &amp;Context, std::unique_ptr&lt; formatted_raw_ostream &gt; os, MCInstPrinter *printer, std::unique_ptr&lt; MCCodeEmitter &gt; emitter, std::unique_ptr&lt; MCAsmBackend &gt; asmbackend)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3dde63a47820ff7740ed6d126a47ad7">getAssembler</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a5a64cfc0ba1eb4d686099f6db64930">getAssemblerPtr</a> () override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ef4c13483eb05982d1c2023484d58ee">emitSyntaxDirective</a> () override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab07e49a5499032dc8f97198892218853">EmitCommentsAndEOL</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14f1e87a295b0eb495042a2a02976cf2">isVerboseAsm</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this streamer supports verbose assembly at all. <a href="#a14f1e87a295b0eb495042a2a02976cf2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa892ddf5fe83cb36e0c714bc4af7e42d">hasRawTextSupport</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Do we support EmitRawText? <a href="#aa892ddf5fe83cb36e0c714bc4af7e42d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d10fbe43b4e2dc5ddde4dacc0429b84">AddComment</a> (const Twine &amp;T, bool EOL=true) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a comment that can be emitted to the generated .s file to make the output of the compiler more readable. <a href="#a6d10fbe43b4e2dc5ddde4dacc0429b84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf7b75691e086935319e3142cb2eb579">AddEncodingComment</a> (const MCInst &amp;Inst, const MCSubtargetInfo &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a comment showing the encoding of an instruction. <a href="#acf7b75691e086935319e3142cb2eb579">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f76a99d4a915c6b36833085bee383c2">getCommentOS</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> that comments can be written to. <a href="#a2f76a99d4a915c6b36833085bee383c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a467ce7d3bd5cb0e5df12b2b7063a4a4d">emitRawComment</a> (const Twine &amp;T, bool TabPrefix=true) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print T and prefix it with the comment string (normally #) and optionally a tab. <a href="#a467ce7d3bd5cb0e5df12b2b7063a4a4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e419b9328977a480fda42c789b77237">addExplicitComment</a> (const Twine &amp;T) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add explicit comment T. <a href="#a5e419b9328977a480fda42c789b77237">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1400e693c6c532e696d1505b75970187">emitExplicitComments</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit added explicit comments. <a href="#a1400e693c6c532e696d1505b75970187">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41c8e31ff5e62e8bbc993811b5087f49">addBlankLine</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a blank line to a .s file to pretty it up. <a href="#a41c8e31ff5e62e8bbc993811b5087f49">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bc00d06c62e15be5f5081158962456d">EmitRegisterName</a> (int64_t Register)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4fa555d80394501b4d6c1cc9a61e7bb">PrintQuotedString</a> (StringRef Data, raw_ostream &amp;OS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8af09b85ea0acebe5fcd63a80944f095">printDwarfFileDirective</a> (unsigned FileNo, StringRef Directory, StringRef Filename, std::optional&lt; MD5::MD5Result &gt; Checksum, std::optional&lt; StringRef &gt; Source, bool UseDwarfDirectory, raw_svector_ostream &amp;OS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a334d1a9d00fbd4ccd62289c19122c63f">emitCFIStartProcImpl</a> (MCDwarfFrameInfo &amp;Frame) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15a985a9b2e5b76cc040405e4ce34088">emitCFIEndProcImpl</a> (MCDwarfFrameInfo &amp;Frame) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">formatted_raw_ostream</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1c141cf8bb1ed4363ade47f67923cca">OSOwner</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">formatted_raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae750100b36d7c5fdd6ab21b3b2281e48">OS</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7167005c9a17ecd52389673205352c79">MAI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter">MCInstPrinter</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35cb5944176a86f920c793960ab25fff">InstPrinter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b30693ee3baa324fc1ea3b73cec7fd8">Assembler</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 128 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a181862a183010080d50d6cc9325007b8">ExplicitCommentToEmit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 128 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe23755981fd1639eeb1d53700c1e2f2">CommentToEmit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream">raw_svector_ostream</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61ca41606388cb3385268b547b418e5f">CommentStream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-null-ostream">raw_null_ostream</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaefb881f9dea8065751e45713eb6ad2b">NullStream</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2072c8f81018bc7772d1cd22ab9a7b05">EmittedSectionDirective</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a135b67ed67b399e1b30c42a10bf30775">IsVerboseAsm</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a814cbef0595e88817db0f42905372d0d">ShowInst</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cccd2fd9b195286021f64be33e83e2a">UseDwarfDirectory</a> = false</td>
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

## MCStreamer Interface Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4712c0b6d11e44d06eea24bc7b786ca9">switchSection</a> (MCSection *Section, uint32_t Subsection) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the current section where code is being emitted to <span class="doxyComputerOutput">Section</span>. <a href="#a4712c0b6d11e44d06eea24bc7b786ca9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34cd5a64eb935155249865a6f30bdc5d">popSection</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Restore the current and previous section from the section stack. <a href="#a34cd5a64eb935155249865a6f30bdc5d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3cd968a6ba01a35c097a702ea02fb4f">emitELFSymverDirective</a> (const MCSymbol *OriginalSym, StringRef Name, bool KeepOriginalSym) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an ELF .symver directive. <a href="#ab3cd968a6ba01a35c097a702ea02fb4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5dd9aa863646f04e05baf2e8ace9406">emitLOHDirective</a> (MCLOHType Kind, const MCLOHArgs &amp;Args) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a Linker Optimization Hint (LOH) directive. <a href="#ab5dd9aa863646f04e05baf2e8ace9406">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49aba7bece7f857a6c983f133890adcc">emitGNUAttribute</a> (unsigned Tag, unsigned Value) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a .gnu_attribute directive. <a href="#a49aba7bece7f857a6c983f133890adcc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6e393e30f9c56864f4db9487f1e6b8b">getMnemonic</a> (const MCInst &amp;MI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the mnemonic for <span class="doxyComputerOutput">MI</span>, if the streamer has access to a instruction printer and returns an empty string otherwise. <a href="#ad6e393e30f9c56864f4db9487f1e6b8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99306d453eed689739055115d79beeca">emitLabel</a> (MCSymbol *Symbol, SMLoc Loc=SMLoc()) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a label for <span class="doxyComputerOutput">Symbol</span> into the current section. <a href="#a99306d453eed689739055115d79beeca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a893d769cea2092372271f39d515a817b">emitAssemblerFlag</a> (MCAssemblerFlag Flag) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Note in the output the specified <span class="doxyComputerOutput">Flag</span>. <a href="#a893d769cea2092372271f39d515a817b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a393824072c5571972394a72ee86cf1">emitLinkerOptions</a> (ArrayRef&lt; std::string &gt; Options) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the given list <span class="doxyComputerOutput">Options</span> of strings as linker options into the output. <a href="#a8a393824072c5571972394a72ee86cf1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae857977308ca4e1d0cf0311bd3f60004">emitDataRegion</a> (MCDataRegionType Kind) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Note in the output the specified region <span class="doxyComputerOutput">Kind</span>. <a href="#ae857977308ca4e1d0cf0311bd3f60004">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a422f5621940beb2e051d9468d4f70922">emitVersionMin</a> (MCVersionMinType Kind, unsigned Major, unsigned Minor, unsigned Update, VersionTuple SDKVersion) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specify the Mach-O minimum deployment target version. <a href="#a422f5621940beb2e051d9468d4f70922">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73d1f3201777b81d5a80bd6da19e7bee">emitBuildVersion</a> (unsigned Platform, unsigned Major, unsigned Minor, unsigned Update, VersionTuple SDKVersion) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit/Specify Mach-O build version command. <a href="#a73d1f3201777b81d5a80bd6da19e7bee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ed0f07369e726c4b4bacacd90e6370e">emitDarwinTargetVariantBuildVersion</a> (unsigned Platform, unsigned Major, unsigned Minor, unsigned Update, VersionTuple SDKVersion) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf1e3a2cb44fc1a7742edfbea3d9d6ee">emitThumbFunc</a> (MCSymbol *Func) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Note in the output that the specified <span class="doxyComputerOutput">Func</span> is a Thumb mode function (ARM target only). <a href="#abf1e3a2cb44fc1a7742edfbea3d9d6ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1d5c7867737745f90d074f16eb1c485">emitAssignment</a> (MCSymbol *Symbol, const MCExpr *Value) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an assignment of <span class="doxyComputerOutput">Value</span> to <span class="doxyComputerOutput">Symbol</span>. <a href="#af1d5c7867737745f90d074f16eb1c485">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c0673e9d30e91b31c2dbbfdae47f3f1">emitConditionalAssignment</a> (MCSymbol *Symbol, const MCExpr *Value) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an assignment of <span class="doxyComputerOutput">Value</span> to <span class="doxyComputerOutput">Symbol</span>, but only if <span class="doxyComputerOutput">Value</span> is also emitted. <a href="#a6c0673e9d30e91b31c2dbbfdae47f3f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d9da6fd250447386af90f45a41bb8a0">emitWeakReference</a> (MCSymbol *Alias, const MCSymbol *Symbol) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an weak reference from <span class="doxyComputerOutput">Alias</span> to <span class="doxyComputerOutput">Symbol</span>. <a href="#a4d9da6fd250447386af90f45a41bb8a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2ddc96d94abf0d970032254268e8de1">emitSymbolAttribute</a> (MCSymbol *Symbol, MCSymbolAttr Attribute) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the given <span class="doxyComputerOutput">Attribute</span> to <span class="doxyComputerOutput">Symbol</span>. <a href="#ae2ddc96d94abf0d970032254268e8de1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c803c21220f5051c6e06a0a09c35017">emitSymbolDesc</a> (MCSymbol *Symbol, unsigned DescValue) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the <span class="doxyComputerOutput">DescValue</span> for the <span class="doxyComputerOutput">Symbol</span>. <a href="#a1c803c21220f5051c6e06a0a09c35017">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f07a7968600a0a57c9be68ce45ab663">beginCOFFSymbolDef</a> (const MCSymbol *Symbol) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Start emitting COFF symbol definition. <a href="#a5f07a7968600a0a57c9be68ce45ab663">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad40a805686d6978c202a33d1959cdab2">emitCOFFSymbolStorageClass</a> (int StorageClass) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the storage class of the symbol. <a href="#ad40a805686d6978c202a33d1959cdab2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a093409e5884cbc663864a9b9babf648f">emitCOFFSymbolType</a> (int Type) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the type of the symbol. <a href="#a093409e5884cbc663864a9b9babf648f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad27b03230251d90cbb679fe5ea2c2eb1">endCOFFSymbolDef</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Marks the end of the symbol definition. <a href="#ad27b03230251d90cbb679fe5ea2c2eb1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa108b614b3c2a6acf218a9d3a5b9bbab">emitCOFFSafeSEH</a> (MCSymbol const *Symbol) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07b9dd53ef7b4b22520cfdd39e97f59f">emitCOFFSymbolIndex</a> (MCSymbol const *Symbol) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits the symbol table index of a Symbol into the current section. <a href="#a07b9dd53ef7b4b22520cfdd39e97f59f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a137f7472e780d6adfc7ce97af2f316ed">emitCOFFSectionIndex</a> (MCSymbol const *Symbol) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits a COFF section index. <a href="#a137f7472e780d6adfc7ce97af2f316ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae58362142a998a77b2da1b204aa9454f">emitCOFFSecRel32</a> (MCSymbol const *Symbol, uint64_t Offset) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits a COFF section relative relocation. <a href="#ae58362142a998a77b2da1b204aa9454f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d4c0f9e042548ec43e2a8bc0d609c01">emitCOFFImgRel32</a> (MCSymbol const *Symbol, int64_t Offset) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits a COFF image relative relocation. <a href="#a5d4c0f9e042548ec43e2a8bc0d609c01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1973d22545db5643cccab850c1ac693f">emitCOFFSecNumber</a> (MCSymbol const *Symbol) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits the physical number of the section containing the given symbol as assigned during object writing (i.e., this is not a runtime relocation). <a href="#a1973d22545db5643cccab850c1ac693f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae27d6f9cc9c43537ed435a6df1bc965c">emitCOFFSecOffset</a> (MCSymbol const *Symbol) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits the offset of the symbol from the beginning of the section during object writing (i.e., this is not a runtime relocation). <a href="#ae27d6f9cc9c43537ed435a6df1bc965c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d3b4a12c2fbc688388c6c2b422f8e88">emitXCOFFLocalCommonSymbol</a> (MCSymbol *LabelSym, uint64_t Size, MCSymbol *CsectSym, Align Alignment) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits an lcomm directive with XCOFF csect information. <a href="#a2d3b4a12c2fbc688388c6c2b422f8e88">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf2edddac64334f7baaa80739f8f2df7">emitXCOFFSymbolLinkageWithVisibility</a> (MCSymbol *Symbol, MCSymbolAttr Linkage, MCSymbolAttr Visibility) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a symbol's linkage and visibility with a linkage directive for XCOFF. <a href="#aaf2edddac64334f7baaa80739f8f2df7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37f26d2730c10e4c90f1b175ea4118e9">emitXCOFFRenameDirective</a> (const MCSymbol *Name, StringRef Rename) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a XCOFF .rename directive which creates a synonym for an illegal or undesirable name. <a href="#a37f26d2730c10e4c90f1b175ea4118e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02c8de429d8ab8ead0705b3b548a86e6">emitXCOFFRefDirective</a> (const MCSymbol *Symbol) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a XCOFF .ref directive which creates R_REF type entry in the relocation table for one or more symbols. <a href="#a02c8de429d8ab8ead0705b3b548a86e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2976594c904759e6ea0d3ded1b113059">emitXCOFFExceptDirective</a> (const MCSymbol *Symbol, const MCSymbol *Trap, unsigned Lang, unsigned Reason, unsigned FunctionSize, bool hasDebug) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an XCOFF .except directive which adds information about a trap instruction to the object file exception section. <a href="#a2976594c904759e6ea0d3ded1b113059">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b923ddd75e27a332230dc648f4443f4">emitXCOFFCInfoSym</a> (StringRef Name, StringRef Metadata) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a C_INFO symbol with XCOFF embedded metadata to the .info section. <a href="#a5b923ddd75e27a332230dc648f4443f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b406af868aa746d08c62b38d8c259f7">emitELFSize</a> (MCSymbol *Symbol, const MCExpr *Value) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an ELF .size directive. <a href="#a3b406af868aa746d08c62b38d8c259f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53cb03e5a5afb8080089249f461f141e">emitCommonSymbol</a> (MCSymbol *Symbol, uint64_t Size, Align ByteAlignment) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a common symbol. <a href="#a53cb03e5a5afb8080089249f461f141e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa905c95a461602c484dfdf155114f4c7">emitLocalCommonSymbol</a> (MCSymbol *Symbol, uint64_t Size, Align ByteAlignment) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a local common (.lcomm) symbol. <a href="#aa905c95a461602c484dfdf155114f4c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ce73ec5824c032df5044c83409259be">emitZerofill</a> (MCSection *Section, MCSymbol *Symbol=nullptr, uint64_t Size=0, Align ByteAlignment=Align(1), SMLoc Loc=SMLoc()) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the zerofill section and an optional symbol. <a href="#a3ce73ec5824c032df5044c83409259be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb1b0b113e4532d3f1e83b665f9c1906">emitTBSSSymbol</a> (MCSection *Section, MCSymbol *Symbol, uint64_t Size, Align ByteAlignment=Align(1)) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a thread local bss (.tbss) symbol. <a href="#afb1b0b113e4532d3f1e83b665f9c1906">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11ee8035c689127e9b32128b00dc47d7">emitBinaryData</a> (StringRef Data) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Functionally identical to EmitBytes. <a href="#a11ee8035c689127e9b32128b00dc47d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a807369cf0e8ddbe75c8c4a671bfc4258">emitBytes</a> (StringRef Data) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the bytes in <span class="doxyComputerOutput">Data</span> into the output. <a href="#a807369cf0e8ddbe75c8c4a671bfc4258">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae37bcdd18e5b8eb58b8d88effad3fed8">emitValueImpl</a> (const MCExpr *Value, unsigned Size, SMLoc Loc=SMLoc()) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the expression <span class="doxyComputerOutput">Value</span> into the output as a native integer of the given <span class="doxyComputerOutput">Size</span> bytes. <a href="#ae37bcdd18e5b8eb58b8d88effad3fed8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11156cb1f872cbe35d40c6f36a21d56f">emitIntValue</a> (uint64_t Value, unsigned Size) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Special case of EmitValue that avoids the client having to pass in a MCExpr for constant integers. <a href="#a11156cb1f872cbe35d40c6f36a21d56f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02ddab75d51b8f46e8e2327dbb0e367b">emitIntValueInHex</a> (uint64_t Value, unsigned Size) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Special case of EmitValue that avoids the client having to pass in a MCExpr for constant integers &amp; prints in Hex format for certain modes. <a href="#a02ddab75d51b8f46e8e2327dbb0e367b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e376ffce522c2c85b62c86d18867336">emitIntValueInHexWithPadding</a> (uint64_t Value, unsigned Size) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Special case of EmitValue that avoids the client having to pass in a MCExpr for constant integers &amp; prints in Hex format for certain modes, pads the field with leading zeros to Size width. <a href="#a9e376ffce522c2c85b62c86d18867336">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f652a1af8c13dd04aa1b2ba2cfd80d8">emitULEB128Value</a> (const MCExpr *Value) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a398cbd8a4b88d125a501b3f6b5932588">emitSLEB128Value</a> (const MCExpr *Value) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ec882a8aecc1b17265d0bebffa5cb1c">emitDTPRel32Value</a> (const MCExpr *Value) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the expression <span class="doxyComputerOutput">Value</span> into the output as a dtprel (32-bit DTP relative) value. <a href="#a2ec882a8aecc1b17265d0bebffa5cb1c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb95b400bf91f96c149f206e45dc0d09">emitDTPRel64Value</a> (const MCExpr *Value) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the expression <span class="doxyComputerOutput">Value</span> into the output as a dtprel (64-bit DTP relative) value. <a href="#afb95b400bf91f96c149f206e45dc0d09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4884277cc2c31ed03c037671a632d8ad">emitTPRel32Value</a> (const MCExpr *Value) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the expression <span class="doxyComputerOutput">Value</span> into the output as a tprel (32-bit TP relative) value. <a href="#a4884277cc2c31ed03c037671a632d8ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ba5fdec68cf4b56fb2ec57f42753267">emitTPRel64Value</a> (const MCExpr *Value) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the expression <span class="doxyComputerOutput">Value</span> into the output as a tprel (64-bit TP relative) value. <a href="#a5ba5fdec68cf4b56fb2ec57f42753267">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa557364f7fbf9210e7937d72e1eaa1e3">emitGPRel64Value</a> (const MCExpr *Value) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the expression <span class="doxyComputerOutput">Value</span> into the output as a gprel64 (64-bit GP relative) value. <a href="#aa557364f7fbf9210e7937d72e1eaa1e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac08027460665b9a74ec5770fc3c69105">emitGPRel32Value</a> (const MCExpr *Value) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the expression <span class="doxyComputerOutput">Value</span> into the output as a gprel32 (32-bit GP relative) value. <a href="#ac08027460665b9a74ec5770fc3c69105">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae6d9fb29c7a596c66c84d2ccb0457dd">emitFill</a> (const MCExpr &amp;NumBytes, uint64_t FillValue, SMLoc Loc=SMLoc()) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit <span class="doxyComputerOutput">Size</span> bytes worth of the value specified by <span class="doxyComputerOutput">FillValue</span>. <a href="#aae6d9fb29c7a596c66c84d2ccb0457dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a664095c8afe2051a5e22b25100685b01">emitFill</a> (const MCExpr &amp;NumValues, int64_t Size, int64_t Expr, SMLoc Loc=SMLoc()) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit <span class="doxyComputerOutput">NumValues</span> copies of <span class="doxyComputerOutput">Size</span> bytes. <a href="#a664095c8afe2051a5e22b25100685b01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36690cdc5f927e7553ec268a036a722f">emitAlignmentDirective</a> (uint64_t ByteAlignment, std::optional&lt; int64_t &gt; Value, unsigned ValueSize, unsigned MaxBytesToEmit)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd79313d43de902e2f2f8d2c0189215c">emitValueToAlignment</a> (Align Alignment, int64_t Value=0, unsigned ValueSize=1, unsigned MaxBytesToEmit=0) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit some number of copies of <span class="doxyComputerOutput">Value</span> until the byte alignment <span class="doxyComputerOutput">ByteAlignment</span> is reached. <a href="#acd79313d43de902e2f2f8d2c0189215c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c9184047a9545737b7e35c9607c64df">emitCodeAlignment</a> (Align Alignment, const MCSubtargetInfo *STI, unsigned MaxBytesToEmit=0) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit nops until the byte alignment <span class="doxyComputerOutput">ByteAlignment</span> is reached. <a href="#a5c9184047a9545737b7e35c9607c64df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae043f2028a3e9aaf8e8aacd77c059dc8">emitValueToOffset</a> (const MCExpr *Offset, unsigned char Value, SMLoc Loc) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit some number of copies of <span class="doxyComputerOutput">Value</span> until the byte offset <span class="doxyComputerOutput">Offset</span> is reached. <a href="#ae043f2028a3e9aaf8e8aacd77c059dc8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bad68e4b10776e708626a8c6b25c965">emitFileDirective</a> (StringRef Filename) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Switch to a new logical file. <a href="#a9bad68e4b10776e708626a8c6b25c965">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20a4c6ed55ed94fa363e630573918107">emitFileDirective</a> (StringRef Filename, StringRef CompilerVersion, StringRef TimeStamp, StringRef Description) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit ".file assembler diretive with additioal info. <a href="#a20a4c6ed55ed94fa363e630573918107">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2807954a9bf3d29ba94545ebaa23584">tryEmitDwarfFileDirective</a> (unsigned FileNo, StringRef Directory, StringRef Filename, std::optional&lt; MD5::MD5Result &gt; Checksum=std::nullopt, std::optional&lt; StringRef &gt; Source=std::nullopt, unsigned CUID=0) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Associate a filename with a specified logical file number. <a href="#aa2807954a9bf3d29ba94545ebaa23584">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa88bfe9ae2423322c5a88908de8ba22">emitDwarfFile0Directive</a> (StringRef Directory, StringRef Filename, std::optional&lt; MD5::MD5Result &gt; Checksum, std::optional&lt; StringRef &gt; Source, unsigned CUID=0) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specify the "root" file of the compilation, using the ".file 0" extension. <a href="#afa88bfe9ae2423322c5a88908de8ba22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbf8b87c2743700b4bc2f187d06c9a28">emitDwarfLocDirective</a> (unsigned FileNo, unsigned Line, unsigned Column, unsigned Flags, unsigned Isa, unsigned Discriminator, StringRef FileName) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This implements the DWARF2 '.loc fileno lineno ...' assembler directive. <a href="#afbf8b87c2743700b4bc2f187d06c9a28">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a8d7833400582f801ce932f7b59261">emitDwarfLocLabelDirective</a> (SMLoc Loc, StringRef Name) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This implements the '.loc_label Name' directive. <a href="#a97a8d7833400582f801ce932f7b59261">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55febacdfb6b6c8b692186d32dbe96c2">getDwarfLineTableSymbol</a> (unsigned CUID) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11b1131686b3d58fdda416597ca504f8">emitCVFileDirective</a> (unsigned FileNo, StringRef Filename, ArrayRef&lt; uint8_t &gt; Checksum, unsigned ChecksumKind) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Associate a filename with a specified logical file number, and also specify that file's checksum information. <a href="#a11b1131686b3d58fdda416597ca504f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6177856d4e399300f3940086c56425cb">emitCVFuncIdDirective</a> (unsigned FuncId) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Introduces a function id for use with .cv_loc. <a href="#a6177856d4e399300f3940086c56425cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c677e18b455acc6e512bae0216093d8">emitCVInlineSiteIdDirective</a> (unsigned FunctionId, unsigned IAFunc, unsigned IAFile, unsigned IALine, unsigned IACol, SMLoc Loc) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Introduces an inline call site id for use with .cv_loc. <a href="#a6c677e18b455acc6e512bae0216093d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0de5f7018dd4bdee0616920178ee0bc">emitCVLocDirective</a> (unsigned FunctionId, unsigned FileNo, unsigned Line, unsigned Column, bool PrologueEnd, bool IsStmt, StringRef FileName, SMLoc Loc) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This implements the CodeView '.cv_loc' assembler directive. <a href="#ad0de5f7018dd4bdee0616920178ee0bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a238e59e2af8906f2cfc5155663d7a196">emitCVLinetableDirective</a> (unsigned FunctionId, const MCSymbol *FnStart, const MCSymbol *FnEnd) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This implements the CodeView '.cv_linetable' assembler directive. <a href="#a238e59e2af8906f2cfc5155663d7a196">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa96077a0e4bce1c56fb5c2660e5752df">emitCVInlineLinetableDirective</a> (unsigned PrimaryFunctionId, unsigned SourceFileId, unsigned SourceLineNum, const MCSymbol *FnStartSym, const MCSymbol *FnEndSym) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This implements the CodeView '.cv_inline_linetable' assembler directive. <a href="#aa96077a0e4bce1c56fb5c2660e5752df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a467384728fb302838e583379b7b23079">PrintCVDefRangePrefix</a> (ArrayRef&lt; std::pair&lt; const MCSymbol *, const MCSymbol * &gt; &gt; Ranges)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa49eb297857f4bf2aeec6b1d3f57b051">emitCVDefRangeDirective</a> (ArrayRef&lt; std::pair&lt; const MCSymbol *, const MCSymbol * &gt; &gt; Ranges, codeview::DefRangeRegisterRelHeader DRHdr) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a096a232a154a45ff185cd71961f565f9">emitCVDefRangeDirective</a> (ArrayRef&lt; std::pair&lt; const MCSymbol *, const MCSymbol * &gt; &gt; Ranges, codeview::DefRangeSubfieldRegisterHeader DRHdr) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a534087ca10707b8e963d0093d687136e">emitCVDefRangeDirective</a> (ArrayRef&lt; std::pair&lt; const MCSymbol *, const MCSymbol * &gt; &gt; Ranges, codeview::DefRangeRegisterHeader DRHdr) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f2246f74c434ed53299fdf711b1f9a5">emitCVDefRangeDirective</a> (ArrayRef&lt; std::pair&lt; const MCSymbol *, const MCSymbol * &gt; &gt; Ranges, codeview::DefRangeFramePointerRelHeader DRHdr) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa1fac5c5ed19d64e3e6b8f69984f21c">emitCVStringTableDirective</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This implements the CodeView '.cv_stringtable' assembler directive. <a href="#afa1fac5c5ed19d64e3e6b8f69984f21c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a6083e6ee9f56004ccbee4b83ccf764">emitCVFileChecksumsDirective</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This implements the CodeView '.cv_filechecksums' assembler directive. <a href="#a3a6083e6ee9f56004ccbee4b83ccf764">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a316200def17e7bb5db6b91900313a262">emitCVFileChecksumOffsetDirective</a> (unsigned FileNo) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This implements the CodeView '.cv_filechecksumoffset' assembler directive. <a href="#a316200def17e7bb5db6b91900313a262">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1fd3e492100e8cc074e33590fc9e951">emitCVFPOData</a> (const MCSymbol *ProcSym, SMLoc L) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This implements the CodeView '.cv_fpo_data' assembler directive. <a href="#af1fd3e492100e8cc074e33590fc9e951">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0a11a27e8bdbf6749d8e7d20fd380f7">emitIdent</a> (StringRef IdentString) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the "identifiers" directive. <a href="#ad0a11a27e8bdbf6749d8e7d20fd380f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90418f29973b14097248f7ac471b4601">emitCFIBKeyFrame</a> () override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65104a9150bbdbc652e32ba00e45c7a4">emitCFIMTETaggedFrame</a> () override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a724fc73861d0edd1560d8bc919fab367">emitCFISections</a> (bool EH, bool Debug) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6996bce7ed70cee8ce64cf58b0f67df1">emitCFIDefCfa</a> (int64_t Register, int64_t Offset, SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fd03efd6ce5b55cc6c6bf1afb4fd650">emitCFIDefCfaOffset</a> (int64_t Offset, SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23730892bc6167f3f73277923a986ea7">emitCFIDefCfaRegister</a> (int64_t Register, SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a719913ede040feaea18c58b51d274fc2">emitCFILLVMDefAspaceCfa</a> (int64_t Register, int64_t Offset, int64_t AddressSpace, SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e9f218fee0bd6340115d4710ce467a9">emitCFIOffset</a> (int64_t Register, int64_t Offset, SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e7a2fbd7a50f4bb4db72650d848e706">emitCFIPersonality</a> (const MCSymbol *Sym, unsigned Encoding) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83ebec98343071d599da4791ca684669">emitCFILsda</a> (const MCSymbol *Sym, unsigned Encoding) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4950e4dfd8d0686f56fcef68f9ad836a">emitCFIRememberState</a> (SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83eb4cee5005e172b3e90427591eb43b">emitCFIRestoreState</a> (SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27f3e7dca0f76d616d10398e7a5b4952">emitCFIRestore</a> (int64_t Register, SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6e4ad4e354e26ed7fd0982a83861dd5">emitCFISameValue</a> (int64_t Register, SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84d605bf22158345464e37444897dc9b">emitCFIRelOffset</a> (int64_t Register, int64_t Offset, SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a9f2fcfbe8ff4ef1d2c161af79131d4">emitCFIAdjustCfaOffset</a> (int64_t Adjustment, SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fef34027fa50e93af1d29428199df26">emitCFIEscape</a> (StringRef Values, SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ba55c78541fd684b5ccd7eb8aacec66">emitCFIGnuArgsSize</a> (int64_t Size, SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9248320d0eb1f90204263d4994606824">emitCFISignalFrame</a> () override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83cbf7779ed7c37391e64acd29fb26d9">emitCFIUndefined</a> (int64_t Register, SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7376cdebe10c84e3d70cf0462eaf8527">emitCFIRegister</a> (int64_t Register1, int64_t Register2, SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f42c1f466d0e89a35438cb99727bc09">emitCFIWindowSave</a> (SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bcea8c54481f254291d8b05ef89b468">emitCFINegateRAState</a> (SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59e34064a47d3e0980a80cb6a48f70f2">emitCFINegateRAStateWithPC</a> (SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9aa19cd6f2863b4b3d8d1658721ce4eb">emitCFIReturnColumn</a> (int64_t Register) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1368dcd0236358f2e93224d719a5ed4c">emitCFILabelDirective</a> (SMLoc Loc, StringRef Name) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebd16a157411cf1e93601fde53dd2947">emitCFIValOffset</a> (int64_t Register, int64_t Offset, SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f68951e04ae06a7a386f17a3a7d1cb5">emitWinCFIStartProc</a> (const MCSymbol *Symbol, SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fd5e1b1e4d675662b464bbf587e8054">emitWinCFIEndProc</a> (SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9a5dce582cf654f096cdad605ea38ce">emitWinCFIFuncletOrFuncEnd</a> (SMLoc Loc) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is used on platforms, such as Windows on ARM64, that require function or funclet sizes to be emitted in .xdata before the End marker is emitted for the frame. <a href="#af9a5dce582cf654f096cdad605ea38ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ce02f7cd680caa9cdc9d19decbec097">emitWinCFIStartChained</a> (SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4606f6d1acb29e734341e0bc78655356">emitWinCFIEndChained</a> (SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c2773f2fd46f185d617c084afa98ab6">emitWinCFIPushReg</a> (MCRegister Register, SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99577354457a83f041f80baf798d507e">emitWinCFISetFrame</a> (MCRegister Register, unsigned Offset, SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecf41e0f616b168c70d4d7e1c5b12b19">emitWinCFIAllocStack</a> (unsigned Size, SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dfc20c93c509c1d196cdf0e8e66acae">emitWinCFISaveReg</a> (MCRegister Register, unsigned Offset, SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af831d087fdf1bd0af05bb382182593f4">emitWinCFISaveXMM</a> (MCRegister Register, unsigned Offset, SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af38a4d16a207c3672f2e06d2f8897915">emitWinCFIPushFrame</a> (bool Code, SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ec5db274b0af678a8e45ccf25b89690">emitWinCFIEndProlog</a> (SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb765c6ee407ec7777308406d9fbcf30">emitWinEHHandler</a> (const MCSymbol *Sym, bool Unwind, bool Except, SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27ab1f18a7bff8a82c03e03302227f0d">emitWinEHHandlerData</a> (SMLoc Loc) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac25530725b6ee241fdd59a2b41cc8222">emitCGProfileEntry</a> (const MCSymbolRefExpr *From, const MCSymbolRefExpr *To, uint64_t Count) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a161ac460fefc16f98a8dd1a9f019af9a">emitInstruction</a> (const MCInst &amp;Inst, const MCSubtargetInfo &amp;STI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the given <span class="doxyComputerOutput">Instruction</span> into the current section. <a href="#a161ac460fefc16f98a8dd1a9f019af9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b50dd93932455982bef5aaf44afd0aa">emitPseudoProbe</a> (uint64_t Guid, uint64_t Index, uint64_t Type, uint64_t Attr, uint64_t Discriminator, const MCPseudoProbeInlineStack &amp;InlineStack, MCSymbol *FnSym) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the a pseudo probe into the current section. <a href="#a9b50dd93932455982bef5aaf44afd0aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecf8ecc5a7e96d648c872b27d1879b97">emitBundleAlignMode</a> (Align Alignment) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the bundle alignment mode from now on in the section. <a href="#aecf8ecc5a7e96d648c872b27d1879b97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bd62cdc3f9bbdf9dccd85a1c5a2c5e3">emitBundleLock</a> (bool AlignToEnd) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The following instructions are a bundle-locked group. <a href="#a8bd62cdc3f9bbdf9dccd85a1c5a2c5e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a336b40b93fb8407be18a6fbf07bc43d0">emitBundleUnlock</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Ends a bundle-locked group. <a href="#a336b40b93fb8407be18a6fbf07bc43d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::pair&lt; bool, std::string &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34bd9da2c0260776c7eb80aef5229322">emitRelocDirective</a> (const MCExpr &amp;Offset, StringRef Name, const MCExpr *Expr, SMLoc Loc, const MCSubtargetInfo &amp;STI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Record a relocation described by the .reloc directive. <a href="#a34bd9da2c0260776c7eb80aef5229322">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a912aa786213dc38228fe5f8a63a4e409">emitAddrsig</a> () override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaec2d1923c9f931fc50ff7d8f06a4555">emitAddrsigSym</a> (const MCSymbol *Sym) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c9b3bbd630571b3a00b01b38742e79c">emitRawTextImpl</a> (StringRef String) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this file is backed by an assembly streamer, this dumps the specified string in the output .s file. <a href="#a9c9b3bbd630571b3a00b01b38742e79c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5333321f84976a4bf06be40827ca62d8">finishImpl</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Streamer specific finalization. <a href="#a5333321f84976a4bf06be40827ca62d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f4b96f764a5ad6bcb7a3e0c0e4ee339">emitDwarfUnitLength</a> (uint64_t Length, const Twine &amp;Comment) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a unit length field. <a href="#a8f4b96f764a5ad6bcb7a3e0c0e4ee339">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5d953a682bfa6d424f05dca8d56b9ed">emitDwarfUnitLength</a> (const Twine &amp;Prefix, const Twine &amp;Comment) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a unit length field. <a href="#aa5d953a682bfa6d424f05dca8d56b9ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc85cf8fcb99aada0bb615989928b516">emitDwarfLineStartLabel</a> (MCSymbol *StartSym) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the debug line start label. <a href="#abc85cf8fcb99aada0bb615989928b516">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa72d5840fe6b92c329861c90b8a7c58c">emitDwarfLineEndEntry</a> (MCSection *Section, MCSymbol *LastLabel, MCSymbol *EndLabel=nullptr) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the debug line end entry. <a href="#aa72d5840fe6b92c329861c90b8a7c58c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79809d23367b5aafd98b71ae67a0d2d4">emitDwarfAdvanceLineAddr</a> (int64_t LineDelta, const MCSymbol *LastLabel, const MCSymbol *Label, unsigned PointerSize) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If targets does not support representing debug line section by .loc/.file directives in assembly output, we need to populate debug line section with raw debug line contents. <a href="#a79809d23367b5aafd98b71ae67a0d2d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MCAsmStreamer() {#a528f3b8c204e96bf6a9b2680f22b4af6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::MCAsmStreamer (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Context, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">formatted_raw_ostream</a> &gt; os, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter">MCInstPrinter</a> * printer, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> &gt; emitter, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> &gt; asmbackend)</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions/#a465c716319177c7bd66f91856de9b950a58188af3953f4687fd6806e933e23fff">llvm::MCTargetOptions::DefaultDwarfDirectory</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions/#a465c716319177c7bd66f91856de9b950ad2087ee63cfdfb4d320b2fed6ccd93a2">llvm::MCTargetOptions::DisableDwarfDirectory</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions/#a465c716319177c7bd66f91856de9b950a0ad3dcce4e7f9e1fa609ed0c529aba6d">llvm::MCTargetOptions::EnableDwarfDirectory</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a91d427d805fbdbcddd4d6381bee35ba6">llvm::MCStreamer::MCStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#a97eec4cd1bdbc225c1aaf199eec5c97f">printer</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a84e19f7283c7e529b0762e1fdd4ba8b0">llvm::MCStreamer::setAllowAutoPadding</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a24b9ec99014d8eeef69271383962ef91">llvm::createAsmStreamer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addBlankLine() {#a41c8e31ff5e62e8bbc993811b5087f49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::addBlankLine ()</td>
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

<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Reference <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### AddComment() {#a6d10fbe43b4e2dc5ddde4dacc0429b84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::AddComment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; T, bool EOL=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Add a comment that can be emitted to the generated .s file to make the output of the compiler more readable.</p>


<p>This only affects the <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer">MCAsmStreamer</a> and only when verbose assembly output is enabled.</p>


<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Referenced by <a href="#a79809d23367b5aafd98b71ae67a0d2d4">emitDwarfAdvanceLineAddr</a>.</p>

</div>
</div>

### AddEncodingComment() {#acf7b75691e086935319e3142cb2eb579}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::AddEncodingComment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a comment showing the encoding of an instruction.</p>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter/#a65397c092d290f6c8d326e30439460fa">llvm::MCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="#ad3dde63a47820ff7740ed6d126a47ad7">getAssembler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#ab01b807c062ac4610366c6772ad5fd16">llvm::MCAssembler::getBackend</a>, <a href="#a2f76a99d4a915c6b36833085bee383c2">getCommentOS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a923971fae5bb26b2613d5b17ce09ac8e">llvm::MCAssembler::getEmitter</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#ad4777f004ef52f665e6ec6defc1cb32a">llvm::MCAsmBackend::getFixupKindInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a>.</p>


<p>Referenced by <a href="#a161ac460fefc16f98a8dd1a9f019af9a">emitInstruction</a>.</p>

</div>
</div>

### addExplicitComment() {#a5e419b9328977a480fda42c789b77237}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::addExplicitComment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; T)</td>
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


<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5b6faabb08339ea1dd11e9d37a668634">llvm::StringRef::back</a>, <a href="#a1400e693c6c532e696d1505b75970187">emitExplicitComments</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a93b15a8c0022febbe39d17ab933737a8">llvm::StringRef::find_first_of</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a61364ca3a5ff90fb2aa0d5a371fd43f7">llvm::StringRef::front</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5d4c961b9b6f1da17df74b4496ecb30e">llvm::StringRef::slice</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>.</p>

</div>
</div>

### EmitCommentsAndEOL() {#ab07e49a5499032dc8f97198892218853}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::EmitCommentsAndEOL ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5b6faabb08339ea1dd11e9d37a668634">llvm::StringRef::back</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aab312a8386488873bac2eddfc67c22be">llvm::StringRef::find</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>.</p>


<p>Referenced by <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### EmitEOL() {#a7064b16a5706077633ab420138948ae9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::EmitEOL ()</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#ab07e49a5499032dc8f97198892218853">EmitCommentsAndEOL</a> and <a href="#a1400e693c6c532e696d1505b75970187">emitExplicitComments</a>.</p>


<p>Referenced by <a href="#a41c8e31ff5e62e8bbc993811b5087f49">addBlankLine</a>, <a href="#a5f07a7968600a0a57c9be68ce45ab663">beginCOFFSymbolDef</a>, <a href="#a912aa786213dc38228fe5f8a63a4e409">emitAddrsig</a>, <a href="#aaec2d1923c9f931fc50ff7d8f06a4555">emitAddrsigSym</a>, <a href="#a36690cdc5f927e7553ec268a036a722f">emitAlignmentDirective</a>, <a href="#a893d769cea2092372271f39d515a817b">emitAssemblerFlag</a>, <a href="#af1d5c7867737745f90d074f16eb1c485">emitAssignment</a>, <a href="#a11ee8035c689127e9b32128b00dc47d7">emitBinaryData</a>, <a href="#a73d1f3201777b81d5a80bd6da19e7bee">emitBuildVersion</a>, <a href="#aecf8ecc5a7e96d648c872b27d1879b97">emitBundleAlignMode</a>, <a href="#a8bd62cdc3f9bbdf9dccd85a1c5a2c5e3">emitBundleLock</a>, <a href="#a336b40b93fb8407be18a6fbf07bc43d0">emitBundleUnlock</a>, <a href="#a807369cf0e8ddbe75c8c4a671bfc4258">emitBytes</a>, <a href="#a9a9f2fcfbe8ff4ef1d2c161af79131d4">emitCFIAdjustCfaOffset</a>, <a href="#a90418f29973b14097248f7ac471b4601">emitCFIBKeyFrame</a>, <a href="#a6996bce7ed70cee8ce64cf58b0f67df1">emitCFIDefCfa</a>, <a href="#a1fd03efd6ce5b55cc6c6bf1afb4fd650">emitCFIDefCfaOffset</a>, <a href="#a23730892bc6167f3f73277923a986ea7">emitCFIDefCfaRegister</a>, <a href="#a7fef34027fa50e93af1d29428199df26">emitCFIEscape</a>, <a href="#a0ba55c78541fd684b5ccd7eb8aacec66">emitCFIGnuArgsSize</a>, <a href="#a1368dcd0236358f2e93224d719a5ed4c">emitCFILabelDirective</a>, <a href="#a719913ede040feaea18c58b51d274fc2">emitCFILLVMDefAspaceCfa</a>, <a href="#a83ebec98343071d599da4791ca684669">emitCFILsda</a>, <a href="#a65104a9150bbdbc652e32ba00e45c7a4">emitCFIMTETaggedFrame</a>, <a href="#a8bcea8c54481f254291d8b05ef89b468">emitCFINegateRAState</a>, <a href="#a59e34064a47d3e0980a80cb6a48f70f2">emitCFINegateRAStateWithPC</a>, <a href="#a4e9f218fee0bd6340115d4710ce467a9">emitCFIOffset</a>, <a href="#a2e7a2fbd7a50f4bb4db72650d848e706">emitCFIPersonality</a>, <a href="#a7376cdebe10c84e3d70cf0462eaf8527">emitCFIRegister</a>, <a href="#a84d605bf22158345464e37444897dc9b">emitCFIRelOffset</a>, <a href="#a4950e4dfd8d0686f56fcef68f9ad836a">emitCFIRememberState</a>, <a href="#a27f3e7dca0f76d616d10398e7a5b4952">emitCFIRestore</a>, <a href="#a83eb4cee5005e172b3e90427591eb43b">emitCFIRestoreState</a>, <a href="#a9aa19cd6f2863b4b3d8d1658721ce4eb">emitCFIReturnColumn</a>, <a href="#ae6e4ad4e354e26ed7fd0982a83861dd5">emitCFISameValue</a>, <a href="#a724fc73861d0edd1560d8bc919fab367">emitCFISections</a>, <a href="#a9248320d0eb1f90204263d4994606824">emitCFISignalFrame</a>, <a href="#a83cbf7779ed7c37391e64acd29fb26d9">emitCFIUndefined</a>, <a href="#aebd16a157411cf1e93601fde53dd2947">emitCFIValOffset</a>, <a href="#a3f42c1f466d0e89a35438cb99727bc09">emitCFIWindowSave</a>, <a href="#ac25530725b6ee241fdd59a2b41cc8222">emitCGProfileEntry</a>, <a href="#a5d4c0f9e042548ec43e2a8bc0d609c01">emitCOFFImgRel32</a>, <a href="#aa108b614b3c2a6acf218a9d3a5b9bbab">emitCOFFSafeSEH</a>, <a href="#a1973d22545db5643cccab850c1ac693f">emitCOFFSecNumber</a>, <a href="#ae27d6f9cc9c43537ed435a6df1bc965c">emitCOFFSecOffset</a>, <a href="#ae58362142a998a77b2da1b204aa9454f">emitCOFFSecRel32</a>, <a href="#a137f7472e780d6adfc7ce97af2f316ed">emitCOFFSectionIndex</a>, <a href="#a07b9dd53ef7b4b22520cfdd39e97f59f">emitCOFFSymbolIndex</a>, <a href="#ad40a805686d6978c202a33d1959cdab2">emitCOFFSymbolStorageClass</a>, <a href="#a093409e5884cbc663864a9b9babf648f">emitCOFFSymbolType</a>, <a href="#a53cb03e5a5afb8080089249f461f141e">emitCommonSymbol</a>, <a href="#a6c0673e9d30e91b31c2dbbfdae47f3f1">emitConditionalAssignment</a>, <a href="#a3f2246f74c434ed53299fdf711b1f9a5">emitCVDefRangeDirective</a>, <a href="#a534087ca10707b8e963d0093d687136e">emitCVDefRangeDirective</a>, <a href="#aa49eb297857f4bf2aeec6b1d3f57b051">emitCVDefRangeDirective</a>, <a href="#a096a232a154a45ff185cd71961f565f9">emitCVDefRangeDirective</a>, <a href="#a316200def17e7bb5db6b91900313a262">emitCVFileChecksumOffsetDirective</a>, <a href="#a3a6083e6ee9f56004ccbee4b83ccf764">emitCVFileChecksumsDirective</a>, <a href="#a11b1131686b3d58fdda416597ca504f8">emitCVFileDirective</a>, <a href="#af1fd3e492100e8cc074e33590fc9e951">emitCVFPOData</a>, <a href="#aa96077a0e4bce1c56fb5c2660e5752df">emitCVInlineLinetableDirective</a>, <a href="#a238e59e2af8906f2cfc5155663d7a196">emitCVLinetableDirective</a>, <a href="#ad0de5f7018dd4bdee0616920178ee0bc">emitCVLocDirective</a>, <a href="#afa1fac5c5ed19d64e3e6b8f69984f21c">emitCVStringTableDirective</a>, <a href="#ae857977308ca4e1d0cf0311bd3f60004">emitDataRegion</a>, <a href="#a2ec882a8aecc1b17265d0bebffa5cb1c">emitDTPRel32Value</a>, <a href="#afb95b400bf91f96c149f206e45dc0d09">emitDTPRel64Value</a>, <a href="#afbf8b87c2743700b4bc2f187d06c9a28">emitDwarfLocDirective</a>, <a href="#a97a8d7833400582f801ce932f7b59261">emitDwarfLocLabelDirective</a>, <a href="#a3b406af868aa746d08c62b38d8c259f7">emitELFSize</a>, <a href="#ab3cd968a6ba01a35c097a702ea02fb4f">emitELFSymverDirective</a>, <a href="#a9bad68e4b10776e708626a8c6b25c965">emitFileDirective</a>, <a href="#a20a4c6ed55ed94fa363e630573918107">emitFileDirective</a>, <a href="#aae6d9fb29c7a596c66c84d2ccb0457dd">emitFill</a>, <a href="#a664095c8afe2051a5e22b25100685b01">emitFill</a>, <a href="#ac08027460665b9a74ec5770fc3c69105">emitGPRel32Value</a>, <a href="#aa557364f7fbf9210e7937d72e1eaa1e3">emitGPRel64Value</a>, <a href="#ad0a11a27e8bdbf6749d8e7d20fd380f7">emitIdent</a>, <a href="#a161ac460fefc16f98a8dd1a9f019af9a">emitInstruction</a>, <a href="#a99306d453eed689739055115d79beeca">emitLabel</a>, <a href="#a8a393824072c5571972394a72ee86cf1">emitLinkerOptions</a>, <a href="#aa905c95a461602c484dfdf155114f4c7">emitLocalCommonSymbol</a>, <a href="#ab5dd9aa863646f04e05baf2e8ace9406">emitLOHDirective</a>, <a href="#a9b50dd93932455982bef5aaf44afd0aa">emitPseudoProbe</a>, <a href="#a467ce7d3bd5cb0e5df12b2b7063a4a4d">emitRawComment</a>, <a href="#a9c9b3bbd630571b3a00b01b38742e79c">emitRawTextImpl</a>, <a href="#a34bd9da2c0260776c7eb80aef5229322">emitRelocDirective</a>, <a href="#a398cbd8a4b88d125a501b3f6b5932588">emitSLEB128Value</a>, <a href="#ae2ddc96d94abf0d970032254268e8de1">emitSymbolAttribute</a>, <a href="#a1c803c21220f5051c6e06a0a09c35017">emitSymbolDesc</a>, <a href="#a2ef4c13483eb05982d1c2023484d58ee">emitSyntaxDirective</a>, <a href="#afb1b0b113e4532d3f1e83b665f9c1906">emitTBSSSymbol</a>, <a href="#abf1e3a2cb44fc1a7742edfbea3d9d6ee">emitThumbFunc</a>, <a href="#a4884277cc2c31ed03c037671a632d8ad">emitTPRel32Value</a>, <a href="#a5ba5fdec68cf4b56fb2ec57f42753267">emitTPRel64Value</a>, <a href="#a2f652a1af8c13dd04aa1b2ba2cfd80d8">emitULEB128Value</a>, <a href="#ae37bcdd18e5b8eb58b8d88effad3fed8">emitValueImpl</a>, <a href="#ae043f2028a3e9aaf8e8aacd77c059dc8">emitValueToOffset</a>, <a href="#a422f5621940beb2e051d9468d4f70922">emitVersionMin</a>, <a href="#a4d9da6fd250447386af90f45a41bb8a0">emitWeakReference</a>, <a href="#aecf41e0f616b168c70d4d7e1c5b12b19">emitWinCFIAllocStack</a>, <a href="#a4606f6d1acb29e734341e0bc78655356">emitWinCFIEndChained</a>, <a href="#a0fd5e1b1e4d675662b464bbf587e8054">emitWinCFIEndProc</a>, <a href="#a0ec5db274b0af678a8e45ccf25b89690">emitWinCFIEndProlog</a>, <a href="#af9a5dce582cf654f096cdad605ea38ce">emitWinCFIFuncletOrFuncEnd</a>, <a href="#af38a4d16a207c3672f2e06d2f8897915">emitWinCFIPushFrame</a>, <a href="#a8c2773f2fd46f185d617c084afa98ab6">emitWinCFIPushReg</a>, <a href="#a1dfc20c93c509c1d196cdf0e8e66acae">emitWinCFISaveReg</a>, <a href="#af831d087fdf1bd0af05bb382182593f4">emitWinCFISaveXMM</a>, <a href="#a99577354457a83f041f80baf798d507e">emitWinCFISetFrame</a>, <a href="#a2ce02f7cd680caa9cdc9d19decbec097">emitWinCFIStartChained</a>, <a href="#a1f68951e04ae06a7a386f17a3a7d1cb5">emitWinCFIStartProc</a>, <a href="#adb765c6ee407ec7777308406d9fbcf30">emitWinEHHandler</a>, <a href="#a27ab1f18a7bff8a82c03e03302227f0d">emitWinEHHandlerData</a>, <a href="#a5b923ddd75e27a332230dc648f4443f4">emitXCOFFCInfoSym</a>, <a href="#a2976594c904759e6ea0d3ded1b113059">emitXCOFFExceptDirective</a>, <a href="#a2d3b4a12c2fbc688388c6c2b422f8e88">emitXCOFFLocalCommonSymbol</a>, <a href="#a02c8de429d8ab8ead0705b3b548a86e6">emitXCOFFRefDirective</a>, <a href="#a37f26d2730c10e4c90f1b175ea4118e9">emitXCOFFRenameDirective</a>, <a href="#aaf2edddac64334f7baaa80739f8f2df7">emitXCOFFSymbolLinkageWithVisibility</a>, <a href="#a3ce73ec5824c032df5044c83409259be">emitZerofill</a> and <a href="#ad27b03230251d90cbb679fe5ea2c2eb1">endCOFFSymbolDef</a>.</p>

</div>
</div>

### emitExplicitComments() {#a1400e693c6c532e696d1505b75970187}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitExplicitComments ()</td>
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

<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>.</p>


<p>Referenced by <a href="#a5e419b9328977a480fda42c789b77237">addExplicitComment</a> and <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitRawComment() {#a467ce7d3bd5cb0e5df12b2b7063a4a4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitRawComment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; T, bool TabPrefix=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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


<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Reference <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitSyntaxDirective() {#a2ef4c13483eb05982d1c2023484d58ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitSyntaxDirective ()</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Reference <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### getAssembler() {#ad3dde63a47820ff7740ed6d126a47ad7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAssembler &amp; anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::getAssembler ()</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Referenced by <a href="#acf7b75691e086935319e3142cb2eb579">AddEncodingComment</a> and <a href="#a5333321f84976a4bf06be40827ca62d8">finishImpl</a>.</p>

</div>
</div>

### getAssemblerPtr() {#a5a5a64cfc0ba1eb4d686099f6db64930}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAssembler * anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::getAssemblerPtr ()</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>

</div>
</div>

### getCommentOS() {#a2f76a99d4a915c6b36833085bee383c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::getCommentOS ()</td>
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

<p>Return a <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> that comments can be written to.</p>


<p>Unlike AddComment, you are required to terminate comments with 
<br/>
 if you use this method.</p>


<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a8ad4ae565ad87db4c534952e2c88f310">llvm::nulls</a>.</p>


<p>Referenced by <a href="#acf7b75691e086935319e3142cb2eb579">AddEncodingComment</a> and <a href="#a161ac460fefc16f98a8dd1a9f019af9a">emitInstruction</a>.</p>

</div>
</div>

### hasRawTextSupport() {#aa892ddf5fe83cb36e0c714bc4af7e42d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::hasRawTextSupport ()</td>
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

<p>Do we support EmitRawText?</p>

<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>

</div>
</div>

### isVerboseAsm() {#a14f1e87a295b0eb495042a2a02976cf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::isVerboseAsm ()</td>
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

<p>Return true if this streamer supports verbose assembly at all.</p>

<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### emitCFIEndProcImpl() {#a15a985a9b2e5b76cc040405e4ce34088}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCFIEndProcImpl (<a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo">MCDwarfFrameInfo</a> &amp; Frame)</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>

</div>
</div>

### emitCFIStartProcImpl() {#a334d1a9d00fbd4ccd62289c19122c63f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCFIStartProcImpl (<a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo">MCDwarfFrameInfo</a> &amp; Frame)</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>

</div>
</div>

### EmitRegisterName() {#a6bc00d06c62e15be5f5081158962456d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::EmitRegisterName (int64_t Register)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>

</div>
</div>

### printDwarfFileDirective() {#a8af09b85ea0acebe5fcd63a80944f095}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::printDwarfFileDirective (unsigned FileNo, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directory, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/md5/md5result">MD5::MD5Result</a> &gt; Checksum, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; Source, bool UseDwarfDirectory, <a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream">raw_svector_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>

</div>
</div>

### PrintQuotedString() {#ab4fa555d80394501b4d6c1cc9a61e7bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::PrintQuotedString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Data, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Assembler {#a4b30693ee3baa324fc1ea3b73cec7fd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MCAssembler&gt; anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::Assembler</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>

</div>
</div>

### CommentStream {#a61ca41606388cb3385268b547b418e5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_svector_ostream anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::CommentStream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>

</div>
</div>

### CommentToEmit {#abe23755981fd1639eeb1d53700c1e2f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallString&lt;128&gt; anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::CommentToEmit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>

</div>
</div>

### EmittedSectionDirective {#a2072c8f81018bc7772d1cd22ab9a7b05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::EmittedSectionDirective = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>

</div>
</div>

### ExplicitCommentToEmit {#a181862a183010080d50d6cc9325007b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallString&lt;128&gt; anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::ExplicitCommentToEmit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>

</div>
</div>

### InstPrinter {#a35cb5944176a86f920c793960ab25fff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MCInstPrinter&gt; anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::InstPrinter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>

</div>
</div>

### IsVerboseAsm {#a135b67ed67b399e1b30c42a10bf30775}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::IsVerboseAsm = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>

</div>
</div>

### MAI {#a7167005c9a17ecd52389673205352c79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCAsmInfo* anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::MAI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>

</div>
</div>

### NullStream {#aaefb881f9dea8065751e45713eb6ad2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_null_ostream anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::NullStream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>

</div>
</div>

### OS {#ae750100b36d7c5fdd6ab21b3b2281e48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">formatted_raw_ostream&amp; anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::OS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>

</div>
</div>

### OSOwner {#ab1c141cf8bb1ed4363ade47f67923cca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;formatted_raw_ostream&gt; anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::OSOwner</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>

</div>
</div>

### ShowInst {#a814cbef0595e88817db0f42905372d0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::ShowInst = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>

</div>
</div>

### UseDwarfDirectory {#a5cccd2fd9b195286021f64be33e83e2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::UseDwarfDirectory = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## MCStreamer Interface

### beginCOFFSymbolDef {#a5f07a7968600a0a57c9be68ce45ab663}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::beginCOFFSymbolDef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol)</td>
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

<p>Start emitting COFF symbol definition.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Symbol</td>
<td class="doxyParamItemDescription"><p>- The symbol to have its External &amp; Type fields set.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Reference <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitAddrsig {#a912aa786213dc38228fe5f8a63a4e409}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitAddrsig ()</td>
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



<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Reference <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitAddrsigSym {#aaec2d1923c9f931fc50ff7d8f06a4555}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitAddrsigSym (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym)</td>
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



<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a27f7a23e572edb7b1bc46d9639c3204a">llvm::MCSymbol::print</a>.</p>

</div>
</div>

### emitAlignmentDirective {#a36690cdc5f927e7553ec268a036a722f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitAlignmentDirective (uint64_t ByteAlignment, std::optional&lt; int64_t &gt; Value, unsigned ValueSize, unsigned MaxBytesToEmit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a434f6a0d80fb13e4326e848a6391f057">llvm::isPowerOf2_64</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4f42ed6fd2569fa43f03814a17f9d94a">llvm::Log2_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp/#a9a1994cc203b2699119e91b908b9d50b">truncateToSize</a>.</p>


<p>Referenced by <a href="#a5c9184047a9545737b7e35c9607c64df">emitCodeAlignment</a> and <a href="#acd79313d43de902e2f2f8d2c0189215c">emitValueToAlignment</a>.</p>

</div>
</div>

### emitAssemblerFlag {#a893d769cea2092372271f39d515a817b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitAssemblerFlag (<a href="/web-llvm/docs/api/namespaces/llvm/#aa09571f0b44fd6bd8fae33d6ead290c1">MCAssemblerFlag</a> Flag)</td>
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

<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa09571f0b44fd6bd8fae33d6ead290c1a97f114ed47db100e48185ee6d6ad531b">llvm::MCAF_Code16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa09571f0b44fd6bd8fae33d6ead290c1ad77d445deab9f2715c6d2b48aee116ea">llvm::MCAF_Code32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa09571f0b44fd6bd8fae33d6ead290c1a836c6b17b1d82a5d54d61120d3a99f8a">llvm::MCAF_Code64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa09571f0b44fd6bd8fae33d6ead290c1adeea37757529c5d5cfeb922221d0f6f0">llvm::MCAF_SubsectionsViaSymbols</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa09571f0b44fd6bd8fae33d6ead290c1a4673762188cd819fd32979a26c1c67b5">llvm::MCAF_SyntaxUnified</a>.</p>

</div>
</div>

### emitAssignment {#af1d5c7867737745f90d074f16eb1c485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitAssignment (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value)</td>
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

<p>Emit an assignment of <span class="doxyComputerOutput">Value</span> to <span class="doxyComputerOutput">Symbol</span>.</p>


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
<td class="doxyParamItemName">Value</td>
<td class="doxyParamItemDescription"><p>- The value for the symbol.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a04736ef5753e5ecda3c29ce902094e68">llvm::MCStreamer::emitAssignment</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a1e56c814d11206720cc23059b871128d">llvm::Value::print</a>.</p>


<p>Referenced by <a href="#abc85cf8fcb99aada0bb615989928b516">emitDwarfLineStartLabel</a>.</p>

</div>
</div>

### emitBinaryData {#a11ee8035c689127e9b32128b00dc47d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitBinaryData (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Data)</td>
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


<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### emitBuildVersion {#a73d1f3201777b81d5a80bd6da19e7bee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitBuildVersion (unsigned Platform, unsigned Major, unsigned Minor, unsigned Update, <a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a> SDKVersion)</td>
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

<p>Emit/Specify Mach-O build version command.</p>


<p><span class="doxyComputerOutput">Platform</span> should be one of MachO::PlatformType.</p>


<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp/#a96037fc0434f2d1c064f7748b41f8c1d">EmitSDKVersionSuffix</a> and <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp/#afe722131e76a74beba89f34b423c7a70">getPlatformName</a>.</p>


<p>Referenced by <a href="#a4ed0f07369e726c4b4bacacd90e6370e">emitDarwinTargetVariantBuildVersion</a>.</p>

</div>
</div>

### emitBundleAlignMode {#aecf8ecc5a7e96d648c872b27d1879b97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitBundleAlignMode (<a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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


<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad82de9da62635df78a534de0f16c1129">llvm::Log2</a>.</p>

</div>
</div>

### emitBundleLock {#a8bd62cdc3f9bbdf9dccd85a1c5a2c5e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitBundleLock (bool AlignToEnd)</td>
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

<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Reference <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitBundleUnlock {#a336b40b93fb8407be18a6fbf07bc43d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitBundleUnlock ()</td>
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

<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Reference <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitBytes {#a807369cf0e8ddbe75c8c4a671bfc4258}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitBytes (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Data)</td>
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


<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ae1b3cf074436ef5b527071540e13bd58">llvm::MCStreamer::getCurrentSectionOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a901607e60c20148ae701b6e8f43b4647">llvm::MCStreamer::getTargetStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp/#a2c1b3db86d8571c3f038c371acbcacb7">isPrintableString</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ae5b35beb6f127e5f47269e9124b886fb">LLVM_LIKELY</a> and <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp/#a41a5d3f4153e507fc78c645cdc1037a0">PrintByteList</a>.</p>

</div>
</div>

### emitCFIAdjustCfaOffset {#a9a9f2fcfbe8ff4ef1d2c161af79131d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCFIAdjustCfaOffset (int64_t Adjustment, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ab98cdd0259874847cd346b396f87ed29">llvm::MCStreamer::emitCFIAdjustCfaOffset</a> and <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitCFIBKeyFrame {#a90418f29973b14097248f7ac471b4601}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCFIBKeyFrame ()</td>
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



<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a18b9227cee7d28b311e88626e31470b3">llvm::MCStreamer::emitCFIBKeyFrame</a> and <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitCFIDefCfa {#a6996bce7ed70cee8ce64cf58b0f67df1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCFIDefCfa (int64_t Register, int64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a06d947eb9b24c3c09aec7dae8b242d36">llvm::MCStreamer::emitCFIDefCfa</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### emitCFIDefCfaOffset {#a1fd03efd6ce5b55cc6c6bf1afb4fd650}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCFIDefCfaOffset (int64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ad00e491df6ac397c2836f4823486b814">llvm::MCStreamer::emitCFIDefCfaOffset</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### emitCFIDefCfaRegister {#a23730892bc6167f3f73277923a986ea7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCFIDefCfaRegister (int64_t Register, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#aa3cb8bdbc2ba4f13b85ae876c8db72c8">llvm::MCStreamer::emitCFIDefCfaRegister</a> and <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitCFIEscape {#a7fef34027fa50e93af1d29428199df26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCFIEscape (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Values, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7f85a7656080c1cece6d55421409c2ac">llvm::MCStreamer::emitCFIEscape</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp/#a0cfb229540a44ffdd406ca12e441fd47">PrintCFIEscape</a>.</p>

</div>
</div>

### emitCFIGnuArgsSize {#a0ba55c78541fd684b5ccd7eb8aacec66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCFIGnuArgsSize (int64_t Size, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a00b5e27ba702e289d1355d83634496e8">llvm::MCStreamer::emitCFIGnuArgsSize</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp/#a0cfb229540a44ffdd406ca12e441fd47">PrintCFIEscape</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### emitCFILabelDirective {#a1368dcd0236358f2e93224d719a5ed4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCFILabelDirective (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a886df281f466da825e86d3db00309322">llvm::MCStreamer::emitCFILabelDirective</a> and <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitCFILLVMDefAspaceCfa {#a719913ede040feaea18c58b51d274fc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCFILLVMDefAspaceCfa (int64_t Register, int64_t Offset, int64_t AddressSpace, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#afd9cd40e1c8cda6d287b38bbbc4a65dd">llvm::MCStreamer::emitCFILLVMDefAspaceCfa</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### emitCFILsda {#a83ebec98343071d599da4791ca684669}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCFILsda (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym, unsigned Encoding)</td>
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



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a5fdf26af0fa16c740221a0f1492652da">llvm::MCStreamer::emitCFILsda</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a27f7a23e572edb7b1bc46d9639c3204a">llvm::MCSymbol::print</a>.</p>

</div>
</div>

### emitCFIMTETaggedFrame {#a65104a9150bbdbc652e32ba00e45c7a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCFIMTETaggedFrame ()</td>
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



<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a6c8bdd2a81dd6498072971ec263d61d3">llvm::MCStreamer::emitCFIMTETaggedFrame</a> and <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitCFINegateRAState {#a8bcea8c54481f254291d8b05ef89b468}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCFINegateRAState (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a5e417903a64e0e2e03a881cc22988c03">llvm::MCStreamer::emitCFINegateRAState</a> and <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitCFINegateRAStateWithPC {#a59e34064a47d3e0980a80cb6a48f70f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCFINegateRAStateWithPC (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a2f9a65946cfd95e5fee5434be8061fba">llvm::MCStreamer::emitCFINegateRAStateWithPC</a> and <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitCFIOffset {#a4e9f218fee0bd6340115d4710ce467a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCFIOffset (int64_t Register, int64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#acc89f9e1b110cc78d0b3782c7169fee3">llvm::MCStreamer::emitCFIOffset</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### emitCFIPersonality {#a2e7a2fbd7a50f4bb4db72650d848e706}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCFIPersonality (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym, unsigned Encoding)</td>
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



<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a3721196eca9702a79c55577d867c8535">llvm::MCStreamer::emitCFIPersonality</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a27f7a23e572edb7b1bc46d9639c3204a">llvm::MCSymbol::print</a>.</p>

</div>
</div>

### emitCFIRegister {#a7376cdebe10c84e3d70cf0462eaf8527}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCFIRegister (int64_t Register1, int64_t Register2, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#aa640c4cba0755dc19a91bdb98fec5998">llvm::MCStreamer::emitCFIRegister</a> and <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitCFIRelOffset {#a84d605bf22158345464e37444897dc9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCFIRelOffset (int64_t Register, int64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ac21d03105248455242c40d1b663dfea1">llvm::MCStreamer::emitCFIRelOffset</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### emitCFIRememberState {#a4950e4dfd8d0686f56fcef68f9ad836a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCFIRememberState (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a861747a0f3a48a53fdff7bdc6c1856d8">llvm::MCStreamer::emitCFIRememberState</a> and <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitCFIRestore {#a27f3e7dca0f76d616d10398e7a5b4952}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCFIRestore (int64_t Register, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#af5f8c58b6d8f44d96b1f1d02ba7af4af">llvm::MCStreamer::emitCFIRestore</a> and <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitCFIRestoreState {#a83eb4cee5005e172b3e90427591eb43b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCFIRestoreState (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#aca048ea2881b4d098c005349f99bab62">llvm::MCStreamer::emitCFIRestoreState</a> and <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitCFIReturnColumn {#a9aa19cd6f2863b4b3d8d1658721ce4eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCFIReturnColumn (int64_t Register)</td>
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



<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a35cbb2583bd074641c370112dc50615c">llvm::MCStreamer::emitCFIReturnColumn</a> and <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitCFISameValue {#ae6e4ad4e354e26ed7fd0982a83861dd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCFISameValue (int64_t Register, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a30e73886a8c818640b69a5ca9dfe3b60">llvm::MCStreamer::emitCFISameValue</a> and <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitCFISections {#a724fc73861d0edd1560d8bc919fab367}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCFISections (bool EH, bool Debug)</td>
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



<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/debug-cpp/#a3fd0c3ac7c0e9187aa5c690ef9c70ebe">Debug</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a8e6d59ce0c2235c1e432aefcd928a1e4">llvm::MCStreamer::emitCFISections</a> and <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitCFISignalFrame {#a9248320d0eb1f90204263d4994606824}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCFISignalFrame ()</td>
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



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#aee53d30c51fc0e9ca7c57c52a95da789">llvm::MCStreamer::emitCFISignalFrame</a> and <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitCFIUndefined {#a83cbf7779ed7c37391e64acd29fb26d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCFIUndefined (int64_t Register, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a52d332cc8f6e4738d2b9c3f78ab28f1a">llvm::MCStreamer::emitCFIUndefined</a> and <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitCFIValOffset {#aebd16a157411cf1e93601fde53dd2947}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCFIValOffset (int64_t Register, int64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ae0930d72d21ce9df1f3d41b685411bd9">llvm::MCStreamer::emitCFIValOffset</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### emitCFIWindowSave {#a3f42c1f466d0e89a35438cb99727bc09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCFIWindowSave (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a396af4f92c9743bcf60f86474c7ebadf">llvm::MCStreamer::emitCFIWindowSave</a> and <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitCGProfileEntry {#ac25530725b6ee241fdd59a2b41cc8222}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCGProfileEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr">MCSymbolRefExpr</a> * From, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr">MCSymbolRefExpr</a> * To, uint64_t Count)</td>
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



<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a048f077746d95f142d02e56586862bf2">llvm::MCSymbolRefExpr::getSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a27f7a23e572edb7b1bc46d9639c3204a">llvm::MCSymbol::print</a>.</p>

</div>
</div>

### emitCodeAlignment {#a5c9184047a9545737b7e35c9607c64df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCodeAlignment (<a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI, unsigned MaxBytesToEmit=0)</td>
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
<td class="doxyParamItemDescription"><p>- The MCSubtargetInfo in operation when padding is emitted.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MaxBytesToEmit</td>
<td class="doxyParamItemDescription"><p>- The maximum numbers of bytes to emit, or 0. If the alignment cannot be reached in this many bytes, no bytes are emitted.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a36690cdc5f927e7553ec268a036a722f">emitAlignmentDirective</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>

</div>
</div>

### emitCOFFImgRel32 {#a5d4c0f9e042548ec43e2a8bc0d609c01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCOFFImgRel32 (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * Symbol, int64_t Offset)</td>
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

<p>Emits a COFF image relative relocation.</p>


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

<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### emitCOFFSafeSEH {#aa108b614b3c2a6acf218a9d3a5b9bbab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCOFFSafeSEH (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * Symbol)</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Reference <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitCOFFSecNumber {#a1973d22545db5643cccab850c1ac693f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCOFFSecNumber (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * Symbol)</td>
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

<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Reference <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitCOFFSecOffset {#ae27d6f9cc9c43537ed435a6df1bc965c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCOFFSecOffset (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * Symbol)</td>
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

<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Reference <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitCOFFSecRel32 {#ae58362142a998a77b2da1b204aa9454f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCOFFSecRel32 (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * Symbol, uint64_t Offset)</td>
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

<p>Emits a COFF section relative relocation.</p>


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

<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### emitCOFFSectionIndex {#a137f7472e780d6adfc7ce97af2f316ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCOFFSectionIndex (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * Symbol)</td>
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

<p>Emits a COFF section index.</p>


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

<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Reference <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitCOFFSymbolIndex {#a07b9dd53ef7b4b22520cfdd39e97f59f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCOFFSymbolIndex (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * Symbol)</td>
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

<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Reference <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitCOFFSymbolStorageClass {#ad40a805686d6978c202a33d1959cdab2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCOFFSymbolStorageClass (int StorageClass)</td>
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
<td class="doxyParamItemName">StorageClass</td>
<td class="doxyParamItemDescription"><p>- The storage class the symbol should have.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Reference <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitCOFFSymbolType {#a093409e5884cbc663864a9b9babf648f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCOFFSymbolType (int Type)</td>
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
<td class="doxyParamItemName">Type</td>
<td class="doxyParamItemDescription"><p>- A COFF type identifier (see COFF::SymbolType in X86COFF.h)</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Reference <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitCommonSymbol {#a53cb03e5a5afb8080089249f461f141e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCommonSymbol (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, uint64_t Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> ByteAlignment)</td>
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

<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="#a37f26d2730c10e4c90f1b175ea4118e9">emitXCOFFRenameDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolxcoff/#a29896ac9b731b80cfb021fb432b73d7d">llvm::MCSymbolXCOFF::getSymbolTableName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolxcoff/#a37e316bff70880cf511b6790ab29ad1d">llvm::MCSymbolXCOFF::hasRename</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad82de9da62635df78a534de0f16c1129">llvm::Log2</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### emitConditionalAssignment {#a6c0673e9d30e91b31c2dbbfdae47f3f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitConditionalAssignment (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value)</td>
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

<p>Emit an assignment of <span class="doxyComputerOutput">Value</span> to <span class="doxyComputerOutput">Symbol</span>, but only if <span class="doxyComputerOutput">Value</span> is also emitted.</p>

<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a1e56c814d11206720cc23059b871128d">llvm::Value::print</a>.</p>

</div>
</div>

### emitCVDefRangeDirective {#aa49eb297857f4bf2aeec6b1d3f57b051}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCVDefRangeDirective (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt; &gt; Ranges, <a href="/web-llvm/docs/api/structs/llvm/codeview/defrangeregisterrelheader">codeview::DefRangeRegisterRelHeader</a> DRHdr)</td>
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



<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/codeview/defrangeregisterrelheader/#aa35912ee6dc477785d65b0bfa20de028">llvm::codeview::DefRangeRegisterRelHeader::BasePointerOffset</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/defrangeregisterrelheader/#a35c53d613d13b10e208764a66610caea">llvm::codeview::DefRangeRegisterRelHeader::Flags</a>, <a href="#a467384728fb302838e583379b7b23079">PrintCVDefRangePrefix</a> and <a href="/web-llvm/docs/api/structs/llvm/codeview/defrangeregisterrelheader/#a5e13ff5f78796391c35246e69a83ab79">llvm::codeview::DefRangeRegisterRelHeader::Register</a>.</p>

</div>
</div>

### emitCVDefRangeDirective {#a096a232a154a45ff185cd71961f565f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCVDefRangeDirective (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt; &gt; Ranges, <a href="/web-llvm/docs/api/structs/llvm/codeview/defrangesubfieldregisterheader">codeview::DefRangeSubfieldRegisterHeader</a> DRHdr)</td>
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



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/defrangesubfieldregisterheader/#a91323e71d4e779505960a2624d644e06">llvm::codeview::DefRangeSubfieldRegisterHeader::OffsetInParent</a>, <a href="#a467384728fb302838e583379b7b23079">PrintCVDefRangePrefix</a> and <a href="/web-llvm/docs/api/structs/llvm/codeview/defrangesubfieldregisterheader/#a8ec4f0468be2b9fd2f3951853e283402">llvm::codeview::DefRangeSubfieldRegisterHeader::Register</a>.</p>

</div>
</div>

### emitCVDefRangeDirective {#a534087ca10707b8e963d0093d687136e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCVDefRangeDirective (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt; &gt; Ranges, <a href="/web-llvm/docs/api/structs/llvm/codeview/defrangeregisterheader">codeview::DefRangeRegisterHeader</a> DRHdr)</td>
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



<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="#a467384728fb302838e583379b7b23079">PrintCVDefRangePrefix</a> and <a href="/web-llvm/docs/api/structs/llvm/codeview/defrangeregisterheader/#a104d5325c4fd1b5af890bde1d9401a97">llvm::codeview::DefRangeRegisterHeader::Register</a>.</p>

</div>
</div>

### emitCVDefRangeDirective {#a3f2246f74c434ed53299fdf711b1f9a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCVDefRangeDirective (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt; &gt; Ranges, <a href="/web-llvm/docs/api/structs/llvm/codeview/defrangeframepointerrelheader">codeview::DefRangeFramePointerRelHeader</a> DRHdr)</td>
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



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/defrangeframepointerrelheader/#a18ec6b7155d33dedeb3105e572c81b34">llvm::codeview::DefRangeFramePointerRelHeader::Offset</a> and <a href="#a467384728fb302838e583379b7b23079">PrintCVDefRangePrefix</a>.</p>

</div>
</div>

### emitCVFileChecksumOffsetDirective {#a316200def17e7bb5db6b91900313a262}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCVFileChecksumOffsetDirective (unsigned FileNo)</td>
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

<p>This implements the CodeView '.cv_filechecksumoffset' assembler directive.</p>

<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Reference <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitCVFileChecksumsDirective {#a3a6083e6ee9f56004ccbee4b83ccf764}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCVFileChecksumsDirective ()</td>
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

<p>This implements the CodeView '.cv_filechecksums' assembler directive.</p>

<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Reference <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitCVFileDirective {#a11b1131686b3d58fdda416597ca504f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAsmStreamer::emitCVFileDirective (unsigned FileNo, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Checksum, unsigned ChecksumKind)</td>
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


<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abec19670f96ed423c2e4d4f10a4c6975">llvm::toHex</a>.</p>

</div>
</div>

### emitCVFPOData {#af1fd3e492100e8cc074e33590fc9e951}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCVFPOData (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * ProcSym, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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

<p>This implements the CodeView '.cv_fpo_data' assembler directive.</p>

<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a27f7a23e572edb7b1bc46d9639c3204a">llvm::MCSymbol::print</a>.</p>

</div>
</div>

### emitCVFuncIdDirective {#a6177856d4e399300f3940086c56425cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAsmStreamer::emitCVFuncIdDirective (unsigned FunctionId)</td>
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

<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a13ac5fe9bbe382dd5e366288ba91fa43">llvm::MCStreamer::emitCVFuncIdDirective</a>.</p>

</div>
</div>

### emitCVInlineLinetableDirective {#aa96077a0e4bce1c56fb5c2660e5752df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCVInlineLinetableDirective (unsigned PrimaryFunctionId, unsigned SourceFileId, unsigned SourceLineNum, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * FnStartSym, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * FnEndSym)</td>
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

<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#af64e1dd74b4eb933d72d30513e283c6f">llvm::MCStreamer::emitCVInlineLinetableDirective</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a27f7a23e572edb7b1bc46d9639c3204a">llvm::MCSymbol::print</a>.</p>

</div>
</div>

### emitCVInlineSiteIdDirective {#a6c677e18b455acc6e512bae0216093d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAsmStreamer::emitCVInlineSiteIdDirective (unsigned FunctionId, unsigned IAFunc, unsigned IAFile, unsigned IALine, unsigned IACol, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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


<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#aea7cedf9c3df1534425168ee9969871c">llvm::MCStreamer::emitCVInlineSiteIdDirective</a>.</p>

</div>
</div>

### emitCVLinetableDirective {#a238e59e2af8906f2cfc5155663d7a196}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCVLinetableDirective (unsigned FunctionId, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * FnStart, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * FnEnd)</td>
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

<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a8afbb0726c0e3513324fc6bf0c8100a1">llvm::MCStreamer::emitCVLinetableDirective</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a27f7a23e572edb7b1bc46d9639c3204a">llvm::MCSymbol::print</a>.</p>

</div>
</div>

### emitCVLocDirective {#ad0de5f7018dd4bdee0616920178ee0bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCVLocDirective (unsigned FunctionId, unsigned FileNo, unsigned Line, unsigned Column, bool PrologueEnd, bool IsStmt, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileName, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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

<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a79e4fddfcfc0d5ed30a1b811fcd17a6e">llvm::MCStreamer::checkCVLocSection</a> and <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitCVStringTableDirective {#afa1fac5c5ed19d64e3e6b8f69984f21c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitCVStringTableDirective ()</td>
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

<p>This implements the CodeView '.cv_stringtable' assembler directive.</p>

<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Reference <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitDarwinTargetVariantBuildVersion {#a4ed0f07369e726c4b4bacacd90e6370e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitDarwinTargetVariantBuildVersion (unsigned Platform, unsigned Major, unsigned Minor, unsigned Update, <a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a> SDKVersion)</td>
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



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Reference <a href="#a73d1f3201777b81d5a80bd6da19e7bee">emitBuildVersion</a>.</p>

</div>
</div>

### emitDataRegion {#ae857977308ca4e1d0cf0311bd3f60004}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitDataRegion (<a href="/web-llvm/docs/api/namespaces/llvm/#a515cb4eba75abc2f0e9dbfffb0137008">MCDataRegionType</a> Kind)</td>
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

<p>Note in the output the specified region <span class="doxyComputerOutput">Kind</span>.</p>

<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a515cb4eba75abc2f0e9dbfffb0137008a05d6258eaccbe86ca4c18e36910fda79">llvm::MCDR_DataRegion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a515cb4eba75abc2f0e9dbfffb0137008a0178c9475f859cfd8a0f552b8e22f412">llvm::MCDR_DataRegionEnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a515cb4eba75abc2f0e9dbfffb0137008adc2335b540bd652d82bf3bcbed5a87d4">llvm::MCDR_DataRegionJT16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a515cb4eba75abc2f0e9dbfffb0137008ac0586422896e4472fa7aa7118d9a4ecb">llvm::MCDR_DataRegionJT32</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a515cb4eba75abc2f0e9dbfffb0137008a1183f27779c00ba04ce7aec4344952d2">llvm::MCDR_DataRegionJT8</a>.</p>

</div>
</div>

### emitDTPRel32Value {#a2ec882a8aecc1b17265d0bebffa5cb1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitDTPRel32Value (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value)</td>
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

<p>Emit the expression <span class="doxyComputerOutput">Value</span> into the output as a dtprel (32-bit DTP relative) value.</p>


<p>This is used to implement assembler directives such as .dtprelword on targets that support them.</p>


<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a1e56c814d11206720cc23059b871128d">llvm::Value::print</a>.</p>

</div>
</div>

### emitDTPRel64Value {#afb95b400bf91f96c149f206e45dc0d09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitDTPRel64Value (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value)</td>
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

<p>Emit the expression <span class="doxyComputerOutput">Value</span> into the output as a dtprel (64-bit DTP relative) value.</p>


<p>This is used to implement assembler directives such as .dtpreldword on targets that support them.</p>


<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a1e56c814d11206720cc23059b871128d">llvm::Value::print</a>.</p>

</div>
</div>

### emitDwarfAdvanceLineAddr {#a79809d23367b5aafd98b71ae67a0d2d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitDwarfAdvanceLineAddr (int64_t LineDelta, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * LastLabel, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Label, unsigned PointerSize)</td>
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

<p>If targets does not support representing debug line section by .loc/.file directives in assembly output, we need to populate debug line section with raw debug line contents.</p>

<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a6d10fbe43b4e2dc5ddde4dacc0429b84">AddComment</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflineaddr/#a002e20f504cfcef55b84c4c7e5b2be68">llvm::MCDwarfLineAddr::Emit</a>, <a href="#a11156cb1f872cbe35d40c6f36a21d56f">emitIntValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ae9c7bfbd6f1a6b08ebabb1ca16be3d7e">llvm::MCStreamer::emitSLEB128IntValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7865bd61cd2c65b2d94c58dd1523bb75">llvm::MCStreamer::emitSymbolValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#abc5f738b9471c3ed31b8f1fc7dc8e914">llvm::MCStreamer::emitULEB128IntValue</a> and <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#ad0d744f05898e32d01f73f8af3cd2071">INT64_MAX</a>.</p>


<p>Referenced by <a href="#aa72d5840fe6b92c329861c90b8a7c58c">emitDwarfLineEndEntry</a>.</p>

</div>
</div>

### emitDwarfFile0Directive {#afa88bfe9ae2423322c5a88908de8ba22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitDwarfFile0Directive (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directory, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/md5/md5result">MD5::MD5Result</a> &gt; Checksum, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; Source, unsigned CUID=0)</td>
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

<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ae5807cb4b1f712252faa7d31f9d19815">llvm::MCStreamer::emitRawText</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a901607e60c20148ae701b6e8f43b4647">llvm::MCStreamer::getTargetStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream/#a9c2cac84e46d3e744aeca03dd3d557d1">llvm::raw_svector_ostream::str</a>.</p>

</div>
</div>

### emitDwarfLineEndEntry {#aa72d5840fe6b92c329861c90b8a7c58c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitDwarfLineEndEntry (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Section, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * LastLabel, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * EndLabel=nullptr)</td>
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

<p>Emit the debug line end entry.</p>

<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a79809d23367b5aafd98b71ae67a0d2d4">emitDwarfAdvanceLineAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#affd5fd4fc8ca1b0f483c51543e58108d">llvm::MCAsmInfo::getCodePointerSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a2e761f9cd5b9c1a95d3201f171d40d8c">llvm::MCSection::getEndSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#ab0bf80f50c3a1ef6cb8351dae8824355">llvm::MCSection::hasEnded</a> and <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#ad0d744f05898e32d01f73f8af3cd2071">INT64_MAX</a>.</p>

</div>
</div>

### emitDwarfLineStartLabel {#abc85cf8fcb99aada0bb615989928b516}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitDwarfLineStartLabel (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * StartSym)</td>
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

<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#af766134165065939f49fb0662c246f66">llvm::MCBinaryExpr::createSub</a>, <a href="#af1d5c7867737745f90d074f16eb1c485">emitAssignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7f1677ad2db297b0202a720530693157">llvm::MCStreamer::emitDwarfLineStartLabel</a>, <a href="#a99306d453eed689739055115d79beeca">emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a0b741aef91502fa04c0f5265a58ba45c">llvm::dwarf::getUnitLengthFieldByteSize</a>.</p>

</div>
</div>

### emitDwarfLocDirective {#afbf8b87c2743700b4bc2f187d06c9a28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitDwarfLocDirective (unsigned FileNo, unsigned Line, unsigned Column, unsigned Flags, unsigned Isa, unsigned Discriminator, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileName)</td>
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

<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h/#a74d34cc02788b4d55fcbdd15b3e0f223">DWARF2_FLAG_BASIC_BLOCK</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h/#aefa88a895bd349d0750ded8be4a29dda">DWARF2_FLAG_EPILOGUE_BEGIN</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h/#a377ba69923635f8154cad5784be89ff6">DWARF2_FLAG_IS_STMT</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h/#ac0c23e2e79a5713602b44382a3ecc960">DWARF2_FLAG_PROLOGUE_END</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a43c1c961a6b54da9fccacdf1cf5fc38f">llvm::MCStreamer::emitDwarfLocDirective</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ae1b3cf074436ef5b527071540e13bd58">llvm::MCStreamer::getCurrentSectionOnly</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdwarflineentry/#a7e7c37719e68c7bf9e494110a30cad90">llvm::MCDwarfLineEntry::make</a>.</p>

</div>
</div>

### emitDwarfLocLabelDirective {#a97a8d7833400582f801ce932f7b59261}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitDwarfLocLabelDirective (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a29df2eab11142e7ff1e8ee74b0cb6322">llvm::MCStreamer::emitDwarfLocLabelDirective</a> and <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitDwarfUnitLength {#a8f4b96f764a5ad6bcb7a3e0c0e4ee339}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitDwarfUnitLength (uint64_t Length, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Comment)</td>
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


<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a392206962fc4ac790aede10497c7e10b">llvm::MCStreamer::emitDwarfUnitLength</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>.</p>

</div>
</div>

### emitDwarfUnitLength {#aa5d953a682bfa6d424f05dca8d56b9ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MCAsmStreamer::emitDwarfUnitLength (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Prefix, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Comment)</td>
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


<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a392206962fc4ac790aede10497c7e10b">llvm::MCStreamer::emitDwarfUnitLength</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>.</p>

</div>
</div>

### emitELFSize {#a3b406af868aa746d08c62b38d8c259f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitELFSize (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value)</td>
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

<p>Emit an ELF .size directive.</p>


<p>This corresponds to an assembler statement such as: .size symbol, expression</p>


<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a1e56c814d11206720cc23059b871128d">llvm::Value::print</a>.</p>

</div>
</div>

### emitELFSymverDirective {#ab3cd968a6ba01a35c097a702ea02fb4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitELFSymverDirective (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * OriginalSym, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool KeepOriginalSym)</td>
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

<p>Emit an ELF .symver directive.</p>


<p>This corresponds to an assembler statement such as: .symver _start, foo@SOME_VERSION</p>


<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a27f7a23e572edb7b1bc46d9639c3204a">llvm::MCSymbol::print</a>.</p>

</div>
</div>

### emitFileDirective {#a9bad68e4b10776e708626a8c6b25c965}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitFileDirective (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename)</td>
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


<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitFileDirective {#a20a4c6ed55ed94fa363e630573918107}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitFileDirective (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CompilerVersion, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TimeStamp, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Description)</td>
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

<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>.</p>

</div>
</div>

### emitFill {#aae6d9fb29c7a596c66c84d2ccb0457dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitFill (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> &amp; NumBytes, uint64_t FillValue, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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
<td class="doxyParamItemName">Loc</td>
<td class="doxyParamItemDescription"><p>- The location of the expression for error reporting.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#af6a6f6142b6fd138cdc9e08217577c4d">llvm::MCStreamer::emitFill</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae3067756d9df7843be2d25cedab37da4">llvm::MCExpr::print</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### emitFill {#a664095c8afe2051a5e22b25100685b01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitFill (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> &amp; NumValues, int64_t Size, int64_t Expr, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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

<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae3067756d9df7843be2d25cedab37da4">llvm::MCExpr::print</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp/#a9a1994cc203b2699119e91b908b9d50b">truncateToSize</a>.</p>

</div>
</div>

### emitGNUAttribute {#a49aba7bece7f857a6c983f133890adcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitGNUAttribute (unsigned Tag, unsigned Value)</td>
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

<p>Emit a .gnu_attribute directive.</p>

<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>

</div>
</div>

### emitGPRel32Value {#ac08027460665b9a74ec5770fc3c69105}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitGPRel32Value (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value)</td>
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

<p>Emit the expression <span class="doxyComputerOutput">Value</span> into the output as a gprel32 (32-bit GP relative) value.</p>


<p>This is used to implement assembler directives such as .gprel32 on targets that support them.</p>


<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a1e56c814d11206720cc23059b871128d">llvm::Value::print</a>.</p>

</div>
</div>

### emitGPRel64Value {#aa557364f7fbf9210e7937d72e1eaa1e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitGPRel64Value (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value)</td>
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

<p>Emit the expression <span class="doxyComputerOutput">Value</span> into the output as a gprel64 (64-bit GP relative) value.</p>


<p>This is used to implement assembler directives such as .gpdword on targets that support them.</p>


<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a1e56c814d11206720cc23059b871128d">llvm::Value::print</a>.</p>

</div>
</div>

### emitIdent {#ad0a11a27e8bdbf6749d8e7d20fd380f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitIdent (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> IdentString)</td>
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


<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitInstruction {#a161ac460fefc16f98a8dd1a9f019af9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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

<p>Emit the given <span class="doxyComputerOutput">Instruction</span> into the current section.</p>

<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#acf7b75691e086935319e3142cb2eb579">AddEncodingComment</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5b6faabb08339ea1dd11e9d37a668634">llvm::StringRef::back</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9299fd6e2b7f540daa945aae967ffe47">llvm::MCStreamer::CurFrag</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a230d5dad7ea2d94e1671a4aa222a2e15">llvm::MCInst::dump_pretty</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="#a2f76a99d4a915c6b36833085bee383c2">getCommentOS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ae1b3cf074436ef5b527071540e13bd58">llvm::MCStreamer::getCurrentSectionOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a901607e60c20148ae701b6e8f43b4647">llvm::MCStreamer::getTargetStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflineentry/#a7e7c37719e68c7bf9e494110a30cad90">llvm::MCDwarfLineEntry::make</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>

</div>
</div>

### emitIntValue {#a11156cb1f872cbe35d40c6f36a21d56f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitIntValue (uint64_t Value, unsigned Size)</td>
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

<p>Special case of EmitValue that avoids the client having to pass in a MCExpr for constant integers.</p>


<p>EmitIntValue - Special case of EmitValue that avoids the client having to pass in a <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> for constant integers.</p>


<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7833630c617e5943c0a41755f5d4bdcf">llvm::MCStreamer::emitValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a79809d23367b5aafd98b71ae67a0d2d4">emitDwarfAdvanceLineAddr</a> and <a href="#ae37bcdd18e5b8eb58b8d88effad3fed8">emitValueImpl</a>.</p>

</div>
</div>

### emitIntValueInHex {#a02ddab75d51b8f46e8e2327dbb0e367b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitIntValueInHex (uint64_t Value, unsigned Size)</td>
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

<p>Special case of EmitValue that avoids the client having to pass in a MCExpr for constant integers &amp; prints in Hex format for certain modes.</p>

<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7833630c617e5943c0a41755f5d4bdcf">llvm::MCStreamer::emitValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### emitIntValueInHexWithPadding {#a9e376ffce522c2c85b62c86d18867336}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitIntValueInHexWithPadding (uint64_t Value, unsigned Size)</td>
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

<p>Special case of EmitValue that avoids the client having to pass in a MCExpr for constant integers &amp; prints in Hex format for certain modes, pads the field with leading zeros to Size width.</p>

<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7833630c617e5943c0a41755f5d4bdcf">llvm::MCStreamer::emitValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### emitLabel {#a99306d453eed689739055115d79beeca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitLabel (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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

<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a822ae1a4f19b7b00a297a100749f9b8a">llvm::MCStreamer::emitLabel</a>.</p>


<p>Referenced by <a href="#abc85cf8fcb99aada0bb615989928b516">emitDwarfLineStartLabel</a> and <a href="#a5333321f84976a4bf06be40827ca62d8">finishImpl</a>.</p>

</div>
</div>

### emitLinkerOptions {#a8a393824072c5571972394a72ee86cf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitLinkerOptions (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::string &gt; Kind)</td>
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

<p>Emit the given list <span class="doxyComputerOutput">Options</span> of strings as linker options into the output.</p>

<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>.</p>

</div>
</div>

### emitLocalCommonSymbol {#aa905c95a461602c484dfdf155114f4c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitLocalCommonSymbol (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, uint64_t Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> ByteAlignment)</td>
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

<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/lcomm/#aae933cd10a930a5312da96502035e331a310fe8dc05086ce23b6826ccb3c37fc7">llvm::LCOMM::ByteAlignment</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad82de9da62635df78a534de0f16c1129">llvm::Log2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lcomm/#aae933cd10a930a5312da96502035e331adce83244e971c1aeafe5840c91d9be0b">llvm::LCOMM::Log2Alignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lcomm/#aae933cd10a930a5312da96502035e331a3062e0ef4c841d66420bf37c2d8fc750">llvm::LCOMM::NoAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>

</div>
</div>

### emitLOHDirective {#ab5dd9aa863646f04e05baf2e8ace9406}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitLOHDirective (<a href="/web-llvm/docs/api/namespaces/llvm/#aadff17100a7bcc6ddd2940e098ddbcf5">MCLOHType</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a62129b64f06d9bc8df1c60845451432b">MCLOHArgs</a> &amp; Args)</td>
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

<p>Emit a Linker Optimization Hint (LOH) directive.</p>


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

<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a38f8d9d12cac93b09a12fb52e853be36">llvm::MCLOHDirectiveName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af90e1137e9c33b46b70c9f0a9f0d449d">llvm::MCLOHIdToName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9f40535ab9cd43a0522f67e16c71ffb9">llvm::MCLOHIdToNbArgs</a>.</p>

</div>
</div>

### emitPseudoProbe {#a9b50dd93932455982bef5aaf44afd0aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitPseudoProbe (uint64_t Guid, uint64_t Index, uint64_t Type, uint64_t Attr, uint64_t Discriminator, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a79515c0650a49e9a7ae8ed6e228b8816">MCPseudoProbeInlineStack</a> &amp; InlineStack, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * FnSym)</td>
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

<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a57c7b2b9784361914262eeb0a6f0b18d">llvm::MCSymbol::getName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af59335be18fa802d111a646be658b7d0acb957607a78494ea70db887d1463437c">llvm::Guid</a>.</p>

</div>
</div>

### emitRawTextImpl {#a9c9b3bbd630571b3a00b01b38742e79c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitRawTextImpl (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> String)</td>
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

<p>If this file is backed by an assembly streamer, this dumps the specified string in the output .s file.</p>


<p>EmitRawText - If this file is backed by an assembly streamer, this dumps the specified string in the output .s file.</p>


<p>This capability is indicated by the <a href="#aa892ddf5fe83cb36e0c714bc4af7e42d">hasRawTextSupport()</a> predicate.</p>


<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a>.</p>

</div>
</div>

### emitRelocDirective {#a34bd9da2c0260776c7eb80aef5229322}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::pair&lt; bool, std::string &gt; &gt; MCAsmStreamer::emitRelocDirective (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> &amp; Offset, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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

<p>Record a relocation described by the .reloc directive.</p>


<p>Return std::nullopt if succeeded. Otherwise, return a pair (Name is invalid, error message).</p>


<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae3067756d9df7843be2d25cedab37da4">llvm::MCExpr::print</a>.</p>

</div>
</div>

### emitSLEB128Value {#a398cbd8a4b88d125a501b3f6b5932588}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitSLEB128Value (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value)</td>
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



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ae9c7bfbd6f1a6b08ebabb1ca16be3d7e">llvm::MCStreamer::emitSLEB128IntValue</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a1e56c814d11206720cc23059b871128d">llvm::Value::print</a>.</p>

</div>
</div>

### emitSymbolAttribute {#ae2ddc96d94abf0d970032254268e8de1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAsmStreamer::emitSymbolAttribute (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243">MCSymbolAttr</a> Attribute)</td>
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

<p>Add the given <span class="doxyComputerOutput">Attribute</span> to <span class="doxyComputerOutput">Symbol</span>.</p>

<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a452eae0b6838f1340eb75102bdfabd47">llvm::MCSA_AltEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243ab79bc663bb12acbf83bd10cdcfdd037e">llvm::MCSA_Cold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a9edfe2cb31eba126ff7c30b999c56646">llvm::MCSA_ELF_TypeCommon</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243ad0efc318f7416b800a38c5cc42ddbfa9">llvm::MCSA_ELF_TypeFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243ad07ba742431c4f5e789624beae77683a">llvm::MCSA_ELF_TypeGnuUniqueObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a5d62f59d328d117d64c99526e77c68df">llvm::MCSA_ELF_TypeIndFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a7eadfaef3a6cc05735b52d92ff0540e9">llvm::MCSA_ELF_TypeNoType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243acf016837e7bf7ff2387b46d789c1f5d4">llvm::MCSA_ELF_TypeObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a86783fdbba192be49198856191150827">llvm::MCSA_ELF_TypeTLS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a345961d937ffac378faab680906913d6">llvm::MCSA_Exported</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243ab11aa8a54bc3faf1ef7db38e4bf4fb60">llvm::MCSA_Extern</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243aa1e94c23156e37812e4d6e078af1d728">llvm::MCSA_Global</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243ae472359b991bb5235c8f6714f4cacb6a">llvm::MCSA_Hidden</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a9c4d91f21dab6846f0eb7cdd8608c16a">llvm::MCSA_IndirectSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a3b2ee46211db7e561d0b732b5ae4fe5e">llvm::MCSA_Internal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243af3367f8319e21bf0779da14146221c55">llvm::MCSA_Invalid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a6f8590ba0f71b1b8b0e937695e303208">llvm::MCSA_LazyReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243ae5c5c7dd59c0c23f91be2b9c8f2594c9">llvm::MCSA_LGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a02f22ce66e6bacb5fbaba644ec799653">llvm::MCSA_Local</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a17067e9f600d7ededa1cd3a6f236d5a7">llvm::MCSA_Memtag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243afb34d5700d536c3f8f8a5004985d1f57">llvm::MCSA_NoDeadStrip</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a39ad38d82f889bf4c82e539beb859d05">llvm::MCSA_PrivateExtern</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a1f47433b83f2818076a3cf55b500233a">llvm::MCSA_Protected</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a80891606fbdc946b4085496f58aafd62">llvm::MCSA_Reference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a83196df34bcdda178fae802a4a06a6dc">llvm::MCSA_SymbolResolver</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a83df6138e7dba38c0c80380486544ea0">llvm::MCSA_Weak</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243aa96e85228ec0460e2b923801660b33f9">llvm::MCSA_WeakAntiDep</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a0506d51c6914f1b55fec60c97d4d8cc9">llvm::MCSA_WeakDefAutoPrivate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a9cd0febd9a535eb96c33815707bab481">llvm::MCSA_WeakDefinition</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a42ec27e2fd185b27d0fbf1aaf0bfd214">llvm::MCSA_WeakReference</a>.</p>

</div>
</div>

### emitSymbolDesc {#a1c803c21220f5051c6e06a0a09c35017}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitSymbolDesc (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, unsigned DescValue)</td>
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

<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Reference <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitTBSSSymbol {#afb1b0b113e4532d3f1e83b665f9c1906}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitTBSSSymbol (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Section, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, uint64_t Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> ByteAlignment=<a href="/web-llvm/docs/api/structs/llvm/align">Align</a>(1))</td>
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

<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad82de9da62635df78a534de0f16c1129">llvm::Log2</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsection/#afecf7c84b079ea5c169f71b6c06ece98a55ed9b1dac938f496436528db3576783">llvm::MCSection::SV_MachO</a>.</p>

</div>
</div>

### emitThumbFunc {#abf1e3a2cb44fc1a7742edfbea3d9d6ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitThumbFunc (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Func)</td>
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

<p>Note in the output that the specified <span class="doxyComputerOutput">Func</span> is a Thumb mode function (ARM target only).</p>

<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Reference <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitTPRel32Value {#a4884277cc2c31ed03c037671a632d8ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitTPRel32Value (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value)</td>
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

<p>Emit the expression <span class="doxyComputerOutput">Value</span> into the output as a tprel (32-bit TP relative) value.</p>


<p>This is used to implement assembler directives such as .tprelword on targets that support them.</p>


<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a1e56c814d11206720cc23059b871128d">llvm::Value::print</a>.</p>

</div>
</div>

### emitTPRel64Value {#a5ba5fdec68cf4b56fb2ec57f42753267}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitTPRel64Value (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value)</td>
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

<p>Emit the expression <span class="doxyComputerOutput">Value</span> into the output as a tprel (64-bit TP relative) value.</p>


<p>This is used to implement assembler directives such as .tpreldword on targets that support them.</p>


<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a1e56c814d11206720cc23059b871128d">llvm::Value::print</a>.</p>

</div>
</div>

### emitULEB128Value {#a2f652a1af8c13dd04aa1b2ba2cfd80d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitULEB128Value (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value)</td>
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



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#abc5f738b9471c3ed31b8f1fc7dc8e914">llvm::MCStreamer::emitULEB128IntValue</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a1e56c814d11206720cc23059b871128d">llvm::Value::print</a>.</p>

</div>
</div>

### emitValueImpl {#ae37bcdd18e5b8eb58b8d88effad3fed8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitValueImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value, unsigned Size, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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

<p>Emit the expression <span class="doxyComputerOutput">Value</span> into the output as a native integer of the given <span class="doxyComputerOutput">Size</span> bytes.</p>


<p>This is used to implement assembler directives such as .word, .quad, etc.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Value</td>
<td class="doxyParamItemDescription"><p>- The value to emit.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>- The size of the integer (in bytes) to emit. This must match a native machine width.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Loc</td>
<td class="doxyParamItemDescription"><p>- The location of the expression for error reporting.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae22967d11b695d268992470debfae4b2">llvm::bit_floor</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="#a11156cb1f872cbe35d40c6f36a21d56f">emitIntValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ae1b3cf074436ef5b527071540e13bd58">llvm::MCStreamer::getCurrentSectionOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a901607e60c20148ae701b6e8f43b4647">llvm::MCStreamer::getTargetStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a1e56c814d11206720cc23059b871128d">llvm::Value::print</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### emitValueToAlignment {#acd79313d43de902e2f2f8d2c0189215c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitValueToAlignment (<a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, int64_t Value=0, unsigned ValueSize=1, unsigned MaxBytesToEmit=0)</td>
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

<p>Emit some number of copies of <span class="doxyComputerOutput">Value</span> until the byte alignment <span class="doxyComputerOutput">ByteAlignment</span> is reached.</p>


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
<td class="doxyParamItemName">Value</td>
<td class="doxyParamItemDescription"><p>- The value to use when filling bytes.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ValueSize</td>
<td class="doxyParamItemDescription"><p>- The size of the integer (in bytes) to emit for <span class="doxyComputerOutput">Value</span>. This must match a native machine width.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MaxBytesToEmit</td>
<td class="doxyParamItemDescription"><p>- The maximum numbers of bytes to emit, or 0. If the alignment cannot be reached in this many bytes, no bytes are emitted.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a36690cdc5f927e7553ec268a036a722f">emitAlignmentDirective</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>

</div>
</div>

### emitValueToOffset {#ae043f2028a3e9aaf8e8aacd77c059dc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitValueToOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Offset, unsigned char Value, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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

<p>Emit some number of copies of <span class="doxyComputerOutput">Value</span> until the byte offset <span class="doxyComputerOutput">Offset</span> is reached.</p>


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
<td class="doxyParamItemName">Value</td>
<td class="doxyParamItemDescription"><p>- The value to use when filling bytes.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### emitVersionMin {#a422f5621940beb2e051d9468d4f70922}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitVersionMin (<a href="/web-llvm/docs/api/namespaces/llvm/#a7b22b2a20e7587321d17cb029ea8626e">MCVersionMinType</a> Type, unsigned Major, unsigned Minor, unsigned Update, <a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a> SDKVersion)</td>
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

<p>Specify the Mach-O minimum deployment target version.</p>

<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp/#a96037fc0434f2d1c064f7748b41f8c1d">EmitSDKVersionSuffix</a> and <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp/#a217b69ba8c630b233ead7f3a622aa3e3">getVersionMinDirective</a>.</p>

</div>
</div>

### emitWeakReference {#a4d9da6fd250447386af90f45a41bb8a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitWeakReference (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Alias, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol)</td>
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

<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a27f7a23e572edb7b1bc46d9639c3204a">llvm::MCSymbol::print</a>.</p>

</div>
</div>

### emitWinCFIAllocStack {#aecf41e0f616b168c70d4d7e1c5b12b19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitWinCFIAllocStack (unsigned Size, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ad9bb2bc90c804c28497604ae91e27bd7">llvm::MCStreamer::emitWinCFIAllocStack</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### emitWinCFIEndChained {#a4606f6d1acb29e734341e0bc78655356}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitWinCFIEndChained (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9b6d232a4258f0dd9f16ee5b4f558633">llvm::MCStreamer::emitWinCFIEndChained</a>.</p>

</div>
</div>

### emitWinCFIEndProc {#a0fd5e1b1e4d675662b464bbf587e8054}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitWinCFIEndProc (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9d158c6b4a4302d51fd73aac4075086d">llvm::MCStreamer::emitWinCFIEndProc</a>.</p>

</div>
</div>

### emitWinCFIEndProlog {#a0ec5db274b0af678a8e45ccf25b89690}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitWinCFIEndProlog (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9b9f4aa69270161dc91d76e3080e6dd2">llvm::MCStreamer::emitWinCFIEndProlog</a>.</p>

</div>
</div>

### emitWinCFIFuncletOrFuncEnd {#af9a5dce582cf654f096cdad605ea38ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitWinCFIFuncletOrFuncEnd (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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


<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#aac38128831e5c5377b98fd32d4f53fc9">llvm::MCStreamer::emitWinCFIFuncletOrFuncEnd</a>.</p>

</div>
</div>

### emitWinCFIPushFrame {#af38a4d16a207c3672f2e06d2f8897915}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitWinCFIPushFrame (bool Code, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a4c579bc3d70f8f348c3ddf8224a31220">llvm::MCStreamer::emitWinCFIPushFrame</a>.</p>

</div>
</div>

### emitWinCFIPushReg {#a8c2773f2fd46f185d617c084afa98ab6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitWinCFIPushReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Register, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a1d0c21ad8ad54697f00aab2c37d77e25">llvm::MCStreamer::emitWinCFIPushReg</a>.</p>

</div>
</div>

### emitWinCFISaveReg {#a1dfc20c93c509c1d196cdf0e8e66acae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitWinCFISaveReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Register, unsigned Offset, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9a30cc0783819b780c3e357162b90aec">llvm::MCStreamer::emitWinCFISaveReg</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### emitWinCFISaveXMM {#af831d087fdf1bd0af05bb382182593f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitWinCFISaveXMM (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Register, unsigned Offset, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a5755faab671780e6c1abcaa95f05fe0b">llvm::MCStreamer::emitWinCFISaveXMM</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### emitWinCFISetFrame {#a99577354457a83f041f80baf798d507e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitWinCFISetFrame (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Register, unsigned Offset, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#acd1f092159870d525f916e3296341d92">llvm::MCStreamer::emitWinCFISetFrame</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### emitWinCFIStartChained {#a2ce02f7cd680caa9cdc9d19decbec097}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitWinCFIStartChained (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#af4abf3b216995cecfbe8fcbc05d5b128">llvm::MCStreamer::emitWinCFIStartChained</a>.</p>

</div>
</div>

### emitWinCFIStartProc {#a1f68951e04ae06a7a386f17a3a7d1cb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitWinCFIStartProc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7787897c604e14c9e152c890e019e3bf">llvm::MCStreamer::emitWinCFIStartProc</a>.</p>

</div>
</div>

### emitWinEHHandler {#adb765c6ee407ec7777308406d9fbcf30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitWinEHHandler (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym, bool Unwind, bool Except, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a8b312a985e2504366d24a2200faf37ff">llvm::Triple::arm</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a26b51b14a3b7ce5cd6abe0c45872dd60">llvm::MCStreamer::emitWinEHHandler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a27f7a23e572edb7b1bc46d9639c3204a">llvm::MCSymbol::print</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ab456eadbc2378864e9aa9e2a545a1e65">llvm::Triple::thumb</a>.</p>

</div>
</div>

### emitWinEHHandlerData {#a27ab1f18a7bff8a82c03e03302227f0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitWinEHHandlerData (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a4e42517f705e57c03ce078fcac4e8f19">llvm::MCStreamer::emitWinEHHandlerData</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/#a22c0c4f7c23db94945872dfe14fa32bc">llvm::WinEH::FrameInfo::Function</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7304c7ee4dda7ad7b71afed08c070cd8">llvm::MCStreamer::getAssociatedXDataSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#af2c1682a7f094bf9534d3461286aa62f">llvm::MCStreamer::getCurrentWinFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#ab7d669d1338ce8b4ddf910da10c51607">llvm::MCSymbol::getSection</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a05b1a7fa3b559a330d9830ec956a8383">llvm::MCStreamer::switchSectionNoPrint</a>.</p>

</div>
</div>

### emitXCOFFCInfoSym {#a5b923ddd75e27a332230dc648f4443f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitXCOFFCInfoSym (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Metadata)</td>
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

<p>Emit a C_INFO symbol with XCOFF embedded metadata to the .info section.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>- The embedded metadata name</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Metadata</td>
<td class="doxyParamItemDescription"><p>- The embedded metadata</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90c017a4d672e046b7e98f67edf082ec">llvm::format_hex</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a7a225814d4cc0d175373f7ffc59f66b4">llvm::support::endian::read32be</a>.</p>

</div>
</div>

### emitXCOFFExceptDirective {#a2976594c904759e6ea0d3ded1b113059}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitXCOFFExceptDirective (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Trap, unsigned Lang, unsigned Reason, unsigned FunctionSize, bool hasDebug)</td>
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

<p>Emit an XCOFF .except directive which adds information about a trap instruction to the object file exception section.</p>


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

<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp/#a434449d5a0f4b334aca9163b13b6286ba178e499decd0c21272bc34e4b3056eab">Trap</a>.</p>

</div>
</div>

### emitXCOFFLocalCommonSymbol {#a2d3b4a12c2fbc688388c6c2b422f8e88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitXCOFFLocalCommonSymbol (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * LabelSym, uint64_t Size, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * CsectSym, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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

<p>Emits an lcomm directive with XCOFF csect information.</p>


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

<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="#a37f26d2730c10e4c90f1b175ea4118e9">emitXCOFFRenameDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolxcoff/#a29896ac9b731b80cfb021fb432b73d7d">llvm::MCSymbolXCOFF::getSymbolTableName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolxcoff/#a37e316bff70880cf511b6790ab29ad1d">llvm::MCSymbolXCOFF::hasRename</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad82de9da62635df78a534de0f16c1129">llvm::Log2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lcomm/#aae933cd10a930a5312da96502035e331adce83244e971c1aeafe5840c91d9be0b">llvm::LCOMM::Log2Alignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a27f7a23e572edb7b1bc46d9639c3204a">llvm::MCSymbol::print</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### emitXCOFFRefDirective {#a02c8de429d8ab8ead0705b3b548a86e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitXCOFFRefDirective (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol)</td>
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

<p>Emit a XCOFF .ref directive which creates R_REF type entry in the relocation table for one or more symbols.</p>


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

<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Reference <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### emitXCOFFRenameDirective {#a37f26d2730c10e4c90f1b175ea4118e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitXCOFFRenameDirective (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Rename)</td>
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

<p>Emit a XCOFF .rename directive which creates a synonym for an illegal or undesirable name.</p>


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

<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>


<p>Referenced by <a href="#a53cb03e5a5afb8080089249f461f141e">emitCommonSymbol</a>, <a href="#a2d3b4a12c2fbc688388c6c2b422f8e88">emitXCOFFLocalCommonSymbol</a> and <a href="#aaf2edddac64334f7baaa80739f8f2df7">emitXCOFFSymbolLinkageWithVisibility</a>.</p>

</div>
</div>

### emitXCOFFSymbolLinkageWithVisibility {#aaf2edddac64334f7baaa80739f8f2df7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitXCOFFSymbolLinkageWithVisibility (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243">MCSymbolAttr</a> Linkage, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243">MCSymbolAttr</a> Visibility)</td>
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

<p>Emit a symbol's linkage and visibility with a linkage directive for XCOFF.</p>


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

<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="#a37f26d2730c10e4c90f1b175ea4118e9">emitXCOFFRenameDirective</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a345961d937ffac378faab680906913d6">llvm::MCSA_Exported</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243ab11aa8a54bc3faf1ef7db38e4bf4fb60">llvm::MCSA_Extern</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243aa1e94c23156e37812e4d6e078af1d728">llvm::MCSA_Global</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243ae472359b991bb5235c8f6714f4cacb6a">llvm::MCSA_Hidden</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243af3367f8319e21bf0779da14146221c55">llvm::MCSA_Invalid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243ae5c5c7dd59c0c23f91be2b9c8f2594c9">llvm::MCSA_LGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a1f47433b83f2818076a3cf55b500233a">llvm::MCSA_Protected</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a83df6138e7dba38c0c80380486544ea0">llvm::MCSA_Weak</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### emitZerofill {#a3ce73ec5824c032df5044c83409259be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::emitZerofill (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Section, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol=nullptr, uint64_t Size=0, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> ByteAlignment=<a href="/web-llvm/docs/api/structs/llvm/align">Align</a>(1), <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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

<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#aac4366cca0c8d3cd472a02a71f4aa34c">llvm::MCSection::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionmacho/#a3daa3b8dd38ee3a426a6f83bb3cac0d2">llvm::MCSectionMachO::getSegmentName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad82de9da62635df78a534de0f16c1129">llvm::Log2</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsection/#afecf7c84b079ea5c169f71b6c06ece98a55ed9b1dac938f496436528db3576783">llvm::MCSection::SV_MachO</a>.</p>

</div>
</div>

### endCOFFSymbolDef {#ad27b03230251d90cbb679fe5ea2c2eb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::endCOFFSymbolDef ()</td>
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

<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Reference <a href="#a7064b16a5706077633ab420138948ae9">EmitEOL</a>.</p>

</div>
</div>

### finishImpl {#a5333321f84976a4bf06be40827ca62d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::finishImpl ()</td>
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

<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcgendwarfinfo/#af945d198ed58841b8d57f45a11e2987e">llvm::MCGenDwarfInfo::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#a89cdc6ed6476f39c32e5a49327bb692e">llvm::MCDwarfLineTable::emit</a>, <a href="#a99306d453eed689739055115d79beeca">emitLabel</a>, <a href="#ad3dde63a47820ff7740ed6d126a47ad7">getAssembler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a> and <a href="#a4712c0b6d11e44d06eea24bc7b786ca9">switchSection</a>.</p>

</div>
</div>

### getDwarfLineTableSymbol {#a55febacdfb6b6c8b692186d32dbe96c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MCAsmStreamer::getDwarfLineTableSymbol (unsigned CUID)</td>
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



<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#aa51d3a6818627c9f45797eeef1f1b91c">llvm::MCStreamer::getDwarfLineTableSymbol</a>.</p>

</div>
</div>

### getMnemonic {#ad6e393e30f9c56864f4db9487f1e6b8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::getMnemonic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI)</td>
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

<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### popSection {#a34cd5a64eb935155249865a6f30bdc5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAsmStreamer::popSection ()</td>
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


<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ad946e0775ff08232ff6dc1bd9a8ed9bb">llvm::MCStreamer::getCurrentSection</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a216005880453270b48e5d5d7daeec6d4">llvm::MCStreamer::popSection</a>.</p>

</div>
</div>

### PrintCVDefRangePrefix {#a467384728fb302838e583379b7b23079}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::PrintCVDefRangePrefix (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt; &gt; Ranges)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>


<p>Referenced by <a href="#a3f2246f74c434ed53299fdf711b1f9a5">emitCVDefRangeDirective</a>, <a href="#a534087ca10707b8e963d0093d687136e">emitCVDefRangeDirective</a>, <a href="#aa49eb297857f4bf2aeec6b1d3f57b051">emitCVDefRangeDirective</a> and <a href="#a096a232a154a45ff185cd71961f565f9">emitCVDefRangeDirective</a>.</p>

</div>
</div>

### switchSection {#a4712c0b6d11e44d06eea24bc7b786ca9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmStreamer::switchSection (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Section, uint32_t Subsec)</td>
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


<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ad946e0775ff08232ff6dc1bd9a8ed9bb">llvm::MCStreamer::getCurrentSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a901607e60c20148ae701b6e8f43b4647">llvm::MCStreamer::getTargetStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ac4f84451dc4abc997c960d484953b1d2">llvm::MCStreamer::switchSection</a>.</p>


<p>Referenced by <a href="#a5333321f84976a4bf06be40827ca62d8">finishImpl</a>.</p>

</div>
</div>

### tryEmitDwarfFileDirective {#aa2807954a9bf3d29ba94545ebaa23584}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; unsigned &gt; MCAsmStreamer::tryEmitDwarfFileDirective (unsigned FileNo, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directory, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/md5/md5result">MD5::MD5Result</a> &gt; Checksum=std::nullopt, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; Source=std::nullopt, unsigned CUID=0)</td>
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


<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ae5807cb4b1f712252faa7d31f9d19815">llvm::MCStreamer::emitRawText</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#af3dabb2d8280080e29d147b7629da1ac">llvm::MCDwarfLineTable::getMCDwarfFiles</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a901607e60c20148ae701b6e8f43b4647">llvm::MCStreamer::getTargetStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream/#a9c2cac84e46d3e744aeca03dd3d557d1">llvm::raw_svector_ostream::str</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#ae399e752589e5b62546a63325cedb528">llvm::MCDwarfLineTable::tryGetFile</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
