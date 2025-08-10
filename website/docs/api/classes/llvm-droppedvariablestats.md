---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/droppedvariablestats
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DroppedVariableStats` Class

<p>A base class to collect and print dropped debug information variable statistics. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DroppedVariableStats { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestats-h">llvm/Passes/DroppedVariableStats.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/droppedvariablestatsir">DroppedVariableStatsIR</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A class to collect and print dropped debug information due to LLVM IR optimization passes. <a href="/web-llvm/docs/api/classes/llvm/droppedvariablestatsir/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46f071337fdc4a5ed806508f6b6073b4">DroppedVariableStats</a> (bool DroppedVarStatsEnabled)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57364af948f3e0f629a32882a0e7f68b">DroppedVariableStats</a> (const DroppedVariableStats &amp;)=delete</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addabc63a03c26b62477fb7af2490f574">~DroppedVariableStats</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad32f8e42bb15683d18d8a78de0f854cc">operator=</a> (const DroppedVariableStats &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2849714d5e1cfb51a1df91c1bc855dcb">getPassDroppedVariables</a> ()</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb370e0ed83426862695812314133aa7">setup</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab91542990bbb5413110da7acf1815924">cleanup</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a039613c35cae74dbc1b9f2bcdc793f9e">calculateDroppedStatsAndPrint</a> (DebugVariables &amp;DbgVariables, StringRef FuncName, StringRef PassID, StringRef FuncOrModName, StringRef PassLevel, const Function *Func)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate the number of dropped variables in an <a href="/web-llvm/docs/api/classes/llvm/function">llvm::Function</a> or <a href="/web-llvm/docs/api/classes/llvm/machinefunction">llvm::MachineFunction</a> and print the relevant information to stdout. <a href="#a039613c35cae74dbc1b9f2bcdc793f9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75d47320ab41eb44b12c355c8a3e9fe7">updateDroppedCount</a> (DILocation *DbgLoc, const DIScope *Scope, const DIScope *DbgValScope, DenseMap&lt; VarID, DILocation * &gt; &amp;InlinedAtsMap, VarID Var, unsigned &amp;DroppedCount)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a <span class="doxyComputerOutput">Var</span> has been dropped or is a false positive. <a href="#a75d47320ab41eb44b12c355c8a3e9fe7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a848e174c81c6209939940cb31f1353cf">run</a> (DebugVariables &amp;DbgVariables, StringRef FuncName, bool Before)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run code to populate relevant data structures over an <a href="/web-llvm/docs/api/classes/llvm/function">llvm::Function</a> or <a href="/web-llvm/docs/api/classes/llvm/machinefunction">llvm::MachineFunction</a>. <a href="#a848e174c81c6209939940cb31f1353cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ad1df667a6a13366805e55ea363ee9b">populateVarIDSetAndInlinedMap</a> (const DILocalVariable *DbgVar, DebugLoc DbgLoc, DenseSet&lt; VarID &gt; &amp;VarIDSet, DenseMap&lt; StringRef, DenseMap&lt; VarID, DILocation * &gt; &gt; &amp;InlinedAtsMap, StringRef FuncName, bool Before)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Populate the VarIDSet and InlinedAtMap with the relevant information needed for before and after pass analysis to determine dropped variable status. <a href="#a2ad1df667a6a13366805e55ea363ee9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1eb80ff593f2b7c49f83baaa60306b25">visitEveryInstruction</a> (unsigned &amp;DroppedCount, DenseMap&lt; VarID, DILocation * &gt; &amp;InlinedAtsMap, VarID Var)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Visit every <a href="/web-llvm/docs/api/classes/llvm/instruction">llvm::Instruction</a> or llvm::MachineInstruction and check if the debug variable denoted by its <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> <span class="doxyComputerOutput">Var</span> may have been dropped by an optimization pass. <a href="#a1eb80ff593f2b7c49f83baaa60306b25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39ae6f33a21851aaab9d15fcb979c037">visitEveryDebugRecord</a> (DenseSet&lt; VarID &gt; &amp;VarIDSet, DenseMap&lt; StringRef, DenseMap&lt; VarID, DILocation * &gt; &gt; &amp;InlinedAtsMap, StringRef FuncName, bool Before)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Visit every debug record in an <a href="/web-llvm/docs/api/classes/llvm/function">llvm::Function</a> or <a href="/web-llvm/docs/api/classes/llvm/machinefunction">llvm::MachineFunction</a> and call populateVarIDSetAndInlinedMap on it. <a href="#a39ae6f33a21851aaab9d15fcb979c037">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e4c7649922447cb5f1fc59c5a9ee77b">removeVarFromAllSets</a> (VarID Var, const Function *F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove a dropped debug variable's <a href="/web-llvm/docs/api/namespaces/llvm/#a07ea053ea2cdbee8e68ebd607c26dc8a">VarID</a> from all Sets in the DroppedVariablesBefore stack. <a href="#a5e4c7649922447cb5f1fc59c5a9ee77b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66487f37dbb3cafb85728feda13892e0">isScopeChildOfOrEqualTo</a> (const DIScope *Scope, const DIScope *DbgValScope)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">Scope</span> is the same as <span class="doxyComputerOutput">DbgValScope</span> or a child scope of <span class="doxyComputerOutput">DbgValScope</span>, return false otherwise. <a href="#a66487f37dbb3cafb85728feda13892e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fdbc373ce011810665540c9e898e989">isInlinedAtChildOfOrEqualTo</a> (const DILocation *InlinedAt, const DILocation *DbgValInlinedAt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">InlinedAt</span> is the same as <span class="doxyComputerOutput">DbgValInlinedAt</span> or part of the InlinedAt chain, return false otherwise. <a href="#a8fdbc373ce011810665540c9e898e989">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6868779973ca0e558f17521d7810da52">DroppedVariableStatsEnabled</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, <a href="/web-llvm/docs/api/structs/llvm/droppedvariablestats/debugvariables">DebugVariables</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a956a96918980eb304dedaa78b88c0d3c">DebugVariablesStack</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A stack of a <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>, that maps <a href="/web-llvm/docs/api/structs/llvm/droppedvariablestats/debugvariables">DebugVariables</a> for every pass to an <a href="/web-llvm/docs/api/classes/llvm/function">llvm::Function</a>. <a href="#a956a96918980eb304dedaa78b88c0d3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07e15724976aed7adc5b3a178548ca77">VisitedScope</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a> tracking whether a scope was visited before. <a href="#a07e15724976aed7adc5b3a178548ca77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a07ea053ea2cdbee8e68ebd607c26dc8a">VarID</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * &gt; &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a276914a247d61781f51e41186a9dc2af">InlinedAts</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A stack of DenseMaps, which map the name of an <a href="/web-llvm/docs/api/classes/llvm/function">llvm::Function</a> to a <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a> of VarIDs and their inlinedAt locations before an optimization pass has run. <a href="#a276914a247d61781f51e41186a9dc2af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9530fc2d82858ef5f7f0f05a572b0451">PassDroppedVariables</a> = false</td>
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

<p>A base class to collect and print dropped debug information variable statistics.</p>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestats-h">DroppedVariableStats.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DroppedVariableStats() {#a46f071337fdc4a5ed806508f6b6073b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DroppedVariableStats::DroppedVariableStats (bool DroppedVarStatsEnabled)</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestats-h">DroppedVariableStats.h</a>.</p>


<p>References <a href="#a6868779973ca0e558f17521d7810da52">DroppedVariableStatsEnabled</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2d79a00fa7c56f57b87f2fe2a3f118c7">llvm::outs</a>.</p>


<p>Referenced by <a href="#a57364af948f3e0f629a32882a0e7f68b">DroppedVariableStats</a>, <a href="/web-llvm/docs/api/classes/llvm/droppedvariablestatsir/#ab45a0f0dfd5a887154fffaae4cc6e3be">llvm::DroppedVariableStatsIR::DroppedVariableStatsIR</a> and <a href="#ad32f8e42bb15683d18d8a78de0f854cc">operator=</a>.</p>

</div>
</div>

### DroppedVariableStats() {#a57364af948f3e0f629a32882a0e7f68b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DroppedVariableStats::DroppedVariableStats (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/droppedvariablestats">DroppedVariableStats</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestats-h">DroppedVariableStats.h</a>.</p>


<p>Reference <a href="#a46f071337fdc4a5ed806508f6b6073b4">DroppedVariableStats</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DroppedVariableStats() {#addabc63a03c26b62477fb7af2490f574}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::DroppedVariableStats::~DroppedVariableStats ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestats-h">DroppedVariableStats.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#ad32f8e42bb15683d18d8a78de0f854cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DroppedVariableStats::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/droppedvariablestats">DroppedVariableStats</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestats-h">DroppedVariableStats.h</a>.</p>


<p>Reference <a href="#a46f071337fdc4a5ed806508f6b6073b4">DroppedVariableStats</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getPassDroppedVariables() {#a2849714d5e1cfb51a1df91c1bc855dcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DroppedVariableStats::getPassDroppedVariables ()</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestats-h">DroppedVariableStats.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### calculateDroppedStatsAndPrint() {#a039613c35cae74dbc1b9f2bcdc793f9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DroppedVariableStats::calculateDroppedStatsAndPrint (<a href="/web-llvm/docs/api/structs/llvm/droppedvariablestats/debugvariables">DebugVariables</a> &amp; DbgVariables, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FuncName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassID, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FuncOrModName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassLevel, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Func)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate the number of dropped variables in an <a href="/web-llvm/docs/api/classes/llvm/function">llvm::Function</a> or <a href="/web-llvm/docs/api/classes/llvm/machinefunction">llvm::MachineFunction</a> and print the relevant information to stdout.</p>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestats-h">DroppedVariableStats.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad409c2de8502b94c8a0b1193307c63b6">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::contains</a>, <a href="/web-llvm/docs/api/structs/llvm/droppedvariablestats/debugvariables/#a5e4d16731206131193654cbea6408074">llvm::DroppedVariableStats::DebugVariables::DebugVariablesAfter</a>, <a href="/web-llvm/docs/api/structs/llvm/droppedvariablestats/debugvariables/#ae0035704c71ffaf5c1e72109a3209140">llvm::DroppedVariableStats::DebugVariables::DebugVariablesBefore</a>, <a href="#a276914a247d61781f51e41186a9dc2af">InlinedAts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2d79a00fa7c56f57b87f2fe2a3f118c7">llvm::outs</a> and <a href="#a1eb80ff593f2b7c49f83baaa60306b25">visitEveryInstruction</a>.</p>

</div>
</div>

### cleanup() {#ab91542990bbb5413110da7acf1815924}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DroppedVariableStats::cleanup ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestats-h">DroppedVariableStats.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a956a96918980eb304dedaa78b88c0d3c">DebugVariablesStack</a> and <a href="#a276914a247d61781f51e41186a9dc2af">InlinedAts</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/droppedvariablestatsir/#a098ebeae73eb3b1c09384466602931e7">llvm::DroppedVariableStatsIR::registerCallbacks</a> and <a href="/web-llvm/docs/api/classes/llvm/droppedvariablestatsir/#abe7c231e11ef6c5345cbf3f9e9ae7979">llvm::DroppedVariableStatsIR::runAfterPass</a>.</p>

</div>
</div>

### populateVarIDSetAndInlinedMap() {#a2ad1df667a6a13366805e55ea363ee9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DroppedVariableStats::populateVarIDSetAndInlinedMap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * DbgVar, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DbgLoc, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a07ea053ea2cdbee8e68ebd607c26dc8a">VarID</a> &gt; &amp; VarIDSet, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a07ea053ea2cdbee8e68ebd607c26dc8a">VarID</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * &gt; &gt; &amp; InlinedAtsMap, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FuncName, bool Before)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Populate the VarIDSet and InlinedAtMap with the relevant information needed for before and after pass analysis to determine dropped variable status.</p>

<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestats-h">DroppedVariableStats.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa9060587edeb01a63e3d3edc959678d1e">Before</a>, <a href="/web-llvm/docs/api/classes/llvm/debugloc/#ada0b6f3c53a53b7274e7aeb23eeab5a8">llvm::DebugLoc::getInlinedAt</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable/#a38229438b1c22802074b3181b0b80b85">llvm::DILocalVariable::getScope</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a> and <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>.</p>

</div>
</div>

### run() {#a848e174c81c6209939940cb31f1353cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DroppedVariableStats::run (<a href="/web-llvm/docs/api/structs/llvm/droppedvariablestats/debugvariables">DebugVariables</a> &amp; DbgVariables, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FuncName, bool Before)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run code to populate relevant data structures over an <a href="/web-llvm/docs/api/classes/llvm/function">llvm::Function</a> or <a href="/web-llvm/docs/api/classes/llvm/machinefunction">llvm::MachineFunction</a>.</p>

<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestats-h">DroppedVariableStats.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa9060587edeb01a63e3d3edc959678d1e">Before</a>, <a href="/web-llvm/docs/api/structs/llvm/droppedvariablestats/debugvariables/#a5e4d16731206131193654cbea6408074">llvm::DroppedVariableStats::DebugVariables::DebugVariablesAfter</a>, <a href="/web-llvm/docs/api/structs/llvm/droppedvariablestats/debugvariables/#ae0035704c71ffaf5c1e72109a3209140">llvm::DroppedVariableStats::DebugVariables::DebugVariablesBefore</a>, <a href="#a276914a247d61781f51e41186a9dc2af">InlinedAts</a> and <a href="#a39ae6f33a21851aaab9d15fcb979c037">visitEveryDebugRecord</a>.</p>

</div>
</div>

### setup() {#afb370e0ed83426862695812314133aa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DroppedVariableStats::setup ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestats-h">DroppedVariableStats.h</a>.</p>


<p>References <a href="#a956a96918980eb304dedaa78b88c0d3c">DebugVariablesStack</a> and <a href="#a276914a247d61781f51e41186a9dc2af">InlinedAts</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/droppedvariablestatsir/#a07f08df571060b6c07de22e8211a6b39">llvm::DroppedVariableStatsIR::runBeforePass</a>.</p>

</div>
</div>

### updateDroppedCount() {#a75d47320ab41eb44b12c355c8a3e9fe7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DroppedVariableStats::updateDroppedCount (<a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DbgLoc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * DbgValScope, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a07ea053ea2cdbee8e68ebd607c26dc8a">VarID</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * &gt; &amp; InlinedAtsMap, <a href="/web-llvm/docs/api/namespaces/llvm/#a07ea053ea2cdbee8e68ebd607c26dc8a">VarID</a> Var, unsigned &amp; DroppedCount)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a <span class="doxyComputerOutput">Var</span> has been dropped or is a false positive.</p>


<p>Also update the <span class="doxyComputerOutput">DroppedCount</span> if a debug variable is dropped.</p>


<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestats-h">DroppedVariableStats.h</a>.</p>

</div>
</div>

### visitEveryDebugRecord() {#a39ae6f33a21851aaab9d15fcb979c037}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::DroppedVariableStats::visitEveryDebugRecord (<a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a07ea053ea2cdbee8e68ebd607c26dc8a">VarID</a> &gt; &amp; VarIDSet, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a07ea053ea2cdbee8e68ebd607c26dc8a">VarID</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * &gt; &gt; &amp; InlinedAtsMap, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FuncName, bool Before)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Visit every debug record in an <a href="/web-llvm/docs/api/classes/llvm/function">llvm::Function</a> or <a href="/web-llvm/docs/api/classes/llvm/machinefunction">llvm::MachineFunction</a> and call populateVarIDSetAndInlinedMap on it.</p>

<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestats-h">DroppedVariableStats.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa9060587edeb01a63e3d3edc959678d1e">Before</a>, <a href="#a956a96918980eb304dedaa78b88c0d3c">DebugVariablesStack</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9b64313b5c1907066b7bab1c60a2ea08">llvm::drop_end</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#a848e174c81c6209939940cb31f1353cf">run</a>.</p>

</div>
</div>

### visitEveryInstruction() {#a1eb80ff593f2b7c49f83baaa60306b25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::DroppedVariableStats::visitEveryInstruction (unsigned &amp; DroppedCount, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a07ea053ea2cdbee8e68ebd607c26dc8a">VarID</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * &gt; &amp; InlinedAtsMap, <a href="/web-llvm/docs/api/namespaces/llvm/#a07ea053ea2cdbee8e68ebd607c26dc8a">VarID</a> Var)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Visit every <a href="/web-llvm/docs/api/classes/llvm/instruction">llvm::Instruction</a> or llvm::MachineInstruction and check if the debug variable denoted by its <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> <span class="doxyComputerOutput">Var</span> may have been dropped by an optimization pass.</p>

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestats-h">DroppedVariableStats.h</a>.</p>


<p>Referenced by <a href="#a039613c35cae74dbc1b9f2bcdc793f9e">calculateDroppedStatsAndPrint</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### isInlinedAtChildOfOrEqualTo() {#a8fdbc373ce011810665540c9e898e989}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DroppedVariableStats::isInlinedAtChildOfOrEqualTo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * InlinedAt, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DbgValInlinedAt)</td>
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

<p>Return true if <span class="doxyComputerOutput">InlinedAt</span> is the same as <span class="doxyComputerOutput">DbgValInlinedAt</span> or part of the InlinedAt chain, return false otherwise.</p>

<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestats-h">DroppedVariableStats.h</a>.</p>

</div>
</div>

### isScopeChildOfOrEqualTo() {#a66487f37dbb3cafb85728feda13892e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DroppedVariableStats::isScopeChildOfOrEqualTo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * DbgValScope)</td>
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

<p>Return true if <span class="doxyComputerOutput">Scope</span> is the same as <span class="doxyComputerOutput">DbgValScope</span> or a child scope of <span class="doxyComputerOutput">DbgValScope</span>, return false otherwise.</p>

<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestats-h">DroppedVariableStats.h</a>.</p>

</div>
</div>

### removeVarFromAllSets() {#a5e4c7649922447cb5f1fc59c5a9ee77b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DroppedVariableStats::removeVarFromAllSets (<a href="/web-llvm/docs/api/namespaces/llvm/#a07ea053ea2cdbee8e68ebd607c26dc8a">VarID</a> Var, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
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

<p>Remove a dropped debug variable's <a href="/web-llvm/docs/api/namespaces/llvm/#a07ea053ea2cdbee8e68ebd607c26dc8a">VarID</a> from all Sets in the DroppedVariablesBefore stack.</p>

<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestats-h">DroppedVariableStats.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### DebugVariablesStack {#a956a96918980eb304dedaa78b88c0d3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;DenseMap&lt;const Function *, DebugVariables&gt; &gt; llvm::DroppedVariableStats::DebugVariablesStack</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A stack of a <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>, that maps <a href="/web-llvm/docs/api/structs/llvm/droppedvariablestats/debugvariables">DebugVariables</a> for every pass to an <a href="/web-llvm/docs/api/classes/llvm/function">llvm::Function</a>.</p>


<p>A stack is used because an optimization pass can call other passes.</p>


<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestats-h">DroppedVariableStats.h</a>.</p>


<p>Referenced by <a href="#ab91542990bbb5413110da7acf1815924">cleanup</a>, <a href="#afb370e0ed83426862695812314133aa7">setup</a> and <a href="#a39ae6f33a21851aaab9d15fcb979c037">visitEveryDebugRecord</a>.</p>

</div>
</div>

### DroppedVariableStatsEnabled {#a6868779973ca0e558f17521d7810da52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DroppedVariableStats::DroppedVariableStatsEnabled = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestats-h">DroppedVariableStats.h</a>.</p>


<p>Referenced by <a href="#a46f071337fdc4a5ed806508f6b6073b4">DroppedVariableStats</a> and <a href="/web-llvm/docs/api/classes/llvm/droppedvariablestatsir/#a098ebeae73eb3b1c09384466602931e7">llvm::DroppedVariableStatsIR::registerCallbacks</a>.</p>

</div>
</div>

### InlinedAts {#a276914a247d61781f51e41186a9dc2af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;DenseMap&lt;StringRef, DenseMap&lt;VarID, DILocation *&gt; &gt; &gt; llvm::DroppedVariableStats::InlinedAts</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A stack of DenseMaps, which map the name of an <a href="/web-llvm/docs/api/classes/llvm/function">llvm::Function</a> to a <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a> of VarIDs and their inlinedAt locations before an optimization pass has run.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestats-h">DroppedVariableStats.h</a>.</p>


<p>Referenced by <a href="#a039613c35cae74dbc1b9f2bcdc793f9e">calculateDroppedStatsAndPrint</a>, <a href="#ab91542990bbb5413110da7acf1815924">cleanup</a>, <a href="#a848e174c81c6209939940cb31f1353cf">run</a> and <a href="#afb370e0ed83426862695812314133aa7">setup</a>.</p>

</div>
</div>

### VisitedScope {#a07e15724976aed7adc5b3a178548ca77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;const DIScope *&gt; llvm::DroppedVariableStats::VisitedScope</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a> tracking whether a scope was visited before.</p>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestats-h">DroppedVariableStats.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### PassDroppedVariables {#a9530fc2d82858ef5f7f0f05a572b0451}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DroppedVariableStats::PassDroppedVariables = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestats-h">DroppedVariableStats.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestats-h">DroppedVariableStats.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
