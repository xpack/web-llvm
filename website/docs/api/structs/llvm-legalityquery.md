---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/legalityquery
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LegalityQuery` Struct Reference

<p>The <a href="/web-llvm/docs/api/structs/llvm/legalityquery">LegalityQuery</a> object bundles together all the information that's needed to decide whether a given operation is legal or not. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::LegalityQuery { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">llvm/CodeGen/GlobalISel/LegalizerInfo.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a477a185800ea3abaeb44ce78c54f96a1">LegalityQuery</a> (unsigned Opcode, const ArrayRef&lt; LLT &gt; Types, const ArrayRef&lt; MemDesc &gt; MMODescrs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3db6b70886c60d50faf05caa05ea81a2">LegalityQuery</a> (unsigned Opcode, const ArrayRef&lt; LLT &gt; Types)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af17219d2dcf5afc625e5bc40a4483b7d">print</a> (raw_ostream &amp;OS) const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd4ab894cdbdc5888a2d10fa5e5f8333">Opcode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab28fca6f8145be28b70ad89bb0c741b0">Types</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/legalityquery/memdesc">MemDesc</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e26ab57991dfde2757e4790a626d6a3">MMODescrs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Operations which require memory can use this to place requirements on the memory type for each MMO. <a href="#a9e26ab57991dfde2757e4790a626d6a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The <a href="/web-llvm/docs/api/structs/llvm/legalityquery">LegalityQuery</a> object bundles together all the information that's needed to decide whether a given operation is legal or not.</p>


<p>For efficiency, it doesn't make a copy of Types so care must be taken not to free it before using the query.</p>


<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LegalityQuery() {#a477a185800ea3abaeb44ce78c54f96a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LegalityQuery::LegalityQuery (unsigned Opcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/legalityquery/memdesc">MemDesc</a> &gt; MMODescrs)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#a9e26ab57991dfde2757e4790a626d6a3">MMODescrs</a>, <a href="#afd4ab894cdbdc5888a2d10fa5e5f8333">Opcode</a> and <a href="#ab28fca6f8145be28b70ad89bb0c741b0">Types</a>.</p>


<p>Referenced by <a href="#a3db6b70886c60d50faf05caa05ea81a2">LegalityQuery</a>.</p>

</div>
</div>

### LegalityQuery() {#a3db6b70886c60d50faf05caa05ea81a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LegalityQuery::LegalityQuery (unsigned Opcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Types)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#a477a185800ea3abaeb44ce78c54f96a1">LegalityQuery</a>, <a href="#afd4ab894cdbdc5888a2d10fa5e5f8333">Opcode</a> and <a href="#ab28fca6f8145be28b70ad89bb0c741b0">Types</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### print() {#af17219d2dcf5afc625e5bc40a4483b7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; LegalityQuery::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerinfo-cpp">LegalizerInfo.cpp</a>.</p>


<p>References <a href="#a9e26ab57991dfde2757e4790a626d6a3">MMODescrs</a>, <a href="#afd4ab894cdbdc5888a2d10fa5e5f8333">Opcode</a> and <a href="#ab28fca6f8145be28b70ad89bb0c741b0">Types</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#af5b725eb16175a6ebbd75e53d6bc0d2c">llvm::LegalizeRuleSet::apply</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### MMODescrs {#a9e26ab57991dfde2757e4790a626d6a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;MemDesc&gt; llvm::LegalityQuery::MMODescrs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Operations which require memory can use this to place requirements on the memory type for each MMO.</p>

<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipslegalizerinfo-cpp/#a093c9466dbe02fe43ee439cda932a7f4">CheckTy0Ty1MemSizeAlign</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a812ebabddd1ad2d8f8bbc6194346e2ed">isLoadStoreSizeLegal</a>, <a href="#a477a185800ea3abaeb44ce78c54f96a1">LegalityQuery</a>, <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a63e981ba0042fbfdd3857f66c82d8d28">llvm::MipsLegalizerInfo::MipsLegalizerInfo</a>, <a href="#af17219d2dcf5afc625e5bc40a4483b7d">print</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a9ae9993cc0e622c6d10e6e9a2aad0a05">shouldWidenLoad</a>.</p>

</div>
</div>

### Opcode {#afd4ab894cdbdc5888a2d10fa5e5f8333}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LegalityQuery::Opcode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legacylegalizerinfo/#ab2df8f41f63c8cd97c9f3b4a6b6374b0">llvm::LegacyLegalizerInfo::getAction</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo/#af3687eafb2772c29aa67ce722c2081fd">llvm::LegalizerInfo::getAction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a812ebabddd1ad2d8f8bbc6194346e2ed">isLoadStoreSizeLegal</a>, <a href="#a3db6b70886c60d50faf05caa05ea81a2">LegalityQuery</a>, <a href="#a477a185800ea3abaeb44ce78c54f96a1">LegalityQuery</a>, <a href="#af17219d2dcf5afc625e5bc40a4483b7d">print</a> and <a href="/web-llvm/docs/api/classes/llvm/x86legalizerinfo/#abfc562c1c7aebc23222627fa24d11df5">llvm::X86LegalizerInfo::X86LegalizerInfo</a>.</p>

</div>
</div>

### Types {#ab28fca6f8145be28b70ad89bb0c741b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;LLT&gt; llvm::LegalityQuery::Types</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a7b80b62a08d65dc70ac57954b7955ca0">llvm::LegalizeRuleSet::alignNumElementsTo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipslegalizerinfo-cpp/#a093c9466dbe02fe43ee439cda932a7f4">CheckTy0Ty1MemSizeAlign</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipslegalizerinfo-cpp/#a3a0fb4a3768823cf9aaeff9fa81ec04e">CheckTyN</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a3b9d49f459b9596f73c60edab6e92673">llvm::LegalizeRuleSet::clampMaxNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a3da19f78bfc264962a18568ea4b8d6c7">llvm::LegalizeRuleSet::clampMinNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/legacylegalizerinfo/#ab2df8f41f63c8cd97c9f3b4a6b6374b0">llvm::LegacyLegalizerInfo::getAction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerinfo-cpp/#a629547dc68b8b25d374ecd455b155fbc">hasNoSimpleLoops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#ad2c8a875d4d2a4e73f7a48e64226b265">isLoadStoreLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a812ebabddd1ad2d8f8bbc6194346e2ed">isLoadStoreSizeLegal</a>, <a href="#a3db6b70886c60d50faf05caa05ea81a2">LegalityQuery</a>, <a href="#a477a185800ea3abaeb44ce78c54f96a1">LegalityQuery</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a1d446dfaa94c6ec0729feaa73d5b6c88">llvm::LegalizeRuleSet::maxScalarEltSameAsIf</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#acd56c0d001ca90095d61c52099f90cd3">llvm::LegalizeRuleSet::maxScalarIf</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a0d8b8e18977cd5ba53ec89aa06bd7506">llvm::LegalizeRuleSet::maxScalarSameAs</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a4aca13e5c1613b22b7c3c9411895fdae">llvm::LegalizeRuleSet::minScalarEltSameAsIf</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#af0cb74dd5e94daaea299005867eac63d">llvm::LegalizeRuleSet::minScalarIf</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a8abe7c10c8bfc8f9c308c89adc98330c">llvm::LegalizeRuleSet::minScalarSameAs</a>, <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a63e981ba0042fbfdd3857f66c82d8d28">llvm::MipsLegalizerInfo::MipsLegalizerInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerinfo-cpp/#ace2b635ecd7fc6de3eb1f8a95530d08d">mutationIsSane</a>, <a href="#af17219d2dcf5afc625e5bc40a4483b7d">print</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a9ae9993cc0e622c6d10e6e9a2aad0a05">shouldWidenLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a430225b2e66451c27e9f4e9462be7df1">llvm::LegalizeRuleSet::widenVectorEltsToVectorMinSize</a> and <a href="/web-llvm/docs/api/classes/llvm/x86legalizerinfo/#abfc562c1c7aebc23222627fa24d11df5">llvm::X86LegalizerInfo::X86LegalizerInfo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerinfo-cpp">LegalizerInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
