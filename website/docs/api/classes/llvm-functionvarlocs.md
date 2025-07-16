---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/functionvarlocs
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `FunctionVarLocs` Class Reference

<p>Data structure describing the variable locations in a function. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::FunctionVarLocs { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/assignmenttrackinganalysis-h">llvm/CodeGen/AssignmentTrackingAnalysis.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8922bc00acf83e71c7f2d47bbcfc0f6">init</a> (FunctionVarLocsBuilder &amp;Builder)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe10e34cd384a2508d34c3b01c5f9866">clear</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa99e4e7d8afaee8fb8a1b3ca0158492a">getDILocalVariable</a> (const VarLocInfo *Loc) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> for the location definition represented by <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a></span>. <a href="#aa99e4e7d8afaee8fb8a1b3ca0158492a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba7fbaeadfac6ae40589e8c2e220da17">getDILocalVariable</a> (VariableID ID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> of the variable represented by <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a></span>. <a href="#aba7fbaeadfac6ae40589e8c2e220da17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac56c6c146df7c7cc4dd5feec8ad8b3e7">getVariable</a> (VariableID ID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a> represented by <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a></span>. <a href="#ac56c6c146df7c7cc4dd5feec8ad8b3e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49453c652051a3e7530ed421bf160c92">print</a> (raw_ostream &amp;OS, const Function &amp;Fn) const</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7df06c821743c0e4bffb8a91a11f7831">Variables</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps <a href="/web-llvm/docs/api/structs/llvm/varlocinfo/#af70494f348808c889f07f71f43cd28ec">VarLocInfo.VariableID</a> to a <a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a> for VarLocRecords. <a href="#a7df06c821743c0e4bffb8a91a11f7831">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/varlocinfo">VarLocInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5abfaf923648478c4c25d6c2ca7e452">VarLocRecords</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of variable location changes grouped by the instruction the change occurs before (see VarLocsBeforeInst). <a href="#ac5abfaf923648478c4c25d6c2ca7e452">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3d4345aafddc924fa9b77466fb95df4">SingleVarLocEnd</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>End of range of VarLocRecords that represent variables with a single location that is valid for the entire scope. <a href="#ac3d4345aafddc924fa9b77466fb95df4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, std::pair&lt; unsigned, unsigned &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85043ecc4b4d23c5bf4332194b10afc5">VarLocsBeforeInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps an instruction to a range of VarLocs that start just before it. <a href="#a85043ecc4b4d23c5bf4332194b10afc5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## iterators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/varlocinfo">VarLocInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82ac348d37f9d4342bf7f7c9433b213c">single_locs_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/varlocinfo">VarLocInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebd1b22de49da2b8b99ad3238bbdad46">single_locs_end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>One past the last single-location variable location definition. <a href="#aebd1b22de49da2b8b99ad3238bbdad46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/varlocinfo">VarLocInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a765a03bce8a48a073d6c1c7321408631">locs_begin</a> (const Instruction *Before) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>First variable location definition that comes before <span class="doxyComputerOutput">Before</span>. <a href="#a765a03bce8a48a073d6c1c7321408631">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/varlocinfo">VarLocInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae40c1e35b923034f750710e914e02d92">locs_end</a> (const Instruction *Before) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>One past the last variable location definition that comes before <span class="doxyComputerOutput">Before</span>. <a href="#ae40c1e35b923034f750710e914e02d92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Data structure describing the variable locations in a function.</p>


<p>Used as the result of the <a href="/web-llvm/docs/api/classes/llvm/assignmenttrackinganalysis">AssignmentTrackingAnalysis</a> pass. Essentially read-only outside of <a href="/web-llvm/docs/api/classes/llvm/assignmenttrackinganalysis">AssignmentTrackingAnalysis</a> where it is built.</p>


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/assignmenttrackinganalysis-h">AssignmentTrackingAnalysis.h</a>.</p>


<div class="doxySectionDef">

## Functions

### clear() {#abe10e34cd384a2508d34c3b01c5f9866}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionVarLocs::clear ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/assignmenttrackinganalysis-h">AssignmentTrackingAnalysis.h</a>, definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### init() {#af8922bc00acf83e71c7f2d47bbcfc0f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionVarLocs::init (<a href="/web-llvm/docs/api/classes/functionvarlocsbuilder">FunctionVarLocsBuilder</a> &amp; Builder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Non-const methods used by <a href="/web-llvm/docs/api/classes/llvm/assignmenttrackinganalysis">AssignmentTrackingAnalysis</a> (which invalidate analysis results if called incorrectly).</p>


<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/assignmenttrackinganalysis-h">AssignmentTrackingAnalysis.h</a>, definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae876eb96b89c1afcc3e9cd285cc3f08c">llvm::filterDbgVars</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getDILocalVariable() {#aa99e4e7d8afaee8fb8a1b3ca0158492a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DILocalVariable * llvm::FunctionVarLocs::getDILocalVariable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/varlocinfo">VarLocInfo</a> * Loc)</td>
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

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> for the location definition represented by <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a></span>.</p>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/assignmenttrackinganalysis-h">AssignmentTrackingAnalysis.h</a>.</p>


<p>Reference <a href="#aa99e4e7d8afaee8fb8a1b3ca0158492a">getDILocalVariable</a>.</p>


<p>Referenced by <a href="#aa99e4e7d8afaee8fb8a1b3ca0158492a">getDILocalVariable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#a4e3d084d08365c418611e1002a444016">processSingleLocVars</a>.</p>

</div>
</div>

### getDILocalVariable() {#aba7fbaeadfac6ae40589e8c2e220da17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DILocalVariable * llvm::FunctionVarLocs::getDILocalVariable (<a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a> ID)</td>
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

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> of the variable represented by <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a></span>.</p>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/assignmenttrackinganalysis-h">AssignmentTrackingAnalysis.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/debugvariable/#af2ca096ab72c055f6c2c7e3ffbe5d6bf">llvm::DebugVariable::getVariable</a> and <a href="#ac56c6c146df7c7cc4dd5feec8ad8b3e7">getVariable</a>.</p>

</div>
</div>

### getVariable() {#ac56c6c146df7c7cc4dd5feec8ad8b3e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DebugVariable &amp; llvm::FunctionVarLocs::getVariable (<a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a> ID)</td>
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

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a> represented by <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a></span>.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/assignmenttrackinganalysis-h">AssignmentTrackingAnalysis.h</a>.</p>


<p>Referenced by <a href="#aba7fbaeadfac6ae40589e8c2e220da17">getDILocalVariable</a>.</p>

</div>
</div>

### print() {#a49453c652051a3e7530ed421bf160c92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionVarLocs::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/assignmenttrackinganalysis-h">AssignmentTrackingAnalysis.h</a>, definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a765a03bce8a48a073d6c1c7321408631">locs_begin</a>, <a href="#ae40c1e35b923034f750710e914e02d92">locs_end</a>, <a href="#a82ac348d37f9d4342bf7f7c9433b213c">single_locs_begin</a> and <a href="#aebd1b22de49da2b8b99ad3238bbdad46">single_locs_end</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### SingleVarLocEnd {#ac3d4345aafddc924fa9b77466fb95df4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FunctionVarLocs::SingleVarLocEnd = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>End of range of VarLocRecords that represent variables with a single location that is valid for the entire scope.</p>


<p>Range starts at 0.</p>


<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/assignmenttrackinganalysis-h">AssignmentTrackingAnalysis.h</a>.</p>

</div>
</div>

### Variables {#a7df06c821743c0e4bffb8a91a11f7831}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;DebugVariable&gt; llvm::FunctionVarLocs::Variables</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps <a href="/web-llvm/docs/api/structs/llvm/varlocinfo/#af70494f348808c889f07f71f43cd28ec">VarLocInfo.VariableID</a> to a <a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a> for VarLocRecords.</p>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/assignmenttrackinganalysis-h">AssignmentTrackingAnalysis.h</a>.</p>

</div>
</div>

### VarLocRecords {#ac5abfaf923648478c4c25d6c2ca7e452}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;VarLocInfo&gt; llvm::FunctionVarLocs::VarLocRecords</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of variable location changes grouped by the instruction the change occurs before (see VarLocsBeforeInst).</p>


<p>The elements from zero to SingleVarLocEnd represent variables with a single location.</p>


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/assignmenttrackinganalysis-h">AssignmentTrackingAnalysis.h</a>.</p>

</div>
</div>

### VarLocsBeforeInst {#a85043ecc4b4d23c5bf4332194b10afc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Instruction *, std::pair&lt;unsigned, unsigned&gt; &gt; llvm::FunctionVarLocs::VarLocsBeforeInst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps an instruction to a range of VarLocs that start just before it.</p>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/assignmenttrackinganalysis-h">AssignmentTrackingAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## iterators

### locs\_begin {#a765a03bce8a48a073d6c1c7321408631}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VarLocInfo * llvm::FunctionVarLocs::locs_begin (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Before)</td>
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

<p>First variable location definition that comes before <span class="doxyComputerOutput">Before</span>.</p>

<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/assignmenttrackinganalysis-h">AssignmentTrackingAnalysis.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa9060587edeb01a63e3d3edc959678d1e">Before</a>.</p>


<p>Referenced by <a href="#a49453c652051a3e7530ed421bf160c92">print</a>.</p>

</div>
</div>

### locs\_end {#ae40c1e35b923034f750710e914e02d92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VarLocInfo * llvm::FunctionVarLocs::locs_end (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Before)</td>
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

<p>One past the last variable location definition that comes before <span class="doxyComputerOutput">Before</span>.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/assignmenttrackinganalysis-h">AssignmentTrackingAnalysis.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa9060587edeb01a63e3d3edc959678d1e">Before</a>.</p>


<p>Referenced by <a href="#a49453c652051a3e7530ed421bf160c92">print</a>.</p>

</div>
</div>

### single\_locs\_begin {#a82ac348d37f9d4342bf7f7c9433b213c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VarLocInfo * llvm::FunctionVarLocs::single_locs_begin ()</td>
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




<p>First single-location variable location definition.</p>


<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/assignmenttrackinganalysis-h">AssignmentTrackingAnalysis.h</a>.</p>


<p>Referenced by <a href="#a49453c652051a3e7530ed421bf160c92">print</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#a4e3d084d08365c418611e1002a444016">processSingleLocVars</a>.</p>

</div>
</div>

### single\_locs\_end {#aebd1b22de49da2b8b99ad3238bbdad46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VarLocInfo * llvm::FunctionVarLocs::single_locs_end ()</td>
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

<p>One past the last single-location variable location definition.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/assignmenttrackinganalysis-h">AssignmentTrackingAnalysis.h</a>.</p>


<p>Referenced by <a href="#a49453c652051a3e7530ed421bf160c92">print</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#a4e3d084d08365c418611e1002a444016">processSingleLocVars</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/assignmenttrackinganalysis-h">AssignmentTrackingAnalysis.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
