---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-basicaliasanalysis-cpp-/linearexpression
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LinearExpression` Struct Reference

<p>Represents zext(sext(trunc(V))) * Scale + Offset. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{BasicAliasAnalysis.cpp}::LinearExpression { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeec6d17276ee78b63e78da5c2b7fb002">LinearExpression</a> (const CastedValue &amp;Val, const APInt &amp;Scale, const APInt &amp;Offset, bool IsNUW, bool IsNSW)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebdb60203b916f2447dad3c400d526aa">LinearExpression</a> (const CastedValue &amp;Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-basicaliasanalysis-cpp-/linearexpression">LinearExpression</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3260da72869dcac5e177b3cd64659c55">mul</a> (const APInt &amp;Other, bool MulIsNUW, bool MulIsNSW) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-basicaliasanalysis-cpp-/castedvalue">CastedValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4088881ed56d57db141b49cb3a32c5df">Val</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab559ee8bb970cc9ca8b0489d8999e24a">Scale</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e6f21a981cf9adfed7cfde7cdbfa966">Offset</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bb8ef57ba003081356665f842082c66">IsNUW</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if all operations in this expression are NUW. <a href="#a2bb8ef57ba003081356665f842082c66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b1ae6ab2115e476b3a973c799976b25">IsNSW</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if all operations in this expression are NSW. <a href="#a2b1ae6ab2115e476b3a973c799976b25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Represents zext(sext(trunc(V))) * Scale + Offset.</p>

<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LinearExpression() {#aeec6d17276ee78b63e78da5c2b7fb002}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{BasicAliasAnalysis.cpp}::LinearExpression::LinearExpression (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-basicaliasanalysis-cpp-/castedvalue">CastedValue</a> &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Scale, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Offset, bool IsNUW, bool IsNSW)</td>
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



<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>References <a href="#a2b1ae6ab2115e476b3a973c799976b25">IsNSW</a>, <a href="#a2bb8ef57ba003081356665f842082c66">IsNUW</a>, <a href="#a2e6f21a981cf9adfed7cfde7cdbfa966">Offset</a>, <a href="#ab559ee8bb970cc9ca8b0489d8999e24a">Scale</a> and <a href="#a4088881ed56d57db141b49cb3a32c5df">Val</a>.</p>


<p>Referenced by <a href="#a3260da72869dcac5e177b3cd64659c55">mul</a>.</p>

</div>
</div>

### LinearExpression() {#aebdb60203b916f2447dad3c400d526aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{BasicAliasAnalysis.cpp}::LinearExpression::LinearExpression (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-basicaliasanalysis-cpp-/castedvalue">CastedValue</a> &amp; Val)</td>
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



<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#a2b1ae6ab2115e476b3a973c799976b25">IsNSW</a>, <a href="#a2bb8ef57ba003081356665f842082c66">IsNUW</a>, <a href="#a2e6f21a981cf9adfed7cfde7cdbfa966">Offset</a>, <a href="#ab559ee8bb970cc9ca8b0489d8999e24a">Scale</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> and <a href="#a4088881ed56d57db141b49cb3a32c5df">Val</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### mul() {#a3260da72869dcac5e177b3cd64659c55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinearExpression anonymous{BasicAliasAnalysis.cpp}::LinearExpression::mul (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Other, bool MulIsNUW, bool MulIsNSW)</td>
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



<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>References <a href="#a2b1ae6ab2115e476b3a973c799976b25">IsNSW</a>, <a href="#a2bb8ef57ba003081356665f842082c66">IsNUW</a>, <a href="#aeec6d17276ee78b63e78da5c2b7fb002">LinearExpression</a>, <a href="#a2e6f21a981cf9adfed7cfde7cdbfa966">Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#ab559ee8bb970cc9ca8b0489d8999e24a">Scale</a> and <a href="#a4088881ed56d57db141b49cb3a32c5df">Val</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### IsNSW {#a2b1ae6ab2115e476b3a973c799976b25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{BasicAliasAnalysis.cpp}::LinearExpression::IsNSW</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if all operations in this expression are NSW.</p>

<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>Referenced by <a href="#aebdb60203b916f2447dad3c400d526aa">LinearExpression</a>, <a href="#aeec6d17276ee78b63e78da5c2b7fb002">LinearExpression</a> and <a href="#a3260da72869dcac5e177b3cd64659c55">mul</a>.</p>

</div>
</div>

### IsNUW {#a2bb8ef57ba003081356665f842082c66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{BasicAliasAnalysis.cpp}::LinearExpression::IsNUW</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if all operations in this expression are NUW.</p>

<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>Referenced by <a href="#aebdb60203b916f2447dad3c400d526aa">LinearExpression</a>, <a href="#aeec6d17276ee78b63e78da5c2b7fb002">LinearExpression</a> and <a href="#a3260da72869dcac5e177b3cd64659c55">mul</a>.</p>

</div>
</div>

### Offset {#a2e6f21a981cf9adfed7cfde7cdbfa966}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt anonymous{BasicAliasAnalysis.cpp}::LinearExpression::Offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>Referenced by <a href="#aebdb60203b916f2447dad3c400d526aa">LinearExpression</a>, <a href="#aeec6d17276ee78b63e78da5c2b7fb002">LinearExpression</a> and <a href="#a3260da72869dcac5e177b3cd64659c55">mul</a>.</p>

</div>
</div>

### Scale {#ab559ee8bb970cc9ca8b0489d8999e24a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt anonymous{BasicAliasAnalysis.cpp}::LinearExpression::Scale</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>Referenced by <a href="#aebdb60203b916f2447dad3c400d526aa">LinearExpression</a>, <a href="#aeec6d17276ee78b63e78da5c2b7fb002">LinearExpression</a> and <a href="#a3260da72869dcac5e177b3cd64659c55">mul</a>.</p>

</div>
</div>

### Val {#a4088881ed56d57db141b49cb3a32c5df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CastedValue anonymous{BasicAliasAnalysis.cpp}::LinearExpression::Val</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>Referenced by <a href="#aebdb60203b916f2447dad3c400d526aa">LinearExpression</a>, <a href="#aeec6d17276ee78b63e78da5c2b7fb002">LinearExpression</a> and <a href="#a3260da72869dcac5e177b3cd64659c55">mul</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
