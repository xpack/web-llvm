---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf5acceltable
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DWARF5AccelTable` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::DWARF5AccelTable { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">llvm/CodeGen/AccelTable.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/acceltable">AccelTable&lt;DataT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class holds an abstract representation of an Accelerator Table, consisting of a sequence of buckets, each bucket containint a sequence of <a href="/web-llvm/docs/api/structs/llvm/acceltablebase/hashdata">HashData</a> entries. <a href="/web-llvm/docs/api/classes/llvm/acceltable/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a2d092326240a50f35f66d64c236f71ca">TUVectorTy</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81ea2dcf89ff49b4ddea037fc39a0f2a">getTypeUnitsSymbols</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns type units that were constructed. <a href="#a81ea2dcf89ff49b4ddea037fc39a0f2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaecededcdfefeab442c2c79f2db781f6">addTypeUnitSymbol</a> (DwarfTypeUnit &amp;U)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a type unit start symbol. <a href="#aaecededcdfefeab442c2c79f2db781f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58236a7cda71ea19518aec7bd2c42661">addTypeUnitSignature</a> (DwarfTypeUnit &amp;U)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a type unit Signature. <a href="#a58236a7cda71ea19518aec7bd2c42661">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a669a5b9e22cbd07f9f999130ed20c46e">convertDieToOffset</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> entries to explicit offset. <a href="#a669a5b9e22cbd07f9f999130ed20c46e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acda854409535c8534bf80610784b613b">addTypeEntries</a> (DWARF5AccelTable &amp;Table)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a2d092326240a50f35f66d64c236f71ca">TUVectorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace0063e454459b137353a04f55026eb6">TUSymbolsOrHashes</a></td>
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


<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### addTypeEntries() {#acda854409535c8534bf80610784b613b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARF5AccelTable::addTypeEntries (<a href="/web-llvm/docs/api/classes/llvm/dwarf5acceltable">DWARF5AccelTable</a> &amp; Table)</td>
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



<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/acceltable/#ad2585d3987ba3e2ed2f15d52301a3c94">llvm::AccelTable&lt; DWARF5AccelTableData &gt;::addName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="/web-llvm/docs/api/classes/llvm/acceltable/#a687daa0ad98557c7e5f4893cbdc772ac">llvm::AccelTable&lt; DataT &gt;::getEntries</a>.</p>

</div>
</div>

### addTypeUnitSignature() {#a58236a7cda71ea19518aec7bd2c42661}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARF5AccelTable::addTypeUnitSignature (<a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit">DwarfTypeUnit</a> &amp; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a type unit Signature.</p>

<p>Declaration at line 414 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>, definition at line 706 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/acceltable-cpp">AccelTable.cpp</a>.</p>

</div>
</div>

### addTypeUnitSymbol() {#aaecededcdfefeab442c2c79f2db781f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARF5AccelTable::addTypeUnitSymbol (<a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit">DwarfTypeUnit</a> &amp; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a type unit start symbol.</p>

<p>Declaration at line 412 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>, definition at line 702 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/acceltable-cpp">AccelTable.cpp</a>.</p>

</div>
</div>

### convertDieToOffset() {#a669a5b9e22cbd07f9f999130ed20c46e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARF5AccelTable::convertDieToOffset ()</td>
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

<p>Convert <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> entries to explicit offset.</p>


<p>Needs to be called after <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> offsets are computed.</p>


<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="/web-llvm/docs/api/classes/llvm/acceltablebase/#af55272c030cb9540e06e2c79663d3f86">llvm::AccelTableBase::Entries</a>.</p>

</div>
</div>

### getTypeUnitsSymbols() {#a81ea2dcf89ff49b4ddea037fc39a0f2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TUVectorTy &amp; llvm::DWARF5AccelTable::getTypeUnitsSymbols ()</td>
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

<p>Returns type units that were constructed.</p>

<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac4372f5cbd92647d1f4f90fcdb8a5474">llvm::emitDWARF5AccelTable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### TUSymbolsOrHashes {#ace0063e454459b137353a04f55026eb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TUVectorTy llvm::DWARF5AccelTable::TUSymbolsOrHashes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/acceltable-cpp">AccelTable.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
