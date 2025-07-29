---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/cskyconstantpool
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CSKYConstantPool` Class



## Declaration

<div class="doxyDeclaration">
class llvm::CSKYConstantPool { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskytargetstreamer-h">Target/CSKY/MCTargetDesc/CSKYTargetStreamer.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afed22d68ebc43027d28f2bb4cd7070a5">EntryVecTy</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/constantpoolentry">ConstantPoolEntry</a>, 4 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a026c38fbfb6e0f42c15a4fd4d7a915f2">CSKYConstantPool</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91eb97e39eb4e9b4befd1914be362617">addEntry</a> (MCStreamer &amp;Streamer, const MCExpr *Value, unsigned Size, SMLoc Loc, const MCExpr *AdjustExpr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a504a7be63300c2c61d79be758524a433">emitAll</a> (MCStreamer &amp;Streamer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f75c8784fe9decc62e9a90e0d266b3f">empty</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a033a9c516df697809b724bae1f94e155">clearCache</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">EntryVecTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af84941cdc13e1fda58a5e64f073bbcf1">Entries</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; int64_t, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr">MCSymbolRefExpr</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af19cbd14346de97cdcf56f6966b5bec3">CachedEntries</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd5e048f14062ebfb23a33fbaeadf19f">CurrentSection</a> = nullptr</td>
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


<p>Definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskytargetstreamer-h">CSKYTargetStreamer.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### EntryVecTy {#afed22d68ebc43027d28f2bb4cd7070a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::CSKYConstantPool::EntryVecTy =  SmallVector&lt;ConstantPoolEntry, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskytargetstreamer-h">CSKYTargetStreamer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### CSKYConstantPool() {#a026c38fbfb6e0f42c15a4fd4d7a915f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CSKYConstantPool::CSKYConstantPool ()</td>
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



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskytargetstreamer-h">CSKYTargetStreamer.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addEntry() {#a91eb97e39eb4e9b4befd1914be362617}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * CSKYConstantPool::addEntry (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Streamer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value, unsigned Size, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * AdjustExpr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskytargetstreamer-h">CSKYTargetStreamer.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskytargetstreamer-cpp">CSKYTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcexpr/#a518604e41db2d171b48aca08cf75f8c1">llvm::CSKYMCExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#af766134165065939f49fb0662c246f66">llvm::MCBinaryExpr::createSub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ae1b3cf074436ef5b527071540e13bd58">llvm::MCStreamer::getCurrentSectionOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcexpr/#ae2988ac0d4593937162372c8b40a7d54">llvm::CSKYMCExpr::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcexpr/#a3e7002ae048cb2d37863aabccc80c3a8">llvm::CSKYMCExpr::getSubExpr</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### clearCache() {#a033a9c516df697809b724bae1f94e155}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CSKYConstantPool::clearCache ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskytargetstreamer-h">CSKYTargetStreamer.h</a>, definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskytargetstreamer-cpp">CSKYTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitAll() {#a504a7be63300c2c61d79be758524a433}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CSKYConstantPool::emitAll (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Streamer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskytargetstreamer-h">CSKYTargetStreamer.h</a>, definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskytargetstreamer-cpp">CSKYTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#aa1dcf543ae68792dfaabeaa31f4ddef2">llvm::MCStreamer::emitCodeAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ab93cbe98a85c26f4749096e5fecca2f5">llvm::MCStreamer::emitDataRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a822ae1a4f19b7b00a297a100749f9b8a">llvm::MCStreamer::emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7833630c617e5943c0a41755f5d4bdcf">llvm::MCStreamer::emitValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#afbcf25f6a20ef3f5197a782bf7e55d55">llvm::MCContext::getSubtargetInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a515cb4eba75abc2f0e9dbfffb0137008a05d6258eaccbe86ca4c18e36910fda79">llvm::MCDR_DataRegion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a515cb4eba75abc2f0e9dbfffb0137008a0178c9475f859cfd8a0f552b8e22f412">llvm::MCDR_DataRegionEnd</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ac4f84451dc4abc997c960d484953b1d2">llvm::MCStreamer::switchSection</a>.</p>

</div>
</div>

### empty() {#a7f75c8784fe9decc62e9a90e0d266b3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CSKYConstantPool::empty ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskytargetstreamer-h">CSKYTargetStreamer.h</a>, definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskytargetstreamer-cpp">CSKYTargetStreamer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CachedEntries {#af19cbd14346de97cdcf56f6966b5bec3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;int64_t, const MCSymbolRefExpr *&gt; llvm::CSKYConstantPool::CachedEntries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskytargetstreamer-h">CSKYTargetStreamer.h</a>.</p>

</div>
</div>

### CurrentSection {#afd5e048f14062ebfb23a33fbaeadf19f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::CSKYConstantPool::CurrentSection = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskytargetstreamer-h">CSKYTargetStreamer.h</a>.</p>

</div>
</div>

### Entries {#af84941cdc13e1fda58a5e64f073bbcf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EntryVecTy llvm::CSKYConstantPool::Entries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskytargetstreamer-h">CSKYTargetStreamer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskytargetstreamer-cpp">CSKYTargetStreamer.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskytargetstreamer-h">CSKYTargetStreamer.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
