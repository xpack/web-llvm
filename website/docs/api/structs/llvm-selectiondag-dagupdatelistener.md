---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/selectiondag/dagupdatelistener
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DAGUpdateListener` Struct Reference

<p>Clients of various APIs that cause global effects on the DAG can optionally implement this interface. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::SelectionDAG::DAGUpdateListener { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondag-h">llvm/CodeGen/SelectionDAG.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/worklistinserter">WorklistInserter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/worklistremover">WorklistRemover</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class is a DAGUpdateListener that removes any deleted nodes from the worklist. <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/worklistremover/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-legalizetypes-cpp-/nodeupdatelistener">NodeUpdateListener</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class is a DAGUpdateListener that listens for updates to nodes and recomputes their ready state. <a href="/web-llvm/docs/api/classes/anonymous-legalizetypes-cpp-/nodeupdatelistener/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-selectiondag-cpp-/rauovwupdatelistener">RAUOVWUpdateListener</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/anonymous-selectiondag-cpp-/rauovwupdatelistener">RAUOVWUpdateListener</a> - Helper for ReplaceAllUsesOfValuesWith - When the node pointed to by a <a href="/web-llvm/docs/api/structs/anonymous-selectiondag-cpp-/usememo">UseMemo</a> is deleted, set the <a href="/web-llvm/docs/api/classes/llvm/user">User</a> to nullptr to indicate that the node already has been taken care of recursively. <a href="/web-llvm/docs/api/classes/anonymous-selectiondag-cpp-/rauovwupdatelistener/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-selectiondag-cpp-/rauwupdatelistener">RAUWUpdateListener</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/anonymous-selectiondag-cpp-/rauwupdatelistener">RAUWUpdateListener</a> - Helper for ReplaceAllUsesWith - When the node pointed to by a use iterator is deleted, increment the use iterator so that it doesn't dangle. <a href="/web-llvm/docs/api/classes/anonymous-selectiondag-cpp-/rauwupdatelistener/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-selectiondagisel-cpp-/iselupdater">ISelUpdater</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/anonymous-selectiondagisel-cpp-/iselupdater">ISelUpdater</a> - helper class to handle updates of the instruction selection graph. <a href="/web-llvm/docs/api/classes/anonymous-selectiondagisel-cpp-/iselupdater/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-selectiondagisel-cpp-/matchstateupdater">MatchStateUpdater</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\A DAG update listener to keep the matching state (i.e. <a href="/web-llvm/docs/api/classes/anonymous-selectiondagisel-cpp-/matchstateupdater/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/selectiondag/dagnodedeletedlistener">DAGNodeDeletedListener</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/selectiondag/dagnodeinsertedlistener">DAGNodeInsertedListener</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3ffbfc6ced2909624e205e7e93b8789">DAGUpdateListener</a> (SelectionDAG &amp;D)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a686e26407d331514b38ceae2c23daf67">~DAGUpdateListener</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d69b75ce8758fd9c5c7d9f9b42c5477">NodeDeleted</a> (SDNode *N, SDNode *E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The node N that was deleted and, if E is not null, an equivalent node E that replaced it. <a href="#a7d69b75ce8758fd9c5c7d9f9b42c5477">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbc277665c4fa07c90be04c91af8966b">NodeUpdated</a> (SDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The node N that was updated. <a href="#adbc277665c4fa07c90be04c91af8966b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a977d82172b6fe7b4fba72554404bde60">NodeInserted</a> (SDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The node N that was inserted. <a href="#a977d82172b6fe7b4fba72554404bde60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/selectiondag/dagupdatelistener">DAGUpdateListener</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ccf5c27bb0d12828404e9ca69677bb2">Next</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affbd659753a061c27261830290a2aaa0">DAG</a></td>
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

<p>Clients of various APIs that cause global effects on the DAG can optionally implement this interface.</p>


<p>This allows the clients to handle the various sorts of updates that happen.</p>


<p>A <a href="/web-llvm/docs/api/structs/llvm/selectiondag/dagupdatelistener">DAGUpdateListener</a> automatically registers itself with DAG when it is constructed, and removes itself when destroyed in RAII fashion.</p>


<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondag-h">SelectionDAG.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DAGUpdateListener() {#ab3ffbfc6ced2909624e205e7e93b8789}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SelectionDAG::DAGUpdateListener::DAGUpdateListener (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; D)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondag-h">SelectionDAG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#affbd659753a061c27261830290a2aaa0">DAG</a>, <a href="#a7ccf5c27bb0d12828404e9ca69677bb2">Next</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a206d1ceace9c38fa4efdaf2d111e1df4">llvm::SelectionDAG::SelectionDAG</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/selectiondag/dagnodedeletedlistener/#a3c08f18bbbed4b12080795dfcf099dba">llvm::SelectionDAG::DAGNodeDeletedListener::DAGNodeDeletedListener</a>, <a href="/web-llvm/docs/api/structs/llvm/selectiondag/dagnodeinsertedlistener/#af4b16a03559534a93eb5d0a322dff196">llvm::SelectionDAG::DAGNodeInsertedListener::DAGNodeInsertedListener</a>, <a href="/web-llvm/docs/api/classes/anonymous-selectiondagisel-cpp-/iselupdater/#a3a04247f436b3867522faa31dbd7e916">anonymous{SelectionDAGISel.cpp}::ISelUpdater::ISelUpdater</a>, <a href="/web-llvm/docs/api/classes/anonymous-selectiondagisel-cpp-/matchstateupdater/#a0c5aa4fc2d1476ab4012b6719fd419a4">anonymous{SelectionDAGISel.cpp}::MatchStateUpdater::MatchStateUpdater</a>, <a href="/web-llvm/docs/api/classes/anonymous-legalizetypes-cpp-/nodeupdatelistener/#a1e5a39703ca3f66df4a37449c50f2e42">anonymous{LegalizeTypes.cpp}::NodeUpdateListener::NodeUpdateListener</a>, <a href="/web-llvm/docs/api/classes/anonymous-selectiondag-cpp-/rauovwupdatelistener/#aec65f32b8e94e44b033075f6dad3f034">anonymous{SelectionDAG.cpp}::RAUOVWUpdateListener::RAUOVWUpdateListener</a>, <a href="/web-llvm/docs/api/classes/anonymous-selectiondag-cpp-/rauwupdatelistener/#a6f8d721912707fda12da5f34b38a18f5">anonymous{SelectionDAG.cpp}::RAUWUpdateListener::RAUWUpdateListener</a>, <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/worklistinserter/#a268520eac2c2d9c23fa328ec68982376">anonymous{DAGCombiner.cpp}::WorklistInserter::WorklistInserter</a> and <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/worklistremover/#ae9606fbf64fa8f7ddb3797c0aa4e1bac">anonymous{DAGCombiner.cpp}::WorklistRemover::WorklistRemover</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DAGUpdateListener() {#a686e26407d331514b38ceae2c23daf67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::SelectionDAG::DAGUpdateListener::~DAGUpdateListener ()</td>
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



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondag-h">SelectionDAG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#affbd659753a061c27261830290a2aaa0">DAG</a> and <a href="#a7ccf5c27bb0d12828404e9ca69677bb2">Next</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### NodeDeleted() {#a7d69b75ce8758fd9c5c7d9f9b42c5477}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAG::DAGUpdateListener::NodeDeleted (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * E)</td>
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

<p>The node N that was deleted and, if E is not null, an equivalent node E that replaced it.</p>

<p>Declaration at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondag-h">SelectionDAG.h</a>, definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>

</div>
</div>

### NodeInserted() {#a977d82172b6fe7b4fba72554404bde60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAG::DAGUpdateListener::NodeInserted (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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

<p>The node N that was inserted.</p>

<p>Declaration at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondag-h">SelectionDAG.h</a>, definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>

</div>
</div>

### NodeUpdated() {#adbc277665c4fa07c90be04c91af8966b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAG::DAGUpdateListener::NodeUpdated (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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

<p>The node N that was updated.</p>

<p>Declaration at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondag-h">SelectionDAG.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DAG {#affbd659753a061c27261830290a2aaa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SelectionDAG&amp; llvm::SelectionDAG::DAGUpdateListener::DAG</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondag-h">SelectionDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/selectiondag/dagnodedeletedlistener/#a3c08f18bbbed4b12080795dfcf099dba">llvm::SelectionDAG::DAGNodeDeletedListener::DAGNodeDeletedListener</a>, <a href="/web-llvm/docs/api/structs/llvm/selectiondag/dagnodeinsertedlistener/#af4b16a03559534a93eb5d0a322dff196">llvm::SelectionDAG::DAGNodeInsertedListener::DAGNodeInsertedListener</a>, <a href="#ab3ffbfc6ced2909624e205e7e93b8789">DAGUpdateListener</a>, <a href="/web-llvm/docs/api/classes/anonymous-selectiondagisel-cpp-/iselupdater/#a3a04247f436b3867522faa31dbd7e916">anonymous{SelectionDAGISel.cpp}::ISelUpdater::ISelUpdater</a>, <a href="/web-llvm/docs/api/classes/anonymous-selectiondagisel-cpp-/matchstateupdater/#a0c5aa4fc2d1476ab4012b6719fd419a4">anonymous{SelectionDAGISel.cpp}::MatchStateUpdater::MatchStateUpdater</a>, <a href="/web-llvm/docs/api/classes/anonymous-selectiondagisel-cpp-/iselupdater/#a44d0f836c752cf8d1a28b71aec4ba564">anonymous{SelectionDAGISel.cpp}::ISelUpdater::NodeInserted</a> and <a href="#a686e26407d331514b38ceae2c23daf67">~DAGUpdateListener</a>.</p>

</div>
</div>

### Next {#a7ccf5c27bb0d12828404e9ca69677bb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DAGUpdateListener* const llvm::SelectionDAG::DAGUpdateListener::Next</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondag-h">SelectionDAG.h</a>.</p>


<p>Referenced by <a href="#ab3ffbfc6ced2909624e205e7e93b8789">DAGUpdateListener</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#afa91c37999052160d434c5bf803257c9">llvm::SelectionDAG::RemoveDeadNodes</a> and <a href="#a686e26407d331514b38ceae2c23daf67">~DAGUpdateListener</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondag-h">SelectionDAG.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
