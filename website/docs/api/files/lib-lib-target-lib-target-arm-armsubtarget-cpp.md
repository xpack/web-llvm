---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `ARMSubtarget.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/arm-h">ARM.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcalllowering-h">ARMCallLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-h">ARMFrameLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/arminstrinfo-h">ARMInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlegalizerinfo-h">ARMLegalizerInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armregisterbankinfo-h">ARMRegisterBankInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-h">ARMTargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-h">MCTargetDesc/ARMMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb1framelowering-h">Thumb1FrameLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb1instrinfo-h">Thumb1InstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb2instrinfo-h">Thumb2InstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/instructionselect-h">llvm/CodeGen/GlobalISel/InstructionSelect.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">llvm/CodeGen/MachineFrameInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">llvm/IR/GlobalValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfo-h">llvm/MC/MCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">llvm/MC/MCTargetOptions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/codegen-h">llvm/Support/CodeGen.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">llvm/Target/TargetOptions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/armtargetparser-h">llvm/TargetParser/ARMTargetParser.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
#include "ARMGenSubtargetInfo.inc"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ITMode { <a href="#acd10987f88cf72d75845f32397f768a2">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29aeb362090e8b5d8b19dbc92c4fb0d7">UseFusedMulOps</a>("arm-use-mulops", cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="#acd10987f88cf72d75845f32397f768a2">ITMode</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f57985fa144303082fa7517a52e6db9">IT</a>(cl::desc("IT block support"), cl::Hidden, cl::init(DefaultIT), cl::values(clEnumValN(DefaultIT, "arm-default-it", "Generate any type of IT block"), clEnumValN(RestrictedIT, "arm-restrict-it", "Disallow complex IT blocks")))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65323d3fd11159039f504dde80f10968">ForceFastISel</a>("arm-force-fast-isel", cl::init(false), cl::Hidden)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ForceFastISel - <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the fast-isel, even for subtargets where it is not currently supported (for testing only). <a href="#a65323d3fd11159039f504dde80f10968">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"arm-subtarget"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9edcf2eb5fb8161f71f0b6540ad9cf95">GET_SUBTARGETINFO_TARGET_DESC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7e319f7bba8b140ee2d876cc3f8308b">GET_SUBTARGETINFO_CTOR</a></td>
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

### ITMode {#acd10987f88cf72d75845f32397f768a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum ITMode </td>
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
<td class="doxyEnumItemName">DefaultIT<a id="acd10987f88cf72d75845f32397f768a2ab849f8954237a1de889c7720af9ae6d6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RestrictedIT<a id="acd10987f88cf72d75845f32397f768a2a37501381a8242efe2f26219eead4ef42"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### ForceFastISel {#a65323d3fd11159039f504dde80f10968}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ForceFastISel("arm-force-fast-isel", cl::init(false), cl::Hidden)</td>
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

<p>ForceFastISel - <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the fast-isel, even for subtargets where it is not currently supported (for testing only).</p>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#a02f4499189ec049069fb68de00a7b551">llvm::ARMSubtarget::useFastISel</a>.</p>

</div>
</div>

### IT {#a6f57985fa144303082fa7517a52e6db9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; ITMode &gt; IT(cl::desc("IT block support"), cl::Hidden, cl::init(DefaultIT), cl::values(clEnumValN(DefaultIT, "arm-default-it", "Generate any type of IT block"), clEnumValN(RestrictedIT, "arm-restrict-it", "Disallow complex IT blocks")))</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-simplifycfg-cpp-/switchlookuptable/#a41f4145f819d062ed7c74067ad334808">anonymous{SimplifyCFG.cpp}::SwitchLookupTable::buildLookup</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp/#a36d763333ed81c8ff62e28b20125a95b">computeImportForFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#aea38a34c36c8f1cb37754bd3bd336053">llvm::gsym::FunctionInfo::decode</a>, <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a662a75681b26812d5306f2ba8d38d4a6">llvm::iplist_impl&lt; IntrusiveListT, TraitsT &gt;::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a011d1f22dc53e608a3bd5a1712a37fdf">llvm::iplist_impl&lt; IntrusiveListT, TraitsT &gt;::erase</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#ac6d7cb2af5197dfb40fa54302fbe06d1">findInitTrampoline</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#ab5fa59567e3acc860411770354a1603a">getInsertPointAfterInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/stacklifetime/#ad5ea64f921940edb72d8186f097d549b">llvm::StackLifetime::getLiveRange</a>, <a href="/web-llvm/docs/api/classes/llvm/cachecost/#ae14c5c1bfcf45b9ab5be1911532eca4c">llvm::CacheCost::getLoopCost</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocation/#a78cc51c415c7e64b5efe2c8458fbd35a">llvm::DILocation::getMergedLocation</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a03dd63ac617c1242b7694a4b0ae4ed25">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getShadowTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a70248d7aab4356a949c5365279b7a970">hasCFUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/controlheightreduction-cpp/#a64bba3cf05c8cb1baa848483e7150830">hoistValue</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#afc15ef658764e1532ae80037d5d6ba6d">llvm::MachineBasicBlock::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a0fa38b8fb6064d05758cc49ec3067610">isAtomicRMWLegalIntTy</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#afdcd0a1d482f4048baba27f0bc051411">llvm::ConstantDataSequential::isElementTypeCompatible</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a7ef36c3b9f5334218cf1b3b7e8e33569">isTypeLegalForLookupTable</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a5d896568c18192e090d13f4831e4abb1">llvm::gsym::FunctionInfo::lookup</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits/normalizedtbd-v4-266563df95186142f944822c118e1d06/#af4e0a994d0feae8ef45c2bdb1c16ead2">llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::NormalizedTBD_V4::NormalizedTBD_V4</a>, <a href="/web-llvm/docs/api/classes/llvm/safestack/stacklayout/#a8a4d99268d104c4ff503df7a2d98927a">llvm::safestack::StackLayout::print</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#a5770d604e68e48d1b8f1e7aa4c89a034">anonymous{LowerSwitch.cpp}::ProcessSwitchInst</a>, <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#ad39bc96a220d57843da9f21165013d1b">llvm::iplist_impl&lt; IntrusiveListT, TraitsT &gt;::remove</a>, <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a99db7b74235ded8f74e4e2a5cc6f6209">llvm::iplist_impl&lt; IntrusiveListT, TraitsT &gt;::remove</a>, <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#ad44b3ea3bab37225bb4ea10d08dad594">llvm::iplist_impl&lt; IntrusiveListT, TraitsT &gt;::remove</a>, <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#af4efd5129806447f1b2eebca75e62c60">llvm::iplist_impl&lt; IntrusiveListT, TraitsT &gt;::remove</a>, <a href="/web-llvm/docs/api/classes/llvm/directedgraph/#af3d77f0eb55733fc66d9a8df01deeffb">llvm::DirectedGraph&lt; DDGNode, DDGEdge &gt;::removeNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifycfg-cpp-/switchlookuptable/#a36955f44027693881a174e8d3f1d3854">anonymous{SimplifyCFG.cpp}::SwitchLookupTable::SwitchLookupTable</a> and <a href="/web-llvm/docs/api/classes/anonymous-simplifycfg-cpp-/switchlookuptable/#a19f38e85c02e7293ac20cdfc25f776df">anonymous{SimplifyCFG.cpp}::SwitchLookupTable::wouldFitInRegister</a>.</p>

</div>
</div>

### UseFusedMulOps {#a29aeb362090e8b5d8b19dbc92c4fb0d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; UseFusedMulOps("arm-use-mulops", cl::init(true), cl::Hidden)</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#a16350880c9e7c3b3c6f960644b0abd6c">llvm::ARMSubtarget::ARMSubtarget</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"arm-subtarget"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>

</div>
</div>

### GET\_SUBTARGETINFO\_CTOR {#aa7e319f7bba8b140ee2d876cc3f8308b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_SUBTARGETINFO_CTOR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>

</div>
</div>

### GET\_SUBTARGETINFO\_TARGET\_DESC {#a9edcf2eb5fb8161f71f0b6540ad9cf95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_SUBTARGETINFO_TARGET_DESC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
