---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/targettransforminfo/peelingpreferences
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `PeelingPreferences` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::TargetTransformInfo::PeelingPreferences { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">llvm/Analysis/TargetTransformInfo.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93102207c7c9430df6ef02447446de9b">PeelCount</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A forced peeling factor (the number of bodied of the original loop that should be peeled off before the loop body). <a href="#a93102207c7c9430df6ef02447446de9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3421601051b06ed7b52a09696bd595b2">AllowPeeling</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow peeling off loop iterations. <a href="#a3421601051b06ed7b52a09696bd595b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71809834780876145831c63077461284">AllowLoopNestsPeeling</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow peeling off loop iterations for loop nests. <a href="#a71809834780876145831c63077461284">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89c02eecae37f89bf86f71336630858d">PeelProfiledIterations</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow peeling basing on profile. <a href="#a89c02eecae37f89bf86f71336630858d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 663 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### AllowLoopNestsPeeling {#a71809834780876145831c63077461284}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetTransformInfo::PeelingPreferences::AllowLoopNestsPeeling</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allow peeling off loop iterations for loop nests.</p>

<p>Definition at line 671 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1b8329ea8794c1e6fa1294a1e5a463dd">llvm::computePeelCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6e86d0ac2e968adc60290ca52da02e42">llvm::gatherPeelingPreferences</a> and <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a9d093749d001a714592c88df0e81b3fe">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getPeelingPreferences</a>.</p>

</div>
</div>

### AllowPeeling {#a3421601051b06ed7b52a09696bd595b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetTransformInfo::PeelingPreferences::AllowPeeling</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allow peeling off loop iterations.</p>

<p>Definition at line 669 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1b8329ea8794c1e6fa1294a1e5a463dd">llvm::computePeelCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6e86d0ac2e968adc60290ca52da02e42">llvm::gatherPeelingPreferences</a> and <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a9d093749d001a714592c88df0e81b3fe">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getPeelingPreferences</a>.</p>

</div>
</div>

### PeelCount {#a93102207c7c9430df6ef02447446de9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetTransformInfo::PeelingPreferences::PeelCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A forced peeling factor (the number of bodied of the original loop that should be peeled off before the loop body).</p>


<p>When set to 0, the a peeling factor based on profile information and other factors.</p>


<p>Definition at line 667 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1b8329ea8794c1e6fa1294a1e5a463dd">llvm::computePeelCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a921421142b15c9fb9196fc4b0d7b77cb">llvm::computeUnrollCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6e86d0ac2e968adc60290ca52da02e42">llvm::gatherPeelingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a9d093749d001a714592c88df0e81b3fe">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getPeelingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonttiimpl/#a9b9400acc54f0441d15d8bda0d27caf7">llvm::HexagonTTIImpl::getPeelingPreferences</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#ab6df82212b20d28e61ff9417744420ff">tryToUnrollLoop</a>.</p>

</div>
</div>

### PeelProfiledIterations {#a89c02eecae37f89bf86f71336630858d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetTransformInfo::PeelingPreferences::PeelProfiledIterations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allow peeling basing on profile.</p>


<p>Uses to enable peeling off all iterations basing on provided profile. If the value is true the peeling cost model can decide to peel only some iterations and in this case it will set this to false.</p>


<p>Definition at line 676 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1b8329ea8794c1e6fa1294a1e5a463dd">llvm::computePeelCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6e86d0ac2e968adc60290ca52da02e42">llvm::gatherPeelingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a9d093749d001a714592c88df0e81b3fe">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getPeelingPreferences</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#ab6df82212b20d28e61ff9417744420ff">tryToUnrollLoop</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
