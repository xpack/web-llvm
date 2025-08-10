---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/deadargumenteliminationpass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DeadArgumentEliminationPass` Class

<p>Eliminate dead arguments (and return values) from functions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DeadArgumentEliminationPass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">llvm/Transforms/IPO/DeadArgumentElimination.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/passinfomixin">PassInfoMixin&lt;DerivedT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A CRTP mix-in to automatically provide informational APIs needed for passes. <a href="/web-llvm/docs/api/structs/llvm/passinfomixin/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cbc5f82a665596b0ff5d374dcf9d01c">UseMap</a> = std::multimap&lt; <a href="/web-llvm/docs/api/structs/llvm/deadargumenteliminationpass/retorarg">RetOrArg</a>, <a href="/web-llvm/docs/api/structs/llvm/deadargumenteliminationpass/retorarg">RetOrArg</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adccc69f6d0152bec28db15a70cf05587">LiveSet</a> = std::set&lt; <a href="/web-llvm/docs/api/structs/llvm/deadargumenteliminationpass/retorarg">RetOrArg</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1eb5a2eac80c369977d7c8747be838ba">LiveFuncSet</a> = std::set&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fc4b7b5727b4a936d7c1c23320a8b12">UseVector</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/deadargumenteliminationpass/retorarg">RetOrArg</a>, 5 &gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Liveness { <a href="#a3dee2ca18ff5275c99041264099fd964">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>During our initial pass over the program, we determine that things are either alive or maybe alive. <a href="#a3dee2ca18ff5275c99041264099fd964">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac009d77b6fca714db3d7b9f11618ac9">DeadArgumentEliminationPass</a> (bool ShouldHackArguments=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">PreservedAnalyses</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29ba94ac3af7390af4fa3209e6647732">run</a> (Module &amp;M, ModuleAnalysisManager &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/deadargumenteliminationpass/retorarg">RetOrArg</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5852130d218f4c275e8194510a9e31dd">createRet</a> (const Function *F, unsigned Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience wrapper. <a href="#a5852130d218f4c275e8194510a9e31dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/deadargumenteliminationpass/retorarg">RetOrArg</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9536f679d7b90e4dc0db3510ab67dce2">createArg</a> (const Function *F, unsigned Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience wrapper. <a href="#a9536f679d7b90e4dc0db3510ab67dce2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3dee2ca18ff5275c99041264099fd964">Liveness</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf0f5b61fd3c855d9628922a79216b3e">markIfNotLive</a> (RetOrArg Use, UseVector &amp;MaybeLiveUses)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> for liveness in LiveValues. <a href="#adf0f5b61fd3c855d9628922a79216b3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3dee2ca18ff5275c99041264099fd964">Liveness</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b24eade63288a140f8e867dd018ad88">surveyUse</a> (const Use *U, UseVector &amp;MaybeLiveUses, unsigned RetValNum=-1U)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Looks at a single use of an argument or return value and determines if it should be alive or not. <a href="#a9b24eade63288a140f8e867dd018ad88">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3dee2ca18ff5275c99041264099fd964">Liveness</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61f8aeca066956a480df0f6960832b2e">surveyUses</a> (const Value *V, UseVector &amp;MaybeLiveUses)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Looks at all the uses of the given value Returns the <a href="#a3dee2ca18ff5275c99041264099fd964">Liveness</a> deduced from the uses of this value. <a href="#a61f8aeca066956a480df0f6960832b2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1da52400f8fb3077bc591f79149890c7">surveyFunction</a> (const Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Performs the initial survey of the specified function, checking out whether it uses any of its incoming arguments or whether any callers use the return value. <a href="#a1da52400f8fb3077bc591f79149890c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad36fe62495d85ca76be9eb8dd1a8125d">isLive</a> (const RetOrArg &amp;RA)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32ffe897f911cd4fcff899217c1731c0">markValue</a> (const RetOrArg &amp;RA, Liveness L, const UseVector &amp;MaybeLiveUses)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Marks the liveness of RA depending on L. <a href="#a32ffe897f911cd4fcff899217c1731c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac585884e30c28f7046c2b046fb8b5c06">markLive</a> (const RetOrArg &amp;RA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark the given return value or argument as live. <a href="#ac585884e30c28f7046c2b046fb8b5c06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2e08655e55ad2ff50fcb32d12912868">markLive</a> (const Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark the given <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> as alive, meaning that it cannot be changed in any way. <a href="#ab2e08655e55ad2ff50fcb32d12912868">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe910acb239df3fc4a3482537eea037b">propagateLiveness</a> (const RetOrArg &amp;RA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given that RA is a live value, propagate it's liveness to any other values it uses (according to Uses). <a href="#abe910acb239df3fc4a3482537eea037b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaee3a451a88969091f337efe37ef22c7">removeDeadStuffFromFunction</a> (Function *F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove any arguments and return values from F that are not in LiveValues. <a href="#aaee3a451a88969091f337efe37ef22c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c6bc96f6df3d5e145ac8366c6de73da">deleteDeadVarargs</a> (Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is an function that takes a ... list, and if llvm.vastart is never called, the varargs list is dead for the function. <a href="#a4c6bc96f6df3d5e145ac8366c6de73da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a661190f7e0254349eda29ce8ca4ea06b">removeDeadArgumentsFromCallers</a> (Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the given function has any arguments that are unused, and changes the caller parameters to be poison instead. <a href="#a661190f7e0254349eda29ce8ca4ea06b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae055a96d2f264f27e75029f4684a75cc">propagateVirtMustcallLiveness</a> (const Module &amp;M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9cbc5f82a665596b0ff5d374dcf9d01c">UseMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb15aeeba5e11ad17b03524730d51b7d">Uses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This maps a return value or argument to any MaybeLive return values or arguments it uses. <a href="#afb15aeeba5e11ad17b03524730d51b7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#adccc69f6d0152bec28db15a70cf05587">LiveSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a404cb9e3e1fb3992697a27bd58e44a68">LiveValues</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This set contains all values that have been determined to be live. <a href="#a404cb9e3e1fb3992697a27bd58e44a68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1eb5a2eac80c369977d7c8747be838ba">LiveFuncSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1991a5019f642f03694439d95fa1b20">LiveFunctions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This set contains all values that are cannot be changed in any way. <a href="#aa1991a5019f642f03694439d95fa1b20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a997b16dfcd40407daf7b4e5b27dbcecf">ShouldHackArguments</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This allows this pass to do double-duty as the dead arg hacking pass (used only by bugpoint). <a href="#a997b16dfcd40407daf7b4e5b27dbcecf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Eliminate dead arguments (and return values) from functions.</p>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### LiveFuncSet {#a1eb5a2eac80c369977d7c8747be838ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DeadArgumentEliminationPass::LiveFuncSet =  std::set&lt;const Function *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>.</p>

</div>
</div>

### LiveSet {#adccc69f6d0152bec28db15a70cf05587}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DeadArgumentEliminationPass::LiveSet =  std::set&lt;RetOrArg&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>.</p>

</div>
</div>

### UseMap {#a9cbc5f82a665596b0ff5d374dcf9d01c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DeadArgumentEliminationPass::UseMap =  std::multimap&lt;RetOrArg, RetOrArg&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>.</p>

</div>
</div>

### UseVector {#a0fc4b7b5727b4a936d7c1c23320a8b12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DeadArgumentEliminationPass::UseVector =  SmallVector&lt;RetOrArg, 5&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### Liveness {#a3dee2ca18ff5275c99041264099fd964}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::DeadArgumentEliminationPass::Liveness </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>During our initial pass over the program, we determine that things are either alive or maybe alive.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Live<a id="a3dee2ca18ff5275c99041264099fd964a8cb9173f3fd92152f18401c8bf8ba21b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MaybeLive<a id="a3dee2ca18ff5275c99041264099fd964af29a24ceeaaae7277109ac9c7a52d958"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>We don't mark anything explicitly dead (even if we know they are), since anything not alive with no registered uses (in Uses) will never be marked alive and will thus become dead in the end.</p>


<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DeadArgumentEliminationPass() {#aac009d77b6fca714db3d7b9f11618ac9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DeadArgumentEliminationPass::DeadArgumentEliminationPass (bool ShouldHackArguments=false)</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>.</p>


<p>Reference <a href="#a997b16dfcd40407daf7b4e5b27dbcecf">ShouldHackArguments</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createArg() {#a9536f679d7b90e4dc0db3510ab67dce2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetOrArg llvm::DeadArgumentEliminationPass::createArg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, unsigned Idx)</td>
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

<p>Convenience wrapper.</p>

<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### createRet() {#a5852130d218f4c275e8194510a9e31dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetOrArg llvm::DeadArgumentEliminationPass::createRet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, unsigned Idx)</td>
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

<p>Convenience wrapper.</p>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### run() {#a29ba94ac3af7390af4fa3209e6647732}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses DeadArgumentEliminationPass::run (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>, definition at line 1132 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/deadargumentelimination-cpp">DeadArgumentElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-deadargumentelimination-cpp-/dae/#aad73a45cb4228e4fdff6c69e56d4d1a6">anonymous{DeadArgumentElimination.cpp}::DAE::runOnModule</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### deleteDeadVarargs() {#a4c6bc96f6df3d5e145ac8366c6de73da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DeadArgumentEliminationPass::deleteDeadVarargs (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this is an function that takes a ... list, and if llvm.vastart is never called, the varargs list is dead for the function.</p>

<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>, definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/deadargumentelimination-cpp">DeadArgumentElimination.cpp</a>.</p>

</div>
</div>

### isLive() {#ad36fe62495d85ca76be9eb8dd1a8125d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DeadArgumentEliminationPass::isLive (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/deadargumenteliminationpass/retorarg">RetOrArg</a> &amp; RA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>, definition at line 712 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/deadargumentelimination-cpp">DeadArgumentElimination.cpp</a>.</p>

</div>
</div>

### markIfNotLive() {#adf0f5b61fd3c855d9628922a79216b3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DeadArgumentEliminationPass::Liveness DeadArgumentEliminationPass::markIfNotLive (<a href="/web-llvm/docs/api/structs/llvm/deadargumenteliminationpass/retorarg">RetOrArg</a> Use, <a href="#a0fc4b7b5727b4a936d7c1c23320a8b12">UseVector</a> &amp; MaybeLiveUses)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> for liveness in LiveValues.</p>


<p>If <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> is not live, it adds <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> to the MaybeLiveUses argument. Returns the determined liveness of <a href="/web-llvm/docs/api/classes/llvm/use">Use</a>.</p>


<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>, definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/deadargumentelimination-cpp">DeadArgumentElimination.cpp</a>.</p>

</div>
</div>

### markLive() {#ac585884e30c28f7046c2b046fb8b5c06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DeadArgumentEliminationPass::markLive (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/deadargumenteliminationpass/retorarg">RetOrArg</a> &amp; RA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark the given return value or argument as live.</p>


<p>Additionally, mark any values that are used by this value (according to Uses) live as well.</p>


<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>, definition at line 701 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/deadargumentelimination-cpp">DeadArgumentElimination.cpp</a>.</p>

</div>
</div>

### markLive() {#ab2e08655e55ad2ff50fcb32d12912868}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DeadArgumentEliminationPass::markLive (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark the given <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> as alive, meaning that it cannot be changed in any way.</p>


<p>Additionally, mark any values that are used as this function's parameters or by its return values (according to Uses) live as well.</p>


<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>, definition at line 686 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/deadargumentelimination-cpp">DeadArgumentElimination.cpp</a>.</p>

</div>
</div>

### markValue() {#a32ffe897f911cd4fcff899217c1731c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DeadArgumentEliminationPass::markValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/deadargumenteliminationpass/retorarg">RetOrArg</a> &amp; RA, <a href="#a3dee2ca18ff5275c99041264099fd964">Liveness</a> L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a0fc4b7b5727b4a936d7c1c23320a8b12">UseVector</a> &amp; MaybeLiveUses)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Marks the liveness of RA depending on L.</p>


<p>If L is MaybeLive, it also takes all uses in MaybeLiveUses and records them in Uses, such that RA will be marked live if any use in MaybeLiveUses gets marked live later on.</p>


<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>, definition at line 661 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/deadargumentelimination-cpp">DeadArgumentElimination.cpp</a>.</p>

</div>
</div>

### propagateLiveness() {#abe910acb239df3fc4a3482537eea037b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DeadArgumentEliminationPass::propagateLiveness (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/deadargumenteliminationpass/retorarg">RetOrArg</a> &amp; RA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given that RA is a live value, propagate it's liveness to any other values it uses (according to Uses).</p>

<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>, definition at line 718 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/deadargumentelimination-cpp">DeadArgumentElimination.cpp</a>.</p>

</div>
</div>

### propagateVirtMustcallLiveness() {#ae055a96d2f264f27e75029f4684a75cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DeadArgumentEliminationPass::propagateVirtMustcallLiveness (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>, definition at line 1112 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/deadargumentelimination-cpp">DeadArgumentElimination.cpp</a>.</p>

</div>
</div>

### removeDeadArgumentsFromCallers() {#a661190f7e0254349eda29ce8ca4ea06b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DeadArgumentEliminationPass::removeDeadArgumentsFromCallers (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks if the given function has any arguments that are unused, and changes the caller parameters to be poison instead.</p>

<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>, definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/deadargumentelimination-cpp">DeadArgumentElimination.cpp</a>.</p>

</div>
</div>

### removeDeadStuffFromFunction() {#aaee3a451a88969091f337efe37ef22c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DeadArgumentEliminationPass::removeDeadStuffFromFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove any arguments and return values from F that are not in LiveValues.</p>


<p>Transform the function and all the callees of the function to not have these arguments and return values.</p>


<p>Declaration at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>, definition at line 736 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/deadargumentelimination-cpp">DeadArgumentElimination.cpp</a>.</p>

</div>
</div>

### surveyFunction() {#a1da52400f8fb3077bc591f79149890c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DeadArgumentEliminationPass::surveyFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Performs the initial survey of the specified function, checking out whether it uses any of its incoming arguments or whether any callers use the return value.</p>


<p>This fills in the LiveValues set and Uses map.</p>


<p>We consider arguments of non-internal functions to be intrinsically alive as well as arguments to functions which have their "address taken".</p>


<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>, definition at line 494 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/deadargumentelimination-cpp">DeadArgumentElimination.cpp</a>.</p>

</div>
</div>

### surveyUse() {#a9b24eade63288a140f8e867dd018ad88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DeadArgumentEliminationPass::Liveness DeadArgumentEliminationPass::surveyUse (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> * U, <a href="#a0fc4b7b5727b4a936d7c1c23320a8b12">UseVector</a> &amp; MaybeLiveUses, unsigned RetValNum=-1U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Looks at a single use of an argument or return value and determines if it should be alive or not.</p>


<p>Adds this use to MaybeLiveUses if it causes the used value to become MaybeLive.</p>


<p>RetValNum is the return value number to use when this use is used in a return instruction. This is used in the recursion, you should always leave it at 0.</p>


<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>, definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/deadargumentelimination-cpp">DeadArgumentElimination.cpp</a>.</p>

</div>
</div>

### surveyUses() {#a61f8aeca066956a480df0f6960832b2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DeadArgumentEliminationPass::Liveness DeadArgumentEliminationPass::surveyUses (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="#a0fc4b7b5727b4a936d7c1c23320a8b12">UseVector</a> &amp; MaybeLiveUses)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Looks at all the uses of the given value Returns the <a href="#a3dee2ca18ff5275c99041264099fd964">Liveness</a> deduced from the uses of this value.</p>


<p>Adds all uses that cause the result to be MaybeLive to MaybeLiveRetUses. If the result is Live, MaybeLiveUses might be modified but its content should be ignored (since it might not be complete).</p>


<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>, definition at line 475 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/deadargumentelimination-cpp">DeadArgumentElimination.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### LiveFunctions {#aa1991a5019f642f03694439d95fa1b20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveFuncSet llvm::DeadArgumentEliminationPass::LiveFunctions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This set contains all values that are cannot be changed in any way.</p>

<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>.</p>

</div>
</div>

### LiveValues {#a404cb9e3e1fb3992697a27bd58e44a68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveSet llvm::DeadArgumentEliminationPass::LiveValues</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This set contains all values that have been determined to be live.</p>

<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>.</p>

</div>
</div>

### ShouldHackArguments {#a997b16dfcd40407daf7b4e5b27dbcecf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DeadArgumentEliminationPass::ShouldHackArguments = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This allows this pass to do double-duty as the dead arg hacking pass (used only by bugpoint).</p>

<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>.</p>


<p>Referenced by <a href="#aac009d77b6fca714db3d7b9f11618ac9">DeadArgumentEliminationPass</a>.</p>

</div>
</div>

### Uses {#afb15aeeba5e11ad17b03524730d51b7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UseMap llvm::DeadArgumentEliminationPass::Uses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This maps a return value or argument to any MaybeLive return values or arguments it uses.</p>


<p>This allows the MaybeLive values to be marked live when any of its users is marked live. For example (indices are left out for clarity):</p>


<ul class="doxyList ">
<li>Uses[ret F] = ret G This means that F calls G, and F returns the value returned by G.</li>
<li>Uses[arg F] = ret G This means that some function calls G and passes its result as an argument to F.</li>
<li>Uses[ret F] = arg F This means that F returns one of its own arguments.</li>
<li>Uses[arg F] = arg G This means that G calls F and passes one of its own (G's) arguments directly to F.</li>
</ul>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/deadargumentelimination-cpp">DeadArgumentElimination.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
