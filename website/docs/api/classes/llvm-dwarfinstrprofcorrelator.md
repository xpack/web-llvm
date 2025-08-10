---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarfinstrprofcorrelator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DwarfInstrProfCorrelator` Class Template

<p><a href="/web-llvm/docs/api/classes/llvm/dwarfinstrprofcorrelator">DwarfInstrProfCorrelator</a> - A child of <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelatorimpl">InstrProfCorrelatorImpl</a> that takes DWARF debug info as input to correlate profiles. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class IntPtrT&gt;
class llvm::DwarfInstrProfCorrelator&lt;IntPtrT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">llvm/ProfileData/InstrProfCorrelator.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelatorimpl">InstrProfCorrelatorImpl&lt;IntPtrT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelatorimpl">InstrProfCorrelatorImpl</a> - A child of <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator">InstrProfCorrelator</a> with a template pointer type so that the ProfileData vector can be materialized. <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelatorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntPtrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a5c0d4ad038bb0679b8e58456ff7e21e2">DwarfInstrProfCorrelator</a> (std::unique_ptr&lt; DWARFContext &gt; DICtx, std::unique_ptr&lt; InstrProfCorrelator::Context &gt; Ctx)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntPtrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac49e751cd44b4fa4ad37170724b2c64b">getLocation</a> (const DWARFDie &amp;Die) const -&gt; std::optional&lt; uint64_t &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the address of the object that the provided <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> symbolizes. <a href="#ac49e751cd44b4fa4ad37170724b2c64b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntPtrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a390b10ea2fb74f707589e9c5d66ab50d">correlateProfileDataImpl</a> (int MaxWarnings, InstrProfCorrelator::CorrelationData *Data=nullptr) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterate over DWARF DIEs to find those that symbolize instrumentation probes and construct the ProfileData vector and Names string. <a href="#a390b10ea2fb74f707589e9c5d66ab50d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntPtrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa4ced264efa6274211ad2560508deee6">correlateProfileNameImpl</a> () override</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntPtrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aafccf6a02c29f43b1ab293366e80e755">DICtx</a></td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntPtrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a83a64b3082a2c3936791f45fe652540b">isDIEOfProbe</a> (const DWARFDie &amp;Die)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the provided <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> symbolizes an instrumentation probe symbol. <a href="#a83a64b3082a2c3936791f45fe652540b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/dwarfinstrprofcorrelator">DwarfInstrProfCorrelator</a> - A child of <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelatorimpl">InstrProfCorrelatorImpl</a> that takes DWARF debug info as input to correlate profiles.</p>

<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DwarfInstrProfCorrelator() {#a5c0d4ad038bb0679b8e58456ff7e21e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntPtrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DwarfInstrProfCorrelator&lt; IntPtrT &gt;::DwarfInstrProfCorrelator (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> &gt; DICtx, std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/instrprofcorrelator/context">InstrProfCorrelator::Context</a> &gt; Ctx)</td>
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



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator/#ac9e9fa2e8b9f1243b2f9b970dc245bef">llvm::InstrProfCorrelator::Ctx</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelatorimpl/#a9110dae8cefc94bca7e5f15b038b2d6a">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::InstrProfCorrelatorImpl</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### correlateProfileDataImpl() {#a390b10ea2fb74f707589e9c5d66ab50d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntPtrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfInstrProfCorrelator::correlateProfileDataImpl (int MaxWarnings, <a href="/web-llvm/docs/api/structs/llvm/instrprofcorrelator/correlationdata">InstrProfCorrelator::CorrelationData</a> * Data=nullptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Iterate over DWARF DIEs to find those that symbolize instrumentation probes and construct the ProfileData vector and Names string.</p>


<p>Here is some example DWARF for an instrumentation probe we are looking for:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">DW_TAG_subprogram</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">DW_AT_low_pc  (0x0000000000000000)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">DW_AT_high_pc (0x0000000000000014)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">DW_AT_name  (</span><span class="doxyHighlightStringLiteral">"foo"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  DW_TAG_variable</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    DW_AT_name  (</span><span class="doxyHighlightStringLiteral">"__profc_foo"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    DW_AT_location  (DW_OP_addr 0x0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    DW_TAG_LLVM_annotation</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      DW_AT_name  (</span><span class="doxyHighlightStringLiteral">"Function Name"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      DW_AT_const_value (</span><span class="doxyHighlightStringLiteral">"foo"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    DW_TAG_LLVM_annotation</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      DW_AT_name  (</span><span class="doxyHighlightStringLiteral">"CFG Hash"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      DW_AT_const_value (12345678)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    DW_TAG_LLVM_annotation</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      DW_AT_name  (</span><span class="doxyHighlightStringLiteral">"Num Counters"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      DW_AT_const_value (2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    NULL</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  NULL</span></span></div>

</div>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">MaxWarnings</td>
<td class="doxyParamItemDescription"><p>the maximum number of warnings to emit (0 = no limit)</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Data</td>
<td class="doxyParamItemDescription"><p>if provided, populate with the correlation data found</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>, definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofcorrelator-cpp">InstrProfCorrelator.cpp</a>.</p>

</div>
</div>

### correlateProfileNameImpl() {#aa4ced264efa6274211ad2560508deee6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntPtrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DwarfInstrProfCorrelator::correlateProfileNameImpl ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>, definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofcorrelator-cpp">InstrProfCorrelator.cpp</a>.</p>

</div>
</div>

### getLocation() {#ac49e751cd44b4fa4ad37170724b2c64b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntPtrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; DwarfInstrProfCorrelator::getLocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; Die)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the address of the object that the provided <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> symbolizes.</p>

<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>, definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofcorrelator-cpp">InstrProfCorrelator.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DICtx {#aafccf6a02c29f43b1ab293366e80e755}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntPtrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;DWARFContext&gt; llvm::DwarfInstrProfCorrelator&lt; IntPtrT &gt;::DICtx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### isDIEOfProbe() {#a83a64b3082a2c3936791f45fe652540b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntPtrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DwarfInstrProfCorrelator::isDIEOfProbe (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; Die)</td>
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

<p>Returns true if the provided <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> symbolizes an instrumentation probe symbol.</p>

<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>, definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofcorrelator-cpp">InstrProfCorrelator.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofcorrelator-cpp">InstrProfCorrelator.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
