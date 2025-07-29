---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/telemetry/entrykind
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `EntryKind` Struct

<p>This struct is used by <a href="/web-llvm/docs/api/structs/llvm/telemetry/telemetryinfo">TelemetryInfo</a> to support isa&lt;&gt;, dyn_cast&lt;&gt; operations. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::telemetry::EntryKind { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/telemetry/telemetry-h">llvm/Telemetry/Telemetry.h</a>"
</div>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/telemetry/#ac13856b6a599c2b0252cbf171d9ec28c">KindType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa79d78c226c25ab33eef07a4a408486f">Base</a> = 0</td>
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

## Description {#details}

<p>This struct is used by <a href="/web-llvm/docs/api/structs/llvm/telemetry/telemetryinfo">TelemetryInfo</a> to support isa&lt;&gt;, dyn_cast&lt;&gt; operations.</p>


<p>It is defined as a struct (rather than an enum) because it is expected to be extended by subclasses which may have additional <a href="/web-llvm/docs/api/structs/llvm/telemetry/telemetryinfo">TelemetryInfo</a> types defined to describe different events.</p>


<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/telemetry/telemetry-h">Telemetry.h</a>.</p>


<div class="doxySectionDef">

## Public Static Attributes

### Base {#aa79d78c226c25ab33eef07a4a408486f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const KindType llvm::telemetry::EntryKind::Base = 0</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/telemetry/telemetry-h">Telemetry.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/telemetry/telemetryinfo/#a4414d70ef6cecd75915163d1c1133c66">llvm::telemetry::TelemetryInfo::classof</a> and <a href="/web-llvm/docs/api/structs/llvm/telemetry/telemetryinfo/#a3508eda368e6d583c0a7d45ff1d6c7a6">llvm::telemetry::TelemetryInfo::getKind</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/telemetry/telemetry-h">Telemetry.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
