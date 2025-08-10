---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/acceltable
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AccelTable` Class Template

<p>This class holds an abstract representation of an Accelerator Table, consisting of a sequence of buckets, each bucket containint a sequence of <a href="/web-llvm/docs/api/structs/llvm/acceltablebase/hashdata">HashData</a> entries. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename DataT&gt;
class llvm::AccelTable&lt;DataT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">llvm/CodeGen/AccelTable.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/acceltablebase">AccelTableBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A base class holding non-template-dependant functionality of the <a href="/web-llvm/docs/api/classes/llvm/acceltable">AccelTable</a> class. <a href="/web-llvm/docs/api/classes/llvm/acceltablebase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DataT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ad99be2267081a09c4c406456ad3d8ff8">AccelTable</a> ()</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename... Types&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad2585d3987ba3e2ed2f15d52301a3c94">addName</a> (DwarfStringPoolEntryRef Name, Types &amp;&amp;... Args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DataT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0f515f50eb9e30dc1cdfef163acfcd8a">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DataT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac388f93e2c3bb0b0015eb24e6c289e7d">addEntries</a> (AccelTable&lt; DataT &gt; &amp;Table)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DataT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/acceltablebase/#ab730d5ae3fc18252ce068047dd4bf339">StringEntries</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a687daa0ad98557c7e5f4893cbdc772ac">getEntries</a> () const</td>
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

<p>This class holds an abstract representation of an Accelerator Table, consisting of a sequence of buckets, each bucket containint a sequence of <a href="/web-llvm/docs/api/structs/llvm/acceltablebase/hashdata">HashData</a> entries.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/user">User</a> of DwarfEmitterImpl should call initialization code for <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a>:</p>


<p>The class is parameterized by the type of entries it holds. The type template parameter also defines the hash function to use for hashing names.</p>


<p><a href="/web-llvm/docs/api/namespaces/llvm/#a2c23d23778140065e285b5263d7d905a">InitializeAllTargetInfos()</a>; <a href="/web-llvm/docs/api/namespaces/llvm/#a162474ccafa6e8ccf58b2b60e7c63845">InitializeAllTargetMCs()</a>; <a href="/web-llvm/docs/api/namespaces/llvm/#ad27eabc8391834dce3a68261f8a334db">InitializeAllTargets()</a>; <a href="/web-llvm/docs/api/namespaces/llvm/#af12a586afbaec83aa9cd8b7e9ab0c116">InitializeAllAsmPrinters()</a>;</p>


<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AccelTable() {#ad99be2267081a09c4c406456ad3d8ff8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DataT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AccelTable&lt; DataT &gt;::AccelTable ()</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/acceltablebase/#a8932a0af798c0b6874c79c7e13816ab1">llvm::AccelTableBase::AccelTableBase</a>.</p>


<p>Referenced by <a href="#ac388f93e2c3bb0b0015eb24e6c289e7d">llvm::AccelTable&lt; DataT &gt;::addEntries</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addEntries() {#ac388f93e2c3bb0b0015eb24e6c289e7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DataT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AccelTable&lt; DataT &gt;::addEntries (<a href="/web-llvm/docs/api/classes/llvm/acceltable">AccelTable</a>&lt; DataT &gt; &amp; Table)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>Reference <a href="#ad99be2267081a09c4c406456ad3d8ff8">llvm::AccelTable&lt; DataT &gt;::AccelTable</a>.</p>

</div>
</div>

### addName() {#ad2585d3987ba3e2ed2f15d52301a3c94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... Types&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AccelTable&lt; AccelTableDataT &gt;::addName (<a href="/web-llvm/docs/api/classes/llvm/dwarfstringpoolentryref">DwarfStringPoolEntryRef</a> Name, Types &amp;&amp;... Args)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/acceltablebase/#a30649c14f157ff596353d96586606f5a">llvm::AccelTableBase::Allocator</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/acceltablebase/#a0c19310cea0ac7206b5f3d7fb3fa53ad">llvm::AccelTableBase::Buckets</a>, <a href="/web-llvm/docs/api/classes/llvm/acceltablebase/#af55272c030cb9540e06e2c79663d3f86">llvm::AccelTableBase::Entries</a> and <a href="/web-llvm/docs/api/classes/llvm/acceltablebase/#a56a09c73b598e3560200b249fd9e0afc">llvm::AccelTableBase::Hash</a>.</p>

</div>
</div>

### clear() {#a0f515f50eb9e30dc1cdfef163acfcd8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DataT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AccelTable&lt; DataT &gt;::clear ()</td>
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



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/acceltablebase/#af55272c030cb9540e06e2c79663d3f86">llvm::AccelTableBase::Entries</a>.</p>

</div>
</div>

### getEntries() {#a687daa0ad98557c7e5f4893cbdc772ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DataT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const StringEntries llvm::AccelTable&lt; DataT &gt;::getEntries ()</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/acceltablebase/#af55272c030cb9540e06e2c79663d3f86">llvm::AccelTableBase::Entries</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf5acceltable/#acda854409535c8534bf80610784b613b">llvm::DWARF5AccelTable::addTypeEntries</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
