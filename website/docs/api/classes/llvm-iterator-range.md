---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/iterator-range
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `iterator_range` Class Template

<p>A range adaptor for a pair of iterators. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename IteratorT&gt;
class llvm::iterator_range&lt;IteratorT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/iterator-range-h">llvm/ADT/iterator_range.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#afc06af8ceb7d8d0498b712802453b38e">iterator_range</a> (Container &amp;&amp;c)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IteratorT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a5b169099ccb57e0b8fbae3fc0c57b826">iterator_range</a> (IteratorT begin_iterator, IteratorT end_iterator)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IteratorT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">IteratorT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af5a020bd9dd7bc8487dd53ce443fdd8f">begin</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IteratorT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">IteratorT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa0344673da91896d39f1b35755ee5d4e">end</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IteratorT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a06fff5bdd2bdf6d2c200e281787dc284">empty</a> () const</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IteratorT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">IteratorT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aeac0e00835772be18abf2daed29f5d1f">begin_iterator</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IteratorT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">IteratorT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a823f166661c0251fc90181a2d9fc13fa">end_iterator</a></td>
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

<p>A range adaptor for a pair of iterators.</p>


<p>This just wraps two iterators into a range-compatible interface. Nothing fancy at all.</p>


<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/iterator-range-h">iterator_range.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### iterator\_range() {#afc06af8ceb7d8d0498b712802453b38e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Container, std::enable_if_t&lt; explicitly_convertible&lt; llvm::detail::IterOfRange&lt; Container &gt;, IteratorT &gt;::value &gt; * = nullptr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::iterator_range&lt; IteratorT &gt;::iterator_range (Container &amp;&amp; c)</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/iterator-range-h">iterator_range.h</a>.</p>

</div>
</div>

### iterator\_range() {#a5b169099ccb57e0b8fbae3fc0c57b826}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IteratorT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::iterator_range&lt; IteratorT &gt;::iterator_range (IteratorT begin_iterator, IteratorT end_iterator)</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/iterator-range-h">iterator_range.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#af5a020bd9dd7bc8487dd53ce443fdd8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IteratorT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IteratorT llvm::iterator_range&lt; IteratorT &gt;::begin ()</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/iterator-range-h">iterator_range.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/ctordtorrunner/#afbff93f2fbb3f7ca330ab6a912e6aee4">llvm::orc::CtorDtorRunner::add</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5c8b942e0a2e8ebef5a138c8d3c4462c">llvm::RegisterBankInfo::applyDefaultMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a30b8af63035799a0478f6b710ce23571">llvm::DominatorTreeBase&lt; BlockT, false &gt;::findNearestCommonDominator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a4eb36b12e0366fb81a9336826c90396d">llvm::jitlink::getOrCreateLocalMachOHeader</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-debuginfosupport-cpp-/#af708da9529b70292b2712cd7ed80d14e">anonymous{DebugInfoSupport.cpp}::getSectionData</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a01b1581633bb40f86d6dc62a1c1a7f72">llvm::LazyCallGraph::RefSCC::insertIncomingRefEdge</a>, <a href="/web-llvm/docs/api/groups/llvmctarget/#ga14fa4ed2b3cf4ff0012d7598e66e89ec">LLVMGetFirstTarget</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcbranchcoalescing-cpp-/ppcbranchcoalescing/#a072a336f973a3de4daa8fe16e5b4570f">anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::mergeCandidates</a>, <a href="/web-llvm/docs/api/namespaces/llvm/at/#aea377383f26585e0da2e86da8e4dfe53">llvm::at::RAUW</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/sectionrange/#abc3e15b404a50ac250ddc31d28aaec57">llvm::jitlink::SectionRange::SectionRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a6ac87d66a2396166f8ea3457900cb0df">llvm::jitlink::splitCompactUnwindBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/branchinst/#a2f934ebbafcd336726a91d636c2cf853">llvm::sandboxir::BranchInst::successors</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/branchinst/#a611d4d9356dd291578cd369630ef3907">llvm::sandboxir::BranchInst::successors</a> and <a href="/web-llvm/docs/api/classes/llvm/jitlink/compactunwindmanager/#af022b036126d33df3324995c04b55864">llvm::jitlink::CompactUnwindManager&lt; CURecTraits &gt;::writeUnwindInfo</a>.</p>

</div>
</div>

### empty() {#a06fff5bdd2bdf6d2c200e281787dc284}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IteratorT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::iterator_range&lt; IteratorT &gt;::empty ()</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/iterator-range-h">iterator_range.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/ctordtorrunner/#afbff93f2fbb3f7ca330ab6a912e6aee4">llvm::orc::CtorDtorRunner::add</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5c8b942e0a2e8ebef5a138c8d3c4462c">llvm::RegisterBankInfo::applyDefaultMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarffile/#a66056de6e47af980edacced419d5d0b8">llvm::DwarfFile::emitUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a30b8af63035799a0478f6b710ce23571">llvm::DominatorTreeBase&lt; BlockT, false &gt;::findNearestCommonDominator</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#aceb315f70b8f69369df84d79274ef420">removeRedundantDbgInstrsUsingForwardScan</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a579e878e02e34bf9699e3d82da2bc070">removeUndefDbgAssignsFromEntryBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/jitlink/sectionrange/#abc3e15b404a50ac250ddc31d28aaec57">llvm::jitlink::SectionRange::SectionRange</a>.</p>

</div>
</div>

### end() {#aa0344673da91896d39f1b35755ee5d4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IteratorT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IteratorT llvm::iterator_range&lt; IteratorT &gt;::end ()</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/iterator-range-h">iterator_range.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a8d0c6052d21638f0a385e226db3bd92f">collectAllHeaderMasks</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-debuginfosupport-cpp-/#af708da9529b70292b2712cd7ed80d14e">anonymous{DebugInfoSupport.cpp}::getSectionData</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a01b1581633bb40f86d6dc62a1c1a7f72">llvm::LazyCallGraph::RefSCC::insertIncomingRefEdge</a>, <a href="/web-llvm/docs/api/groups/llvmctarget/#ga57bc27c27706c0ee7a36152ff7f65a56">LLVMGetTargetFromName</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcbranchcoalescing-cpp-/ppcbranchcoalescing/#a072a336f973a3de4daa8fe16e5b4570f">anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::mergeCandidates</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a00afc372e6cccfa7fd2904fde074a757">PerformExtractEltToVMOVRRD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/at/#aea377383f26585e0da2e86da8e4dfe53">llvm::at::RAUW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a6ac87d66a2396166f8ea3457900cb0df">llvm::jitlink::splitCompactUnwindBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/branchinst/#a2f934ebbafcd336726a91d636c2cf853">llvm::sandboxir::BranchInst::successors</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/branchinst/#a611d4d9356dd291578cd369630ef3907">llvm::sandboxir::BranchInst::successors</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### begin\_iterator {#aeac0e00835772be18abf2daed29f5d1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IteratorT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IteratorT llvm::iterator_range&lt; IteratorT &gt;::begin_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/iterator-range-h">iterator_range.h</a>.</p>

</div>
</div>

### end\_iterator {#a823f166661c0251fc90181a2d9fc13fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IteratorT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IteratorT llvm::iterator_range&lt; IteratorT &gt;::end_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/iterator-range-h">iterator_range.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/iterator-range-h">iterator_range.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
