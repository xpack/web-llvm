---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/enumtables-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `EnumTables.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/enumtables-h">llvm/DebugInfo/PDB/Native/EnumTables.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/rawconstants-h">llvm/DebugInfo/PDB/Native/RawConstants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scopedprinter-h">llvm/Support/ScopedPrinter.h</a>"
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/pdb">pdb</a></td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/enumentry">EnumEntry</a>&lt; uint16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a775045dee7acef62b40d364e9f4c0f3a">OMFSegMapDescFlagNames</a>[] = ...</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e056b4e14acc1f861119e7a25b98f81">PDB_ENUM_CLASS_ENT</a>(enum_class, enum)&nbsp;&nbsp;&nbsp;  { #enum, std::underlying_type_t&lt;enum_class&gt;(enum_class::enum) }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a597ab97aa58e7146e905dda529b8ffd1">PDB_ENUM_ENT</a>(ns, enum)&nbsp;&nbsp;&nbsp;  { #enum, ns::enum }</td>
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

## Variables

### OMFSegMapDescFlagNames {#a775045dee7acef62b40d364e9f4c0f3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const EnumEntry&lt;uint16_t&gt; OMFSegMapDescFlagNames[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    <a href="#a7e056b4e14acc1f861119e7a25b98f81">PDB_ENUM_CLASS_ENT</a>(<a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a39ee700138913a49bc90faf2c1db0b9b">OMFSegDescFlags</a>, Read),
    <a href="#a7e056b4e14acc1f861119e7a25b98f81">PDB_ENUM_CLASS_ENT</a>(<a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a39ee700138913a49bc90faf2c1db0b9b">OMFSegDescFlags</a>, Write),
    <a href="#a7e056b4e14acc1f861119e7a25b98f81">PDB_ENUM_CLASS_ENT</a>(<a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a39ee700138913a49bc90faf2c1db0b9b">OMFSegDescFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/program-cpp/#a3cc4767a85e498eea6b41bfbbdb4d2e9">Execute</a>),
    <a href="#a7e056b4e14acc1f861119e7a25b98f81">PDB_ENUM_CLASS_ENT</a>(<a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a39ee700138913a49bc90faf2c1db0b9b">OMFSegDescFlags</a>, AddressIs32Bit),
    <a href="#a7e056b4e14acc1f861119e7a25b98f81">PDB_ENUM_CLASS_ENT</a>(<a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a39ee700138913a49bc90faf2c1db0b9b">OMFSegDescFlags</a>, IsSelector),
    <a href="#a7e056b4e14acc1f861119e7a25b98f81">PDB_ENUM_CLASS_ENT</a>(<a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a39ee700138913a49bc90faf2c1db0b9b">OMFSegDescFlags</a>, IsAbsoluteAddress),
    <a href="#a7e056b4e14acc1f861119e7a25b98f81">PDB_ENUM_CLASS_ENT</a>(<a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a39ee700138913a49bc90faf2c1db0b9b">OMFSegDescFlags</a>, IsGroup),
}
</div>
</dd>
</dl>

<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/enumtables-cpp">EnumTables.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#aa09217ff0c27f62d91ae4c196d66cb14">llvm::pdb::getOMFSegMapDescFlagNames</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### PDB\_ENUM\_CLASS\_ENT {#a7e056b4e14acc1f861119e7a25b98f81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PDB_ENUM_CLASS_ENT(enum_class, enum)&nbsp;&nbsp;&nbsp;  { #enum, std::underlying_type_t&lt;enum_class&gt;(enum_class::enum) }</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 16 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/enumtables-cpp">EnumTables.cpp</a>.</p>

</div>
</div>

### PDB\_ENUM\_ENT {#a597ab97aa58e7146e905dda529b8ffd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PDB_ENUM_ENT(ns, enum)&nbsp;&nbsp;&nbsp;  { #enum, ns::enum }</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/enumtables-cpp">EnumTables.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
