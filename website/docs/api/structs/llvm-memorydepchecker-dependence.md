---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/memorydepchecker/dependence
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Dependence` Struct Reference

<p>Dependece between memory access instructions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::MemoryDepChecker::Dependence { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">llvm/Analysis/LoopAccessAnalysis.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">DepType { <a href="#ae336b0e8514b99a44e73c3e2494c3cea">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The type of the dependence. <a href="#ae336b0e8514b99a44e73c3e2494c3cea">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40efa3de48a570060d0db38b654d9ea3">Dependence</a> (unsigned Source, unsigned Destination, DepType Type)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a587c4bfaaf058747310f58b2f8d14f1c">getSource</a> (const MemoryDepChecker &amp;DepChecker) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the source instruction of the dependence. <a href="#a587c4bfaaf058747310f58b2f8d14f1c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29795bb317fb25a2cb114309a80a19f2">getDestination</a> (const MemoryDepChecker &amp;DepChecker) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the destination instruction of the dependence. <a href="#a29795bb317fb25a2cb114309a80a19f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a623aabb69f601ada6b290ac7d15e69a5">isForward</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lexically forward dependence. <a href="#a623aabb69f601ada6b290ac7d15e69a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68f3caaf7ba7f284e0feb00ae907e4c2">isBackward</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lexically backward dependence. <a href="#a68f3caaf7ba7f284e0feb00ae907e4c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cbfae0900c7bc2adb637840e589ed4e">isPossiblyBackward</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>May be a lexically backward dependence type (includes Unknown). <a href="#a4cbfae0900c7bc2adb637840e589ed4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8169d805ee357d7dc129683171b02a7f">print</a> (raw_ostream &amp;OS, unsigned Depth, const SmallVectorImpl&lt; Instruction * &gt; &amp;Instrs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the dependence. <a href="#a8169d805ee357d7dc129683171b02a7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3bc38ce52bab4fecf99d63404db047e">Source</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Index of the source of the dependence in the InstMap vector. <a href="#ad3bc38ce52bab4fecf99d63404db047e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d4c114023f646b32b50625f4f830c9b">Destination</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Index of the destination of the dependence in the InstMap vector. <a href="#a3d4c114023f646b32b50625f4f830c9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae336b0e8514b99a44e73c3e2494c3cea">DepType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a328598cc338e6d6c8d81e6cc4dd68873">Type</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The type of the dependence. <a href="#a328598cc338e6d6c8d81e6cc4dd68873">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memorydepchecker/#ac661dd363bcde8b1e9516390eff1c400">VectorizationSafetyStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7e624cd937996851e961d72cdca670d">isSafeForVectorization</a> (DepType Type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/memorydepchecker/dependence">Dependence</a> types that don't prevent vectorization. <a href="#af7e624cd937996851e961d72cdca670d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1ce4569bdd7d1341b095de3aeeb2765">DepName</a>[] = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>String version of the types. <a href="#af1ce4569bdd7d1341b095de3aeeb2765">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Dependece between memory access instructions.</p>

<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### DepType {#ae336b0e8514b99a44e73c3e2494c3cea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MemoryDepChecker::Dependence::DepType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The type of the dependence.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoDep<a id="ae336b0e8514b99a44e73c3e2494c3ceaae12470995d757ddbebbd627f397fe349"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Unknown<a id="ae336b0e8514b99a44e73c3e2494c3ceaa3d96a899c885f75def67055e4b486dab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IndirectUnsafe<a id="ae336b0e8514b99a44e73c3e2494c3ceaa006edf4988ecca6989849eb1e4b92662"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Forward<a id="ae336b0e8514b99a44e73c3e2494c3ceaa0e2ea83a39804701390079f7d07ed112"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ForwardButPreventsForwarding<a id="ae336b0e8514b99a44e73c3e2494c3ceaaec0ae061c48cbea01461ccb40dbc4c7a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Backward<a id="ae336b0e8514b99a44e73c3e2494c3ceaa4af323986f2ce2d7f10399fe8997096b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BackwardVectorizable<a id="ae336b0e8514b99a44e73c3e2494c3ceaa2a42f6e575ea09a8ee7c396bf3821b4d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BackwardVectorizableButPreventsForwarding<a id="ae336b0e8514b99a44e73c3e2494c3ceaa219afbca7ad4b6a18f20c507b7b12353"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Dependence() {#a40efa3de48a570060d0db38b654d9ea3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MemoryDepChecker::Dependence::Dependence (unsigned Source, unsigned Destination, <a href="#ae336b0e8514b99a44e73c3e2494c3cea">DepType</a> Type)</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<p>References <a href="#a3d4c114023f646b32b50625f4f830c9b">Destination</a>, <a href="#ad3bc38ce52bab4fecf99d63404db047e">Source</a> and <a href="#a328598cc338e6d6c8d81e6cc4dd68873">Type</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getDestination() {#a29795bb317fb25a2cb114309a80a19f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * llvm::MemoryDepChecker::Dependence::getDestination (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorydepchecker">MemoryDepChecker</a> &amp; DepChecker)</td>
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

<p>Return the destination instruction of the dependence.</p>

<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<p>References <a href="#a3d4c114023f646b32b50625f4f830c9b">Destination</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydepchecker/#a77779b1cb3dd7968c598f9d6de68282e">llvm::MemoryDepChecker::getMemoryInstructions</a> and <a href="/web-llvm/docs/api/classes/llvm/memorydepchecker/#a7610f9bf36472cdb43096b7bcafd0a89">llvm::MemoryDepChecker::MemoryDepChecker</a>.</p>

</div>
</div>

### getSource() {#a587c4bfaaf058747310f58b2f8d14f1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * llvm::MemoryDepChecker::Dependence::getSource (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorydepchecker">MemoryDepChecker</a> &amp; DepChecker)</td>
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

<p>Return the source instruction of the dependence.</p>

<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memorydepchecker/#a77779b1cb3dd7968c598f9d6de68282e">llvm::MemoryDepChecker::getMemoryInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydepchecker/#a7610f9bf36472cdb43096b7bcafd0a89">llvm::MemoryDepChecker::MemoryDepChecker</a> and <a href="#ad3bc38ce52bab4fecf99d63404db047e">Source</a>.</p>

</div>
</div>

### isBackward() {#a68f3caaf7ba7f284e0feb00ae907e4c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemoryDepChecker::Dependence::isBackward ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lexically backward dependence.</p>

<p>Declaration at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>, definition at line 1695 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>


<p>References <a href="#ae336b0e8514b99a44e73c3e2494c3ceaa4af323986f2ce2d7f10399fe8997096b">Backward</a>, <a href="#ae336b0e8514b99a44e73c3e2494c3ceaa2a42f6e575ea09a8ee7c396bf3821b4d">BackwardVectorizable</a>, <a href="#ae336b0e8514b99a44e73c3e2494c3ceaa219afbca7ad4b6a18f20c507b7b12353">BackwardVectorizableButPreventsForwarding</a>, <a href="#ae336b0e8514b99a44e73c3e2494c3ceaa0e2ea83a39804701390079f7d07ed112">Forward</a>, <a href="#ae336b0e8514b99a44e73c3e2494c3ceaaec0ae061c48cbea01461ccb40dbc4c7a">ForwardButPreventsForwarding</a>, <a href="#ae336b0e8514b99a44e73c3e2494c3ceaa006edf4988ecca6989849eb1e4b92662">IndirectUnsafe</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#ae336b0e8514b99a44e73c3e2494c3ceaae12470995d757ddbebbd627f397fe349">NoDep</a>, <a href="#a328598cc338e6d6c8d81e6cc4dd68873">Type</a> and <a href="#ae336b0e8514b99a44e73c3e2494c3ceaa3d96a899c885f75def67055e4b486dab">Unknown</a>.</p>


<p>Referenced by <a href="#a4cbfae0900c7bc2adb637840e589ed4e">isPossiblyBackward</a>.</p>

</div>
</div>

### isForward() {#a623aabb69f601ada6b290ac7d15e69a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemoryDepChecker::Dependence::isForward ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lexically forward dependence.</p>

<p>Declaration at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>, definition at line 1716 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>


<p>References <a href="#ae336b0e8514b99a44e73c3e2494c3ceaa4af323986f2ce2d7f10399fe8997096b">Backward</a>, <a href="#ae336b0e8514b99a44e73c3e2494c3ceaa2a42f6e575ea09a8ee7c396bf3821b4d">BackwardVectorizable</a>, <a href="#ae336b0e8514b99a44e73c3e2494c3ceaa219afbca7ad4b6a18f20c507b7b12353">BackwardVectorizableButPreventsForwarding</a>, <a href="#ae336b0e8514b99a44e73c3e2494c3ceaa0e2ea83a39804701390079f7d07ed112">Forward</a>, <a href="#ae336b0e8514b99a44e73c3e2494c3ceaaec0ae061c48cbea01461ccb40dbc4c7a">ForwardButPreventsForwarding</a>, <a href="#ae336b0e8514b99a44e73c3e2494c3ceaa006edf4988ecca6989849eb1e4b92662">IndirectUnsafe</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#ae336b0e8514b99a44e73c3e2494c3ceaae12470995d757ddbebbd627f397fe349">NoDep</a>, <a href="#a328598cc338e6d6c8d81e6cc4dd68873">Type</a> and <a href="#ae336b0e8514b99a44e73c3e2494c3ceaa3d96a899c885f75def67055e4b486dab">Unknown</a>.</p>

</div>
</div>

### isPossiblyBackward() {#a4cbfae0900c7bc2adb637840e589ed4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemoryDepChecker::Dependence::isPossiblyBackward ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>May be a lexically backward dependence type (includes Unknown).</p>

<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>, definition at line 1712 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>


<p>References <a href="#ae336b0e8514b99a44e73c3e2494c3ceaa006edf4988ecca6989849eb1e4b92662">IndirectUnsafe</a>, <a href="#a68f3caaf7ba7f284e0feb00ae907e4c2">isBackward</a>, <a href="#a328598cc338e6d6c8d81e6cc4dd68873">Type</a> and <a href="#ae336b0e8514b99a44e73c3e2494c3ceaa3d96a899c885f75def67055e4b486dab">Unknown</a>.</p>

</div>
</div>

### print() {#a8169d805ee357d7dc129683171b02a7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemoryDepChecker::Dependence::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, unsigned Depth, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; Instrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the dependence.</p>


<p><span class="doxyComputerOutput">Instr</span> is used to map the instruction indices to instructions.</p>


<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>, definition at line 2351 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>


<p>References <a href="#af1ce4569bdd7d1341b095de3aeeb2765">DepName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="#a3d4c114023f646b32b50625f4f830c9b">Destination</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a>, <a href="#ad3bc38ce52bab4fecf99d63404db047e">Source</a> and <a href="#a328598cc338e6d6c8d81e6cc4dd68873">Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo/#a8acfde41662b7ec9d592d905da1dbb22">llvm::LoopAccessInfo::print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Destination {#a3d4c114023f646b32b50625f4f830c9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MemoryDepChecker::Dependence::Destination</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Index of the destination of the dependence in the InstMap vector.</p>

<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<p>Referenced by <a href="#a40efa3de48a570060d0db38b654d9ea3">Dependence</a>, <a href="#a29795bb317fb25a2cb114309a80a19f2">getDestination</a> and <a href="#a8169d805ee357d7dc129683171b02a7f">print</a>.</p>

</div>
</div>

### Source {#ad3bc38ce52bab4fecf99d63404db047e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MemoryDepChecker::Dependence::Source</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Index of the source of the dependence in the InstMap vector.</p>

<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<p>Referenced by <a href="#a40efa3de48a570060d0db38b654d9ea3">Dependence</a>, <a href="#a587c4bfaaf058747310f58b2f8d14f1c">getSource</a> and <a href="#a8169d805ee357d7dc129683171b02a7f">print</a>.</p>

</div>
</div>

### Type {#a328598cc338e6d6c8d81e6cc4dd68873}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DepType llvm::MemoryDepChecker::Dependence::Type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The type of the dependence.</p>

<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<p>Referenced by <a href="#a40efa3de48a570060d0db38b654d9ea3">Dependence</a>, <a href="#a68f3caaf7ba7f284e0feb00ae907e4c2">isBackward</a>, <a href="#a623aabb69f601ada6b290ac7d15e69a5">isForward</a>, <a href="#a4cbfae0900c7bc2adb637840e589ed4e">isPossiblyBackward</a>, <a href="#af7e624cd937996851e961d72cdca670d">isSafeForVectorization</a> and <a href="#a8169d805ee357d7dc129683171b02a7f">print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### isSafeForVectorization() {#af7e624cd937996851e961d72cdca670d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryDepChecker::VectorizationSafetyStatus MemoryDepChecker::Dependence::isSafeForVectorization (<a href="#ae336b0e8514b99a44e73c3e2494c3cea">DepType</a> Type)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/structs/llvm/memorydepchecker/dependence">Dependence</a> types that don't prevent vectorization.</p>

<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>, definition at line 1677 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>


<p>References <a href="#ae336b0e8514b99a44e73c3e2494c3ceaa4af323986f2ce2d7f10399fe8997096b">Backward</a>, <a href="#ae336b0e8514b99a44e73c3e2494c3ceaa2a42f6e575ea09a8ee7c396bf3821b4d">BackwardVectorizable</a>, <a href="#ae336b0e8514b99a44e73c3e2494c3ceaa219afbca7ad4b6a18f20c507b7b12353">BackwardVectorizableButPreventsForwarding</a>, <a href="#ae336b0e8514b99a44e73c3e2494c3ceaa0e2ea83a39804701390079f7d07ed112">Forward</a>, <a href="#ae336b0e8514b99a44e73c3e2494c3ceaaec0ae061c48cbea01461ccb40dbc4c7a">ForwardButPreventsForwarding</a>, <a href="#ae336b0e8514b99a44e73c3e2494c3ceaa006edf4988ecca6989849eb1e4b92662">IndirectUnsafe</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#ae336b0e8514b99a44e73c3e2494c3ceaae12470995d757ddbebbd627f397fe349">NoDep</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydepchecker/#ac661dd363bcde8b1e9516390eff1c400ad1b0fb720d53739ff1265c71d6977de8">llvm::MemoryDepChecker::PossiblySafeWithRtChecks</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydepchecker/#ac661dd363bcde8b1e9516390eff1c400ac6eea0560cd6f377e78dff2c85cc9122">llvm::MemoryDepChecker::Safe</a>, <a href="#a328598cc338e6d6c8d81e6cc4dd68873">Type</a>, <a href="#ae336b0e8514b99a44e73c3e2494c3ceaa3d96a899c885f75def67055e4b486dab">Unknown</a> and <a href="/web-llvm/docs/api/classes/llvm/memorydepchecker/#ac661dd363bcde8b1e9516390eff1c400ad3d57868b6ff9839eff631d2cc8acbce">llvm::MemoryDepChecker::Unsafe</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memorydepchecker/#a2e54d4cd15784b0f0480ca88bcf3165f">llvm::MemoryDepChecker::areDepsSafe</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### DepName {#af1ce4569bdd7d1341b095de3aeeb2765}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * MemoryDepChecker::Dependence::DepName</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>String version of the types.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    "NoDep",
    "Unknown",
    "IndirectUnsafe",
    "Forward",
    "ForwardButPreventsForwarding",
    "Backward",
    "BackwardVectorizable",
    "BackwardVectorizableButPreventsForwarding"}
</div>
</dd>
</dl>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<p>Referenced by <a href="#a8169d805ee357d7dc129683171b02a7f">print</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
