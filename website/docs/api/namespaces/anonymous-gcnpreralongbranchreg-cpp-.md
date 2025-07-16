---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-gcnpreralongbranchreg-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{GCNPreRALongBranchReg.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{GCNPreRALongBranchReg.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-gcnpreralongbranchreg-cpp-/gcnpreralongbranchreg">GCNPreRALongBranchReg</a></td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; double &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cc6e6349acbe2be32cbf40e3a49b433">LongBranchFactor</a>("amdgpu-long-branch-factor", cl::init(1.0), cl::Hidden, cl::desc("Factor to apply to what qualifies as a long branch " "to reserve a pair of scalar registers. If this value " "is 0 the long branch registers are never reserved. As this " "value grows the greater chance the branch distance will fall " "within the threshold and the registers will be marked to be " "reserved. We lean towards always reserving a register for  " "long jumps"))</td>
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

## Variables

### LongBranchFactor {#a0cc6e6349acbe2be32cbf40e3a49b433}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; double &gt; anonymous{GCNPreRALongBranchReg.cpp}::LongBranchFactor("amdgpu-long-branch-factor", cl::init(1.0), cl::Hidden, cl::desc("Factor to apply to what qualifies as a long branch " "to reserve a pair of scalar registers. If this value " "is 0 the long branch registers are never reserved. As this " "value grows the greater chance the branch distance will fall " "within the threshold and the registers will be marked to be " "reserved. We lean towards always reserving a register for  " "long jumps"))</td>
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



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnpreralongbranchreg-cpp">GCNPreRALongBranchReg.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-gcnpreralongbranchreg-cpp-/gcnpreralongbranchreg/#a8b5ef68b98f901c64096eb633984c661">anonymous{GCNPreRALongBranchReg.cpp}::GCNPreRALongBranchReg::runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnpreralongbranchreg-cpp">GCNPreRALongBranchReg.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
