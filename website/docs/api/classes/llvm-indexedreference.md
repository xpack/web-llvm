---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/indexedreference
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `IndexedReference` Class Reference

<p>Represents a memory reference as a base pointer and a set of indexing operations. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::IndexedReference { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">llvm/Analysis/LoopCacheAnalysis.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34966ddc17806181257201a312ab2025">operator&lt;&lt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a726079632be5714f8c5e86023ca51f8b">IndexedReference</a> (Instruction &amp;StoreOrLoadInst, const LoopInfo &amp;LI, ScalarEvolution &amp;SE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an indexed reference given a <span class="doxyComputerOutput">StoreOrLoadInst</span> instruction. <a href="#a726079632be5714f8c5e86023ca51f8b">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd2bfc563b0813b904383e7ca49f1511">isValid</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00e125bb3ce22868608246589df76543">getBasePointer</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef3d54c9ec716d007cb7ba0b2deab8b5">getNumSubscripts</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06a4b381bd3760668fd5b5e3c42bc1c3">getSubscript</a> (unsigned SubNum) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2467ee11489e5b3869ef020700a4b386">getFirstSubscript</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac92889237640e228616fe66424984fb9">getLastSubscript</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68b97d806d8c2e58e42e7038bc6d45b8">hasSpacialReuse</a> (const IndexedReference &amp;Other, unsigned CLS, AAResults &amp;AA) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true/false if the current object and the indexed reference <span class="doxyComputerOutput">Other</span> are/aren't in the same cache line of size <span class="doxyComputerOutput">CLS</span>. <a href="#a68b97d806d8c2e58e42e7038bc6d45b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b2b20549af64712df253586da3701a8">hasTemporalReuse</a> (const IndexedReference &amp;Other, unsigned MaxDistance, const Loop &amp;L, DependenceInfo &amp;DI, AAResults &amp;AA) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the current object and the indexed reference <span class="doxyComputerOutput">Other</span> have distance smaller than <span class="doxyComputerOutput">MaxDistance</span> in the dimension associated with the given loop <span class="doxyComputerOutput">L</span>. <a href="#a6b2b20549af64712df253586da3701a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a1cc894ddad08bd7a0c618141f7ece5f3">CacheCostTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0182cdf55f9bfbdd904e3f5e6802316a">computeRefCost</a> (const Loop &amp;L, unsigned CLS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the cost of the reference w.r.t. <a href="#a0182cdf55f9bfbdd904e3f5e6802316a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7c94cc18ec7f097c7e7efd29a243dec">delinearize</a> (const LoopInfo &amp;LI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to delinearize the indexed reference. <a href="#ab7c94cc18ec7f097c7e7efd29a243dec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa19b26a518d45c9a5a70432d0ecb157d">tryDelinearizeFixedSize</a> (const SCEV *AccessFn, SmallVectorImpl&lt; const SCEV * &gt; &amp;Subscripts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to delinearize <span class="doxyComputerOutput">AccessFn</span> for fixed-size arrays. <a href="#aa19b26a518d45c9a5a70432d0ecb157d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70369337c8ca88a174064bcd6a80a6c4">isLoopInvariant</a> (const Loop &amp;L) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the index reference is invariant with respect to loop <span class="doxyComputerOutput">L</span>. <a href="#a70369337c8ca88a174064bcd6a80a6c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdbd415a6f330e2622c8016bd1b4dd91">isConsecutive</a> (const Loop &amp;L, const SCEV *&amp;Stride, unsigned CLS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the indexed reference is 'consecutive' in loop <span class="doxyComputerOutput">L</span>. <a href="#acdbd415a6f330e2622c8016bd1b4dd91">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac23a43b26bc8012ac37d141778544e17">getSubscriptIndex</a> (const Loop &amp;L) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve the index of the subscript corresponding to the given loop <span class="doxyComputerOutput">L</span>. <a href="#ac23a43b26bc8012ac37d141778544e17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4051003f58cbf1844188e4d4f1e193a7">getLastCoefficient</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the coefficient used in the rightmost dimension. <a href="#a4051003f58cbf1844188e4d4f1e193a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d5458f0495a60ca1e8e33ef920e7e1b">isCoeffForLoopZeroOrInvariant</a> (const SCEV &amp;Subscript, const Loop &amp;L) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the coefficient corresponding to induction variable of loop <span class="doxyComputerOutput">L</span> in the given <span class="doxyComputerOutput">Subscript</span> is zero or is loop invariant in <span class="doxyComputerOutput">L</span>. <a href="#a9d5458f0495a60ca1e8e33ef920e7e1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3fc3737837f3cb90844388f0e5c5f03">isSimpleAddRecurrence</a> (const SCEV &amp;Subscript, const Loop &amp;L) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify that the given <span class="doxyComputerOutput">Subscript</span> is 'well formed' (must be a simple add recurrence). <a href="#ae3fc3737837f3cb90844388f0e5c5f03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf4a379d4a57480b6bb5e67e126cf680">isAliased</a> (const IndexedReference &amp;Other, AAResults &amp;AA) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the given reference <span class="doxyComputerOutput">Other</span> is definetely aliased with the indexed reference represented by this class. <a href="#abf4a379d4a57480b6bb5e67e126cf680">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1daea37adfe269bee5cd7fc4a86bc7f">IsValid</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the reference can be delinearized, false otherwise. <a href="#af1daea37adfe269bee5cd7fc4a86bc7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ddfac4f988dda35236faac2c29b7d5a">StoreOrLoadInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represent the memory reference instruction. <a href="#a3ddfac4f988dda35236faac2c29b7d5a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c368b78930e2754e5dfa3aba37f3d6a">BasePointer</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The base pointer of the memory reference. <a href="#a1c368b78930e2754e5dfa3aba37f3d6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, 3 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2efa66320d34c4cf7d7b790d183ff986">Subscripts</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The subscript (indexes) of the memory reference. <a href="#a2efa66320d34c4cf7d7b790d183ff986">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, 3 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d3249a42232ab9df50d89ef6c319c2b">Sizes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The dimensions of the memory reference. <a href="#a6d3249a42232ab9df50d89ef6c319c2b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35fc7edbc65c26019ac59a49d573c997">SE</a></td>
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

<p>Represents a memory reference as a base pointer and a set of indexing operations.</p>


<p>For example given the array reference A[i][2j+1][3k+2] in a 3-dim loop nest: for(i=0;i&lt;n;++i) for(j=0;j&lt;m;++j) for(k=0;k&lt;o;++k) ... A[i][2j+1][3k+2] ... We expect: BasePointer -&gt; A Subscripts -&gt; [{0,+,1}&lt;for.i&gt;][{1,+,2}&lt;for.j&gt;][{2,+,3}&lt;for.k&gt;] Sizes -&gt; [m][o][4]</p>


<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>.</p>


<div class="doxySectionDef">

## Friends

### operator&lt;&lt; {#a34966ddc17806181257201a312ab2025}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/indexedreference">IndexedReference</a> &amp; R</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>.</p>


<p>Reference <a href="#a726079632be5714f8c5e86023ca51f8b">IndexedReference</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### IndexedReference() {#a726079632be5714f8c5e86023ca51f8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndexedReference::IndexedReference (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; StoreOrLoadInst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct an indexed reference given a <span class="doxyComputerOutput">StoreOrLoadInst</span> instruction.</p>

<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>, definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp">LoopCacheAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="#a68b97d806d8c2e58e42e7038bc6d45b8">hasSpacialReuse</a>, <a href="#a6b2b20549af64712df253586da3701a8">hasTemporalReuse</a> and <a href="#a34966ddc17806181257201a312ab2025">operator&lt;&lt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### computeRefCost() {#a0182cdf55f9bfbdd904e3f5e6802316a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CacheCostTy IndexedReference::computeRefCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, unsigned CLS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the cost of the reference w.r.t.</p>


<p>the given loop <span class="doxyComputerOutput">L</span> when it is considered in the innermost position in the loop nest. The cost is defined as:</p>


<ul class="doxyList ">
<li>equal to one if the reference is loop invariant, or</li>
<li>equal to '(TripCount * stride) / cache_line_size' if:

<ul class="doxyList ">
<li>the reference stride is less than the cache line size, and</li>
<li>the coefficient of this loop's index variable used in all other subscripts is zero</li>
</ul></li>
<li>or otherwise equal to 'TripCount'.</li>
</ul>

<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>, definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp">LoopCacheAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp/#af6ab0b42b53810d4456cb51537349222">CacheLineSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp/#a605f4ae007c6b19244c175eb1990abc1">computeTripCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac59306eb826e349ac7429736b1506432">llvm::Type::getExtendedType</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#a57207993e2fe6ec98912e8072e4600bc">llvm::InstructionCost::getInvalid</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a99ab4a82c6d7373e2e367986b9527bf0">llvm::SCEVAddRecExpr::getLoop</a>, <a href="#aef3d54c9ec716d007cb7ba0b2deab8b5">getNumSubscripts</a>, <a href="#a06a4b381bd3760668fd5b5e3c42bc1c3">getSubscript</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#aefeda9454a5e8dfcec3deb106964832a">llvm::SCEV::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

### getBasePointer() {#a00e125bb3ce22868608246589df76543}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::IndexedReference::getBasePointer ()</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>.</p>

</div>
</div>

### getFirstSubscript() {#a2467ee11489e5b3869ef020700a4b386}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::IndexedReference::getFirstSubscript ()</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getLastSubscript() {#ac92889237640e228616fe66424984fb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::IndexedReference::getLastSubscript ()</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a68b97d806d8c2e58e42e7038bc6d45b8">hasSpacialReuse</a>.</p>

</div>
</div>

### getNumSubscripts() {#aef3d54c9ec716d007cb7ba0b2deab8b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::IndexedReference::getNumSubscripts ()</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>.</p>


<p>Referenced by <a href="#a0182cdf55f9bfbdd904e3f5e6802316a">computeRefCost</a>, <a href="#a06a4b381bd3760668fd5b5e3c42bc1c3">getSubscript</a> and <a href="#a68b97d806d8c2e58e42e7038bc6d45b8">hasSpacialReuse</a>.</p>

</div>
</div>

### getSubscript() {#a06a4b381bd3760668fd5b5e3c42bc1c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::IndexedReference::getSubscript (unsigned SubNum)</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aef3d54c9ec716d007cb7ba0b2deab8b5">getNumSubscripts</a>.</p>


<p>Referenced by <a href="#a0182cdf55f9bfbdd904e3f5e6802316a">computeRefCost</a> and <a href="#a68b97d806d8c2e58e42e7038bc6d45b8">hasSpacialReuse</a>.</p>

</div>
</div>

### hasSpacialReuse() {#a68b97d806d8c2e58e42e7038bc6d45b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; bool &gt; IndexedReference::hasSpacialReuse (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/indexedreference">IndexedReference</a> &amp; Other, unsigned CLS, <a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> &amp; AA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true/false if the current object and the indexed reference <span class="doxyComputerOutput">Other</span> are/aren't in the same cache line of size <span class="doxyComputerOutput">CLS</span>.</p>


<p>Two references are in the same chace line iff the distance between them in the innermost dimension is less than the cache line size. Return std::nullopt if unsure.</p>


<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>, definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp">LoopCacheAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ac92889237640e228616fe66424984fb9">getLastSubscript</a>, <a href="#aef3d54c9ec716d007cb7ba0b2deab8b5">getNumSubscripts</a>, <a href="#a06a4b381bd3760668fd5b5e3c42bc1c3">getSubscript</a>, <a href="/web-llvm/docs/api/classes/llvm/scevconstant/#a476a7aca5d55536fcbfb498dfe5d380d">llvm::SCEVConstant::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a>, <a href="#a726079632be5714f8c5e86023ca51f8b">IndexedReference</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adc4eb8be6f7a12ede962987fb9cabb47">llvm::seq</a>.</p>

</div>
</div>

### hasTemporalReuse() {#a6b2b20549af64712df253586da3701a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; bool &gt; IndexedReference::hasTemporalReuse (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/indexedreference">IndexedReference</a> &amp; Other, unsigned MaxDistance, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/classes/llvm/dependenceinfo">DependenceInfo</a> &amp; DI, <a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> &amp; AA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the current object and the indexed reference <span class="doxyComputerOutput">Other</span> have distance smaller than <span class="doxyComputerOutput">MaxDistance</span> in the dimension associated with the given loop <span class="doxyComputerOutput">L</span>.</p>


<p>Return false if the distance is not smaller than <span class="doxyComputerOutput">MaxDistance</span> and std::nullopt if unsure.</p>


<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>, definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp">LoopCacheAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/dependenceinfo/#a49197b24cced248bed2d2c89c641a6dd">llvm::DependenceInfo::depends</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa8f4be0661aa64f5b1f20b15e93bb403">llvm::ConstantInt::getSExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/scevconstant/#a476a7aca5d55536fcbfb498dfe5d380d">llvm::SCEVConstant::getValue</a>, <a href="#a726079632be5714f8c5e86023ca51f8b">IndexedReference</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a882d55a6aa2028e1a5ad708b275334e0">llvm::ConstantInt::isZero</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### isValid() {#abd2bfc563b0813b904383e7ca49f1511}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IndexedReference::isValid ()</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### delinearize() {#ab7c94cc18ec7f097c7e7efd29a243dec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IndexedReference::delinearize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempt to delinearize the indexed reference.</p>

<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>, definition at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp">LoopCacheAnalysis.cpp</a>.</p>

</div>
</div>

### getLastCoefficient() {#a4051003f58cbf1844188e4d4f1e193a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * IndexedReference::getLastCoefficient ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the coefficient used in the rightmost dimension.</p>

<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>, definition at line 517 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp">LoopCacheAnalysis.cpp</a>.</p>

</div>
</div>

### getSubscriptIndex() {#ac23a43b26bc8012ac37d141778544e17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int IndexedReference::getSubscriptIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Retrieve the index of the subscript corresponding to the given loop <span class="doxyComputerOutput">L</span>.</p>


<p>Return a zero-based positive index if the subscript index is succesfully located and a negative value otherwise. For example given the indexed reference 'A[i][2j+1][3k+2]', the call 'getSubscriptIndex(loop-k)' would return value 2.</p>


<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>, definition at line 507 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp">LoopCacheAnalysis.cpp</a>.</p>

</div>
</div>

### isAliased() {#abf4a379d4a57480b6bb5e67e126cf680}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IndexedReference::isAliased (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/indexedreference">IndexedReference</a> &amp; Other, <a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> &amp; AA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the given reference <span class="doxyComputerOutput">Other</span> is definetely aliased with the indexed reference represented by this class.</p>

<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>, definition at line 550 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp">LoopCacheAnalysis.cpp</a>.</p>

</div>
</div>

### isCoeffForLoopZeroOrInvariant() {#a9d5458f0495a60ca1e8e33ef920e7e1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IndexedReference::isCoeffForLoopZeroOrInvariant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> &amp; Subscript, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the coefficient corresponding to induction variable of loop <span class="doxyComputerOutput">L</span> in the given <span class="doxyComputerOutput">Subscript</span> is zero or is loop invariant in <span class="doxyComputerOutput">L</span>.</p>

<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>, definition at line 523 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp">LoopCacheAnalysis.cpp</a>.</p>

</div>
</div>

### isConsecutive() {#acdbd415a6f330e2622c8016bd1b4dd91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IndexedReference::isConsecutive (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *&amp; Stride, unsigned CLS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the indexed reference is 'consecutive' in loop <span class="doxyComputerOutput">L</span>.</p>


<p>An indexed reference is 'consecutive' if the only coefficient that uses the loop induction variable is the rightmost one, and the access stride is smaller than the cache line size <span class="doxyComputerOutput">CLS</span>. Provide a valid <span class="doxyComputerOutput">Stride</span> value if the indexed reference is 'consecutive'.</p>


<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>, definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp">LoopCacheAnalysis.cpp</a>.</p>

</div>
</div>

### isLoopInvariant() {#a70369337c8ca88a174064bcd6a80a6c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IndexedReference::isLoopInvariant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the index reference is invariant with respect to loop <span class="doxyComputerOutput">L</span>.</p>

<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>, definition at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp">LoopCacheAnalysis.cpp</a>.</p>

</div>
</div>

### isSimpleAddRecurrence() {#ae3fc3737837f3cb90844388f0e5c5f03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IndexedReference::isSimpleAddRecurrence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> &amp; Subscript, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify that the given <span class="doxyComputerOutput">Subscript</span> is 'well formed' (must be a simple add recurrence).</p>

<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>, definition at line 530 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp">LoopCacheAnalysis.cpp</a>.</p>

</div>
</div>

### tryDelinearizeFixedSize() {#aa19b26a518d45c9a5a70432d0ecb157d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IndexedReference::tryDelinearizeFixedSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * AccessFn, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; &amp; Subscripts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempt to delinearize <span class="doxyComputerOutput">AccessFn</span> for fixed-size arrays.</p>

<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>, definition at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp">LoopCacheAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BasePointer {#a1c368b78930e2754e5dfa3aba37f3d6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV* llvm::IndexedReference::BasePointer = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The base pointer of the memory reference.</p>

<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>.</p>

</div>
</div>

### IsValid {#af1daea37adfe269bee5cd7fc4a86bc7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IndexedReference::IsValid = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the reference can be delinearized, false otherwise.</p>

<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>.</p>

</div>
</div>

### SE {#a35fc7edbc65c26019ac59a49d573c997}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution&amp; llvm::IndexedReference::SE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>.</p>

</div>
</div>

### Sizes {#a6d3249a42232ab9df50d89ef6c319c2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;const SCEV *, 3&gt; llvm::IndexedReference::Sizes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The dimensions of the memory reference.</p>

<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>.</p>

</div>
</div>

### StoreOrLoadInst {#a3ddfac4f988dda35236faac2c29b7d5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction&amp; llvm::IndexedReference::StoreOrLoadInst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represent the memory reference instruction.</p>

<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>.</p>

</div>
</div>

### Subscripts {#a2efa66320d34c4cf7d7b790d183ff986}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;const SCEV *, 3&gt; llvm::IndexedReference::Subscripts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The subscript (indexes) of the memory reference.</p>

<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopcacheanalysis-h">LoopCacheAnalysis.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp">LoopCacheAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
