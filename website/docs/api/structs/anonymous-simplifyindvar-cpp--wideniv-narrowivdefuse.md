---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `NarrowIVDefUse` Struct

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> a link in the Narrow IV def-use chain along with the WideIV that computes the same value as the Narrow IV def. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a955ac9474c41fccd8a181bf35cb3f8a6">NarrowIVDefUse</a> (Instruction *ND, Instruction *NU, Instruction *WD, bool NeverNegative)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e016da67d6b8bbf10f63bb125d25e11">NarrowDef</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d5e94a7ebb4f2950eec1132228f6556">NarrowUse</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41ae7e1b14cb78ee141c769563f59a7c">WideDef</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeef9f24cc8914e50d2296cdd85b87fdc">NeverNegative</a> = false</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> a link in the Narrow IV def-use chain along with the WideIV that computes the same value as the Narrow IV def.</p>


<p>This avoids caching Use* pointers.</p>


<p>Definition at line 1115 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### NarrowIVDefUse() {#a955ac9474c41fccd8a181bf35cb3f8a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::NarrowIVDefUse (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * ND, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * NU, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * WD, bool NeverNegative)</td>
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



<p>Definition at line 1125 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="#a5e016da67d6b8bbf10f63bb125d25e11">NarrowDef</a>, <a href="#a7d5e94a7ebb4f2950eec1132228f6556">NarrowUse</a>, <a href="#aeef9f24cc8914e50d2296cdd85b87fdc">NeverNegative</a> and <a href="#a41ae7e1b14cb78ee141c769563f59a7c">WideDef</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### NarrowDef {#a5e016da67d6b8bbf10f63bb125d25e11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::NarrowDef = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1116 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#aee57a451f8dea6781fa17e7728ee78b5">anonymous{SimplifyIndVar.cpp}::WidenIV::cloneArithmeticIVUser</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#ae5441d4cfeb857eb3f3afad58fd88c08">anonymous{SimplifyIndVar.cpp}::WidenIV::cloneBitwiseIVUser</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a5586ec5eac8a93b87b095f949ea8daf3">anonymous{SimplifyIndVar.cpp}::WidenIV::createWideIV</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a5acadc27f8741ff017a264df16bb8885">anonymous{SimplifyIndVar.cpp}::WidenIV::getExtendedOperandRecurrence</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a2c90afd148f896bab791bdcad6b41dd0">anonymous{SimplifyIndVar.cpp}::WidenIV::getWideRecurrence</a>, <a href="#a955ac9474c41fccd8a181bf35cb3f8a6">NarrowIVDefUse</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a821be8169bc31b8413a69cd7f22ff9ab">anonymous{SimplifyIndVar.cpp}::WidenIV::truncateIVUse</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a39eadf98e4773739cd4e7b4befee6fb5">anonymous{SimplifyIndVar.cpp}::WidenIV::widenIVUse</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#aa9eefc297d0b2b8097701f80c06ba19d">anonymous{SimplifyIndVar.cpp}::WidenIV::widenLoopCompare</a> and <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#acd093283d4e8d1301859f0a98a157680">anonymous{SimplifyIndVar.cpp}::WidenIV::widenWithVariantUse</a>.</p>

</div>
</div>

### NarrowUse {#a7d5e94a7ebb4f2950eec1132228f6556}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::NarrowUse = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1117 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#aee57a451f8dea6781fa17e7728ee78b5">anonymous{SimplifyIndVar.cpp}::WidenIV::cloneArithmeticIVUser</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#ae5441d4cfeb857eb3f3afad58fd88c08">anonymous{SimplifyIndVar.cpp}::WidenIV::cloneBitwiseIVUser</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a7ee5e663199f460b53a80855073e21bd">anonymous{SimplifyIndVar.cpp}::WidenIV::cloneIVUser</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a5586ec5eac8a93b87b095f949ea8daf3">anonymous{SimplifyIndVar.cpp}::WidenIV::createWideIV</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a5acadc27f8741ff017a264df16bb8885">anonymous{SimplifyIndVar.cpp}::WidenIV::getExtendedOperandRecurrence</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a2c90afd148f896bab791bdcad6b41dd0">anonymous{SimplifyIndVar.cpp}::WidenIV::getWideRecurrence</a>, <a href="#a955ac9474c41fccd8a181bf35cb3f8a6">NarrowIVDefUse</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a821be8169bc31b8413a69cd7f22ff9ab">anonymous{SimplifyIndVar.cpp}::WidenIV::truncateIVUse</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a39eadf98e4773739cd4e7b4befee6fb5">anonymous{SimplifyIndVar.cpp}::WidenIV::widenIVUse</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#aa9eefc297d0b2b8097701f80c06ba19d">anonymous{SimplifyIndVar.cpp}::WidenIV::widenLoopCompare</a> and <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#acd093283d4e8d1301859f0a98a157680">anonymous{SimplifyIndVar.cpp}::WidenIV::widenWithVariantUse</a>.</p>

</div>
</div>

### NeverNegative {#aeef9f24cc8914e50d2296cdd85b87fdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::NeverNegative = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1123 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a5acadc27f8741ff017a264df16bb8885">anonymous{SimplifyIndVar.cpp}::WidenIV::getExtendedOperandRecurrence</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a2c90afd148f896bab791bdcad6b41dd0">anonymous{SimplifyIndVar.cpp}::WidenIV::getWideRecurrence</a>, <a href="#a955ac9474c41fccd8a181bf35cb3f8a6">NarrowIVDefUse</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a821be8169bc31b8413a69cd7f22ff9ab">anonymous{SimplifyIndVar.cpp}::WidenIV::truncateIVUse</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a39eadf98e4773739cd4e7b4befee6fb5">anonymous{SimplifyIndVar.cpp}::WidenIV::widenIVUse</a> and <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#aa9eefc297d0b2b8097701f80c06ba19d">anonymous{SimplifyIndVar.cpp}::WidenIV::widenLoopCompare</a>.</p>

</div>
</div>

### WideDef {#a41ae7e1b14cb78ee141c769563f59a7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::WideDef = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1118 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#aee57a451f8dea6781fa17e7728ee78b5">anonymous{SimplifyIndVar.cpp}::WidenIV::cloneArithmeticIVUser</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#ae5441d4cfeb857eb3f3afad58fd88c08">anonymous{SimplifyIndVar.cpp}::WidenIV::cloneBitwiseIVUser</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a5acadc27f8741ff017a264df16bb8885">anonymous{SimplifyIndVar.cpp}::WidenIV::getExtendedOperandRecurrence</a>, <a href="#a955ac9474c41fccd8a181bf35cb3f8a6">NarrowIVDefUse</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a821be8169bc31b8413a69cd7f22ff9ab">anonymous{SimplifyIndVar.cpp}::WidenIV::truncateIVUse</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a39eadf98e4773739cd4e7b4befee6fb5">anonymous{SimplifyIndVar.cpp}::WidenIV::widenIVUse</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#aa9eefc297d0b2b8097701f80c06ba19d">anonymous{SimplifyIndVar.cpp}::WidenIV::widenLoopCompare</a> and <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#acd093283d4e8d1301859f0a98a157680">anonymous{SimplifyIndVar.cpp}::WidenIV::widenWithVariantUse</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
