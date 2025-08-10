---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-mipscalllowering-cpp-/mipsoutgoingvalueassigner
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `MipsOutgoingValueAssigner` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{MipsCallLowering.cpp}::MipsOutgoingValueAssigner { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/calllowering/outgoingvalueassigner">OutgoingValueAssigner</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20b360f0572d5be095c85fda2d7fac69">MipsOutgoingValueAssigner</a> (CCAssignFn *AssignFn_, const char *Func, bool IsReturn)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3df6a7e63762376a088acec41d1f3623">assignArg</a> (unsigned ValNo, EVT OrigVT, MVT ValVT, MVT LocVT, CCValAssign::LocInfo LocInfo, const CallLowering::ArgInfo &amp;Info, ISD::ArgFlagsTy Flags, CCState &amp;State_) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wrap call to (typically tablegenerated CCAssignFn). <a href="#a3df6a7e63762376a088acec41d1f3623">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f0f97c9ffe5a38edab45ff049d01d41">Func</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the name of the function being called FIXME: Relying on this is unsound. <a href="#a6f0f97c9ffe5a38edab45ff049d01d41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a579f9c20df295de9293bcc8bf3512fce">IsReturn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is this a return value, or an outgoing call operand. <a href="#a579f9c20df295de9293bcc8bf3512fce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipscalllowering-cpp">MipsCallLowering.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MipsOutgoingValueAssigner() {#a20b360f0572d5be095c85fda2d7fac69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MipsCallLowering.cpp}::MipsOutgoingValueAssigner::MipsOutgoingValueAssigner (CCAssignFn * AssignFn_, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Func, bool IsReturn)</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipscalllowering-cpp">MipsCallLowering.cpp</a>.</p>


<p>References <a href="#a6f0f97c9ffe5a38edab45ff049d01d41">Func</a>, <a href="#a579f9c20df295de9293bcc8bf3512fce">IsReturn</a> and <a href="/web-llvm/docs/api/structs/llvm/calllowering/outgoingvalueassigner/#a2189160214171b9862ade30c943b7a8e">llvm::CallLowering::OutgoingValueAssigner::OutgoingValueAssigner</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### assignArg() {#a3df6a7e63762376a088acec41d1f3623}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsCallLowering.cpp}::MipsOutgoingValueAssigner::assignArg (unsigned ValNo, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> OrigVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> ValVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> LocVT, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45">CCValAssign::LocInfo</a> LocInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/calllowering/arginfo">CallLowering::ArgInfo</a> &amp; Info, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> Flags, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; State)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Wrap call to (typically tablegenerated CCAssignFn).</p>


<p>This may be overridden to track additional state information as arguments are assigned or apply target specific hacks around the legacy infrastructure.</p>


<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipscalllowering-cpp">MipsCallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/calllowering/valueassigner/#ab1caf846fc79aa5976216a32724c9e10">llvm::CallLowering::ValueAssigner::assignArg</a>, <a href="#a6f0f97c9ffe5a38edab45ff049d01d41">Func</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a5db8faf73cf29bcefdb3bdfadf3dc2c1">llvm::EVT::getEVT</a>, <a href="#a579f9c20df295de9293bcc8bf3512fce">IsReturn</a> and <a href="/web-llvm/docs/api/classes/llvm/mipsccstate/#a4b59cb89474f9bb8123234228d0fb9de">llvm::MipsCCState::PreAnalyzeReturnValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Func {#a6f0f97c9ffe5a38edab45ff049d01d41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* anonymous{MipsCallLowering.cpp}::MipsOutgoingValueAssigner::Func = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is the name of the function being called FIXME: Relying on this is unsound.</p>

<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipscalllowering-cpp">MipsCallLowering.cpp</a>.</p>


<p>Referenced by <a href="#a3df6a7e63762376a088acec41d1f3623">assignArg</a> and <a href="#a20b360f0572d5be095c85fda2d7fac69">MipsOutgoingValueAssigner</a>.</p>

</div>
</div>

### IsReturn {#a579f9c20df295de9293bcc8bf3512fce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsCallLowering.cpp}::MipsOutgoingValueAssigner::IsReturn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Is this a return value, or an outgoing call operand.</p>

<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipscalllowering-cpp">MipsCallLowering.cpp</a>.</p>


<p>Referenced by <a href="#a3df6a7e63762376a088acec41d1f3623">assignArg</a> and <a href="#a20b360f0572d5be095c85fda2d7fac69">MipsOutgoingValueAssigner</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipscalllowering-cpp">MipsCallLowering.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
