---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/droppedvariablestatsir
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DroppedVariableStatsIR` Class

<p>A class to collect and print dropped debug information due to LLVM IR optimization passes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DroppedVariableStatsIR { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestatsir-h">llvm/Passes/DroppedVariableStatsIR.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/droppedvariablestats">DroppedVariableStats</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A base class to collect and print dropped debug information variable statistics. <a href="/web-llvm/docs/api/classes/llvm/droppedvariablestats/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab45a0f0dfd5a887154fffaae4cc6e3be">DroppedVariableStatsIR</a> (bool DroppedVarStatsEnabled)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07f08df571060b6c07de22e8211a6b39">runBeforePass</a> (StringRef P, Any IR)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe7c231e11ef6c5345cbf3f9e9ae7979">runAfterPass</a> (StringRef P, Any IR)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a098ebeae73eb3b1c09384466602931e7">registerCallbacks</a> (PassInstrumentationCallbacks &amp;PIC)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a23a96fd79e729c3090093a655910a2">runAfterPassFunction</a> (StringRef PassID, const Function *F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecdc286e360b6fc2c596653b09f10172">runAfterPassModule</a> (StringRef PassID, const Module *M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e5303df31c27454e5a397d3c5b994fe">runOnFunction</a> (StringRef PassID, const Function *F, bool Before)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Populate DebugVariablesBefore, DebugVariablesAfter, InlinedAts before or after a pass has run to facilitate dropped variable calculation for an <a href="/web-llvm/docs/api/classes/llvm/function">llvm::Function</a>. <a href="#a9e5303df31c27454e5a397d3c5b994fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8bda08c4d9257b90f02f31ed78eee4d">calculateDroppedVarStatsOnFunction</a> (const Function *F, StringRef PassID, StringRef FuncOrModName, StringRef PassLevel)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterate over all Instructions in a <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> and report any dropped debug information. <a href="#aa8bda08c4d9257b90f02f31ed78eee4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8c1bd3a74a9a4065492d0fc2361368a">runOnModule</a> (StringRef PassID, const Module *M, bool Before)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Populate DebugVariablesBefore, DebugVariablesAfter, InlinedAts before or after a pass has run to facilitate dropped variable calculation for an <a href="/web-llvm/docs/api/classes/llvm/module">llvm::Module</a>. <a href="#aa8c1bd3a74a9a4065492d0fc2361368a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64aeea98541b11aed02802d08d79b860">calculateDroppedVarStatsOnModule</a> (const Module *M, StringRef PassID, StringRef FuncOrModName, StringRef PassLevel)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterate over all Functions in a <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> and report any dropped debug information. <a href="#a64aeea98541b11aed02802d08d79b860">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3faee18808aed1804ac4480fb2105cd">visitEveryInstruction</a> (unsigned &amp;DroppedCount, DenseMap&lt; VarID, DILocation * &gt; &amp;InlinedAtsMap, VarID Var) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Override base class method to run on an <a href="/web-llvm/docs/api/classes/llvm/function">llvm::Function</a> specifically. <a href="#ae3faee18808aed1804ac4480fb2105cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6ed4852a8021c4fedc463204a04187d">visitEveryDebugRecord</a> (DenseSet&lt; VarID &gt; &amp;VarIDSet, DenseMap&lt; StringRef, DenseMap&lt; VarID, DILocation * &gt; &gt; &amp;InlinedAtsMap, StringRef FuncName, bool Before) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Override base class method to run on #dbg_values specifically. <a href="#af6ed4852a8021c4fedc463204a04187d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5e3262a494b356aec08110c59e4c954">Func</a></td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> IRUnitT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4eef0fd77593e91fcc5fddb642ddcb14">unwrapIR</a> (Any IR)</td>
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

<p>A class to collect and print dropped debug information due to LLVM IR optimization passes.</p>


<p>After every LLVM IR pass is run, it will print how many #dbg_values were dropped due to that pass.</p>


<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestatsir-h">DroppedVariableStatsIR.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DroppedVariableStatsIR() {#ab45a0f0dfd5a887154fffaae4cc6e3be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DroppedVariableStatsIR::DroppedVariableStatsIR (bool DroppedVarStatsEnabled)</td>
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



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestatsir-h">DroppedVariableStatsIR.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/droppedvariablestats/#a46f071337fdc4a5ed806508f6b6073b4">llvm::DroppedVariableStats::DroppedVariableStats</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### registerCallbacks() {#a098ebeae73eb3b1c09384466602931e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DroppedVariableStatsIR::registerCallbacks (<a href="/web-llvm/docs/api/classes/llvm/passinstrumentationcallbacks">PassInstrumentationCallbacks</a> &amp; PIC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestatsir-h">DroppedVariableStatsIR.h</a>, definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/droppedvariablestatsir-cpp">DroppedVariableStatsIR.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/droppedvariablestats/#ab91542990bbb5413110da7acf1815924">llvm::DroppedVariableStats::cleanup</a>, <a href="/web-llvm/docs/api/classes/llvm/droppedvariablestats/#a6868779973ca0e558f17521d7810da52">llvm::DroppedVariableStats::DroppedVariableStatsEnabled</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>, <a href="#abe7c231e11ef6c5345cbf3f9e9ae7979">runAfterPass</a> and <a href="#a07f08df571060b6c07de22e8211a6b39">runBeforePass</a>.</p>

</div>
</div>

### runAfterPass() {#abe7c231e11ef6c5345cbf3f9e9ae7979}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DroppedVariableStatsIR::runAfterPass (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> P, <a href="/web-llvm/docs/api/classes/llvm/any">Any</a> IR)</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestatsir-h">DroppedVariableStatsIR.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/droppedvariablestats/#ab91542990bbb5413110da7acf1815924">llvm::DroppedVariableStats::cleanup</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="#a098ebeae73eb3b1c09384466602931e7">registerCallbacks</a>.</p>

</div>
</div>

### runBeforePass() {#a07f08df571060b6c07de22e8211a6b39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DroppedVariableStatsIR::runBeforePass (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> P, <a href="/web-llvm/docs/api/classes/llvm/any">Any</a> IR)</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestatsir-h">DroppedVariableStatsIR.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/droppedvariablestats/#afb370e0ed83426862695812314133aa7">llvm::DroppedVariableStats::setup</a>.</p>


<p>Referenced by <a href="#a098ebeae73eb3b1c09384466602931e7">registerCallbacks</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### calculateDroppedVarStatsOnFunction() {#aa8bda08c4d9257b90f02f31ed78eee4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DroppedVariableStatsIR::calculateDroppedVarStatsOnFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassID, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FuncOrModName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassLevel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Iterate over all Instructions in a <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> and report any dropped debug information.</p>

<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestatsir-h">DroppedVariableStatsIR.h</a>, definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/droppedvariablestatsir-cpp">DroppedVariableStatsIR.cpp</a>.</p>

</div>
</div>

### calculateDroppedVarStatsOnModule() {#a64aeea98541b11aed02802d08d79b860}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DroppedVariableStatsIR::calculateDroppedVarStatsOnModule (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassID, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FuncOrModName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassLevel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Iterate over all Functions in a <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> and report any dropped debug information.</p>


<p>Will call calculateDroppedVarStatsOnFunction on every <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>.</p>


<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestatsir-h">DroppedVariableStatsIR.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/droppedvariablestatsir-cpp">DroppedVariableStatsIR.cpp</a>.</p>

</div>
</div>

### runAfterPassFunction() {#a9a23a96fd79e729c3090093a655910a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DroppedVariableStatsIR::runAfterPassFunction (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestatsir-h">DroppedVariableStatsIR.h</a>.</p>

</div>
</div>

### runAfterPassModule() {#aecdc286e360b6fc2c596653b09f10172}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DroppedVariableStatsIR::runAfterPassModule (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M)</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestatsir-h">DroppedVariableStatsIR.h</a>.</p>

</div>
</div>

### runOnFunction() {#a9e5303df31c27454e5a397d3c5b994fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DroppedVariableStatsIR::runOnFunction (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, bool Before)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Populate DebugVariablesBefore, DebugVariablesAfter, InlinedAts before or after a pass has run to facilitate dropped variable calculation for an <a href="/web-llvm/docs/api/classes/llvm/function">llvm::Function</a>.</p>

<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestatsir-h">DroppedVariableStatsIR.h</a>, definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/droppedvariablestatsir-cpp">DroppedVariableStatsIR.cpp</a>.</p>

</div>
</div>

### runOnModule() {#aa8c1bd3a74a9a4065492d0fc2361368a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DroppedVariableStatsIR::runOnModule (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M, bool Before)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Populate DebugVariablesBefore, DebugVariablesAfter, InlinedAts before or after a pass has run to facilitate dropped variable calculation for an <a href="/web-llvm/docs/api/classes/llvm/module">llvm::Module</a>.</p>


<p>Calls runOnFunction on every <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> in the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>.</p>


<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestatsir-h">DroppedVariableStatsIR.h</a>, definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/droppedvariablestatsir-cpp">DroppedVariableStatsIR.cpp</a>.</p>

</div>
</div>

### visitEveryDebugRecord() {#af6ed4852a8021c4fedc463204a04187d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DroppedVariableStatsIR::visitEveryDebugRecord (<a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a07ea053ea2cdbee8e68ebd607c26dc8a">VarID</a> &gt; &amp; VarIDSet, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a07ea053ea2cdbee8e68ebd607c26dc8a">VarID</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * &gt; &gt; &amp; InlinedAtsMap, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FuncName, bool Before)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Override base class method to run on #dbg_values specifically.</p>

<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestatsir-h">DroppedVariableStatsIR.h</a>, definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/droppedvariablestatsir-cpp">DroppedVariableStatsIR.cpp</a>.</p>

</div>
</div>

### visitEveryInstruction() {#ae3faee18808aed1804ac4480fb2105cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DroppedVariableStatsIR::visitEveryInstruction (unsigned &amp; DroppedCount, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a07ea053ea2cdbee8e68ebd607c26dc8a">VarID</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * &gt; &amp; InlinedAtsMap, <a href="/web-llvm/docs/api/namespaces/llvm/#a07ea053ea2cdbee8e68ebd607c26dc8a">VarID</a> Var)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Override base class method to run on an <a href="/web-llvm/docs/api/classes/llvm/function">llvm::Function</a> specifically.</p>

<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestatsir-h">DroppedVariableStatsIR.h</a>, definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/droppedvariablestatsir-cpp">DroppedVariableStatsIR.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Func {#ad5e3262a494b356aec08110c59e4c954}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function* llvm::DroppedVariableStatsIR::Func</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestatsir-h">DroppedVariableStatsIR.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### unwrapIR() {#a4eef0fd77593e91fcc5fddb642ddcb14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const IRUnitT * llvm::DroppedVariableStatsIR::unwrapIR (<a href="/web-llvm/docs/api/classes/llvm/any">Any</a> IR)</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestatsir-h">DroppedVariableStatsIR.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestatsir-h">DroppedVariableStatsIR.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/passes/droppedvariablestatsir-cpp">DroppedVariableStatsIR.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
