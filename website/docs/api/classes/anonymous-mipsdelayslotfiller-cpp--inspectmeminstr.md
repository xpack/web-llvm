---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-mipsdelayslotfiller-cpp-/inspectmeminstr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InspectMemInstr` Class Reference

<p>Base class for inspecting loads and stores. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{MipsDelaySlotFiller.cpp}::InspectMemInstr { ... }
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/loadfromstackorconst">LoadFromStackOrConst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This subclass accepts loads from stacks and constant loads. <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/loadfromstackorconst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/memdefsuses">MemDefsUses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This subclass uses memory dependence information to determine whether a memory instruction can be moved to a delay slot. <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/memdefsuses/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/nomeminstr">NoMemInstr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This subclass rejects any memory instructions. <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/nomeminstr/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cbd66d12f12e089c39647a2c61b91f5">InspectMemInstr</a> (bool ForbidMemInstr_)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1463fcec6c6df4639528ee9a8903716b">~InspectMemInstr</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeac46d9736097831494137e479fe5e62">hasHazard</a> (const MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if MI cannot be moved to delay slot. <a href="#aeac46d9736097831494137e479fe5e62">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cdb7a92406f9ae96cf1c0c1d0966319">hasHazard_</a> (const MachineInstr &amp;MI)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f92a0b2e58876fa6cf07a604579dc8a">OrigSeenLoad</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flags indicating whether loads or stores have been seen. <a href="#a1f92a0b2e58876fa6cf07a604579dc8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5757d36debd5db21c7c7942ce4110fdc">OrigSeenStore</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4a387747294e277253fddf050e56701">SeenLoad</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af38e950704db0b55d4532a3fb8df5ea1">SeenStore</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cc413f2f72544ba07a01299e6215072">ForbidMemInstr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> instructions are not allowed to move to delay slot if this flag is true. <a href="#a7cc413f2f72544ba07a01299e6215072">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Base class for inspecting loads and stores.</p>

<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InspectMemInstr() {#a1cbd66d12f12e089c39647a2c61b91f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MipsDelaySlotFiller.cpp}::InspectMemInstr::InspectMemInstr (bool ForbidMemInstr_)</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a>.</p>


<p>Reference <a href="#a7cc413f2f72544ba07a01299e6215072">ForbidMemInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/loadfromstackorconst/#a357d1e3001d390b4b70cc5b808b87998">anonymous{MipsDelaySlotFiller.cpp}::LoadFromStackOrConst::LoadFromStackOrConst</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/memdefsuses/#a5f6f4501f68cb4af2d98c6677a088663">anonymous{MipsDelaySlotFiller.cpp}::MemDefsUses::MemDefsUses</a> and <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/nomeminstr/#a5ac26db9ad4a8926b281baa3fdcd32c8">anonymous{MipsDelaySlotFiller.cpp}::NoMemInstr::NoMemInstr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~InspectMemInstr() {#a1463fcec6c6df4639528ee9a8903716b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual anonymous{MipsDelaySlotFiller.cpp}::InspectMemInstr::~InspectMemInstr ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### hasHazard() {#aeac46d9736097831494137e479fe5e62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InspectMemInstr::hasHazard (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if MI cannot be moved to delay slot.</p>

<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a>.</p>


<p>References <a href="#a7cc413f2f72544ba07a01299e6215072">ForbidMemInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a1f92a0b2e58876fa6cf07a604579dc8a">OrigSeenLoad</a>, <a href="#a5757d36debd5db21c7c7942ce4110fdc">OrigSeenStore</a>, <a href="#aa4a387747294e277253fddf050e56701">SeenLoad</a> and <a href="#af38e950704db0b55d4532a3fb8df5ea1">SeenStore</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### hasHazard\_() {#a0cdb7a92406f9ae96cf1c0c1d0966319}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool anonymous{MipsDelaySlotFiller.cpp}::InspectMemInstr::hasHazard_ (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### ForbidMemInstr {#a7cc413f2f72544ba07a01299e6215072}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsDelaySlotFiller.cpp}::InspectMemInstr::ForbidMemInstr</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> instructions are not allowed to move to delay slot if this flag is true.</p>

<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a>.</p>


<p>Referenced by <a href="#aeac46d9736097831494137e479fe5e62">hasHazard</a> and <a href="#a1cbd66d12f12e089c39647a2c61b91f5">InspectMemInstr</a>.</p>

</div>
</div>

### OrigSeenLoad {#a1f92a0b2e58876fa6cf07a604579dc8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsDelaySlotFiller.cpp}::InspectMemInstr::OrigSeenLoad = false</td>
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

<p>Flags indicating whether loads or stores have been seen.</p>

<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a>.</p>


<p>Referenced by <a href="#aeac46d9736097831494137e479fe5e62">hasHazard</a>.</p>

</div>
</div>

### OrigSeenStore {#a5757d36debd5db21c7c7942ce4110fdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsDelaySlotFiller.cpp}::InspectMemInstr::OrigSeenStore = false</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a>.</p>


<p>Referenced by <a href="#aeac46d9736097831494137e479fe5e62">hasHazard</a>.</p>

</div>
</div>

### SeenLoad {#aa4a387747294e277253fddf050e56701}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsDelaySlotFiller.cpp}::InspectMemInstr::SeenLoad = false</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a>.</p>


<p>Referenced by <a href="#aeac46d9736097831494137e479fe5e62">hasHazard</a>.</p>

</div>
</div>

### SeenStore {#af38e950704db0b55d4532a3fb8df5ea1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsDelaySlotFiller.cpp}::InspectMemInstr::SeenStore = false</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a>.</p>


<p>Referenced by <a href="#aeac46d9736097831494137e479fe5e62">hasHazard</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
