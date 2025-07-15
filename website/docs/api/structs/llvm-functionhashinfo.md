---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/functionhashinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `FunctionHashInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::FunctionHashInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/structuralhash-h">llvm/IR/StructuralHash.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea2663e0d31bed3084f018802267b5c1">FunctionHashInfo</a> (stable_hash FuntionHash, std::unique_ptr&lt; IndexInstrMap &gt; IndexInstruction, std::unique_ptr&lt; IndexOperandHashMapType &gt; IndexOperandHashMap)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a3f07bd5ee30b6a57ddc214f64d5fd941">stable_hash</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53710ecc9d5c197134ef13e5fee9fb85">FunctionHash</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A hash value representing the structural content of the function. <a href="#a53710ecc9d5c197134ef13e5fee9fb85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a439bd5f3a661cbf4b5e546a765998732">IndexInstrMap</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a601a20cabca86828bab466676a5b43ee">IndexInstruction</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A mapping from instruction indices to instruction pointers. <a href="#a601a20cabca86828bab466676a5b43ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a84743af686727e503a41a7cc9e590820">IndexOperandHashMapType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca2780c727031b075fc811f340c2f4bf">IndexOperandHashMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A mapping from pairs of instruction indices and operand indices to the hashes of the operands. <a href="#aca2780c727031b075fc811f340c2f4bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/structuralhash-h">StructuralHash.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FunctionHashInfo() {#aea2663e0d31bed3084f018802267b5c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FunctionHashInfo::FunctionHashInfo (<a href="/web-llvm/docs/api/namespaces/llvm/#a3f07bd5ee30b6a57ddc214f64d5fd941">stable_hash</a> FuntionHash, std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a439bd5f3a661cbf4b5e546a765998732">IndexInstrMap</a> &gt; IndexInstruction, std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a84743af686727e503a41a7cc9e590820">IndexOperandHashMapType</a> &gt; IndexOperandHashMap)</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/structuralhash-h">StructuralHash.h</a>.</p>


<p>References <a href="#a53710ecc9d5c197134ef13e5fee9fb85">FunctionHash</a>, <a href="#a601a20cabca86828bab466676a5b43ee">IndexInstruction</a>, <a href="#aca2780c727031b075fc811f340c2f4bf">IndexOperandHashMap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### FunctionHash {#a53710ecc9d5c197134ef13e5fee9fb85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">stable_hash llvm::FunctionHashInfo::FunctionHash</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A hash value representing the structural content of the function.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/structuralhash-h">StructuralHash.h</a>.</p>


<p>Referenced by <a href="#aea2663e0d31bed3084f018802267b5c1">FunctionHashInfo</a>.</p>

</div>
</div>

### IndexInstruction {#a601a20cabca86828bab466676a5b43ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;IndexInstrMap&gt; llvm::FunctionHashInfo::IndexInstruction</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A mapping from instruction indices to instruction pointers.</p>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/structuralhash-h">StructuralHash.h</a>.</p>


<p>Referenced by <a href="#aea2663e0d31bed3084f018802267b5c1">FunctionHashInfo</a>.</p>

</div>
</div>

### IndexOperandHashMap {#aca2780c727031b075fc811f340c2f4bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;IndexOperandHashMapType&gt; llvm::FunctionHashInfo::IndexOperandHashMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A mapping from pairs of instruction indices and operand indices to the hashes of the operands.</p>


<p>This can be used to analyze or reconstruct the differences in ignored operands</p>


<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/structuralhash-h">StructuralHash.h</a>.</p>


<p>Referenced by <a href="#aea2663e0d31bed3084f018802267b5c1">FunctionHashInfo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/structuralhash-h">StructuralHash.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
