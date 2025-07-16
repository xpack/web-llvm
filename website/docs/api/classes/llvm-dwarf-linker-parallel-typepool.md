---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf-linker/parallel/typepool
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TypePool` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typepool">TypePool</a> keeps type descriptors which contain partially cloned <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> correspinding to each type. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::dwarf_linker::parallel::TypePool { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/typepool-h">DWARFLinker/Parallel/TypePool.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/concurrenthashtablebyptr">ConcurrentHashTableByPtr&lt;KeyTy, KeyDataTy, AllocatorTy, Info&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6839d6a080e53655c5952f319ca64256">TypePool</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#ae00955922b792a539fb6b19062e0a1af">TypeEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d5dd239d695012f27da4cac70118c8a">insert</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeentrybody">TypeEntryBody</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4001c0dc6e6990fa6a0a2919e5db9068">getOrCreateTypeEntryBody</a> (TypeEntry *Entry, TypeEntry *ParentEntry)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create or return existing type entry body for the specified <span class="doxyComputerOutput">Entry</span>. <a href="#a4001c0dc6e6990fa6a0a2919e5db9068">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc3a99b565580cdbf5d12e00d21eac17">sortTypes</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sort children for each kept type entry. <a href="#afc3a99b565580cdbf5d12e00d21eac17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#ae00955922b792a539fb6b19062e0a1af">TypeEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7c866021042c7a61e07bb8278865dad">getRoot</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return root for all type entries. <a href="#ac7c866021042c7a61e07bb8278865dad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a276eec77bd8816b367fb396d8a1962ca">getThreadLocalAllocator</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return thread local allocator used by pool. <a href="#a276eec77bd8816b367fb396d8a1962ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#ae00955922b792a539fb6b19062e0a1af">TypeEntry</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#ae00955922b792a539fb6b19062e0a1af">TypeEntry</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaf3e39090db837a7c2900b8363a25ab">TypesComparator</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#ae00955922b792a539fb6b19062e0a1af">TypeEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29e4128240419e9ca8b3791b562a87ec">Root</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/parallel/#a4e82d98d22361038741bca9bd34bca85">llvm::parallel::PerThreadBumpPtrAllocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4f33abb56c0e0c3b016352b2b533242">Allocator</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typepool">TypePool</a> keeps type descriptors which contain partially cloned <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> correspinding to each type.</p>


<p>Types are identified by names.</p>


<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/typepool-h">TypePool.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TypePool() {#a6839d6a080e53655c5952f319ca64256}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::TypePool::TypePool ()</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/typepool-h">TypePool.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/concurrenthashtablebyptr/#aedb1b2d838f24c81b5c649395e24ef08">llvm::ConcurrentHashTableByPtr&lt; StringRef, TypeEntry, llvm::parallel::PerThreadBumpPtrAllocator, TypeEntryInfo &gt;::ConcurrentHashTableByPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeentrybody/#ad5911f089676e212db39133a0bba14e8">llvm::dwarf_linker::parallel::TypeEntryBody::create</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmapentry/#a09f6c55119f75e7997dab2bbd8d2f065">llvm::StringMapEntry&lt; std::atomic&lt; TypeEntryBody * &gt; &gt;::create</a> and <a href="#a29e4128240419e9ca8b3791b562a87ec">Root</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getOrCreateTypeEntryBody() {#a4001c0dc6e6990fa6a0a2919e5db9068}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeEntryBody * llvm::dwarf_linker::parallel::TypePool::getOrCreateTypeEntryBody (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#ae00955922b792a539fb6b19062e0a1af">TypeEntry</a> * Entry, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#ae00955922b792a539fb6b19062e0a1af">TypeEntry</a> * ParentEntry)</td>
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

<p>Create or return existing type entry body for the specified <span class="doxyComputerOutput">Entry</span>.</p>


<p>Link that entry as child for the specified <span class="doxyComputerOutput">ParentEntry</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The existing or created type entry body.</p></dd>
</dl>


<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/typepool-h">TypePool.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeentrybody/#ad5911f089676e212db39133a0bba14e8">llvm::dwarf_linker::parallel::TypeEntryBody::create</a> and <a href="/web-llvm/docs/api/classes/llvm/stringmapentrystorage/#a79b2f851e3b48002897943fc4049c9cb">llvm::StringMapEntryStorage&lt; ValueTy &gt;::getValue</a>.</p>

</div>
</div>

### getRoot() {#ac7c866021042c7a61e07bb8278865dad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeEntry * llvm::dwarf_linker::parallel::TypePool::getRoot ()</td>
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

<p>Return root for all type entries.</p>

<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/typepool-h">TypePool.h</a>.</p>


<p>Reference <a href="#a29e4128240419e9ca8b3791b562a87ec">Root</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ab33a7e6fdc362895e1b739081c1286ba">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmit</a> and <a href="#afc3a99b565580cdbf5d12e00d21eac17">sortTypes</a>.</p>

</div>
</div>

### getThreadLocalAllocator() {#a276eec77bd8816b367fb396d8a1962ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator &amp; llvm::dwarf_linker::parallel::TypePool::getThreadLocalAllocator ()</td>
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

<p>Return thread local allocator used by pool.</p>

<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/typepool-h">TypePool.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a1df1c26e0a60f062547d6ba537e0021a">llvm::dwarf_linker::parallel::CompileUnit::cloneDIE</a>.</p>

</div>
</div>

### insert() {#a9d5dd239d695012f27da4cac70118c8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeEntry * llvm::dwarf_linker::parallel::TypePool::insert (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/typepool-h">TypePool.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/concurrenthashtablebyptr/#aedb1b2d838f24c81b5c649395e24ef08">llvm::ConcurrentHashTableByPtr&lt; StringRef, TypeEntry, llvm::parallel::PerThreadBumpPtrAllocator, TypeEntryInfo &gt;::ConcurrentHashTableByPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmapentry/#aa90d7ff5110be6315425ec6c29da762b">llvm::StringMapEntry&lt; ValueTy &gt;::first</a> and <a href="#a9d5dd239d695012f27da4cac70118c8a">insert</a>.</p>


<p>Referenced by <a href="#a9d5dd239d695012f27da4cac70118c8a">insert</a>.</p>

</div>
</div>

### sortTypes() {#afc3a99b565580cdbf5d12e00d21eac17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::TypePool::sortTypes ()</td>
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

<p>Sort children for each kept type entry.</p>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/typepool-h">TypePool.h</a>.</p>


<p>References <a href="#ac7c866021042c7a61e07bb8278865dad">getRoot</a> and <a href="#aeaf3e39090db837a7c2900b8363a25ab">TypesComparator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Root {#a29e4128240419e9ca8b3791b562a87ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeEntry* llvm::dwarf_linker::parallel::TypePool::Root = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/typepool-h">TypePool.h</a>.</p>


<p>Referenced by <a href="#ac7c866021042c7a61e07bb8278865dad">getRoot</a> and <a href="#a6839d6a080e53655c5952f319ca64256">TypePool</a>.</p>

</div>
</div>

### TypesComparator {#aeaf3e39090db837a7c2900b8363a25ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;bool(const TypeEntry *LHS, const TypeEntry *RHS)&gt; llvm::dwarf_linker::parallel::TypePool::TypesComparator</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= [](<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#ae00955922b792a539fb6b19062e0a1af">TypeEntry</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#ae00955922b792a539fb6b19062e0a1af">TypeEntry</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>) -&gt; bool {
    return <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>-&gt;getKey() &lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>-&gt;getKey();
  }
</div>
</dd>
</dl>

<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/typepool-h">TypePool.h</a>.</p>


<p>Referenced by <a href="#afc3a99b565580cdbf5d12e00d21eac17">sortTypes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Allocator {#ac4f33abb56c0e0c3b016352b2b533242}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::parallel::PerThreadBumpPtrAllocator llvm::dwarf_linker::parallel::TypePool::Allocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/typepool-h">TypePool.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/typepool-h">TypePool.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
