---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/loopvectorizehints
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LoopVectorizeHints` Class Reference

<p>Utility class for getting and setting loop vectorizer hints in the form of loop metadata. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LoopVectorizeHints { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">llvm/Transforms/Vectorize/LoopVectorizationLegality.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">HintKind { <a href="#ab55beb35b45b4953bcc0858db2aefa13">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ForceKind { <a href="#a55ab1072c44295ad279535d714a0f33e">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ScalableForceKind { <a href="#a041ce1f90aff1772f662dd0c8e3ec4f4">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa68245d8ed8fafd80a06d5092f434093">LoopVectorizeHints</a> (const Loop *L, bool InterleaveOnlyWhenForced, OptimizationRemarkEmitter &amp;ORE, const TargetTransformInfo *TTI=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2f5ef2d522fb80de283a23d5bed6d86">setAlreadyVectorized</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark the loop L as already vectorized by setting the width to 1. <a href="#aa2f5ef2d522fb80de283a23d5bed6d86">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21b6d9e2aa12c8c68d8e2f122ec7ecec">allowVectorization</a> (Function *F, Loop *L, bool VectorizeOnlyWhenForced) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a440979b6103588bef39bd2d62065d5ff">emitRemarkWithHints</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dumps all the hint information. <a href="#a440979b6103588bef39bd2d62065d5ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50cae5c2df432357d50f182d310ce7b7">getWidth</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad98353127dbeb649d41ca07da5074b49">getInterleave</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0277f27ebe0f8317170a739b2080d0c">getIsVectorized</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7592f6d851162d7f66f26408f40e9388">getPredicate</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum <a href="#a55ab1072c44295ad279535d714a0f33e">ForceKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20ecacbd54e401685d798d86161af6cf">getForce</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1289a2ba34766f399d81f71c0f6b3a94">isScalableVectorizationDisabled</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcf8c2b35316773f1ab0ba70aeb2a6de">vectorizeAnalysisPassName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If hints are provided that force vectorization, use the AlwaysPrint pass name to force the frontend to print the diagnostic. <a href="#abcf8c2b35316773f1ab0ba70aeb2a6de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b74e08f930d32c0d31482179fd0a805">allowReordering</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When enabling loop hints are provided we allow the vectorizer to change the order of operations that is given by the scalar loop. <a href="#a2b74e08f930d32c0d31482179fd0a805">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a475b1d2223ddab6c0ab44dfcea7dcba7">isPotentiallyUnsafe</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af611ab8bb7005d705fe61049bf572524">setPotentiallyUnsafe</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66d62fe0e498ad2b6e01955e1e87bfdb">getHintsFromMetadata</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find hints specified in the loop metadata and update local values. <a href="#a66d62fe0e498ad2b6e01955e1e87bfdb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c41f3a348468dcfc4feb8f9ff817750">setHint</a> (StringRef Name, Metadata *Arg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks string hint with one operand and set value if valid. <a href="#a5c41f3a348468dcfc4feb8f9ff817750">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">Hint</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b5b14a0b7ba1bde914b50c32aa30836">Width</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vectorization width. <a href="#a6b5b14a0b7ba1bde914b50c32aa30836">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">Hint</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a778d68368b6bec7e5ed806e776484960">Interleave</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vectorization interleave factor. <a href="#a778d68368b6bec7e5ed806e776484960">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">Hint</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4949a6033951eb0f8216faed9cc15de8">Force</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vectorization forced. <a href="#a4949a6033951eb0f8216faed9cc15de8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">Hint</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a254189831d4e9ec05df8461af3aa693d">IsVectorized</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Already Vectorized. <a href="#a254189831d4e9ec05df8461af3aa693d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">Hint</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacfb678356a7eded74eea46c47132143">Predicate</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vector <a href="/web-llvm/docs/api/classes/predicate">Predicate</a>. <a href="#aacfb678356a7eded74eea46c47132143">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">Hint</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ad4d189dc6b4cd3b3ff21e53f993dbd">Scalable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Says whether we should use fixed width or scalable vectorization. <a href="#a7ad4d189dc6b4cd3b3ff21e53f993dbd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc661affb2a486b05617f0c5b6858f21">PotentiallyUnsafe</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if there is any unsafe math in the loop. <a href="#acc661affb2a486b05617f0c5b6858f21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d015aa99e593e61f941f47915440d94">TheLoop</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The loop these hints belong to. <a href="#a8d015aa99e593e61f941f47915440d94">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca0212ad8b5615a31607c92413792432">ORE</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Interface to emit optimization remarks. <a href="#aca0212ad8b5615a31607c92413792432">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6da1c88fa8e2412ec4cf53611cf8944b">Prefix</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the loop metadata prefix. <a href="#a6da1c88fa8e2412ec4cf53611cf8944b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Utility class for getting and setting loop vectorizer hints in the form of loop metadata.</p>


<p>This class keeps a number of loop annotations locally (as member variables) and can, upon request, write them back as metadata on the loop. It will initially scan the loop for existing metadata, and will update the local values based on information in the loop. We cannot write all values to metadata, as the mere presence of some info, for example 'force', means a decision has been made. So, we need to be careful NOT to add them if the user hasn't specifically asked so.</p>


<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### ForceKind {#a55ab1072c44295ad279535d714a0f33e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::LoopVectorizeHints::ForceKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_Undefined<a id="a55ab1072c44295ad279535d714a0f33ea8914fe2dbf82d457456e8e4faa201b87"></a></td>
<td class="doxyEnumItemDescription">Not selected (= -1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_Disabled<a id="a55ab1072c44295ad279535d714a0f33ea980c2c6e59ca5dcf413baa325d8bc385"></a></td>
<td class="doxyEnumItemDescription">Forcing disabled (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_Enabled<a id="a55ab1072c44295ad279535d714a0f33ea278ca681847fb2bad9707f76d899b231"></a></td>
<td class="doxyEnumItemDescription">Forcing enabled (= 1)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### HintKind {#ab55beb35b45b4953bcc0858db2aefa13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::LoopVectorizeHints::HintKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HK_WIDTH<a id="ab55beb35b45b4953bcc0858db2aefa13a8c7b297419f72d9372757eeccde0f426"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HK_INTERLEAVE<a id="ab55beb35b45b4953bcc0858db2aefa13aa653c1662e7b9afd10582cf7b4e87d31"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HK_FORCE<a id="ab55beb35b45b4953bcc0858db2aefa13a88c336175ac015009848ca0e4445e8aa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HK_ISVECTORIZED<a id="ab55beb35b45b4953bcc0858db2aefa13a9cb9de1531ada09326aa3c3f2c84fe4b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HK_PREDICATE<a id="ab55beb35b45b4953bcc0858db2aefa13a6c1bb02f848fe2b8aa7a7bac27309811"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HK_SCALABLE<a id="ab55beb35b45b4953bcc0858db2aefa13a2d0202d213ebe96247b4e183b73baa7e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### ScalableForceKind {#a041ce1f90aff1772f662dd0c8e3ec4f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::LoopVectorizeHints::ScalableForceKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SK_Unspecified<a id="a041ce1f90aff1772f662dd0c8e3ec4f4a99f04f3a0c3cb69e39acbc12c93b49da"></a></td>
<td class="doxyEnumItemDescription">Not selected (= -1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SK_FixedWidthOnly<a id="a041ce1f90aff1772f662dd0c8e3ec4f4ac46ef7a95288338ce20df95d296898f4"></a></td>
<td class="doxyEnumItemDescription">Disables vectorization with scalable vectors (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SK_PreferScalable<a id="a041ce1f90aff1772f662dd0c8e3ec4f4a7d9d22c5375d2c00b79a4a897967a2f6"></a></td>
<td class="doxyEnumItemDescription">Vectorize loops using scalable vectors or fixed-width vectors, but favor scalable vectors when the cost-model is inconclusive (= 1)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LoopVectorizeHints() {#aa68245d8ed8fafd80a06d5092f434093}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LoopVectorizeHints::LoopVectorizeHints (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, bool InterleaveOnlyWhenForced, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp; ORE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * TTI=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a55ab1072c44295ad279535d714a0f33ea8914fe2dbf82d457456e8e4faa201b87">FK_Undefined</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp/#a07fab21a3826937dd616c857eeae0fd4">ForceScalableVectorization</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="#ad98353127dbeb649d41ca07da5074b49">getInterleave</a>, <a href="#a50cae5c2df432357d50f182d310ce7b7">getWidth</a>, <a href="/web-llvm/docs/api/structs/llvm/vectorizerparams/#a5ccaa3f1275b2e841f5c23852d61b872">llvm::VectorizerParams::isInterleaveForced</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a041ce1f90aff1772f662dd0c8e3ec4f4ac46ef7a95288338ce20df95d296898f4">SK_FixedWidthOnly</a>, <a href="#a041ce1f90aff1772f662dd0c8e3ec4f4a7d9d22c5375d2c00b79a4a897967a2f6">SK_PreferScalable</a>, <a href="#a041ce1f90aff1772f662dd0c8e3ec4f4a99f04f3a0c3cb69e39acbc12c93b49da">SK_Unspecified</a> and <a href="/web-llvm/docs/api/structs/llvm/vectorizerparams/#a6a8f6b7564d1df823a8d8e8dcecf6802">llvm::VectorizerParams::VectorizationInterleave</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### allowReordering() {#a2b74e08f930d32c0d31482179fd0a805}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizeHints::allowReordering ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When enabling loop hints are provided we allow the vectorizer to change the order of operations that is given by the scalar loop.</p>


<p>This is not enabled by default because can be unsafe or inefficient. For example, reordering floating-point operations will change the way round-off error accumulates in the loop.</p>


<p>Declaration at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>


<p>References <a href="#a55ab1072c44295ad279535d714a0f33ea278ca681847fb2bad9707f76d899b231">FK_Enabled</a>, <a href="#a20ecacbd54e401685d798d86161af6cf">getForce</a>, <a href="#a50cae5c2df432357d50f182d310ce7b7">getWidth</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a16fc625dd8e918129c473b1b0bf1486f">llvm::HintsAllowReordering</a>.</p>

</div>
</div>

### allowVectorization() {#a21b6d9e2aa12c8c68d8e2f122ec7ecec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizeHints::allowVectorization (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, bool VectorizeOnlyWhenForced)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a440979b6103588bef39bd2d62065d5ff">emitRemarkWithHints</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a55ab1072c44295ad279535d714a0f33ea980c2c6e59ca5dcf413baa325d8bc385">FK_Disabled</a>, <a href="#a55ab1072c44295ad279535d714a0f33ea278ca681847fb2bad9707f76d899b231">FK_Enabled</a>, <a href="#a20ecacbd54e401685d798d86161af6cf">getForce</a>, <a href="#af0277f27ebe0f8317170a739b2080d0c">getIsVectorized</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="#abcf8c2b35316773f1ab0ba70aeb2a6de">vectorizeAnalysisPassName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a806ec23d6f44b02ad8cf3b1e61c05495">isExplicitVecOuterLoop</a> and <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

### emitRemarkWithHints() {#a440979b6103588bef39bd2d62065d5ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopVectorizeHints::emitRemarkWithHints ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dumps all the hint information.</p>

<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>


<p>References <a href="#a55ab1072c44295ad279535d714a0f33ea980c2c6e59ca5dcf413baa325d8bc385">FK_Disabled</a>, <a href="#a55ab1072c44295ad279535d714a0f33ea278ca681847fb2bad9707f76d899b231">FK_Enabled</a>, <a href="#ad98353127dbeb649d41ca07da5074b49">getInterleave</a>, <a href="#a50cae5c2df432357d50f182d310ce7b7">getWidth</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp/#a0eff4a8bccb143ae91e197e6a59d4692">LV_NAME</a>.</p>


<p>Referenced by <a href="#a21b6d9e2aa12c8c68d8e2f122ec7ecec">allowVectorization</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a806ec23d6f44b02ad8cf3b1e61c05495">isExplicitVecOuterLoop</a> and <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

### getForce() {#a20ecacbd54e401685d798d86161af6cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum ForceKind llvm::LoopVectorizeHints::getForce ()</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>


<p>References <a href="#a55ab1072c44295ad279535d714a0f33ea980c2c6e59ca5dcf413baa325d8bc385">FK_Disabled</a>, <a href="#a55ab1072c44295ad279535d714a0f33ea8914fe2dbf82d457456e8e4faa201b87">FK_Undefined</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7d25a8a9d14a556b1ca44f8fe0dfdd8b">llvm::hasDisableAllTransformsHint</a>.</p>


<p>Referenced by <a href="#a2b74e08f930d32c0d31482179fd0a805">allowReordering</a>, <a href="#a21b6d9e2aa12c8c68d8e2f122ec7ecec">allowVectorization</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a8cde912cc23c18f493e4e5005c85748b">getScalarEpilogueLowering</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a806ec23d6f44b02ad8cf3b1e61c05495">isExplicitVecOuterLoop</a>, <a href="#a475b1d2223ddab6c0ab44dfcea7dcba7">isPotentiallyUnsafe</a>, <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a> and <a href="#abcf8c2b35316773f1ab0ba70aeb2a6de">vectorizeAnalysisPassName</a>.</p>

</div>
</div>

### getInterleave() {#ad98353127dbeb649d41ca07da5074b49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LoopVectorizeHints::getInterleave ()</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a868145c1795173f9642f99c354f91a7d">llvm::hasUnrollTransformation</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3e837c0d2a0521b4a4680071cac0dcbaa70bd8f3da4232ad809b2ffdcc1254bd">llvm::TM_Disable</a>.</p>


<p>Referenced by <a href="#a440979b6103588bef39bd2d62065d5ff">emitRemarkWithHints</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a806ec23d6f44b02ad8cf3b1e61c05495">isExplicitVecOuterLoop</a>, <a href="#aa68245d8ed8fafd80a06d5092f434093">LoopVectorizeHints</a> and <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

### getIsVectorized() {#af0277f27ebe0f8317170a739b2080d0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LoopVectorizeHints::getIsVectorized ()</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>


<p>Referenced by <a href="#a21b6d9e2aa12c8c68d8e2f122ec7ecec">allowVectorization</a>.</p>

</div>
</div>

### getPredicate() {#a7592f6d851162d7f66f26408f40e9388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LoopVectorizeHints::getPredicate ()</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a8cde912cc23c18f493e4e5005c85748b">getScalarEpilogueLowering</a>.</p>

</div>
</div>

### getWidth() {#a50cae5c2df432357d50f182d310ce7b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ElementCount llvm::LoopVectorizeHints::getWidth ()</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a79ea372f9aa69492fccfafc0e5a1589c">llvm::ElementCount::get</a> and <a href="#a041ce1f90aff1772f662dd0c8e3ec4f4a7d9d22c5375d2c00b79a4a897967a2f6">SK_PreferScalable</a>.</p>


<p>Referenced by <a href="#a2b74e08f930d32c0d31482179fd0a805">allowReordering</a>, <a href="#a440979b6103588bef39bd2d62065d5ff">emitRemarkWithHints</a>, <a href="#aa68245d8ed8fafd80a06d5092f434093">LoopVectorizeHints</a>, <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#adeb41c907ebde15846bc643325909f95">processLoopInVPlanNativePath</a> and <a href="#abcf8c2b35316773f1ab0ba70aeb2a6de">vectorizeAnalysisPassName</a>.</p>

</div>
</div>

### isPotentiallyUnsafe() {#a475b1d2223ddab6c0ab44dfcea7dcba7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizeHints::isPotentiallyUnsafe ()</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>


<p>References <a href="#a55ab1072c44295ad279535d714a0f33ea278ca681847fb2bad9707f76d899b231">FK_Enabled</a> and <a href="#a20ecacbd54e401685d798d86161af6cf">getForce</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

### isScalableVectorizationDisabled() {#a1289a2ba34766f399d81f71c0f6b3a94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizeHints::isScalableVectorizationDisabled ()</td>
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
<dd><p>true if scalable vectorization has been explicitly disabled.</p></dd>
</dl>


<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>


<p>Reference <a href="#a041ce1f90aff1772f662dd0c8e3ec4f4ac46ef7a95288338ce20df95d296898f4">SK_FixedWidthOnly</a>.</p>

</div>
</div>

### setAlreadyVectorized() {#aa2f5ef2d522fb80de283a23d5bed6d86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopVectorizeHints::setAlreadyVectorized ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark the loop L as already vectorized by setting the width to 1.</p>

<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata/#a4c720c398a263087e00d7358b05636d5">llvm::ConstantAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#affbb7e2e9ad8d18114816f2443d672b9">llvm::MDString::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac8a1ae2e1de53a840bee516d1f5bb173">llvm::makePostTransformationMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#a4c1c1093a7749409c70838678514cc7c">llvm::Twine::str</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#adeb41c907ebde15846bc643325909f95">processLoopInVPlanNativePath</a>.</p>

</div>
</div>

### setPotentiallyUnsafe() {#af611ab8bb7005d705fe61049bf572524}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopVectorizeHints::setPotentiallyUnsafe ()</td>
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



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### vectorizeAnalysisPassName() {#abcf8c2b35316773f1ab0ba70aeb2a6de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::LoopVectorizeHints::vectorizeAnalysisPassName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If hints are provided that force vectorization, use the AlwaysPrint pass name to force the frontend to print the diagnostic.</p>

<p>Declaration at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis/#aa17011a05879d3698f829ff869dc9a88">llvm::OptimizationRemarkAnalysis::AlwaysPrint</a>, <a href="#a55ab1072c44295ad279535d714a0f33ea980c2c6e59ca5dcf413baa325d8bc385">FK_Disabled</a>, <a href="#a55ab1072c44295ad279535d714a0f33ea8914fe2dbf82d457456e8e4faa201b87">FK_Undefined</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="#a20ecacbd54e401685d798d86161af6cf">getForce</a>, <a href="#a50cae5c2df432357d50f182d310ce7b7">getWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lint-cpp/#a45005634b54e2126cb3e6ec0dbc9ade4">isZero</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp/#a0eff4a8bccb143ae91e197e6a59d4692">LV_NAME</a>.</p>


<p>Referenced by <a href="#a21b6d9e2aa12c8c68d8e2f122ec7ecec">allowVectorization</a>, <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab425bb10a0f4af749bbb29aa07fc6854">llvm::reportVectorizationFailure</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getHintsFromMetadata() {#a66d62fe0e498ad2b6e01955e1e87bfdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopVectorizeHints::getHintsFromMetadata ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find hints specified in the loop metadata and update local values.</p>

<p>Declaration at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>

</div>
</div>

### setHint() {#a5c41f3a348468dcfc4feb8f9ff817750}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopVectorizeHints::setHint (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Arg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks string hint with one operand and set value if valid.</p>

<p>Declaration at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>, definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Force {#a4949a6033951eb0f8216faed9cc15de8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Hint llvm::LoopVectorizeHints::Force</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Vectorization forced.</p>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### Interleave {#a778d68368b6bec7e5ed806e776484960}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Hint llvm::LoopVectorizeHints::Interleave</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Vectorization interleave factor.</p>

<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### IsVectorized {#a254189831d4e9ec05df8461af3aa693d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Hint llvm::LoopVectorizeHints::IsVectorized</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Already Vectorized.</p>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### ORE {#aca0212ad8b5615a31607c92413792432}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkEmitter&amp; llvm::LoopVectorizeHints::ORE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Interface to emit optimization remarks.</p>

<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### PotentiallyUnsafe {#acc661affb2a486b05617f0c5b6858f21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizeHints::PotentiallyUnsafe = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if there is any unsafe math in the loop.</p>

<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### Predicate {#aacfb678356a7eded74eea46c47132143}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Hint llvm::LoopVectorizeHints::Predicate</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Vector <a href="/web-llvm/docs/api/classes/predicate">Predicate</a>.</p>

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### Scalable {#a7ad4d189dc6b4cd3b3ff21e53f993dbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Hint llvm::LoopVectorizeHints::Scalable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Says whether we should use fixed width or scalable vectorization.</p>

<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### TheLoop {#a8d015aa99e593e61f941f47915440d94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Loop* llvm::LoopVectorizeHints::TheLoop</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The loop these hints belong to.</p>

<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

### Width {#a6b5b14a0b7ba1bde914b50c32aa30836}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Hint llvm::LoopVectorizeHints::Width</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Vectorization width.</p>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### Prefix() {#a6da1c88fa8e2412ec4cf53611cf8944b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::LoopVectorizeHints::Prefix ()</td>
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

<p>Return the loop metadata prefix.</p>

<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">LoopVectorizationLegality.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
