---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/vfinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `VFInfo` Struct Reference

<p>Holds the <a href="/web-llvm/docs/api/structs/llvm/vfshape">VFShape</a> for a specific scalar to vector function mapping. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::VFInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">llvm/IR/VFABIDemangler.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b430434548d148d4fcab54003f5f57b">getParamIndexForOptionalMask</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Set Architecture. <a href="#a9b430434548d148d4fcab54003f5f57b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a7b7f899842cba56b84e670f7d48700">isMasked</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if at least one of the operands to the vectorized function has the kind 'GlobalPredicate'. <a href="#a7a7b7f899842cba56b84e670f7d48700">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/vfshape">VFShape</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9bb08bdbfc73cf77e85c835840baf10">Shape</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfb66d9c1a71777713734b160cc4f0b5">ScalarName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Classification of the vector function. <a href="#abfb66d9c1a71777713734b160cc4f0b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87c240df9a221a4e18326c7adc599629">VectorName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scalar <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> Name. <a href="#a87c240df9a221a4e18326c7adc599629">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#abe2c24a8dc2fb979e8e54e15f088169c">VFISAKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8ab6db11ae7c0891185e2a2a1f338d5">ISA</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vector <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> Name associated to this <a href="/web-llvm/docs/api/structs/llvm/vfinfo">VFInfo</a>. <a href="#aa8ab6db11ae7c0891185e2a2a1f338d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Holds the <a href="/web-llvm/docs/api/structs/llvm/vfshape">VFShape</a> for a specific scalar to vector function mapping.</p>

<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getParamIndexForOptionalMask() {#a9b430434548d148d4fcab54003f5f57b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; llvm::VFInfo::getParamIndexForOptionalMask ()</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Set Architecture.</p>


<p>Returns the index of the first parameter with the kind 'GlobalPredicate', if any exist.</p>


<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39adf3e3249ad10ccf5bf901eb83c105cc3">llvm::GlobalPredicate</a> and <a href="#ad9bb08bdbfc73cf77e85c835840baf10">Shape</a>.</p>


<p>Referenced by <a href="#a7a7b7f899842cba56b84e670f7d48700">isMasked</a>.</p>

</div>
</div>

### isMasked() {#a7a7b7f899842cba56b84e670f7d48700}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VFInfo::isMasked ()</td>
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

<p>Returns true if at least one of the operands to the vectorized function has the kind 'GlobalPredicate'.</p>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a>.</p>


<p>Reference <a href="#a9b430434548d148d4fcab54003f5f57b">getParamIndexForOptionalMask</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ISA {#aa8ab6db11ae7c0891185e2a2a1f338d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VFISAKind llvm::VFInfo::ISA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Vector <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> Name associated to this <a href="/web-llvm/docs/api/structs/llvm/vfinfo">VFInfo</a>.</p>

<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a>.</p>

</div>
</div>

### ScalarName {#abfb66d9c1a71777713734b160cc4f0b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::VFInfo::ScalarName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Classification of the vector function.</p>

<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a>.</p>

</div>
</div>

### Shape {#ad9bb08bdbfc73cf77e85c835840baf10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VFShape llvm::VFInfo::Shape</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a>.</p>


<p>Referenced by <a href="#a9b430434548d148d4fcab54003f5f57b">getParamIndexForOptionalMask</a>.</p>

</div>
</div>

### VectorName {#a87c240df9a221a4e18326c7adc599629}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::VFInfo::VectorName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scalar <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> Name.</p>

<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
