---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/triehashindexgenerator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `TrieHashIndexGenerator` Struct

<p>The utility class that helps computing the index of the object inside trie from its hash. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::TrieHashIndexGenerator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/triehashindexgenerator-h">llvm/ADT/TrieHashIndexGenerator.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bd33f30c29b0e7770a7236748e39f51">getNumBits</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addddf0cf44f031951d26ef1f6498d7de">next</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbc9c1828c3ba51438a1fd2d14a52a2b">hint</a> (unsigned Index, unsigned Bit)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa243b9e79e08ba0917b9033159b957aa">getCollidingBits</a> (ArrayRef&lt; uint8_t &gt; CollidingBits) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa71aa120340de3173855fc9c19869e81">end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b3d7e12e65589a81b29a0fbeb5476c2">NumRootBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6412103a68c90fd47ce68c9494674119">NumSubtrieBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33664850672b797f3da588b9c02d1a80">Bytes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ccc1711881e6ab8fd991061d0904dd8">StartBit</a> = std::nullopt</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1ebaccf6864d268e8d92fe6346516e3">getIndex</a> (ArrayRef&lt; uint8_t &gt; Bytes, size_t StartBit, size_t NumBits)</td>
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

<p>The utility class that helps computing the index of the object inside trie from its hash.</p>


<p>The generator can be configured with the number of bits used for each level of trie structure with <span class="doxyComputerOutput">NumRootsBits</span> and <span class="doxyComputerOutput">NumSubtrieBits</span>. For example, try computing indexes for a 16-bit hash 0x1234 with 8-bit root and 4-bit sub-trie:</p>


<p>IndexGenerator IndexGen{8, 4, Hash}; size_t index1 = IndexGen.next(); // index 18 in root node. size_t index2 = IndexGen.next(); // index 3 in sub-trie level 1. size_t index3 = IndexGen.next(); // index 4 in sub-tire level 2.</p>


<p>This is used by different trie implementation to figure out where to insert/find the object in the data structure.</p>


<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/triehashindexgenerator-h">TrieHashIndexGenerator.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### end() {#aa71aa120340de3173855fc9c19869e81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::TrieHashIndexGenerator::end ()</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/triehashindexgenerator-h">TrieHashIndexGenerator.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/#a7184c737372d1fa8d3783e5000463f2b">llvm::ThreadSafeTrieRawHashMapBase::find</a>, <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/#aa9dbc0a952dfbed82b71fd482c4fcdd7">llvm::ThreadSafeTrieRawHashMapBase::insert</a> and <a href="#addddf0cf44f031951d26ef1f6498d7de">next</a>.</p>

</div>
</div>

### getCollidingBits() {#aa243b9e79e08ba0917b9033159b957aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::TrieHashIndexGenerator::getCollidingBits (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; CollidingBits)</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/triehashindexgenerator-h">TrieHashIndexGenerator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae1ebaccf6864d268e8d92fe6346516e3">getIndex</a>, <a href="#a6412103a68c90fd47ce68c9494674119">NumSubtrieBits</a> and <a href="#a1ccc1711881e6ab8fd991061d0904dd8">StartBit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/#aa9dbc0a952dfbed82b71fd482c4fcdd7">llvm::ThreadSafeTrieRawHashMapBase::insert</a>.</p>

</div>
</div>

### getNumBits() {#a5bd33f30c29b0e7770a7236748e39f51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::TrieHashIndexGenerator::getNumBits ()</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/triehashindexgenerator-h">TrieHashIndexGenerator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a33664850672b797f3da588b9c02d1a80">Bytes</a>, <a href="#a2b3d7e12e65589a81b29a0fbeb5476c2">NumRootBits</a>, <a href="#a6412103a68c90fd47ce68c9494674119">NumSubtrieBits</a> and <a href="#a1ccc1711881e6ab8fd991061d0904dd8">StartBit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/#aa9dbc0a952dfbed82b71fd482c4fcdd7">llvm::ThreadSafeTrieRawHashMapBase::insert</a>.</p>

</div>
</div>

### hint() {#afbc9c1828c3ba51438a1fd2d14a52a2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::TrieHashIndexGenerator::hint (unsigned Index, unsigned Bit)</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/triehashindexgenerator-h">TrieHashIndexGenerator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a33664850672b797f3da588b9c02d1a80">Bytes</a>, <a href="#a2b3d7e12e65589a81b29a0fbeb5476c2">NumRootBits</a>, <a href="#a6412103a68c90fd47ce68c9494674119">NumSubtrieBits</a> and <a href="#a1ccc1711881e6ab8fd991061d0904dd8">StartBit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/#aa9dbc0a952dfbed82b71fd482c4fcdd7">llvm::ThreadSafeTrieRawHashMapBase::insert</a>.</p>

</div>
</div>

### next() {#addddf0cf44f031951d26ef1f6498d7de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::TrieHashIndexGenerator::next ()</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/triehashindexgenerator-h">TrieHashIndexGenerator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a33664850672b797f3da588b9c02d1a80">Bytes</a>, <a href="#aa71aa120340de3173855fc9c19869e81">end</a>, <a href="#ae1ebaccf6864d268e8d92fe6346516e3">getIndex</a>, <a href="#a2b3d7e12e65589a81b29a0fbeb5476c2">NumRootBits</a>, <a href="#a6412103a68c90fd47ce68c9494674119">NumSubtrieBits</a> and <a href="#a1ccc1711881e6ab8fd991061d0904dd8">StartBit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/#a7184c737372d1fa8d3783e5000463f2b">llvm::ThreadSafeTrieRawHashMapBase::find</a> and <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/#aa9dbc0a952dfbed82b71fd482c4fcdd7">llvm::ThreadSafeTrieRawHashMapBase::insert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Bytes {#a33664850672b797f3da588b9c02d1a80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;uint8_t&gt; llvm::TrieHashIndexGenerator::Bytes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/triehashindexgenerator-h">TrieHashIndexGenerator.h</a>.</p>


<p>Referenced by <a href="#ae1ebaccf6864d268e8d92fe6346516e3">getIndex</a>, <a href="#a5bd33f30c29b0e7770a7236748e39f51">getNumBits</a>, <a href="#afbc9c1828c3ba51438a1fd2d14a52a2b">hint</a> and <a href="#addddf0cf44f031951d26ef1f6498d7de">next</a>.</p>

</div>
</div>

### NumRootBits {#a2b3d7e12e65589a81b29a0fbeb5476c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::TrieHashIndexGenerator::NumRootBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/triehashindexgenerator-h">TrieHashIndexGenerator.h</a>.</p>


<p>Referenced by <a href="#a5bd33f30c29b0e7770a7236748e39f51">getNumBits</a>, <a href="#afbc9c1828c3ba51438a1fd2d14a52a2b">hint</a> and <a href="#addddf0cf44f031951d26ef1f6498d7de">next</a>.</p>

</div>
</div>

### NumSubtrieBits {#a6412103a68c90fd47ce68c9494674119}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::TrieHashIndexGenerator::NumSubtrieBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/triehashindexgenerator-h">TrieHashIndexGenerator.h</a>.</p>


<p>Referenced by <a href="#aa243b9e79e08ba0917b9033159b957aa">getCollidingBits</a>, <a href="#a5bd33f30c29b0e7770a7236748e39f51">getNumBits</a>, <a href="#afbc9c1828c3ba51438a1fd2d14a52a2b">hint</a> and <a href="#addddf0cf44f031951d26ef1f6498d7de">next</a>.</p>

</div>
</div>

### StartBit {#a1ccc1711881e6ab8fd991061d0904dd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;size_t&gt; llvm::TrieHashIndexGenerator::StartBit = std::nullopt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/triehashindexgenerator-h">TrieHashIndexGenerator.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/#a7184c737372d1fa8d3783e5000463f2b">llvm::ThreadSafeTrieRawHashMapBase::find</a>, <a href="#aa243b9e79e08ba0917b9033159b957aa">getCollidingBits</a>, <a href="#ae1ebaccf6864d268e8d92fe6346516e3">getIndex</a>, <a href="#a5bd33f30c29b0e7770a7236748e39f51">getNumBits</a>, <a href="#afbc9c1828c3ba51438a1fd2d14a52a2b">hint</a> and <a href="#addddf0cf44f031951d26ef1f6498d7de">next</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getIndex() {#ae1ebaccf6864d268e8d92fe6346516e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::TrieHashIndexGenerator::getIndex (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Bytes, size_t StartBit, size_t NumBits)</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/triehashindexgenerator-h">TrieHashIndexGenerator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a33664850672b797f3da588b9c02d1a80">Bytes</a> and <a href="#a1ccc1711881e6ab8fd991061d0904dd8">StartBit</a>.</p>


<p>Referenced by <a href="#aa243b9e79e08ba0917b9033159b957aa">getCollidingBits</a> and <a href="#addddf0cf44f031951d26ef1f6498d7de">next</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/triehashindexgenerator-h">TrieHashIndexGenerator.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
