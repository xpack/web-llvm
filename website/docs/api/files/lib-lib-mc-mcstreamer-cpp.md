---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/mc/mcstreamer-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `MCStreamer.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">llvm/MC/MCStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">llvm/ADT/SmallString.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/coff-h">llvm/BinaryFormat/COFF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">llvm/BinaryFormat/MachO.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecord-h">llvm/DebugInfo/CodeView/SymbolRecord.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmbackend-h">llvm/MC/MCAsmBackend.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfo-h">llvm/MC/MCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">llvm/MC/MCCodeView.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">llvm/MC/MCDwarf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">llvm/MC/MCInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">llvm/MC/MCInstPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">llvm/MC/MCObjectFileInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">llvm/MC/MCPseudoProbe.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregister-h">llvm/MC/MCRegister.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">llvm/MC/MCRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">llvm/MC/MCSection.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectioncoff-h">llvm/MC/MCSectionCOFF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">llvm/MC/MCSymbol.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwin64eh-h">llvm/MC/MCWin64EH.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwineh-h">llvm/MC/MCWinEH.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/leb128-h">llvm/Support/LEB128.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">llvm/Support/MathExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include &lt;cstdlib&gt;
#include &lt;optional&gt;
#include &lt;utility&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4b504b0bbdb4909cebdc60855bd6fd6a">copyBytesForDefRange</a> (SmallString&lt; 20 &gt; &amp;BytePrefix, codeview::SymbolKind SymKind, const T &amp;DefRangeHeader)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Only call this on endian-specific types like ulittle16_t and little32_t, or structs composed of them. <a href="#a4b504b0bbdb4909cebdc60855bd6fd6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95d4c56e1e0262813f1d792a7c3a689b">getWinCFISection</a> (MCContext &amp;Context, unsigned *NextWinCFIID, MCSection *MainCFISec, const MCSection *TextSec)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa393c949f47f42880e9be43c46254ffe">encodeSEHRegNum</a> (MCContext &amp;Ctx, MCRegister Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f345912dc87cc1bffdc9ba77c1486c6">targetVersionOrMinimumSupportedOSVersion</a> (const Triple &amp;Target, VersionTuple TargetVersion)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/#a7b22b2a20e7587321d17cb029ea8626e">MCVersionMinType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a756e7237c531f502872667409836888a">getMachoVersionMinLoadCommandType</a> (const Triple &amp;Target)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3979fff418a971520363c40327d25f65">getMachoBuildVersionSupportedOS</a> (const Triple &amp;Target)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a3cdacd46a54ada4abe329c88c7a92504">MachO::PlatformType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e301ba901f8c3ef4e2f13aad44ee1ad">getMachoBuildVersionPlatformType</a> (const Triple &amp;Target)</td>
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

### copyBytesForDefRange() {#a4b504b0bbdb4909cebdc60855bd6fd6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void copyBytesForDefRange (<a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 20 &gt; &amp; BytePrefix, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ac3fd578f133e7ee0210c835b393bca59">codeview::SymbolKind</a> SymKind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; DefRangeHeader)</td>
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

<p>Only call this on endian-specific types like ulittle16_t and little32_t, or structs composed of them.</p>

<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ac10e5da4db3a744be65230314f023f54">llvm::MCStreamer::emitCVDefRangeDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a430e37112215f7ce7208db38075768b6">llvm::MCStreamer::emitCVDefRangeDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a82c73f0d0e0884350e6de0b3928a75e2">llvm::MCStreamer::emitCVDefRangeDirective</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#af444716cb34ad63a956c3d68098af874">llvm::MCStreamer::emitCVDefRangeDirective</a>.</p>

</div>
</div>

### encodeSEHRegNum() {#aa393c949f47f42880e9be43c46254ffe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned encodeSEHRegNum (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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



<p>Definition at line 905 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a1d0c21ad8ad54697f00aab2c37d77e25">llvm::MCStreamer::emitWinCFIPushReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9a30cc0783819b780c3e357162b90aec">llvm::MCStreamer::emitWinCFISaveReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a5755faab671780e6c1abcaa95f05fe0b">llvm::MCStreamer::emitWinCFISaveXMM</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#acd1f092159870d525f916e3296341d92">llvm::MCStreamer::emitWinCFISetFrame</a>.</p>

</div>
</div>

### getMachoBuildVersionPlatformType() {#a9e301ba901f8c3ef4e2f13aad44ee1ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::PlatformType getMachoBuildVersionPlatformType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; Target)</td>
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



<p>Definition at line 1413 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda0824a8c56de913d60c6f55edc0ac3148">llvm::Triple::Darwin</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda600aa0b72f321a0cdf0e4b3f38b9b6c8">llvm::Triple::DriverKit</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdafad6e6763679be1478d9283a7344d243">llvm::Triple::IOS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda690ddf3bb28281cc7afa9c7de4ff4075">llvm::Triple::MacOSX</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda2838cf6df0f09591c50d752d46c4350d">llvm::Triple::TvOS</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda87a3c8454473c64f6d605ebd757759ad">llvm::Triple::WatchOS</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdabb5225659a201976ce2594df579e3623">llvm::Triple::XROS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#aa1789315a3765f97ea5e82e21f4b9e47">llvm::MCStreamer::emitVersionForTarget</a>.</p>

</div>
</div>

### getMachoBuildVersionSupportedOS() {#a3979fff418a971520363c40327d25f65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VersionTuple getMachoBuildVersionSupportedOS (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; Target)</td>
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



<p>Definition at line 1385 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda0824a8c56de913d60c6f55edc0ac3148">llvm::Triple::Darwin</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda600aa0b72f321a0cdf0e4b3f38b9b6c8">llvm::Triple::DriverKit</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdafad6e6763679be1478d9283a7344d243">llvm::Triple::IOS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda690ddf3bb28281cc7afa9c7de4ff4075">llvm::Triple::MacOSX</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda2838cf6df0f09591c50d752d46c4350d">llvm::Triple::TvOS</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda87a3c8454473c64f6d605ebd757759ad">llvm::Triple::WatchOS</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdabb5225659a201976ce2594df579e3623">llvm::Triple::XROS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#aa1789315a3765f97ea5e82e21f4b9e47">llvm::MCStreamer::emitVersionForTarget</a>.</p>

</div>
</div>

### getMachoVersionMinLoadCommandType() {#a756e7237c531f502872667409836888a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCVersionMinType getMachoVersionMinLoadCommandType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; Target)</td>
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



<p>Definition at line 1365 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda0824a8c56de913d60c6f55edc0ac3148">llvm::Triple::Darwin</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdafad6e6763679be1478d9283a7344d243">llvm::Triple::IOS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda690ddf3bb28281cc7afa9c7de4ff4075">llvm::Triple::MacOSX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b22b2a20e7587321d17cb029ea8626ead9e407b6ec006c31f17818a1283f6d3f">llvm::MCVM_IOSVersionMin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b22b2a20e7587321d17cb029ea8626ea386d6f60bcd1993e7d17e07a0af6affb">llvm::MCVM_OSXVersionMin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b22b2a20e7587321d17cb029ea8626eaa7ab690e482966c940af477dcf395dce">llvm::MCVM_TvOSVersionMin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b22b2a20e7587321d17cb029ea8626ea183c1e03234356aae7e6f65d0b0931f4">llvm::MCVM_WatchOSVersionMin</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda2838cf6df0f09591c50d752d46c4350d">llvm::Triple::TvOS</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda87a3c8454473c64f6d605ebd757759ad">llvm::Triple::WatchOS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#aa1789315a3765f97ea5e82e21f4b9e47">llvm::MCStreamer::emitVersionForTarget</a>.</p>

</div>
</div>

### getWinCFISection() {#a95d4c56e1e0262813f1d792a7c3a689b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * getWinCFISection (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Context, unsigned * NextWinCFIID, <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * MainCFISec, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * TextSec)</td>
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



<p>Definition at line 857 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#abb2a5b3cc2301597c2ffed2e4b04f45ead3941c7129f5525831b86bad485c5c84">llvm::COFF::IMAGE_COMDAT_SELECT_ANY</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa86b861e119d7e8b4bf5d9664671667ca">llvm::COFF::IMAGE_SCN_LNK_COMDAT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a28fee3751eb70ba6768349da24ac79d4">llvm::MCStreamer::getAssociatedPDataSection</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7304c7ee4dda7ad7b71afed08c070cd8">llvm::MCStreamer::getAssociatedXDataSection</a>.</p>

</div>
</div>

### targetVersionOrMinimumSupportedOSVersion() {#a8f345912dc87cc1bffdc9ba77c1486c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VersionTuple targetVersionOrMinimumSupportedOSVersion (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; Target, <a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a> TargetVersion)</td>
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



<p>Definition at line 1358 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp">MCStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/versiontuple/#ad07e5841d788dc29bdda972b3f92be6b">llvm::VersionTuple::empty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#aa1789315a3765f97ea5e82e21f4b9e47">llvm::MCStreamer::emitVersionForTarget</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
