---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sandboxir/seedcollector
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SeedCollector` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::sandboxir::SeedCollector { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">llvm/Transforms/Vectorize/SandboxVectorizer/SeedCollector.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a330c68039614e8c42c1e1ccdf3cd10a5">SeedCollector</a> (BasicBlock *BB, ScalarEvolution &amp;SE)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6201643830489323548830a4cc800e37">~SeedCollector</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/seedcontainer/iterator">SeedContainer::iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ea93654ec8c65c6c1fb615d8923a560">getStoreSeeds</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/seedcontainer/iterator">SeedContainer::iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01fd2151991c3ec033bd1aeaabfdc014">getLoadSeeds</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f1b62cc06c2374b3a575a10a1ba4ca4">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd60efe9a807a336d72b4cb3206b655f">dump</a> () const</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acecb68042dc471813eec25efc65dfe48">totalNumSeedGroups</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns the number of <a href="/web-llvm/docs/api/classes/llvm/sandboxir/seedbundle">SeedBundle</a> groups for all seed types. <a href="#acecb68042dc471813eec25efc65dfe48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/seedcontainer">SeedContainer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e930c82d0b2a4cc08f06de0f82731d3">StoreSeeds</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/seedcontainer">SeedContainer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb30e1854ee38bb065adee4b6ea3867e">LoadSeeds</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3400b1743304b9a073a0634b3238e02">Ctx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/context/callbackid">Context::CallbackID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40b9fdb74cd2958b578e7ae1a7f82fd6">EraseCallbackID</a></td>
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


<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SeedCollector() {#a330c68039614e8c42c1e1ccdf3cd10a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::SeedCollector::SeedCollector (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>, definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/seedcollector-cpp">SeedCollector.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#af1b11c35cb962ef32e3423fe567b4495">llvm::sandboxir::CollectSeeds</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#a3019002eb2b04987eae4158ac938245e">llvm::sandboxir::isValidMemSeed</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/seedcollector-cpp/#ae6ccfae54f1893444a1f212f837f6884">LoadSeedsDef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#a89201844d1c5cc37bbab4c1179f18b9e">llvm::sandboxir::SeedGroupsLimit</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/seedcollector-cpp/#a325636d60b5bbf6f40ac646f0fd82db8">StoreSeedsDef</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SeedCollector() {#a6201643830489323548830a4cc800e37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::SeedCollector::~SeedCollector ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>, definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/seedcollector-cpp">SeedCollector.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#afd60efe9a807a336d72b4cb3206b655f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::SeedCollector::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>, definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/seedcollector-cpp">SeedCollector.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="#a9f1b62cc06c2374b3a575a10a1ba4ca4">print</a>.</p>

</div>
</div>

### getLoadSeeds() {#a01fd2151991c3ec033bd1aeaabfdc014}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; SeedContainer::iterator &gt; llvm::sandboxir::SeedCollector::getLoadSeeds ()</td>
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



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>

</div>
</div>

### getStoreSeeds() {#a8ea93654ec8c65c6c1fb615d8923a560}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; SeedContainer::iterator &gt; llvm::sandboxir::SeedCollector::getStoreSeeds ()</td>
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



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>

</div>
</div>

### print() {#a9f1b62cc06c2374b3a575a10a1ba4ca4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::SeedCollector::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>, definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/seedcollector-cpp">SeedCollector.cpp</a>.</p>


<p>Referenced by <a href="#afd60efe9a807a336d72b4cb3206b655f">dump</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### totalNumSeedGroups() {#acecb68042dc471813eec25efc65dfe48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sandboxir::SeedCollector::totalNumSeedGroups ()</td>
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

<p>\Returns the number of <a href="/web-llvm/docs/api/classes/llvm/sandboxir/seedbundle">SeedBundle</a> groups for all seed types.</p>


<p>This is to be used for limiting compilation time.</p>


<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Ctx {#ad3400b1743304b9a073a0634b3238e02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Context&amp; llvm::sandboxir::SeedCollector::Ctx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>

</div>
</div>

### EraseCallbackID {#a40b9fdb74cd2958b578e7ae1a7f82fd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Context::CallbackID llvm::sandboxir::SeedCollector::EraseCallbackID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>

</div>
</div>

### LoadSeeds {#abb30e1854ee38bb065adee4b6ea3867e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SeedContainer llvm::sandboxir::SeedCollector::LoadSeeds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>

</div>
</div>

### StoreSeeds {#a3e930c82d0b2a4cc08f06de0f82731d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SeedContainer llvm::sandboxir::SeedCollector::StoreSeeds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/seedcollector-h">SeedCollector.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/seedcollector-cpp">SeedCollector.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
