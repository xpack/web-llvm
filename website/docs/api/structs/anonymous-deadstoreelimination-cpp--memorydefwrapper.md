---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-deadstoreelimination-cpp-/memorydefwrapper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MemoryDefWrapper` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{DeadStoreElimination.cpp}::MemoryDefWrapper { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaec6e16f4b71ac7ed349a49aebedfae">MemoryDefWrapper</a> (MemoryDef *MemDef, ArrayRef&lt; std::pair&lt; MemoryLocation, bool &gt; &gt; MemLocations)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adba1b2b1805c9f7dd7ca315e41dcdded">DefInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/memorylocationwrapper">MemoryLocationWrapper</a>, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02849cff77b89e851615cd54faa29d0d">DefinedLocations</a></td>
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


<p>Definition at line 835 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MemoryDefWrapper() {#adaec6e16f4b71ac7ed349a49aebedfae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{DeadStoreElimination.cpp}::MemoryDefWrapper::MemoryDefWrapper (<a href="/web-llvm/docs/api/classes/llvm/memorydef">MemoryDef</a> * MemDef, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a>, bool &gt; &gt; MemLocations)</td>
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



<p>Definition at line 836 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>References <a href="#a02849cff77b89e851615cd54faa29d0d">DefinedLocations</a>, <a href="#adba1b2b1805c9f7dd7ca315e41dcdded">DefInst</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryuseordef/#abe63c310031eb3c578b122f0c31739d7">llvm::MemoryUseOrDef::getMemoryInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DefinedLocations {#a02849cff77b89e851615cd54faa29d0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MemoryLocationWrapper, 1&gt; anonymous{DeadStoreElimination.cpp}::MemoryDefWrapper::DefinedLocations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 844 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a341c9b08b6693494d83c9a28aae1d3a8">anonymous{DeadStoreElimination.cpp}::DSEState::eliminateDeadDefs</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#acdd3b591101453540fdf4b9d17d49100">anonymous{DeadStoreElimination.cpp}::DSEState::eliminateDeadDefs</a> and <a href="#adaec6e16f4b71ac7ed349a49aebedfae">MemoryDefWrapper</a>.</p>

</div>
</div>

### DefInst {#adba1b2b1805c9f7dd7ca315e41dcdded}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* anonymous{DeadStoreElimination.cpp}::MemoryDefWrapper::DefInst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 843 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a341c9b08b6693494d83c9a28aae1d3a8">anonymous{DeadStoreElimination.cpp}::DSEState::eliminateDeadDefs</a> and <a href="#adaec6e16f4b71ac7ed349a49aebedfae">MemoryDefWrapper</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp">DeadStoreElimination.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
