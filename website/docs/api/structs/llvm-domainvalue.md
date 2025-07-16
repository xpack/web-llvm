---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/domainvalue
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DomainValue` Struct Reference

<p>A <a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> is a bit like <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a>' ValNo, but it also keeps track of execution domains. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::DomainValue { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">llvm/CodeGen/ExecutionDomainFix.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a765760aae1c271856a0249b1e617e334">DomainValue</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ecbb686a014a13d5a43b1139f764dd8">isCollapsed</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A collapsed <a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> has no instructions to twiddle - it simply keeps track of the domains where the registers are already available. <a href="#a7ecbb686a014a13d5a43b1139f764dd8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad92cb37a10bc8235f051713f9794b460">hasDomain</a> (unsigned domain) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is domain available? <a href="#ad92cb37a10bc8235f051713f9794b460">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aade39495c740074c67779094a365fa4c">addDomain</a> (unsigned domain)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark domain as available. <a href="#aade39495c740074c67779094a365fa4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ffd5788af6dfff6f4ff7897c76c378f">setSingleDomain</a> (unsigned domain)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a145f2b34d8a016cbf6843c16e5f16c49">getCommonDomains</a> (unsigned mask) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return bitmask of domains that are available and in mask. <a href="#a145f2b34d8a016cbf6843c16e5f16c49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf3512221a2d452552008de9af129baf">getFirstDomain</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>First domain available. <a href="#acf3512221a2d452552008de9af129baf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20b22b90ca45add43e8d2679dc222855">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear this <a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> and point to next which has all its data. <a href="#a20b22b90ca45add43e8d2679dc222855">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca1c38278b064f620b6dfc465eb17198">Refs</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Basic reference counting. <a href="#aca1c38278b064f620b6dfc465eb17198">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac900f658d1c226c23057b843aa5df4d0">AvailableDomains</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Bitmask of available domains. <a href="#ac900f658d1c226c23057b843aa5df4d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81594f3b613bebc91349100513f9f0f9">Next</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pointer to the next <a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> in a chain. <a href="#a81594f3b613bebc91349100513f9f0f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a339c0645a839f644497a7efde4f30cfd">Instrs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Twiddleable instructions using or defining these registers. <a href="#a339c0645a839f644497a7efde4f30cfd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A <a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> is a bit like <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a>' ValNo, but it also keeps track of execution domains.</p>


<p>An open <a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> represents a set of instructions that can still switch execution domain. Multiple registers may refer to the same open <a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> - they will eventually be collapsed to the same execution domain.</p>


<p>A collapsed <a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> represents a single register that has been forced into one of more execution domains. There is a separate collapsed <a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> for each register, but it may contain multiple execution domains. A register value is initially created in a single execution domain, but if we were forced to pay the penalty of a domain crossing, we keep track of the fact that the register is now available in multiple domains.</p>


<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DomainValue() {#a765760aae1c271856a0249b1e617e334}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DomainValue::DomainValue ()</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>.</p>


<p>Reference <a href="#a20b22b90ca45add43e8d2679dc222855">clear</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addDomain() {#aade39495c740074c67779094a365fa4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomainValue::addDomain (unsigned domain)</td>
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

<p>Mark domain as available.</p>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ac900f658d1c226c23057b843aa5df4d0">AvailableDomains</a>.</p>

</div>
</div>

### clear() {#a20b22b90ca45add43e8d2679dc222855}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomainValue::clear ()</td>
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

<p>Clear this <a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> and point to next which has all its data.</p>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>.</p>


<p>References <a href="#ac900f658d1c226c23057b843aa5df4d0">AvailableDomains</a>, <a href="#a339c0645a839f644497a7efde4f30cfd">Instrs</a> and <a href="#a81594f3b613bebc91349100513f9f0f9">Next</a>.</p>


<p>Referenced by <a href="#a765760aae1c271856a0249b1e617e334">DomainValue</a>.</p>

</div>
</div>

### getCommonDomains() {#a145f2b34d8a016cbf6843c16e5f16c49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DomainValue::getCommonDomains (unsigned mask)</td>
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

<p>Return bitmask of domains that are available and in mask.</p>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>.</p>


<p>Reference <a href="#ac900f658d1c226c23057b843aa5df4d0">AvailableDomains</a>.</p>

</div>
</div>

### getFirstDomain() {#acf3512221a2d452552008de9af129baf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DomainValue::getFirstDomain ()</td>
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

<p>First domain available.</p>

<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>.</p>


<p>References <a href="#ac900f658d1c226c23057b843aa5df4d0">AvailableDomains</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a>.</p>

</div>
</div>

### hasDomain() {#ad92cb37a10bc8235f051713f9794b460}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DomainValue::hasDomain (unsigned domain)</td>
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

<p>Is domain available?</p>

<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ac900f658d1c226c23057b843aa5df4d0">AvailableDomains</a>.</p>

</div>
</div>

### isCollapsed() {#a7ecbb686a014a13d5a43b1139f764dd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DomainValue::isCollapsed ()</td>
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

<p>A collapsed <a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> has no instructions to twiddle - it simply keeps track of the domains where the registers are already available.</p>

<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>.</p>


<p>Reference <a href="#a339c0645a839f644497a7efde4f30cfd">Instrs</a>.</p>

</div>
</div>

### setSingleDomain() {#a3ffd5788af6dfff6f4ff7897c76c378f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomainValue::setSingleDomain (unsigned domain)</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ac900f658d1c226c23057b843aa5df4d0">AvailableDomains</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AvailableDomains {#ac900f658d1c226c23057b843aa5df4d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DomainValue::AvailableDomains</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Bitmask of available domains.</p>


<p>For an open <a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a>, it is the still possible domains for collapsing. For a collapsed <a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> it is the domains where the register is available for free.</p>


<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>.</p>


<p>Referenced by <a href="#aade39495c740074c67779094a365fa4c">addDomain</a>, <a href="#a20b22b90ca45add43e8d2679dc222855">clear</a>, <a href="#a145f2b34d8a016cbf6843c16e5f16c49">getCommonDomains</a>, <a href="#acf3512221a2d452552008de9af129baf">getFirstDomain</a>, <a href="#ad92cb37a10bc8235f051713f9794b460">hasDomain</a> and <a href="#a3ffd5788af6dfff6f4ff7897c76c378f">setSingleDomain</a>.</p>

</div>
</div>

### Instrs {#a339c0645a839f644497a7efde4f30cfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineInstr *, 8&gt; llvm::DomainValue::Instrs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Twiddleable instructions using or defining these registers.</p>

<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>.</p>


<p>Referenced by <a href="#a20b22b90ca45add43e8d2679dc222855">clear</a> and <a href="#a7ecbb686a014a13d5a43b1139f764dd8">isCollapsed</a>.</p>

</div>
</div>

### Next {#a81594f3b613bebc91349100513f9f0f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DomainValue* llvm::DomainValue::Next</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pointer to the next <a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> in a chain.</p>


<p>When two DomainValues are merged, Victim.Next is set to point to Victor, so old <a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> references can be updated by following the chain.</p>


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>.</p>


<p>Referenced by <a href="#a20b22b90ca45add43e8d2679dc222855">clear</a>.</p>

</div>
</div>

### Refs {#aca1c38278b064f620b6dfc465eb17198}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DomainValue::Refs = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Basic reference counting.</p>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
