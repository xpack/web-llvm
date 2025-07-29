---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/functionpropertiesupdater
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `FunctionPropertiesUpdater` Class

<p>Correctly update <a href="/web-llvm/docs/api/classes/llvm/functionpropertiesinfo">FunctionPropertiesInfo</a> post-inlining. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::FunctionPropertiesUpdater { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">llvm/Analysis/FunctionPropertiesAnalysis.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ba00e4f051e690dfe2e14625ce165d3">FunctionPropertiesUpdater</a> (FunctionPropertiesInfo &amp;FPI, CallBase &amp;CB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53810b3b6ca8d3846b024899661c5e4a">finish</a> (FunctionAnalysisManager &amp;FAM) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ce3135b0a1f6d6c05a38f92126bc526">finishAndTest</a> (FunctionAnalysisManager &amp;FAM) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0edd2d1a08b62b0f009af78697526382">getUpdatedDominatorTree</a> (FunctionAnalysisManager &amp;FAM) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functionpropertiesinfo">FunctionPropertiesInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd9963aa36dc6d19186ae2fc3c6dd2ca">FPI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88d8ba65aa17d6fb80c4795dd989f080">CallSiteBB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a6f0b76850d58cfb23cd8a9d4aedd6b">Caller</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad878a73d2ed25091c9f6b1dc43603a29">Successors</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#aca76acb70a839a2462d3e9ae346e1eb0">DominatorTree::UpdateType</a>, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8417a1311fd385d39242ce023059e69b">DomTreeUpdates</a></td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab05bcbf5897f3f995136f9e442629a7c">isUpdateValid</a> (Function &amp;F, const FunctionPropertiesInfo &amp;FPI, FunctionAnalysisManager &amp;FAM)</td>
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

<p>Correctly update <a href="/web-llvm/docs/api/classes/llvm/functionpropertiesinfo">FunctionPropertiesInfo</a> post-inlining.</p>


<p>A <a href="/web-llvm/docs/api/classes/llvm/functionpropertiesupdater">FunctionPropertiesUpdater</a> keeps the state necessary for tracking the changes <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a> makes. The idea is that inlining will at most modify a few BBs of the Caller (maybe the entry BB and definitely the callsite BB) and potentially affect exception handling BBs in the case of invoke inlining.</p>


<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FunctionPropertiesUpdater() {#a1ba00e4f051e690dfe2e14625ce165d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPropertiesUpdater::FunctionPropertiesUpdater (<a href="/web-llvm/docs/api/classes/llvm/functionpropertiesinfo">FunctionPropertiesInfo</a> &amp; FPI, <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>, definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/functionpropertiesanalysis-cpp">FunctionPropertiesAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9aa408bc83db2292cc1a57a3e6b206c2">llvm::succ_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5684e4976198c1b64b694d3972ddf78">llvm::succ_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### finish() {#a53810b3b6ca8d3846b024899661c5e4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionPropertiesUpdater::finish (<a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> &amp; FAM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>, definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/functionpropertiesanalysis-cpp">FunctionPropertiesAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a1a42c1ba878bd637f374197d05f0a97f">llvm::SetVector&lt; T, Vector, Set, N &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9aa408bc83db2292cc1a57a3e6b206c2">llvm::succ_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5684e4976198c1b64b694d3972ddf78">llvm::succ_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>.</p>


<p>Referenced by <a href="#a8ce3135b0a1f6d6c05a38f92126bc526">finishAndTest</a>.</p>

</div>
</div>

### finishAndTest() {#a8ce3135b0a1f6d6c05a38f92126bc526}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FunctionPropertiesUpdater::finishAndTest (<a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> &amp; FAM)</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a> and <a href="#a53810b3b6ca8d3846b024899661c5e4a">finish</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getUpdatedDominatorTree() {#a0edd2d1a08b62b0f009af78697526382}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree &amp; FunctionPropertiesUpdater::getUpdatedDominatorTree (<a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> &amp; FAM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>, definition at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/functionpropertiesanalysis-cpp">FunctionPropertiesAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Caller {#a9a6f0b76850d58cfb23cd8a9d4aedd6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function&amp; llvm::FunctionPropertiesUpdater::Caller</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>

</div>
</div>

### CallSiteBB {#a88d8ba65aa17d6fb80c4795dd989f080}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock&amp; llvm::FunctionPropertiesUpdater::CallSiteBB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>

</div>
</div>

### DomTreeUpdates {#a8417a1311fd385d39242ce023059e69b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;DominatorTree::UpdateType, 2&gt; llvm::FunctionPropertiesUpdater::DomTreeUpdates</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>

</div>
</div>

### FPI {#afd9963aa36dc6d19186ae2fc3c6dd2ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPropertiesInfo&amp; llvm::FunctionPropertiesUpdater::FPI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>

</div>
</div>

### Successors {#ad878a73d2ed25091c9f6b1dc43603a29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;const BasicBlock *&gt; llvm::FunctionPropertiesUpdater::Successors</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### isUpdateValid() {#ab05bcbf5897f3f995136f9e442629a7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FunctionPropertiesUpdater::isUpdateValid (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functionpropertiesinfo">FunctionPropertiesInfo</a> &amp; FPI, <a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> &amp; FAM)</td>
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



<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a>, definition at line 481 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/functionpropertiesanalysis-cpp">FunctionPropertiesAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/functionpropertiesanalysis-h">FunctionPropertiesAnalysis.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/functionpropertiesanalysis-cpp">FunctionPropertiesAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
