---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/ipsccpoptions
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `IPSCCPOptions` Struct Reference

<p>A set of parameters to control various transforms performed by IPSCCP pass. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::IPSCCPOptions { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sccp-h">llvm/Transforms/IPO/SCCP.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a068d538384d610da3d97e56d2a07fa96">IPSCCPOptions</a> (bool AllowFuncSpec=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ipsccpoptions">IPSCCPOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a580e5f0146669ff3b96812482c7802f5">setFuncSpec</a> (bool FuncSpec)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enables or disables Specialization of Functions. <a href="#a580e5f0146669ff3b96812482c7802f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46abeeea976ed98593f67b9ca4d60ec6">AllowFuncSpec</a></td>
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

<p>A set of parameters to control various transforms performed by IPSCCP pass.</p>


<p>Each of the boolean parameters can be set to: true - enabling the transformation. false - disabling the transformation. Intended use is to create a default object, modify parameters with additional setters and then pass it to IPSCCP.</p>


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sccp-h">SCCP.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### IPSCCPOptions() {#a068d538384d610da3d97e56d2a07fa96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IPSCCPOptions::IPSCCPOptions (bool AllowFuncSpec=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sccp-h">SCCP.h</a>.</p>


<p>Reference <a href="#a46abeeea976ed98593f67b9ca4d60ec6">AllowFuncSpec</a>.</p>


<p>Referenced by <a href="#a580e5f0146669ff3b96812482c7802f5">setFuncSpec</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### setFuncSpec() {#a580e5f0146669ff3b96812482c7802f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IPSCCPOptions &amp; llvm::IPSCCPOptions::setFuncSpec (bool FuncSpec)</td>
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

<p>Enables or disables Specialization of Functions.</p>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sccp-h">SCCP.h</a>.</p>


<p>References <a href="#a46abeeea976ed98593f67b9ca4d60ec6">AllowFuncSpec</a> and <a href="#a068d538384d610da3d97e56d2a07fa96">IPSCCPOptions</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AllowFuncSpec {#a46abeeea976ed98593f67b9ca4d60ec6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IPSCCPOptions::AllowFuncSpec</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sccp-h">SCCP.h</a>.</p>


<p>Referenced by <a href="#a068d538384d610da3d97e56d2a07fa96">IPSCCPOptions</a> and <a href="#a580e5f0146669ff3b96812482c7802f5">setFuncSpec</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sccp-h">SCCP.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
