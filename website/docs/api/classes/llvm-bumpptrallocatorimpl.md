---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/bumpptrallocatorimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BumpPtrAllocatorImpl` Class Template Reference

<p>Allocate memory in an ever growing pool, as if by bump-pointer. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename AllocatorT = MallocAllocator, size_t SlabSize = 4096, size_t SizeThreshold = SlabSize, size_t GrowthDelay = 128&gt;
class llvm::BumpPtrAllocatorImpl&lt;AllocatorT, SlabSize, SizeThreshold, GrowthDelay&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">llvm/Support/Allocator.h</a>"
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/allocatorbase">AllocatorBase&lt;DerivedT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CRTP base class providing obvious overloads for the core <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/allocatorbase/#a3bfc5b8ce6ce70645e6f4662af9eef50">Allocate()</a></span> methods of LLVM-style allocators. <a href="/web-llvm/docs/api/classes/llvm/allocatorbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/allocatorholder">AllocatorHolder&lt;Alloc&gt;</a></td>
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/allocatorlist">AllocatorList&lt;T, AllocatorT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A linked-list with a custom, local allocator. <a href="/web-llvm/docs/api/classes/llvm/allocatorlist/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/allocatorholder">AllocatorHolder&lt;Alloc&gt;</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a09cd650b95550c64b9062492b6e82bac">AllocTy</a> = <a href="/web-llvm/docs/api/classes/llvm/detail/allocatorholder">detail::AllocatorHolder</a>&lt; AllocatorT &gt;</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8c5ed7ab075c43b64daa213617d97dc9">SpecificBumpPtrAllocator</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a5c9184057954831f8428e7a7393947bb">BumpPtrAllocatorImpl</a> ()=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aa97f1b8aea425f7d0284ae828a286e59">BumpPtrAllocatorImpl</a> (T &amp;&amp;Allocator)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a60efd3795be57cbe166e03fb99784033">BumpPtrAllocatorImpl</a> (BumpPtrAllocatorImpl &amp;&amp;Old)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#acd85cdb8917cb6e029f9466faa6bef40">~BumpPtrAllocatorImpl</a> ()</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bumpptrallocatorimpl">BumpPtrAllocatorImpl</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac54189a6911cb2907ab72441831275b7">operator=</a> (BumpPtrAllocatorImpl &amp;&amp;RHS)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a977c94ac0ef5e305e5cf40726351d88a">Reset</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deallocate all but the current slab and reset the current pointer to the beginning of it, freeing all memory allocated so far. <a href="#a977c94ac0ef5e305e5cf40726351d88a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#acbae7c06e77fa64145cca176963b6863">LLVM_ATTRIBUTE_RETURNS_NONNULL</a> void *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4054c3eefe873caf49c2290808d409ac">Allocate</a> (size_t Size, Align Alignment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate space at the specified alignment. <a href="#a4054c3eefe873caf49c2290808d409ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#acbae7c06e77fa64145cca176963b6863">LLVM_ATTRIBUTE_RETURNS_NONNULL</a> <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ac6a5e0eb6a9944baf6ba14b640eab6e1">LLVM_ATTRIBUTE_NOINLINE</a> void *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aef3aaf3bf7c0ec3ad8ad4941b14bb846">AllocateSlow</a> (size_t Size, size_t SizeToAllocate, Align Alignment)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#acbae7c06e77fa64145cca176963b6863">LLVM_ATTRIBUTE_RETURNS_NONNULL</a> void *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2adb37af1eac8aa7fffd51ee4617e972">Allocate</a> (size_t Size, size_t Alignment)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa306ee4f02f1a5e8022576b65a7398af">Deallocate</a> (const void *Ptr, size_t Size, size_t)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a025ef2135bf2cb796d8868d0df71c081">GetNumSlabs</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a37fb633e742bf184c02ea432d3b377f0">identifyObject</a> (const void *Ptr) -&gt; std::optional&lt; int64_t &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae01786d2b3278d6cced61f9e1621ed9b">identifyKnownObject</a> (const void *Ptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A wrapper around identifyObject that additionally asserts that the object is indeed within the allocator. <a href="#ae01786d2b3278d6cced61f9e1621ed9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7473a4e7b2a9f87d91432add2af05cee">identifyKnownAlignedObject</a> (const void *Ptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A wrapper around identifyKnownObject. <a href="#a7473a4e7b2a9f87d91432add2af05cee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab660226d33c184962339e80a7e7d4a6e">getTotalMemory</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a81f8c869eeebd173c53552bf1a6f6e26">getBytesAllocated</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a372470a41c7178bb2a5b67d022de2b3b">setRedZoneSize</a> (size_t NewSize)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0bbab0d4a967c1e3280c5aa1c9856f6a">PrintStats</a> () const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aff57d74786db8f014b40cbd5df09036c">StartNewSlab</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a new slab and move the bump pointers over into the new slab, modifying CurPtr and End. <a href="#aff57d74786db8f014b40cbd5df09036c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a37e9737e1cdc5072290229439a6d5fee">DeallocateSlabs</a> (SmallVectorImpl&lt; void * &gt;::iterator I, SmallVectorImpl&lt; void * &gt;::iterator E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deallocate a sequence of slabs. <a href="#a37e9737e1cdc5072290229439a6d5fee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a96ac7fb36dc13e72af11c77d4d7b8975">DeallocateCustomSizedSlabs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deallocate all memory for custom sized slabs. <a href="#a96ac7fb36dc13e72af11c77d4d7b8975">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac1e513b44d8e4d928007f58e0d78a31c">CurPtr</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The current pointer into the current slab. <a href="#ac1e513b44d8e4d928007f58e0d78a31c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9738c4d4f84c1f57e2c7b1c615fc6465">End</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The end of the current slab. <a href="#a9738c4d4f84c1f57e2c7b1c615fc6465">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; void *, 4 &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa46e60cf122c4fb4e6b32aedb3d39568">Slabs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The slabs allocated so far. <a href="#aa46e60cf122c4fb4e6b32aedb3d39568">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; void *, size_t &gt;, 0 &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1fcf06e30780f6ebf5b423e5de261287">CustomSizedSlabs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Custom-sized slabs allocated for too-large allocation requests. <a href="#a1fcf06e30780f6ebf5b423e5de261287">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a083e7347626273c8dcd7f564a2724067">BytesAllocated</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>How many bytes we've allocated. <a href="#a083e7347626273c8dcd7f564a2724067">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad5e779fef80d14de45c539b3ee18a98b">RedZoneSize</a> = 1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of bytes to put between allocations when running under a sanitizer. <a href="#ad5e779fef80d14de45c539b3ee18a98b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae4259d33a1748583e0e087d519417c2b">computeSlabSize</a> (unsigned SlabIdx)</td>
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

<p>Allocate memory in an ever growing pool, as if by bump-pointer.</p>


<p>This isn't strictly a bump-pointer allocator as it uses backing slabs of memory rather than relying on a boundless contiguous heap. However, it has bump-pointer semantics in that it is a monotonically growing pool of memory where every allocation is found by merely allocating the next N bytes in the slab, or the next N bytes in the next slab.</p>


<p>Note that this also has a threshold for forcing allocations above a certain size into their own slab.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/bumpptrallocatorimpl">BumpPtrAllocatorImpl</a> template defaults to using a <a href="/web-llvm/docs/api/classes/llvm/mallocallocator">MallocAllocator</a> object, which wraps malloc, to allocate memory, but it can be changed to use a custom allocator.</p>


<p>The GrowthDelay specifies after how many allocated slabs the allocator increases the size of the slabs.</p>


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### AllocTy {#a09cd650b95550c64b9062492b6e82bac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AllocatorT = MallocAllocator, size_t SlabSize = 4096, size_t SizeThreshold = SlabSize, size_t GrowthDelay = 128&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::BumpPtrAllocatorImpl&lt; AllocatorT, SlabSize, SizeThreshold, GrowthDelay &gt;::AllocTy =  detail::AllocatorHolder&lt;AllocatorT&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### SpecificBumpPtrAllocator {#a8c5ed7ab075c43b64daa213617d97dc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### BumpPtrAllocatorImpl() {#a5c9184057954831f8428e7a7393947bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AllocatorT = MallocAllocator, size_t SlabSize = 4096, size_t SizeThreshold = SlabSize, size_t GrowthDelay = 128&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BumpPtrAllocatorImpl&lt; AllocatorT, SlabSize, SizeThreshold, GrowthDelay &gt;::BumpPtrAllocatorImpl ()</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a>.</p>

</div>
</div>

### BumpPtrAllocatorImpl() {#aa97f1b8aea425f7d0284ae828a286e59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BumpPtrAllocatorImpl&lt; AllocatorT, SlabSize, SizeThreshold, GrowthDelay &gt;::BumpPtrAllocatorImpl (T &amp;&amp; Allocator)</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a>.</p>

</div>
</div>

### BumpPtrAllocatorImpl() {#a60efd3795be57cbe166e03fb99784033}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AllocatorT = MallocAllocator, size_t SlabSize = 4096, size_t SizeThreshold = SlabSize, size_t GrowthDelay = 128&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BumpPtrAllocatorImpl&lt; AllocatorT, SlabSize, SizeThreshold, GrowthDelay &gt;::BumpPtrAllocatorImpl (<a href="/web-llvm/docs/api/classes/llvm/bumpptrallocatorimpl">BumpPtrAllocatorImpl</a> &amp;&amp; Old)</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~BumpPtrAllocatorImpl() {#acd85cdb8917cb6e029f9466faa6bef40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AllocatorT = MallocAllocator, size_t SlabSize = 4096, size_t SizeThreshold = SlabSize, size_t GrowthDelay = 128&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BumpPtrAllocatorImpl&lt; AllocatorT, SlabSize, SizeThreshold, GrowthDelay &gt;::~BumpPtrAllocatorImpl ()</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#ac54189a6911cb2907ab72441831275b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AllocatorT = MallocAllocator, size_t SlabSize = 4096, size_t SizeThreshold = SlabSize, size_t GrowthDelay = 128&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocatorImpl &amp; llvm::BumpPtrAllocatorImpl&lt; AllocatorT, SlabSize, SizeThreshold, GrowthDelay &gt;::operator= (<a href="/web-llvm/docs/api/classes/llvm/bumpptrallocatorimpl">BumpPtrAllocatorImpl</a> &amp;&amp; RHS)</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### Allocate() {#a4054c3eefe873caf49c2290808d409ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AllocatorT = MallocAllocator, size_t SlabSize = 4096, size_t SizeThreshold = SlabSize, size_t GrowthDelay = 128&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_RETURNS_NONNULL void * llvm::BumpPtrAllocatorImpl&lt; AllocatorT, SlabSize, SizeThreshold, GrowthDelay &gt;::Allocate (size_t Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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

<p>Allocate space at the specified alignment.</p>

<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a>.</p>


<p>Referenced by <a href="#a2adb37af1eac8aa7fffd51ee4617e972">llvm::BumpPtrAllocatorImpl&lt; MallocAllocator, 65536 &gt;::Allocate</a>, <a href="/web-llvm/docs/api/classes/llvm/bitsinit/#ad964d60acd20953d20b1e673a397d5e2">llvm::BitsInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/condopinit/#a181dad1cdd60a83a181108d90acd4738">llvm::CondOpInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/daginit/#a8068bfe8ffd6450e61e72665e6887abc">llvm::DagInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/listinit/#a43379a4cffc2ed53c7bf95fe72e60454">llvm::ListInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/recordrecty/#af99419a971a2b329732cb2a89e6a004b">llvm::RecordRecTy::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vardefinit/#a79b06bf58989430bbbad88e098ce32b6">llvm::VarDefInit::get</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/appendingtypetablebuilder-cpp/#aa69f6dc0f79ddc38844c8585a439c2b1">stabilize</a>.</p>

</div>
</div>

### Allocate() {#a2adb37af1eac8aa7fffd51ee4617e972}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AllocatorT = MallocAllocator, size_t SlabSize = 4096, size_t SizeThreshold = SlabSize, size_t GrowthDelay = 128&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_RETURNS_NONNULL void * llvm::BumpPtrAllocatorImpl&lt; AllocatorT, SlabSize, SizeThreshold, GrowthDelay &gt;::Allocate (size_t Size, size_t Alignment)</td>
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



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a>.</p>

</div>
</div>

### AllocateSlow() {#aef3aaf3bf7c0ec3ad8ad4941b14bb846}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AllocatorT = MallocAllocator, size_t SlabSize = 4096, size_t SizeThreshold = SlabSize, size_t GrowthDelay = 128&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_RETURNS_NONNULL LLVM_ATTRIBUTE_NOINLINE void * llvm::BumpPtrAllocatorImpl&lt; AllocatorT, SlabSize, SizeThreshold, GrowthDelay &gt;::AllocateSlow (size_t Size, size_t SizeToAllocate, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a>.</p>


<p>Referenced by <a href="#a4054c3eefe873caf49c2290808d409ac">llvm::BumpPtrAllocatorImpl&lt; MallocAllocator, 65536 &gt;::Allocate</a>.</p>

</div>
</div>

### Deallocate() {#aa306ee4f02f1a5e8022576b65a7398af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AllocatorT = MallocAllocator, size_t SlabSize = 4096, size_t SizeThreshold = SlabSize, size_t GrowthDelay = 128&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BumpPtrAllocatorImpl&lt; AllocatorT, SlabSize, SizeThreshold, GrowthDelay &gt;::Deallocate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * Ptr, size_t Size, size_t)</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a>.</p>

</div>
</div>

### getBytesAllocated() {#a81f8c869eeebd173c53552bf1a6f6e26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AllocatorT = MallocAllocator, size_t SlabSize = 4096, size_t SizeThreshold = SlabSize, size_t GrowthDelay = 128&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::BumpPtrAllocatorImpl&lt; AllocatorT, SlabSize, SizeThreshold, GrowthDelay &gt;::getBytesAllocated ()</td>
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



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a>.</p>

</div>
</div>

### GetNumSlabs() {#a025ef2135bf2cb796d8868d0df71c081}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AllocatorT = MallocAllocator, size_t SlabSize = 4096, size_t SizeThreshold = SlabSize, size_t GrowthDelay = 128&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::BumpPtrAllocatorImpl&lt; AllocatorT, SlabSize, SizeThreshold, GrowthDelay &gt;::GetNumSlabs ()</td>
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



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a>.</p>

</div>
</div>

### getTotalMemory() {#ab660226d33c184962339e80a7e7d4a6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AllocatorT = MallocAllocator, size_t SlabSize = 4096, size_t SizeThreshold = SlabSize, size_t GrowthDelay = 128&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::BumpPtrAllocatorImpl&lt; AllocatorT, SlabSize, SizeThreshold, GrowthDelay &gt;::getTotalMemory ()</td>
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



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a>.</p>

</div>
</div>

### identifyKnownAlignedObject() {#a7473a4e7b2a9f87d91432add2af05cee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::BumpPtrAllocatorImpl&lt; AllocatorT, SlabSize, SizeThreshold, GrowthDelay &gt;::identifyKnownAlignedObject (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * Ptr)</td>
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

<p>A wrapper around identifyKnownObject.</p>


<p>Accepts type information about the object and produces a smaller identifier by relying on the alignment information. Note that sub-classes may have different alignment, so the most base class should be passed as template parameter in order to obtain correct results. For that reason automatic template parameter deduction is disabled.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An index uniquely and reproducibly identifying an input pointer <span class="doxyComputerOutput">Ptr</span> in the given allocator. This identifier is different from the ones produced by identifyObject and identifyAlignedObject.</p></dd>
</dl>


<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a>.</p>

</div>
</div>

### identifyKnownObject() {#ae01786d2b3278d6cced61f9e1621ed9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AllocatorT = MallocAllocator, size_t SlabSize = 4096, size_t SizeThreshold = SlabSize, size_t GrowthDelay = 128&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::BumpPtrAllocatorImpl&lt; AllocatorT, SlabSize, SizeThreshold, GrowthDelay &gt;::identifyKnownObject (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * Ptr)</td>
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

<p>A wrapper around identifyObject that additionally asserts that the object is indeed within the allocator.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An index uniquely and reproducibly identifying an input pointer <span class="doxyComputerOutput">Ptr</span> in the given allocator.</p></dd>
</dl>


<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a>.</p>


<p>Referenced by <a href="#a7473a4e7b2a9f87d91432add2af05cee">llvm::BumpPtrAllocatorImpl&lt; MallocAllocator, 65536 &gt;::identifyKnownAlignedObject</a>.</p>

</div>
</div>

### identifyObject() {#a37fb633e742bf184c02ea432d3b377f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AllocatorT = MallocAllocator, size_t SlabSize = 4096, size_t SizeThreshold = SlabSize, size_t GrowthDelay = 128&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; int64_t &gt; llvm::BumpPtrAllocatorImpl&lt; AllocatorT, SlabSize, SizeThreshold, GrowthDelay &gt;::identifyObject (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * Ptr)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An index uniquely and reproducibly identifying an input pointer <span class="doxyComputerOutput">Ptr</span> in the given allocator. The returned value is negative iff the object is inside a custom-size slab. Returns an empty optional if the pointer is not found in the allocator.</p></dd>
</dl>


<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a>.</p>


<p>Referenced by <a href="#ae01786d2b3278d6cced61f9e1621ed9b">llvm::BumpPtrAllocatorImpl&lt; MallocAllocator, 65536 &gt;::identifyKnownObject</a>.</p>

</div>
</div>

### PrintStats() {#a0bbab0d4a967c1e3280c5aa1c9856f6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AllocatorT = MallocAllocator, size_t SlabSize = 4096, size_t SizeThreshold = SlabSize, size_t GrowthDelay = 128&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BumpPtrAllocatorImpl&lt; AllocatorT, SlabSize, SizeThreshold, GrowthDelay &gt;::PrintStats ()</td>
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



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a>.</p>

</div>
</div>

### Reset() {#a977c94ac0ef5e305e5cf40726351d88a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AllocatorT = MallocAllocator, size_t SlabSize = 4096, size_t SizeThreshold = SlabSize, size_t GrowthDelay = 128&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BumpPtrAllocatorImpl&lt; AllocatorT, SlabSize, SizeThreshold, GrowthDelay &gt;::Reset ()</td>
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

<p>Deallocate all but the current slab and reset the current pointer to the beginning of it, freeing all memory allocated so far.</p>

<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a>.</p>

</div>
</div>

### setRedZoneSize() {#a372470a41c7178bb2a5b67d022de2b3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AllocatorT = MallocAllocator, size_t SlabSize = 4096, size_t SizeThreshold = SlabSize, size_t GrowthDelay = 128&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BumpPtrAllocatorImpl&lt; AllocatorT, SlabSize, SizeThreshold, GrowthDelay &gt;::setRedZoneSize (size_t NewSize)</td>
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



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### DeallocateCustomSizedSlabs() {#a96ac7fb36dc13e72af11c77d4d7b8975}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AllocatorT = MallocAllocator, size_t SlabSize = 4096, size_t SizeThreshold = SlabSize, size_t GrowthDelay = 128&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BumpPtrAllocatorImpl&lt; AllocatorT, SlabSize, SizeThreshold, GrowthDelay &gt;::DeallocateCustomSizedSlabs ()</td>
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

<p>Deallocate all memory for custom sized slabs.</p>

<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a>.</p>

</div>
</div>

### DeallocateSlabs() {#a37e9737e1cdc5072290229439a6d5fee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AllocatorT = MallocAllocator, size_t SlabSize = 4096, size_t SizeThreshold = SlabSize, size_t GrowthDelay = 128&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BumpPtrAllocatorImpl&lt; AllocatorT, SlabSize, SizeThreshold, GrowthDelay &gt;::DeallocateSlabs (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; void * &gt;::iterator I, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; void * &gt;::iterator E)</td>
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

<p>Deallocate a sequence of slabs.</p>

<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a>.</p>

</div>
</div>

### StartNewSlab() {#aff57d74786db8f014b40cbd5df09036c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AllocatorT = MallocAllocator, size_t SlabSize = 4096, size_t SizeThreshold = SlabSize, size_t GrowthDelay = 128&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BumpPtrAllocatorImpl&lt; AllocatorT, SlabSize, SizeThreshold, GrowthDelay &gt;::StartNewSlab ()</td>
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

<p>Allocate a new slab and move the bump pointers over into the new slab, modifying CurPtr and End.</p>

<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BytesAllocated {#a083e7347626273c8dcd7f564a2724067}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AllocatorT = MallocAllocator, size_t SlabSize = 4096, size_t SizeThreshold = SlabSize, size_t GrowthDelay = 128&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::BumpPtrAllocatorImpl&lt; AllocatorT, SlabSize, SizeThreshold, GrowthDelay &gt;::BytesAllocated = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>How many bytes we've allocated.</p>


<p>Used so that we can compute how much space was wasted.</p>


<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a>.</p>

</div>
</div>

### CurPtr {#ac1e513b44d8e4d928007f58e0d78a31c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AllocatorT = MallocAllocator, size_t SlabSize = 4096, size_t SizeThreshold = SlabSize, size_t GrowthDelay = 128&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char* llvm::BumpPtrAllocatorImpl&lt; AllocatorT, SlabSize, SizeThreshold, GrowthDelay &gt;::CurPtr = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The current pointer into the current slab.</p>


<p>This points to the next free byte in the slab.</p>


<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a>.</p>

</div>
</div>

### CustomSizedSlabs {#a1fcf06e30780f6ebf5b423e5de261287}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AllocatorT = MallocAllocator, size_t SlabSize = 4096, size_t SizeThreshold = SlabSize, size_t GrowthDelay = 128&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::pair&lt;void *, size_t&gt;, 0&gt; llvm::BumpPtrAllocatorImpl&lt; AllocatorT, SlabSize, SizeThreshold, GrowthDelay &gt;::CustomSizedSlabs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Custom-sized slabs allocated for too-large allocation requests.</p>

<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a>.</p>

</div>
</div>

### End {#a9738c4d4f84c1f57e2c7b1c615fc6465}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AllocatorT = MallocAllocator, size_t SlabSize = 4096, size_t SizeThreshold = SlabSize, size_t GrowthDelay = 128&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char* llvm::BumpPtrAllocatorImpl&lt; AllocatorT, SlabSize, SizeThreshold, GrowthDelay &gt;::End = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The end of the current slab.</p>

<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a>.</p>

</div>
</div>

### RedZoneSize {#ad5e779fef80d14de45c539b3ee18a98b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AllocatorT = MallocAllocator, size_t SlabSize = 4096, size_t SizeThreshold = SlabSize, size_t GrowthDelay = 128&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::BumpPtrAllocatorImpl&lt; AllocatorT, SlabSize, SizeThreshold, GrowthDelay &gt;::RedZoneSize = 1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of bytes to put between allocations when running under a sanitizer.</p>

<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a>.</p>

</div>
</div>

### Slabs {#aa46e60cf122c4fb4e6b32aedb3d39568}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AllocatorT = MallocAllocator, size_t SlabSize = 4096, size_t SizeThreshold = SlabSize, size_t GrowthDelay = 128&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;void *, 4&gt; llvm::BumpPtrAllocatorImpl&lt; AllocatorT, SlabSize, SizeThreshold, GrowthDelay &gt;::Slabs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The slabs allocated so far.</p>

<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### computeSlabSize() {#ae4259d33a1748583e0e087d519417c2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AllocatorT = MallocAllocator, size_t SlabSize = 4096, size_t SizeThreshold = SlabSize, size_t GrowthDelay = 128&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::BumpPtrAllocatorImpl&lt; AllocatorT, SlabSize, SizeThreshold, GrowthDelay &gt;::computeSlabSize (unsigned SlabIdx)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">Allocator.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
