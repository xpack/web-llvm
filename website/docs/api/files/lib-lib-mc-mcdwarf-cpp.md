---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/mc/mcdwarf-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `MCDwarf.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">llvm/MC/MCDwarf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">llvm/ADT/SmallString.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">llvm/BinaryFormat/Dwarf.h</a>"
#include "llvm/Config/config.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfo-h">llvm/MC/MCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">llvm/MC/MCObjectFileInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectstreamer-h">llvm/MC/MCObjectStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">llvm/MC/MCRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">llvm/MC/MCSection.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">llvm/MC/MCStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">llvm/MC/MCSymbol.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endianstream-h">llvm/Support/EndianStream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/leb128-h">llvm/Support/LEB128.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">llvm/Support/MathExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">llvm/Support/Path.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">llvm/Support/SourceMgr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include &lt;optional&gt;
#include &lt;string&gt;
#include &lt;utility&gt;
#include &lt;vector&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-mcdwarf-cpp-">anonymous{MCDwarf.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl">FrameEmitterImpl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-mcdwarf-cpp-/ciekey">CIEKey</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ce1bed1bbcf6373d4bedd7ef53477f2">ScaleAddrDelta</a> (MCContext &amp;Context, uint64_t AddrDelta)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a831093d85c75c64067ee4ecd1e811860">makeEndMinusStartExpr</a> (MCContext &amp;Ctx, const MCSymbol &amp;Start, const MCSymbol &amp;End, int IntVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad484999912240f5615d60831473902cd">makeStartPlusIntExpr</a> (MCContext &amp;Ctx, const MCSymbol &amp;Start, int IntVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46eb8d3c0aed8e455691e71a12c142fd">forceExpAbs</a> (MCStreamer &amp;OS, const MCExpr *Expr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a479c805988e7c9a81faae52757503066">emitAbsValue</a> (MCStreamer &amp;OS, const MCExpr *Value, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f51a5e71249c406f3e5f1dd24201546">emitOneV5FileEntry</a> (MCStreamer *MCOS, const MCDwarfFile &amp;DwarfFile, bool EmitMD5, bool HasAnySource, std::optional&lt; MCDwarfLineStr &gt; &amp;LineStr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a316a87d22716c281f8e9320a97ea5acf">isRootFile</a> (const MCDwarfFile &amp;RootFile, StringRef &amp;Directory, StringRef &amp;FileName, std::optional&lt; MD5::MD5Result &gt; Checksum)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a45bf6d0fbef0afa6304a0a90d4cc7c">SpecialAddr</a> (MCDwarfLineTableParams Params, uint64_t op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a special op, return the address skip amount (in units of DWARF2_LINE_MIN_INSN_LENGTH). <a href="#a1a45bf6d0fbef0afa6304a0a90d4cc7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa131aa465a52fed2d70d09bfd862f8da">EmitAbbrev</a> (MCStreamer *MCOS, uint64_t Name, uint64_t Form)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3810dff97d2b1f712f053e18a98f383">EmitGenDwarfAbbrev</a> (MCStreamer *MCOS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b98f9e375747640ed4f1f019b0558aa">EmitGenDwarfAranges</a> (MCStreamer *MCOS, const MCSymbol *InfoSectionSymbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a> (MCStreamer *MCOS, const MCSymbol *AbbrevSectionSymbol, const MCSymbol *LineSectionSymbol, const MCSymbol *RangesSymbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd1c7609888ea3462f400dcfbca2e486">emitGenDwarfRanges</a> (MCStreamer *MCOS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab521cbeeba5f775524447eec5b221d56">getDataAlignmentFactor</a> (MCStreamer &amp;streamer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae482cc4ee4cf4d5b4bfe6e1dde4f1ed8">getSizeForEncoding</a> (MCStreamer &amp;streamer, unsigned symbolEncoding)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07c0db5089a287c91b8197cad7f2eeda">emitFDESymbol</a> (MCObjectStreamer &amp;streamer, const MCSymbol &amp;symbol, unsigned symbolEncoding, bool isEH)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5b673bb0b1684ee529dc9fcafd6167b">EmitPersonality</a> (MCStreamer &amp;streamer, const MCSymbol &amp;symbol, unsigned symbolEncoding)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabfe51a98519272e0f4ee5e0fdcb90b0">emitEncodingByte</a> (MCObjectStreamer &amp;Streamer, unsigned Encoding)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a845dfa10e848411e52b9dbba304cb887">getCIEVersion</a> (bool IsEH, unsigned DwarfVersion)</td>
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

### EmitAbbrev() {#aa131aa465a52fed2d70d09bfd862f8da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void EmitAbbrev (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> * MCOS, uint64_t Name, uint64_t Form)</td>
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



<p>Definition at line 800 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#abc5f738b9471c3ed31b8f1fc7dc8e914">llvm::MCStreamer::emitULEB128IntValue</a>.</p>


<p>Referenced by <a href="#ae3810dff97d2b1f712f053e18a98f383">EmitGenDwarfAbbrev</a>.</p>

</div>
</div>

### emitAbsValue() {#a479c805988e7c9a81faae52757503066}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitAbsValue (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value, unsigned Size)</td>
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



<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7833630c617e5943c0a41755f5d4bdcf">llvm::MCStreamer::emitValue</a>, <a href="#a46eb8d3c0aed8e455691e71a12c142fd">forceExpAbs</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a06884c9e11f3d8bb503abfb8dc03586b">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCIE</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a53a38280a7cf030655d4ad153dcf8cc1">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCompactUnwind</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a3d9503972de494ac87e3025a25bbbbb6">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitFDE</a>, <a href="#a07c0db5089a287c91b8197cad7f2eeda">emitFDESymbol</a>, <a href="#a1b98f9e375747640ed4f1f019b0558aa">EmitGenDwarfAranges</a>, <a href="#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a> and <a href="#acd1c7609888ea3462f400dcfbca2e486">emitGenDwarfRanges</a>.</p>

</div>
</div>

### emitEncodingByte() {#aabfe51a98519272e0f4ee5e0fdcb90b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitEncodingByte (<a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer">MCObjectStreamer</a> &amp; Streamer, unsigned Encoding)</td>
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



<p>Definition at line 1351 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#af47540299db471532b82aba9314f1fc2">llvm::MCStreamer::emitInt8</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a06884c9e11f3d8bb503abfb8dc03586b">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCIE</a>.</p>

</div>
</div>

### emitFDESymbol() {#a07c0db5089a287c91b8197cad7f2eeda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitFDESymbol (<a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer">MCObjectStreamer</a> &amp; streamer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; symbol, unsigned symbolEncoding, bool isEH)</td>
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



<p>Definition at line 1301 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#abaf90036262e5f40f8497a449975e700">llvm::MCAsmInfo::doDwarfFDESymbolsUseAbsDiff</a>, <a href="#a479c805988e7c9a81faae52757503066">emitAbsValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7833630c617e5943c0a41755f5d4bdcf">llvm::MCStreamer::emitValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aa3beac794c4afb5b1fb6d06cb7786587">llvm::MCContext::getAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a9e11e3c1ca2c5f957aa7a7a16ff40e24">llvm::MCAsmInfo::getExprForFDESymbol</a>, <a href="#ae482cc4ee4cf4d5b4bfe6e1dde4f1ed8">getSizeForEncoding</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a3d9503972de494ac87e3025a25bbbbb6">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitFDE</a>.</p>

</div>
</div>

### EmitGenDwarfAbbrev() {#ae3810dff97d2b1f712f053e18a98f383}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void EmitGenDwarfAbbrev (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> * MCOS)</td>
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



<p>Definition at line 807 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255a0dca9833b8163863bfe1a9aa315a2dd8">llvm::dwarf::DW_CHILDREN_no</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255a4b8a3f1fe8eed309f0b034064b508050">llvm::dwarf::DW_CHILDREN_yes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a34b4d38e06d609b405f4a79c223ed8d2">llvm::dwarf::DWARF64</a>, <a href="#aa131aa465a52fed2d70d09bfd862f8da">EmitAbbrev</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#af47540299db471532b82aba9314f1fc2">llvm::MCStreamer::emitInt8</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#abc5f738b9471c3ed31b8f1fc7dc8e914">llvm::MCStreamer::emitULEB128IntValue</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a2a19163118e2b27686c1010ab26556a3">llvm::MCContext::getCompilationDir</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#ac10c6a9d85782db274d19ef8f828d9fc">llvm::MCObjectFileInfo::getDwarfAbbrevSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a2757e59e5aa1e5a66e2b11352caa61bd">llvm::MCContext::getDwarfDebugFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ae871de84d03670534d73ae7448b6b6d9">llvm::MCContext::getDwarfFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a99c58fcbed2434b9535b866015cd0259">llvm::MCContext::getDwarfVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a0ffd38472bf725df4e4c3cac8c0ad771">llvm::MCContext::getGenDwarfSectionSyms</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a01d6d82d18a5da901c50a546932c4264">llvm::MCContext::getObjectFileInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ac4f84451dc4abc997c960d484953b1d2">llvm::MCStreamer::switchSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcgendwarfinfo/#af945d198ed58841b8d57f45a11e2987e">llvm::MCGenDwarfInfo::Emit</a>.</p>

</div>
</div>

### EmitGenDwarfAranges() {#a1b98f9e375747640ed4f1f019b0558aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void EmitGenDwarfAranges (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> * MCOS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * InfoSectionSymbol)</td>
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



<p>Definition at line 856 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#af37a255a9a1f06e51c27b3a5a5c7baf4adc3aedef0caeccf6d845a430da6d3f8d">llvm::dwarf::DW_LENGTH_DWARF64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a34b4d38e06d609b405f4a79c223ed8d2">llvm::dwarf::DWARF64</a>, <a href="#a479c805988e7c9a81faae52757503066">emitAbsValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9d412a2cef594fc0f45de176d51fee3b">llvm::MCStreamer::emitInt16</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#acc3817979bc871dba942b87773da1cc0">llvm::MCStreamer::emitInt32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#af47540299db471532b82aba9314f1fc2">llvm::MCStreamer::emitInt8</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a971830cc1546210be8cc86fa568be8d0">llvm::MCStreamer::emitIntValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7865bd61cd2c65b2d94c58dd1523bb75">llvm::MCStreamer::emitSymbolValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7833630c617e5943c0a41755f5d4bdcf">llvm::MCStreamer::emitValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aa3beac794c4afb5b1fb6d06cb7786587">llvm::MCContext::getAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#affd5fd4fc8ca1b0f483c51543e58108d">llvm::MCAsmInfo::getCodePointerSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#ae17df2cce5c5b2cb1688d22f2d90820c">llvm::MCObjectFileInfo::getDwarfARangesSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ae871de84d03670534d73ae7448b6b6d9">llvm::MCContext::getDwarfFormat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa234436b20c856bcf616330ffcad6939">llvm::dwarf::getDwarfOffsetByteSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a0ffd38472bf725df4e4c3cac8c0ad771">llvm::MCContext::getGenDwarfSectionSyms</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a01d6d82d18a5da901c50a546932c4264">llvm::MCContext::getObjectFileInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a0b741aef91502fa04c0f5265a58ba45c">llvm::dwarf::getUnitLengthFieldByteSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="#a831093d85c75c64067ee4ecd1e811860">makeEndMinusStartExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a7712b3a2d11d7c25f0378d814255b253">llvm::MCAsmInfo::needsDwarfSectionOffsetDirective</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ac4f84451dc4abc997c960d484953b1d2">llvm::MCStreamer::switchSection</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcgendwarfinfo/#af945d198ed58841b8d57f45a11e2987e">llvm::MCGenDwarfInfo::Emit</a>.</p>

</div>
</div>

### EmitGenDwarfInfo() {#a8ecc921219ca991a8cd7607227646ccf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void EmitGenDwarfInfo (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> * MCOS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * AbbrevSectionSymbol, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * LineSectionSymbol, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * RangesSymbol)</td>
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



<p>Definition at line 935 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a299bf2f0329389424760f4a7c8af75ac">llvm::MCContext::createTempSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#af37a255a9a1f06e51c27b3a5a5c7baf4adc3aedef0caeccf6d845a430da6d3f8d">llvm::dwarf::DW_LENGTH_DWARF64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a34b4d38e06d609b405f4a79c223ed8d2">llvm::dwarf::DWARF64</a>, <a href="#a479c805988e7c9a81faae52757503066">emitAbsValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#af94e84eca402017c9ce57b7b4c4104e3">llvm::MCStreamer::emitBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9d412a2cef594fc0f45de176d51fee3b">llvm::MCStreamer::emitInt16</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#acc3817979bc871dba942b87773da1cc0">llvm::MCStreamer::emitInt32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#af47540299db471532b82aba9314f1fc2">llvm::MCStreamer::emitInt8</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a971830cc1546210be8cc86fa568be8d0">llvm::MCStreamer::emitIntValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a822ae1a4f19b7b00a297a100749f9b8a">llvm::MCStreamer::emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7865bd61cd2c65b2d94c58dd1523bb75">llvm::MCStreamer::emitSymbolValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#abc5f738b9471c3ed31b8f1fc7dc8e914">llvm::MCStreamer::emitULEB128IntValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7833630c617e5943c0a41755f5d4bdcf">llvm::MCStreamer::emitValue</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a002a323feef10733642f9f92f6a94f1a">llvm::sys::path::get_separator</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aa3beac794c4afb5b1fb6d06cb7786587">llvm::MCContext::getAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#affd5fd4fc8ca1b0f483c51543e58108d">llvm::MCAsmInfo::getCodePointerSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a2a19163118e2b27686c1010ab26556a3">llvm::MCContext::getCompilationDir</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a2757e59e5aa1e5a66e2b11352caa61bd">llvm::MCContext::getDwarfDebugFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a1fa812f878a36093c56d691c50a23a3e">llvm::MCContext::getDwarfDebugProducer</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ae871de84d03670534d73ae7448b6b6d9">llvm::MCContext::getDwarfFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a82d739b35c6534d476fc5bf7d2ee57cb">llvm::MCObjectFileInfo::getDwarfInfoSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa234436b20c856bcf616330ffcad6939">llvm::dwarf::getDwarfOffsetByteSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a99c58fcbed2434b9535b866015cd0259">llvm::MCContext::getDwarfVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a0ffd38472bf725df4e4c3cac8c0ad771">llvm::MCContext::getGenDwarfSectionSyms</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a11e4d2892230408be583cbf6ee7c28c0">llvm::MCContext::getMCDwarfDirs</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a81530c44115124e6e977b6e14b8ec4a1">llvm::MCContext::getMCDwarfFiles</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a62f7e21c9dac9e7acb4fdd713e712d20">llvm::MCContext::getMCDwarfLineTable</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aed43a765c7bd89683590bab0196c87b3">llvm::MCContext::getMCGenDwarfLabelEntries</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a01d6d82d18a5da901c50a546932c4264">llvm::MCContext::getObjectFileInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#a65fb41d3f061e9004436525117bf6f8b">llvm::MCDwarfLineTable::getRootFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a0b741aef91502fa04c0f5265a58ba45c">llvm::dwarf::getUnitLengthFieldByteSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="#a831093d85c75c64067ee4ecd1e811860">makeEndMinusStartExpr</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarffile/#a14ad1cb6e8857b9f234f15e73434f508">llvm::MCDwarfFile::Name</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a7712b3a2d11d7c25f0378d814255b253">llvm::MCAsmInfo::needsDwarfSectionOffsetDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ac4f84451dc4abc997c960d484953b1d2">llvm::MCStreamer::switchSection</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcgendwarfinfo/#af945d198ed58841b8d57f45a11e2987e">llvm::MCGenDwarfInfo::Emit</a>.</p>

</div>
</div>

### emitGenDwarfRanges() {#acd1c7609888ea3462f400dcfbca2e486}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * emitGenDwarfRanges (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> * MCOS)</td>
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



<p>Definition at line 1109 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a64eafd6bed9f342e423e74a93223135c">llvm::MCStreamer::AddComment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a299bf2f0329389424760f4a7c8af75ac">llvm::MCContext::createTempSymbol</a>, <a href="#a479c805988e7c9a81faae52757503066">emitAbsValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#af6a6f6142b6fd138cdc9e08217577c4d">llvm::MCStreamer::emitFill</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#acc3817979bc871dba942b87773da1cc0">llvm::MCStreamer::emitInt32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#af47540299db471532b82aba9314f1fc2">llvm::MCStreamer::emitInt8</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a971830cc1546210be8cc86fa568be8d0">llvm::MCStreamer::emitIntValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a822ae1a4f19b7b00a297a100749f9b8a">llvm::MCStreamer::emitLabel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcdwarf/#ad32db1a85072666827c900bee74761b1">llvm::mcdwarf::emitListsTableHeaderStart</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#abe4c2642ccb651af1def37f17f10bd19">llvm::MCStreamer::emitULEB128Value</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7833630c617e5943c0a41755f5d4bdcf">llvm::MCStreamer::emitValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aa3beac794c4afb5b1fb6d06cb7786587">llvm::MCContext::getAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#affd5fd4fc8ca1b0f483c51543e58108d">llvm::MCAsmInfo::getCodePointerSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a31df4edd580fc4f6e43318cd9c5ed5bc">llvm::MCObjectFileInfo::getDwarfRangesSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a7cddd5b91a2f88c1c204cafeca322517">llvm::MCObjectFileInfo::getDwarfRnglistsSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a99c58fcbed2434b9535b866015cd0259">llvm::MCContext::getDwarfVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a0ffd38472bf725df4e4c3cac8c0ad771">llvm::MCContext::getGenDwarfSectionSyms</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a01d6d82d18a5da901c50a546932c4264">llvm::MCContext::getObjectFileInfo</a>, <a href="#a831093d85c75c64067ee4ecd1e811860">makeEndMinusStartExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ac4f84451dc4abc997c960d484953b1d2">llvm::MCStreamer::switchSection</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcgendwarfinfo/#af945d198ed58841b8d57f45a11e2987e">llvm::MCGenDwarfInfo::Emit</a>.</p>

</div>
</div>

### emitOneV5FileEntry() {#a7f51a5e71249c406f3e5f1dd24201546}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitOneV5FileEntry (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> * MCOS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcdwarffile">MCDwarfFile</a> &amp; DwarfFile, bool EmitMD5, bool HasAnySource, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinestr">MCDwarfLineStr</a> &gt; &amp; LineStr)</td>
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



<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a1d73c2da2d5410a07113b9f24c640c12">llvm::MCStreamer::emitBinaryData</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#af94e84eca402017c9ce57b7b4c4104e3">llvm::MCStreamer::emitBytes</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#abc5f738b9471c3ed31b8f1fc7dc8e914">llvm::MCStreamer::emitULEB128IntValue</a>.</p>

</div>
</div>

### EmitPersonality() {#aa5b673bb0b1684ee529dc9fcafd6167b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void EmitPersonality (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; streamer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; symbol, unsigned symbolEncoding)</td>
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



<p>Definition at line 1315 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7833630c617e5943c0a41755f5d4bdcf">llvm::MCStreamer::emitValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aa3beac794c4afb5b1fb6d06cb7786587">llvm::MCContext::getAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ae3fe25dab4d13b8a586b9647a0347738">llvm::MCAsmInfo::getExprForPersonalitySymbol</a>, <a href="#ae482cc4ee4cf4d5b4bfe6e1dde4f1ed8">getSizeForEncoding</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a06884c9e11f3d8bb503abfb8dc03586b">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCIE</a>.</p>

</div>
</div>

### forceExpAbs() {#a46eb8d3c0aed8e455691e71a12c142fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * forceExpAbs (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr)</td>
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



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a04736ef5753e5ecda3c29ce902094e68">llvm::MCStreamer::emitAssignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#a479c805988e7c9a81faae52757503066">emitAbsValue</a>.</p>

</div>
</div>

### getCIEVersion() {#a845dfa10e848411e52b9dbba304cb887}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getCIEVersion (bool IsEH, unsigned DwarfVersion)</td>
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



<p>Definition at line 1610 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a06884c9e11f3d8bb503abfb8dc03586b">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCIE</a>.</p>

</div>
</div>

### getDataAlignmentFactor() {#ab521cbeeba5f775524447eec5b221d56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int getDataAlignmentFactor (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; streamer)</td>
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



<p>Definition at line 1270 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aa3beac794c4afb5b1fb6d06cb7786587">llvm::MCContext::getAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ab0d84507baa4a3f190f760d53422d54e">llvm::MCAsmInfo::getCalleeSaveStackSlotSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#aa5ade20e196d9d9bc1df3c4fa3c2279a">llvm::MCAsmInfo::isStackGrowthDirectionUp</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a483ddfcbeaea69d0917549e79f76e7fe">anonymous{MCDwarf.cpp}::FrameEmitterImpl::emitCFIInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a06884c9e11f3d8bb503abfb8dc03586b">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf/fde/#a908b837fc83c1d8f4e314b33f0607de1">llvm::dwarf::FDE::FDE</a>.</p>

</div>
</div>

### getSizeForEncoding() {#ae482cc4ee4cf4d5b4bfe6e1dde4f1ed8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getSizeForEncoding (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; streamer, unsigned symbolEncoding)</td>
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



<p>Definition at line 1280 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255ab8bb265a153372d87860f6a33d858f3e">llvm::dwarf::DW_EH_PE_absptr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255abf732c58551b977c2f830e8ddd06e64f">llvm::dwarf::DW_EH_PE_sdata2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255a68bcc7d64ea60cf76503e913360e0b01">llvm::dwarf::DW_EH_PE_sdata4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255ab4f228eae8e91cb5eb218c4372d2cd75">llvm::dwarf::DW_EH_PE_sdata8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255a43244ccf6c5f085a9fdf303d86761a27">llvm::dwarf::DW_EH_PE_signed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255ab06941f802d97190e82e32018265b5f1">llvm::dwarf::DW_EH_PE_udata2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255abfafdba601fd5cab55113f2cdb96c033">llvm::dwarf::DW_EH_PE_udata4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255ac75ce7ce2df1136a194d4cd1d889c06a">llvm::dwarf::DW_EH_PE_udata8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aa3beac794c4afb5b1fb6d06cb7786587">llvm::MCContext::getAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#affd5fd4fc8ca1b0f483c51543e58108d">llvm::MCAsmInfo::getCodePointerSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a06884c9e11f3d8bb503abfb8dc03586b">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCIE</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a53a38280a7cf030655d4ad153dcf8cc1">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCompactUnwind</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a3d9503972de494ac87e3025a25bbbbb6">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitFDE</a>, <a href="#a07c0db5089a287c91b8197cad7f2eeda">emitFDESymbol</a> and <a href="#aa5b673bb0b1684ee529dc9fcafd6167b">EmitPersonality</a>.</p>

</div>
</div>

### isRootFile() {#a316a87d22716c281f8e9320a97ea5acf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isRootFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcdwarffile">MCDwarfFile</a> &amp; RootFile, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Directory, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; FileName, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/md5/md5result">MD5::MD5Result</a> &gt; Checksum)</td>
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



<p>Definition at line 610 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/mcdwarffile/#a07c9bf0537b9f094eb0b52b12116ecc6">llvm::MCDwarfFile::Checksum</a> and <a href="/web-llvm/docs/api/structs/llvm/mcdwarffile/#a14ad1cb6e8857b9f234f15e73434f508">llvm::MCDwarfFile::Name</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableheader/#af400fb04adbd61dff400a8a4a756aff9">llvm::MCDwarfLineTableHeader::tryGetFile</a>.</p>

</div>
</div>

### makeEndMinusStartExpr() {#a831093d85c75c64067ee4ecd1e811860}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * makeEndMinusStartExpr (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; Start, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; End, int IntVal)</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#ac393df34745cae1433909c2049978bd4">llvm::MCBinaryExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a2042f1a9af632c3d4d83f157201623d2">llvm::MCBinaryExpr::Sub</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a06884c9e11f3d8bb503abfb8dc03586b">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCIE</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a53a38280a7cf030655d4ad153dcf8cc1">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCompactUnwind</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a3d9503972de494ac87e3025a25bbbbb6">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitFDE</a>, <a href="#a1b98f9e375747640ed4f1f019b0558aa">EmitGenDwarfAranges</a>, <a href="#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a> and <a href="#acd1c7609888ea3462f400dcfbca2e486">emitGenDwarfRanges</a>.</p>

</div>
</div>

### makeStartPlusIntExpr() {#ad484999912240f5615d60831473902cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * makeStartPlusIntExpr (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; Start, int IntVal)</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629ae3bbdb1bec11d89ba5478648dcd3ec3c">llvm::MCBinaryExpr::Add</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#ac393df34745cae1433909c2049978bd4">llvm::MCBinaryExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinestr/#ad325ab6e610eb8bd1f59534515561fdc">llvm::MCDwarfLineStr::emitRef</a>.</p>

</div>
</div>

### ScaleAddrDelta() {#a3ce1bed1bbcf6373d4bedd7ef53477f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t ScaleAddrDelta (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Context, uint64_t AddrDelta)</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcdwarflineaddr/#ae0f19d1d97309d2c250054dae4569622">llvm::MCDwarfLineAddr::encode</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdwarfframeemitter/#aa8057040c954e677e4172d5b69650b72">llvm::MCDwarfFrameEmitter::encodeAdvanceLoc</a>.</p>

</div>
</div>

### SpecialAddr() {#a1a45bf6d0fbef0afa6304a0a90d4cc7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t SpecialAddr (<a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableparams">MCDwarfLineTableParams</a> Params, uint64_t op)</td>
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

<p>Given a special op, return the address skip amount (in units of DWARF2_LINE_MIN_INSN_LENGTH).</p>

<p>Definition at line 711 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableparams/#aa098ab41af3f8cee8b1939003d55a776">llvm::MCDwarfLineTableParams::DWARF2LineOpcodeBase</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableparams/#ac75e30002379b9f61625bc8d2b4b1919">llvm::MCDwarfLineTableParams::DWARF2LineRange</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcdwarflineaddr/#ae0f19d1d97309d2c250054dae4569622">llvm::MCDwarfLineAddr::encode</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
