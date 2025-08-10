---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-siinserthardclauses-cpp-/siinserthardclauses/clauseinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ClauseInfo` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::ClauseInfo { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-siinserthardclauses-cpp-/#a05f3bd1f05d10f71d36966379038c069">HardClauseType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8756be0eec6dd68e52f250497ce43aa0">Type</a> = <a href="/web-llvm/docs/api/namespaces/anonymous-siinserthardclauses-cpp-/#a05f3bd1f05d10f71d36966379038c069aa5be04416de1c7632343fd7d93b37d4d">HARDCLAUSE_ILLEGAL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedcb208b69428c3f1d6aeed2150d46bc">First</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b2c54a90de8f029d4331b5048522bd4">Last</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a2fbbe5c31e2244394c38df2453fd4b">Length</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fdbda7fa9415f7ed59027fc5ed9fb03">TrailingInternalLength</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad49bf054ec85b06fe8908221b28ec038">BaseOps</a></td>
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


<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinserthardclauses-cpp">SIInsertHardClauses.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### BaseOps {#ad49bf054ec85b06fe8908221b28ec038}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;const MachineOperand *, 4&gt; anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::ClauseInfo::BaseOps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinserthardclauses-cpp">SIInsertHardClauses.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinserthardclauses-cpp-/siinserthardclauses/#a014ee381e519aa7b2b38d66744faa5bb">anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::runOnMachineFunction</a>.</p>

</div>
</div>

### First {#aedcb208b69428c3f1d6aeed2150d46bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr* anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::ClauseInfo::First = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinserthardclauses-cpp">SIInsertHardClauses.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinserthardclauses-cpp-/siinserthardclauses/#afea2f73a2971b1c2238c0996efdb1201">anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::emitClause</a>.</p>

</div>
</div>

### Last {#a8b2c54a90de8f029d4331b5048522bd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr* anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::ClauseInfo::Last = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinserthardclauses-cpp">SIInsertHardClauses.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinserthardclauses-cpp-/siinserthardclauses/#afea2f73a2971b1c2238c0996efdb1201">anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::emitClause</a> and <a href="/web-llvm/docs/api/classes/anonymous-siinserthardclauses-cpp-/siinserthardclauses/#a014ee381e519aa7b2b38d66744faa5bb">anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::runOnMachineFunction</a>.</p>

</div>
</div>

### Length {#a8a2fbbe5c31e2244394c38df2453fd4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::ClauseInfo::Length = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinserthardclauses-cpp">SIInsertHardClauses.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinserthardclauses-cpp-/siinserthardclauses/#afea2f73a2971b1c2238c0996efdb1201">anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::emitClause</a> and <a href="/web-llvm/docs/api/classes/anonymous-siinserthardclauses-cpp-/siinserthardclauses/#a014ee381e519aa7b2b38d66744faa5bb">anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::runOnMachineFunction</a>.</p>

</div>
</div>

### TrailingInternalLength {#a1fdbda7fa9415f7ed59027fc5ed9fb03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::ClauseInfo::TrailingInternalLength = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinserthardclauses-cpp">SIInsertHardClauses.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinserthardclauses-cpp-/siinserthardclauses/#a014ee381e519aa7b2b38d66744faa5bb">anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::runOnMachineFunction</a>.</p>

</div>
</div>

### Type {#a8756be0eec6dd68e52f250497ce43aa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HardClauseType anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::ClauseInfo::Type = <a href="/web-llvm/docs/api/namespaces/anonymous-siinserthardclauses-cpp-/#a05f3bd1f05d10f71d36966379038c069aa5be04416de1c7632343fd7d93b37d4d">HARDCLAUSE_ILLEGAL</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinserthardclauses-cpp">SIInsertHardClauses.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinserthardclauses-cpp-/siinserthardclauses/#a014ee381e519aa7b2b38d66744faa5bb">anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinserthardclauses-cpp">SIInsertHardClauses.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
