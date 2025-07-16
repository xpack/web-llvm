---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/ilpvalue
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ILPValue` Struct Reference

<p>Represent the ILP of the subDAG rooted at a DAG node. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::ILPValue { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledfs-h">llvm/CodeGen/ScheduleDFS.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a43de3ddd722270a256a87a513c6fb2">ILPValue</a> (unsigned count, unsigned length)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07f69c54ea482df17e857dcfb8beefe2">operator&lt;</a> (ILPValue RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abffe08b0b41ced0b8dcd45ee534fe8f2">operator&gt;</a> (ILPValue RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15bfbc3d6b52ea9beb968635c955328a">operator&lt;=</a> (ILPValue RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2034fa92ac1dd565e1c6c6ce8020965e">operator&gt;=</a> (ILPValue RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66e49dcd600dc169a7b3d36298e9e311">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d4e7eb6e7c6d7dad1e3906d0e72cba7">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc40db1d4327d54c401f118309d6273a">InstrCount</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11a9c5cf8b43a32aa10801e4e0d7427d">Length</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Length may either correspond to depth or height, depending on direction, and cycles or nodes depending on context. <a href="#a11a9c5cf8b43a32aa10801e4e0d7427d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Represent the ILP of the subDAG rooted at a DAG node.</p>


<p>ILPValues summarize the DAG subtree rooted at each node. ILPValues are valid for all nodes regardless of their subtree membership.</p>


<p>When computed using bottom-up DFS, this metric assumes that the DAG is a forest of trees with roots at the bottom of the schedule branching upward.</p>


<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledfs-h">ScheduleDFS.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ILPValue() {#a5a43de3ddd722270a256a87a513c6fb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ILPValue::ILPValue (unsigned count, unsigned length)</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledfs-h">ScheduleDFS.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab1772fd431decccb7926d484ea223db7">llvm::count</a>, <a href="#adc40db1d4327d54c401f118309d6273a">InstrCount</a> and <a href="#a11a9c5cf8b43a32aa10801e4e0d7427d">Length</a>.</p>


<p>Referenced by <a href="#a07f69c54ea482df17e857dcfb8beefe2">operator&lt;</a>, <a href="#a15bfbc3d6b52ea9beb968635c955328a">operator&lt;=</a>, <a href="#abffe08b0b41ced0b8dcd45ee534fe8f2">operator&gt;</a> and <a href="#a2034fa92ac1dd565e1c6c6ce8020965e">operator&gt;=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator&lt;() {#a07f69c54ea482df17e857dcfb8beefe2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ILPValue::operator&lt; (<a href="/web-llvm/docs/api/structs/llvm/ilpvalue">ILPValue</a> RHS)</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledfs-h">ScheduleDFS.h</a>.</p>


<p>References <a href="#a5a43de3ddd722270a256a87a513c6fb2">ILPValue</a>, <a href="#adc40db1d4327d54c401f118309d6273a">InstrCount</a>, <a href="#a11a9c5cf8b43a32aa10801e4e0d7427d">Length</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&lt;=() {#a15bfbc3d6b52ea9beb968635c955328a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ILPValue::operator&lt;= (<a href="/web-llvm/docs/api/structs/llvm/ilpvalue">ILPValue</a> RHS)</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledfs-h">ScheduleDFS.h</a>.</p>


<p>References <a href="#a5a43de3ddd722270a256a87a513c6fb2">ILPValue</a>, <a href="#adc40db1d4327d54c401f118309d6273a">InstrCount</a>, <a href="#a11a9c5cf8b43a32aa10801e4e0d7427d">Length</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&gt;() {#abffe08b0b41ced0b8dcd45ee534fe8f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ILPValue::operator&gt; (<a href="/web-llvm/docs/api/structs/llvm/ilpvalue">ILPValue</a> RHS)</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledfs-h">ScheduleDFS.h</a>.</p>


<p>References <a href="#a5a43de3ddd722270a256a87a513c6fb2">ILPValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&gt;=() {#a2034fa92ac1dd565e1c6c6ce8020965e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ILPValue::operator&gt;= (<a href="/web-llvm/docs/api/structs/llvm/ilpvalue">ILPValue</a> RHS)</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledfs-h">ScheduleDFS.h</a>.</p>


<p>References <a href="#a5a43de3ddd722270a256a87a513c6fb2">ILPValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a2d4e7eb6e7c6d7dad1e3906d0e72cba7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void ILPValue::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledfs-h">ScheduleDFS.h</a>, definition at line 1530 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>.</p>

</div>
</div>

### print() {#a66e49dcd600dc169a7b3d36298e9e311}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void ILPValue::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledfs-h">ScheduleDFS.h</a>, definition at line 1522 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="#adc40db1d4327d54c401f118309d6273a">InstrCount</a>, <a href="#a11a9c5cf8b43a32aa10801e4e0d7427d">Length</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a91c8d2b343c64ec256cb452b08158fce">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### InstrCount {#adc40db1d4327d54c401f118309d6273a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ILPValue::InstrCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledfs-h">ScheduleDFS.h</a>.</p>


<p>Referenced by <a href="#a5a43de3ddd722270a256a87a513c6fb2">ILPValue</a>, <a href="#a07f69c54ea482df17e857dcfb8beefe2">operator&lt;</a>, <a href="#a15bfbc3d6b52ea9beb968635c955328a">operator&lt;=</a> and <a href="#a66e49dcd600dc169a7b3d36298e9e311">print</a>.</p>

</div>
</div>

### Length {#a11a9c5cf8b43a32aa10801e4e0d7427d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ILPValue::Length</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Length may either correspond to depth or height, depending on direction, and cycles or nodes depending on context.</p>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledfs-h">ScheduleDFS.h</a>.</p>


<p>Referenced by <a href="#a5a43de3ddd722270a256a87a513c6fb2">ILPValue</a>, <a href="#a07f69c54ea482df17e857dcfb8beefe2">operator&lt;</a>, <a href="#a15bfbc3d6b52ea9beb968635c955328a">operator&lt;=</a> and <a href="#a66e49dcd600dc169a7b3d36298e9e311">print</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledfs-h">ScheduleDFS.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
