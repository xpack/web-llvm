---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-riscvcalllowering-cpp-/riscvincomingvalueassigner
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `RISCVIncomingValueAssigner` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{RISCVCallLowering.cpp}::RISCVIncomingValueAssigner { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/calllowering/incomingvalueassigner">IncomingValueAssigner</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6b496b35a57d56af1dfb2c4a7be0be4">RISCVIncomingValueAssigner</a> (RISCVCCAssignFn *RISCVAssignFn_, bool IsRet)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa00177ed35b852b9cff4b22d156ad7f2">assignArg</a> (unsigned ValNo, EVT OrigVT, MVT ValVT, MVT LocVT, CCValAssign::LocInfo LocInfo, const CallLowering::ArgInfo &amp;Info, ISD::ArgFlagsTy Flags, CCState &amp;State) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wrap call to (typically tablegenerated CCAssignFn). <a href="#aa00177ed35b852b9cff4b22d156ad7f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">RISCVCCAssignFn *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48aa2dd0b79b62c8b0ec87526b1f2ffe">RISCVAssignFn</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a435c6b734876ac674292b5e1950213ee">IsRet</a></td>
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


<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvcalllowering-cpp">RISCVCallLowering.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RISCVIncomingValueAssigner() {#ad6b496b35a57d56af1dfb2c4a7be0be4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{RISCVCallLowering.cpp}::RISCVIncomingValueAssigner::RISCVIncomingValueAssigner (RISCVCCAssignFn * RISCVAssignFn_, bool IsRet)</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvcalllowering-cpp">RISCVCallLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/calllowering/incomingvalueassigner/#a13b43a063ba0bd7c472e835dc34f0a95">llvm::CallLowering::IncomingValueAssigner::IncomingValueAssigner</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### assignArg() {#aa00177ed35b852b9cff4b22d156ad7f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVCallLowering.cpp}::RISCVIncomingValueAssigner::assignArg (unsigned ValNo, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> OrigVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> ValVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> LocVT, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45">CCValAssign::LocInfo</a> LocInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/calllowering/arginfo">CallLowering::ArgInfo</a> &amp; Info, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> Flags, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; State)</td>
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


<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvcalllowering-cpp">RISCVCallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a447ebcc5de7a1d9bc163862bf2c78e41">llvm::MVT::isScalableVector</a> and <a href="/web-llvm/docs/api/structs/llvm/calllowering/valueassigner/#ad737172e1e2f85c9f819c2e4e8b364b7">llvm::CallLowering::ValueAssigner::StackSize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### IsRet {#a435c6b734876ac674292b5e1950213ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVCallLowering.cpp}::RISCVIncomingValueAssigner::IsRet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvcalllowering-cpp">RISCVCallLowering.cpp</a>.</p>

</div>
</div>

### RISCVAssignFn {#a48aa2dd0b79b62c8b0ec87526b1f2ffe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVCCAssignFn* anonymous{RISCVCallLowering.cpp}::RISCVIncomingValueAssigner::RISCVAssignFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvcalllowering-cpp">RISCVCallLowering.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvcalllowering-cpp">RISCVCallLowering.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
