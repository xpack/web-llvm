---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/utils-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `Utils.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselworklist-h">GISelWorkList.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">llvm/ADT/APFloat.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">llvm/CodeGen/Register.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">llvm/CodeGenTypes/LowLevelType.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">llvm/IR/DebugLoc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">llvm/Support/Alignment.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include &lt;cstdint&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/valueandvreg">ValueAndVReg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Simple struct used to hold a constant integer value and a virtual register. <a href="/web-llvm/docs/api/structs/llvm/valueandvreg/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/fpvalueandvreg">FPValueAndVReg</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/definitionandsourceregister">DefinitionAndSourceRegister</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Simple struct used to hold a <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> value and the instruction which defines it. <a href="/web-llvm/docs/api/structs/llvm/definitionandsourceregister/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regorconstant">RegOrConstant</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a value which can be a <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> or a constant. <a href="/web-llvm/docs/api/classes/llvm/regorconstant/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/giconstant">GIConstant</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An integer-like constant. <a href="/web-llvm/docs/api/classes/llvm/giconstant/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gfconstant">GFConstant</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An floating-point-like constant. <a href="/web-llvm/docs/api/classes/llvm/gfconstant/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13021f3389a4d7727128cd0e1650ba08">GISEL_VECREDUCE_CASES_ALL</a>&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42d8e909f2bea1119192cca95df057fa">GISEL_VECREDUCE_CASES_NONSEQ</a>&nbsp;&nbsp;&nbsp;...</td>
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

## Macro Definitions

### GISEL\_VECREDUCE\_CASES\_ALL {#a13021f3389a4d7727128cd0e1650ba08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GISEL_VECREDUCE_CASES_ALL&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case TargetOpcode::G_VECREDUCE_SEQ_FADD:                                     \
  case TargetOpcode::G_VECREDUCE_SEQ_FMUL:                                     \
  case TargetOpcode::G_VECREDUCE_FADD:                                         \
  case TargetOpcode::G_VECREDUCE_FMUL:                                         \
  case TargetOpcode::G_VECREDUCE_FMAX:                                         \
  case TargetOpcode::G_VECREDUCE_FMIN:                                         \
  case TargetOpcode::G_VECREDUCE_FMAXIMUM:                                     \
  case TargetOpcode::G_VECREDUCE_FMINIMUM:                                     \
  case TargetOpcode::G_VECREDUCE_ADD:                                          \
  case TargetOpcode::G_VECREDUCE_MUL:                                          \
  case TargetOpcode::G_VECREDUCE_AND:                                          \
  case TargetOpcode::G_VECREDUCE_OR:                                           \
  case TargetOpcode::G_VECREDUCE_XOR:                                          \
  case TargetOpcode::G_VECREDUCE_SMAX:                                         \
  case TargetOpcode::G_VECREDUCE_SMIN:                                         \
  case TargetOpcode::G_VECREDUCE_UMAX:                                         \
  case TargetOpcode::G_VECREDUCE_UMIN:
</div>
</dd>
</dl>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/utils-h">Utils.h</a>.</p>

</div>
</div>

### GISEL\_VECREDUCE\_CASES\_NONSEQ {#a42d8e909f2bea1119192cca95df057fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GISEL_VECREDUCE_CASES_NONSEQ&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case TargetOpcode::G_VECREDUCE_FADD:                                         \
  case TargetOpcode::G_VECREDUCE_FMUL:                                         \
  case TargetOpcode::G_VECREDUCE_FMAX:                                         \
  case TargetOpcode::G_VECREDUCE_FMIN:                                         \
  case TargetOpcode::G_VECREDUCE_FMAXIMUM:                                     \
  case TargetOpcode::G_VECREDUCE_FMINIMUM:                                     \
  case TargetOpcode::G_VECREDUCE_ADD:                                          \
  case TargetOpcode::G_VECREDUCE_MUL:                                          \
  case TargetOpcode::G_VECREDUCE_AND:                                          \
  case TargetOpcode::G_VECREDUCE_OR:                                           \
  case TargetOpcode::G_VECREDUCE_XOR:                                          \
  case TargetOpcode::G_VECREDUCE_SMAX:                                         \
  case TargetOpcode::G_VECREDUCE_SMIN:                                         \
  case TargetOpcode::G_VECREDUCE_UMAX:                                         \
  case TargetOpcode::G_VECREDUCE_UMIN:
</div>
</dd>
</dl>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/utils-h">Utils.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aa8fe481cda91a90b364e410009785003">llvm::LegalizerHelper::fewerElementsVector</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aa411af5653e9ed6cd4f664853b61bf0d">llvm::LegalizerHelper::lower</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
