---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/transfertracker/usebeforedef
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `UseBeforeDef` Struct

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> of a use-before-def: created when a value that's live-in to the current block isn't available in any machine location, but it will be defined in this block. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct TransferTracker::UseBeforeDef { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36b9ea5387fdb74402bcacb3d6cd342c">UseBeforeDef</a> (ArrayRef&lt; DbgOp &gt; Values, DebugVariableID VarID, const DbgValueProperties &amp;Properties)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/livedebugvalues/dbgop">DbgOp</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b4cddff9a13c0b5b465ecab3fdc931e">Values</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> of this variable, def'd in block. <a href="#a6b4cddff9a13c0b5b465ecab3fdc931e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/livedebugvalues/#a2ad7532d3e36d429cab7c3ade85c5f77">DebugVariableID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50c91294ada6dd3784568a79d0f29866">VarID</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identity of this variable. <a href="#a50c91294ada6dd3784568a79d0f29866">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalueproperties">DbgValueProperties</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ea6a66deb8d30b11cceab65d5cda94e">Properties</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Additional variable properties. <a href="#a4ea6a66deb8d30b11cceab65d5cda94e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> of a use-before-def: created when a value that's live-in to the current block isn't available in any machine location, but it will be defined in this block.</p>

<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### UseBeforeDef() {#a36b9ea5387fdb74402bcacb3d6cd342c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TransferTracker::UseBeforeDef::UseBeforeDef (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/livedebugvalues/dbgop">DbgOp</a> &gt; Values, <a href="/web-llvm/docs/api/namespaces/livedebugvalues/#a2ad7532d3e36d429cab7c3ade85c5f77">DebugVariableID</a> VarID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalueproperties">DbgValueProperties</a> &amp; Properties)</td>
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



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="#a4ea6a66deb8d30b11cceab65d5cda94e">Properties</a>, <a href="#a6b4cddff9a13c0b5b465ecab3fdc931e">Values</a> and <a href="#a50c91294ada6dd3784568a79d0f29866">VarID</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Properties {#a4ea6a66deb8d30b11cceab65d5cda94e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgValueProperties TransferTracker::UseBeforeDef::Properties</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Additional variable properties.</p>

<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#a36b9ea5387fdb74402bcacb3d6cd342c">UseBeforeDef</a>.</p>

</div>
</div>

### Values {#a6b4cddff9a13c0b5b465ecab3fdc931e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;DbgOp&gt; TransferTracker::UseBeforeDef::Values</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> of this variable, def'd in block.</p>

<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#a36b9ea5387fdb74402bcacb3d6cd342c">UseBeforeDef</a>.</p>

</div>
</div>

### VarID {#a50c91294ada6dd3784568a79d0f29866}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugVariableID TransferTracker::UseBeforeDef::VarID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Identity of this variable.</p>

<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#a36b9ea5387fdb74402bcacb3d6cd342c">UseBeforeDef</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
