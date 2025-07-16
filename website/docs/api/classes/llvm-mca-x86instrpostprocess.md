---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mca/x86instrpostprocess
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `X86InstrPostProcess` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::mca::X86InstrPostProcess { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mca/x86custombehaviour-h">Target/X86/MCA/X86CustomBehaviour.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/instrpostprocess">InstrPostProcess</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class which can be overriden by targets to modify the <a href="/web-llvm/docs/api/classes/llvm/mca/instruction">mca::Instruction</a> objects before the pipeline starts. <a href="/web-llvm/docs/api/classes/llvm/mca/instrpostprocess/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd94ce45bf3d942a2619e7f406b6eb53">X86InstrPostProcess</a> (const MCSubtargetInfo &amp;STI, const MCInstrInfo &amp;MCII)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3a1d72cc7cfd1562c2e1e965196c54d">~X86InstrPostProcess</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac96877e4c086ac4fe55701fedb3704b6">postProcessInstruction</a> (std::unique_ptr&lt; Instruction &gt; &amp;Inst, const MCInst &amp;MCI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method can be overriden by targets to modify the <a href="/web-llvm/docs/api/classes/llvm/mca/instruction">mca::Instruction</a> object after it has been lowered from the <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>. <a href="#ac96877e4c086ac4fe55701fedb3704b6">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae08dda42a1312300f88627b0d3567080">setMemBarriers</a> (std::unique_ptr&lt; Instruction &gt; &amp;Inst, const MCInst &amp;MCI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called within <a href="/web-llvm/docs/api/classes/llvm/mca/x86instrpostprocess">X86InstrPostProcess</a> to specify certain instructions as load and store barriers. <a href="#ae08dda42a1312300f88627b0d3567080">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mca/x86custombehaviour-h">X86CustomBehaviour.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### X86InstrPostProcess() {#acd94ce45bf3d942a2619e7f406b6eb53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::X86InstrPostProcess::X86InstrPostProcess (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; MCII)</td>
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



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mca/x86custombehaviour-h">X86CustomBehaviour.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mca/instrpostprocess/#ad0c98ba2801809b09e24b4c270abcc85">llvm::mca::InstrPostProcess::InstrPostProcess</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instrpostprocess/#aac08030fd3e230d4d35e745849ecd789">llvm::mca::InstrPostProcess::MCII</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/instrpostprocess/#a7c4d4cfb0828cb3ed1f40e38b1ca3c2a">llvm::mca::InstrPostProcess::STI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~X86InstrPostProcess() {#ad3a1d72cc7cfd1562c2e1e965196c54d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::X86InstrPostProcess::~X86InstrPostProcess ()</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mca/x86custombehaviour-h">X86CustomBehaviour.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### postProcessInstruction() {#ac96877e4c086ac4fe55701fedb3704b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::X86InstrPostProcess::postProcessInstruction (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/instruction">Instruction</a> &gt; &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MCI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method can be overriden by targets to modify the <a href="/web-llvm/docs/api/classes/llvm/mca/instruction">mca::Instruction</a> object after it has been lowered from the <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>.</p>


<p>This is generally a less disruptive alternative to modifying the scheduling model.</p>


<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mca/x86custombehaviour-h">X86CustomBehaviour.h</a>, definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mca/x86custombehaviour-cpp">X86CustomBehaviour.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### setMemBarriers() {#ae08dda42a1312300f88627b0d3567080}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::X86InstrPostProcess::setMemBarriers (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/instruction">Instruction</a> &gt; &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Called within <a href="/web-llvm/docs/api/classes/llvm/mca/x86instrpostprocess">X86InstrPostProcess</a> to specify certain instructions as load and store barriers.</p>

<p>Declaration at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mca/x86custombehaviour-h">X86CustomBehaviour.h</a>, definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mca/x86custombehaviour-cpp">X86CustomBehaviour.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mca/x86custombehaviour-cpp">X86CustomBehaviour.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mca/x86custombehaviour-h">X86CustomBehaviour.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
