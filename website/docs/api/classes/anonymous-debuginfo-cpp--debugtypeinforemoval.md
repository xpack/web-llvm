---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-debuginfo-cpp-/debugtypeinforemoval
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DebugTypeInfoRemoval` Class Reference

<p>Helper class to downgrade -g metadata to -gline-tables-only metadata. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{DebugInfo.cpp}::DebugTypeInfoRemoval { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0b0dbd8d394eb00810235441430c6be">DebugTypeInfoRemoval</a> (LLVMContext &amp;C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaf61273af35380b962e3aa6ffd2aaef">map</a> (Metadata *M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a121d20c7173eb47c19fae1b58a018a61">mapNode</a> (Metadata *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae05a2c490e9c5e36b78c0280c5592a1a">traverseAndRemap</a> (MDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively remap N and all its referenced children. <a href="#ae05a2c490e9c5e36b78c0280c5592a1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab68916ddd3fdbe6a0e36c01b05c70ad7">getReplacementSubprogram</a> (DISubprogram *MDS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dicompileunit">DICompileUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab06c12ec87d7b161fc8eddda9163a12c">getReplacementCU</a> (DICompileUnit *CU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new compile unit, to replace the one given. <a href="#ab06c12ec87d7b161fc8eddda9163a12c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43dfac922bc5930b99c3f71cb12b2240">getReplacementMDLocation</a> (DILocation *MLD)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58395bf8777edc256caeeb4ccfb59fd5">getReplacementMDNode</a> (MDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new generic <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a>, to replace the one given. <a href="#a58395bf8777edc256caeeb4ccfb59fd5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82815957ea5e3ab8eddfa5b132f6a60d">remap</a> (MDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to re-map N to a newly created node. <a href="#a82815957ea5e3ab8eddfa5b132f6a60d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa386ef096b062bdc2ef21d85c3ddd676">traverse</a> (MDNode *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Do the remapping traversal. <a href="#aa386ef096b062bdc2ef21d85c3ddd676">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3897c9eedb5404e865f71e414ed53b09">EmptySubroutineType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The (void)() type. <a href="#a3897c9eedb5404e865f71e414ed53b09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef4c2bd02ebb877ab65e07799b3d01e3">Replacements</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> *, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01343325054055ef42ae878b7b724fc0">NewToLinkageName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remember what linkage name we originally had before stripping. <a href="#a01343325054055ef42ae878b7b724fc0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Helper class to downgrade -g metadata to -gline-tables-only metadata.</p>

<p>Definition at line 637 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DebugTypeInfoRemoval() {#aa0b0dbd8d394eb00810235441430c6be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{DebugInfo.cpp}::DebugTypeInfoRemoval::DebugTypeInfoRemoval (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
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



<p>Definition at line 659 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a3897c9eedb5404e865f71e414ed53b09">EmptySubroutineType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### map() {#aaaf61273af35380b962e3aa6ffd2aaef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * anonymous{DebugInfo.cpp}::DebugTypeInfoRemoval::map (<a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * M)</td>
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



<p>Definition at line 663 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>Referenced by <a href="#a121d20c7173eb47c19fae1b58a018a61">mapNode</a>.</p>

</div>
</div>

### mapNode() {#a121d20c7173eb47c19fae1b58a018a61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * anonymous{DebugInfo.cpp}::DebugTypeInfoRemoval::mapNode (<a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * N)</td>
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



<p>Definition at line 672 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="#aaaf61273af35380b962e3aa6ffd2aaef">map</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### traverseAndRemap() {#ae05a2c490e9c5e36b78c0280c5592a1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{DebugInfo.cpp}::DebugTypeInfoRemoval::traverseAndRemap (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * N)</td>
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

<p>Recursively remap N and all its referenced children.</p>


<p>Does a DF post-order traversal, so as to remap bottoms up.</p>


<p>Definition at line 676 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getReplacementCU() {#ab06c12ec87d7b161fc8eddda9163a12c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DICompileUnit * anonymous{DebugInfo.cpp}::DebugTypeInfoRemoval::getReplacementCU (<a href="/web-llvm/docs/api/classes/llvm/dicompileunit">DICompileUnit</a> * CU)</td>
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

<p>Create a new compile unit, to replace the one given.</p>

<p>Definition at line 729 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>

</div>
</div>

### getReplacementMDLocation() {#a43dfac922bc5930b99c3f71cb12b2240}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DILocation * anonymous{DebugInfo.cpp}::DebugTypeInfoRemoval::getReplacementMDLocation (<a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * MLD)</td>
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



<p>Definition at line 749 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>

</div>
</div>

### getReplacementMDNode() {#a58395bf8777edc256caeeb4ccfb59fd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * anonymous{DebugInfo.cpp}::DebugTypeInfoRemoval::getReplacementMDNode (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * N)</td>
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

<p>Create a new generic <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a>, to replace the one given.</p>

<p>Definition at line 760 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>

</div>
</div>

### getReplacementSubprogram() {#ab68916ddd3fdbe6a0e36c01b05c70ad7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DISubprogram * anonymous{DebugInfo.cpp}::DebugTypeInfoRemoval::getReplacementSubprogram (<a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> * MDS)</td>
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



<p>Definition at line 680 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>

</div>
</div>

### remap() {#a82815957ea5e3ab8eddfa5b132f6a60d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{DebugInfo.cpp}::DebugTypeInfoRemoval::remap (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * N)</td>
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

<p>Attempt to re-map N to a newly created node.</p>

<p>Definition at line 771 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>

</div>
</div>

### traverse() {#aa386ef096b062bdc2ef21d85c3ddd676}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DebugTypeInfoRemoval::traverse (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Do the remapping traversal.</p>

<p>Definition at line 805 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### EmptySubroutineType {#a3897c9eedb5404e865f71e414ed53b09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode* anonymous{DebugInfo.cpp}::DebugTypeInfoRemoval::EmptySubroutineType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The (void)() type.</p>

<p>Definition at line 642 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>Referenced by <a href="#aa0b0dbd8d394eb00810235441430c6be">DebugTypeInfoRemoval</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### NewToLinkageName {#a01343325054055ef42ae878b7b724fc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;DISubprogram *, StringRef&gt; anonymous{DebugInfo.cpp}::DebugTypeInfoRemoval::NewToLinkageName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remember what linkage name we originally had before stripping.</p>


<p>If we end up making two subprograms identical who originally had different linkage names, then we need to make one of them distinct, to avoid them getting uniqued. Maps the new node to the old linkage name.</p>


<p>Definition at line 649 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>

</div>
</div>

### Replacements {#aef4c2bd02ebb877ab65e07799b3d01e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Metadata *, Metadata *&gt; anonymous{DebugInfo.cpp}::DebugTypeInfoRemoval::Replacements</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 638 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
