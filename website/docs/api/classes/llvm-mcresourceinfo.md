---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcresourceinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MCResourceInfo` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MCResourceInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-h">Target/AMDGPU/AMDGPUMCResourceInfo.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ResourceInfoKind { <a href="#af48e911064e158653df0cd355208c590">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a036e50449cbcf927e271aec60a631d14">MCResourceInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af18c19f635c52afe1ddcfa8b0908de6f">addMaxVGPRCandidate</a> (int32_t candidate)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2c8383dcf4dceabc21a1897570ab76e">addMaxAGPRCandidate</a> (int32_t candidate)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b49c357b7b7adab83211b02a55dca8e">addMaxSGPRCandidate</a> (int32_t candidate)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6fb66900168f71c259a40c4213258ee">getSymbol</a> (StringRef FuncName, ResourceInfoKind RIK, MCContext &amp;OutContext, bool IsLocal)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4df37ccc4bac970ed9da45c24bf04a42">getSymRefExpr</a> (StringRef FuncName, ResourceInfoKind RIK, MCContext &amp;Ctx, bool IsLocal)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8ecde31b2988ffcf2f415e6dfab63cc">reset</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a862c4550519c6358f03989ab5915c65f">finalize</a> (MCContext &amp;OutContext)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdfa9217c601394fde2e02fbbfb5aff4">getMaxVGPRSymbol</a> (MCContext &amp;OutContext)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e13c8211ac78de4ed02bd7facb5c18f">getMaxAGPRSymbol</a> (MCContext &amp;OutContext)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43e26b05f46ee6277cdb509e6e264304">getMaxSGPRSymbol</a> (MCContext &amp;OutContext)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3681fb2c471c1278bfd939456c752f22">gatherResourceInfo</a> (const MachineFunction &amp;MF, const AMDGPUResourceUsageAnalysis::SIFunctionResourceInfo &amp;FRI, MCContext &amp;OutContext)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/amdgpuresourceusageanalysis">AMDGPUResourceUsageAnalysis</a> gathers resource usage on a per-function granularity. <a href="#a3681fb2c471c1278bfd939456c752f22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fa44a1fa346266bc9d287dce014dcfb">createTotalNumVGPRs</a> (const MachineFunction &amp;MF, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeac390246bd74f8e7897e99b30ae2c6f">createTotalNumSGPRs</a> (const MachineFunction &amp;MF, bool hasXnack, MCContext &amp;Ctx)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ea3236ce25bd56781a60e066fdc55ac">assignResourceInfoExpr</a> (int64_t localValue, ResourceInfoKind RIK, AMDGPUMCExpr::VariantKind Kind, const MachineFunction &amp;MF, const SmallVectorImpl&lt; const Function * &gt; &amp;Callees, MCContext &amp;OutContext)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af826946895c5ac191bd1a576ba580e19">assignMaxRegs</a> (MCContext &amp;OutContext)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06078cfdbd5126cfeae1751c7b53c6cb">MaxVGPR</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fadbc65cbd70407192494222c989432">MaxAGPR</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a518e0bad446b212664759a42432b504d">MaxSGPR</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9f9a4112f96522301add2287ee66e43">Finalized</a> = false</td>
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


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-h">AMDGPUMCResourceInfo.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### ResourceInfoKind {#af48e911064e158653df0cd355208c590}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MCResourceInfo::ResourceInfoKind </td>
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
<td class="doxyEnumItemName">RIK_NumVGPR<a id="af48e911064e158653df0cd355208c590a8da10f6cf6332ee63770a2b025ec0137"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RIK_NumAGPR<a id="af48e911064e158653df0cd355208c590a1c2a6e80379270ae20b862a7965b06e2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RIK_NumSGPR<a id="af48e911064e158653df0cd355208c590aefa4ed4642c49f918d0520d91df06308"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RIK_PrivateSegSize<a id="af48e911064e158653df0cd355208c590a100073e901dedc43d53055d3145387ba"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RIK_UsesVCC<a id="af48e911064e158653df0cd355208c590a19b2edc3c20039db0b831e29083f32a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RIK_UsesFlatScratch<a id="af48e911064e158653df0cd355208c590a2211b28e5485598e631dd11904189ece"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RIK_HasDynSizedStack<a id="af48e911064e158653df0cd355208c590a569998460199830dadbec581c57d281c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RIK_HasRecursion<a id="af48e911064e158653df0cd355208c590a0356f9fc433377d29810e057025a9df4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RIK_HasIndirectCall<a id="af48e911064e158653df0cd355208c590ac75093b0903f372c30885a79ffbc88f2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-h">AMDGPUMCResourceInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MCResourceInfo() {#a036e50449cbcf927e271aec60a631d14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCResourceInfo::MCResourceInfo ()</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-h">AMDGPUMCResourceInfo.h</a>.</p>


<p>Referenced by <a href="#ab8ecde31b2988ffcf2f415e6dfab63cc">reset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addMaxAGPRCandidate() {#ac2c8383dcf4dceabc21a1897570ab76e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCResourceInfo::addMaxAGPRCandidate (int32_t candidate)</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-h">AMDGPUMCResourceInfo.h</a>.</p>


<p>Referenced by <a href="#a3681fb2c471c1278bfd939456c752f22">gatherResourceInfo</a>.</p>

</div>
</div>

### addMaxSGPRCandidate() {#a2b49c357b7b7adab83211b02a55dca8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCResourceInfo::addMaxSGPRCandidate (int32_t candidate)</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-h">AMDGPUMCResourceInfo.h</a>.</p>


<p>Referenced by <a href="#a3681fb2c471c1278bfd939456c752f22">gatherResourceInfo</a>.</p>

</div>
</div>

### addMaxVGPRCandidate() {#af18c19f635c52afe1ddcfa8b0908de6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCResourceInfo::addMaxVGPRCandidate (int32_t candidate)</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-h">AMDGPUMCResourceInfo.h</a>.</p>


<p>Referenced by <a href="#a3681fb2c471c1278bfd939456c752f22">gatherResourceInfo</a>.</p>

</div>
</div>

### createTotalNumSGPRs() {#aeac390246bd74f8e7897e99b30ae2c6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * MCResourceInfo::createTotalNumSGPRs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, bool hasXnack, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-h">AMDGPUMCResourceInfo.h</a>, definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-cpp">AMDGPUMCResourceInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a3cbe1086ebf00680e8dc374e07305cfb">llvm::MCBinaryExpr::createAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#a99e0974cd15aab665b6eba448cd94a5f">llvm::AMDGPUMCExpr::createExtraSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a57c7b2b9784361914262eeb0a6f0b18d">llvm::MCSymbol::getName</a>, <a href="#a4df37ccc4bac970ed9da45c24bf04a42">getSymRefExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3ba1af4b9d9faa4a33729bbbecee83d1">llvm::GlobalValue::hasLocalLinkage</a>, <a href="#af48e911064e158653df0cd355208c590aefa4ed4642c49f918d0520d91df06308">RIK_NumSGPR</a>, <a href="#af48e911064e158653df0cd355208c590a2211b28e5485598e631dd11904189ece">RIK_UsesFlatScratch</a> and <a href="#af48e911064e158653df0cd355208c590a19b2edc3c20039db0b831e29083f32a3">RIK_UsesVCC</a>.</p>

</div>
</div>

### createTotalNumVGPRs() {#a6fa44a1fa346266bc9d287dce014dcfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * MCResourceInfo::createTotalNumVGPRs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-h">AMDGPUMCResourceInfo.h</a>, definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-cpp">AMDGPUMCResourceInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#a65eb9f650ce7f4dd73c2961f327f3128">llvm::AMDGPUMCExpr::createTotalNumVGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a57c7b2b9784361914262eeb0a6f0b18d">llvm::MCSymbol::getName</a>, <a href="#a4df37ccc4bac970ed9da45c24bf04a42">getSymRefExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3ba1af4b9d9faa4a33729bbbecee83d1">llvm::GlobalValue::hasLocalLinkage</a>, <a href="#af48e911064e158653df0cd355208c590a1c2a6e80379270ae20b862a7965b06e2">RIK_NumAGPR</a> and <a href="#af48e911064e158653df0cd355208c590a8da10f6cf6332ee63770a2b025ec0137">RIK_NumVGPR</a>.</p>

</div>
</div>

### finalize() {#a862c4550519c6358f03989ab5915c65f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCResourceInfo::finalize (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; OutContext)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-h">AMDGPUMCResourceInfo.h</a>, definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-cpp">AMDGPUMCResourceInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### gatherResourceInfo() {#a3681fb2c471c1278bfd939456c752f22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCResourceInfo::gatherResourceInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/amdgpuresourceusageanalysis/sifunctionresourceinfo">AMDGPUResourceUsageAnalysis::SIFunctionResourceInfo</a> &amp; FRI, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; OutContext)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/structs/llvm/amdgpuresourceusageanalysis">AMDGPUResourceUsageAnalysis</a> gathers resource usage on a per-function granularity.</p>


<p>However, some resource info has to be assigned the call transitive maximum or accumulative. For example, if A calls B and B's VGPR usage exceeds A's, A should be assigned B's VGPR usage. Furthermore, functions with indirect calls should be assigned the module level maximum.</p>


<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-h">AMDGPUMCResourceInfo.h</a>, definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-cpp">AMDGPUMCResourceInfo.cpp</a>.</p>


<p>References <a href="#ac2c8383dcf4dceabc21a1897570ab76e">addMaxAGPRCandidate</a>, <a href="#a2b49c357b7b7adab83211b02a55dca8e">addMaxSGPRCandidate</a>, <a href="#af18c19f635c52afe1ddcfa8b0908de6f">addMaxVGPRCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#ac4e921b9d06cd1d20aa4994fc39ec64eade9b37ace7482eb448727fdbd65a75f0">llvm::AMDGPUMCExpr::AGVK_Max</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#ac4e921b9d06cd1d20aa4994fc39ec64ea5f70392190112d47213e6cc3df8bf8cc">llvm::AMDGPUMCExpr::AGVK_Or</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpuresourceusageanalysis/sifunctionresourceinfo/#adf12c3cdbbcf0fd01e9397a693a6bf8e">llvm::AMDGPUResourceUsageAnalysis::SIFunctionResourceInfo::Callees</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpuresourceusageanalysis/sifunctionresourceinfo/#af3efb2b20e885f6310064a3affb7a296">llvm::AMDGPUResourceUsageAnalysis::SIFunctionResourceInfo::CalleeSegmentSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a3cbe1086ebf00680e8dc374e07305cfb">llvm::MCBinaryExpr::createAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#a245bacdf3c88f5963f1ea0b9cc20ffb0">llvm::AMDGPUMCExpr::createMax</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a5f494edc0a569c7fc9ff4181243be1ed">llvm::Function::getCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="#a5e13c8211ac78de4ed02bd7facb5c18f">getMaxAGPRSymbol</a>, <a href="#a43e26b05f46ee6277cdb509e6e264304">getMaxSGPRSymbol</a>, <a href="#acdfa9217c601394fde2e02fbbfb5aff4">getMaxVGPRSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a57c7b2b9784361914262eeb0a6f0b18d">llvm::MCSymbol::getName</a>, <a href="#ab6fb66900168f71c259a40c4213258ee">getSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a2192a3f25b0bc0505cc168a012038046">llvm::MCSymbol::getVariableValue</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpuresourceusageanalysis/sifunctionresourceinfo/#a7646a5431ba0550b290b5888d0d6898b">llvm::AMDGPUResourceUsageAnalysis::SIFunctionResourceInfo::HasDynamicallySizedStack</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpuresourceusageanalysis/sifunctionresourceinfo/#a9dfea6fbc3e9600bcafa0a2371e9e2de">llvm::AMDGPUResourceUsageAnalysis::SIFunctionResourceInfo::HasIndirectCall</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3ba1af4b9d9faa4a33729bbbecee83d1">llvm::GlobalValue::hasLocalLinkage</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpuresourceusageanalysis/sifunctionresourceinfo/#aeddee414e364d6b8d346964c88b3b50b">llvm::AMDGPUResourceUsageAnalysis::SIFunctionResourceInfo::HasRecursion</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a3c65c76a817d60e322ff750366674a92">llvm::AMDGPU::isEntryFunctionCC</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae066b71f79346e6cf0e978da4656e1bc">llvm::MCExpr::isSymbolUsedInExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a620bf1ce8489b3da259faf0c55a862aa">llvm::MCSymbol::isVariable</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpuresourceusageanalysis/sifunctionresourceinfo/#a9307d03fbda2e54a7b2ecb78bac47019">llvm::AMDGPUResourceUsageAnalysis::SIFunctionResourceInfo::NumAGPR</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpuresourceusageanalysis/sifunctionresourceinfo/#a8a250107696bf3f9bd50f12ed52b937d">llvm::AMDGPUResourceUsageAnalysis::SIFunctionResourceInfo::NumExplicitSGPR</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpuresourceusageanalysis/sifunctionresourceinfo/#ace2f47e698e52d6ee942db8b7196e665">llvm::AMDGPUResourceUsageAnalysis::SIFunctionResourceInfo::NumVGPR</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpuresourceusageanalysis/sifunctionresourceinfo/#a9182e409604c9f69e188aa4580e5d7b1">llvm::AMDGPUResourceUsageAnalysis::SIFunctionResourceInfo::PrivateSegmentSize</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#af48e911064e158653df0cd355208c590a569998460199830dadbec581c57d281c">RIK_HasDynSizedStack</a>, <a href="#af48e911064e158653df0cd355208c590ac75093b0903f372c30885a79ffbc88f2">RIK_HasIndirectCall</a>, <a href="#af48e911064e158653df0cd355208c590a0356f9fc433377d29810e057025a9df4">RIK_HasRecursion</a>, <a href="#af48e911064e158653df0cd355208c590a1c2a6e80379270ae20b862a7965b06e2">RIK_NumAGPR</a>, <a href="#af48e911064e158653df0cd355208c590aefa4ed4642c49f918d0520d91df06308">RIK_NumSGPR</a>, <a href="#af48e911064e158653df0cd355208c590a8da10f6cf6332ee63770a2b025ec0137">RIK_NumVGPR</a>, <a href="#af48e911064e158653df0cd355208c590a100073e901dedc43d53055d3145387ba">RIK_PrivateSegSize</a>, <a href="#af48e911064e158653df0cd355208c590a2211b28e5485598e631dd11904189ece">RIK_UsesFlatScratch</a>, <a href="#af48e911064e158653df0cd355208c590a19b2edc3c20039db0b831e29083f32a3">RIK_UsesVCC</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a7f1486460b5e2da7f4527bbb2da54eff">llvm::MCSymbol::setVariableValue</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpuresourceusageanalysis/sifunctionresourceinfo/#a1ad15d21553e3b179b6b0f78efad4e3a">llvm::AMDGPUResourceUsageAnalysis::SIFunctionResourceInfo::UsesFlatScratch</a> and <a href="/web-llvm/docs/api/structs/llvm/amdgpuresourceusageanalysis/sifunctionresourceinfo/#ab9afb486dfec15a26a2b0b26a9b5302d">llvm::AMDGPUResourceUsageAnalysis::SIFunctionResourceInfo::UsesVCC</a>.</p>

</div>
</div>

### getMaxAGPRSymbol() {#a5e13c8211ac78de4ed02bd7facb5c18f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MCResourceInfo::getMaxAGPRSymbol (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; OutContext)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-h">AMDGPUMCResourceInfo.h</a>, definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-cpp">AMDGPUMCResourceInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ac11eef690074972378846024abbe8722">llvm::MCContext::getOrCreateSymbol</a>.</p>


<p>Referenced by <a href="#a3681fb2c471c1278bfd939456c752f22">gatherResourceInfo</a>.</p>

</div>
</div>

### getMaxSGPRSymbol() {#a43e26b05f46ee6277cdb509e6e264304}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MCResourceInfo::getMaxSGPRSymbol (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; OutContext)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-h">AMDGPUMCResourceInfo.h</a>, definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-cpp">AMDGPUMCResourceInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ac11eef690074972378846024abbe8722">llvm::MCContext::getOrCreateSymbol</a>.</p>


<p>Referenced by <a href="#a3681fb2c471c1278bfd939456c752f22">gatherResourceInfo</a>.</p>

</div>
</div>

### getMaxVGPRSymbol() {#acdfa9217c601394fde2e02fbbfb5aff4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MCResourceInfo::getMaxVGPRSymbol (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; OutContext)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-h">AMDGPUMCResourceInfo.h</a>, definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-cpp">AMDGPUMCResourceInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ac11eef690074972378846024abbe8722">llvm::MCContext::getOrCreateSymbol</a>.</p>


<p>Referenced by <a href="#a3681fb2c471c1278bfd939456c752f22">gatherResourceInfo</a>.</p>

</div>
</div>

### getSymbol() {#ab6fb66900168f71c259a40c4213258ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MCResourceInfo::getSymbol (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FuncName, <a href="#af48e911064e158653df0cd355208c590">ResourceInfoKind</a> RIK, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; OutContext, bool IsLocal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-h">AMDGPUMCResourceInfo.h</a>, definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-cpp">AMDGPUMCResourceInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aa3beac794c4afb5b1fb6d06cb7786587">llvm::MCContext::getAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ac11eef690074972378846024abbe8722">llvm::MCContext::getOrCreateSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a021c993cfff75d122f448141f200673a">llvm::MCAsmInfo::getPrivateGlobalPrefix</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#af48e911064e158653df0cd355208c590a569998460199830dadbec581c57d281c">RIK_HasDynSizedStack</a>, <a href="#af48e911064e158653df0cd355208c590ac75093b0903f372c30885a79ffbc88f2">RIK_HasIndirectCall</a>, <a href="#af48e911064e158653df0cd355208c590a0356f9fc433377d29810e057025a9df4">RIK_HasRecursion</a>, <a href="#af48e911064e158653df0cd355208c590a1c2a6e80379270ae20b862a7965b06e2">RIK_NumAGPR</a>, <a href="#af48e911064e158653df0cd355208c590aefa4ed4642c49f918d0520d91df06308">RIK_NumSGPR</a>, <a href="#af48e911064e158653df0cd355208c590a8da10f6cf6332ee63770a2b025ec0137">RIK_NumVGPR</a>, <a href="#af48e911064e158653df0cd355208c590a100073e901dedc43d53055d3145387ba">RIK_PrivateSegSize</a>, <a href="#af48e911064e158653df0cd355208c590a2211b28e5485598e631dd11904189ece">RIK_UsesFlatScratch</a> and <a href="#af48e911064e158653df0cd355208c590a19b2edc3c20039db0b831e29083f32a3">RIK_UsesVCC</a>.</p>


<p>Referenced by <a href="#a3681fb2c471c1278bfd939456c752f22">gatherResourceInfo</a> and <a href="#a4df37ccc4bac970ed9da45c24bf04a42">getSymRefExpr</a>.</p>

</div>
</div>

### getSymRefExpr() {#a4df37ccc4bac970ed9da45c24bf04a42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * MCResourceInfo::getSymRefExpr (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FuncName, <a href="#af48e911064e158653df0cd355208c590">ResourceInfoKind</a> RIK, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, bool IsLocal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-h">AMDGPUMCResourceInfo.h</a>, definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-cpp">AMDGPUMCResourceInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a> and <a href="#ab6fb66900168f71c259a40c4213258ee">getSymbol</a>.</p>


<p>Referenced by <a href="#aeac390246bd74f8e7897e99b30ae2c6f">createTotalNumSGPRs</a> and <a href="#a6fa44a1fa346266bc9d287dce014dcfb">createTotalNumVGPRs</a>.</p>

</div>
</div>

### reset() {#ab8ecde31b2988ffcf2f415e6dfab63cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCResourceInfo::reset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-h">AMDGPUMCResourceInfo.h</a>, definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-cpp">AMDGPUMCResourceInfo.cpp</a>.</p>


<p>Reference <a href="#a036e50449cbcf927e271aec60a631d14">MCResourceInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### assignMaxRegs() {#af826946895c5ac191bd1a576ba580e19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCResourceInfo::assignMaxRegs (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; OutContext)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-h">AMDGPUMCResourceInfo.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-cpp">AMDGPUMCResourceInfo.cpp</a>.</p>

</div>
</div>

### assignResourceInfoExpr() {#a5ea3236ce25bd56781a60e066fdc55ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCResourceInfo::assignResourceInfoExpr (int64_t localValue, <a href="#af48e911064e158653df0cd355208c590">ResourceInfoKind</a> RIK, <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#ac4e921b9d06cd1d20aa4994fc39ec64e">AMDGPUMCExpr::VariantKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt; &amp; Callees, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; OutContext)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-h">AMDGPUMCResourceInfo.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-cpp">AMDGPUMCResourceInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Finalized {#af9f9a4112f96522301add2287ee66e43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCResourceInfo::Finalized = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-h">AMDGPUMCResourceInfo.h</a>.</p>

</div>
</div>

### MaxAGPR {#a9fadbc65cbd70407192494222c989432}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t llvm::MCResourceInfo::MaxAGPR = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-h">AMDGPUMCResourceInfo.h</a>.</p>

</div>
</div>

### MaxSGPR {#a518e0bad446b212664759a42432b504d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t llvm::MCResourceInfo::MaxSGPR = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-h">AMDGPUMCResourceInfo.h</a>.</p>

</div>
</div>

### MaxVGPR {#a06078cfdbd5126cfeae1751c7b53c6cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t llvm::MCResourceInfo::MaxVGPR = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-h">AMDGPUMCResourceInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-cpp">AMDGPUMCResourceInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcresourceinfo-h">AMDGPUMCResourceInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
