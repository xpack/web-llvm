---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/typeswitch
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `TypeSwitch` Class Template

<p>This class implements a switch-like dispatch statement for a value of 'T' using dyn_cast functionality. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T, typename ResultT = void&gt;
class llvm::TypeSwitch&lt;T, ResultT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/typeswitch-h">llvm/ADT/TypeSwitch.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/typeswitchbase">TypeSwitchBase&lt;DerivedT, T&gt;</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename ResultT = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0e98bbeaba6fbd292907110f3b350885">BaseT</a> = <a href="/web-llvm/docs/api/classes/llvm/detail/typeswitchbase">detail::TypeSwitchBase</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/typeswitch">TypeSwitch</a>&lt; T, ResultT &gt;, T &gt;</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename ResultT = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a5f8b4c9ccb1bab34c84ccbd45a5ea30e">TypeSwitch</a> (TypeSwitch &amp;&amp;other)=default</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename ResultT = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#afbd47b7a2eaa69d7fa65aef1206d1899">operator ResultT</a> ()</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename CaseT, typename CallableT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a78c545287cbe57529ce7751e25c815a5">Case</a> (CallableT &amp;&amp;caseFn) -&gt; <a href="/web-llvm/docs/api/classes/llvm/typeswitch">TypeSwitch</a>&lt; T, ResultT &gt; &amp;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a case on the given type. <a href="#a78c545287cbe57529ce7751e25c815a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename CallableT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">ResultT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a52d46e4f7483f96b4d5f1b8a2b20cca6">Default</a> (CallableT &amp;&amp;defaultFn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>As a default, invoke the given callable within the root value. <a href="#a52d46e4f7483f96b4d5f1b8a2b20cca6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename ResultT = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">ResultT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5ee781e919541e19e824c26204d98fe2">Default</a> (ResultT defaultResult)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>As a default, return the given value. <a href="#a5ee781e919541e19e824c26204d98fe2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename ResultT = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::optional&lt; ResultT &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab241ebc8f099792967cdc9dd7070b32b">result</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The pointer to the result of this switch statement, once known, null before that. <a href="#ab241ebc8f099792967cdc9dd7070b32b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class implements a switch-like dispatch statement for a value of 'T' using dyn_cast functionality.</p>


<p>Each <span class="doxyComputerOutput">Case&lt;T&gt;</span> takes a callable to be invoked if the root value isa&lt;T&gt;, the callable is invoked with the result of <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">dyn_cast&lt;T&gt;()</a> as a parameter.</p>


<p>Example: Operation *op = ...; <a href="/web-llvm/docs/api/structs/llvm/logicalresult">LogicalResult</a> result = TypeSwitch&lt;Operation *, LogicalResult&gt;(op) .Case&lt;ConstantOp&gt;([](ConstantOp op) { ... }) .Default([](Operation *op) { ... });</p>


<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/typeswitch-h">TypeSwitch.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### BaseT {#a0e98bbeaba6fbd292907110f3b350885}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename ResultT = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::TypeSwitch&lt; T, ResultT &gt;::BaseT =  detail::TypeSwitchBase&lt;TypeSwitch&lt;T, ResultT&gt;, T&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/typeswitch-h">TypeSwitch.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### TypeSwitch() {#a5f8b4c9ccb1bab34c84ccbd45a5ea30e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename ResultT = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TypeSwitch&lt; T, ResultT &gt;::TypeSwitch (<a href="/web-llvm/docs/api/classes/llvm/typeswitch">TypeSwitch</a> &amp;&amp; other)</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/typeswitch-h">TypeSwitch.h</a>.</p>


<p>Reference <a href="#a5f8b4c9ccb1bab34c84ccbd45a5ea30e">llvm::TypeSwitch&lt; T, ResultT &gt;::TypeSwitch</a>.</p>


<p>Referenced by <a href="#a78c545287cbe57529ce7751e25c815a5">llvm::TypeSwitch&lt; T, ResultT &gt;::Case</a> and <a href="#a5f8b4c9ccb1bab34c84ccbd45a5ea30e">llvm::TypeSwitch&lt; T, ResultT &gt;::TypeSwitch</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator ResultT() {#afbd47b7a2eaa69d7fa65aef1206d1899}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename ResultT = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TypeSwitch&lt; T, ResultT &gt;::operator ResultT ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/typeswitch-h">TypeSwitch.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### Case() {#a78c545287cbe57529ce7751e25c815a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename CaseT, typename CallableT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeSwitch&lt; T, ResultT &gt; &amp; llvm::TypeSwitch&lt; T, ResultT &gt;::Case (CallableT &amp;&amp; caseFn)</td>
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

<p>Add a case on the given type.</p>

<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/typeswitch-h">TypeSwitch.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/detail/typeswitchbase/#a47c8f0bc76ad4fa3a6f2dc31e77604ba">llvm::detail::TypeSwitchBase&lt; TypeSwitch&lt; T, void &gt;, T &gt;::castValue</a>, <a href="#a5f8b4c9ccb1bab34c84ccbd45a5ea30e">llvm::TypeSwitch&lt; T, ResultT &gt;::TypeSwitch</a> and <a href="/web-llvm/docs/api/classes/llvm/detail/typeswitchbase/#ac90e9cd026c236f96b3800b5db4ecb88">llvm::detail::TypeSwitchBase&lt; TypeSwitch&lt; T, void &gt;, T &gt;::value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#ad0faf4b8ff1cf3306958d056dcb2fde2">createEVLRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#aa216c2cbc8d9610dc20db065aca671d3">llvm::LoopVectorizationPlanner::emitInvalidCostRemarks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a5999b0390c92ee4af2544fe9772454bf">llvm::vputils::getSCEVExprForVPValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vptypeanalysis/#aac3fb75b481d61e325b6d869d0f5f278">llvm::VPTypeAnalysis::inferScalarType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a0c663bf15e8398176f591270e7676f96">llvm::vputils::isUniformAcrossVFsAndUFs</a>.</p>

</div>
</div>

### Default() {#a52d46e4f7483f96b4d5f1b8a2b20cca6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename CallableT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ResultT llvm::TypeSwitch&lt; T, ResultT &gt;::Default (CallableT &amp;&amp; defaultFn)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>As a default, invoke the given callable within the root value.</p>

<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/typeswitch-h">TypeSwitch.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/detail/typeswitchbase/#ac90e9cd026c236f96b3800b5db4ecb88">llvm::detail::TypeSwitchBase&lt; TypeSwitch&lt; T, void &gt;, T &gt;::value</a>.</p>

</div>
</div>

### Default() {#a5ee781e919541e19e824c26204d98fe2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename ResultT = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ResultT llvm::TypeSwitch&lt; T, ResultT &gt;::Default (ResultT defaultResult)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>As a default, return the given value.</p>

<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/typeswitch-h">TypeSwitch.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### result {#ab241ebc8f099792967cdc9dd7070b32b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename ResultT = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;ResultT&gt; llvm::TypeSwitch&lt; T, ResultT &gt;::result</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The pointer to the result of this switch statement, once known, null before that.</p>

<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/typeswitch-h">TypeSwitch.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/typeswitch-h">TypeSwitch.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
