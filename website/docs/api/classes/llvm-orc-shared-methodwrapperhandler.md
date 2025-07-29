---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/shared/methodwrapperhandler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MethodWrapperHandler` Class Template

<p>A function object that takes an <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> as its first argument, casts that address to a ClassT*, then calls the given method on that pointer passing in the remaining function arguments. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename RetT, typename ClassT, typename... ArgTs&gt;
class llvm::orc::shared::MethodWrapperHandler&lt;RetT, ClassT, ArgTs&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">llvm/ExecutionEngine/Orc/Shared/WrapperFunctionUtils.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename RetT, typename ClassT, typename... ArgTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a46899ff17b3ae88fa5833fd0d62ac166">MethodT</a> = RetT(ClassT::*)(ArgTs...)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename RetT, typename ClassT, typename... ArgTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a52554e4b248e2a8522054f070f002fa5">MethodWrapperHandler</a> (MethodT M)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename RetT, typename ClassT, typename... ArgTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a70ffbc1ac2af66528c7830838143d78e">operator()</a> (ExecutorAddr ObjAddr, ArgTs &amp;...Args)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename RetT, typename ClassT, typename... ArgTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a46899ff17b3ae88fa5833fd0d62ac166">MethodT</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a141ed788562cbab6e2b42a0f546247dd">M</a></td>
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

<p>A function object that takes an <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> as its first argument, casts that address to a ClassT*, then calls the given method on that pointer passing in the remaining function arguments.</p>


<p>This utility removes some of the boilerplate from writing wrappers for method calls.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">MyClass {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">public</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> myMethod(uint32_t, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">) { ... }</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">// SPS Method signature -- note MyClass object address as first argument.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight">SPSMyMethodWrapperSignature =</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  SPSTuple&lt;SPSExecutorAddr, uint32_t, bool&gt;;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">WrapperFunctionResult</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">myMethodCallWrapper(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *ArgData, </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> ArgSize) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> WrapperFunction&lt;SPSMyMethodWrapperSignature&gt;::handle(</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">     ArgData, ArgSize, <a href="/web-llvm/docs/api/namespaces/llvm/orc/shared/#a22daede26acd2cbd316d09f0c21e12dd">makeMethodWrapperHandler</a>(&amp;MyClass::myMethod));</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Definition at line 604 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">WrapperFunctionUtils.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### MethodT {#a46899ff17b3ae88fa5833fd0d62ac166}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename RetT, typename ClassT, typename... ArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::MethodWrapperHandler&lt; RetT, ClassT, ArgTs &gt;::MethodT =  RetT (ClassT::*)(ArgTs...)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">WrapperFunctionUtils.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MethodWrapperHandler() {#a52554e4b248e2a8522054f070f002fa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename RetT, typename ClassT, typename... ArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::shared::MethodWrapperHandler&lt; RetT, ClassT, ArgTs &gt;::MethodWrapperHandler (<a href="#a46899ff17b3ae88fa5833fd0d62ac166">MethodT</a> M)</td>
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



<p>Definition at line 607 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">WrapperFunctionUtils.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator()() {#a70ffbc1ac2af66528c7830838143d78e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename RetT, typename ClassT, typename... ArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetT llvm::orc::shared::MethodWrapperHandler&lt; RetT, ClassT, ArgTs &gt;::operator() (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> ObjAddr, ArgTs &amp;... Args)</td>
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



<p>Definition at line 608 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">WrapperFunctionUtils.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr/#af5df5d5fa49d180d3ca3de567f60de79">llvm::orc::ExecutorAddr::toPtr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### M {#a141ed788562cbab6e2b42a0f546247dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename RetT, typename ClassT, typename... ArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MethodT llvm::orc::shared::MethodWrapperHandler&lt; RetT, ClassT, ArgTs &gt;::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 613 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">WrapperFunctionUtils.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">WrapperFunctionUtils.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
