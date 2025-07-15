---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/irmover/structtypekeyinfo/keyty
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `KeyTy` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::IRMover::StructTypeKeyInfo::KeyTy { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/linker/irmover-h">llvm/Linker/IRMover.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14667b1b9a9683359f1b3faddf937e3f">KeyTy</a> (ArrayRef&lt; Type * &gt; E, bool P)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86d120bb232e943708fd59d0c03802c3">KeyTy</a> (const StructType *ST)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33f87c520ff964c5d3c2b7d858f77898">operator==</a> (const KeyTy &amp;that) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f459e0ea239e1bb557e3996d0a8b4ae">operator!=</a> (const KeyTy &amp;that) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65b04dde0888b357f62c1e5212aa04b0">ETypes</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2722698f84dd9eb7cb49da186648050e">IsPacked</a></td>
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


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/linker/irmover-h">IRMover.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### KeyTy() {#a14667b1b9a9683359f1b3faddf937e3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRMover::StructTypeKeyInfo::KeyTy::KeyTy (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; E, bool P)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/linker/irmover-h">IRMover.h</a>, definition at line 1668 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/irmover-cpp">IRMover.cpp</a>.</p>


<p>References <a href="#a65b04dde0888b357f62c1e5212aa04b0">ETypes</a>, <a href="#a2722698f84dd9eb7cb49da186648050e">IsPacked</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="#a8f459e0ea239e1bb557e3996d0a8b4ae">operator!=</a> and <a href="#a33f87c520ff964c5d3c2b7d858f77898">operator==</a>.</p>

</div>
</div>

### KeyTy() {#a86d120bb232e943708fd59d0c03802c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRMover::StructTypeKeyInfo::KeyTy::KeyTy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> * ST)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/linker/irmover-h">IRMover.h</a>, definition at line 1671 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/irmover-cpp">IRMover.cpp</a>.</p>


<p>References <a href="#a65b04dde0888b357f62c1e5212aa04b0">ETypes</a> and <a href="#a2722698f84dd9eb7cb49da186648050e">IsPacked</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a8f459e0ea239e1bb557e3996d0a8b4ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IRMover::StructTypeKeyInfo::KeyTy::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irmover/structtypekeyinfo/keyty">KeyTy</a> &amp; that)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/linker/irmover-h">IRMover.h</a>, definition at line 1678 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/irmover-cpp">IRMover.cpp</a>.</p>


<p>References <a href="#a14667b1b9a9683359f1b3faddf937e3f">KeyTy</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4d812a2dd18aa186c164447e20e348e7">llvm::operator==</a>.</p>

</div>
</div>

### operator==() {#a33f87c520ff964c5d3c2b7d858f77898}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IRMover::StructTypeKeyInfo::KeyTy::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irmover/structtypekeyinfo/keyty">KeyTy</a> &amp; that)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/linker/irmover-h">IRMover.h</a>, definition at line 1674 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/irmover-cpp">IRMover.cpp</a>.</p>


<p>References <a href="#a65b04dde0888b357f62c1e5212aa04b0">ETypes</a>, <a href="#a2722698f84dd9eb7cb49da186648050e">IsPacked</a> and <a href="#a14667b1b9a9683359f1b3faddf937e3f">KeyTy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ETypes {#a65b04dde0888b357f62c1e5212aa04b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;Type *&gt; llvm::IRMover::StructTypeKeyInfo::KeyTy::ETypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/linker/irmover-h">IRMover.h</a>.</p>


<p>Referenced by <a href="#a14667b1b9a9683359f1b3faddf937e3f">KeyTy</a>, <a href="#a86d120bb232e943708fd59d0c03802c3">KeyTy</a> and <a href="#a33f87c520ff964c5d3c2b7d858f77898">operator==</a>.</p>

</div>
</div>

### IsPacked {#a2722698f84dd9eb7cb49da186648050e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IRMover::StructTypeKeyInfo::KeyTy::IsPacked</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/linker/irmover-h">IRMover.h</a>.</p>


<p>Referenced by <a href="#a14667b1b9a9683359f1b3faddf937e3f">KeyTy</a>, <a href="#a86d120bb232e943708fd59d0c03802c3">KeyTy</a> and <a href="#a33f87c520ff964c5d3c2b7d858f77898">operator==</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/linker/irmover-h">IRMover.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/linker/irmover-cpp">IRMover.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
