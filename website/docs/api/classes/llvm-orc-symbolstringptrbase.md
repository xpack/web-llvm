---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/symbolstringptrbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SymbolStringPtrBase` Class Reference

<p>Base class for both owning and non-owning symbol-string ptrs. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::SymbolStringPtrBase { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">llvm/ExecutionEngine/Orc/SymbolStringPool.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/nonowningsymbolstringptr">NonOwningSymbolStringPtr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Non-owning <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringpool">SymbolStringPool</a> entry pointer. <a href="/web-llvm/docs/api/classes/llvm/orc/nonowningsymbolstringptr/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pointer to a pooled string representing a symbol name. <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebb3cd4d613cd5b3d221aaae4edf5569">PoolEntry</a> = <a href="/web-llvm/docs/api/classes/llvm/stringmapentry">SymbolStringPool::PoolMapEntry</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06b870f4121fbfb731e868be15bb29bb">PoolEntryPtr</a> = <a href="#aebb3cd4d613cd5b3d221aaae4edf5569">PoolEntry</a> *</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d138690b665adad56e54e7dd02add11">SymbolStringPool</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a482cd8d2598e81796c3a59c45eaef7d5">DenseMapInfo&lt; SymbolStringPtr &gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88f314c1255acfed0196cf710bae656d">DenseMapInfo&lt; NonOwningSymbolStringPtr &gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b7ce7f9f1c791bd2f0b49f8e6da71d6">operator==</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26be68a9375f75e5f50eddcea618ea2a">operator!=</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e5409fcef534cd27b47d7d43a408c37">operator&lt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a110e9c1b1b05e2c756e957217488c505">operator&lt;&lt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a334e27918886db7a1a9e3ac95e34d569">SymbolStringPtrBase</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af651c5737b9068c9d88afc90feb6cc76">SymbolStringPtrBase</a> (std::nullptr_t)</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9228c32870e4e7468129f513bdf08d7">SymbolStringPtrBase</a> (PoolEntryPtr S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebe2819e3240c427fbe3fa1e5db0499b">operator bool</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8409e0a17be65178506004871bdddd21">operator*</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f51f2be1bf297c8b1e549a97013704b">poolEntryIsAlive</a> () const</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c61081d6ca746abebdb07d0f0e5b88a">getRefCount</a> () const</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a06b870f4121fbfb731e868be15bb29bb">PoolEntryPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa114e683cff1ea8ab53012cc24dd8ae7">S</a> = nullptr</td>
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

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14c3bf7cb9994c35678a43283a4c2d18">isRealPoolEntry</a> (PoolEntryPtr P)</td>
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

## Protected Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ab60cb2e191e0f337c5b9c01f83df50">EmptyBitPattern</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c12eb3feddd7779165cfb2cd143c3b9">TombstoneBitPattern</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60013cce074a97d7be044661b9987518">InvalidPtrMask</a> = ...</td>
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

<p>Base class for both owning and non-owning symbol-string ptrs.</p>


<p>All symbol-string ptrs are convertible to bool, dereferenceable and comparable.</p>


<p>SymbolStringPtrBases are default-constructible and constructible from nullptr to enable comparison with these values.</p>


<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>


<div class="doxySectionDef">

## Protected Member Typedefs

### PoolEntry {#aebb3cd4d613cd5b3d221aaae4edf5569}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::SymbolStringPtrBase::PoolEntry =  SymbolStringPool::PoolMapEntry</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>

</div>
</div>

### PoolEntryPtr {#a06b870f4121fbfb731e868be15bb29bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::SymbolStringPtrBase::PoolEntryPtr =  PoolEntry *</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### DenseMapInfo&lt; NonOwningSymbolStringPtr &gt; {#a88f314c1255acfed0196cf710bae656d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/densemapinfo">DenseMapInfo</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/nonowningsymbolstringptr">NonOwningSymbolStringPtr</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>


<p>Reference <a href="#a3d138690b665adad56e54e7dd02add11">SymbolStringPool</a>.</p>

</div>
</div>

### DenseMapInfo&lt; SymbolStringPtr &gt; {#a482cd8d2598e81796c3a59c45eaef7d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/densemapinfo">DenseMapInfo</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>

</div>
</div>

### operator!= {#a26be68a9375f75e5f50eddcea618ea2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptrbase">SymbolStringPtrBase</a> LHS, <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptrbase">SymbolStringPtrBase</a> RHS</td>
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


<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a334e27918886db7a1a9e3ac95e34d569">SymbolStringPtrBase</a>.</p>

</div>
</div>

### operator&lt; {#a3e5409fcef534cd27b47d7d43a408c37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptrbase">SymbolStringPtrBase</a> LHS, <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptrbase">SymbolStringPtrBase</a> RHS</td>
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


<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a334e27918886db7a1a9e3ac95e34d569">SymbolStringPtrBase</a>.</p>

</div>
</div>

### operator&lt;&lt; {#a110e9c1b1b05e2c756e957217488c505}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptrbase">SymbolStringPtrBase</a> &amp; Sym</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>, definition at line 14 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/symbolstringpool-cpp">SymbolStringPool.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringmapentry/#aa90d7ff5110be6315425ec6c29da762b">llvm::StringMapEntry&lt; ValueTy &gt;::first</a>, <a href="#aa114e683cff1ea8ab53012cc24dd8ae7">S</a> and <a href="#a334e27918886db7a1a9e3ac95e34d569">SymbolStringPtrBase</a>.</p>

</div>
</div>

### operator== {#a5b7ce7f9f1c791bd2f0b49f8e6da71d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptrbase">SymbolStringPtrBase</a> LHS, <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptrbase">SymbolStringPtrBase</a> RHS</td>
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


<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a334e27918886db7a1a9e3ac95e34d569">SymbolStringPtrBase</a>.</p>

</div>
</div>

### SymbolStringPool {#a3d138690b665adad56e54e7dd02add11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringpool">SymbolStringPool</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>


<p>Referenced by <a href="#a88f314c1255acfed0196cf710bae656d">DenseMapInfo&lt; NonOwningSymbolStringPtr &gt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SymbolStringPtrBase() {#a334e27918886db7a1a9e3ac95e34d569}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::SymbolStringPtrBase::SymbolStringPtrBase ()</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/nonowningsymbolstringptr/#ad73e0535a9a136547f13a1a26e771cfc">llvm::orc::NonOwningSymbolStringPtr::NonOwningSymbolStringPtr</a>, <a href="#a26be68a9375f75e5f50eddcea618ea2a">operator!=</a>, <a href="#a3e5409fcef534cd27b47d7d43a408c37">operator&lt;</a>, <a href="#a110e9c1b1b05e2c756e957217488c505">operator&lt;&lt;</a>, <a href="#a5b7ce7f9f1c791bd2f0b49f8e6da71d6">operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr/#a4d790896dc61ffa90284f101f4c0c250">llvm::orc::SymbolStringPtr::SymbolStringPtr</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr/#a296e6fc69dc1f640b1c42f19e9e9e3f8">llvm::orc::SymbolStringPtr::SymbolStringPtr</a>.</p>

</div>
</div>

### SymbolStringPtrBase() {#af651c5737b9068c9d88afc90feb6cc76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::SymbolStringPtrBase::SymbolStringPtrBase (std::nullptr_t)</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### SymbolStringPtrBase() {#ae9228c32870e4e7468129f513bdf08d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::SymbolStringPtrBase::SymbolStringPtrBase (<a href="#a06b870f4121fbfb731e868be15bb29bb">PoolEntryPtr</a> S)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>


<p>Reference <a href="#aa114e683cff1ea8ab53012cc24dd8ae7">S</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator bool() {#aebe2819e3240c427fbe3fa1e5db0499b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::SymbolStringPtrBase::operator bool ()</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>


<p>Reference <a href="#aa114e683cff1ea8ab53012cc24dd8ae7">S</a>.</p>

</div>
</div>

### operator\*() {#a8409e0a17be65178506004871bdddd21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::orc::SymbolStringPtrBase::operator* ()</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>


<p>Reference <a href="#aa114e683cff1ea8ab53012cc24dd8ae7">S</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### poolEntryIsAlive() {#a2f51f2be1bf297c8b1e549a97013704b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::SymbolStringPtrBase::poolEntryIsAlive ()</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>


<p>References <a href="#a14c3bf7cb9994c35678a43283a4c2d18">isRealPoolEntry</a> and <a href="#aa114e683cff1ea8ab53012cc24dd8ae7">S</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr/#a296e6fc69dc1f640b1c42f19e9e9e3f8">llvm::orc::SymbolStringPtr::SymbolStringPtr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getRefCount() {#a7c61081d6ca746abebdb07d0f0e5b88a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::orc::SymbolStringPtrBase::getRefCount ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>


<p>References <a href="#a14c3bf7cb9994c35678a43283a4c2d18">isRealPoolEntry</a> and <a href="#aa114e683cff1ea8ab53012cc24dd8ae7">S</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### S {#aa114e683cff1ea8ab53012cc24dd8ae7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PoolEntryPtr llvm::orc::SymbolStringPtrBase::S = nullptr</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringpoolentryunsafe/#a08a5c6e6a4cc582bb37eb471ba039019">llvm::orc::SymbolStringPoolEntryUnsafe::from</a>, <a href="#a7c61081d6ca746abebdb07d0f0e5b88a">getRefCount</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringpoolentryunsafe/#ab404390b250a0b4ca46d3a6ec59b65d0">llvm::orc::SymbolStringPoolEntryUnsafe::moveToSymbolStringPtr</a>, <a href="#aebe2819e3240c427fbe3fa1e5db0499b">operator bool</a>, <a href="#a8409e0a17be65178506004871bdddd21">operator*</a>, <a href="#a110e9c1b1b05e2c756e957217488c505">operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr/#ab589619d31010e7cd7159dfd84a7c966">llvm::orc::SymbolStringPtr::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr/#aa705c22cc74b735ca4a65d4d446b3468">llvm::orc::SymbolStringPtr::operator=</a>, <a href="#a2f51f2be1bf297c8b1e549a97013704b">poolEntryIsAlive</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr/#a4d790896dc61ffa90284f101f4c0c250">llvm::orc::SymbolStringPtr::SymbolStringPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr/#a296e6fc69dc1f640b1c42f19e9e9e3f8">llvm::orc::SymbolStringPtr::SymbolStringPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr/#af3b8aff0ad25b1ae523b52dfacfea97b">llvm::orc::SymbolStringPtr::SymbolStringPtr</a> and <a href="#ae9228c32870e4e7468129f513bdf08d7">SymbolStringPtrBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### isRealPoolEntry() {#a14c3bf7cb9994c35678a43283a4c2d18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::SymbolStringPtrBase::isRealPoolEntry (<a href="#a06b870f4121fbfb731e868be15bb29bb">PoolEntryPtr</a> P)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>


<p>References <a href="#a60013cce074a97d7be044661b9987518">InvalidPtrMask</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="#a7c61081d6ca746abebdb07d0f0e5b88a">getRefCount</a>, <a href="#a2f51f2be1bf297c8b1e549a97013704b">poolEntryIsAlive</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr/#a296e6fc69dc1f640b1c42f19e9e9e3f8">llvm::orc::SymbolStringPtr::SymbolStringPtr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Attributes

### EmptyBitPattern {#a8ab60cb2e191e0f337c5b9c01f83df50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uintptr_t llvm::orc::SymbolStringPtrBase::EmptyBitPattern</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel protected">protected</span>
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
<div class="doxyVerbatim">=
      std::numeric_limits&lt;uintptr_t&gt;<a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">::max</a>()
      &lt;&lt; <a href="/web-llvm/docs/api/structs/llvm/pointerliketypetraits">PointerLikeTypeTraits</a>&lt;<a href="#a06b870f4121fbfb731e868be15bb29bb">PoolEntryPtr</a>&gt;::NumLowBitsAvailable
</div>
</dd>
</dl>

<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>

</div>
</div>

### InvalidPtrMask {#a60013cce074a97d7be044661b9987518}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uintptr_t llvm::orc::SymbolStringPtrBase::InvalidPtrMask</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel protected">protected</span>
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
<div class="doxyVerbatim">=
      (std::numeric_limits&lt;uintptr_t&gt;<a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">::max</a>() - 3)
      &lt;&lt; <a href="/web-llvm/docs/api/structs/llvm/pointerliketypetraits">PointerLikeTypeTraits</a>&lt;<a href="#a06b870f4121fbfb731e868be15bb29bb">PoolEntryPtr</a>&gt;::NumLowBitsAvailable
</div>
</dd>
</dl>

<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>


<p>Referenced by <a href="#a14c3bf7cb9994c35678a43283a4c2d18">isRealPoolEntry</a>.</p>

</div>
</div>

### TombstoneBitPattern {#a8c12eb3feddd7779165cfb2cd143c3b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uintptr_t llvm::orc::SymbolStringPtrBase::TombstoneBitPattern</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel protected">protected</span>
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
<div class="doxyVerbatim">=
      (std::numeric_limits&lt;uintptr_t&gt;<a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">::max</a>() - 1)
      &lt;&lt; <a href="/web-llvm/docs/api/structs/llvm/pointerliketypetraits">PointerLikeTypeTraits</a>&lt;<a href="#a06b870f4121fbfb731e868be15bb29bb">PoolEntryPtr</a>&gt;::NumLowBitsAvailable
</div>
</dd>
</dl>

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/symbolstringpool-cpp">SymbolStringPool.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
