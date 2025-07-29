---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/mc/mcasmstreamer-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `MCAsmStreamer.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">llvm/ADT/SmallString.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecord-h">llvm/DebugInfo/CodeView/SymbolRecord.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmbackend-h">llvm/MC/MCAsmBackend.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfo-h">llvm/MC/MCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">llvm/MC/MCAssembler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeemitter-h">llvm/MC/MCCodeEmitter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">llvm/MC/MCCodeView.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixupkindinfo-h">llvm/MC/MCFixupKindInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">llvm/MC/MCInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">llvm/MC/MCInstPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">llvm/MC/MCObjectFileInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectwriter-h">llvm/MC/MCObjectWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">llvm/MC/MCPseudoProbe.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregister-h">llvm/MC/MCRegister.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">llvm/MC/MCRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionmacho-h">llvm/MC/MCSectionMachO.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">llvm/MC/MCStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolxcoff-h">llvm/MC/MCSymbolXCOFF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/format-h">llvm/Support/Format.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formattedstream-h">llvm/Support/FormattedStream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/leb128-h">llvm/Support/LEB128.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">llvm/Support/MathExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">llvm/Support/Path.h</a>"
#include &lt;algorithm&gt;
#include &lt;optional&gt;
#include "llvm/BinaryFormat/MachO.def"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-mcasmstreamer-cpp-">anonymous{MCAsmStreamer.cpp}</a></td>
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

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a1994cc203b2699119e91b908b9d50b">truncateToSize</a> (int64_t Value, unsigned Bytes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a217b69ba8c630b233ead7f3a622aa3e3">getVersionMinDirective</a> (MCVersionMinType Type)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96037fc0434f2d1c064f7748b41f8c1d">EmitSDKVersionSuffix</a> (raw_ostream &amp;OS, const VersionTuple &amp;SDKVersion)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe722131e76a74beba89f34b423c7a70">getPlatformName</a> (MachO::PlatformType Type)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c1b3db86d8571c3f038c371acbcacb7">isPrintableString</a> (StringRef Data)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b2ce12e7db9e5e52f0b6f4e1d6df56a">toOctal</a> (int X)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41a5d3f4153e507fc78c645cdc1037a0">PrintByteList</a> (StringRef Data, raw_ostream &amp;OS, MCAsmInfo::AsmCharLiteralSyntax ACLS)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cfb229540a44ffdd406ca12e441fd47">PrintCFIEscape</a> (llvm::formatted_raw_ostream &amp;OS, StringRef Values)</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6fe6c7765cda797476c1ce86165ae93">PLATFORM</a>(platform, id, name, build_name, target, tapi_target, marketing)&nbsp;&nbsp;&nbsp;...</td>
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

### EmitSDKVersionSuffix() {#a96037fc0434f2d1c064f7748b41f8c1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void EmitSDKVersionSuffix (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a> &amp; SDKVersion)</td>
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



<p>Definition at line 647 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/versiontuple/#ad07e5841d788dc29bdda972b3f92be6b">llvm::VersionTuple::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/versiontuple/#a56a72b8793b8e0df7217c9b19a83320b">llvm::VersionTuple::getMajor</a>, <a href="/web-llvm/docs/api/classes/llvm/versiontuple/#af16679f141c8a480a1e6dcc0b8bcf5de">llvm::VersionTuple::getMinor</a> and <a href="/web-llvm/docs/api/classes/llvm/versiontuple/#aa338b51f08e9ffa7fb62c92276d9c7a6">llvm::VersionTuple::getSubminor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a73d1f3201777b81d5a80bd6da19e7bee">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitBuildVersion</a> and <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a422f5621940beb2e051d9468d4f70922">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitVersionMin</a>.</p>

</div>
</div>

### getPlatformName() {#afe722131e76a74beba89f34b423c7a70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * getPlatformName (<a href="/web-llvm/docs/api/namespaces/llvm/macho/#a3cdacd46a54ada4abe329c88c7a92504">MachO::PlatformType</a> Type)</td>
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



<p>Definition at line 670 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a73d1f3201777b81d5a80bd6da19e7bee">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitBuildVersion</a>.</p>

</div>
</div>

### getVersionMinDirective() {#a217b69ba8c630b233ead7f3a622aa3e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * getVersionMinDirective (<a href="/web-llvm/docs/api/namespaces/llvm/#a7b22b2a20e7587321d17cb029ea8626e">MCVersionMinType</a> Type)</td>
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



<p>Definition at line 637 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b22b2a20e7587321d17cb029ea8626ead9e407b6ec006c31f17818a1283f6d3f">llvm::MCVM_IOSVersionMin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b22b2a20e7587321d17cb029ea8626ea386d6f60bcd1993e7d17e07a0af6affb">llvm::MCVM_OSXVersionMin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b22b2a20e7587321d17cb029ea8626eaa7ab690e482966c940af477dcf395dce">llvm::MCVM_TvOSVersionMin</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7b22b2a20e7587321d17cb029ea8626ea183c1e03234356aae7e6f65d0b0931f4">llvm::MCVM_WatchOSVersionMin</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a422f5621940beb2e051d9468d4f70922">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitVersionMin</a>.</p>

</div>
</div>

### isPrintableString() {#a2c1b3db86d8571c3f038c371acbcacb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isPrintableString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Data)</td>
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



<p>Definition at line 1179 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a807369cf0e8ddbe75c8c4a671bfc4258">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitBytes</a>.</p>

</div>
</div>

### PrintByteList() {#a41a5d3f4153e507fc78c645cdc1037a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PrintByteList (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Data, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ae0a2d87aa9c2d59f6c38b3d55f530fd9">MCAsmInfo::AsmCharLiteralSyntax</a> ACLS)</td>
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



<p>Definition at line 1190 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ae0a2d87aa9c2d59f6c38b3d55f530fd9ad1ecc712b2ab5b0f004b0935208910f5">llvm::MCAsmInfo::ACLS_SingleQuotePrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ae0a2d87aa9c2d59f6c38b3d55f530fd9a86253400608583c262a2539ece4b5e50">llvm::MCAsmInfo::ACLS_Unknown</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a> and <a href="#a6b2ce12e7db9e5e52f0b6f4e1d6df56a">toOctal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a807369cf0e8ddbe75c8c4a671bfc4258">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitBytes</a>.</p>

</div>
</div>

### PrintCFIEscape() {#a0cfb229540a44ffdd406ca12e441fd47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PrintCFIEscape (<a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">llvm::formatted_raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Values)</td>
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



<p>Definition at line 2043 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a7fef34027fa50e93af1d29428199df26">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCFIEscape</a> and <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a0ba55c78541fd684b5ccd7eb8aacec66">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCFIGnuArgsSize</a>.</p>

</div>
</div>

### toOctal() {#a6b2ce12e7db9e5e52f0b6f4e1d6df56a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char toOctal (int X)</td>
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



<p>Definition at line 1188 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="#a41a5d3f4153e507fc78c645cdc1037a0">PrintByteList</a>.</p>

</div>
</div>

### truncateToSize() {#a9a1994cc203b2699119e91b908b9d50b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t truncateToSize (int64_t Value, unsigned Bytes)</td>
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



<p>Definition at line 482 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a36690cdc5f927e7553ec268a036a722f">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitAlignmentDirective</a> and <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a664095c8afe2051a5e22b25100685b01">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitFill</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### PLATFORM {#af6fe6c7765cda797476c1ce86165ae93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PLATFORM(platform, id, name, build_name, target, tapi_target, marketing)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case MachO::PLATFORM_##platform:                                             \
    return #build_name;
</div>
</dd>
</dl>

<p>Definition at line 673 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp">MCAsmStreamer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
