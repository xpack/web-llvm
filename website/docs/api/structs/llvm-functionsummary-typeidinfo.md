---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/functionsummary/typeidinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `TypeIdInfo` Struct

<p>All type identifier related information. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::FunctionSummary::TypeIdInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">llvm/IR/ModuleSummaryIndex.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3aad34dbb3cc1fb6daa0a79dbcf5166">TypeTests</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of type identifiers used by this function in llvm.type.test intrinsics referenced by something other than an llvm.assume intrinsic, represented as GUIDs. <a href="#ab3aad34dbb3cc1fb6daa0a79dbcf5166">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/vfuncid">VFuncId</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6b8eea40d56e793d1c5cd4d1b921147">TypeTestAssumeVCalls</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of virtual calls made by this function using (respectively) llvm.assume(llvm.type.test) or llvm.type.checked.load intrinsics that do not have all constant integer arguments. <a href="#ab6b8eea40d56e793d1c5cd4d1b921147">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/vfuncid">VFuncId</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9173f15dad28f7e5e05a4b133fc54021">TypeCheckedLoadVCalls</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/constvcall">ConstVCall</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0f29b48b080b735fa7f1a579d2a8936">TypeTestAssumeConstVCalls</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of virtual calls made by this function using (respectively) llvm.assume(llvm.type.test) or llvm.type.checked.load intrinsics with all constant integer arguments. <a href="#ab0f29b48b080b735fa7f1a579d2a8936">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/constvcall">ConstVCall</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fd68c70ca503931dfedb66add9ddaf1">TypeCheckedLoadConstVCalls</a></td>
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

<p>All type identifier related information.</p>


<p>Because these fields are relatively uncommon we only allocate space for them if necessary.</p>


<p>Definition at line 751 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### TypeCheckedLoadConstVCalls {#a5fd68c70ca503931dfedb66add9ddaf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;ConstVCall&gt; llvm::FunctionSummary::TypeIdInfo::TypeCheckedLoadConstVCalls</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 766 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ae452e35369a6552e0059f13304193c49">anonymous{AsmWriter.cpp}::AssemblyWriter::printTypeIdInfo</a>.</p>

</div>
</div>

### TypeCheckedLoadVCalls {#a9173f15dad28f7e5e05a4b133fc54021}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;VFuncId&gt; llvm::FunctionSummary::TypeIdInfo::TypeCheckedLoadVCalls</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 760 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ae452e35369a6552e0059f13304193c49">anonymous{AsmWriter.cpp}::AssemblyWriter::printTypeIdInfo</a>.</p>

</div>
</div>

### TypeTestAssumeConstVCalls {#ab0f29b48b080b735fa7f1a579d2a8936}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;ConstVCall&gt; llvm::FunctionSummary::TypeIdInfo::TypeTestAssumeConstVCalls</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of virtual calls made by this function using (respectively) llvm.assume(llvm.type.test) or llvm.type.checked.load intrinsics with all constant integer arguments.</p>

<p>Definition at line 765 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ae452e35369a6552e0059f13304193c49">anonymous{AsmWriter.cpp}::AssemblyWriter::printTypeIdInfo</a>.</p>

</div>
</div>

### TypeTestAssumeVCalls {#ab6b8eea40d56e793d1c5cd4d1b921147}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;VFuncId&gt; llvm::FunctionSummary::TypeIdInfo::TypeTestAssumeVCalls</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of virtual calls made by this function using (respectively) llvm.assume(llvm.type.test) or llvm.type.checked.load intrinsics that do not have all constant integer arguments.</p>

<p>Definition at line 760 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ae452e35369a6552e0059f13304193c49">anonymous{AsmWriter.cpp}::AssemblyWriter::printTypeIdInfo</a>.</p>

</div>
</div>

### TypeTests {#ab3aad34dbb3cc1fb6daa0a79dbcf5166}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;GlobalValue::GUID&gt; llvm::FunctionSummary::TypeIdInfo::TypeTests</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of type identifiers used by this function in llvm.type.test intrinsics referenced by something other than an llvm.assume intrinsic, represented as GUIDs.</p>

<p>Definition at line 755 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ae452e35369a6552e0059f13304193c49">anonymous{AsmWriter.cpp}::AssemblyWriter::printTypeIdInfo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
