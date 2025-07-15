---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/analysisusage
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AnalysisUsage` Class Reference

<p>Represent the analysis usage information of a pass. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AnalysisUsage { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">llvm/PassAnalysisSupport.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca5945c84f7ab80d6fb87b09c633aff9">VectorType</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa371d2d081bd5a108b861090ac8f8cf7">AnalysisUsage</a> ()=default</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a053677ebc731b47a534f841b11b5cf0c">addRequiredID</a> (const void *ID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5db2bbeaefe8bec69aeaaa53707ed560">addRequiredID</a> (char &amp;ID)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class PassClass&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae0adcccca08fb686c9ce00f9397b660c">addRequired</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39c64174b9b56285668f8fc3602c868a">addRequiredTransitiveID</a> (char &amp;ID)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class PassClass&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afd8af3487564621ceeb41c2838c4469e">addRequiredTransitive</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a573df5c9c3024ebb646e15cc7450bf91">addPreservedID</a> (const void *ID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bec6c0110eba34c58f70e6cb0ae8b32">addPreservedID</a> (char &amp;ID)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class PassClass&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae9356b720f6fbab112d809738dcc4f2a">addPreserved</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the specified <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> class to the set of analyses preserved by this pass. <a href="#ae9356b720f6fbab112d809738dcc4f2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e3b2899057c9d61b73d239680b6cada">addUsedIfAvailableID</a> (const void *ID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eb4c96bc9f31369564e5061a0137bb8">addUsedIfAvailableID</a> (char &amp;ID)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class PassClass&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaeddaf79040291b6f3e0db57943aac39">addUsedIfAvailable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the specified <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> class to the set of analyses used by this pass. <a href="#aaeddaf79040291b6f3e0db57943aac39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d75c71bee6e69f3d97990380abf728c">addPreserved</a> (StringRef Arg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> with the specified argument string to the set of analyses preserved by this pass. <a href="#a8d75c71bee6e69f3d97990380abf728c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af22b06a6a4f9df80454071685a0d6a02">setPreservesAll</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set by analyses that do not transform their input at all. <a href="#af22b06a6a4f9df80454071685a0d6a02">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af25c3e35aa8152adb82963b80be929c0">getPreservesAll</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether a pass said it does not transform its input at all. <a href="#af25c3e35aa8152adb82963b80be929c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af11a6ebf7ab3c388234cb6d5378439a3">setPreservesCFG</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function should be called by the pass, iff they do not: <a href="#af11a6ebf7ab3c388234cb6d5378439a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aca5945c84f7ab80d6fb87b09c633aff9">VectorType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a299caaa13ef3566bddb9781064aebdb9">getRequiredSet</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aca5945c84f7ab80d6fb87b09c633aff9">VectorType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab8bb94b2d54bff44ec50eade145bd08">getRequiredTransitiveSet</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aca5945c84f7ab80d6fb87b09c633aff9">VectorType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9c346823bed8d8787ced3ce5b0a2ced">getPreservedSet</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aca5945c84f7ab80d6fb87b09c633aff9">VectorType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0364d79e9c78f6781cbe243737f5908">getUsedSet</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37238617ecc9dfba096f741af35a22b5">pushUnique</a> (VectorType &amp;Set, AnalysisID ID)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace9a731cb503747b320a3e3af97329ed">Required</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets of analyses required and preserved by a pass. <a href="#ace9a731cb503747b320a3e3af97329ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a>, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7679b6b025283655237ec7e54b8db03">RequiredTransitive</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a>, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d80ecdab831a4832c10772885b6f870">Preserved</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a>, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e2851d16535f5b3303055c55470591f">Used</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84420a5edaba9365265c276d05067d8e">PreservesAll</a> = false</td>
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

<p>Represent the analysis usage information of a pass.</p>


<p>This tracks analyses that the pass REQUIRES (must be available when the pass runs), REQUIRES TRANSITIVE (must be available throughout the lifetime of the pass), and analyses that the pass PRESERVES (the pass does not invalidate the results of these analyses). This information is provided by a pass to the <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> infrastructure through the getAnalysisUsage virtual function.</p>


<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### VectorType {#aca5945c84f7ab80d6fb87b09c633aff9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AnalysisUsage::VectorType =  SmallVectorImpl&lt;AnalysisID&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AnalysisUsage() {#aa371d2d081bd5a108b861090ac8f8cf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AnalysisUsage::AnalysisUsage ()</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>.</p>


<p>Reference <a href="#aa371d2d081bd5a108b861090ac8f8cf7">AnalysisUsage</a>.</p>


<p>Referenced by <a href="#ae9356b720f6fbab112d809738dcc4f2a">addPreserved</a>, <a href="#a4bec6c0110eba34c58f70e6cb0ae8b32">addPreservedID</a>, <a href="#a573df5c9c3024ebb646e15cc7450bf91">addPreservedID</a>, <a href="#ae0adcccca08fb686c9ce00f9397b660c">addRequired</a>, <a href="#afd8af3487564621ceeb41c2838c4469e">addRequiredTransitive</a>, <a href="#aaeddaf79040291b6f3e0db57943aac39">addUsedIfAvailable</a>, <a href="#a9eb4c96bc9f31369564e5061a0137bb8">addUsedIfAvailableID</a>, <a href="#a6e3b2899057c9d61b73d239680b6cada">addUsedIfAvailableID</a> and <a href="#aa371d2d081bd5a108b861090ac8f8cf7">AnalysisUsage</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### addPreserved() {#ae9356b720f6fbab112d809738dcc4f2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class PassClass&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisUsage &amp; llvm::AnalysisUsage::addPreserved ()</td>
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

<p>Add the specified <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> class to the set of analyses preserved by this pass.</p>

<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>.</p>


<p>Reference <a href="#aa371d2d081bd5a108b861090ac8f8cf7">AnalysisUsage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionalcompares-cpp-/aarch64conditionalcompares/#a79c4f2a0f6ffc1499b12ed125d7eb037">anonymous{AArch64ConditionalCompares.cpp}::AArch64ConditionalCompares::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionoptimizer-cpp-/aarch64conditionoptimizer/#afa9ad6e0c297b9d03d6ed1b5d600040a">anonymous{AArch64ConditionOptimizer.cpp}::AArch64ConditionOptimizer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64falkorhwpffix-cpp-/falkormarkstridedaccesseslegacy/#a88542bfc6717233646f03c1c1b3fc323">anonymous{AArch64FalkorHWPFFix.cpp}::FalkorMarkStridedAccessesLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64lowerhomogeneousprologepilog-cpp-/aarch64lowerhomogeneousprologepilog/#ac90310a56e9cae1304a02023e8a760ee">anonymous{AArch64LowerHomogeneousPrologEpilog.cpp}::AArch64LowerHomogeneousPrologEpilog::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuatomicoptimizer-cpp-/amdgpuatomicoptimizer/#a7b032b77e7952375b0c26433648a04ba">anonymous{AMDGPUAtomicOptimizer.cpp}::AMDGPUAtomicOptimizer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteundefforphi-cpp-/amdgpurewriteundefforphilegacy/#afe2e66ff8c88acacb1fe5c1d7cfca524">anonymous{AMDGPURewriteUndefForPHI.cpp}::AMDGPURewriteUndefForPHILegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerldslegacy/#a85bd1cfc3c12dd62d2a5e73d63709dd2">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDSLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-arcoptaddrmode-cpp-/arcoptaddrmode/#aa224aadf7ce53e6b8441944cc88ec676">anonymous{ARCOptAddrMode.cpp}::ARCOptAddrMode::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-armloadstoreoptimizer-cpp-/armpreallocloadstoreopt/#a2cc5513ac011ecae784dde32daf9f4d6">anonymous{ARMLoadStoreOptimizer.cpp}::ARMPreAllocLoadStoreOpt::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-armparalleldsp-cpp-/armparalleldsp/#a150618f73ac168f3449ea9325dc36b81">anonymous{ARMParallelDSP.cpp}::ARMParallelDSP::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-breakcriticaledges-cpp-/breakcriticaledges/#ac685b1d7dc92083ee7a83dde52325281">anonymous{BreakCriticalEdges.cpp}::BreakCriticalEdges::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-callbrprepare-cpp-/callbrprepare/#a514b18b803a20c005c79f430f221b8e7">anonymous{CallBrPrepare.cpp}::CallBrPrepare::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-dwarfehprepare-cpp-/dwarfehpreparelegacypass/#aa1137d5ee4c2aaf0524f3fe814dd329a">anonymous{DwarfEHPrepare.cpp}::DwarfEHPrepareLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/dxiloploweringlegacy/#a157185a2d2388f8a3fa61136cc134b74">anonymous{DXILOpLowering.cpp}::DXILOpLoweringLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilprepare-cpp-/dxilpreparemodule/#a08490029620a1fbff3597782d3a64dcf">anonymous{DXILPrepare.cpp}::DXILPrepareModule::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilresourceaccess-cpp-/dxilresourceaccesslegacy/#a3c78206fa673dfb8c1593242c7266abc">anonymous{DXILResourceAccess.cpp}::DXILResourceAccessLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiltranslatemetadata-cpp-/dxiltranslatemetadatalegacy/#a6823b845ca70cda2be48edfded9c4f07">anonymous{DXILTranslateMetadata.cpp}::DXILTranslateMetadataLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-earlycse-cpp-/earlycselegacycommonpass/#add6c1a279c781bf576a2fe4aa46fca4a">anonymous{EarlyCSE.cpp}::EarlyCSELegacyCommonPass&lt; UseMemorySSA &gt;::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-entryexitinstrumenter-cpp-/postinlineentryexitinstrumenter/#a796b98b416305760f2230be328dc38a0">anonymous{EntryExitInstrumenter.cpp}::PostInlineEntryExitInstrumenter::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandlargedivrem-cpp-/expandlargedivremlegacypass/#a0e0d90119d2ccdbf87c1ec020c54d57d">anonymous{ExpandLargeDivRem.cpp}::ExpandLargeDivRemLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandlargefpconvert-cpp-/expandlargefpconvertlegacypass/#a840614b97dcdefd491294e1147e5aa7e">anonymous{ExpandLargeFpConvert.cpp}::ExpandLargeFpConvertLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-fixirreducible-cpp-/fixirreducible/#aaf7bcebe6f015802ac9bb5287c4c3999">anonymous{FixIrreducible.cpp}::FixIrreducible::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnrewritepartialreguses-cpp-/gcnrewritepartialreguses/#a624377ff0520ceb23b042f018dc1e992">anonymous{GCNRewritePartialRegUses.cpp}::GCNRewritePartialRegUses::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcrootlowering-cpp-/lowerintrinsics/#a6dd7dba6eaa5dbc596a942319506a45c">anonymous{GCRootLowering.cpp}::LowerIntrinsics::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hardwareloops-cpp-/hardwareloopslegacy/#ac18db99454865f90f10be7c256f3471f">anonymous{HardwareLoops.cpp}::HardwareLoopsLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/hexagonbitsimplify/#a6a18fae55fe83e3bbb3cff95adf00f1b">anonymous{HexagonBitSimplify.cpp}::HexagonBitSimplify::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncommongep-cpp-/hexagoncommongep/#a2b2ceca55e74b675689b101431a52f2a">anonymous{HexagonCommonGEP.cpp}::HexagonCommonGEP::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstextenders-cpp-/hexagonconstextenders/#aea3d3b278c26a3ae7bfbe1d7368da81e">anonymous{HexagonConstExtenders.cpp}::HexagonConstExtenders::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncopyhoisting-cpp-/hexagoncopyhoisting/#aa83b5eb5a61f13970f855c9a645e449a">anonymous{HexagonCopyHoisting.cpp}::HexagonCopyHoisting::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonearlyifconv-cpp-/hexagonearlyifconversion/#a83bc48ff47a675c6f7edbb2486949eba">anonymous{HexagonEarlyIfConv.cpp}::HexagonEarlyIfConversion::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonexpandcondsets-cpp-/hexagonexpandcondsets/#a311a761b70b5ef2ce83f724a4311c5ca">anonymous{HexagonExpandCondsets.cpp}::HexagonExpandCondsets::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagongenextract-cpp-/hexagongenextract/#a5707542f1ed48d8046d39b60514b308d">anonymous{HexagonGenExtract.cpp}::HexagonGenExtract::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagongeninsert-cpp-/hexagongeninsert/#a1037fdc4fbedfc5b656bd2c64d0c2d1a">anonymous{HexagonGenInsert.cpp}::HexagonGenInsert::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagongenmemabsolute-cpp-/hexagongenmemabsolute/#abd017b299743136e04848899825d97b8">anonymous{HexagonGenMemAbsolute.cpp}::HexagonGenMemAbsolute::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagongenpredicate-cpp-/hexagongenpredicate/#ac94f3a52927582f7e0b5e0b3919799d3">anonymous{HexagonGenPredicate.cpp}::HexagonGenPredicate::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonloadstorewidening-cpp-/hexagonloadwidening/#a5c2b477c6d7659f57199e9a02f66afa7">anonymous{HexagonLoadStoreWidening.cpp}::HexagonLoadWidening::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonloadstorewidening-cpp-/hexagonstorewidening/#a64f1baf3598ea9f38dd1433657990e3d">anonymous{HexagonLoadStoreWidening.cpp}::HexagonStoreWidening::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonloopidiomrecognition-cpp-/hexagonloopidiomrecognizelegacypass/#a72a353211e73685a259ed17f21bfcd4f">anonymous{HexagonLoopIdiomRecognition.cpp}::HexagonLoopIdiomRecognizeLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonoptimizeszextends-cpp-/hexagonoptimizeszextends/#a1d4b281de1bd93793ccd793ca400e664">anonymous{HexagonOptimizeSZextends.cpp}::HexagonOptimizeSZextends::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonsplitdouble-cpp-/hexagonsplitdoubleregs/#acaa8476d2635e69280db04810879d756">anonymous{HexagonSplitDouble.cpp}::HexagonSplitDoubleRegs::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvliwpacketizer-cpp-/hexagonpacketizer/#aef7b5d1821cb1da9e2591a655e6da756">anonymous{HexagonVLIWPacketizer.cpp}::HexagonPacketizer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-indirectbrexpandpass-cpp-/indirectbrexpandlegacypass/#abb8fafa560b5e35f0f7e13cdf27ea3dc">anonymous{IndirectBrExpandPass.cpp}::IndirectBrExpandLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-inferaddressspaces-cpp-/inferaddressspaces/#a950f96fe966c590afad7e1fb9d626179">anonymous{InferAddressSpaces.cpp}::InferAddressSpaces::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-lcssa-cpp-/lcssawrapperpass/#a4694a636db811386299d0db5acb8bcf8">anonymous{LCSSA.cpp}::LCSSAWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-licm-cpp-/legacylicmpass/#a8c00ffe14e3127e04bc1f74c02d42079">anonymous{LICM.cpp}::LegacyLICMPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchdeadregisterdefinitions-cpp-/loongarchdeadregisterdefinitions/#aee2662f8d6234409ecad4a99ee4d99c1">anonymous{LoongArchDeadRegisterDefinitions.cpp}::LoongArchDeadRegisterDefinitions::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopdataprefetch-cpp-/loopdataprefetchlegacypass/#a1d8d70074433585c3dab03ab0e3da5ab">anonymous{LoopDataPrefetch.cpp}::LoopDataPrefetchLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopextractor-cpp-/loopextractorlegacypass/#ab2e454c9a32974fd2c4f6f3cd70ab231">anonymous{LoopExtractor.cpp}::LoopExtractorLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopsimplify-cpp-/loopsimplify/#aad4eebf0b60c11aab758e8d05d278c23">anonymous{LoopSimplify.cpp}::LoopSimplify::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecse-cpp-/machinecselegacy/#ac3b719058248e500cf47614f838e2dbd">anonymous{MachineCSE.cpp}::MachineCSELegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-machinedebugify-cpp-/debugifymachinemodule/#a3b40ae7b90ab98622f28bf6ca66f940f">anonymous{MachineDebugify.cpp}::DebugifyMachineModule::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinelicm-cpp-/machinelicmbase/#a71713757d5aaefec6ab754b4fd74f1ec">anonymous{MachineLICM.cpp}::MachineLICMBase::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinemoduleinfo-cpp-/freemachinefunction/#a8c084e7306897aea2d4b48da0bbe00be">anonymous{MachineModuleInfo.cpp}::FreeMachineFunction::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a91bb84179044c30641f066d505ac80cc">anonymous{MachineOutliner.cpp}::MachineOutliner::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machinescheduler/#acfe823cc8d6d37bb30948aa5598ebbcd">anonymous{MachineScheduler.cpp}::MachineScheduler::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinesink-cpp-/machinesinking/#aa7678b365028630e8b51cb7b43988523">anonymous{MachineSink.cpp}::MachineSinking::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-machinestripdebug-cpp-/stripdebugmachinemodule/#a43b75493aa0ac47c4a8b194ece8a640e">anonymous{MachineStripDebug.cpp}::StripDebugMachineModule::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsmoduleiseldagtodag-cpp-/mipsmoduledagtodagisel/#a276e73140fd2ad3e9ff7989a72587e48">anonymous{MipsModuleISelDAGToDAG.cpp}::MipsModuleDAGToDAGISel::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsprelegalizercombiner-cpp-/mipsprelegalizercombiner/#a15ad2de16cc122c2bbf5e48df00ba98f">anonymous{MipsPreLegalizerCombiner.cpp}::MipsPreLegalizerCombiner::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-mvetailpredication-cpp-/mvetailpredication/#a501d45b17714ffbb35cfce22c4d2579f">anonymous{MVETailPredication.cpp}::MVETailPredication::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-mvetpandvptoptimisationspass-cpp-/mvetpandvptoptimisations/#a1542078b155e6cab78ec2bd9891e0dbf">anonymous{MVETPAndVPTOptimisationsPass.cpp}::MVETPAndVPTOptimisations::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-naryreassociate-cpp-/naryreassociatelegacypass/#acdc8ee047a896abe97f66951eecf26f3">anonymous{NaryReassociate.cpp}::NaryReassociateLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-nvptxallocahoisting-cpp-/nvptxallocahoisting/#aa4af3183833cf966a70e463c515f2e0c">anonymous{NVPTXAllocaHoisting.cpp}::NVPTXAllocaHoisting::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-nvptxloweraggrcopies-cpp-/nvptxloweraggrcopies/#a13dab7a3b75e368828460c2b365556a9">anonymous{NVPTXLowerAggrCopies.cpp}::NVPTXLowerAggrCopies::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-partiallyinlinelibcalls-cpp-/partiallyinlinelibcallslegacypass/#ade5e04b82d1e1419ce848bd0edd5cbe5">anonymous{PartiallyInlineLibCalls.cpp}::PartiallyInlineLibCallsLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/peepholeoptimizerlegacy/#a7965466f4f6cbc82341601e38cf7f6ec">anonymous{PeepholeOptimizer.cpp}::PeepholeOptimizerLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-postraschedulerlist-cpp-/postrascheduler/#a7ca1172aa08500cf1376986689afcfcc">anonymous{PostRASchedulerList.cpp}::PostRAScheduler::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcboolrettoint-cpp-/ppcboolrettoint/#a11e3444b331ddd64964613fe19bfde30">anonymous{PPCBoolRetToInt.cpp}::PPCBoolRetToInt::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcloopinstrformprep-cpp-/ppcloopinstrformprep/#a1f7a99b42cdfd0cf468d8963f557fe15">anonymous{PPCLoopInstrFormPrep.cpp}::PPCLoopInstrFormPrep::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcmipeephole-cpp-/ppcmipeephole/#a082099f868d05e244d23d2f39cb47d9f">anonymous{PPCMIPeephole.cpp}::PPCMIPeephole::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxfmamutate-cpp-/ppcvsxfmamutate/#ad0e354981e89c51610b71099b5e82cc8">anonymous{PPCVSXFMAMutate.cpp}::PPCVSXFMAMutate::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-prologepiloginserter-cpp-/pei/#a63fab4b6208ac6a9e73d72821e5d24a8">anonymous{PrologEpilogInserter.cpp}::PEI::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600optimizevectorregisters-cpp-/r600vectorregmerger/#ac75ad1526a7fdc5f26ee2807a660eb46">anonymous{R600OptimizeVectorRegisters.cpp}::R600VectorRegMerger::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600packetizer-cpp-/r600packetizer/#a8ca6bb3044f7fedb5c95bba1d03ede31">anonymous{R600Packetizer.cpp}::R600Packetizer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-reassociate-cpp-/reassociatelegacypass/#a8f2f64c5906687a22c672cef94198d23">anonymous{Reassociate.cpp}::ReassociateLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#a4d13f3859751e81e68b91336687b574d">anonymous{RegAllocBasic.cpp}::RABasic::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocpbqp-cpp-/regallocpbqp/#a71020ccbea35e322e29b2b44608289af">anonymous{RegAllocPBQP.cpp}::RegAllocPBQP::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/registercoalescer/#a3ae96d8cb445f62aa68d962e73704705">anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-renameindependentsubregs-cpp-/renameindependentsubregs/#af72b255cdd9f377d029480d76c863fed">anonymous{RenameIndependentSubregs.cpp}::RenameIndependentSubregs::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-resetmachinefunctionpass-cpp-/resetmachinefunction/#a140aab2c7b311c5b71c4be09678d25ef">anonymous{ResetMachineFunctionPass.cpp}::ResetMachineFunction::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvdeadregisterdefinitions-cpp-/riscvdeadregisterdefinitions/#a8988e1e95d5ec1c4126892fc99480b2b">anonymous{RISCVDeadRegisterDefinitions.cpp}::RISCVDeadRegisterDefinitions::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/riscvinsertvsetvli/#a18d6edb1a33bc0f9a4cfd44799f58a84">anonymous{RISCVInsertVSETVLI.cpp}::RISCVInsertVSETVLI::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-safestack-cpp-/safestacklegacypass/#abd80a14763d6d9490edc13415b2b27c1">anonymous{SafeStack.cpp}::SafeStackLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizemaskedmemintrin-cpp-/scalarizemaskedmemintrinlegacypass/#acb6810b35d387d87910b3ac8aa7f845c">anonymous{ScalarizeMaskedMemIntrin.cpp}::ScalarizeMaskedMemIntrinLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizerlegacypass/#ac7cbd2b993094c7b16ea309d58ee9037">anonymous{Scalarizer.cpp}::ScalarizerLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-shadowstackgclowering-cpp-/shadowstackgclowering/#a285ffb8e8bf77ec4947b95cf8b129109">anonymous{ShadowStackGCLowering.cpp}::ShadowStackGCLowering::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopieslegacy/#a5b7801b5d05f081b0c053e5f84dabcf6">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopiesLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a51964e59ed1cde09d8e6d578e9c46d83">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-silatebranchlowering-cpp-/silatebranchlowering/#acd113bbd2eeeda07a7f4eeab24a3cc91">anonymous{SILateBranchLowering.cpp}::SILateBranchLowering::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-silowercontrolflow-cpp-/silowercontrolflowlegacy/#a806a4ecc192e76abda8a370e6507418f">anonymous{SILowerControlFlow.cpp}::SILowerControlFlowLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifycfgpass-cpp-/cfgsimplifypass/#a22030b0a4e64e31ea350bd9762a4c820">anonymous{SimplifyCFGPass.cpp}::CFGSimplifyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-sink-cpp-/sinkinglegacypass/#a63a0ebb8bc075dbdbed33044d75affba">anonymous{Sink.cpp}::SinkingLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverangelegacy/#a6b6807c43df612f845d9d5bea25804e6">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRangeLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-siwholequadmode-cpp-/siwholequadmode/#ac990e329276c09c80bf74e725059b0ce">anonymous{SIWholeQuadMode.cpp}::SIWholeQuadMode::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#adce8f406f264753a41f5271df4cf0e0c">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvprelegalizer-cpp-/spirvprelegalizer/#a8f8d10685e5b83c93ffe50fe3bca2493">anonymous{SPIRVPreLegalizer.cpp}::SPIRVPreLegalizer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-sroa-cpp-/sroalegacypass/#aaf2dc11e06db98231687e6812f2824c0">anonymous{SROA.cpp}::SROALegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-stackslotcoloring-cpp-/stackslotcoloring/#a2cb6c60df9a13bed6099f591bc74969d">anonymous{StackSlotColoring.cpp}::StackSlotColoring::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-structurizecfg-cpp-/structurizecfglegacypass/#abe30a2c7f18e2cb17df9295407d6c22c">anonymous{StructurizeCFG.cpp}::StructurizeCFGLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-tailrecursionelimination-cpp-/tailcallelim/#a47925ada0fb01af49d7ec3b8f448ea65">anonymous{TailRecursionElimination.cpp}::TailCallElim::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-twoaddressinstructionpass-cpp-/twoaddressinstructionlegacypass/#acd910999edf78b013dcbbfa6f2ef0353">anonymous{TwoAddressInstructionPass.cpp}::TwoAddressInstructionLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-typepromotion-cpp-/typepromotionlegacy/#a2fb471fbcaa1b3ba35fb894cff9bc55d">anonymous{TypePromotion.cpp}::TypePromotionLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-unifyloopexits-cpp-/unifyloopexitslegacypass/#a6e8cc7508e2a0724fa2e3b286138f9ad">anonymous{UnifyLoopExits.cpp}::UnifyLoopExitsLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-unreachableblockelim-cpp-/unreachableblockelimlegacypass/#ac19ddf020c3cc4bb87b82e982fdccd14">anonymous{UnreachableBlockElim.cpp}::UnreachableBlockElimLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyargumentmove-cpp-/webassemblyargumentmove/#ae22526ea4a5851f84c6f910fc1dad5f3">anonymous{WebAssemblyArgumentMove.cpp}::WebAssemblyArgumentMove::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblymemintrinsicresults-cpp-/webassemblymemintrinsicresults/#a8652a0cd0eac81b30e2fae4c1c0483c0">anonymous{WebAssemblyMemIntrinsicResults.cpp}::WebAssemblyMemIntrinsicResults::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyregcoloring-cpp-/webassemblyregcoloring/#ae22e46e1547c33232ec93271f5333b80">anonymous{WebAssemblyRegColoring.cpp}::WebAssemblyRegColoring::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblysetp2alignoperands-cpp-/webassemblysetp2alignoperands/#a7b4e9b3f4da1f9c7856861233a4f35c4">anonymous{WebAssemblySetP2AlignOperands.cpp}::WebAssemblySetP2AlignOperands::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsicslegacypass/#ae7b4a930d529b3c3150aae1f17ebdc88">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsicsLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86padshortfunction-cpp-/padshortfunc/#ae26e2f0582e2b06ee89f695f067c7582">anonymous{X86PadShortFunction.cpp}::PadShortFunc::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-xrayinstrumentation-cpp-/xrayinstrumentation/#a09e5cc047d879ebea6c53e307060e4b4">anonymous{XRayInstrumentation.cpp}::XRayInstrumentation::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a7bdb6c2ba8990a862902b14f958e3430">llvm::AMDGPUAsmPrinter::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphsccpass/#a6cc67c5a27b53bc940d292c0aeb6aba3">llvm::CallGraphSCCPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/gvn/gvnlegacypass/#a4fbb957c41dca25995c37de1d627cba9">llvm::gvn::GVNLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncombiningpass/#a5acf47fe333b314ccdb4c0a26f39db97">llvm::InstructionCombiningPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/instructionselect/#a2e38abc4ce9e5203c25ee22862ec012c">llvm::InstructionSelect::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/irtranslator/#aaafe4f214c3f8bae83b25c2c1a476c63">llvm::IRTranslator::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizer/#a68852b9eac9877f212aaf4dd687756cb">llvm::Legalizer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalswrapperpass/#accef3521ae76625b599b616c6f2b5fbf">llvm::LiveIntervalsWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a864fd57b4304ef933b3281d0ef85a88e">llvm::MachineFunctionPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/machinepipeliner/#a2d903deabefad32494df9e3b54667d4d">llvm::MachinePipeliner::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsdagtodagisellegacy/#ab237b5d85abd4902672837a781b46a98">llvm::MipsDAGToDAGISelLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/ragreedy/#aec26bf822b32b653438f2c81d8a220a2">llvm::RAGreedy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/regtomemwrapperpass/#a0be1bffebb870699c735d0cb25ca58ac">llvm::RegToMemWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/llvm/replacewithvecliblegacy/#a3f441f0bb1565ba024c12d645511b53e">llvm::ReplaceWithVeclibLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisellegacy/#a77e4cdd5d33f676fb695a8204f7b70ff">llvm::SelectionDAGISelLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvmergeregionexittargets/#a2162395b97baa410f6b5a0dd6b160c12">llvm::SPIRVMergeRegionExitTargets::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvstructurizer/#a0861553af62de2a79f4a9abecc92b3bb">llvm::SPIRVStructurizer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/stackprotector/#a12935cfbb9f5f549b39564e54ad1d816">llvm::StackProtector::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/siannotatecontrolflowlegacy/#aee9d51ef08a7d3163b2f1601fdaa94a5">SIAnnotateControlFlowLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92caae34bfacc63bda0f23d5d005a89e">llvm::getLoopAnalysisUsage</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa353f9585311abf1b6f698049f5a29b7">llvm::getSelectionDAGFallbackAnalysisUsage</a>.</p>

</div>
</div>

### addPreservedID() {#a573df5c9c3024ebb646e15cc7450bf91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisUsage &amp; llvm::AnalysisUsage::addPreservedID (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * ID)</td>
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




<p>Add the specified <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> to the set of analyses preserved by this pass.</p>


<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>.</p>


<p>Reference <a href="#aa371d2d081bd5a108b861090ac8f8cf7">AnalysisUsage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-breakcriticaledges-cpp-/breakcriticaledges/#ac685b1d7dc92083ee7a83dde52325281">anonymous{BreakCriticalEdges.cpp}::BreakCriticalEdges::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandpostrapseudos-cpp-/expandpostra/#aa5baa1113a3a4807e774c6abdb7ee0ee">anonymous{ExpandPostRAPseudos.cpp}::ExpandPostRA::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorloopcarriedreuse-cpp-/hexagonvectorloopcarriedreuselegacypass/#aaa01e8caee7e8d84bd3a0311252cbfba">anonymous{HexagonVectorLoopCarriedReuse.cpp}::HexagonVectorLoopCarriedReuseLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-lcssa-cpp-/lcssawrapperpass/#a4694a636db811386299d0db5acb8bcf8">anonymous{LCSSA.cpp}::LCSSAWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopdataprefetch-cpp-/loopdataprefetchlegacypass/#a1d8d70074433585c3dab03ab0e3da5ab">anonymous{LoopDataPrefetch.cpp}::LoopDataPrefetchLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopsimplify-cpp-/loopsimplify/#aad4eebf0b60c11aab758e8d05d278c23">anonymous{LoopSimplify.cpp}::LoopSimplify::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kexpandpseudo-cpp-/m68kexpandpseudo/#a465bd03de634225491ac00bfd350cedd">anonymous{M68kExpandPseudo.cpp}::M68kExpandPseudo::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecse-cpp-/machinecselegacy/#ac3b719058248e500cf47614f838e2dbd">anonymous{MachineCSE.cpp}::MachineCSELegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#a4d13f3859751e81e68b91336687b574d">anonymous{RegAllocBasic.cpp}::RABasic::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/registercoalescer/#a3ae96d8cb445f62aa68d962e73704705">anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-stackslotcoloring-cpp-/stackslotcoloring/#a2cb6c60df9a13bed6099f591bc74969d">anonymous{StackSlotColoring.cpp}::StackSlotColoring::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-twoaddressinstructionpass-cpp-/twoaddressinstructionlegacypass/#acd910999edf78b013dcbbfa6f2ef0353">anonymous{TwoAddressInstructionPass.cpp}::TwoAddressInstructionLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyargumentmove-cpp-/webassemblyargumentmove/#ae22526ea4a5851f84c6f910fc1dad5f3">anonymous{WebAssemblyArgumentMove.cpp}::WebAssemblyArgumentMove::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyregcoloring-cpp-/webassemblyregcoloring/#ae22e46e1547c33232ec93271f5333b80">anonymous{WebAssemblyRegColoring.cpp}::WebAssemblyRegColoring::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblysetp2alignoperands-cpp-/webassemblysetp2alignoperands/#a7b4e9b3f4da1f9c7856861233a4f35c4">anonymous{WebAssemblySetP2AlignOperands.cpp}::WebAssemblySetP2AlignOperands::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86expandpseudo-cpp-/x86expandpseudo/#ad5509857d884eab759de5c011843e3d4">anonymous{X86ExpandPseudo.cpp}::X86ExpandPseudo::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86floatingpoint-cpp-/fps/#aea62108993f8b9340a6075e331f77b8c">anonymous{X86FloatingPoint.cpp}::FPS::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalswrapperpass/#accef3521ae76625b599b616c6f2b5fbf">llvm::LiveIntervalsWrapperPass::getAnalysisUsage</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92caae34bfacc63bda0f23d5d005a89e">llvm::getLoopAnalysisUsage</a>.</p>

</div>
</div>

### addPreservedID() {#a4bec6c0110eba34c58f70e6cb0ae8b32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisUsage &amp; llvm::AnalysisUsage::addPreservedID (char &amp; ID)</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>.</p>


<p>Reference <a href="#aa371d2d081bd5a108b861090ac8f8cf7">AnalysisUsage</a>.</p>

</div>
</div>

### addRequired() {#ae0adcccca08fb686c9ce00f9397b660c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class PassClass&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisUsage &amp; llvm::AnalysisUsage::addRequired ()</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>.</p>


<p>References <a href="#a053677ebc731b47a534f841b11b5cf0c">addRequiredID</a> and <a href="#aa371d2d081bd5a108b861090ac8f8cf7">AnalysisUsage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/amdgpuannotateuniformvalueslegacy/#a0940e969144d7bb0f8ff60e409b68d9e">AMDGPUAnnotateUniformValuesLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/amdgpulatecodegenpreparelegacy/#a6212af167be4a14e4c75d2cc6963a211">AMDGPULateCodeGenPrepareLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64cleanuplocaldynamictlspass-cpp-/ldtlscleanup/#a1c8bf8f7dabac34ad685f706dcdf4d68">anonymous{AArch64CleanupLocalDynamicTLSPass.cpp}::LDTLSCleanup::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionalcompares-cpp-/aarch64conditionalcompares/#a79c4f2a0f6ffc1499b12ed125d7eb037">anonymous{AArch64ConditionalCompares.cpp}::AArch64ConditionalCompares::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionoptimizer-cpp-/aarch64conditionoptimizer/#afa9ad6e0c297b9d03d6ed1b5d600040a">anonymous{AArch64ConditionOptimizer.cpp}::AArch64ConditionOptimizer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64falkorhwpffix-cpp-/falkorhwpffix/#a8c2dbb4993bc4963bf1aba0aa5b37177">anonymous{AArch64FalkorHWPFFix.cpp}::FalkorHWPFFix::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64falkorhwpffix-cpp-/falkormarkstridedaccesseslegacy/#a88542bfc6717233646f03c1c1b3fc323">anonymous{AArch64FalkorHWPFFix.cpp}::FalkorMarkStridedAccessesLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a86323ef0ad8018c4d1050ff9951387b2">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64lowerhomogeneousprologepilog-cpp-/aarch64lowerhomogeneousprologepilog/#ac90310a56e9cae1304a02023e8a760ee">anonymous{AArch64LowerHomogeneousPrologEpilog.cpp}::AArch64LowerHomogeneousPrologEpilog::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#ac55399d94c119f2fe23552670cfe1b26">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64postcoalescerpass-cpp-/aarch64postcoalescer/#a5541f5ee801d6b8854f5f78264334b58">anonymous{AArch64PostCoalescerPass.cpp}::AArch64PostCoalescer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64postselectoptimize-cpp-/aarch64postselectoptimize/#abdab7ae0af7e2167213c95ea87397bfb">anonymous{AArch64PostSelectOptimize.cpp}::AArch64PostSelectOptimize::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-alwaysinliner-cpp-/alwaysinlinerlegacypass/#ae32fe1f5d3c8e5bc6d996133d1c7189a">anonymous{AlwaysInliner.cpp}::AlwaysInlinerLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuatomicoptimizer-cpp-/amdgpuatomicoptimizer/#a7b032b77e7952375b0c26433648a04ba">anonymous{AMDGPUAtomicOptimizer.cpp}::AMDGPUAtomicOptimizer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuattributor-cpp-/amdgpuattributorlegacy/#ada9a70da7d545ede8f1d77054966a8d9">anonymous{AMDGPUAttributor.cpp}::AMDGPUAttributorLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepare/#a22e75df81a9f4db7a37b45db0c520bb8">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepare::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuglobaliseldivergencelowering-cpp-/amdgpuglobaliseldivergencelowering/#ae3d7560cc1865d6fd6bbe1c30bf95723">anonymous{AMDGPUGlobalISelDivergenceLowering.cpp}::AMDGPUGlobalISelDivergenceLowering::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/amdgpulowerbufferfatpointers/#a7cb445b46f1664c10d876c3e8357b369">anonymous{AMDGPULowerBufferFatPointers.cpp}::AMDGPULowerBufferFatPointers::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerkernelarguments-cpp-/amdgpulowerkernelarguments/#ae229b01702efbed872d75427d4cf0405">anonymous{AMDGPULowerKernelArguments.cpp}::AMDGPULowerKernelArguments::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermoduleldslegacy/#ab69d1675f05de8109f7c1021a9b7bbc8">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDSLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpumarklastscratchload-cpp-/amdgpumarklastscratchload/#a55615e9a70e295c32f8387234c5ee722">anonymous{AMDGPUMarkLastScratchLoad.cpp}::AMDGPUMarkLastScratchLoad::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpupromotealloca-cpp-/amdgpupromotealloca/#a862c305aa8da9877b0b1adc40047f85d">anonymous{AMDGPUPromoteAlloca.cpp}::AMDGPUPromoteAlloca::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpupromotealloca-cpp-/amdgpupromoteallocatovector/#aad5855d9b0d61f931ddb2051de0762c6">anonymous{AMDGPUPromoteAlloca.cpp}::AMDGPUPromoteAllocaToVector::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpupromotekernelarguments-cpp-/amdgpupromotekernelarguments/#aae3cceff303ca5502f751e40b4a2aa16">anonymous{AMDGPUPromoteKernelArguments.cpp}::AMDGPUPromoteKernelArguments::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuregbanklegalize-cpp-/amdgpuregbanklegalize/#a50b1cba3ede49a7877f198e456ab857c">anonymous{AMDGPURegBankLegalize.cpp}::AMDGPURegBankLegalize::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuregbankselect-cpp-/amdgpuregbankselect/#a94a64b0446c0430a0aa88e931f2fb029">anonymous{AMDGPURegBankSelect.cpp}::AMDGPURegBankSelect::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteoutarguments-cpp-/amdgpurewriteoutarguments/#af4b26d5c6b40a6d1f66d4e96b5352d9b">anonymous{AMDGPURewriteOutArguments.cpp}::AMDGPURewriteOutArguments::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteundefforphi-cpp-/amdgpurewriteundefforphilegacy/#afe2e66ff8c88acacb1fe5c1d7cfca524">anonymous{AMDGPURewriteUndefForPHI.cpp}::AMDGPURewriteUndefForPHILegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-arcoptaddrmode-cpp-/arcoptaddrmode/#aa224aadf7ce53e6b8441944cc88ec676">anonymous{ARCOptAddrMode.cpp}::ARCOptAddrMode::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-armconstantislandpass-cpp-/armconstantislands/#a225e3a366286304012ebb04ca6aee82d">anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-armfixcortexa57aes1742098pass-cpp-/armfixcortexa57aes1742098/#a5232447e95e3e81c9754a18aee3f183d">anonymous{ARMFixCortexA57AES1742098Pass.cpp}::ARMFixCortexA57AES1742098::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-armloadstoreoptimizer-cpp-/armpreallocloadstoreopt/#a2cc5513ac011ecae784dde32daf9f4d6">anonymous{ARMLoadStoreOptimizer.cpp}::ARMPreAllocLoadStoreOpt::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-armlowoverheadloops-cpp-/armlowoverheadloops/#af5b3b47d9f63f641b02afd1f74e738d1">anonymous{ARMLowOverheadLoops.cpp}::ARMLowOverheadLoops::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-armparalleldsp-cpp-/armparalleldsp/#a150618f73ac168f3449ea9325dc36b81">anonymous{ARMParallelDSP.cpp}::ARMParallelDSP::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-basicblocksections-cpp-/basicblocksections/#af2caf856b1f9546f0855b33391857973">anonymous{BasicBlockSections.cpp}::BasicBlockSections::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpfcheckandadjustir-cpp-/bpfcheckandadjustir/#a678b8f3053aac113a9f6aed33d65b733">anonymous{BPFCheckAndAdjustIR.cpp}::BPFCheckAndAdjustIR::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-branchfolding-cpp-/branchfolderpass/#a78829d89aee87c166fde97d60972afab">anonymous{BranchFolding.cpp}::BranchFolderPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-callprinter-cpp-/callgraphdotprinter/#ab8495a00f0c8d8dc82aa00ea515dc692">anonymous{CallPrinter.cpp}::CallGraphDOTPrinter::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-callprinter-cpp-/callgraphviewer/#acdb259f5a825cd4226f7ddb29f94c869">anonymous{CallPrinter.cpp}::CallGraphViewer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/codegenpreparelegacypass/#a4e6eaa6981139214f5c249f3b365e2a3">anonymous{CodeGenPrepare.cpp}::CodeGenPrepareLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-complexdeinterleavingpass-cpp-/complexdeinterleavinglegacypass/#ae39cf189b0a2930fb659bcecc57d2167">anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-constanthoisting-cpp-/constanthoistinglegacypass/#a5c306d7b0d842abb33b4b7f02d897cc4">anonymous{ConstantHoisting.cpp}::ConstantHoistingLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-dce-cpp-/dcelegacypass/#a2a7be817b0869b862a91dba894f3a804">anonymous{DCE.cpp}::DCELegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-dwarfehprepare-cpp-/dwarfehpreparelegacypass/#aa1137d5ee4c2aaf0524f3fe814dd329a">anonymous{DwarfEHPrepare.cpp}::DwarfEHPrepareLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxcontainerglobals-cpp-/dxcontainerglobals/#a5e5375542fbfad721eeef4fc1ec31563">anonymous{DXContainerGlobals.cpp}::DXContainerGlobals::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/dxiloploweringlegacy/#a157185a2d2388f8a3fa61136cc134b74">anonymous{DXILOpLowering.cpp}::DXILOpLoweringLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilprepare-cpp-/dxilpreparemodule/#a08490029620a1fbff3597782d3a64dcf">anonymous{DXILPrepare.cpp}::DXILPrepareModule::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilprettyprinter-cpp-/dxilprettyprinterlegacy/#a91b0e2d13da7d7eeaf54b8702e459dac">anonymous{DXILPrettyPrinter.cpp}::DXILPrettyPrinterLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilresourceaccess-cpp-/dxilresourceaccesslegacy/#a3c78206fa673dfb8c1593242c7266abc">anonymous{DXILResourceAccess.cpp}::DXILResourceAccessLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiltranslatemetadata-cpp-/dxiltranslatemetadatalegacy/#a6823b845ca70cda2be48edfded9c4f07">anonymous{DXILTranslateMetadata.cpp}::DXILTranslateMetadataLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-earlycse-cpp-/earlycselegacycommonpass/#add6c1a279c781bf576a2fe4aa46fca4a">anonymous{EarlyCSE.cpp}::EarlyCSELegacyCommonPass&lt; UseMemorySSA &gt;::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandlargedivrem-cpp-/expandlargedivremlegacypass/#a0e0d90119d2ccdbf87c1ec020c54d57d">anonymous{ExpandLargeDivRem.cpp}::ExpandLargeDivRemLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandlargefpconvert-cpp-/expandlargefpconvertlegacypass/#a840614b97dcdefd491294e1147e5aa7e">anonymous{ExpandLargeFpConvert.cpp}::ExpandLargeFpConvertLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandreductions-cpp-/expandreductions/#ae6ad7189d53a46066fce43bcab716ab2">anonymous{ExpandReductions.cpp}::ExpandReductions::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-fixirreducible-cpp-/fixirreducible/#aaf7bcebe6f015802ac9bb5287c4c3999">anonymous{FixIrreducible.cpp}::FixIrreducible::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-flattencfgpass-cpp-/flattencfglegacypass/#ad40418337fba6307c22fc9518bdb1daf">anonymous{FlattenCFGPass.cpp}::FlattenCFGLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnnsareassign-cpp-/gcnnsareassign/#ac14efeec9a3e2cddd316e0ec3ad74c79">anonymous{GCNNSAReassign.cpp}::GCNNSAReassign::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnpreraoptimizations-cpp-/gcnpreraoptimizations/#a21808667d9b3c477d4ade30180851fec">anonymous{GCNPreRAOptimizations.cpp}::GCNPreRAOptimizations::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcrootlowering-cpp-/gcmachinecodeanalysis/#a9539c0e4d2cea8bc107ed991bb50b777">anonymous{GCRootLowering.cpp}::GCMachineCodeAnalysis::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcrootlowering-cpp-/lowerintrinsics/#a6dd7dba6eaa5dbc596a942319506a45c">anonymous{GCRootLowering.cpp}::LowerIntrinsics::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hardwareloops-cpp-/hardwareloopslegacy/#ac18db99454865f90f10be7c256f3471f">anonymous{HardwareLoops.cpp}::HardwareLoopsLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/hexagonbitsimplify/#a6a18fae55fe83e3bbb3cff95adf00f1b">anonymous{HexagonBitSimplify.cpp}::HexagonBitSimplify::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncommongep-cpp-/hexagoncommongep/#a2b2ceca55e74b675689b101431a52f2a">anonymous{HexagonCommonGEP.cpp}::HexagonCommonGEP::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstextenders-cpp-/hexagonconstextenders/#aea3d3b278c26a3ae7bfbe1d7368da81e">anonymous{HexagonConstExtenders.cpp}::HexagonConstExtenders::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncopyhoisting-cpp-/hexagoncopyhoisting/#aa83b5eb5a61f13970f855c9a645e449a">anonymous{HexagonCopyHoisting.cpp}::HexagonCopyHoisting::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonearlyifconv-cpp-/hexagonearlyifconversion/#a83bc48ff47a675c6f7edbb2486949eba">anonymous{HexagonEarlyIfConv.cpp}::HexagonEarlyIfConversion::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonexpandcondsets-cpp-/hexagonexpandcondsets/#a311a761b70b5ef2ce83f724a4311c5ca">anonymous{HexagonExpandCondsets.cpp}::HexagonExpandCondsets::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagongenextract-cpp-/hexagongenextract/#a5707542f1ed48d8046d39b60514b308d">anonymous{HexagonGenExtract.cpp}::HexagonGenExtract::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagongeninsert-cpp-/hexagongeninsert/#a1037fdc4fbedfc5b656bd2c64d0c2d1a">anonymous{HexagonGenInsert.cpp}::HexagonGenInsert::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagongenmemabsolute-cpp-/hexagongenmemabsolute/#abd017b299743136e04848899825d97b8">anonymous{HexagonGenMemAbsolute.cpp}::HexagonGenMemAbsolute::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagongenpredicate-cpp-/hexagongenpredicate/#ac94f3a52927582f7e0b5e0b3919799d3">anonymous{HexagonGenPredicate.cpp}::HexagonGenPredicate::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonhardwareloops-cpp-/hexagonhardwareloops/#a6883ae5f17e638eb68522e3e2cde21c6">anonymous{HexagonHardwareLoops.cpp}::HexagonHardwareLoops::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonloadstorewidening-cpp-/hexagonloadwidening/#a5c2b477c6d7659f57199e9a02f66afa7">anonymous{HexagonLoadStoreWidening.cpp}::HexagonLoadWidening::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonloadstorewidening-cpp-/hexagonstorewidening/#a64f1baf3598ea9f38dd1433657990e3d">anonymous{HexagonLoadStoreWidening.cpp}::HexagonStoreWidening::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonloopalign-cpp-/hexagonloopalign/#aee1009b261417f4e10ba2bfe481f4d99">anonymous{HexagonLoopAlign.cpp}::HexagonLoopAlign::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonloopidiomrecognition-cpp-/hexagonloopidiomrecognizelegacypass/#a72a353211e73685a259ed17f21bfcd4f">anonymous{HexagonLoopIdiomRecognition.cpp}::HexagonLoopIdiomRecognizeLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonnewvaluejump-cpp-/hexagonnewvaluejump/#a19d887b47ccf986d1a7cfaddf387920e">anonymous{HexagonNewValueJump.cpp}::HexagonNewValueJump::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonoptaddrmode-cpp-/hexagonoptaddrmode/#afef5504e71fa5e9ee7699f60446d0115">anonymous{HexagonOptAddrMode.cpp}::HexagonOptAddrMode::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonrdfopt-cpp-/hexagonrdfopt/#aaf2555430b493cb574fc002d72c827f1">anonymous{HexagonRDFOpt.cpp}::HexagonRDFOpt::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonsplitdouble-cpp-/hexagonsplitdoubleregs/#acaa8476d2635e69280db04810879d756">anonymous{HexagonSplitDouble.cpp}::HexagonSplitDoubleRegs::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombinelegacy/#abd5bd35073dfc041b595cdaee05bb3b3">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombineLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvliwpacketizer-cpp-/hexagonpacketizer/#aef7b5d1821cb1da9e2591a655e6da756">anonymous{HexagonVLIWPacketizer.cpp}::HexagonPacketizer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-ifconversion-cpp-/ifconverter/#a9d02eb24e13645d5e8d4b5108a2b1933">anonymous{IfConversion.cpp}::IfConverter::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-implicitnullchecks-cpp-/implicitnullchecks/#ab1fc2ec69c6bd7e03ab4f5ff67e90728">anonymous{ImplicitNullChecks.cpp}::ImplicitNullChecks::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-inferaddressspaces-cpp-/inferaddressspaces/#a950f96fe966c590afad7e1fb9d626179">anonymous{InferAddressSpaces.cpp}::InferAddressSpaces::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-instsimplifypass-cpp-/instsimplifylegacypass/#a050c5b493bb56cdbcf056a3f17a3994f">anonymous{InstSimplifyPass.cpp}::InstSimplifyLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-interleavedaccesspass-cpp-/interleavedaccess/#aac977fbdda0d61e77203eac9a53b0eba">anonymous{InterleavedAccessPass.cpp}::InterleavedAccess::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/interleavedloadcombine/#ae150a828e8305ad8c3ead8ceee930089">anonymous{InterleavedLoadCombinePass.cpp}::InterleavedLoadCombine::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-lcssa-cpp-/lcssawrapperpass/#a4694a636db811386299d0db5acb8bcf8">anonymous{LCSSA.cpp}::LCSSAWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-licm-cpp-/legacylicmpass/#a8c00ffe14e3127e04bc1f74c02d42079">anonymous{LICM.cpp}::LegacyLICMPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-loadstorevectorizer-cpp-/loadstorevectorizerlegacypass/#a4131111ba674d294e4c9fe6c7c46ae84">anonymous{LoadStoreVectorizer.cpp}::LoadStoreVectorizerLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchdeadregisterdefinitions-cpp-/loongarchdeadregisterdefinitions/#aee2662f8d6234409ecad4a99ee4d99c1">anonymous{LoongArchDeadRegisterDefinitions.cpp}::LoongArchDeadRegisterDefinitions::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopdataprefetch-cpp-/loopdataprefetchlegacypass/#a1d8d70074433585c3dab03ab0e3da5ab">anonymous{LoopDataPrefetch.cpp}::LoopDataPrefetchLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopextractor-cpp-/loopextractorlegacypass/#ab2e454c9a32974fd2c4f6f3cd70ab231">anonymous{LoopExtractor.cpp}::LoopExtractorLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopsimplify-cpp-/loopsimplify/#aad4eebf0b60c11aab758e8d05d278c23">anonymous{LoopSimplify.cpp}::LoopSimplify::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopunrollpass-cpp-/loopunroll/#a300d24aab1f2cf36089d0daa640d5b8f">anonymous{LoopUnrollPass.cpp}::LoopUnroll::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowerswitch-cpp-/lowerswitchlegacypass/#ab55ff6eff576b4a53dbfc40032f394c4">anonymous{LowerSwitch.cpp}::LowerSwitchLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/machineblockplacement/#a237eea84de9a4035f23734cb04d32389">anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/machineblockplacementstats/#af6fdd4aa0d9c5af936fea8be657b7c7a">anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacementStats::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-machinecheckdebugify-cpp-/checkdebugmachinemodule/#aa9d0124df2e155e60e441d086e0f0769">anonymous{MachineCheckDebugify.cpp}::CheckDebugMachineModule::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecse-cpp-/machinecselegacy/#ac3b719058248e500cf47614f838e2dbd">anonymous{MachineCSE.cpp}::MachineCSELegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-machinedebugify-cpp-/debugifymachinemodule/#a3b40ae7b90ab98622f28bf6ca66f940f">anonymous{MachineDebugify.cpp}::DebugifyMachineModule::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinefunctionsplitter-cpp-/machinefunctionsplitter/#ab0ffdd6a9a1d23949f793e83a0ce7cec">anonymous{MachineFunctionSplitter.cpp}::MachineFunctionSplitter::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinelicm-cpp-/machinelicmbase/#a71713757d5aaefec6ab754b4fd74f1ec">anonymous{MachineLICM.cpp}::MachineLICMBase::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinemoduleinfo-cpp-/freemachinefunction/#a8c084e7306897aea2d4b48da0bbe00be">anonymous{MachineModuleInfo.cpp}::FreeMachineFunction::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a91bb84179044c30641f066d505ac80cc">anonymous{MachineOutliner.cpp}::MachineOutliner::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machinescheduler/#acfe823cc8d6d37bb30948aa5598ebbcd">anonymous{MachineScheduler.cpp}::MachineScheduler::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/postmachinescheduler/#a065b9f9c1b17415e3e76fb115be4f7b4">anonymous{MachineScheduler.cpp}::PostMachineScheduler::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinesink-cpp-/machinesinking/#aa7678b365028630e8b51cb7b43988523">anonymous{MachineSink.cpp}::MachineSinking::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-machinestripdebug-cpp-/stripdebugmachinemodule/#a43b75493aa0ac47c4a8b194ece8a640e">anonymous{MachineStripDebug.cpp}::StripDebugMachineModule::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-mem2reg-cpp-/promotelegacypass/#a82a0f24161fb10b3fb9c5ca7f01b05cc">anonymous{Mem2Reg.cpp}::PromoteLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-mips16hardfloat-cpp-/mips16hardfloat/#af19d4487f8cb225bcce0c323d24e9d05">anonymous{Mips16HardFloat.cpp}::Mips16HardFloat::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/mipsdelayslotfiller/#a94dc249ca8d34e16710b6a150efe00d9">anonymous{MipsDelaySlotFiller.cpp}::MipsDelaySlotFiller::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsmoduleiseldagtodag-cpp-/mipsmoduledagtodagisel/#a276e73140fd2ad3e9ff7989a72587e48">anonymous{MipsModuleISelDAGToDAG.cpp}::MipsModuleDAGToDAGISel::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsoptimizepiccall-cpp-/optimizepiccall/#a74f168686fcf897333fc50993ce7bd47">anonymous{MipsOptimizePICCall.cpp}::OptimizePICCall::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsprelegalizercombiner-cpp-/mipsprelegalizercombiner/#a15ad2de16cc122c2bbf5e48df00ba98f">anonymous{MipsPreLegalizerCombiner.cpp}::MipsPreLegalizerCombiner::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-moduloschedule-cpp-/moduloscheduletest/#a763e80108bd2b1b85d36eb4850392234">anonymous{ModuloSchedule.cpp}::ModuloScheduleTest::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-mvegatherscatterlowering-cpp-/mvegatherscatterlowering/#afa4a0702e24a4ace54875ffda7200ae2">anonymous{MVEGatherScatterLowering.cpp}::MVEGatherScatterLowering::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-mvelaneinterleavingpass-cpp-/mvelaneinterleaving/#a5d398dffcffa3207fea0090bfcb6b18a">anonymous{MVELaneInterleavingPass.cpp}::MVELaneInterleaving::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-mvetailpredication-cpp-/mvetailpredication/#a501d45b17714ffbb35cfce22c4d2579f">anonymous{MVETailPredication.cpp}::MVETailPredication::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-mvetpandvptoptimisationspass-cpp-/mvetpandvptoptimisations/#a1542078b155e6cab78ec2bd9891e0dbf">anonymous{MVETPAndVPTOptimisationsPass.cpp}::MVETPAndVPTOptimisations::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-naryreassociate-cpp-/naryreassociatelegacypass/#acdc8ee047a896abe97f66951eecf26f3">anonymous{NaryReassociate.cpp}::NaryReassociateLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-nvptxloweraggrcopies-cpp-/nvptxloweraggrcopies/#a13dab7a3b75e368828460c2b365556a9">anonymous{NVPTXLowerAggrCopies.cpp}::NVPTXLowerAggrCopies::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-nvptxlowerargs-cpp-/nvptxlowerargs/#a6e8ca04c9f6a67bcc80d536b263c2105">anonymous{NVPTXLowerArgs.cpp}::NVPTXLowerArgs::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-partiallyinlinelibcalls-cpp-/partiallyinlinelibcallslegacypass/#ade5e04b82d1e1419ce848bd0edd5cbe5">anonymous{PartiallyInlineLibCalls.cpp}::PartiallyInlineLibCallsLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/peepholeoptimizerlegacy/#a7965466f4f6cbc82341601e38cf7f6ec">anonymous{PeepholeOptimizer.cpp}::PeepholeOptimizerLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-placesafepoints-cpp-/placebackedgesafepointslegacypass/#acdbf6d8b413ffb81652cf8c434ee423a">anonymous{PlaceSafepoints.cpp}::PlaceBackedgeSafepointsLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-postraschedulerlist-cpp-/postrascheduler/#a7ca1172aa08500cf1376986689afcfcc">anonymous{PostRASchedulerList.cpp}::PostRAScheduler::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcbranchcoalescing-cpp-/ppcbranchcoalescing/#a2ae2b3027535582801166cef1673ecbc">anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcctrloops-cpp-/ppcctrloops/#a19fdc5190a4a5e96f8a433cc87c9421c">anonymous{PPCCTRLoops.cpp}::PPCCTRLoops::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcctrloopsverify-cpp-/ppcctrloopsverify/#a47b5b0305fc7dcfdb07067fe735e5c48">anonymous{PPCCTRLoopsVerify.cpp}::PPCCTRLoopsVerify::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcgenscalarmassentries-cpp-/ppcgenscalarmassentries/#ae783839eedd5ea2ac282612112981262">anonymous{PPCGenScalarMASSEntries.cpp}::PPCGenScalarMASSEntries::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcloopinstrformprep-cpp-/ppcloopinstrformprep/#a1f7a99b42cdfd0cf468d8963f557fe15">anonymous{PPCLoopInstrFormPrep.cpp}::PPCLoopInstrFormPrep::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppclowermassventries-cpp-/ppclowermassventries/#a9ef3feaa598c937267b5c8343c0c09b2">anonymous{PPCLowerMASSVEntries.cpp}::PPCLowerMASSVEntries::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcmipeephole-cpp-/ppcmipeephole/#a082099f868d05e244d23d2f39cb47d9f">anonymous{PPCMIPeephole.cpp}::PPCMIPeephole::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcreducecrlogicals-cpp-/ppcreducecrlogicals/#ab30c2f24f66704c3debfd08a32e6710e">anonymous{PPCReduceCRLogicals.cpp}::PPCReduceCRLogicals::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppctlsdynamiccall-cpp-/ppctlsdynamiccall/#afb8bbf7345d8ec58a890a17540c7ef5b">anonymous{PPCTLSDynamicCall.cpp}::PPCTLSDynamicCall::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxfmamutate-cpp-/ppcvsxfmamutate/#ad0e354981e89c51610b71099b5e82cc8">anonymous{PPCVSXFMAMutate.cpp}::PPCVSXFMAMutate::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-preiselintrinsiclowering-cpp-/preiselintrinsicloweringlegacypass/#a4646a2335914e23a6f7c676431ddfa30">anonymous{PreISelIntrinsicLowering.cpp}::PreISelIntrinsicLoweringLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-prologepiloginserter-cpp-/pei/#a63fab4b6208ac6a9e73d72821e5d24a8">anonymous{PrologEpilogInserter.cpp}::PEI::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a21c3c4b8d8ffa687c62ee01b4095ca8b">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600optimizevectorregisters-cpp-/r600vectorregmerger/#ac75ad1526a7fdc5f26ee2807a660eb46">anonymous{R600OptimizeVectorRegisters.cpp}::R600VectorRegMerger::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600packetizer-cpp-/r600packetizer/#a8ca6bb3044f7fedb5c95bba1d03ede31">anonymous{R600Packetizer.cpp}::R600Packetizer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#a4d13f3859751e81e68b91336687b574d">anonymous{RegAllocBasic.cpp}::RABasic::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocpbqp-cpp-/regallocpbqp/#a71020ccbea35e322e29b2b44608289af">anonymous{RegAllocPBQP.cpp}::RegAllocPBQP::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/registercoalescer/#a3ae96d8cb445f62aa68d962e73704705">anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-regusageinfocollector-cpp-/regusageinfocollectorlegacy/#ad487cac993b0d3201079cd70c21279c8">anonymous{RegUsageInfoCollector.cpp}::RegUsageInfoCollectorLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-regusageinfopropagate-cpp-/regusageinfopropagationlegacy/#a10a8c6e435b643810f3886c69822dbf2">anonymous{RegUsageInfoPropagate.cpp}::RegUsageInfoPropagationLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-renameindependentsubregs-cpp-/renameindependentsubregs/#af72b255cdd9f377d029480d76c863fed">anonymous{RenameIndependentSubregs.cpp}::RenameIndependentSubregs::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvcodegenprepare-cpp-/riscvcodegenprepare/#ab97b46bd6a2c271a6a2a97aff8fae7c1">anonymous{RISCVCodeGenPrepare.cpp}::RISCVCodeGenPrepare::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvdeadregisterdefinitions-cpp-/riscvdeadregisterdefinitions/#a8988e1e95d5ec1c4126892fc99480b2b">anonymous{RISCVDeadRegisterDefinitions.cpp}::RISCVDeadRegisterDefinitions::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvgatherscatterlowering-cpp-/riscvgatherscatterlowering/#a0466570efcd27f0c4485577a37159688">anonymous{RISCVGatherScatterLowering.cpp}::RISCVGatherScatterLowering::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvvloptimizer-cpp-/riscvvloptimizer/#aa14a7f95541927aba67d68823ffa2958">anonymous{RISCVVLOptimizer.cpp}::RISCVVLOptimizer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvzacasabifix-cpp-/riscvzacasabifix/#ad8d174cc8e85d5b8f7570bf963539769">anonymous{RISCVZacasABIFix.cpp}::RISCVZacasABIFix::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-safestack-cpp-/safestacklegacypass/#abd80a14763d6d9490edc13415b2b27c1">anonymous{SafeStack.cpp}::SafeStackLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizemaskedmemintrin-cpp-/scalarizemaskedmemintrinlegacypass/#acb6810b35d387d87910b3ac8aa7f845c">anonymous{ScalarizeMaskedMemIntrin.cpp}::ScalarizeMaskedMemIntrinLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizerlegacypass/#ac7cbd2b993094c7b16ea309d58ee9037">anonymous{Scalarizer.cpp}::ScalarizerLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-selectoptimize-cpp-/selectoptimize/#a94063cc83bab14b9c34f595f6e2692eb">anonymous{SelectOptimize.cpp}::SelectOptimize::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-separateconstoffsetfromgep-cpp-/separateconstoffsetfromgeplegacypass/#a81256fb5d7e5a723f09517f9d9297f91">anonymous{SeparateConstOffsetFromGEP.cpp}::SeparateConstOffsetFromGEPLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-shrinkwrap-cpp-/shrinkwrap/#a269884a1a9c68cf90e38daf6a0110bc4">anonymous{ShrinkWrap.cpp}::ShrinkWrap::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopieslegacy/#a5b7801b5d05f081b0c053e5f84dabcf6">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopiesLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-siformmemoryclauses-cpp-/siformmemoryclauses/#a7db6582b867e122bd23862020ee89628">anonymous{SIFormMemoryClauses.cpp}::SIFormMemoryClauses::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a51964e59ed1cde09d8e6d578e9c46d83">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-silatebranchlowering-cpp-/silatebranchlowering/#acd113bbd2eeeda07a7f4eeab24a3cc91">anonymous{SILateBranchLowering.cpp}::SILateBranchLowering::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloadstoreoptimizer-cpp-/siloadstoreoptimizerlegacy/#aae29199e4c801d23eca02b6d2cac7864">anonymous{SILoadStoreOptimizer.cpp}::SILoadStoreOptimizerLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-silowersgprspills-cpp-/silowersgprspillslegacy/#adcfc087805876f59c13dc6f1796b6554">anonymous{SILowerSGPRSpills.cpp}::SILowerSGPRSpillsLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifycfgpass-cpp-/cfgsimplifypass/#a22030b0a4e64e31ea350bd9762a4c820">anonymous{SimplifyCFGPass.cpp}::CFGSimplifyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-sink-cpp-/sinkinglegacypass/#a63a0ebb8bc075dbdbed33044d75affba">anonymous{Sink.cpp}::SinkingLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizeexecmaskingprera-cpp-/sioptimizeexecmaskingprera/#aea34846856fb7148baa6d82e06c246b4">anonymous{SIOptimizeExecMaskingPreRA.cpp}::SIOptimizeExecMaskingPreRA::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverangelegacy/#a6b6807c43df612f845d9d5bea25804e6">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRangeLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipreallocatewwmregs-cpp-/sipreallocatewwmregslegacy/#afc84aba53e7ecaa959484476e87ca761">anonymous{SIPreAllocateWWMRegs.cpp}::SIPreAllocateWWMRegsLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-siwholequadmode-cpp-/siwholequadmode/#ac990e329276c09c80bf74e725059b0ce">anonymous{SIWholeQuadMode.cpp}::SIWholeQuadMode::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#adce8f406f264753a41f5271df4cf0e0c">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-sroa-cpp-/sroalegacypass/#aaf2dc11e06db98231687e6812f2824c0">anonymous{SROA.cpp}::SROALegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-stackframelayoutanalysispass-cpp-/stackframelayoutanalysispass/#a8e0327390d0eda5d61ba53f7171c4832">anonymous{StackFrameLayoutAnalysisPass.cpp}::StackFrameLayoutAnalysisPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-stackslotcoloring-cpp-/stackslotcoloring/#a2cb6c60df9a13bed6099f591bc74969d">anonymous{StackSlotColoring.cpp}::StackSlotColoring::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-straightlinestrengthreduce-cpp-/straightlinestrengthreducelegacypass/#acb64aa0d77f5a3c7745951769fc79d32">anonymous{StraightLineStrengthReduce.cpp}::StraightLineStrengthReduceLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-structurizecfg-cpp-/structurizecfglegacypass/#abe30a2c7f18e2cb17df9295407d6c22c">anonymous{StructurizeCFG.cpp}::StructurizeCFGLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-sveintrinsicopts-cpp-/sveintrinsicopts/#ab1126ddaa19fe6e6ab65392b3e517bc8">anonymous{SVEIntrinsicOpts.cpp}::SVEIntrinsicOpts::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzldcleanup-cpp-/systemzldcleanup/#a6fa7da9dd93bcae47100dad33845cec1">anonymous{SystemZLDCleanup.cpp}::SystemZLDCleanup::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemztdc-cpp-/systemztdcpass/#a38d804eb84c703e3cf6875e297e10e2a">anonymous{SystemZTDC.cpp}::SystemZTDCPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-tailduplication-cpp-/tailduplicatebaselegacy/#a7c2254f107f71e0200efa186d6b1ee07">anonymous{TailDuplication.cpp}::TailDuplicateBaseLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-tailrecursionelimination-cpp-/tailcallelim/#a47925ada0fb01af49d7ec3b8f448ea65">anonymous{TailRecursionElimination.cpp}::TailCallElim::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-typepromotion-cpp-/typepromotionlegacy/#a2fb471fbcaa1b3ba35fb894cff9bc55d">anonymous{TypePromotion.cpp}::TypePromotionLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-unifyloopexits-cpp-/unifyloopexitslegacypass/#a6e8cc7508e2a0724fa2e3b286138f9ad">anonymous{UnifyLoopExits.cpp}::UnifyLoopExitsLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyloweremscriptenehsjlj-cpp-/webassemblyloweremscriptenehsjlj/#a37781da040b260dd412d4940409a73ac">anonymous{WebAssemblyLowerEmscriptenEHSjLj.cpp}::WebAssemblyLowerEmscriptenEHSjLj::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblymemintrinsicresults-cpp-/webassemblymemintrinsicresults/#a8652a0cd0eac81b30e2fae4c1c0483c0">anonymous{WebAssemblyMemIntrinsicResults.cpp}::WebAssemblyMemIntrinsicResults::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyregcoloring-cpp-/webassemblyregcoloring/#ae22e46e1547c33232ec93271f5333b80">anonymous{WebAssemblyRegColoring.cpp}::WebAssemblyRegColoring::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86avoidstoreforwardingblocks-cpp-/x86avoidsfbpass/#a247afc8fd2ab0e7678848565fed1afc6">anonymous{X86AvoidStoreForwardingBlocks.cpp}::X86AvoidSFBPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86cmovconversion-cpp-/x86cmovconverterpass/#a07b7a8067b7d36ef1cbfb3c9bbff6583">anonymous{X86CmovConversion.cpp}::X86CmovConverterPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fixupbwinsts-cpp-/fixupbwinstpass/#a096bbbc9c6acbaab809a2369153f7545">anonymous{X86FixupBWInsts.cpp}::FixupBWInstPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fixupleas-cpp-/fixupleapass/#a63c5beadd6fb5e08f03bedc34012d700">anonymous{X86FixupLEAs.cpp}::FixupLEAPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86floatingpoint-cpp-/fps/#aea62108993f8b9340a6075e331f77b8c">anonymous{X86FloatingPoint.cpp}::FPS::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86instrinfo-cpp-/ldtlscleanup/#a815d4538b65b224b2851bce510be31b5">anonymous{X86InstrInfo.cpp}::LDTLSCleanup::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loadvalueinjectionloadhardening-cpp-/x86loadvalueinjectionloadhardeningpass/#ad749b69fe5b007dd43501842cd4e7e54">anonymous{X86LoadValueInjectionLoadHardening.cpp}::X86LoadValueInjectionLoadHardeningPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsicslegacypass/#ae7b4a930d529b3c3150aae1f17ebdc88">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsicsLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxtypelegacypass/#a015b9c8ff8717813f33a49593f94c69e">anonymous{X86LowerAMXType.cpp}::X86LowerAMXTypeLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86optimizeleas-cpp-/x86optimizeleapass/#ad1d3aa40393f3b36a3387aa421b08ace">anonymous{X86OptimizeLEAs.cpp}::X86OptimizeLEAPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86padshortfunction-cpp-/padshortfunc/#ae26e2f0582e2b06ee89f695f067c7582">anonymous{X86PadShortFunction.cpp}::PadShortFunc::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86pretileconfig-cpp-/x86pretileconfig/#a8308acd7809a1513f0d5ec058b073376">anonymous{X86PreTileConfig.cpp}::X86PreTileConfig::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86tileconfig-cpp-/x86tileconfig/#a4558428d90159a830030eb03d453a896">anonymous{X86TileConfig.cpp}::X86TileConfig::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a7bdb6c2ba8990a862902b14f958e3430">llvm::AMDGPUAsmPrinter::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudagtodagisellegacy/#a651caf414b8453f19c8db57e6e54df38">llvm::AMDGPUDAGToDAGISelLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/armblockplacement/#a36b58733e95f9deecf66046e2225981b">llvm::ARMBlockPlacement::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a83d7606b4830b8a51e2b3e12bf83632a">llvm::AsmPrinter::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfowrapperpass/#a579d94f1352d6cd8f75f163611370eaa">llvm::BlockFrequencyInfoWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfowrapperpass/#a398c57492156d37f18c5f633ab737624">llvm::BranchProbabilityInfoWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/breakfalsedeps/#a19ddb6c23028cd28bd1a8af5ce87d7c0">llvm::BreakFalseDeps::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphsccpass/#a6cc67c5a27b53bc940d292c0aeb6aba3">llvm::CallGraphSCCPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/dominancefrontierwrapperpass/#aadf918d033a8cf2044193a772167c4b7">llvm::DominanceFrontierWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/dotgraphtraitsmoduleprinterwrapperpass/#a8d6349c94f5cc780a5012a7ea0c4cf65">llvm::DOTGraphTraitsModulePrinterWrapperPass&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/dotgraphtraitsmoduleviewerwrapperpass/#a77af4b66b182e5bfd7259af5e3bcab4b">llvm::DOTGraphTraitsModuleViewerWrapperPass&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/dotgraphtraitsprinterwrapperpass/#aa02c07be447c35d11d0e51b8227abf39">llvm::DOTGraphTraitsPrinterWrapperPass&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/dotgraphtraitsviewerwrapperpass/#aa53bd38cae43bd17c1a4bf54a4be7573">llvm::DOTGraphTraitsViewerWrapperPass&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/executiondomainfix/#a101879a381eb818b929145a3354575b8">llvm::ExecutionDomainFix::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/llvm/gcnregpressureprinter/#a09fac16a8dbd49b56f447fb67c25a7f6">llvm::GCNRegPressurePrinter::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalsaawrapperpass/#a4b41f1cc377f82f71a9ec4bc098bb51d">llvm::GlobalsAAWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/gvn/gvnlegacypass/#a4fbb957c41dca25995c37de1d627cba9">llvm::gvn::GVNLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncombiningpass/#a5acf47fe333b314ccdb4c0a26f39db97">llvm::InstructionCombiningPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/instructionselect/#a2e38abc4ce9e5203c25ee22862ec012c">llvm::InstructionSelect::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/irtranslator/#aaafe4f214c3f8bae83b25c2c1a476c63">llvm::IRTranslator::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/ivuserswrapperpass/#a2a6e37f929fea8da36f9d521ae9b7b70">llvm::IVUsersWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/lazymachineblockfrequencyinfopass/#a4baa9cde9ae3aae6350176fa7babd486">llvm::LazyMachineBlockFrequencyInfoPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfowrapperpass/#a88df80fe534b444c6c3a4f86af2a6e29">llvm::LazyValueInfoWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizer/#a68852b9eac9877f212aaf4dd687756cb">llvm::Legalizer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/loadstoreopt/#a2d9b6f1892dc9fc078273cf43fe05e0e">llvm::LoadStoreOpt::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/localizer/#a0f9298248f028bcd2339d3b057b94b9b">llvm::Localizer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfowrapperpass/#a0b4c24a0a443b66c32862e27f2465435">llvm::MachineBlockFrequencyInfoWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/machinedominancefrontier/#a15b4c7bc0355aff1097b39ec564024bb">llvm::MachineDominanceFrontier::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a864fd57b4304ef933b3281d0ef85a88e">llvm::MachineFunctionPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/machineloopinfowrapperpass/#afaa4271266208faad34d94dbd46a0960">llvm::MachineLoopInfoWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkemitterpass/#ac0cb9698e491946d2cf46481400a8be9">llvm::MachineOptimizationRemarkEmitterPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/machinepipeliner/#a2d903deabefad32494df9e3b54667d4d">llvm::MachinePipeliner::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregioninfopass/#a138a7223339102ce9302bbe172ad77e8">llvm::MachineRegionInfoPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/machinetracemetricswrapperpass/#a403a5f3fc736cb3dfd9027e13ee06ba3">llvm::MachineTraceMetricsWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependencewrapperpass/#a69de200b873b4a8db94ace6a23d48902">llvm::MemoryDependenceWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/mipssedagtodagisellegacy/#a227e431ba575d1ef75fd46c006a11b09">llvm::MipsSEDAGToDAGISelLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindexwrapperpass/#a2ed39a7e690b34efc20b0ca087eae9fe">llvm::ModuleSummaryIndexWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxasmprinter/#ad83d673ef5c2132ede29c1ecf12edbdb">llvm::NVPTXAsmPrinter::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitterwrapperpass/#a44f11b80f077d6ebcac565cdef537011">llvm::OptimizationRemarkEmitterWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/ragreedy/#aec26bf822b32b653438f2c81d8a220a2">llvm::RAGreedy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocscoring/#a53ef8003044b0180da48f67a14d7b499">llvm::RegAllocScoring::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#a9a6d36010e8ada5ee58eeda765414a89">llvm::RegBankSelect::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/regioninfopass/#ad510ccd391f3fe3ea27847ab0ed19128">llvm::RegionInfoPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/regtomemwrapperpass/#a0be1bffebb870699c735d0cb25ca58ac">llvm::RegToMemWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/llvm/replacewithvecliblegacy/#a3f441f0bb1565ba024c12d645511b53e">llvm::ReplaceWithVeclibLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaawrapperpass/#a32058631091d870731e84c6560df00ed">llvm::SCEVAAWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisellegacy/#a77e4cdd5d33f676fb695a8204f7b70ff">llvm::SelectionDAGISelLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvconvergenceregionanalysiswrapperpass/#a2e30d1d18cc19cd57ef656bdcd7f1af4">llvm::SPIRVConvergenceRegionAnalysisWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvmergeregionexittargets/#a2162395b97baa410f6b5a0dd6b160c12">llvm::SPIRVMergeRegionExitTargets::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvstructurizer/#a0861553af62de2a79f4a9abecc92b3bb">llvm::SPIRVStructurizer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/stackprotector/#a12935cfbb9f5f549b39564e54ad1d816">llvm::StackProtector::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/stacksafetyglobalinfowrapperpass/#ad9b2c5ee714836c1882885e67cde2560">llvm::StackSafetyGlobalInfoWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyexceptioninfo/#a486fb725db438a958960d6c37d6b7d99">llvm::WebAssemblyExceptionInfo::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/siannotatecontrolflowlegacy/#aee9d51ef08a7d3163b2f1601fdaa94a5">SIAnnotateControlFlowLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/siloweri1copieslegacy/#a9e28afb909e82dbc71cb02be08e5cd18">SILowerI1CopiesLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/staticdatasplitter/#a48f7d5a8f72495d4935141353576299b">StaticDataSplitter::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92caae34bfacc63bda0f23d5d005a89e">llvm::getLoopAnalysisUsage</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-cpp/#acb4ccb1e3e3e40a5db92d467a97369c6">INITIALIZE_PASS</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/mlregallocevictadvisor-cpp/#a4035cde766164dedab4604c02b29e045">INITIALIZE_PASS</a>.</p>

</div>
</div>

### addRequiredID() {#a053677ebc731b47a534f841b11b5cf0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisUsage &amp; AnalysisUsage::addRequiredID (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Add the specified <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> to the required set of the usage info for a pass.</p>


<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>, definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a>.</p>


<p>Referenced by <a href="#ae0adcccca08fb686c9ce00f9397b660c">addRequired</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonloopidiomrecognition-cpp-/hexagonloopidiomrecognizelegacypass/#a72a353211e73685a259ed17f21bfcd4f">anonymous{HexagonLoopIdiomRecognition.cpp}::HexagonLoopIdiomRecognizeLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorloopcarriedreuse-cpp-/hexagonvectorloopcarriedreuselegacypass/#aaa01e8caee7e8d84bd3a0311252cbfba">anonymous{HexagonVectorLoopCarriedReuse.cpp}::HexagonVectorLoopCarriedReuseLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopdataprefetch-cpp-/loopdataprefetchlegacypass/#a1d8d70074433585c3dab03ab0e3da5ab">anonymous{LoopDataPrefetch.cpp}::LoopDataPrefetchLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopextractor-cpp-/loopextractorlegacypass/#ab2e454c9a32974fd2c4f6f3cd70ab231">anonymous{LoopExtractor.cpp}::LoopExtractorLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#a4d13f3859751e81e68b91336687b574d">anonymous{RegAllocBasic.cpp}::RABasic::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocpbqp-cpp-/regallocpbqp/#a71020ccbea35e322e29b2b44608289af">anonymous{RegAllocPBQP.cpp}::RegAllocPBQP::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-safepointirverifier-cpp-/safepointirverifier/#ae76cdbccee1d4895823600a0135d5cab">anonymous{SafepointIRVerifier.cpp}::SafepointIRVerifier::getAnalysisUsage</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92caae34bfacc63bda0f23d5d005a89e">llvm::getLoopAnalysisUsage</a>.</p>

</div>
</div>

### addRequiredID() {#a5db2bbeaefe8bec69aeaaa53707ed560}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisUsage &amp; AnalysisUsage::addRequiredID (char &amp; ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>, definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a>.</p>

</div>
</div>

### addRequiredTransitive() {#afd8af3487564621ceeb41c2838c4469e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class PassClass&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisUsage &amp; llvm::AnalysisUsage::addRequiredTransitive ()</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>.</p>


<p>References <a href="#a39c64174b9b56285668f8fc3602c868a">addRequiredTransitiveID</a> and <a href="#aa371d2d081bd5a108b861090ac8f8cf7">AnalysisUsage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aaresultswrapperpass/#abcb7db4473bd2451956a9b070a3dc9bf">llvm::AAResultsWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/basicaawrapperpass/#a85c4a3f5d899acf70cedc62e6c6e1bc7">llvm::BasicAAWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/dependenceanalysiswrapperpass/#a19a49a9e878953637bc1532c2cb79000">llvm::DependenceAnalysisWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/shaderflagsanalysiswrapper/#a1aefe709e54965ad86ee26fd0a353e61">llvm::dxil::ShaderFlagsAnalysisWrapper::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilresourcebindingwrapperpass/#a45a05495a4fe8461285b363d7b50cc07">llvm::DXILResourceBindingWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyblockfrequencyinfopass/#ac268a272ef00fe938673b99e143edcae">llvm::LazyBlockFrequencyInfoPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/lazybranchprobabilityinfopass/#a3346ab2912dff435990fec3deb0dda4e">llvm::LazyBranchProbabilityInfoPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalswrapperpass/#accef3521ae76625b599b616c6f2b5fbf">llvm::LiveIntervalsWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfowrapperpass/#a715603b0503ecf76d50bebba1820cc49">llvm::LoopInfoWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependencewrapperpass/#a69de200b873b4a8db94ace6a23d48902">llvm::MemoryDependenceWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssawrapperpass/#ab9923984766bd759aab387db40458ceb">llvm::MemorySSAWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/regioninfopass/#ad510ccd391f3fe3ea27847ab0ed19128">llvm::RegionInfoPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolutionwrapperpass/#a014973e92bb76ade4c63ea2765c7b882">llvm::ScalarEvolutionWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/stacksafetyinfowrapperpass/#a94bec38d78b1f49fdeb91b1f96783bf8">llvm::StackSafetyInfoWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyblockfrequencyinfopass/#a8969b22606511eb0e2b2e028a3c0f332">llvm::LazyBlockFrequencyInfoPass::getLazyBFIAnalysisUsage</a> and <a href="/web-llvm/docs/api/classes/llvm/lazybranchprobabilityinfopass/#ae5b21e8d080e9e008453b0a52dd865b5">llvm::LazyBranchProbabilityInfoPass::getLazyBPIAnalysisUsage</a>.</p>

</div>
</div>

### addRequiredTransitiveID() {#a39c64174b9b56285668f8fc3602c868a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisUsage &amp; AnalysisUsage::addRequiredTransitiveID (char &amp; ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>, definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a>.</p>


<p>Referenced by <a href="#afd8af3487564621ceeb41c2838c4469e">addRequiredTransitive</a> and <a href="/web-llvm/docs/api/classes/llvm/liveintervalswrapperpass/#accef3521ae76625b599b616c6f2b5fbf">llvm::LiveIntervalsWrapperPass::getAnalysisUsage</a>.</p>

</div>
</div>

### addUsedIfAvailable() {#aaeddaf79040291b6f3e0db57943aac39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class PassClass&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisUsage &amp; llvm::AnalysisUsage::addUsedIfAvailable ()</td>
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

<p>Add the specified <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> class to the set of analyses used by this pass.</p>

<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>.</p>


<p>Reference <a href="#aa371d2d081bd5a108b861090ac8f8cf7">AnalysisUsage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-basicblocksections-cpp-/basicblocksections/#af2caf856b1f9546f0855b33391857973">anonymous{BasicBlockSections.cpp}::BasicBlockSections::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/codegenpreparelegacypass/#a4e6eaa6981139214f5c249f3b365e2a3">anonymous{CodeGenPrepare.cpp}::CodeGenPrepareLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-globalmergefunctions-cpp-/globalmergefuncpasswrapper/#a8ef3651109e98ef564491e2c89febed6">anonymous{GlobalMergeFunctions.cpp}::GlobalMergeFuncPassWrapper::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopextractor-cpp-/loopextractorlegacypass/#ab2e454c9a32974fd2c4f6f3cd70ab231">anonymous{LoopExtractor.cpp}::LoopExtractorLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-machinefunctionprinterpass-cpp-/machinefunctionprinterpass/#a9c20c030f23f043969372d085e3dcff1">anonymous{MachineFunctionPrinterPass.cpp}::MachineFunctionPrinterPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinefunctionsplitter-cpp-/machinefunctionsplitter/#ab0ffdd6a9a1d23949f793e83a0ce7cec">anonymous{MachineFunctionSplitter.cpp}::MachineFunctionSplitter::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a91bb84179044c30641f066d505ac80cc">anonymous{MachineOutliner.cpp}::MachineOutliner::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifierlegacypass/#a8bf9633b31eab4615963eab9c234097d">anonymous{MachineVerifier.cpp}::MachineVerifierLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/riscvinsertvsetvli/#a18d6edb1a33bc0f9a4cfd44799f58a84">anonymous{RISCVInsertVSETVLI.cpp}::RISCVInsertVSETVLI::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a51964e59ed1cde09d8e6d578e9c46d83">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-silowercontrolflow-cpp-/silowercontrolflowlegacy/#a806a4ecc192e76abda8a370e6507418f">anonymous{SILowerControlFlow.cpp}::SILowerControlFlowLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-silowerwwmcopies-cpp-/silowerwwmcopieslegacy/#ae4fe0e77240235e99d707dd0c9ac9bbf">anonymous{SILowerWWMCopies.cpp}::SILowerWWMCopiesLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-twoaddressinstructionpass-cpp-/twoaddressinstructionlegacypass/#acd910999edf78b013dcbbfa6f2ef0353">anonymous{TwoAddressInstructionPass.cpp}::TwoAddressInstructionLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86flagscopylowering-cpp-/x86flagscopyloweringpass/#a7f4aa63016da5d33c9eff538e57c491c">anonymous{X86FlagsCopyLowering.cpp}::X86FlagsCopyLoweringPass::getAnalysisUsage</a> and <a href="/web-llvm/docs/api/classes/llvm/aaresultswrapperpass/#abcb7db4473bd2451956a9b070a3dc9bf">llvm::AAResultsWrapperPass::getAnalysisUsage</a>.</p>

</div>
</div>

### addUsedIfAvailableID() {#a6e3b2899057c9d61b73d239680b6cada}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisUsage &amp; llvm::AnalysisUsage::addUsedIfAvailableID (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * ID)</td>
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




<p>Add the specified <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> to the set of analyses used by this pass if they are available..</p>


<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>.</p>


<p>Reference <a href="#aa371d2d081bd5a108b861090ac8f8cf7">AnalysisUsage</a>.</p>

</div>
</div>

### addUsedIfAvailableID() {#a9eb4c96bc9f31369564e5061a0137bb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisUsage &amp; llvm::AnalysisUsage::addUsedIfAvailableID (char &amp; ID)</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>.</p>


<p>Reference <a href="#aa371d2d081bd5a108b861090ac8f8cf7">AnalysisUsage</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addPreserved() {#a8d75c71bee6e69f3d97990380abf728c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisUsage &amp; AnalysisUsage::addPreserved (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Arg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> with the specified argument string to the set of analyses preserved by this pass.</p>


<p>If no such <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> exists, do nothing. This can be useful when a pass is trivially preserved, but may not be linked in. Be careful about spelling!</p>


<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>, definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a>.</p>

</div>
</div>

### getPreservedSet() {#af9c346823bed8d8787ced3ce5b0a2ced}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VectorType &amp; llvm::AnalysisUsage::getPreservedSet ()</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#adfe9cc105a283f4d7e4e56c6d4440adb">llvm::PMDataManager::dumpPreservedSet</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#aa2fd2b9e450d0a3dc5255cc52151b7ff">llvm::PMDataManager::preserveHigherLevelAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#af740891e192aa63a0fbbfe317301cbdb">llvm::PMDataManager::removeNotPreservedAnalysis</a> and <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a86a4b032c64ea61c59d12929a76c9833">llvm::PMDataManager::verifyPreservedAnalysis</a>.</p>

</div>
</div>

### getPreservesAll() {#af25c3e35aa8152adb82963b80be929c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AnalysisUsage::getPreservesAll ()</td>
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

<p>Determine whether a pass said it does not transform its input at all.</p>

<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#aa2fd2b9e450d0a3dc5255cc52151b7ff">llvm::PMDataManager::preserveHigherLevelAnalysis</a> and <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#af740891e192aa63a0fbbfe317301cbdb">llvm::PMDataManager::removeNotPreservedAnalysis</a>.</p>

</div>
</div>

### getRequiredSet() {#a299caaa13ef3566bddb9781064aebdb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VectorType &amp; llvm::AnalysisUsage::getRequiredSet ()</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#ad3081121743797ac69560ffa5f381ced">llvm::PMDataManager::collectRequiredAndUsedAnalyses</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a799e97f6f38435a58b8ecf6a85eb7399">llvm::PMDataManager::dumpRequiredSet</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a813e1d4b6102a11cad9963778f889d4d">llvm::PMDataManager::initializeAnalysisImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#a5fb719fc8062d116b93091d9c9addd43">llvm::PMTopLevelManager::schedulePass</a>.</p>

</div>
</div>

### getRequiredTransitiveSet() {#aab8bb94b2d54bff44ec50eade145bd08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VectorType &amp; llvm::AnalysisUsage::getRequiredTransitiveSet ()</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#a5eab64f06a4196bd59b9b19251eefddb">llvm::PMTopLevelManager::setLastUser</a>.</p>

</div>
</div>

### getUsedSet() {#ad0364d79e9c78f6781cbe243737f5908}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VectorType &amp; llvm::AnalysisUsage::getUsedSet ()</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#ad3081121743797ac69560ffa5f381ced">llvm::PMDataManager::collectRequiredAndUsedAnalyses</a> and <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#af71955a48208ff25a6c8b5f6f2890417">llvm::PMDataManager::dumpUsedSet</a>.</p>

</div>
</div>

### setPreservesAll() {#af22b06a6a4f9df80454071685a0d6a02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AnalysisUsage::setPreservesAll ()</td>
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

<p>Set by analyses that do not transform their input at all.</p>

<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/amdgpuannotateuniformvalueslegacy/#a0940e969144d7bb0f8ff60e409b68d9e">AMDGPUAnnotateUniformValuesLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/amdgpulatecodegenpreparelegacy/#a6212af167be4a14e4c75d2cc6963a211">AMDGPULateCodeGenPrepareLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a17d725ff2e1212ba5b883e21e03a8040">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64collectloh-cpp-/aarch64collectloh/#adda581e02a66efe37da98da76ecb3854">anonymous{AArch64CollectLOH.cpp}::AArch64CollectLOH::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64lowerhomogeneousprologepilog-cpp-/aarch64lowerhomogeneousprologepilog/#ac90310a56e9cae1304a02023e8a760ee">anonymous{AArch64LowerHomogeneousPrologEpilog.cpp}::AArch64LowerHomogeneousPrologEpilog::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64postcoalescerpass-cpp-/aarch64postcoalescer/#a5541f5ee801d6b8854f5f78264334b58">anonymous{AArch64PostCoalescerPass.cpp}::AArch64PostCoalescer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpualwaysinlinepass-cpp-/amdgpualwaysinline/#a749b60bd9db9299533fac8a9d1e46430">anonymous{AMDGPUAlwaysInlinePass.cpp}::AMDGPUAlwaysInline::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuannotatekernelfeatures-cpp-/amdgpuannotatekernelfeatures/#aafd88529f6193a278e1c5bb87943eb13">anonymous{AMDGPUAnnotateKernelFeatures.cpp}::AMDGPUAnnotateKernelFeatures::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepare/#a22e75df81a9f4db7a37b45db0c520bb8">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepare::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerkernelarguments-cpp-/amdgpulowerkernelarguments/#ae229b01702efbed872d75427d4cf0405">anonymous{AMDGPULowerKernelArguments.cpp}::AMDGPULowerKernelArguments::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerkernelattributes-cpp-/amdgpulowerkernelattributes/#adc2844f2cf295806e216f87f85230cc2">anonymous{AMDGPULowerKernelAttributes.cpp}::AMDGPULowerKernelAttributes::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpumarklastscratchload-cpp-/amdgpumarklastscratchload/#a55615e9a70e295c32f8387234c5ee722">anonymous{AMDGPUMarkLastScratchLoad.cpp}::AMDGPUMarkLastScratchLoad::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuperfhintanalysis-cpp-/amdgpuperfhintanalysislegacy/#a5bd508d0aa5b1097b5dccf7a510378d2">anonymous{AMDGPUPerfHintAnalysis.cpp}::AMDGPUPerfHintAnalysisLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpupromotekernelarguments-cpp-/amdgpupromotekernelarguments/#aae3cceff303ca5502f751e40b4a2aa16">anonymous{AMDGPUPromoteKernelArguments.cpp}::AMDGPUPromoteKernelArguments::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpureservewwmregs-cpp-/amdgpureservewwmregs/#a759c31f47f7d345689094fe7bc64b76b">anonymous{AMDGPUReserveWWMRegs.cpp}::AMDGPUReserveWWMRegs::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-basicblocksections-cpp-/basicblocksections/#af2caf856b1f9546f0855b33391857973">anonymous{BasicBlockSections.cpp}::BasicBlockSections::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriterpass-cpp-/writebitcodepass/#a5640e06d444a1564388aca39019de10f">anonymous{BitcodeWriterPass.cpp}::WriteBitcodePass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-callgraphsccpass-cpp-/printcallgraphpass/#a9738492e9f76329e7cb119273957e576">anonymous{CallGraphSCCPass.cpp}::PrintCallGraphPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-callprinter-cpp-/callgraphdotprinter/#ab8495a00f0c8d8dc82aa00ea515dc692">anonymous{CallPrinter.cpp}::CallGraphDOTPrinter::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-callprinter-cpp-/callgraphviewer/#acdb259f5a825cd4226f7ddb29f94c869">anonymous{CallPrinter.cpp}::CallGraphViewer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfiinstrinserter-cpp-/cfiinstrinserter/#a401fddeacac222c9da6d8f079df1ae73">anonymous{CFIInstrInserter.cpp}::CFIInstrInserter::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/checkdebugifyfunctionpass/#a6cd1a8e209b645dd2cb00cd825d54f1e">anonymous{Debugify.cpp}::CheckDebugifyFunctionPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/checkdebugifymodulepass/#a965322cec67de05385691c2fbb9709d5">anonymous{Debugify.cpp}::CheckDebugifyModulePass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/debugifyfunctionpass/#a03bae1274a3327c829f25255e07b7fff">anonymous{Debugify.cpp}::DebugifyFunctionPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/debugifymodulepass/#a9dfc374b2f8dd1e966126043b5dc862e">anonymous{Debugify.cpp}::DebugifyModulePass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxcontainerglobals-cpp-/dxcontainerglobals/#a5e5375542fbfad721eeef4fc1ec31563">anonymous{DXContainerGlobals.cpp}::DXContainerGlobals::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilprettyprinter-cpp-/dxilprettyprinterlegacy/#a91b0e2d13da7d7eeaf54b8702e459dac">anonymous{DXILPrettyPrinter.cpp}::DXILPrettyPrinterLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilwriterpass-cpp-/embeddxilpass/#a3ff3a3b3d9d46d5eb4e6ec905043134e">anonymous{DXILWriterPass.cpp}::EmbedDXILPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilwriterpass-cpp-/writedxilpass/#ac33368dd8de8a054afce2a08054282db">anonymous{DXILWriterPass.cpp}::WriteDXILPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnnsareassign-cpp-/gcnnsareassign/#ac14efeec9a3e2cddd316e0ec3ad74c79">anonymous{GCNNSAReassign.cpp}::GCNNSAReassign::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnpreralongbranchreg-cpp-/gcnpreralongbranchreg/#afb6ba3c17c92b95011fc41ab13d42bfd">anonymous{GCNPreRALongBranchReg.cpp}::GCNPreRALongBranchReg::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnpreraoptimizations-cpp-/gcnpreraoptimizations/#a21808667d9b3c477d4ade30180851fec">anonymous{GCNPreRAOptimizations.cpp}::GCNPreRAOptimizations::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcrootlowering-cpp-/gcmachinecodeanalysis/#a9539c0e4d2cea8bc107ed991bb50b777">anonymous{GCRootLowering.cpp}::GCMachineCodeAnalysis::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-globalmergefunctions-cpp-/globalmergefuncpasswrapper/#a8ef3651109e98ef564491e2c89febed6">anonymous{GlobalMergeFunctions.cpp}::GlobalMergeFuncPassWrapper::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonoptaddrmode-cpp-/hexagonoptaddrmode/#afef5504e71fa5e9ee7699f60446d0115">anonymous{HexagonOptAddrMode.cpp}::HexagonOptAddrMode::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonrdfopt-cpp-/hexagonrdfopt/#aaf2555430b493cb574fc002d72c827f1">anonymous{HexagonRDFOpt.cpp}::HexagonRDFOpt::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagontfrcleanup-cpp-/hexagontfrcleanup/#a604484cae36402d521e7028ee1d6dac3">anonymous{HexagonTfrCleanup.cpp}::HexagonTfrCleanup::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-irprintingpasses-cpp-/printfunctionpasswrapper/#afa38ecf931353de58771fc18d7144af8">anonymous{IRPrintingPasses.cpp}::PrintFunctionPassWrapper::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-irprintingpasses-cpp-/printmodulepasswrapper/#aeea45a65b34c284353e78eb795be3acb">anonymous{IRPrintingPasses.cpp}::PrintModulePassWrapper::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-looppass-cpp-/printlooppasswrapper/#a017b44b4b12138980d86c54018d935d7">anonymous{LoopPass.cpp}::PrintLoopPassWrapper::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/machineblockplacementstats/#af6fdd4aa0d9c5af936fea8be657b7c7a">anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacementStats::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-machinecheckdebugify-cpp-/checkdebugmachinemodule/#aa9d0124df2e155e60e441d086e0f0769">anonymous{MachineCheckDebugify.cpp}::CheckDebugMachineModule::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-machinefunctionprinterpass-cpp-/machinefunctionprinterpass/#a9c20c030f23f043969372d085e3dcff1">anonymous{MachineFunctionPrinterPass.cpp}::MachineFunctionPrinterPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a91bb84179044c30641f066d505ac80cc">anonymous{MachineOutliner.cpp}::MachineOutliner::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifierlegacypass/#a8bf9633b31eab4615963eab9c234097d">anonymous{MachineVerifier.cpp}::MachineVerifierLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-mirprintingpass-cpp-/mirprintingpass/#a2061e381fbe8d27f4605655122d12896">anonymous{MIRPrintingPass.cpp}::MIRPrintingPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-placesafepoints-cpp-/placebackedgesafepointslegacypass/#acdbf6d8b413ffb81652cf8c434ee423a">anonymous{PlaceSafepoints.cpp}::PlaceBackedgeSafepointsLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-pseudoprobeinserter-cpp-/pseudoprobeinserter/#a5f9ac029b6cb53c20f4048100a4661ee">anonymous{PseudoProbeInserter.cpp}::PseudoProbeInserter::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-regionpass-cpp-/printregionpass/#a13ec83cd99b5c69aab4f793532ff2cd1">anonymous{RegionPass.cpp}::PrintRegionPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-regusageinfocollector-cpp-/regusageinfocollectorlegacy/#ad487cac993b0d3201079cd70c21279c8">anonymous{RegUsageInfoCollector.cpp}::RegUsageInfoCollectorLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-regusageinfopropagate-cpp-/regusageinfopropagationlegacy/#a10a8c6e435b643810f3886c69822dbf2">anonymous{RegUsageInfoPropagate.cpp}::RegUsageInfoPropagationLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-safepointirverifier-cpp-/safepointirverifier/#ae76cdbccee1d4895823600a0135d5cab">anonymous{SafepointIRVerifier.cpp}::SafepointIRVerifier::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-shrinkwrap-cpp-/shrinkwrap/#a269884a1a9c68cf90e38daf6a0110bc4">anonymous{ShrinkWrap.cpp}::ShrinkWrap::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixvgprcopies-cpp-/sifixvgprcopieslegacy/#ad01b7a48f7bbbe84057c887429a69839">anonymous{SIFixVGPRCopies.cpp}::SIFixVGPRCopiesLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-siformmemoryclauses-cpp-/siformmemoryclauses/#a7db6582b867e122bd23862020ee89628">anonymous{SIFormMemoryClauses.cpp}::SIFormMemoryClauses::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-silowersgprspills-cpp-/silowersgprspillslegacy/#adcfc087805876f59c13dc6f1796b6554">anonymous{SILowerSGPRSpills.cpp}::SILowerSGPRSpillsLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-silowerwwmcopies-cpp-/silowerwwmcopieslegacy/#ae4fe0e77240235e99d707dd0c9ac9bbf">anonymous{SILowerWWMCopies.cpp}::SILowerWWMCopiesLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizeexecmaskingprera-cpp-/sioptimizeexecmaskingprera/#aea34846856fb7148baa6d82e06c246b4">anonymous{SIOptimizeExecMaskingPreRA.cpp}::SIOptimizeExecMaskingPreRA::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipostrabundler-cpp-/sipostrabundler/#a534884966e628dce25d2894c82eec18c">anonymous{SIPostRABundler.cpp}::SIPostRABundler::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipreallocatewwmregs-cpp-/sipreallocatewwmregslegacy/#afc84aba53e7ecaa959484476e87ca761">anonymous{SIPreAllocateWWMRegs.cpp}::SIPreAllocateWWMRegsLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-stackframelayoutanalysispass-cpp-/stackframelayoutanalysispass/#a8e0327390d0eda5d61ba53f7171c4832">anonymous{StackFrameLayoutAnalysisPass.cpp}::StackFrameLayoutAnalysisPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-stackmaplivenessanalysis-cpp-/stackmapliveness/#a99990daadc9889fd551ddaaedf1b7fae">anonymous{StackMapLivenessAnalysis.cpp}::StackMapLiveness::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-verifier-cpp-/verifierlegacypass/#a8faeb767a099e954fbf70948b0a60621">anonymous{Verifier.cpp}::VerifierLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fasttileconfig-cpp-/x86fasttileconfig/#a2921503b35e21d57b7d96675fbf00e0c">anonymous{X86FastTileConfig.cpp}::X86FastTileConfig::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86pretileconfig-cpp-/x86pretileconfig/#a8308acd7809a1513f0d5ec058b073376">anonymous{X86PreTileConfig.cpp}::X86PreTileConfig::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86tileconfig-cpp-/x86tileconfig/#a4558428d90159a830030eb03d453a896">anonymous{X86TileConfig.cpp}::X86TileConfig::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresultswrapperpass/#abcb7db4473bd2451956a9b070a3dc9bf">llvm::AAResultsWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuaawrapperpass/#aae3842f5ebd07a9a43bded7ec0e95d35">llvm::AMDGPUAAWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuargumentusageinfo/#a28f751e3d3a288ca82633b729856c103">llvm::AMDGPUArgumentUsageInfo::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpuresourceusageanalysis/#a16ddf3cda8c18103f9e328509ce9f40c">llvm::AMDGPUResourceUsageAnalysis::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a83d7606b4830b8a51e2b3e12bf83632a">llvm::AsmPrinter::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/assignmenttrackinganalysis/#a4059c0b8932bd5d3ba52decec3f63123">llvm::AssignmentTrackingAnalysis::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/basicaawrapperpass/#a85c4a3f5d899acf70cedc62e6c6e1bc7">llvm::BasicAAWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfowrapperpass/#a579d94f1352d6cd8f75f163611370eaa">llvm::BlockFrequencyInfoWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfowrapperpass/#a398c57492156d37f18c5f633ab737624">llvm::BranchProbabilityInfoWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/breakfalsedeps/#a19ddb6c23028cd28bd1a8af5ce87d7c0">llvm::BreakFalseDeps::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphwrapperpass/#a4bf057166fbb8c0244ad73b8a99b3aac">llvm::CallGraphWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/cfifixup/#a21a81212850b124689f4a354520c7d67">llvm::CFIFixup::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/dependenceanalysiswrapperpass/#a19a49a9e878953637bc1532c2cb79000">llvm::DependenceAnalysisWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/dominancefrontierwrapperpass/#aadf918d033a8cf2044193a772167c4b7">llvm::DominanceFrontierWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreewrapperpass/#a84707f0e64e6bbb735382002c5e3a467">llvm::DominatorTreeWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/dotgraphtraitsmoduleprinterwrapperpass/#a8d6349c94f5cc780a5012a7ea0c4cf65">llvm::DOTGraphTraitsModulePrinterWrapperPass&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/dotgraphtraitsmoduleviewerwrapperpass/#a77af4b66b182e5bfd7259af5e3bcab4b">llvm::DOTGraphTraitsModuleViewerWrapperPass&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/dotgraphtraitsprinterwrapperpass/#aa02c07be447c35d11d0e51b8227abf39">llvm::DOTGraphTraitsPrinterWrapperPass&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/dotgraphtraitsviewerwrapperpass/#aa53bd38cae43bd17c1a4bf54a4be7573">llvm::DOTGraphTraitsViewerWrapperPass&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/dummycgsccpass/#afbe4e434241cffa8dcc09af5c6d3daf1">llvm::DummyCGSCCPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/shaderflagsanalysiswrapper/#a1aefe709e54965ad86ee26fd0a353e61">llvm::dxil::ShaderFlagsAnalysisWrapper::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilmetadataanalysiswrapperpass/#a38a340dd3903748b4b0ac7a0d18aad7b">llvm::DXILMetadataAnalysisWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilresourcebindingwrapperpass/#a45a05495a4fe8461285b363d7b50cc07">llvm::DXILResourceBindingWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilresourcemdwrapper/#a2418a7db96d992f63f1253c7a3e6b77e">llvm::DXILResourceMDWrapper::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/executiondomainfix/#a101879a381eb818b929145a3354575b8">llvm::ExecutionDomainFix::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/llvm/externalaawrapperpass/#a07ab00406ef42a0a69e296f81cc02a4e">llvm::ExternalAAWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/llvm/gcnregpressureprinter/#a09fac16a8dbd49b56f447fb67c25a7f6">llvm::GCNRegPressurePrinter::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/giselcseanalysiswrapperpass/#a80bd1a58682fb0185a69986b2e46da6a">llvm::GISelCSEAnalysisWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbitsanalysis/#a820ff32b223ab9b5fcf5e122365f3e3f">llvm::GISelKnownBitsAnalysis::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalsaawrapperpass/#a4b41f1cc377f82f71a9ec4bc098bb51d">llvm::GlobalsAAWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/immutablemodulesummaryindexwrapperpass/#af9f04be0eabac94d3e70839a0dafd355">llvm::ImmutableModuleSummaryIndexWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/irsimilarityidentifierwrapperpass/#ac8c07be8e3ab623bc681b30b9ef54bde">llvm::IRSimilarityIdentifierWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/ivuserswrapperpass/#a2a6e37f929fea8da36f9d521ae9b7b70">llvm::IVUsersWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyblockfrequencyinfopass/#ac268a272ef00fe938673b99e143edcae">llvm::LazyBlockFrequencyInfoPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/lazybranchprobabilityinfopass/#a3346ab2912dff435990fec3deb0dda4e">llvm::LazyBranchProbabilityInfoPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/lazymachineblockfrequencyinfopass/#a4baa9cde9ae3aae6350176fa7babd486">llvm::LazyMachineBlockFrequencyInfoPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfowrapperpass/#a88df80fe534b444c6c3a4f86af2a6e29">llvm::LazyValueInfoWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/llvm/lcssaverificationpass/#ac724a8f53b6f75906d991602c8d1f0a2">llvm::LCSSAVerificationPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/loadstoreopt/#a2d9b6f1892dc9fc078273cf43fe05e0e">llvm::LoadStoreOpt::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfowrapperpass/#a715603b0503ecf76d50bebba1820cc49">llvm::LoopInfoWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfowrapperpass/#a0b4c24a0a443b66c32862e27f2465435">llvm::MachineBlockFrequencyInfoWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebranchprobabilityinfowrapperpass/#ab8144e6887548fba895809b7009a5bb5">llvm::MachineBranchProbabilityInfoWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/machinedominancefrontier/#a15b4c7bc0355aff1097b39ec564024bb">llvm::MachineDominanceFrontier::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/machinedominatortreewrapperpass/#a066eec47bcb29d88f49905ef05daa68f">llvm::MachineDominatorTreeWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/machineloopinfowrapperpass/#afaa4271266208faad34d94dbd46a0960">llvm::MachineLoopInfoWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkemitterpass/#ac0cb9698e491946d2cf46481400a8be9">llvm::MachineOptimizationRemarkEmitterPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/machinepostdominatortreewrapperpass/#af5427ad4a8cc065f90e80adf7cc4c5d2">llvm::MachinePostDominatorTreeWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregioninfopass/#a138a7223339102ce9302bbe172ad77e8">llvm::MachineRegionInfoPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/machinetracemetricswrapperpass/#a403a5f3fc736cb3dfd9027e13ee06ba3">llvm::MachineTraceMetricsWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependencewrapperpass/#a69de200b873b4a8db94ace6a23d48902">llvm::MemoryDependenceWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssawrapperpass/#ab9923984766bd759aab387db40458ceb">llvm::MemorySSAWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindexwrapperpass/#a2ed39a7e690b34efc20b0ca087eae9fe">llvm::ModuleSummaryIndexWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxaawrapperpass/#ac24a90ae169149c05383a12929fa150e">llvm::NVPTXAAWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitterwrapperpass/#a44f11b80f077d6ebcac565cdef537011">llvm::OptimizationRemarkEmitterWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/phivalueswrapperpass/#ad03f7cfb05488dfa41c64d829ca00361">llvm::PhiValuesWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/llvm/postdominatortreewrapperpass/#aef6149888751bd6762249c304fa760a9">llvm::PostDominatorTreeWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfowrapperpass/#a3c443df4c0bb348bde78fcf4a1c5b951">llvm::ProfileSummaryInfoWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis/#a55b5dbb2a8d0bc48a7867741fb7bdebd">llvm::ReachingDefAnalysis::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocevictionadvisoranalysis/#a005390fe88a690353da791886d6c1dcd">llvm::RegAllocEvictionAdvisorAnalysis::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocpriorityadvisoranalysis/#a8349e67bcda852a915644c9feb681d1e">llvm::RegAllocPriorityAdvisorAnalysis::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocscoring/#a53ef8003044b0180da48f67a14d7b499">llvm::RegAllocScoring::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/regioninfopass/#ad510ccd391f3fe3ea27847ab0ed19128">llvm::RegionInfoPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/regtomemwrapperpass/#a0be1bffebb870699c735d0cb25ca58ac">llvm::RegToMemWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolutionwrapperpass/#a014973e92bb76ade4c63ea2765c7b882">llvm::ScalarEvolutionWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaawrapperpass/#a32058631091d870731e84c6560df00ed">llvm::SCEVAAWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/scopednoaliasaawrapperpass/#ac30e57b586d7447a1d1903c066981182">llvm::ScopedNoAliasAAWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvconvergenceregionanalysiswrapperpass/#a2e30d1d18cc19cd57ef656bdcd7f1af4">llvm::SPIRVConvergenceRegionAnalysisWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/stacksafetyglobalinfowrapperpass/#ad9b2c5ee714836c1882885e67cde2560">llvm::StackSafetyGlobalInfoWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/stacksafetyinfowrapperpass/#a94bec38d78b1f49fdeb91b1f96783bf8">llvm::StackSafetyInfoWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/typebasedaawrapperpass/#af09271b67d65353fbf683e17d023f51e">llvm::TypeBasedAAWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmapwrapperlegacy/#ae6b2a92b14ba5fe23649b6e8c78ee008">llvm::VirtRegMapWrapperLegacy::getAnalysisUsage</a> and <a href="/web-llvm/docs/api/classes/llvm/webassemblyexceptioninfo/#a486fb725db438a958960d6c37d6b7d99">llvm::WebAssemblyExceptionInfo::getAnalysisUsage</a>.</p>

</div>
</div>

### setPreservesCFG() {#af11a6ebf7ab3c388234cb6d5378439a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AnalysisUsage::setPreservesCFG ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function should be called by the pass, iff they do not:</p>


<ol class="doxyList" type="1">
<li>Add or remove basic blocks from the function</li>
<li>Modify terminator instructions in any way.</li>
</ol>

<p>This function annotates the <a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> info object to say that analyses that only depend on the CFG are preserved by this pass.</p>


<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>, definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64a53fix835769-cpp-/aarch64a53fix835769/#a6c8f59c36d372f7f4d09230b5fa8e284">anonymous{AArch64A53Fix835769.cpp}::AArch64A53Fix835769::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64a57fploadbalancing-cpp-/aarch64a57fploadbalancing/#aa2db0c35a3d950df675b8c432a50b5c5">anonymous{AArch64A57FPLoadBalancing.cpp}::AArch64A57FPLoadBalancing::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64advsimdscalarpass-cpp-/aarch64advsimdscalar/#ae7f5c4d5129a204b95505e6785267e2e">anonymous{AArch64AdvSIMDScalarPass.cpp}::AArch64AdvSIMDScalar::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64cleanuplocaldynamictlspass-cpp-/ldtlscleanup/#a1c8bf8f7dabac34ad685f706dcdf4d68">anonymous{AArch64CleanupLocalDynamicTLSPass.cpp}::LDTLSCleanup::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64deadregisterdefinitionspass-cpp-/aarch64deadregisterdefinitions/#ae3a8a880480618caa4028b981645d977">anonymous{AArch64DeadRegisterDefinitionsPass.cpp}::AArch64DeadRegisterDefinitions::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64falkorhwpffix-cpp-/falkorhwpffix/#a8c2dbb4993bc4963bf1aba0aa5b37177">anonymous{AArch64FalkorHWPFFix.cpp}::FalkorHWPFFix::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#ac55399d94c119f2fe23552670cfe1b26">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64postselectoptimize-cpp-/aarch64postselectoptimize/#abdab7ae0af7e2167213c95ea87397bfb">anonymous{AArch64PostSelectOptimize.cpp}::AArch64PostSelectOptimize::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktaggingprera-cpp-/aarch64stacktaggingprera/#a41e868ca45ea3b66bb4b40b6d238efad">anonymous{AArch64StackTaggingPreRA.cpp}::AArch64StackTaggingPreRA::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuglobaliseldivergencelowering-cpp-/amdgpuglobaliseldivergencelowering/#ae3d7560cc1865d6fd6bbe1c30bf95723">anonymous{AMDGPUGlobalISelDivergenceLowering.cpp}::AMDGPUGlobalISelDivergenceLowering::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/#ab544e1282d5f0b4a4f0bbad08d93446b">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpupromotealloca-cpp-/amdgpupromotealloca/#a862c305aa8da9877b0b1adc40047f85d">anonymous{AMDGPUPromoteAlloca.cpp}::AMDGPUPromoteAlloca::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpupromotealloca-cpp-/amdgpupromoteallocatovector/#aad5855d9b0d61f931ddb2051de0762c6">anonymous{AMDGPUPromoteAlloca.cpp}::AMDGPUPromoteAllocaToVector::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteundefforphi-cpp-/amdgpurewriteundefforphilegacy/#afe2e66ff8c88acacb1fe5c1d7cfca524">anonymous{AMDGPURewriteUndefForPHI.cpp}::AMDGPURewriteUndefForPHILegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-arcoptaddrmode-cpp-/arcoptaddrmode/#aa224aadf7ce53e6b8441944cc88ec676">anonymous{ARCOptAddrMode.cpp}::ARCOptAddrMode::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-armfixcortexa57aes1742098pass-cpp-/armfixcortexa57aes1742098/#a5232447e95e3e81c9754a18aee3f183d">anonymous{ARMFixCortexA57AES1742098Pass.cpp}::ARMFixCortexA57AES1742098::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-armlowoverheadloops-cpp-/armlowoverheadloops/#af5b3b47d9f63f641b02afd1f74e738d1">anonymous{ARMLowOverheadLoops.cpp}::ARMLowOverheadLoops::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-armparalleldsp-cpp-/armparalleldsp/#a150618f73ac168f3449ea9325dc36b81">anonymous{ARMParallelDSP.cpp}::ARMParallelDSP::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-armslshardening-cpp-/armslshardening/#afca1e1fe53665a96f514eab1ee8b1a44">anonymous{ARMSLSHardening.cpp}::ARMSLSHardening::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-complexdeinterleavingpass-cpp-/complexdeinterleavinglegacypass/#ae39cf189b0a2930fb659bcecc57d2167">anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-constanthoisting-cpp-/constanthoistinglegacypass/#a5c306d7b0d842abb33b4b7f02d897cc4">anonymous{ConstantHoisting.cpp}::ConstantHoistingLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-dce-cpp-/dcelegacypass/#a2a7be817b0869b862a91dba894f3a804">anonymous{DCE.cpp}::DCELegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-deadmachineinstructionelim-cpp-/deadmachineinstructionelim/#a5339d020402df6d7bf7f208c63c18f6d">anonymous{DeadMachineInstructionElim.cpp}::DeadMachineInstructionElim::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-detectdeadlanes-cpp-/detectdeadlanes/#a520d24cc590ed35981a1e52459a0b27f">anonymous{DetectDeadLanes.cpp}::DetectDeadLanes::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-earlycse-cpp-/earlycselegacycommonpass/#add6c1a279c781bf576a2fe4aa46fca4a">anonymous{EarlyCSE.cpp}::EarlyCSELegacyCommonPass&lt; UseMemorySSA &gt;::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandpostrapseudos-cpp-/expandpostra/#aa5baa1113a3a4807e774c6abdb7ee0ee">anonymous{ExpandPostRAPseudos.cpp}::ExpandPostRA::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandreductions-cpp-/expandreductions/#ae6ad7189d53a46066fce43bcab716ab2">anonymous{ExpandReductions.cpp}::ExpandReductions::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-fixupstatepointcallersaved-cpp-/fixupstatepointcallersaved/#a23566de7a7bc3843887349c7e4571d5f">anonymous{FixupStatepointCallerSaved.cpp}::FixupStatepointCallerSaved::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcncreatevopd-cpp-/gcncreatevopd/#ae4c82190d5071dc67b65c0f8294a0388">anonymous{GCNCreateVOPD.cpp}::GCNCreateVOPD::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcndppcombine-cpp-/gcndppcombinelegacy/#a309e214c2251d8be26b1d035e4508d66">anonymous{GCNDPPCombine.cpp}::GCNDPPCombineLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnrewritepartialreguses-cpp-/gcnrewritepartialreguses/#a624377ff0520ceb23b042f018dc1e992">anonymous{GCNRewritePartialRegUses.cpp}::GCNRewritePartialRegUses::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-globalmerge-cpp-/globalmerge/#a306b0d81a7cf944346a854335c0c3436">anonymous{GlobalMerge.cpp}::GlobalMerge::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonbranchrelaxation-cpp-/hexagonbranchrelaxation/#a699d917c91d8002ac38b6afb9a4a0bc0">anonymous{HexagonBranchRelaxation.cpp}::HexagonBranchRelaxation::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonfixuphwloops-cpp-/hexagonfixuphwloops/#a1259ea8f78d4518136f3988f0c1dd39a">anonymous{HexagonFixupHwLoops.cpp}::HexagonFixupHwLoops::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombinelegacy/#abd5bd35073dfc041b595cdaee05bb3b3">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombineLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorloopcarriedreuse-cpp-/hexagonvectorloopcarriedreuselegacypass/#aaa01e8caee7e8d84bd3a0311252cbfba">anonymous{HexagonVectorLoopCarriedReuse.cpp}::HexagonVectorLoopCarriedReuseLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvliwpacketizer-cpp-/hexagonpacketizer/#aef7b5d1821cb1da9e2591a655e6da756">anonymous{HexagonVLIWPacketizer.cpp}::HexagonPacketizer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-inferaddressspaces-cpp-/inferaddressspaces/#a950f96fe966c590afad7e1fb9d626179">anonymous{InferAddressSpaces.cpp}::InferAddressSpaces::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-initundef-cpp-/initundef/#a1270dd5bc303ee7f6913b8d37c722f2d">anonymous{InitUndef.cpp}::InitUndef::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-instsimplifypass-cpp-/instsimplifylegacypass/#a050c5b493bb56cdbcf056a3f17a3994f">anonymous{InstSimplifyPass.cpp}::InstSimplifyLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-interleavedaccesspass-cpp-/interleavedaccess/#aac977fbdda0d61e77203eac9a53b0eba">anonymous{InterleavedAccessPass.cpp}::InterleavedAccess::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-lcssa-cpp-/lcssawrapperpass/#a4694a636db811386299d0db5acb8bcf8">anonymous{LCSSA.cpp}::LCSSAWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvalues-cpp-/livedebugvalues/#a1f7fc129902e171c5b9634a6f5356c30">anonymous{LiveDebugValues.cpp}::LiveDebugValues::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-liverangeshrink-cpp-/liverangeshrink/#a721abdc3316893cdbfc108e5e9482297">anonymous{LiveRangeShrink.cpp}::LiveRangeShrink::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-loadstorevectorizer-cpp-/loadstorevectorizerlegacypass/#a4131111ba674d294e4c9fe6c7c46ae84">anonymous{LoadStoreVectorizer.cpp}::LoadStoreVectorizerLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-localstackslotallocation-cpp-/localstackslotpass/#a7118963bc665915b6323fd085b3a8e76">anonymous{LocalStackSlotAllocation.cpp}::LocalStackSlotPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchdeadregisterdefinitions-cpp-/loongarchdeadregisterdefinitions/#aee2662f8d6234409ecad4a99ee4d99c1">anonymous{LoongArchDeadRegisterDefinitions.cpp}::LoongArchDeadRegisterDefinitions::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchexpandpseudoinsts-cpp-/loongarchpreraexpandpseudo/#a5113d66f486d0459d3f5c80790038562">anonymous{LoongArchExpandPseudoInsts.cpp}::LoongArchPreRAExpandPseudo::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#ac68ad8a9e078ae9d244899fba282ed1a">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchoptwinstrs-cpp-/loongarchoptwinstrs/#a89b4fdb8278a64c8de5f798c88aac9bc">anonymous{LoongArchOptWInstrs.cpp}::LoongArchOptWInstrs::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kexpandpseudo-cpp-/m68kexpandpseudo/#a465bd03de634225491ac00bfd350cedd">anonymous{M68kExpandPseudo.cpp}::M68kExpandPseudo::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-m68kinstrinfo-cpp-/m68kglobalbasereg/#a8bcb196b218764566bf32112c7cd296b">anonymous{M68kInstrInfo.cpp}::M68kGlobalBaseReg::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecfgprinter-cpp-/machinecfgprinter/#a3cb6854a1ab652189ce8bc14e2aeb278">anonymous{MachineCFGPrinter.cpp}::MachineCFGPrinter::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/machinecopypropagation/#ac30711a34966bbea7d746ec2a4794dea">anonymous{MachineCopyPropagation.cpp}::MachineCopyPropagation::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecse-cpp-/machinecselegacy/#ac3b719058248e500cf47614f838e2dbd">anonymous{MachineCSE.cpp}::MachineCSELegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-machinedebugify-cpp-/debugifymachinemodule/#a3b40ae7b90ab98622f28bf6ca66f940f">anonymous{MachineDebugify.cpp}::DebugifyMachineModule::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinelateinstrscleanup-cpp-/machinelateinstrscleanup/#a7a19edf03f141cc330deb5ba2cd867a4">anonymous{MachineLateInstrsCleanup.cpp}::MachineLateInstrsCleanup::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machinescheduler/#acfe823cc8d6d37bb30948aa5598ebbcd">anonymous{MachineScheduler.cpp}::MachineScheduler::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/postmachinescheduler/#a065b9f9c1b17415e3e76fb115be4f7b4">anonymous{MachineScheduler.cpp}::PostMachineScheduler::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinesink-cpp-/postramachinesinking/#a62d3eccd9992d21281a8a354bfe4074b">anonymous{MachineSink.cpp}::PostRAMachineSinking::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-machinestripdebug-cpp-/stripdebugmachinemodule/#a43b75493aa0ac47c4a8b194ece8a640e">anonymous{MachineStripDebug.cpp}::StripDebugMachineModule::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-mem2reg-cpp-/promotelegacypass/#a82a0f24161fb10b3fb9c5ca7f01b05cc">anonymous{Mem2Reg.cpp}::PromoteLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsprelegalizercombiner-cpp-/mipsprelegalizercombiner/#a15ad2de16cc122c2bbf5e48df00ba98f">anonymous{MipsPreLegalizerCombiner.cpp}::MipsPreLegalizerCombiner::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-mircanonicalizerpass-cpp-/mircanonicalizer/#a01ea902aab9bf3f4831d0426c54a647a">anonymous{MIRCanonicalizerPass.cpp}::MIRCanonicalizer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-mirnamerpass-cpp-/mirnamer/#af813c085322fce08dc3c64bc6fa9b7ba">anonymous{MIRNamerPass.cpp}::MIRNamer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-mvegatherscatterlowering-cpp-/mvegatherscatterlowering/#afa4a0702e24a4ace54875ffda7200ae2">anonymous{MVEGatherScatterLowering.cpp}::MVEGatherScatterLowering::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-mvelaneinterleavingpass-cpp-/mvelaneinterleaving/#a5d398dffcffa3207fea0090bfcb6b18a">anonymous{MVELaneInterleavingPass.cpp}::MVELaneInterleaving::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-mvetailpredication-cpp-/mvetailpredication/#a501d45b17714ffbb35cfce22c4d2579f">anonymous{MVETailPredication.cpp}::MVETailPredication::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-naryreassociate-cpp-/naryreassociatelegacypass/#acdc8ee047a896abe97f66951eecf26f3">anonymous{NaryReassociate.cpp}::NaryReassociateLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-nvptxatomiclower-cpp-/nvptxatomiclower/#a9fe4ce230d62f0e88ec36d6d958da2be">anonymous{NVPTXAtomicLower.cpp}::NVPTXAtomicLower::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-optimizephis-cpp-/optimizephislegacy/#ad5c42f306bbd7bc25fd8a3922cf7565e">anonymous{OptimizePHIs.cpp}::OptimizePHIsLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/peepholeoptimizerlegacy/#a7965466f4f6cbc82341601e38cf7f6ec">anonymous{PeepholeOptimizer.cpp}::PeepholeOptimizerLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-postrahazardrecognizer-cpp-/postrahazardrecognizer/#afa8609d98b24d2196e814edb7615ab65">anonymous{PostRAHazardRecognizer.cpp}::PostRAHazardRecognizer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-postraschedulerlist-cpp-/postrascheduler/#a7ca1172aa08500cf1376986689afcfcc">anonymous{PostRASchedulerList.cpp}::PostRAScheduler::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-prologepiloginserter-cpp-/pei/#a63fab4b6208ac6a9e73d72821e5d24a8">anonymous{PrologEpilogInserter.cpp}::PEI::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600optimizevectorregisters-cpp-/r600vectorregmerger/#ac75ad1526a7fdc5f26ee2807a660eb46">anonymous{R600OptimizeVectorRegisters.cpp}::R600VectorRegMerger::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600packetizer-cpp-/r600packetizer/#a8ca6bb3044f7fedb5c95bba1d03ede31">anonymous{R600Packetizer.cpp}::R600Packetizer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-reassociate-cpp-/reassociatelegacypass/#a8f2f64c5906687a22c672cef94198d23">anonymous{Reassociate.cpp}::ReassociateLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#a4d13f3859751e81e68b91336687b574d">anonymous{RegAllocBasic.cpp}::RABasic::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocfast-cpp-/regallocfast/#a043d0d50602bb12a2a21b19de98421f6">anonymous{RegAllocFast.cpp}::RegAllocFast::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocpbqp-cpp-/regallocpbqp/#a71020ccbea35e322e29b2b44608289af">anonymous{RegAllocPBQP.cpp}::RegAllocPBQP::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/registercoalescer/#a3ae96d8cb445f62aa68d962e73704705">anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-removeredundantdebugvalues-cpp-/removeredundantdebugvalues/#a390b2e9aec8e5561c20fddc969263a81">anonymous{RemoveRedundantDebugValues.cpp}::RemoveRedundantDebugValues::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-renameindependentsubregs-cpp-/renameindependentsubregs/#af72b255cdd9f377d029480d76c863fed">anonymous{RenameIndependentSubregs.cpp}::RenameIndependentSubregs::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvcodegenprepare-cpp-/riscvcodegenprepare/#ab97b46bd6a2c271a6a2a97aff8fae7c1">anonymous{RISCVCodeGenPrepare.cpp}::RISCVCodeGenPrepare::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvdeadregisterdefinitions-cpp-/riscvdeadregisterdefinitions/#a8988e1e95d5ec1c4126892fc99480b2b">anonymous{RISCVDeadRegisterDefinitions.cpp}::RISCVDeadRegisterDefinitions::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvexpandpseudoinsts-cpp-/riscvpreraexpandpseudo/#aacfa214012152eed21058d3543365987">anonymous{RISCVExpandPseudoInsts.cpp}::RISCVPreRAExpandPseudo::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvgatherscatterlowering-cpp-/riscvgatherscatterlowering/#a0466570efcd27f0c4485577a37159688">anonymous{RISCVGatherScatterLowering.cpp}::RISCVGatherScatterLowering::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertreadwritecsr-cpp-/riscvinsertreadwritecsr/#a97e911b6e0c66c59cfe76e99860d310d">anonymous{RISCVInsertReadWriteCSR.cpp}::RISCVInsertReadWriteCSR::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/riscvinsertvsetvli/#a18d6edb1a33bc0f9a4cfd44799f58a84">anonymous{RISCVInsertVSETVLI.cpp}::RISCVInsertVSETVLI::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertwritevxrm-cpp-/riscvinsertwritevxrm/#aa4b3e7360bd8c5b811220dabe0b771ac">anonymous{RISCVInsertWriteVXRM.cpp}::RISCVInsertWriteVXRM::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvlandingpadsetup-cpp-/riscvlandingpadsetup/#a1134f12f99485d9b2c5419a637f96247">anonymous{RISCVLandingPadSetup.cpp}::RISCVLandingPadSetup::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#a00b10aea4e3e75657cd1bd8c3d5da7dc">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvoptwinstrs-cpp-/riscvoptwinstrs/#a1d0abd3363bd49ce776104caf3367699">anonymous{RISCVOptWInstrs.cpp}::RISCVOptWInstrs::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvvloptimizer-cpp-/riscvvloptimizer/#aa14a7f95541927aba67d68823ffa2958">anonymous{RISCVVLOptimizer.cpp}::RISCVVLOptimizer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvzacasabifix-cpp-/riscvzacasabifix/#ad8d174cc8e85d5b8f7570bf963539769">anonymous{RISCVZacasABIFix.cpp}::RISCVZacasABIFix::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-separateconstoffsetfromgep-cpp-/separateconstoffsetfromgeplegacypass/#a81256fb5d7e5a723f09517f9d9297f91">anonymous{SeparateConstOffsetFromGEP.cpp}::SeparateConstOffsetFromGEPLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopieslegacy/#a5b7801b5d05f081b0c053e5f84dabcf6">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopiesLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandslegacy/#aa8c97a68703b232666c4c3002c2bf47a">anonymous{SIFoldOperands.cpp}::SIFoldOperandsLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinserthardclauses-cpp-/siinserthardclauses/#a7bb312e7b09ff030930708b97628fa7f">anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a51964e59ed1cde09d8e6d578e9c46d83">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloadstoreoptimizer-cpp-/siloadstoreoptimizerlegacy/#aae29199e4c801d23eca02b6d2cac7864">anonymous{SILoadStoreOptimizer.cpp}::SILoadStoreOptimizerLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/simemorylegalizer/#a10405db39963d1a6c70496c5ddccb210">anonymous{SIMemoryLegalizer.cpp}::SIMemoryLegalizer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-simoderegister-cpp-/simoderegister/#a155eded900a371175503436a69208b01">anonymous{SIModeRegister.cpp}::SIModeRegister::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-sink-cpp-/sinkinglegacypass/#a63a0ebb8bc075dbdbed33044d75affba">anonymous{Sink.cpp}::SinkingLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizeexecmasking-cpp-/sioptimizeexecmaskinglegacy/#a72905f4b369e4de53ec6335a89b2797d">anonymous{SIOptimizeExecMasking.cpp}::SIOptimizeExecMaskingLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverangelegacy/#a6b6807c43df612f845d9d5bea25804e6">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRangeLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sipeepholesdwalegacy/#a2900d98a17da13cc2615f601435ad97a">anonymous{SIPeepholeSDWA.cpp}::SIPeepholeSDWALegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-sishrinkinstructions-cpp-/sishrinkinstructionslegacy/#a523bf2a48621de73d223839ee01be3be">anonymous{SIShrinkInstructions.cpp}::SIShrinkInstructionsLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-smepeepholeopt-cpp-/smepeepholeopt/#a702b0cb450f7f926f1cf6782f18d1780">anonymous{SMEPeepholeOpt.cpp}::SMEPeepholeOpt::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-stackmaplivenessanalysis-cpp-/stackmapliveness/#a99990daadc9889fd551ddaaedf1b7fae">anonymous{StackMapLivenessAnalysis.cpp}::StackMapLiveness::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-stackslotcoloring-cpp-/stackslotcoloring/#a2cb6c60df9a13bed6099f591bc74969d">anonymous{StackSlotColoring.cpp}::StackSlotColoring::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-straightlinestrengthreduce-cpp-/straightlinestrengthreducelegacypass/#acb64aa0d77f5a3c7745951769fc79d32">anonymous{StraightLineStrengthReduce.cpp}::StraightLineStrengthReduceLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-sveintrinsicopts-cpp-/sveintrinsicopts/#ab1126ddaa19fe6e6ab65392b3e517bc8">anonymous{SVEIntrinsicOpts.cpp}::SVEIntrinsicOpts::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzcopyphysregs-cpp-/systemzcopyphysregs/#a2eea9f8c09a76da3091d119af43f3bc1">anonymous{SystemZCopyPhysRegs.cpp}::SystemZCopyPhysRegs::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzldcleanup-cpp-/systemzldcleanup/#a6fa7da9dd93bcae47100dad33845cec1">anonymous{SystemZLDCleanup.cpp}::SystemZLDCleanup::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-twoaddressinstructionpass-cpp-/twoaddressinstructionlegacypass/#acd910999edf78b013dcbbfa6f2ef0353">anonymous{TwoAddressInstructionPass.cpp}::TwoAddressInstructionLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-typepromotion-cpp-/typepromotionlegacy/#a2fb471fbcaa1b3ba35fb894cff9bc55d">anonymous{TypePromotion.cpp}::TypePromotionLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyargumentmove-cpp-/webassemblyargumentmove/#ae22526ea4a5851f84c6f910fc1dad5f3">anonymous{WebAssemblyArgumentMove.cpp}::WebAssemblyArgumentMove::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblymemintrinsicresults-cpp-/webassemblymemintrinsicresults/#a8652a0cd0eac81b30e2fae4c1c0483c0">anonymous{WebAssemblyMemIntrinsicResults.cpp}::WebAssemblyMemIntrinsicResults::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyregcoloring-cpp-/webassemblyregcoloring/#ae22e46e1547c33232ec93271f5333b80">anonymous{WebAssemblyRegColoring.cpp}::WebAssemblyRegColoring::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblysetp2alignoperands-cpp-/webassemblysetp2alignoperands/#a7b4e9b3f4da1f9c7856861233a4f35c4">anonymous{WebAssemblySetP2AlignOperands.cpp}::WebAssemblySetP2AlignOperands::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86argumentstackslotrebase-cpp-/x86argumentstackslotpass/#afaa9b072bb02e8464954952a8119ddcd">anonymous{X86ArgumentStackSlotRebase.cpp}::X86ArgumentStackSlotPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/x86domainreassignment/#a65886b817d882e7c94ed64d866989c85">anonymous{X86DomainReassignment.cpp}::X86DomainReassignment::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86expandpseudo-cpp-/x86expandpseudo/#ad5509857d884eab759de5c011843e3d4">anonymous{X86ExpandPseudo.cpp}::X86ExpandPseudo::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86floatingpoint-cpp-/fps/#aea62108993f8b9340a6075e331f77b8c">anonymous{X86FloatingPoint.cpp}::FPS::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86instrinfo-cpp-/cgbr/#a6e64c610aa356172aa4c35196c22fef6">anonymous{X86InstrInfo.cpp}::CGBR::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86instrinfo-cpp-/ldtlscleanup/#a815d4538b65b224b2851bce510be31b5">anonymous{X86InstrInfo.cpp}::LDTLSCleanup::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loadvalueinjectionloadhardening-cpp-/x86loadvalueinjectionloadhardeningpass/#ad749b69fe5b007dd43501842cd4e7e54">anonymous{X86LoadValueInjectionLoadHardening.cpp}::X86LoadValueInjectionLoadHardeningPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxtypelegacypass/#a015b9c8ff8717813f33a49593f94c69e">anonymous{X86LowerAMXType.cpp}::X86LowerAMXTypeLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86partialreduction-cpp-/x86partialreduction/#a1eff7741fd0063a741148d611571cfa0">anonymous{X86PartialReduction.cpp}::X86PartialReduction::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86winehstate-cpp-/winehstatepass/#a73e99813111e70bd76222e7aed294503">anonymous{X86WinEHState.cpp}::WinEHStatePass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-xrayinstrumentation-cpp-/xrayinstrumentation/#a09e5cc047d879ebea6c53e307060e4b4">anonymous{XRayInstrumentation.cpp}::XRayInstrumentation::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncombiningpass/#a5acf47fe333b314ccdb4c0a26f39db97">llvm::InstructionCombiningPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalswrapperpass/#accef3521ae76625b599b616c6f2b5fbf">llvm::LiveIntervalsWrapperPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/ragreedy/#aec26bf822b32b653438f2c81d8a220a2">llvm::RAGreedy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/llvm/replacewithvecliblegacy/#a3f441f0bb1565ba024c12d645511b53e">llvm::ReplaceWithVeclibLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/removeloadsintofakeuses/#ad479518efb9b613ce2581dee4e14f0a4">RemoveLoadsIntoFakeUses::getAnalysisUsage</a> and <a href="/web-llvm/docs/api/classes/siloweri1copieslegacy/#a9e28afb909e82dbc71cb02be08e5cd18">SILowerI1CopiesLegacy::getAnalysisUsage</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### pushUnique() {#a37238617ecc9dfba096f741af35a22b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AnalysisUsage::pushUnique (<a href="#aca5945c84f7ab80d6fb87b09c633aff9">VectorType</a> &amp; Set, <a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a> ID)</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Preserved {#a7d80ecdab831a4832c10772885b6f870}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;AnalysisID, 2&gt; llvm::AnalysisUsage::Preserved</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>.</p>

</div>
</div>

### PreservesAll {#a84420a5edaba9365265c276d05067d8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AnalysisUsage::PreservesAll = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>.</p>

</div>
</div>

### Required {#ace9a731cb503747b320a3e3af97329ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;AnalysisID, 8&gt; llvm::AnalysisUsage::Required</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets of analyses required and preserved by a pass.</p>

<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>.</p>

</div>
</div>

### RequiredTransitive {#ad7679b6b025283655237ec7e54b8db03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;AnalysisID, 2&gt; llvm::AnalysisUsage::RequiredTransitive</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>.</p>

</div>
</div>

### Used {#a8e2851d16535f5b3303055c55470591f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;AnalysisID, 0&gt; llvm::AnalysisUsage::Used</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
