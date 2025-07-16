---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/inlineasm/subconstraintinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SubConstraintInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::InlineAsm::SubConstraintInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">llvm/IR/InlineAsm.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc5fa4299629de73c7290ee407e971df">SubConstraintInfo</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default constructor. <a href="#adc5fa4299629de73c7290ee407e971df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9eb2f77e099aa841114a5fa767ed406">MatchingInput</a> = -1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MatchingInput - If this is not -1, this is an output constraint where an input constraint is required to match it (e.g. <a href="#ac9eb2f77e099aa841114a5fa767ed406">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineasm/#adbd59a81e5e06598a94e8b0e3b216d99">ConstraintCodeVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a907e764ba5f5a8cf55fcddac6c782d53">Codes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Code - The constraint code, either the register name (in braces) or the constraint letter/number. <a href="#a907e764ba5f5a8cf55fcddac6c782d53">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SubConstraintInfo() {#adc5fa4299629de73c7290ee407e971df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InlineAsm::SubConstraintInfo::SubConstraintInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Default constructor.</p>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Codes {#a907e764ba5f5a8cf55fcddac6c782d53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstraintCodeVector llvm::InlineAsm::SubConstraintInfo::Codes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Code - The constraint code, either the register name (in braces) or the constraint letter/number.</p>

<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/inlineasm/constraintinfo/#af49538ed53bce83dcf52b11234d559a4">llvm::InlineAsm::ConstraintInfo::selectAlternative</a>.</p>

</div>
</div>

### MatchingInput {#ac9eb2f77e099aa841114a5fa767ed406}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::InlineAsm::SubConstraintInfo::MatchingInput = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MatchingInput - If this is not -1, this is an output constraint where an input constraint is required to match it (e.g.</p>


<p>"0"). The value is the constraint number that matches this one (for example, if this is constraint #0 and constraint #4 has the value "0", this will be 4).</p>


<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/inlineasm/constraintinfo/#aa7d317c3dcdf1f805c995e9b3f2cba5f">llvm::InlineAsm::ConstraintInfo::Parse</a> and <a href="/web-llvm/docs/api/structs/llvm/inlineasm/constraintinfo/#af49538ed53bce83dcf52b11234d559a4">llvm::InlineAsm::ConstraintInfo::selectAlternative</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
