---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-x86loweramxtype-cpp-/x86volatiletiledata
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `X86VolatileTileData` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{X86LowerAMXType.cpp}::X86VolatileTileData { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a276c0ab02eb7fbabfd714b4df79caf">X86VolatileTileData</a> (Function &amp;Func)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32cdbea620898dd330525454e568cbb7">updatePhiIncomings</a> (BasicBlock *BB, SmallVector&lt; Instruction *, 2 &gt; &amp;Incomings)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08cafff5f8ac9e8fa42633409bc04d90">replacePhiDefWithLoad</a> (Instruction *PHI, Value *StorePtr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb433ec9d181eb8f489c857b23c55535">volatileTileData</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f767b83cb14d5a70423c68254648c18">volatileTilePHI</a> (PHINode *PHI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae77aa371550f54db6fe53ff0459c700d">volatileTileNonPHI</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14965d38e557198922f30813cc73f5a2">F</a></td>
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


<p>Definition at line 662 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxtype-cpp">X86LowerAMXType.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### X86VolatileTileData() {#a0a276c0ab02eb7fbabfd714b4df79caf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{X86LowerAMXType.cpp}::X86VolatileTileData::X86VolatileTileData (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Func)</td>
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



<p>Definition at line 666 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxtype-cpp">X86LowerAMXType.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### replacePhiDefWithLoad() {#a08cafff5f8ac9e8fa42633409bc04d90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{X86LowerAMXType.cpp}::X86VolatileTileData::replacePhiDefWithLoad (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * PHI, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * StorePtr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 669 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxtype-cpp">X86LowerAMXType.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxtype-cpp/#a20c7ea50a73d61a91772d1c57f2baade">replaceWithTileLoad</a>.</p>


<p>Referenced by <a href="#a4f767b83cb14d5a70423c68254648c18">volatileTilePHI</a>.</p>

</div>
</div>

### updatePhiIncomings() {#a32cdbea620898dd330525454e568cbb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{X86LowerAMXType.cpp}::X86VolatileTileData::updatePhiIncomings (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 2 &gt; &amp; Incomings)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 667 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxtype-cpp">X86LowerAMXType.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxtype-cpp/#a26d326912ec9ff7ea15f2b356f5d31eb">createTileStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxtype-cpp/#a660392f54efb6a70e2b59a840ccf1728">getAllocaPos</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxtype-cpp/#a20c7ea50a73d61a91772d1c57f2baade">replaceWithTileLoad</a>.</p>


<p>Referenced by <a href="#a4f767b83cb14d5a70423c68254648c18">volatileTilePHI</a>.</p>

</div>
</div>

### volatileTileData() {#aeb433ec9d181eb8f489c857b23c55535}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86LowerAMXType.cpp}::X86VolatileTileData::volatileTileData ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 670 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxtype-cpp">X86LowerAMXType.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxtype-cpp/#acf41daf3eeda8514648fe10fbd699be7">isIncomingOfPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#ae77aa371550f54db6fe53ff0459c700d">volatileTileNonPHI</a> and <a href="#a4f767b83cb14d5a70423c68254648c18">volatileTilePHI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxtypelegacypass/#a63b5e6f11338cd1363537097457e4265">anonymous{X86LowerAMXType.cpp}::X86LowerAMXTypeLegacyPass::runOnFunction</a>.</p>

</div>
</div>

### volatileTileNonPHI() {#ae77aa371550f54db6fe53ff0459c700d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{X86LowerAMXType.cpp}::X86VolatileTileData::volatileTileNonPHI (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 672 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxtype-cpp">X86LowerAMXType.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxtype-cpp/#a26d326912ec9ff7ea15f2b356f5d31eb">createTileStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxtype-cpp/#a660392f54efb6a70e2b59a840ccf1728">getAllocaPos</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxtype-cpp/#a20c7ea50a73d61a91772d1c57f2baade">replaceWithTileLoad</a>.</p>


<p>Referenced by <a href="#aeb433ec9d181eb8f489c857b23c55535">volatileTileData</a>.</p>

</div>
</div>

### volatileTilePHI() {#a4f767b83cb14d5a70423c68254648c18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{X86LowerAMXType.cpp}::X86VolatileTileData::volatileTilePHI (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * PHI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 671 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxtype-cpp">X86LowerAMXType.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a08cafff5f8ac9e8fa42633409bc04d90">replacePhiDefWithLoad</a> and <a href="#a32cdbea620898dd330525454e568cbb7">updatePhiIncomings</a>.</p>


<p>Referenced by <a href="#aeb433ec9d181eb8f489c857b23c55535">volatileTileData</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### F {#a14965d38e557198922f30813cc73f5a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function&amp; anonymous{X86LowerAMXType.cpp}::X86VolatileTileData::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 663 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxtype-cpp">X86LowerAMXType.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxtype-cpp">X86LowerAMXType.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
