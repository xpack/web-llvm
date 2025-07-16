---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/kernelinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `KernelInfo` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace KernelInfo { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ce86cd1750ba693983bdec2c5d361be">getKernelEnvironementGVFromKernelInitCB</a> (CallBase *KernelInitCB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantstruct">ConstantStruct</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc35ca85aef2e06a527c9edfe484eb56">getKernelEnvironementFromKernelInitCB</a> (CallBase *KernelInitCB)</td>
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

### getKernelEnvironementFromKernelInitCB() {#afc35ca85aef2e06a527c9edfe484eb56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantStruct * KernelInfo::getKernelEnvironementFromKernelInitCB (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * KernelInitCB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a0698d5bcabbfbca4f56a9d7a81cecb25">llvm::GlobalVariable::getInitializer</a> and <a href="#a3ce86cd1750ba693983bdec2c5d361be">getKernelEnvironementGVFromKernelInitCB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#a16144b1e0f0bc86c81b262b2f82c44df">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::buildCustomStateMachine</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ae4b9f7a4322b4668f7fd018deef3e839">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::changeToSPMDMode</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ac5c4384a376959ec882f7650e427dbb5">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaexecutiondomainfunction/#a2e8065095902b6763ce9c78e1178816d">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::isInitialThreadOnlyEdge</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#adc155013f4c88522a318f0f19a29cbb2">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::manifest</a> and <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ab05c198311b34d95f57423b9f9c1d1e6">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::updateImpl</a>.</p>

</div>
</div>

### getKernelEnvironementGVFromKernelInitCB() {#a3ce86cd1750ba693983bdec2c5d361be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable * KernelInfo::getKernelEnvironementGVFromKernelInitCB (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * KernelInitCB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a966eb231e7d4e572874d2cb49b18faea">llvm::Value::stripPointerCasts</a>.</p>


<p>Referenced by <a href="#afc35ca85aef2e06a527c9edfe484eb56">getKernelEnvironementFromKernelInitCB</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ac5c4384a376959ec882f7650e427dbb5">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::initialize</a> and <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#adc155013f4c88522a318f0f19a29cbb2">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::manifest</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
