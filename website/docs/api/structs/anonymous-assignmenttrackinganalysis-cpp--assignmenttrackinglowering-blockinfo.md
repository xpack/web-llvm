---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/blockinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `BlockInfo` Struct Reference

<p>Represents the stack and debug assignments in a block. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::BlockInfo { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AssignmentKind { <a href="#a18dd7c40cb2aa433af76616e735090b8">...</a> }</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a6dbc33281ca02381e72c1f2fa02df7">operator==</a> (const BlockInfo &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare every element in each map to determine structural equality (slow). <a href="#a5a6dbc33281ca02381e72c1f2fa02df7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90de349e69c84d6914830dc69a24dce4">operator!=</a> (const BlockInfo &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/#aecd3fbed2e4d7501952b5de23ba8aba8">AssignmentMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6974ef522e174edd5d642a6c1944f64">getAssignmentMap</a> (AssignmentKind Kind) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/#aecd3fbed2e4d7501952b5de23ba8aba8">AssignmentMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcfc018005d820413373226a73d54df5">getAssignmentMap</a> (AssignmentKind Kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ae304c31727a0078847a77bcd03cc8f">isVariableTracked</a> (VariableID Var) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/assignment">Assignment</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a900eab1edc84fc7a4019a4a8e4265479">getAssignment</a> (AssignmentKind Kind, VariableID Var) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/#a4012a71c02f4a13c5234aea48e772f4c">LocKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad14a1f4665ec4ba25713394d96149c9f">getLocKind</a> (VariableID Var) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab36ee7c2540e102a20cbe92c353855c3">setLocKind</a> (VariableID Var, LocKind K)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set <a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/#a4012a71c02f4a13c5234aea48e772f4c">LocKind</a> for <span class="doxyComputerOutput">Var</span> only: does not set <a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/#a4012a71c02f4a13c5234aea48e772f4c">LocKind</a> for VariableIDs of fragments contained win <span class="doxyComputerOutput">Var</span>. <a href="#ab36ee7c2540e102a20cbe92c353855c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90796cfe4e37e29b83b767a3980b260e">setAssignment</a> (AssignmentKind Kind, VariableID Var, const Assignment &amp;AV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the assignment in the <span class="doxyComputerOutput">Kind</span> assignment map for <span class="doxyComputerOutput">Var</span> only: does not set the assignment for VariableIDs of fragments contained win <span class="doxyComputerOutput">Var</span>. <a href="#a90796cfe4e37e29b83b767a3980b260e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9949d7162eb05d27f378272a5fcdbd42">hasAssignment</a> (AssignmentKind Kind, VariableID Var, const Assignment &amp;AV) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if there is an assignment matching <span class="doxyComputerOutput">AV</span> in the <span class="doxyComputerOutput">Kind</span> assignment map. <a href="#a9949d7162eb05d27f378272a5fcdbd42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5428542a35fd4c95c834564dac738b2e">isValid</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2346dd54caeed393d2d20ea1b16cd884">init</a> (int NumVars)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear everything and initialise with ⊤-values for all variables. <a href="#a2346dd54caeed393d2d20ea1b16cd884">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12113c1e4ec4e1892f1b698037ef564e">VariableIDsInBlock</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of variables (<a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a>) being tracked in this block. <a href="#a12113c1e4ec4e1892f1b698037ef564e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/#aecd3fbed2e4d7501952b5de23ba8aba8">AssignmentMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e3def5ef72cac3b96b46dc49101455a">StackHomeValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dominating assignment to memory for each variable, indexed by <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a>. <a href="#a9e3def5ef72cac3b96b46dc49101455a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/#aecd3fbed2e4d7501952b5de23ba8aba8">AssignmentMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2aa7b8898030a62260d23b4cb2123e0e">DebugValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dominating assignemnt to each variable, indexed by <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a>. <a href="#a2aa7b8898030a62260d23b4cb2123e0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/#afadbf47f53cfe3d4eb25a3cb1e53b19d">LocMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2093a4ceea2a878bc3123b23f27ca2f2">LiveLoc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Location kind for each variable. <a href="#a2093a4ceea2a878bc3123b23f27ca2f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ElmtType, typename FnInputType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a54bf171d1df58ef76a0a3ca44e5da767">joinElmt</a> (int Index, SmallVector&lt; ElmtType &gt; &amp;Target, const SmallVector&lt; ElmtType &gt; &amp;A, const SmallVector&lt; ElmtType &gt; &amp;B, ElmtType(*Fn)(FnInputType, FnInputType))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper for join. <a href="#a54bf171d1df58ef76a0a3ca44e5da767">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static BlockInfo</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b2b6c6ae6de640c0773759a93aac1c1">join</a> (const BlockInfo &amp;A, const BlockInfo &amp;B, int NumVars)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See comment for AssignmentTrackingLowering::joinBlockInfo. <a href="#a9b2b6c6ae6de640c0773759a93aac1c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Represents the stack and debug assignments in a block.</p>


<p>Used to describe the live-in and live-out values for blocks, as well as the "current" value as we process each instruction in a block.</p>


<p>Definition at line 1145 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### AssignmentKind {#a18dd7c40cb2aa433af76616e735090b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::BlockInfo::AssignmentKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Stack<a id="a18dd7c40cb2aa433af76616e735090b8ad81a584233dbf7947dd5607751d03fb5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Debug<a id="a18dd7c40cb2aa433af76616e735090b8af4e2e71122e311bde75a6c3ee11c3aa2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1166 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a90de349e69c84d6914830dc69a24dce4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::BlockInfo::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BlockInfo &amp; Other)</td>
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



<p>Definition at line 1230 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### operator==() {#a5a6dbc33281ca02381e72c1f2fa02df7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::BlockInfo::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BlockInfo &amp; Other)</td>
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

<p>Compare every element in each map to determine structural equality (slow).</p>

<p>Definition at line 1223 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAssignment() {#a900eab1edc84fc7a4019a4a8e4265479}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Assignment &amp; anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::BlockInfo::getAssignment (AssignmentKind Kind, <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a> Var)</td>
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



<p>Definition at line 1185 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### getAssignmentMap() {#ae6974ef522e174edd5d642a6c1944f64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AssignmentMap &amp; anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::BlockInfo::getAssignmentMap (AssignmentKind Kind)</td>
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



<p>Definition at line 1167 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### getAssignmentMap() {#abcfc018005d820413373226a73d54df5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssignmentMap &amp; anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::BlockInfo::getAssignmentMap (AssignmentKind Kind)</td>
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



<p>Definition at line 1176 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### getLocKind() {#ad14a1f4665ec4ba25713394d96149c9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocKind anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::BlockInfo::getLocKind (<a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a> Var)</td>
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



<p>Definition at line 1190 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### hasAssignment() {#a9949d7162eb05d27f378272a5fcdbd42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::BlockInfo::hasAssignment (AssignmentKind Kind, <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a> Var, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/assignment">Assignment</a> &amp; AV)</td>
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

<p>Return true if there is an assignment matching <span class="doxyComputerOutput">AV</span> in the <span class="doxyComputerOutput">Kind</span> assignment map.</p>


<p>Does consider assignments for VariableIDs of fragments contained win <span class="doxyComputerOutput">Var</span>.</p>


<p>Definition at line 1214 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### init() {#a2346dd54caeed393d2d20ea1b16cd884}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::BlockInfo::init (int NumVars)</td>
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

<p>Clear everything and initialise with ⊤-values for all variables.</p>

<p>Definition at line 1237 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### isValid() {#a5428542a35fd4c95c834564dac738b2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::BlockInfo::isValid ()</td>
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



<p>Definition at line 1231 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### isVariableTracked() {#a3ae304c31727a0078847a77bcd03cc8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::BlockInfo::isVariableTracked (<a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a> Var)</td>
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



<p>Definition at line 1181 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### setAssignment() {#a90796cfe4e37e29b83b767a3980b260e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::BlockInfo::setAssignment (AssignmentKind Kind, <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a> Var, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/assignment">Assignment</a> &amp; AV)</td>
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

<p>Set the assignment in the <span class="doxyComputerOutput">Kind</span> assignment map for <span class="doxyComputerOutput">Var</span> only: does not set the assignment for VariableIDs of fragments contained win <span class="doxyComputerOutput">Var</span>.</p>

<p>Definition at line 1205 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### setLocKind() {#ab36ee7c2540e102a20cbe92c353855c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::BlockInfo::setLocKind (<a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a> Var, <a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/#a4012a71c02f4a13c5234aea48e772f4c">LocKind</a> K)</td>
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

<p>Set <a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/#a4012a71c02f4a13c5234aea48e772f4c">LocKind</a> for <span class="doxyComputerOutput">Var</span> only: does not set <a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/#a4012a71c02f4a13c5234aea48e772f4c">LocKind</a> for VariableIDs of fragments contained win <span class="doxyComputerOutput">Var</span>.</p>

<p>Definition at line 1197 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DebugValue {#a2aa7b8898030a62260d23b4cb2123e0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssignmentMap anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::BlockInfo::DebugValue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dominating assignemnt to each variable, indexed by <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a>.</p>

<p>Definition at line 1152 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### LiveLoc {#a2093a4ceea2a878bc3123b23f27ca2f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocMap anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::BlockInfo::LiveLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Location kind for each variable.</p>


<p>LiveLoc indicates whether the dominating assignment in StackHomeValue (<a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/#a4012a71c02f4a13c5234aea48e772f4cadba5553473d129a7985fb532dc249ff4">LocKind::Mem</a>), DebugValue (<a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/#a4012a71c02f4a13c5234aea48e772f4ca5988c20a047cfe063999787584b0aca7">LocKind::Val</a>), or neither (<a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/#a4012a71c02f4a13c5234aea48e772f4ca6adf97f83acf6453d4a6a4b1070f3754">LocKind::None</a>) is valid, in that order of preference. This cannot be derived by inspecting DebugValue and StackHomeValue due to the fact that there's no distinction in <a href="/web-llvm/docs/api/structs/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/assignment">Assignment</a> (the class) between whether an assignment is unknown or a merge of multiple assignments (both are Status::NoneOrPhi). In other words, the memory location may well be valid while both DebugValue and StackHomeValue contain Assignments that have a <a href="/web-llvm/docs/api/structs/status">Status</a> of NoneOrPhi. Indexed by <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a>.</p>


<p>Definition at line 1163 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### StackHomeValue {#a9e3def5ef72cac3b96b46dc49101455a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssignmentMap anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::BlockInfo::StackHomeValue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dominating assignment to memory for each variable, indexed by <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a>.</p>

<p>Definition at line 1150 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### VariableIDsInBlock {#a12113c1e4ec4e1892f1b698037ef564e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::BlockInfo::VariableIDsInBlock</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of variables (<a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a>) being tracked in this block.</p>

<p>Definition at line 1147 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### join() {#a9b2b6c6ae6de640c0773759a93aac1c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockInfo anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::BlockInfo::join (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BlockInfo &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BlockInfo &amp; B, int NumVars)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>See comment for AssignmentTrackingLowering::joinBlockInfo.</p>

<p>Definition at line 1259 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### joinElmt() {#a54bf171d1df58ef76a0a3ca44e5da767}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ElmtType, typename FnInputType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::BlockInfo::joinElmt (int Index, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; ElmtType &gt; &amp; Target, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; ElmtType &gt; &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; ElmtType &gt; &amp; B, ElmtType(*)(FnInputType, FnInputType) Fn)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper for join.</p>

<p>Definition at line 1251 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
