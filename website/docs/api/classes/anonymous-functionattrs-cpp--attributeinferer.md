---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-functionattrs-cpp-/attributeinferer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AttributeInferer` Class Reference

<p>Collects a set of attribute inference requests and performs them all in one go on a single SCC <a href="/web-llvm/docs/api/classes/node">Node</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{FunctionAttrs.cpp}::AttributeInferer { ... }
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a314532e07f85e5eee1f874a5d79598ff">registerAttrInference</a> (InferenceDescriptor AttrInference)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a322a5409ce5be2c9d2045f16b8439048">run</a> (const SCCNodeSet &amp;SCCNodes, SmallSet&lt; Function *, 8 &gt; &amp;Changed)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform all the requested attribute inference actions according to the attribute predicates stored before. <a href="#a322a5409ce5be2c9d2045f16b8439048">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-functionattrs-cpp-/attributeinferer/inferencedescriptor">InferenceDescriptor</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62e263c6bd7d9041d930aa222bd8659c">InferenceDescriptors</a></td>
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

<p>Collects a set of attribute inference requests and performs them all in one go on a single SCC <a href="/web-llvm/docs/api/classes/node">Node</a>.</p>


<p>Inference involves scanning function bodies looking for instructions that violate attribute assumptions. As soon as all the bodies are fine we are free to set the attribute. Customization of inference for individual attributes is performed by providing a handful of predicates for each attribute.</p>


<p>Definition at line 1679 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp">FunctionAttrs.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### registerAttrInference() {#a314532e07f85e5eee1f874a5d79598ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{FunctionAttrs.cpp}::AttributeInferer::registerAttrInference (<a href="/web-llvm/docs/api/structs/anonymous-functionattrs-cpp-/attributeinferer/inferencedescriptor">InferenceDescriptor</a> AttrInference)</td>
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



<p>Definition at line 1717 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp">FunctionAttrs.cpp</a>.</p>

</div>
</div>

### run() {#a322a5409ce5be2c9d2045f16b8439048}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{FunctionAttrs.cpp}::AttributeInferer::run (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/anonymous-functionattrs-cpp-/#ae5e7383d35ed634befab95c8c2c99a1b">SCCNodeSet</a> &amp; SCCNodes, <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, 8 &gt; &amp; Changed)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform all the requested attribute inference actions according to the attribute predicates stored before.</p>

<p>Definition at line 1721 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp">FunctionAttrs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d13fd05401d8eb0c97b9864a0eb6028">llvm::copy_if</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a7de5a04920954ac964059cfc428ad">llvm::erase_if</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### InferenceDescriptors {#a62e263c6bd7d9041d930aa222bd8659c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;InferenceDescriptor, 4&gt; anonymous{FunctionAttrs.cpp}::AttributeInferer::InferenceDescriptors</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1714 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp">FunctionAttrs.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp">FunctionAttrs.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
