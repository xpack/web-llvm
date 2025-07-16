---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-builtingcs-cpp-/shadowstackgc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ShadowStackGC` Class Reference

<p>A GC strategy for uncooperative targets. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{BuiltinGCs.cpp}::ShadowStackGC { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcstrategy">GCStrategy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/gcstrategy">GCStrategy</a> describes a garbage collector algorithm's code generation requirements, and provides overridable hooks for those needs which cannot be abstractly described. <a href="/web-llvm/docs/api/classes/llvm/gcstrategy/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8025e65721f637e779cc6f8fdaa7a0fc">ShadowStackGC</a> ()=default</td>
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

<p>A GC strategy for uncooperative targets.</p>


<p>This implements lowering for the llvm.gc* intrinsics for targets that do not natively support them (which includes the C backend). Note that the code generated is not quite as efficient as algorithms which generate stack maps to identify roots.</p>


<p>In order to support this particular transformation, all stack roots are coallocated in the stack. This allows a fully target-independent stack map while introducing only minor runtime overhead.</p>


<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp">BuiltinGCs.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ShadowStackGC() {#a8025e65721f637e779cc6f8fdaa7a0fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{BuiltinGCs.cpp}::ShadowStackGC::ShadowStackGC ()</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp">BuiltinGCs.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp">BuiltinGCs.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
