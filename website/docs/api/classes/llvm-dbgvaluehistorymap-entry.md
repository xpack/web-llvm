---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dbgvaluehistorymap/entry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Entry` Class

<p>Specifies a change in a variable's debug value history. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DbgValueHistoryMap::Entry { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dbgentityhistorycalculator-h">llvm/CodeGen/DbgEntityHistoryCalculator.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">EntryKind { <a href="#a8faceb2b5e06a5c451ed2826a251a6fe">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82e5382a6c3935325d02f92447db9719">Entry</a> (const MachineInstr *Instr, EntryKind Kind)</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a291c59e78175dad5465ba495dc3395d9">getInstr</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap/#a4265c0d28c85b8718ec1bbe653f730c1">EntryIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3ff9d741b8a1617ebdf67f6a191a46f">getEndIndex</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a8faceb2b5e06a5c451ed2826a251a6fe">EntryKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe69e402995510166e2d371f58e4377e">getEntryKind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a433a321f7d8ea1ebce86f849a8b48144">isClobber</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af55497d312b06c544559645f1704ace1">isDbgValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3efb92466cb77431ad1728ed249c5d97">isClosed</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed164c557082e36b16d28d237e12d4f8">endEntry</a> (EntryIndex EndIndex)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad03771bb8479c37821fc891fc834a0c8">DbgValueHistoryMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 1, <a href="#a8faceb2b5e06a5c451ed2826a251a6fe">EntryKind</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0a5543c0be07ec8f5aa24ef45f5d77a">Instr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap/#a4265c0d28c85b8718ec1bbe653f730c1">EntryIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab604b957d7a9c7476fb583edc2b47674">EndIndex</a></td>
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

<p>Specifies a change in a variable's debug value history.</p>


<p>There exist two types of entries:</p>


<ul class="doxyList ">
<li>Debug value entry:

A new debug value becomes live. If the entry's <span class="doxyComputerOutput">EndIndex</span> is <span class="doxyComputerOutput">NoEntry</span>, the value is valid until the end of the function. For other values, the index points to the entry in the entry vector that ends this debug value. The ending entry can either be an overlapping debug value, or an instruction that clobbers the value.</li>
<li>Clobbering entry:

This entry's instruction clobbers one or more preceding register-described debug values that have their end index set to this entry's position in the entry vector.</li>
</ul>

<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dbgentityhistorycalculator-h">DbgEntityHistoryCalculator.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### EntryKind {#a8faceb2b5e06a5c451ed2826a251a6fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::DbgValueHistoryMap::Entry::EntryKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DbgValue<a id="a8faceb2b5e06a5c451ed2826a251a6feae0b2e00729d636a0eb21047089ae4e9b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Clobber<a id="a8faceb2b5e06a5c451ed2826a251a6fead3bbe882180335a82af2d5584530d7ab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dbgentityhistorycalculator-h">DbgEntityHistoryCalculator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Entry() {#a82e5382a6c3935325d02f92447db9719}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DbgValueHistoryMap::Entry::Entry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * Instr, <a href="#a8faceb2b5e06a5c451ed2826a251a6fe">EntryKind</a> Kind)</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dbgentityhistorycalculator-h">DbgEntityHistoryCalculator.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap/#ab40e7785b2b4a89c507cfaf4f1430338">llvm::DbgValueHistoryMap::NoEntry</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### endEntry() {#aed164c557082e36b16d28d237e12d4f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DbgValueHistoryMap::Entry::endEntry (<a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap/#a4265c0d28c85b8718ec1bbe653f730c1">EntryIndex</a> EndIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dbgentityhistorycalculator-h">DbgEntityHistoryCalculator.h</a>, definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dbgentityhistorycalculator-cpp">DbgEntityHistoryCalculator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3efb92466cb77431ad1728ed249c5d97">isClosed</a> and <a href="#af55497d312b06c544559645f1704ace1">isDbgValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0c5e19523172e41e6a320be6fd748e17">llvm::calculateDbgEntityHistory</a>.</p>

</div>
</div>

### getEndIndex() {#aa3ff9d741b8a1617ebdf67f6a191a46f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EntryIndex llvm::DbgValueHistoryMap::Entry::getEndIndex ()</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dbgentityhistorycalculator-h">DbgEntityHistoryCalculator.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap/#aaaf208f55ecf4cf0c79d9f83a75c252f">llvm::DbgValueHistoryMap::dump</a>.</p>

</div>
</div>

### getEntryKind() {#abe69e402995510166e2d371f58e4377e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EntryKind llvm::DbgValueHistoryMap::Entry::getEntryKind ()</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dbgentityhistorycalculator-h">DbgEntityHistoryCalculator.h</a>.</p>


<p>Referenced by <a href="#a433a321f7d8ea1ebce86f849a8b48144">isClobber</a> and <a href="#af55497d312b06c544559645f1704ace1">isDbgValue</a>.</p>

</div>
</div>

### getInstr() {#a291c59e78175dad5465ba495dc3395d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstr * llvm::DbgValueHistoryMap::Entry::getInstr ()</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dbgentityhistorycalculator-h">DbgEntityHistoryCalculator.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap/#aaaf208f55ecf4cf0c79d9f83a75c252f">llvm::DbgValueHistoryMap::dump</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap/#aceba016c6edf58c62cc5a0e7001d70e4">llvm::DbgValueHistoryMap::hasNonEmptyLocation</a>.</p>

</div>
</div>

### isClobber() {#a433a321f7d8ea1ebce86f849a8b48144}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgValueHistoryMap::Entry::isClobber ()</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dbgentityhistorycalculator-h">DbgEntityHistoryCalculator.h</a>.</p>


<p>References <a href="#a8faceb2b5e06a5c451ed2826a251a6fead3bbe882180335a82af2d5584530d7ab">Clobber</a> and <a href="#abe69e402995510166e2d371f58e4377e">getEntryKind</a>.</p>

</div>
</div>

### isClosed() {#a3efb92466cb77431ad1728ed249c5d97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgValueHistoryMap::Entry::isClosed ()</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dbgentityhistorycalculator-h">DbgEntityHistoryCalculator.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap/#ab40e7785b2b4a89c507cfaf4f1430338">llvm::DbgValueHistoryMap::NoEntry</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0c5e19523172e41e6a320be6fd748e17">llvm::calculateDbgEntityHistory</a>, <a href="#aed164c557082e36b16d28d237e12d4f8">endEntry</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap/#a19a6a168a50b639280b51eada31cae76">llvm::DbgValueHistoryMap::trimLocationRanges</a>.</p>

</div>
</div>

### isDbgValue() {#af55497d312b06c544559645f1704ace1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgValueHistoryMap::Entry::isDbgValue ()</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dbgentityhistorycalculator-h">DbgEntityHistoryCalculator.h</a>.</p>


<p>References <a href="#a8faceb2b5e06a5c451ed2826a251a6feae0b2e00729d636a0eb21047089ae4e9b">DbgValue</a> and <a href="#abe69e402995510166e2d371f58e4377e">getEntryKind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0c5e19523172e41e6a320be6fd748e17">llvm::calculateDbgEntityHistory</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap/#aaaf208f55ecf4cf0c79d9f83a75c252f">llvm::DbgValueHistoryMap::dump</a>, <a href="#aed164c557082e36b16d28d237e12d4f8">endEntry</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap/#aceba016c6edf58c62cc5a0e7001d70e4">llvm::DbgValueHistoryMap::hasNonEmptyLocation</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DbgValueHistoryMap {#ad03771bb8479c37821fc891fc834a0c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::DbgValueHistoryMap::Entry::DbgValueHistoryMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dbgentityhistorycalculator-h">DbgEntityHistoryCalculator.h</a>.</p>

</div>
</div>

### EndIndex {#ab604b957d7a9c7476fb583edc2b47674}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EntryIndex llvm::DbgValueHistoryMap::Entry::EndIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dbgentityhistorycalculator-h">DbgEntityHistoryCalculator.h</a>.</p>

</div>
</div>

### Instr {#aa0a5543c0be07ec8f5aa24ef45f5d77a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerIntPair&lt;const MachineInstr *, 1, EntryKind&gt; llvm::DbgValueHistoryMap::Entry::Instr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dbgentityhistorycalculator-h">DbgEntityHistoryCalculator.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dbgentityhistorycalculator-h">DbgEntityHistoryCalculator.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dbgentityhistorycalculator-cpp">DbgEntityHistoryCalculator.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
