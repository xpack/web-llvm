---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/allocatorbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AllocatorBase` Class Template Reference

<p>CRTP base class providing obvious overloads for the core <span class="doxyComputerOutput"><a href="#a3bfc5b8ce6ce70645e6f4662af9eef50">Allocate()</a></span> methods of LLVM-style allocators. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename DerivedT&gt;
class llvm::AllocatorBase&lt;DerivedT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocatorbase-h">llvm/Support/AllocatorBase.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bumpptrallocatorimpl">BumpPtrAllocatorImpl&lt;AllocatorT, SlabSize, SizeThreshold, GrowthDelay&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate memory in an ever growing pool, as if by bump-pointer. <a href="/web-llvm/docs/api/classes/llvm/bumpptrallocatorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parallel/perthreadallocator">PerThreadAllocator&lt;AllocatorTy&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/parallel/perthreadallocator">PerThreadAllocator</a> is used in conjunction with ThreadPoolExecutor to allow per-thread allocations. <a href="/web-llvm/docs/api/classes/llvm/parallel/perthreadallocator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3bfc5b8ce6ce70645e6f4662af9eef50">Allocate</a> (size_t Size, size_t Alignment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate <em>Size</em> bytes of <em>Alignment</em> aligned memory. <a href="#a3bfc5b8ce6ce70645e6f4662af9eef50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6cbd5349a066f9e36c0386d2bbcb1fa6">Deallocate</a> (const void *Ptr, size_t Size, size_t Alignment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deallocate <em>Ptr</em> to <em>Size</em> bytes of memory allocated by this allocator. <a href="#a6cbd5349a066f9e36c0386d2bbcb1fa6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4fc98cdad23c7a21cad8b05412cd3252">Allocate</a> (size_t Num=1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate space for a sequence of objects without constructing them. <a href="#a4fc98cdad23c7a21cad8b05412cd3252">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7ecd03ef46d3780034e848fbe26ae78f">Deallocate</a> (T *Ptr, size_t Num=1) -&gt; std::enable_if_t&lt;!std::is_same_v&lt; std::remove_cv_t&lt; T &gt;, void &gt;, void &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deallocate space for a sequence of objects without constructing them. <a href="#a7ecd03ef46d3780034e848fbe26ae78f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>CRTP base class providing obvious overloads for the core <span class="doxyComputerOutput"><a href="#a3bfc5b8ce6ce70645e6f4662af9eef50">Allocate()</a></span> methods of LLVM-style allocators.</p>


<p>This base class both documents the full public interface exposed by all LLVM-style allocators, and redirects all of the overloads to a single core set of methods which the derived class must define.</p>


<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocatorbase-h">AllocatorBase.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### Allocate() {#a3bfc5b8ce6ce70645e6f4662af9eef50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::AllocatorBase&lt; DerivedT &gt;::Allocate (size_t Size, size_t Alignment)</td>
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

<p>Allocate <em>Size</em> bytes of <em>Alignment</em> aligned memory.</p>


<p>This method must be implemented by <span class="doxyComputerOutput">DerivedT</span>.</p>


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocatorbase-h">AllocatorBase.h</a>.</p>


<p>References <a href="#a3bfc5b8ce6ce70645e6f4662af9eef50">llvm::AllocatorBase&lt; DerivedT &gt;::Allocate</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a4fc98cdad23c7a21cad8b05412cd3252">llvm::AllocatorBase&lt; DerivedT &gt;::Allocate</a> and <a href="#a3bfc5b8ce6ce70645e6f4662af9eef50">llvm::AllocatorBase&lt; DerivedT &gt;::Allocate</a>.</p>

</div>
</div>

### Allocate() {#a4fc98cdad23c7a21cad8b05412cd3252}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T * llvm::AllocatorBase&lt; DerivedT &gt;::Allocate (size_t Num=1)</td>
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

<p>Allocate space for a sequence of objects without constructing them.</p>

<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocatorbase-h">AllocatorBase.h</a>.</p>


<p>References <a href="#a3bfc5b8ce6ce70645e6f4662af9eef50">llvm::AllocatorBase&lt; DerivedT &gt;::Allocate</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### Deallocate() {#a6cbd5349a066f9e36c0386d2bbcb1fa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AllocatorBase&lt; DerivedT &gt;::Deallocate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * Ptr, size_t Size, size_t Alignment)</td>
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

<p>Deallocate <em>Ptr</em> to <em>Size</em> bytes of memory allocated by this allocator.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocatorbase-h">AllocatorBase.h</a>.</p>


<p>References <a href="#a6cbd5349a066f9e36c0386d2bbcb1fa6">llvm::AllocatorBase&lt; DerivedT &gt;::Deallocate</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a6cbd5349a066f9e36c0386d2bbcb1fa6">llvm::AllocatorBase&lt; DerivedT &gt;::Deallocate</a> and <a href="#a7ecd03ef46d3780034e848fbe26ae78f">llvm::AllocatorBase&lt; DerivedT &gt;::Deallocate</a>.</p>

</div>
</div>

### Deallocate() {#a7ecd03ef46d3780034e848fbe26ae78f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt;!std::is_same_v&lt; std::remove_cv_t&lt; T &gt;, void &gt;, void &gt; llvm::AllocatorBase&lt; DerivedT &gt;::Deallocate (T * Ptr, size_t Num=1)</td>
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

<p>Deallocate space for a sequence of objects without constructing them.</p>

<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocatorbase-h">AllocatorBase.h</a>.</p>


<p>References <a href="#a6cbd5349a066f9e36c0386d2bbcb1fa6">llvm::AllocatorBase&lt; DerivedT &gt;::Deallocate</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocatorbase-h">AllocatorBase.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
