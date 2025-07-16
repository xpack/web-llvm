---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/calllowering/outgoingvalueassigner
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `OutgoingValueAssigner` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::CallLowering::OutgoingValueAssigner { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">llvm/CodeGen/GlobalISel/CallLowering.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/calllowering/valueassigner">ValueAssigner</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> handling is mostly uniform between the four places that make these decisions: function formal arguments, call instruction args, call instruction returns and function returns. <a href="/web-llvm/docs/api/structs/llvm/calllowering/valueassigner/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/aarch64outgoingvalueassigner">AArch64OutgoingValueAssigner</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-mipscalllowering-cpp-/mipsoutgoingvalueassigner">MipsOutgoingValueAssigner</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvoutgoingvalueassigner">RISCVOutgoingValueAssigner</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-x86calllowering-cpp-/x86outgoingvalueassigner">X86OutgoingValueAssigner</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2189160214171b9862ade30c943b7a8e">OutgoingValueAssigner</a> (CCAssignFn *AssignFn_, CCAssignFn *AssignFnVarArg_=nullptr)</td>
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


<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### OutgoingValueAssigner() {#a2189160214171b9862ade30c943b7a8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CallLowering::OutgoingValueAssigner::OutgoingValueAssigner (<a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> * AssignFn_, <a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> * AssignFnVarArg_=nullptr)</td>
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



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/calllowering/valueassigner/#a356248ea0464de7b7fa769e23aa0690c">llvm::CallLowering::ValueAssigner::ValueAssigner</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/aarch64outgoingvalueassigner/#a2ceb0453e55656ee3a5ee8f5e541d7bf">anonymous{AArch64CallLowering.cpp}::AArch64OutgoingValueAssigner::AArch64OutgoingValueAssigner</a>, <a href="/web-llvm/docs/api/structs/anonymous-mipscalllowering-cpp-/mipsoutgoingvalueassigner/#a20b360f0572d5be095c85fda2d7fac69">anonymous{MipsCallLowering.cpp}::MipsOutgoingValueAssigner::MipsOutgoingValueAssigner</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvoutgoingvalueassigner/#acc68888f8e1147361287f73ac253f77f">anonymous{RISCVCallLowering.cpp}::RISCVOutgoingValueAssigner::RISCVOutgoingValueAssigner</a> and <a href="/web-llvm/docs/api/structs/anonymous-x86calllowering-cpp-/x86outgoingvalueassigner/#a3680ddda4c3cc903abaa2bc90081b4ec">anonymous{X86CallLowering.cpp}::X86OutgoingValueAssigner::X86OutgoingValueAssigner</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
