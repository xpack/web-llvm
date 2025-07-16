---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/shared/spsserializationtraits-bf8924ae7d79c09d623eda7a9bca91c9
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SPSSerializationTraits` Class Template Reference



## Declaration

<div class="doxyDeclaration">
class llvm::orc::shared::SPSSerializationTraits&lt;SPSPerfJITDebugEntry, PerfJITDebugEntry&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">llvm/ExecutionEngine/Orc/Shared/PerfSharedStructs.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f6660b662ca55807e022cf061f21c2f">size</a> (const PerfJITDebugEntry &amp;Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c07c9caeade685e44ce4b07bd6a1b01">deserialize</a> (SPSInputBuffer &amp;IB, PerfJITDebugEntry &amp;Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa34f45a8b857a8a7247dbd966a832f0">serialize</a> (SPSOutputBuffer &amp;OB, const PerfJITDebugEntry &amp;Val)</td>
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


<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### deserialize() {#a6c07c9caeade685e44ce4b07bd6a1b01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITDebugEntry, PerfJITDebugEntry &gt;::deserialize (<a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsinputbuffer">SPSInputBuffer</a> &amp; IB, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitdebugentry">PerfJITDebugEntry</a> &amp; Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitdebugentry/#a96fbd75b3f55dda4a483318c010d5582">llvm::orc::PerfJITDebugEntry::Addr</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitdebugentry/#ad160a48a1e0c89e3d4b75f493a3a2481">llvm::orc::PerfJITDebugEntry::Discrim</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitdebugentry/#afdf9cf60ed88f09b1f1a605e3adb87be">llvm::orc::PerfJITDebugEntry::Lineno</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitdebugentry/#ad177378fc798a380609c94922326dd37">llvm::orc::PerfJITDebugEntry::Name</a>.</p>

</div>
</div>

### serialize() {#afa34f45a8b857a8a7247dbd966a832f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITDebugEntry, PerfJITDebugEntry &gt;::serialize (<a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsoutputbuffer">SPSOutputBuffer</a> &amp; OB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitdebugentry">PerfJITDebugEntry</a> &amp; Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitdebugentry/#a96fbd75b3f55dda4a483318c010d5582">llvm::orc::PerfJITDebugEntry::Addr</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitdebugentry/#ad160a48a1e0c89e3d4b75f493a3a2481">llvm::orc::PerfJITDebugEntry::Discrim</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitdebugentry/#afdf9cf60ed88f09b1f1a605e3adb87be">llvm::orc::PerfJITDebugEntry::Lineno</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitdebugentry/#ad177378fc798a380609c94922326dd37">llvm::orc::PerfJITDebugEntry::Name</a>.</p>

</div>
</div>

### size() {#a1f6660b662ca55807e022cf061f21c2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITDebugEntry, PerfJITDebugEntry &gt;::size (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitdebugentry">PerfJITDebugEntry</a> &amp; Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitdebugentry/#a96fbd75b3f55dda4a483318c010d5582">llvm::orc::PerfJITDebugEntry::Addr</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitdebugentry/#ad160a48a1e0c89e3d4b75f493a3a2481">llvm::orc::PerfJITDebugEntry::Discrim</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitdebugentry/#afdf9cf60ed88f09b1f1a605e3adb87be">llvm::orc::PerfJITDebugEntry::Lineno</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitdebugentry/#ad177378fc798a380609c94922326dd37">llvm::orc::PerfJITDebugEntry::Name</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
