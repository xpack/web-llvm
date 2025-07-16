---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/isd/outputarg
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `OutputArg` Struct Reference

<p><a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">OutputArg</a> - This struct carries flags and a value for a single outgoing (actual) argument or outgoing (from the perspective of the caller) return value virtual register. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::ISD::OutputArg { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetcallingconv-h">llvm/CodeGen/TargetCallingConv.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af260a571fd05a56ee1cbff2df731d8c5">OutputArg</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4abedbf68c72cdf0b9e467449a89fd3a">OutputArg</a> (ArgFlagsTy flags, MVT vt, EVT argvt, bool isfixed, unsigned origIdx, unsigned partOffs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ArgFlagsTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9b038a2e2396b3adaa0bf5afcb64ecd">Flags</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1917d95ba39feaf5b4a650070158e258">VT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace47c19b0e1662fc30bae524c74e562e">ArgVT</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bb58c151230b43fe1f83b08a3158548">IsFixed</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IsFixed - Is this a "fixed" value, ie not passed through a vararg "...". <a href="#a9bb58c151230b43fe1f83b08a3158548">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adac8e7c169fa96072e748b5e18c091cd">OrigArgIndex</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Index original <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>'s argument. <a href="#adac8e7c169fa96072e748b5e18c091cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54f80dfe606c40c169f70b4e3b4cfc0f">PartOffset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Offset in bytes of current output value relative to the beginning of original argument. <a href="#a54f80dfe606c40c169f70b4e3b4cfc0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">OutputArg</a> - This struct carries flags and a value for a single outgoing (actual) argument or outgoing (from the perspective of the caller) return value virtual register.</p>

<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetcallingconv-h">TargetCallingConv.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### OutputArg() {#af260a571fd05a56ee1cbff2df731d8c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ISD::OutputArg::OutputArg ()</td>
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



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetcallingconv-h">TargetCallingConv.h</a>.</p>

</div>
</div>

### OutputArg() {#a4abedbf68c72cdf0b9e467449a89fd3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ISD::OutputArg::OutputArg (<a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ArgFlagsTy</a> flags, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> vt, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> argvt, bool isfixed, unsigned origIdx, unsigned partOffs)</td>
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



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetcallingconv-h">TargetCallingConv.h</a>.</p>


<p>References <a href="#ace47c19b0e1662fc30bae524c74e562e">ArgVT</a>, <a href="#ae9b038a2e2396b3adaa0bf5afcb64ecd">Flags</a>, <a href="#a9bb58c151230b43fe1f83b08a3158548">IsFixed</a>, <a href="#adac8e7c169fa96072e748b5e18c091cd">OrigArgIndex</a>, <a href="#a54f80dfe606c40c169f70b4e3b4cfc0f">PartOffset</a> and <a href="#a1917d95ba39feaf5b4a650070158e258">VT</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ArgVT {#ace47c19b0e1662fc30bae524c74e562e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT llvm::ISD::OutputArg::ArgVT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetcallingconv-h">TargetCallingConv.h</a>.</p>


<p>Referenced by <a href="#a4abedbf68c72cdf0b9e467449a89fd3a">OutputArg</a>.</p>

</div>
</div>

### Flags {#ae9b038a2e2396b3adaa0bf5afcb64ecd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgFlagsTy llvm::ISD::OutputArg::Flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetcallingconv-h">TargetCallingConv.h</a>.</p>


<p>Referenced by <a href="#a4abedbf68c72cdf0b9e467449a89fd3a">OutputArg</a>.</p>

</div>
</div>

### IsFixed {#a9bb58c151230b43fe1f83b08a3158548}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::OutputArg::IsFixed = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IsFixed - Is this a "fixed" value, ie not passed through a vararg "...".</p>

<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetcallingconv-h">TargetCallingConv.h</a>.</p>


<p>Referenced by <a href="#a4abedbf68c72cdf0b9e467449a89fd3a">OutputArg</a>.</p>

</div>
</div>

### OrigArgIndex {#adac8e7c169fa96072e748b5e18c091cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ISD::OutputArg::OrigArgIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Index original <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>'s argument.</p>

<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetcallingconv-h">TargetCallingConv.h</a>.</p>


<p>Referenced by <a href="#a4abedbf68c72cdf0b9e467449a89fd3a">OutputArg</a>.</p>

</div>
</div>

### PartOffset {#a54f80dfe606c40c169f70b4e3b4cfc0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ISD::OutputArg::PartOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Offset in bytes of current output value relative to the beginning of original argument.</p>


<p>E.g. if argument was splitted into four 32 bit registers, we got 4 OutputArgs with PartOffsets 0, 4, 8 and 12.</p>


<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetcallingconv-h">TargetCallingConv.h</a>.</p>


<p>Referenced by <a href="#a4abedbf68c72cdf0b9e467449a89fd3a">OutputArg</a>.</p>

</div>
</div>

### VT {#a1917d95ba39feaf5b4a650070158e258}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT llvm::ISD::OutputArg::VT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetcallingconv-h">TargetCallingConv.h</a>.</p>


<p>Referenced by <a href="#a4abedbf68c72cdf0b9e467449a89fd3a">OutputArg</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetcallingconv-h">TargetCallingConv.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
