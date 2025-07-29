---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/functionvarlocsbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `FunctionVarLocsBuilder` Class

<p>Helper class to build FunctionVarLocs, since that class isn't easy to modify. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class FunctionVarLocsBuilder { ... }
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9848c6070f02f12648056d70d3884c8e">getNumVariables</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec2bf0c2cd1ac41ee26614348afeeb8c">insertVariable</a> (DebugVariable V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find or insert <span class="doxyComputerOutput">V</span> and return the <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. <a href="#aec2bf0c2cd1ac41ee26614348afeeb8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe7cb885c1a677f036f0aa21a03b96ac">getVariable</a> (VariableID ID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a variable from its <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a></span>. <a href="#afe7cb885c1a677f036f0aa21a03b96ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/varlocinfo">VarLocInfo</a> &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9263b193fc0f1585fc4d68fc9e0aee0e">getWedge</a> (VarLocInsertPt Before) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return ptr to wedge of defs or nullptr if no defs come just before /p Before. <a href="#a9263b193fc0f1585fc4d68fc9e0aee0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f8d8b3153be3260587c06c0cf6340f0">setWedge</a> (VarLocInsertPt Before, SmallVector&lt; VarLocInfo &gt; &amp;&amp;Wedge)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace the defs that come just before /p Before with /p Wedge. <a href="#a4f8d8b3153be3260587c06c0cf6340f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bdc6ab1fe66386aa7c0acc76c0c5c75">addSingleLocVar</a> (DebugVariable Var, DIExpression *Expr, DebugLoc DL, RawLocationWrapper R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a def for a variable that is valid for its lifetime. <a href="#a9bdc6ab1fe66386aa7c0acc76c0c5c75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6e3c63d3b0c045ac17a629271c3f981">addVarLoc</a> (VarLocInsertPt Before, DebugVariable Var, DIExpression *Expr, DebugLoc DL, RawLocationWrapper R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a def to the wedge of defs just before /p Before. <a href="#af6e3c63d3b0c045ac17a629271c3f981">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3ef33b07b60ec856f225bb6617a230e">FunctionVarLocs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/uniquevector">UniqueVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2208be074caf1c68003dd9161dc6fb81">Variables</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a6c7f6b65820380603c12c83d4d3b620c">VarLocInsertPt</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/varlocinfo">VarLocInfo</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af32ae17744b0604281c8e1deada5754b">VarLocsBeforeInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/varlocinfo">VarLocInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c5c66fe8d8037a647e8f8e151070b20">SingleLocVars</a></td>
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

<p>Helper class to build FunctionVarLocs, since that class isn't easy to modify.</p>


<p>TODO: There's not a great deal of value in the split, it could be worth merging the two classes.</p>


<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### addSingleLocVar() {#a9bdc6ab1fe66386aa7c0acc76c0c5c75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionVarLocsBuilder::addSingleLocVar (<a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a> Var, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, <a href="/web-llvm/docs/api/classes/llvm/rawlocationwrapper">RawLocationWrapper</a> R)</td>
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

<p>Add a def for a variable that is valid for its lifetime.</p>

<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/structs/llvm/varlocinfo/#ad7e310409e444bad60535cf956972194">llvm::VarLocInfo::DL</a>, <a href="/web-llvm/docs/api/structs/llvm/varlocinfo/#a2db7bf8bbe7f16fcee0e9f21aa87fe03">llvm::VarLocInfo::Expr</a>, <a href="#aec2bf0c2cd1ac41ee26614348afeeb8c">insertVariable</a>, <a href="/web-llvm/docs/api/structs/llvm/varlocinfo/#a95406039aa97abe00aa3b1265d846455">llvm::VarLocInfo::Values</a> and <a href="/web-llvm/docs/api/structs/llvm/varlocinfo/#af70494f348808c889f07f71f43cd28ec">llvm::VarLocInfo::VariableID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a4ad92667dcad9ad33a52a2e1c505a03a">buildOverlapMapAndRecordDeclares</a>.</p>

</div>
</div>

### addVarLoc() {#af6e3c63d3b0c045ac17a629271c3f981}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionVarLocsBuilder::addVarLoc (<a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a6c7f6b65820380603c12c83d4d3b620c">VarLocInsertPt</a> Before, <a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a> Var, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, <a href="/web-llvm/docs/api/classes/llvm/rawlocationwrapper">RawLocationWrapper</a> R)</td>
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

<p>Add a def to the wedge of defs just before /p Before.</p>

<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa9060587edeb01a63e3d3edc959678d1e">Before</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/structs/llvm/varlocinfo/#ad7e310409e444bad60535cf956972194">llvm::VarLocInfo::DL</a>, <a href="/web-llvm/docs/api/structs/llvm/varlocinfo/#a2db7bf8bbe7f16fcee0e9f21aa87fe03">llvm::VarLocInfo::Expr</a>, <a href="#aec2bf0c2cd1ac41ee26614348afeeb8c">insertVariable</a>, <a href="/web-llvm/docs/api/structs/llvm/varlocinfo/#a95406039aa97abe00aa3b1265d846455">llvm::VarLocInfo::Values</a> and <a href="/web-llvm/docs/api/structs/llvm/varlocinfo/#af70494f348808c889f07f71f43cd28ec">llvm::VarLocInfo::VariableID</a>.</p>

</div>
</div>

### getNumVariables() {#a9848c6070f02f12648056d70d3884c8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned FunctionVarLocsBuilder::getNumVariables ()</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a4ad92667dcad9ad33a52a2e1c505a03a">buildOverlapMapAndRecordDeclares</a>.</p>

</div>
</div>

### getVariable() {#afe7cb885c1a677f036f0aa21a03b96ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DebugVariable &amp; FunctionVarLocsBuilder::getVariable (<a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a> ID)</td>
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

<p>Get a variable from its <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a></span>.</p>

<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#ad959466c7f8b886a2caa4967c46d48db">removeRedundantDbgLocsUsingBackwardScan</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a72b4d4469e68630addc74e567526f261">removeRedundantDbgLocsUsingForwardScan</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a4e75fd1680471e758ffbca9f8d893884">removeUndefDbgLocsFromEntryBlock</a>.</p>

</div>
</div>

### getWedge() {#a9263b193fc0f1585fc4d68fc9e0aee0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallVectorImpl&lt; VarLocInfo &gt; * FunctionVarLocsBuilder::getWedge (<a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a6c7f6b65820380603c12c83d4d3b620c">VarLocInsertPt</a> Before)</td>
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

<p>Return ptr to wedge of defs or nullptr if no defs come just before /p Before.</p>

<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa9060587edeb01a63e3d3edc959678d1e">Before</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#ad959466c7f8b886a2caa4967c46d48db">removeRedundantDbgLocsUsingBackwardScan</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a72b4d4469e68630addc74e567526f261">removeRedundantDbgLocsUsingForwardScan</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a4e75fd1680471e758ffbca9f8d893884">removeUndefDbgLocsFromEntryBlock</a>.</p>

</div>
</div>

### insertVariable() {#aec2bf0c2cd1ac41ee26614348afeeb8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VariableID FunctionVarLocsBuilder::insertVariable (<a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a> V)</td>
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

<p>Find or insert <span class="doxyComputerOutput">V</span> and return the <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>

<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>


<p>Referenced by <a href="#a9bdc6ab1fe66386aa7c0acc76c0c5c75">addSingleLocVar</a>, <a href="#af6e3c63d3b0c045ac17a629271c3f981">addVarLoc</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a4ad92667dcad9ad33a52a2e1c505a03a">buildOverlapMapAndRecordDeclares</a>.</p>

</div>
</div>

### setWedge() {#a4f8d8b3153be3260587c06c0cf6340f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionVarLocsBuilder::setWedge (<a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a6c7f6b65820380603c12c83d4d3b620c">VarLocInsertPt</a> Before, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/varlocinfo">VarLocInfo</a> &gt; &amp;&amp; Wedge)</td>
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

<p>Replace the defs that come just before /p Before with /p Wedge.</p>

<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa9060587edeb01a63e3d3edc959678d1e">Before</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#ad959466c7f8b886a2caa4967c46d48db">removeRedundantDbgLocsUsingBackwardScan</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a72b4d4469e68630addc74e567526f261">removeRedundantDbgLocsUsingForwardScan</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a4e75fd1680471e758ffbca9f8d893884">removeUndefDbgLocsFromEntryBlock</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### FunctionVarLocs {#aa3ef33b07b60ec856f225bb6617a230e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend FunctionVarLocsBuilder::FunctionVarLocs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### SingleLocVars {#a0c5c66fe8d8037a647e8f8e151070b20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;VarLocInfo&gt; FunctionVarLocsBuilder::SingleLocVars</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### Variables {#a2208be074caf1c68003dd9161dc6fb81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UniqueVector&lt;DebugVariable&gt; FunctionVarLocsBuilder::Variables</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### VarLocsBeforeInst {#af32ae17744b0604281c8e1deada5754b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;VarLocInsertPt, SmallVector&lt;VarLocInfo&gt; &gt; FunctionVarLocsBuilder::VarLocsBeforeInst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
