---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/nonrelocatablestringpool
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `NonRelocatableStringpool` Class

<p>A string table that doesn't need relocations. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::NonRelocatableStringpool { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/nonrelocatablestringpool-h">llvm/CodeGen/NonRelocatableStringpool.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/strongtype">StrongType&lt;T, S&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper for making strong types. <a href="/web-llvm/docs/api/classes/llvm/strongtype/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/strongtype">StrongType&lt;T, S&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper for making strong types. <a href="/web-llvm/docs/api/classes/llvm/strongtype/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66112d610babd2a7ef56b84e4daa4b87">MapTy</a> = <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentry">DwarfStringPoolEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Entries are stored into the <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a> and simply linked together through the second element of this pair in order to keep track of insertion order. <a href="#a66112d610babd2a7ef56b84e4daa4b87">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6894c288fd5cf163c1afb34c3ec5c81d">NonRelocatableStringpool</a> (bool PutEmptyString=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfstringpoolentryref">DwarfStringPoolEntryRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f09cd502a02a7f167d302f5bdde88e8">getEntry</a> (StringRef S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcdd0ccc4040ffdb46a684d771cacf8f">getStringOffset</a> (StringRef S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the offset of string <span class="doxyComputerOutput">S</span> in the string table. <a href="#adcdd0ccc4040ffdb46a684d771cacf8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6efe11e41ed3e37c95dc444f11580605">internString</a> (StringRef S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get permanent storage for <span class="doxyComputerOutput">S</span> (but do not necessarily emit <span class="doxyComputerOutput">S</span> in the output section). <a href="#a6efe11e41ed3e37c95dc444f11580605">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa65339df962a16332302d4634b47e570">getSize</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfstringpoolentryref">DwarfStringPoolEntryRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a648f04a20283c7dd28b9fad17ba85fac">getEntriesForEmission</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the list of strings to be emitted. <a href="#a648f04a20283c7dd28b9fad17ba85fac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a66112d610babd2a7ef56b84e4daa4b87">MapTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef8ec6918d60613a8f0a82cc2f92442c">Strings</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa46660176565335151d6ddaddde55428">CurrentEndOffset</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa031a713b2d6b2542b30f94625756962">NumEntries</a> = 0</td>
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

<p>A string table that doesn't need relocations.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> this class when a string table doesn't need relocations. This class provides this ability by just associating offsets with strings.</p>


<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/nonrelocatablestringpool-h">NonRelocatableStringpool.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### MapTy {#a66112d610babd2a7ef56b84e4daa4b87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::NonRelocatableStringpool::MapTy =  StringMap&lt;DwarfStringPoolEntry, BumpPtrAllocator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Entries are stored into the <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a> and simply linked together through the second element of this pair in order to keep track of insertion order.</p>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/nonrelocatablestringpool-h">NonRelocatableStringpool.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### NonRelocatableStringpool() {#a6894c288fd5cf163c1afb34c3ec5c81d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::NonRelocatableStringpool::NonRelocatableStringpool (bool PutEmptyString=false)</td>
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



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/nonrelocatablestringpool-h">NonRelocatableStringpool.h</a>.</p>


<p>Reference <a href="#a3f09cd502a02a7f167d302f5bdde88e8">getEntry</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getEntriesForEmission() {#a648f04a20283c7dd28b9fad17ba85fac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; DwarfStringPoolEntryRef &gt; llvm::NonRelocatableStringpool::getEntriesForEmission ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the list of strings to be emitted.</p>


<p>This does not contain the strings which were added via internString only.</p>


<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/nonrelocatablestringpool-h">NonRelocatableStringpool.h</a>, definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/nonrelocatablestringpool-cpp">NonRelocatableStringpool.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer/#a6af42c1280c80b31795c26ab738637d6">llvm::dwarf_linker::classic::DwarfStreamer::emitLineStrings</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer/#a4e79865080aad82450af13818c5bccde">llvm::dwarf_linker::classic::DwarfStreamer::emitStrings</a>.</p>

</div>
</div>

### getEntry() {#a3f09cd502a02a7f167d302f5bdde88e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfStringPoolEntryRef llvm::NonRelocatableStringpool::getEntry (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/nonrelocatablestringpool-h">NonRelocatableStringpool.h</a>, definition at line 14 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/nonrelocatablestringpool-cpp">NonRelocatableStringpool.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>


<p>Referenced by <a href="#adcdd0ccc4040ffdb46a684d771cacf8f">getStringOffset</a> and <a href="#a6894c288fd5cf163c1afb34c3ec5c81d">NonRelocatableStringpool</a>.</p>

</div>
</div>

### getSize() {#aa65339df962a16332302d4634b47e570}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::NonRelocatableStringpool::getSize ()</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/nonrelocatablestringpool-h">NonRelocatableStringpool.h</a>.</p>

</div>
</div>

### getStringOffset() {#adcdd0ccc4040ffdb46a684d771cacf8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::NonRelocatableStringpool::getStringOffset (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
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

<p>Get the offset of string <span class="doxyComputerOutput">S</span> in the string table.</p>


<p>This can insert a new element or return the offset of a pre-existing one.</p>


<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/nonrelocatablestringpool-h">NonRelocatableStringpool.h</a>.</p>


<p>Reference <a href="#a3f09cd502a02a7f167d302f5bdde88e8">getEntry</a>.</p>

</div>
</div>

### internString() {#a6efe11e41ed3e37c95dc444f11580605}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::NonRelocatableStringpool::internString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get permanent storage for <span class="doxyComputerOutput">S</span> (but do not necessarily emit <span class="doxyComputerOutput">S</span> in the output section).</p>


<p>A latter call to <a href="#adcdd0ccc4040ffdb46a684d771cacf8f">getStringOffset()</a> with the same string will chain it though.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> that points to permanent storage to use in place of <span class="doxyComputerOutput">S</span>.</p></dd>
</dl>


<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/nonrelocatablestringpool-h">NonRelocatableStringpool.h</a>, definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/nonrelocatablestringpool-cpp">NonRelocatableStringpool.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentry/#a7a1b7fb50f627423becd2123526ff26b">llvm::DwarfStringPoolEntry::NotIndexed</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CurrentEndOffset {#aa46660176565335151d6ddaddde55428}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::NonRelocatableStringpool::CurrentEndOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/nonrelocatablestringpool-h">NonRelocatableStringpool.h</a>.</p>

</div>
</div>

### NumEntries {#aa031a713b2d6b2542b30f94625756962}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::NonRelocatableStringpool::NumEntries = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/nonrelocatablestringpool-h">NonRelocatableStringpool.h</a>.</p>

</div>
</div>

### Strings {#aef8ec6918d60613a8f0a82cc2f92442c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapTy llvm::NonRelocatableStringpool::Strings</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/nonrelocatablestringpool-h">NonRelocatableStringpool.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/nonrelocatablestringpool-h">NonRelocatableStringpool.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/nonrelocatablestringpool-cpp">NonRelocatableStringpool.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
