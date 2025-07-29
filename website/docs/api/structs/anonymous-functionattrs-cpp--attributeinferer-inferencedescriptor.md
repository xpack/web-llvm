---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-functionattrs-cpp-/attributeinferer/inferencedescriptor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `InferenceDescriptor` Struct

<p>Describes a request for inference of a single attribute. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{FunctionAttrs.cpp}::AttributeInferer::InferenceDescriptor { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e7461606959f6bd3261825d77648e54">InferenceDescriptor</a> (Attribute::AttrKind AK, std::function&lt; bool(const Function &amp;)&gt; SkipFunc, std::function&lt; bool(Instruction &amp;)&gt; InstrScan, std::function&lt; void(Function &amp;)&gt; SetAttr, bool ReqExactDef)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20a121afceb526fe739e2d647a8b40fa">SkipFunction</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this function does not have to be handled. <a href="#a20a121afceb526fe739e2d647a8b40fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp;)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a636947ee80d51e22069bc3ab1d7534e3">InstrBreaksAttribute</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this instruction violates attribute assumptions. <a href="#a636947ee80d51e22069bc3ab1d7534e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08492ef05965dd1d0877068ec4e687c5">SetAttribute</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the inferred attribute for this function. <a href="#a08492ef05965dd1d0877068ec4e687c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2455026da63c7def882730d5c0af61de">AKind</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> we derive. <a href="#a2455026da63c7def882730d5c0af61de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaad765d34835c286ef433f03e072d01a">RequiresExactDefinition</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If true, only "exact" definitions can be used to infer this attribute. <a href="#aaad765d34835c286ef433f03e072d01a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Describes a request for inference of a single attribute.</p>

<p>Definition at line 1682 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp">FunctionAttrs.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InferenceDescriptor() {#a7e7461606959f6bd3261825d77648e54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{FunctionAttrs.cpp}::AttributeInferer::InferenceDescriptor::InferenceDescriptor (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> AK, std::function&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; SkipFunc, std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp;)&gt; InstrScan, std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; SetAttr, bool ReqExactDef)</td>
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



<p>Definition at line 1703 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp">FunctionAttrs.cpp</a>.</p>


<p>References <a href="#a2455026da63c7def882730d5c0af61de">AKind</a>, <a href="#a636947ee80d51e22069bc3ab1d7534e3">InstrBreaksAttribute</a>, <a href="#aaad765d34835c286ef433f03e072d01a">RequiresExactDefinition</a>, <a href="#a08492ef05965dd1d0877068ec4e687c5">SetAttribute</a> and <a href="#a20a121afceb526fe739e2d647a8b40fa">SkipFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AKind {#a2455026da63c7def882730d5c0af61de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute::AttrKind anonymous{FunctionAttrs.cpp}::AttributeInferer::InferenceDescriptor::AKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> we derive.</p>

<p>Definition at line 1697 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp">FunctionAttrs.cpp</a>.</p>


<p>Referenced by <a href="#a7e7461606959f6bd3261825d77648e54">InferenceDescriptor</a>.</p>

</div>
</div>

### InstrBreaksAttribute {#a636947ee80d51e22069bc3ab1d7534e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;bool(Instruction &amp;)&gt; anonymous{FunctionAttrs.cpp}::AttributeInferer::InferenceDescriptor::InstrBreaksAttribute</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this instruction violates attribute assumptions.</p>

<p>Definition at line 1691 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp">FunctionAttrs.cpp</a>.</p>


<p>Referenced by <a href="#a7e7461606959f6bd3261825d77648e54">InferenceDescriptor</a>.</p>

</div>
</div>

### RequiresExactDefinition {#aaad765d34835c286ef433f03e072d01a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{FunctionAttrs.cpp}::AttributeInferer::InferenceDescriptor::RequiresExactDefinition</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If true, only "exact" definitions can be used to infer this attribute.</p>


<p>See <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a008adb117253c7a0dde2f796be489d65">GlobalValue::isDefinitionExact</a>.</p>


<p>Definition at line 1701 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp">FunctionAttrs.cpp</a>.</p>


<p>Referenced by <a href="#a7e7461606959f6bd3261825d77648e54">InferenceDescriptor</a>.</p>

</div>
</div>

### SetAttribute {#a08492ef05965dd1d0877068ec4e687c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;void(Function &amp;)&gt; anonymous{FunctionAttrs.cpp}::AttributeInferer::InferenceDescriptor::SetAttribute</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets the inferred attribute for this function.</p>

<p>Definition at line 1694 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp">FunctionAttrs.cpp</a>.</p>


<p>Referenced by <a href="#a7e7461606959f6bd3261825d77648e54">InferenceDescriptor</a>.</p>

</div>
</div>

### SkipFunction {#a20a121afceb526fe739e2d647a8b40fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;bool(const Function &amp;)&gt; anonymous{FunctionAttrs.cpp}::AttributeInferer::InferenceDescriptor::SkipFunction</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this function does not have to be handled.</p>


<p>General intent for this predicate is to provide an optimization for functions that do not need this attribute inference at all (say, for functions that already have the attribute).</p>


<p>Definition at line 1688 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp">FunctionAttrs.cpp</a>.</p>


<p>Referenced by <a href="#a7e7461606959f6bd3261825d77648e54">InferenceDescriptor</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp">FunctionAttrs.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
