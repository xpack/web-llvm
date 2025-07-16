---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/varlocinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `VarLocInfo` Struct Reference

<p>Variable location definition used by <a href="/web-llvm/docs/api/classes/llvm/functionvarlocs">FunctionVarLocs</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::VarLocInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/assignmenttrackinganalysis-h">llvm/CodeGen/AssignmentTrackingAnalysis.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">llvm::VariableID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af70494f348808c889f07f71f43cd28ec">VariableID</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2db7bf8bbe7f16fcee0e9f21aa87fe03">Expr</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7e310409e444bad60535cf956972194">DL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/rawlocationwrapper">RawLocationWrapper</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95406039aa97abe00aa3b1265d846455">Values</a> = <a href="/web-llvm/docs/api/classes/llvm/rawlocationwrapper">RawLocationWrapper</a>()</td>
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

<p>Variable location definition used by <a href="/web-llvm/docs/api/classes/llvm/functionvarlocs">FunctionVarLocs</a>.</p>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/assignmenttrackinganalysis-h">AssignmentTrackingAnalysis.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### DL {#ad7e310409e444bad60535cf956972194}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc llvm::VarLocInfo::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/assignmenttrackinganalysis-h">AssignmentTrackingAnalysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/functionvarlocsbuilder/#a9bdc6ab1fe66386aa7c0acc76c0c5c75">FunctionVarLocsBuilder::addSingleLocVar</a>, <a href="/web-llvm/docs/api/classes/functionvarlocsbuilder/#af6e3c63d3b0c045ac17a629271c3f981">FunctionVarLocsBuilder::addVarLoc</a>, <a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/#a81d863ec17163a5dcedc09cb1a48aadf">anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::emitDbgValue</a> and <a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/#a9db16f6b49d380b76183877d54b42c5c">anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::run</a>.</p>

</div>
</div>

### Expr {#a2db7bf8bbe7f16fcee0e9f21aa87fe03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIExpression* llvm::VarLocInfo::Expr = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/assignmenttrackinganalysis-h">AssignmentTrackingAnalysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/functionvarlocsbuilder/#a9bdc6ab1fe66386aa7c0acc76c0c5c75">FunctionVarLocsBuilder::addSingleLocVar</a>, <a href="/web-llvm/docs/api/classes/functionvarlocsbuilder/#af6e3c63d3b0c045ac17a629271c3f981">FunctionVarLocsBuilder::addVarLoc</a>, <a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/#a81d863ec17163a5dcedc09cb1a48aadf">anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::emitDbgValue</a> and <a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/#a9db16f6b49d380b76183877d54b42c5c">anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::run</a>.</p>

</div>
</div>

### Values {#a95406039aa97abe00aa3b1265d846455}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RawLocationWrapper llvm::VarLocInfo::Values = <a href="/web-llvm/docs/api/classes/llvm/rawlocationwrapper">RawLocationWrapper</a>()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/assignmenttrackinganalysis-h">AssignmentTrackingAnalysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/functionvarlocsbuilder/#a9bdc6ab1fe66386aa7c0acc76c0c5c75">FunctionVarLocsBuilder::addSingleLocVar</a>, <a href="/web-llvm/docs/api/classes/functionvarlocsbuilder/#af6e3c63d3b0c045ac17a629271c3f981">FunctionVarLocsBuilder::addVarLoc</a>, <a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/#a81d863ec17163a5dcedc09cb1a48aadf">anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::emitDbgValue</a> and <a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/#a9db16f6b49d380b76183877d54b42c5c">anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::run</a>.</p>

</div>
</div>

### VariableID {#af70494f348808c889f07f71f43cd28ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VariableID llvm::VarLocInfo::VariableID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/assignmenttrackinganalysis-h">AssignmentTrackingAnalysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/functionvarlocsbuilder/#a9bdc6ab1fe66386aa7c0acc76c0c5c75">FunctionVarLocsBuilder::addSingleLocVar</a>, <a href="/web-llvm/docs/api/classes/functionvarlocsbuilder/#af6e3c63d3b0c045ac17a629271c3f981">FunctionVarLocsBuilder::addVarLoc</a>, <a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/#a81d863ec17163a5dcedc09cb1a48aadf">anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::emitDbgValue</a> and <a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/#a9db16f6b49d380b76183877d54b42c5c">anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::run</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/assignmenttrackinganalysis-h">AssignmentTrackingAnalysis.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
