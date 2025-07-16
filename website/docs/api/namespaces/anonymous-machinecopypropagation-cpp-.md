---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-machinecopypropagation-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{MachineCopyPropagation.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{MachineCopyPropagation.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/copytracker">CopyTracker</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/machinecopypropagation">MachineCopyPropagation</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/destsourcepair">DestSourcePair</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20ee831cc20a58e40d9d76c4264f7eb5">isCopyInstr</a> (const MachineInstr &amp;MI, const TargetInstrInfo &amp;TII, bool UseCopyInstr)</td>
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

## Functions

### isCopyInstr() {#a20ee831cc20a58e40d9d76c4264f7eb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; DestSourcePair &gt; anonymous{MachineCopyPropagation.cpp}::isCopyInstr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> &amp; TII, bool UseCopyInstr)</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecopypropagation-cpp">MachineCopyPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/copytracker/#a9e13fad0f5191583a8266f873d87cf6d">anonymous{MachineCopyPropagation.cpp}::CopyTracker::clobberRegUnit</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/copytracker/#a57a867565747e5ed15e3f6e417857a1b">anonymous{MachineCopyPropagation.cpp}::CopyTracker::findAvailBackwardCopy</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/copytracker/#afa3ae93d47c5dcf2858522c9868301ca">anonymous{MachineCopyPropagation.cpp}::CopyTracker::findAvailCopy</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/copytracker/#adc8ca4d1d7106281e788558813399a48">anonymous{MachineCopyPropagation.cpp}::CopyTracker::findLastSeenDefInCopy</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/copytracker/#abbf02514d481b5292b34f111865e4605">anonymous{MachineCopyPropagation.cpp}::CopyTracker::invalidateRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecopypropagation-cpp/#aa3f54ba0f4f9c1bff1b6e218a98256d3">isNopCopy</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/copytracker/#a900f1a90fad33256f71fe326507afa43">anonymous{MachineCopyPropagation.cpp}::CopyTracker::trackCopy</a> and <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/copytracker/#a6fc3c1b63330a00fb5f865c0b76ca058">anonymous{MachineCopyPropagation.cpp}::CopyTracker::trackSrcUsers</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecopypropagation-cpp">MachineCopyPropagation.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
