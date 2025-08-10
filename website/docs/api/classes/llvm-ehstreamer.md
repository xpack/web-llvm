---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ehstreamer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `EHStreamer` Class

<p>Emits exception handling directives. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::EHStreamer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-h">CodeGen/AsmPrinter/EHStreamer.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmprinterhandler">AsmPrinterHandler</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collects and handles <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> objects required to build debug or EH information. <a href="/web-llvm/docs/api/classes/llvm/asmprinterhandler/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aixexception">AIXException</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/armexception">ARMException</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfcfiexception">DwarfCFIException</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/wasmexception">WasmException</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/winexception">WinException</a></td>
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

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8263fed2d1a8589d4124ec53fdc8f26b">RangeMapType</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, <a href="/web-llvm/docs/api/structs/llvm/ehstreamer/padrange">PadRange</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae951249a56bafbb7b57c4f571f9b4a3a">EHStreamer</a> (AsmPrinter *A)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a587c61624bc329ab1c8d2317f19e1c08">~EHStreamer</a> () override</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a093b0a333833131b3fb12fb62f915bf1">computeActionsTable</a> (const SmallVectorImpl&lt; const LandingPadInfo * &gt; &amp;LandingPads, SmallVectorImpl&lt; ActionEntry &gt; &amp;Actions, SmallVectorImpl&lt; unsigned &gt; &amp;FirstActions)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the actions table and gather the first action index for each landing pad site. <a href="#a093b0a333833131b3fb12fb62f915bf1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f1ea57bc156f9e309b4049bc1d10e17">computePadMap</a> (const SmallVectorImpl&lt; const LandingPadInfo * &gt; &amp;LandingPads, RangeMapType &amp;PadMap)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49694eb08442bb35020b9d8dfad6d7e5">computeCallSiteTable</a> (SmallVectorImpl&lt; CallSiteEntry &gt; &amp;CallSites, SmallVectorImpl&lt; CallSiteRange &gt; &amp;CallSiteRanges, const SmallVectorImpl&lt; const LandingPadInfo * &gt; &amp;LandingPads, const SmallVectorImpl&lt; unsigned &gt; &amp;FirstActions)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the call-site table and the call-site ranges. <a href="#a49694eb08442bb35020b9d8dfad6d7e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a420cc4a7a63b33a52659768b133b5f1b">emitExceptionTable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit landing pads and actions. <a href="#a420cc4a7a63b33a52659768b133b5f1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0693fd10cd699cd25acfe38350e47577">emitTypeInfos</a> (unsigned TTypeEncoding, MCSymbol *TTBaseLabel)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a346d40526a13ec03f632cd9fd1b51ca9">Asm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> of directive emission. <a href="#a346d40526a13ec03f632cd9fd1b51ca9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cb51f746d76c12843c38bba07e25377">MMI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collected machine module information. <a href="#a8cb51f746d76c12843c38bba07e25377">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add3aa627d6c1eb31f0b6563af39b8b64">callToNoUnwindFunction</a> (const MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return ‘true` if this is a call to a function marked ‘nounwind`. <a href="#add3aa627d6c1eb31f0b6563af39b8b64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5934c1c4bc925089b02df1024ace20fd">sharedTypeIDs</a> (const LandingPadInfo *L, const LandingPadInfo *R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>How many leading type ids two landing pads have in common. <a href="#a5934c1c4bc925089b02df1024ace20fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53e615f9a2ef0dec49685674e388c6d2">isFilterEHSelector</a> (int Selector)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a588e43cc9f4e6e19f0b10e9e65518f01">isCleanupEHSelector</a> (int Selector)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6de56377798490410db5d499f851ffcc">isCatchEHSelector</a> (int Selector)</td>
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

## Description {#details}

<p>Emits exception handling directives.</p>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-h">EHStreamer.h</a>.</p>


<div class="doxySectionDef">

## Protected Member Typedefs

### RangeMapType {#a8263fed2d1a8589d4124ec53fdc8f26b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::EHStreamer::RangeMapType =  DenseMap&lt;MCSymbol *, PadRange&gt;</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-h">EHStreamer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### EHStreamer() {#ae951249a56bafbb7b57c4f571f9b4a3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EHStreamer::EHStreamer (<a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> * A)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-h">EHStreamer.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-cpp">EHStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a346d40526a13ec03f632cd9fd1b51ca9">Asm</a> and <a href="#a8cb51f746d76c12843c38bba07e25377">MMI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aixexception/#ac84eccdb64e1cb2f2fdfd32afbcb1353">llvm::AIXException::AIXException</a>, <a href="/web-llvm/docs/api/classes/llvm/armexception/#a8f5282c5b11cd8d515249b8cd5dc06cb">llvm::ARMException::ARMException</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcfiexception/#ae7b960a20f8d91ff62d697bae1a4d921">llvm::DwarfCFIException::DwarfCFIException</a>, <a href="/web-llvm/docs/api/classes/llvm/wasmexception/#aef95e7cb1b029601fa05185d266b0474">llvm::WasmException::WasmException</a> and <a href="/web-llvm/docs/api/classes/llvm/winexception/#a9c131e14aaffab522028a174694b29ad">llvm::WinException::WinException</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~EHStreamer() {#a587c61624bc329ab1c8d2317f19e1c08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EHStreamer::~EHStreamer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-h">EHStreamer.h</a>.</p>


<p>References <a href="#add3aa627d6c1eb31f0b6563af39b8b64">callToNoUnwindFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### computeActionsTable() {#a093b0a333833131b3fb12fb62f915bf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void EHStreamer::computeActionsTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/landingpadinfo">LandingPadInfo</a> * &gt; &amp; LandingPads, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/ehstreamer/actionentry">ActionEntry</a> &gt; &amp; Actions, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; FirstActions)</td>
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

<p>Compute the actions table and gather the first action index for each landing pad site.</p>

<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-h">EHStreamer.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-cpp">EHStreamer.cpp</a>.</p>


<p>References <a href="#a346d40526a13ec03f632cd9fd1b51ca9">Asm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afc68cb8d27a815bcc3e86fd6c53df3dd">llvm::getSLEB128Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa02a1d8fb0f561ab81f4a2570db7dc28">llvm::getULEB128Size</a>, <a href="#a53e615f9a2ef0dec49685674e388c6d2">isFilterEHSelector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>, <a href="#a5934c1c4bc925089b02df1024ace20fd">sharedTypeIDs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/structs/llvm/landingpadinfo/#af8df3c441f1b6d7b8606a1604d5c29e3">llvm::LandingPadInfo::TypeIds</a>.</p>


<p>Referenced by <a href="#a420cc4a7a63b33a52659768b133b5f1b">emitExceptionTable</a>.</p>

</div>
</div>

### computeCallSiteTable() {#a49694eb08442bb35020b9d8dfad6d7e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void EHStreamer::computeCallSiteTable (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/ehstreamer/callsiteentry">CallSiteEntry</a> &gt; &amp; CallSites, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/ehstreamer/callsiterange">CallSiteRange</a> &gt; &amp; CallSiteRanges, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/landingpadinfo">LandingPadInfo</a> * &gt; &amp; LandingPads, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; FirstActions)</td>
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

<p>Compute the call-site table and the call-site ranges.</p>


<p>Compute the call-site table.</p>


<p>The entry for an invoke has a try-range containing the call, a non-zero landing pad and an appropriate action. The entry for an ordinary call has a try-range containing the call and zero for the landing pad and the action. Calls marked 'nounwind' have no entry and must not be contained in the try-range of any entry - they form gaps in the table. Entries must be ordered by try-range address. CallSiteRanges vector is only populated for Itanium exception handling.</p>


<p>The entry for an invoke has a try-range containing the call, a non-zero landing pad, and an appropriate action. The entry for an ordinary call has a try-range containing the call and zero for the landing pad and the action. Calls marked 'nounwind' have no entry and must not be contained in the try-range of any entry - they form gaps in the table. Entries must be ordered by try-range address.</p>


<p>Call-sites are split into one or more call-site ranges associated with different sections of the function.</p>


<ul class="doxyList ">
<li>Without -basic-block-sections, all call-sites are grouped into one call-site-range corresponding to the function section.</li>
<li>With -basic-block-sections, one call-site range is created for each section, with its FragmentBeginLabel and FragmentEndLabel respectively</li>
</ul>

<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-h">EHStreamer.h</a>, definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-cpp">EHStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/ehstreamer/callsiteentry/#aa6505d626d005463a5a85492da38cc28">llvm::EHStreamer::CallSiteEntry::Action</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84a7e6bb0931a72759d39514aa924b420bc">llvm::AIX</a>, <a href="#a346d40526a13ec03f632cd9fd1b51ca9">Asm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/structs/llvm/landingpadinfo/#af2a11ab96d84007873d7803f2df9e881">llvm::LandingPadInfo::BeginLabels</a>, <a href="#add3aa627d6c1eb31f0b6563af39b8b64">callToNoUnwindFunction</a>, <a href="#a1f1ea57bc156f9e309b4049bc1d10e17">computePadMap</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/structs/llvm/ehstreamer/callsiteentry/#ab4e49554456434e3732647a566d0d6fe">llvm::EHStreamer::CallSiteEntry::EndLabel</a>, <a href="/web-llvm/docs/api/structs/llvm/landingpadinfo/#a0c7386f43dd7813531d1c0498bc0194e">llvm::LandingPadInfo::EndLabels</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/structs/llvm/landingpadinfo/#a1197e6ef704b54459dcb2586cf4d5ba2">llvm::LandingPadInfo::LandingPadLabel</a>, <a href="/web-llvm/docs/api/structs/llvm/ehstreamer/callsiteentry/#a4f438afdc653ceeb2fcd6ade380a5fff">llvm::EHStreamer::CallSiteEntry::LPad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84a0f60fd9b862dff366e18e32c6d98d96b">llvm::SjLj</a>.</p>


<p>Referenced by <a href="#a420cc4a7a63b33a52659768b133b5f1b">emitExceptionTable</a>.</p>

</div>
</div>

### computePadMap() {#a1f1ea57bc156f9e309b4049bc1d10e17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void EHStreamer::computePadMap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/landingpadinfo">LandingPadInfo</a> * &gt; &amp; LandingPads, <a href="#a8263fed2d1a8589d4124ec53fdc8f26b">RangeMapType</a> &amp; PadMap)</td>
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



<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-h">EHStreamer.h</a>, definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-cpp">EHStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/landingpadinfo/#af2a11ab96d84007873d7803f2df9e881">llvm::LandingPadInfo::BeginLabels</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a53408c95a7bfb5443b43fb2134c3eb23">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a2899e74730516967f04d81966bb4f881">llvm::MCSymbol::isDefined</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#a49694eb08442bb35020b9d8dfad6d7e5">computeCallSiteTable</a>.</p>

</div>
</div>

### emitExceptionTable() {#a420cc4a7a63b33a52659768b133b5f1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * EHStreamer::emitExceptionTable ()</td>
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

<p>Emit landing pads and actions.</p>


<p>The general organization of the table is complex, but the basic concepts are easy. First there is a header which describes the location and organization of the three components that follow.</p>


<ol class="doxyList" type="1">
<li>The landing pad site information describes the range of code covered by the try. In our case it's an accumulation of the ranges covered by the invokes in the try. There is also a reference to the landing pad that handles the exception once processed. Finally an index into the actions table.</li>
<li>The action table, in our case, is composed of pairs of type ids and next action offset. Starting with the action index from the landing pad site, each type Id is checked for a match to the current exception. If it matches then the exception and type id are passed on to the landing pad. Otherwise the next action is looked up. This chain is terminated with a next action of zero. If no type id is found the frame is unwound and handling continues.</li>
<li><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> id table contains references to all the C++ typeinfo for all catches in the function. This tables is reversed indexed base 1.</li>
</ol>

<p>Returns the starting symbol of an exception table.</p>


<p>The general organization of the table is complex, but the basic concepts are easy. First there is a header which describes the location and organization of the three components that follow.</p>


<ol class="doxyList" type="1">
<li>The landing pad site information describes the range of code covered by the try. In our case it's an accumulation of the ranges covered by the invokes in the try. There is also a reference to the landing pad that handles the exception once processed. Finally an index into the actions table.</li>
<li>The action table, in our case, is composed of pairs of type IDs and next action offset. Starting with the action index from the landing pad site, each type <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> is checked for a match to the current exception. If it matches then the exception and type id are passed on to the landing pad. Otherwise the next action is looked up. This chain is terminated with a next action of zero. If no type id is found then the frame is unwound and handling continues.</li>
<li><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> table contains references to all the C++ typeinfo for all catches in the function. This tables is reverse indexed base 1.</li>
</ol>

<p>Returns the starting symbol of an exception table.</p>


<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-h">EHStreamer.h</a>, definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-cpp">EHStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/ehstreamer/callsiteentry/#aa6505d626d005463a5a85492da38cc28">llvm::EHStreamer::CallSiteEntry::Action</a>, <a href="#a346d40526a13ec03f632cd9fd1b51ca9">Asm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/structs/llvm/ehstreamer/callsiteentry/#a345bd76360ebfd1fb6b1f7af07a85d6b">llvm::EHStreamer::CallSiteEntry::BeginLabel</a>, <a href="/web-llvm/docs/api/structs/llvm/ehstreamer/callsiterange/#a63037668bfef08c9f4e41b7df8283645">llvm::EHStreamer::CallSiteRange::CallSiteBeginIdx</a>, <a href="/web-llvm/docs/api/structs/llvm/ehstreamer/callsiterange/#a0c9f8892aca6d8e9f51845fc0e0ff92f">llvm::EHStreamer::CallSiteRange::CallSiteEndIdx</a>, <a href="#a093b0a333833131b3fb12fb62f915bf1">computeActionsTable</a>, <a href="#a49694eb08442bb35020b9d8dfad6d7e5">computeCallSiteTable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#af766134165065939f49fb0662c246f66">llvm::MCBinaryExpr::createSub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255ab8bb265a153372d87860f6a33d858f3e">llvm::dwarf::DW_EH_PE_absptr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255af88641d07cb5fdb688ad0d4e78314222">llvm::dwarf::DW_EH_PE_omit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255a18cb02c6dc96569494f65b82ab70487b">llvm::dwarf::DW_EH_PE_pcrel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255abfafdba601fd5cab55113f2cdb96c033">llvm::dwarf::DW_EH_PE_udata4</a>, <a href="#a0693fd10cd699cd25acfe38350e47577">emitTypeInfos</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/structs/llvm/ehstreamer/callsiteentry/#ab4e49554456434e3732647a566d0d6fe">llvm::EHStreamer::CallSiteEntry::EndLabel</a>, <a href="/web-llvm/docs/api/structs/llvm/ehstreamer/callsiterange/#ac721d87b73bce0475fb86c761422eb69">llvm::EHStreamer::CallSiteRange::FragmentBeginLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a6b69bd34ce0b70bf055291bc9533dac1">llvm::MachineFunction::getFilterIds</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aa3fd81545fc9f10418752ee043f8645f">llvm::MachineFunction::getLandingPads</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a57c7b2b9784361914262eeb0a6f0b18d">llvm::MCSymbol::getName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afc68cb8d27a815bcc3e86fd6c53df3dd">llvm::getSLEB128Size</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a6de7ce9849875fbf2121a30b4d722455">llvm::MachineFunction::getTypeInfos</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa02a1d8fb0f561ab81f4a2570db7dc28">llvm::getULEB128Size</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/structs/llvm/landingpadinfo/#a1197e6ef704b54459dcb2586cf4d5ba2">llvm::LandingPadInfo::LandingPadLabel</a>, <a href="/web-llvm/docs/api/structs/llvm/ehstreamer/callsiteentry/#a4f438afdc653ceeb2fcd6ade380a5fff">llvm::EHStreamer::CallSiteEntry::LPad</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84a0f60fd9b862dff366e18e32c6d98d96b">llvm::SjLj</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84af93da81fd23e2eeaf8de29b04bb2399f">llvm::Wasm</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aixexception/#a1e6ef18a51de2a6db89efe13415ccb32">llvm::AIXException::endFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/armexception/#aabdec7bf5c7d63c648b278d130aca3c2">llvm::ARMException::endFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcfiexception/#a9426a42a3f02c0367711fb8f3ebbb297">llvm::DwarfCFIException::endFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/wasmexception/#ae3f7a2c3431323c5e22c2c175ebef9cb">llvm::WasmException::endFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/winexception/#a10a2af29c117a6bab2aaecaefb17f4d8">llvm::WinException::endFunction</a>.</p>

</div>
</div>

### emitTypeInfos() {#a0693fd10cd699cd25acfe38350e47577}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void EHStreamer::emitTypeInfos (unsigned TTypeEncoding, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * TTBaseLabel)</td>
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



<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-h">EHStreamer.h</a>, definition at line 809 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-cpp">EHStreamer.cpp</a>.</p>


<p>References <a href="#a346d40526a13ec03f632cd9fd1b51ca9">Asm</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a6b69bd34ce0b70bf055291bc9533dac1">llvm::MachineFunction::getFilterIds</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a6de7ce9849875fbf2121a30b4d722455">llvm::MachineFunction::getTypeInfos</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a53e615f9a2ef0dec49685674e388c6d2">isFilterEHSelector</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>.</p>


<p>Referenced by <a href="#a420cc4a7a63b33a52659768b133b5f1b">emitExceptionTable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Asm {#a346d40526a13ec03f632cd9fd1b51ca9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmPrinter* llvm::EHStreamer::Asm</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> of directive emission.</p>

<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-h">EHStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcfiexception/#a4a39b36e2558580b82448046a957b229">llvm::DwarfCFIException::beginBasicBlockSection</a>, <a href="/web-llvm/docs/api/classes/llvm/winexception/#a404abd4e71fcd8ee5d5b0277163dda55">llvm::WinException::beginFunclet</a>, <a href="/web-llvm/docs/api/classes/llvm/armexception/#ad22476d7463665ca4c25d7fde2824398">llvm::ARMException::beginFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcfiexception/#af2d29f19a7e1b49d4ecf82154691a33d">llvm::DwarfCFIException::beginFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/winexception/#aeaa5422d8ee3dd96aca4513a89a94035">llvm::WinException::beginFunction</a>, <a href="#a093b0a333833131b3fb12fb62f915bf1">computeActionsTable</a>, <a href="#a49694eb08442bb35020b9d8dfad6d7e5">computeCallSiteTable</a>, <a href="/web-llvm/docs/api/classes/llvm/wasmexception/#a8db890ae03cb072b7198ebcc5d52028b">llvm::WasmException::computeCallSiteTable</a>, <a href="#ae951249a56bafbb7b57c4f571f9b4a3a">EHStreamer</a>, <a href="#a420cc4a7a63b33a52659768b133b5f1b">emitExceptionTable</a>, <a href="#a0693fd10cd699cd25acfe38350e47577">emitTypeInfos</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcfiexception/#a43ad56f21d39d07911749e59241bffd3">llvm::DwarfCFIException::endBasicBlockSection</a>, <a href="/web-llvm/docs/api/classes/llvm/winexception/#ad926330cb107f609d6bdbedb07980e79">llvm::WinException::endFunclet</a>, <a href="/web-llvm/docs/api/classes/llvm/aixexception/#a1e6ef18a51de2a6db89efe13415ccb32">llvm::AIXException::endFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/armexception/#aabdec7bf5c7d63c648b278d130aca3c2">llvm::ARMException::endFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/wasmexception/#ae3f7a2c3431323c5e22c2c175ebef9cb">llvm::WasmException::endFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/winexception/#a10a2af29c117a6bab2aaecaefb17f4d8">llvm::WinException::endFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcfiexception/#a96fc5ffe2ecf42de68fc799201ad72d7">llvm::DwarfCFIException::endModule</a>, <a href="/web-llvm/docs/api/classes/llvm/wasmexception/#ab671a798b9580f337321bc4a8523fe25">llvm::WasmException::endModule</a>, <a href="/web-llvm/docs/api/classes/llvm/winexception/#a83914a214e61b299cd1a8ee9a7eade71">llvm::WinException::endModule</a>, <a href="/web-llvm/docs/api/classes/llvm/armexception/#ac30ae0f84b1d66394277e9b0d14dcf91">llvm::ARMException::markFunctionEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/winexception/#a2b2d68aa2cdbb373f491a58dc2a9aed1">llvm::WinException::markFunctionEnd</a> and <a href="/web-llvm/docs/api/classes/llvm/winexception/#a9c131e14aaffab522028a174694b29ad">llvm::WinException::WinException</a>.</p>

</div>
</div>

### MMI {#a8cb51f746d76c12843c38bba07e25377}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineModuleInfo* llvm::EHStreamer::MMI</td>
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

<p>Collected machine module information.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-h">EHStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcfiexception/#a4a39b36e2558580b82448046a957b229">llvm::DwarfCFIException::beginBasicBlockSection</a>, <a href="/web-llvm/docs/api/classes/llvm/winexception/#a404abd4e71fcd8ee5d5b0277163dda55">llvm::WinException::beginFunclet</a>, <a href="#ae951249a56bafbb7b57c4f571f9b4a3a">EHStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/winexception/#a83914a214e61b299cd1a8ee9a7eade71">llvm::WinException::endModule</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### callToNoUnwindFunction() {#add3aa627d6c1eb31f0b6563af39b8b64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool EHStreamer::callToNoUnwindFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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

<p>Return ‘true` if this is a call to a function marked ‘nounwind`.</p>


<p>Return ‘false` otherwise.</p>


<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-h">EHStreamer.h</a>, definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-cpp">EHStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a49694eb08442bb35020b9d8dfad6d7e5">computeCallSiteTable</a> and <a href="#a587c61624bc329ab1c8d2317f19e1c08">~EHStreamer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### isCatchEHSelector() {#a6de56377798490410db5d499f851ffcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EHStreamer::isCatchEHSelector (int Selector)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-h">EHStreamer.h</a>.</p>

</div>
</div>

### isCleanupEHSelector() {#a588e43cc9f4e6e19f0b10e9e65518f01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EHStreamer::isCleanupEHSelector (int Selector)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-h">EHStreamer.h</a>.</p>

</div>
</div>

### isFilterEHSelector() {#a53e615f9a2ef0dec49685674e388c6d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EHStreamer::isFilterEHSelector (int Selector)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-h">EHStreamer.h</a>.</p>


<p>Referenced by <a href="#a093b0a333833131b3fb12fb62f915bf1">computeActionsTable</a> and <a href="#a0693fd10cd699cd25acfe38350e47577">emitTypeInfos</a>.</p>

</div>
</div>

### sharedTypeIDs() {#a5934c1c4bc925089b02df1024ace20fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned EHStreamer::sharedTypeIDs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/landingpadinfo">LandingPadInfo</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/landingpadinfo">LandingPadInfo</a> * R)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>How many leading type ids two landing pads have in common.</p>

<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-h">EHStreamer.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-cpp">EHStreamer.cpp</a>.</p>


<p>Referenced by <a href="#a093b0a333833131b3fb12fb62f915bf1">computeActionsTable</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-cpp">EHStreamer.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-h">EHStreamer.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
