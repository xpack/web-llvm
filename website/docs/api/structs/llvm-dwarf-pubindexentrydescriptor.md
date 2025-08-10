---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dwarf/pubindexentrydescriptor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `PubIndexEntryDescriptor` Struct

<p>Describes an entry of the various gnu_pub* debug sections. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::dwarf::PubIndexEntryDescriptor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">llvm/BinaryFormat/Dwarf.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a8ef5c7b403bc51a24a99faba21ec5966">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fb02a28f34e4bd318ced32cd28f1ea3">PubIndexEntryDescriptor</a> (GDBIndexEntryKind Kind, GDBIndexEntryLinkage Linkage)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b07e847eb1e77bc760e3885f9d1e9d6">PubIndexEntryDescriptor</a> (GDBIndexEntryKind Kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5689c4041e22879a695a9f4eb8b54273">PubIndexEntryDescriptor</a> (uint8_t Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee36ab72318c5b379ec541e7be7b35fc">toBits</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa8b16f5736856a2cf2a7b6760e780496">GDBIndexEntryKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95a212504141f399610fb6f5f0f25ad9">Kind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#af7fa49be5f14db1ae78725f042601075">GDBIndexEntryLinkage</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cf2ac416beae32dd5e70d97af464edf">Linkage</a></td>
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

<p>Describes an entry of the various gnu_pub* debug sections.</p>


<p>The gnu_pub* kind looks like:</p>


<p>0-3 reserved 4-6 symbol kind 7 0 == global, 1 == static</p>


<p>A gdb_index descriptor includes the above kind, shifted 24 bits up with the offset of the cu within the debug_info section stored in those 24 bits.</p>


<p>Definition at line 1155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a8ef5c7b403bc51a24a99faba21ec5966}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
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
<td class="doxyEnumItemName">KIND_OFFSET<a id="a8ef5c7b403bc51a24a99faba21ec5966a7bdb1f15e5457e8174e82b455ef8cb9e"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">KIND_MASK<a id="a8ef5c7b403bc51a24a99faba21ec5966a81219f105d517f5033f2e24ce50f93ea"></a></td>
<td class="doxyEnumItemDescription"> (= 7 &lt;&lt; KIND_OFFSET)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LINKAGE_OFFSET<a id="a8ef5c7b403bc51a24a99faba21ec5966a85c8e2a777594ae90aa49cb66ae47e13"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LINKAGE_MASK<a id="a8ef5c7b403bc51a24a99faba21ec5966a62ef6dd0c2d5c780a5a1b5cd2f304e98"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; LINKAGE_OFFSET)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### PubIndexEntryDescriptor() {#a0fb02a28f34e4bd318ced32cd28f1ea3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf::PubIndexEntryDescriptor::PubIndexEntryDescriptor (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa8b16f5736856a2cf2a7b6760e780496">GDBIndexEntryKind</a> Kind, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#af7fa49be5f14db1ae78725f042601075">GDBIndexEntryLinkage</a> Linkage)</td>
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



<p>Definition at line 1158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>


<p>References <a href="#a95a212504141f399610fb6f5f0f25ad9">Kind</a> and <a href="#a7cf2ac416beae32dd5e70d97af464edf">Linkage</a>.</p>

</div>
</div>

### PubIndexEntryDescriptor() {#a7b07e847eb1e77bc760e3885f9d1e9d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf::PubIndexEntryDescriptor::PubIndexEntryDescriptor (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa8b16f5736856a2cf2a7b6760e780496">GDBIndexEntryKind</a> Kind)</td>
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



<p>Definition at line 1160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#af7fa49be5f14db1ae78725f042601075abd7dd3283cd836680c9779f0ca7960e8">llvm::dwarf::GIEL_EXTERNAL</a>, <a href="#a95a212504141f399610fb6f5f0f25ad9">Kind</a> and <a href="#a7cf2ac416beae32dd5e70d97af464edf">Linkage</a>.</p>

</div>
</div>

### PubIndexEntryDescriptor() {#a5689c4041e22879a695a9f4eb8b54273}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf::PubIndexEntryDescriptor::PubIndexEntryDescriptor (uint8_t Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>


<p>References <a href="#a95a212504141f399610fb6f5f0f25ad9">Kind</a> and <a href="#a7cf2ac416beae32dd5e70d97af464edf">Linkage</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### toBits() {#aee36ab72318c5b379ec541e7be7b35fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::dwarf::PubIndexEntryDescriptor::toBits ()</td>
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



<p>Definition at line 1167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>


<p>References <a href="#a95a212504141f399610fb6f5f0f25ad9">Kind</a> and <a href="#a7cf2ac416beae32dd5e70d97af464edf">Linkage</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Kind {#a95a212504141f399610fb6f5f0f25ad9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GDBIndexEntryKind llvm::dwarf::PubIndexEntryDescriptor::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>


<p>Referenced by <a href="#a7b07e847eb1e77bc760e3885f9d1e9d6">PubIndexEntryDescriptor</a>, <a href="#a0fb02a28f34e4bd318ced32cd28f1ea3">PubIndexEntryDescriptor</a>, <a href="#a5689c4041e22879a695a9f4eb8b54273">PubIndexEntryDescriptor</a> and <a href="#aee36ab72318c5b379ec541e7be7b35fc">toBits</a>.</p>

</div>
</div>

### Linkage {#a7cf2ac416beae32dd5e70d97af464edf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GDBIndexEntryLinkage llvm::dwarf::PubIndexEntryDescriptor::Linkage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>


<p>Referenced by <a href="#a7b07e847eb1e77bc760e3885f9d1e9d6">PubIndexEntryDescriptor</a>, <a href="#a0fb02a28f34e4bd318ced32cd28f1ea3">PubIndexEntryDescriptor</a>, <a href="#a5689c4041e22879a695a9f4eb8b54273">PubIndexEntryDescriptor</a> and <a href="#aee36ab72318c5b379ec541e7be7b35fc">toBits</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
