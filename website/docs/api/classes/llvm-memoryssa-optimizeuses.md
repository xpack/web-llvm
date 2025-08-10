---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/memoryssa/optimizeuses
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `OptimizeUses` Class

<p>This class is a batch walker of all <a href="/web-llvm/docs/api/classes/llvm/memoryuse">MemoryUse</a>'s in the program, and points their defining access at the thing that actually clobbers them. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MemorySSA::OptimizeUses { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7fb8e8bcc5cf17ad15225ab3cb9e401">OptimizeUses</a> (MemorySSA *MSSA, CachingWalker *Walker, BatchAAResults *BAA, DominatorTree *DT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a195658a43b30378309ff4e62455dc137">optimizeUses</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optimize uses to point to their actual clobbering definitions. <a href="#a195658a43b30378309ff4e62455dc137">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb4afff4441502cbce3571ec00d0ada3">optimizeUsesInBlock</a> (const BasicBlock *, unsigned long &amp;, unsigned long &amp;, SmallVectorImpl&lt; MemoryAccess * &gt; &amp;, DenseMap&lt; MemoryLocOrCall, MemlocStackInfo &gt; &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optimize the uses in a given block This is basically the SSA renaming algorithm, with one caveat: We are able to use a single stack for all MemoryUses. <a href="#acb4afff4441502cbce3571ec00d0ada3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47d5cc88db69afde5daaa2773e47a9fe">MSSA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryssa/cachingwalker">CachingWalker</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab52d2db73fe03289efbca3f0414b8bda">Walker</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78bb9b4cc2902c24215ca19f8e7f7a28">AA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6778484e11a1d033766e2638b9c29644">DT</a></td>
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

<p>This class is a batch walker of all <a href="/web-llvm/docs/api/classes/llvm/memoryuse">MemoryUse</a>'s in the program, and points their defining access at the thing that actually clobbers them.</p>


<p>Because it is a batch walker that touches everything, it does not operate like the other walkers. This walker is basically performing a top-down SSA renaming pass, where the version stack is used as the cache. This enables it to be significantly more time and memory efficient than using the regular walker, which is walking bottom-up.</p>


<p>Definition at line 1304 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### OptimizeUses() {#ad7fb8e8bcc5cf17ad15225ab3cb9e401}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MemorySSA::OptimizeUses::OptimizeUses (<a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> * MSSA, <a href="/web-llvm/docs/api/classes/llvm/memoryssa/cachingwalker">CachingWalker</a> * Walker, <a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> * BAA, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT)</td>
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



<p>Definition at line 1306 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#a49f6b5c5e36a86395a7f91838768798d">llvm::MemorySSA::MemorySSA</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### optimizeUses() {#a195658a43b30378309ff4e62455dc137}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSA::OptimizeUses::optimizeUses ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Optimize uses to point to their actual clobbering definitions.</p>

<p>Definition at line 1310 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad6e19a09aeed4c56617c284e099c81de">llvm::depth_first</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#acd30a2d319950c138d97d5b3356342b5">llvm::MemorySSA::ensureOptimizedUses</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### optimizeUsesInBlock() {#acb4afff4441502cbce3571ec00d0ada3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSA::OptimizeUses::optimizeUsesInBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, unsigned long &amp; StackEpoch, unsigned long &amp; PopEpoch, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * &gt; &amp; VersionStack, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; MemoryLocOrCall, MemlocStackInfo &gt; &amp; LocStackInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Optimize the uses in a given block This is basically the SSA renaming algorithm, with one caveat: We are able to use a single stack for all MemoryUses.</p>


<p>This is because the set of <em>possible</em> reaching MemoryDefs is the same for every <a href="/web-llvm/docs/api/classes/llvm/memoryuse">MemoryUse</a>. The <em>actual</em> clobbering <a href="/web-llvm/docs/api/classes/llvm/memorydef">MemoryDef</a> is just going to be some position in that stack of possible ones.</p>


<p>We track the stack positions that each <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> needs to check, and last ended at. This is because we only want to check the things that changed since last time. The same <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> should get clobbered by the same store (getModRefInfo does not use invariantness or things like this, and if they start, we can modify MemoryLocOrCall to include relevant data)</p>


<p>Definition at line 1330 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AA {#a78bb9b4cc2902c24215ca19f8e7f7a28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BatchAAResults* llvm::MemorySSA::OptimizeUses::AA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1336 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>

</div>
</div>

### DT {#a6778484e11a1d033766e2638b9c29644}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* llvm::MemorySSA::OptimizeUses::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1337 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>

</div>
</div>

### MSSA {#a47d5cc88db69afde5daaa2773e47a9fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemorySSA* llvm::MemorySSA::OptimizeUses::MSSA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1334 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>

</div>
</div>

### Walker {#ab52d2db73fe03289efbca3f0414b8bda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CachingWalker* llvm::MemorySSA::OptimizeUses::Walker</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1335 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
