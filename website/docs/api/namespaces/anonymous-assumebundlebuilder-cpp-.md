---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-assumebundlebuilder-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{AssumeBundleBuilder.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{AssumeBundleBuilder.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate">AssumeBuilderState</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class contain all knowledge that have been gather while building an llvm.assume and the function to manipulate it. <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumesimplify">AssumeSimplify</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3399afc79b7612b8471c010d3f3638e">isUsefullToPreserve</a> (Attribute::AttrKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/retainedknowledge">RetainedKnowledge</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3d9d3b5408e22143d8aee0d684454c4">canonicalizedKnowledge</a> (RetainedKnowledge RK, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function will try to transform the given knowledge into a more canonical one. <a href="#ae3d9d3b5408e22143d8aee0d684454c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa816756908e8f79bdcf1b5871e78a9ca">simplifyAssumes</a> (Function &amp;F, AssumptionCache *AC, DominatorTree *DT)</td>
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


<div class="doxySectionDef">

## Functions

### canonicalizedKnowledge() {#ae3d9d3b5408e22143d8aee0d684454c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetainedKnowledge anonymous{AssumeBundleBuilder.cpp}::canonicalizedKnowledge (<a href="/web-llvm/docs/api/structs/llvm/retainedknowledge">RetainedKnowledge</a> RK, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function will try to transform the given knowledge into a more canonical one.</p>


<p>the canonical knowledge maybe the given one.</p>


<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/retainedknowledge/#a3b64a97b9157b9bd9a1d924cae66254b">llvm::RetainedKnowledge::ArgValue</a>, <a href="/web-llvm/docs/api/structs/llvm/retainedknowledge/#a054a26c551d4de8f1af4d75a7a67a42a">llvm::RetainedKnowledge::AttrKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3ac5d9eb48038aa973017317279eadf5">llvm::GetPointerBaseWithConstantOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b1c5788b85ffa254be0e834edf5cf8f">llvm::getUnderlyingObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59f98bbb1f440db8d5db1c8b5bd819f6">llvm::MinAlign</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ed745230c0e6c52f4b1ec0dae8c07fb">llvm::Value::stripInBoundsOffsets</a> and <a href="/web-llvm/docs/api/structs/llvm/retainedknowledge/#a99ac6afa72b262e95ceb85328c6cb5c6">llvm::RetainedKnowledge::WasOn</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#a201cb1ede84e08442e7433b7b3eaed69">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::addKnowledge</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a21fa9fb3ba25eaa02fae01f428ef2fdf">llvm::simplifyRetainedKnowledge</a>.</p>

</div>
</div>

### isUsefullToPreserve() {#ab3399afc79b7612b8471c010d3f3638e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AssumeBundleBuilder.cpp}::isUsefullToPreserve (Attribute::AttrKind Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#aa411f806557fdaf4af309b7c541757d2">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::addAttribute</a>.</p>

</div>
</div>

### simplifyAssumes() {#aa816756908e8f79bdcf1b5871e78a9ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AssumeBundleBuilder.cpp}::simplifyAssumes (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 545 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumesimplify/#a0879506ce04a79b173daca40d1967e35">anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::dropRedundantKnowledge</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumesimplify/#a239c7971faca8f43b6528d7bc217b7dd">anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::MadeChange</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumesimplify/#a1dc2ed29bdcb3fedb0639cc8e88a7ecd">anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::mergeAssumes</a> and <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumesimplify/#a0e2f2e4897006cc2a16468e9e99f7b6d">anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::RunCleanup</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
