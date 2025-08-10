---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-promotememorytoregister-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `anonymous{PromoteMemoryToRegister.cpp}` Namespace



## Definition

<div class="doxyDefinition">
namespace anonymous{PromoteMemoryToRegister.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-promotememorytoregister-cpp-/assignmenttrackinginfo">AssignmentTrackingInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper for updating assignment tracking debug info when promoting allocas. <a href="/web-llvm/docs/api/classes/anonymous-promotememorytoregister-cpp-/assignmenttrackinginfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/allocainfo">AllocaInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/renamepassdata">RenamePassData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Data package used by RenamePass(). <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/renamepassdata/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-promotememorytoregister-cpp-/largeblockinfo">LargeBlockInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This assigns and keeps a per-bb relative ordering of load/store instructions in the block that directly load or store an alloca. <a href="/web-llvm/docs/api/classes/anonymous-promotememorytoregister-cpp-/largeblockinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/promotemem2reg">PromoteMem2Reg</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d4100416db594644cb6cd161b245636">createDebugValue</a> (DIBuilder &amp;DIB, Value *NewValue, DILocalVariable *Variable, DIExpression *Expression, const DILocation *DI, DbgVariableRecord *InsertBefore)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acce7135d82ed41802b7c4ccd9059d3db">createDebugValue</a> (DIBuilder &amp;DIB, Value *NewValue, DILocalVariable *Variable, DIExpression *Expression, const DILocation *DI, Instruction *InsertBefore)</td>
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


<div class="doxySectionDef">

## Functions

### createDebugValue() {#a9d4100416db594644cb6cd161b245636}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PromoteMemoryToRegister.cpp}::createDebugValue (<a href="/web-llvm/docs/api/classes/llvm/dibuilder">DIBuilder</a> &amp; DIB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NewValue, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * Variable, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expression, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DI, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> * InsertBefore)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a8337b222b982e9caf0f6226efb56039c">llvm::DbgVariableRecord::createDbgVariableRecord</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-promotememorytoregister-cpp-/assignmenttrackinginfo/#a92fba2b8745329ee14995b36cf720f68">anonymous{PromoteMemoryToRegister.cpp}::AssignmentTrackingInfo::updateForDeletedStore</a>.</p>

</div>
</div>

### createDebugValue() {#acce7135d82ed41802b7c4ccd9059d3db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PromoteMemoryToRegister.cpp}::createDebugValue (<a href="/web-llvm/docs/api/classes/llvm/dibuilder">DIBuilder</a> &amp; DIB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NewValue, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * Variable, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expression, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DI, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * InsertBefore)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a> and <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a915a8d23e084b7a40475a3ce2245495b">llvm::DIBuilder::insertDbgValueIntrinsic</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
