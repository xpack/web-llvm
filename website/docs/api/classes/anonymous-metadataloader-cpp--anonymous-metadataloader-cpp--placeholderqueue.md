---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-metadataloader-cpp-/anonymous-metadataloader-cpp-/placeholderqueue
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PlaceholderQueue` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{MetadataLoader.cpp}::anonymous{MetadataLoader.cpp}::PlaceholderQueue { ... }
</div>

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3e95032032e437d6e0af79ff39390e0">~PlaceholderQueue</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a484bc81556c86852c5ede280baebdd7b">empty</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/distinctmdoperandplaceholder">DistinctMDOperandPlaceholder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49a61d6bde2f6c3a38128341f8d99753">getPlaceholderOp</a> (unsigned ID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53488e7b5292861d1b4ac7636ac8d272">flush</a> (BitcodeReaderMetadataList &amp;MetadataList)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab99ee806589a55f539ce9b5b42a07fd6">getTemporaries</a> (BitcodeReaderMetadataList &amp;MetadataList, DenseSet&lt; unsigned &gt; &amp;Temporaries)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the list of temporaries nodes in the queue, these need to be loaded before we can flush the queue. <a href="#ab99ee806589a55f539ce9b5b42a07fd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::deque&lt; <a href="/web-llvm/docs/api/classes/llvm/distinctmdoperandplaceholder">DistinctMDOperandPlaceholder</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a076132634f3dc5094f23c83191ee0075">PHs</a></td>
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


<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>


<div class="doxySectionDef">

## Public Destructor

### \~PlaceholderQueue() {#ae3e95032032e437d6e0af79ff39390e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MetadataLoader.cpp}::anonymous{MetadataLoader.cpp}::PlaceholderQueue::~PlaceholderQueue ()</td>
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



<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a484bc81556c86852c5ede280baebdd7b">empty</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### empty() {#a484bc81556c86852c5ede280baebdd7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MetadataLoader.cpp}::anonymous{MetadataLoader.cpp}::PlaceholderQueue::empty ()</td>
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



<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>


<p>Referenced by <a href="#ae3e95032032e437d6e0af79ff39390e0">~PlaceholderQueue</a>.</p>

</div>
</div>

### flush() {#a53488e7b5292861d1b4ac7636ac8d272}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MetadataLoader.cpp}::PlaceholderQueue::flush (<a href="/web-llvm/docs/api/classes/anonymous-metadataloader-cpp-/bitcodereadermetadatalist">BitcodeReaderMetadataList</a> &amp; MetadataList)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a53488e7b5292861d1b4ac7636ac8d272">flush</a> and <a href="/web-llvm/docs/api/classes/anonymous-metadataloader-cpp-/bitcodereadermetadatalist/#ac3901ff56e9318392be6e1613da5f660">anonymous{MetadataLoader.cpp}::BitcodeReaderMetadataList::lookup</a>.</p>


<p>Referenced by <a href="#a53488e7b5292861d1b4ac7636ac8d272">flush</a>.</p>

</div>
</div>

### getPlaceholderOp() {#a49a61d6bde2f6c3a38128341f8d99753}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DistinctMDOperandPlaceholder &amp; anonymous{MetadataLoader.cpp}::PlaceholderQueue::getPlaceholderOp (unsigned ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>


<p>Reference <a href="#a49a61d6bde2f6c3a38128341f8d99753">getPlaceholderOp</a>.</p>


<p>Referenced by <a href="#a49a61d6bde2f6c3a38128341f8d99753">getPlaceholderOp</a>.</p>

</div>
</div>

### getTemporaries() {#ab99ee806589a55f539ce9b5b42a07fd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MetadataLoader.cpp}::anonymous{MetadataLoader.cpp}::PlaceholderQueue::getTemporaries (<a href="/web-llvm/docs/api/classes/anonymous-metadataloader-cpp-/bitcodereadermetadatalist">BitcodeReaderMetadataList</a> &amp; MetadataList, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; unsigned &gt; &amp; Temporaries)</td>
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

<p>Return the list of temporaries nodes in the queue, these need to be loaded before we can flush the queue.</p>

<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/anonymous-metadataloader-cpp-/bitcodereadermetadatalist/#ac3901ff56e9318392be6e1613da5f660">anonymous{MetadataLoader.cpp}::BitcodeReaderMetadataList::lookup</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### PHs {#a076132634f3dc5094f23c83191ee0075}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::deque&lt;DistinctMDOperandPlaceholder&gt; anonymous{MetadataLoader.cpp}::anonymous{MetadataLoader.cpp}::PlaceholderQueue::PHs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp">MetadataLoader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
