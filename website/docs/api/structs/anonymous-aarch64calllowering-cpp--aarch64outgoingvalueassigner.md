---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-aarch64calllowering-cpp-/aarch64outgoingvalueassigner
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `AArch64OutgoingValueAssigner` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{AArch64CallLowering.cpp}::AArch64OutgoingValueAssigner { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ceb0453e55656ee3a5ee8f5e541d7bf">AArch64OutgoingValueAssigner</a> (CCAssignFn *AssignFn_, CCAssignFn *AssignFnVarArg_, const AArch64Subtarget &amp;Subtarget_, bool IsReturn)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e31012ae290be156077d90c19f46432">assignArg</a> (unsigned ValNo, EVT OrigVT, MVT ValVT, MVT LocVT, CCValAssign::LocInfo LocInfo, const CallLowering::ArgInfo &amp;Info, ISD::ArgFlagsTy Flags, CCState &amp;State) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wrap call to (typically tablegenerated CCAssignFn). <a href="#a4e31012ae290be156077d90c19f46432">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget">AArch64Subtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b6d79f3983ea4389717e84fe2a926cb">Subtarget</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4ac685d0df693b84553092e8f62e097">IsReturn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Track if this is used for a return instead of function argument passing. <a href="#ac4ac685d0df693b84553092e8f62e097">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AArch64OutgoingValueAssigner() {#a2ceb0453e55656ee3a5ee8f5e541d7bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AArch64CallLowering.cpp}::AArch64OutgoingValueAssigner::AArch64OutgoingValueAssigner (CCAssignFn * AssignFn_, CCAssignFn * AssignFnVarArg_, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget">AArch64Subtarget</a> &amp; Subtarget_, bool IsReturn)</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<p>References <a href="#ac4ac685d0df693b84553092e8f62e097">IsReturn</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/outgoingvalueassigner/#a2189160214171b9862ade30c943b7a8e">llvm::CallLowering::OutgoingValueAssigner::OutgoingValueAssigner</a> and <a href="#a2b6d79f3983ea4389717e84fe2a926cb">Subtarget</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### assignArg() {#a4e31012ae290be156077d90c19f46432}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64CallLowering.cpp}::AArch64OutgoingValueAssigner::assignArg (unsigned ValNo, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> OrigVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> ValVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> LocVT, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45">CCValAssign::LocInfo</a> LocInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/calllowering/arginfo">CallLowering::ArgInfo</a> &amp; Info, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> Flags, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; State)</td>
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


<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp/#a9a1ffccd0b7e439109060f4d29334142">applyStackPassedSmallTypeDAGHack</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/valueassigner/#a27f3aed59700f4ccc3924ea6e6eb1f34">llvm::CallLowering::ValueAssigner::AssignFn</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/valueassigner/#a758ece099367984b17faa8d140b2b787">llvm::CallLowering::ValueAssigner::AssignFnVarArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#ac4ac685d0df693b84553092e8f62e097">IsReturn</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/valueassigner/#ad737172e1e2f85c9f819c2e4e8b364b7">llvm::CallLowering::ValueAssigner::StackSize</a> and <a href="#a2b6d79f3983ea4389717e84fe2a926cb">Subtarget</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### IsReturn {#ac4ac685d0df693b84553092e8f62e097}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64CallLowering.cpp}::AArch64OutgoingValueAssigner::IsReturn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Track if this is used for a return instead of function argument passing.</p>


<p>We apply a hack to i1/i8/i16 stack passed values, but do not use stack passed returns for them and cannot apply the type adjustment.</p>


<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<p>Referenced by <a href="#a2ceb0453e55656ee3a5ee8f5e541d7bf">AArch64OutgoingValueAssigner</a> and <a href="#a4e31012ae290be156077d90c19f46432">assignArg</a>.</p>

</div>
</div>

### Subtarget {#a2b6d79f3983ea4389717e84fe2a926cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AArch64Subtarget&amp; anonymous{AArch64CallLowering.cpp}::AArch64OutgoingValueAssigner::Subtarget</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<p>Referenced by <a href="#a2ceb0453e55656ee3a5ee8f5e541d7bf">AArch64OutgoingValueAssigner</a> and <a href="#a4e31012ae290be156077d90c19f46432">assignArg</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
