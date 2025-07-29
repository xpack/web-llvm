---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-dataflowsanitizer-cpp-/transformedfunction
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `TransformedFunction` Struct

<p><a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/transformedfunction">TransformedFunction</a> is used to express the result of transforming one function type into another. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{DataFlowSanitizer.cpp}::TransformedFunction { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a540553d433997e37f9ec297e050fd305">TransformedFunction</a> (FunctionType *OriginalType, FunctionType *TransformedType, const std::vector&lt; unsigned &gt; &amp;ArgumentIndexMapping)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa81d781c4b52de2f5a7ceee0d588ee17">TransformedFunction</a> (const TransformedFunction &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a944ac4bc7de31c1effccea0631ca7e2f">TransformedFunction</a> (TransformedFunction &amp;&amp;)=default</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/transformedfunction">TransformedFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e1c50c7751a36279bceba23c338249f">operator=</a> (const TransformedFunction &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/transformedfunction">TransformedFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18e23e02126c8fd10548c05c5e727e98">operator=</a> (TransformedFunction &amp;&amp;)=default</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f8428ade5405ff3f60f6931073024d6">OriginalType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> of the function before the transformation. <a href="#a2f8428ade5405ff3f60f6931073024d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eaef9f97f7a9f88c4074dd207541b88">TransformedType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> of the function after the transformation. <a href="#a6eaef9f97f7a9f88c4074dd207541b88">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee9b90c50e4cab5497133418264f68c">ArgumentIndexMapping</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transforming a function may change the position of arguments. <a href="#a7ee9b90c50e4cab5497133418264f68c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/transformedfunction">TransformedFunction</a> is used to express the result of transforming one function type into another.</p>


<p>This struct is immutable. It holds metadata useful for updating calls of the old function to the new type.</p>


<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TransformedFunction() {#a540553d433997e37f9ec297e050fd305}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{DataFlowSanitizer.cpp}::TransformedFunction::TransformedFunction (<a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * OriginalType, <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * TransformedType, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; unsigned &gt; &amp; ArgumentIndexMapping)</td>
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



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>References <a href="#a7ee9b90c50e4cab5497133418264f68c">ArgumentIndexMapping</a>, <a href="#a2f8428ade5405ff3f60f6931073024d6">OriginalType</a> and <a href="#a6eaef9f97f7a9f88c4074dd207541b88">TransformedType</a>.</p>


<p>Referenced by <a href="#a0e1c50c7751a36279bceba23c338249f">operator=</a>, <a href="#a18e23e02126c8fd10548c05c5e727e98">operator=</a>, <a href="#aa81d781c4b52de2f5a7ceee0d588ee17">TransformedFunction</a> and <a href="#a944ac4bc7de31c1effccea0631ca7e2f">TransformedFunction</a>.</p>

</div>
</div>

### TransformedFunction() {#aa81d781c4b52de2f5a7ceee0d588ee17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{DataFlowSanitizer.cpp}::TransformedFunction::TransformedFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/transformedfunction">TransformedFunction</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>Reference <a href="#a540553d433997e37f9ec297e050fd305">TransformedFunction</a>.</p>

</div>
</div>

### TransformedFunction() {#a944ac4bc7de31c1effccea0631ca7e2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{DataFlowSanitizer.cpp}::TransformedFunction::TransformedFunction (<a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/transformedfunction">TransformedFunction</a> &amp;&amp;)</td>
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



<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>Reference <a href="#a540553d433997e37f9ec297e050fd305">TransformedFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a0e1c50c7751a36279bceba23c338249f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TransformedFunction &amp; anonymous{DataFlowSanitizer.cpp}::TransformedFunction::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/transformedfunction">TransformedFunction</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>Reference <a href="#a540553d433997e37f9ec297e050fd305">TransformedFunction</a>.</p>

</div>
</div>

### operator=() {#a18e23e02126c8fd10548c05c5e727e98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TransformedFunction &amp; anonymous{DataFlowSanitizer.cpp}::TransformedFunction::operator= (<a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/transformedfunction">TransformedFunction</a> &amp;&amp;)</td>
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



<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>Reference <a href="#a540553d433997e37f9ec297e050fd305">TransformedFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ArgumentIndexMapping {#a7ee9b90c50e4cab5497133418264f68c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;unsigned&gt; anonymous{DataFlowSanitizer.cpp}::TransformedFunction::ArgumentIndexMapping</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transforming a function may change the position of arguments.</p>


<p>This member records the mapping from each argument's old position to its new position. <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> positions are zero-indexed. If the transformation from F to F' made the first argument of F into the third argument of F', then ArgumentIndexMapping[0] will equal 2.</p>


<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a540553d433997e37f9ec297e050fd305">TransformedFunction</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-dataflowsanitizer-cpp-/#a284ebf18528088df1b6da4af334a545b">anonymous{DataFlowSanitizer.cpp}::transformFunctionAttributes</a>.</p>

</div>
</div>

### OriginalType {#a2f8428ade5405ff3f60f6931073024d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType* anonymous{DataFlowSanitizer.cpp}::TransformedFunction::OriginalType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> of the function before the transformation.</p>

<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a540553d433997e37f9ec297e050fd305">TransformedFunction</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-dataflowsanitizer-cpp-/#a284ebf18528088df1b6da4af334a545b">anonymous{DataFlowSanitizer.cpp}::transformFunctionAttributes</a>.</p>

</div>
</div>

### TransformedType {#a6eaef9f97f7a9f88c4074dd207541b88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType* anonymous{DataFlowSanitizer.cpp}::TransformedFunction::TransformedType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> of the function after the transformation.</p>

<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a540553d433997e37f9ec297e050fd305">TransformedFunction</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-dataflowsanitizer-cpp-/#a284ebf18528088df1b6da4af334a545b">anonymous{DataFlowSanitizer.cpp}::transformFunctionAttributes</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
